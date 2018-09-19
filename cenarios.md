---
layout: default
title: Cenários
category: Modelagem
---

# Cenários

------------
## Cenário de imprimir board

**Título:** Impressão de [board]() 

**Objetivo:** Passar algumas informações de à board para uma folha de papel.

**Contexto:**
- **Pré-condição:** O usuário deve ter acesso à board que quer imprimir.
- **Pós-condição:** A aplicação deverá comunicar ao browser que uma impressão está sendo solicitada.

**Atores:** Usuário

**Recursos:** Dispositivo desktop com browser compatível com os recursos do Trello e com acesso à impressora, além da impressora devidamente preparada para impressão.

**Episódios:**
- Usuário realiza [Login]();
- Usuário acessa a board desejada;
- Usuário abre o [Menu lateral]();
- Usuário seleciona a opção **Mais**;
- Usuário seleciona a opção **Imprimir e Exportar**;
- Usuário seleciona a opção **Imprimir...**;
- A aplicação converte a board para um formato imprimível;
- Browser faz a comunicação com o Sistema Operacional, que por sua vez comunica-se com a impressora.

--------------
## Cenário de adicionar Stickers

**Título:** Adição de [Stickers]()

**Objetivo:** Adição de elementos visuais que facilitem a orientação intuitiva e visual do usuário pela [board]().

**Contexto:**
- **Pré-condição:** O usuário deve ter acesso à board na qual quer adicionar stickers.
- **Pós-condição:** Um sticker deve ser adicionado a um card na board em questão.

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser em um dispositivo desktop.

**Episódios:**
- Usuário faz [Login]();
- Usuário acessa a board desejada;
- Usuário abre o [Menu Lateral]();
- Usuário seleciona a opção **Stickers**;
- Usuário clica e arrasta o Sticker desejado até o card desejado;

--------------
## Cenário de editar/remover Stickers

**Título:** Edição de [Stickers]()

**Objetivo:** Editar o estado atual de sticker previamente adicionado.

**Contexto:**
- **Pré-condição:** Deve existir um sticker em uma [board]() com o acesso do usuário que queira remover ou editar este mesmo sticker.
- **Pós-condição:** O sticker não mais estará onde está.

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- Usuário faz [Login]();
- Usuário acessa a board em questão;
- Usuário clica com o botão direito do mouse no [Card]() de onde quer mover o sticker;
- Usuário clica com o botão esquerdo do mouse no sticker que quer editar;
- Usuário seleciona uma das opções: **Girar**, **Mover** ou **Remover** segundo sua vontade;
- Em caso de **Girar** ou **Mover**, o usuário clica e segura com o botão esquerdo do mouse, movendo o cursos até que o sticker alcance a posição desejada;

--------------
## Cenário de Alterar Tela de Fundo

**Título:** Alteração da Tela de Fundo de uma [Board]()

**Objetivo:** Criação de uma identidade visual para a board em questão.

**Contexto:**
- **Pré-condição:** O usuário deve ter acesso à board a qual quer alterar o plano de fundo.
- **Pós-condição:** A tela de fundo dessa board será alterada.

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- Usuário faz [Login]();
- Usuário acessa a board cujo plano quer alterar;
- Usuário abre o [Menu Lateral]();
- Usuário seleciona a opção **Alterar Tela de Fundo**;
- Usuário seleciona entre as opções **Cores** ou **Fotos**;
    - Caso o board seja de um time [Business Class](), a opção **Personalizar** também estará disponível;
- Caso tenha selecionado **Cores**, o usuário escolhe uma entre as nove cores disponíveis, ou clica na **seta à esqueda** para voltar à tela anterior;
- Caso tenha selecionado **Fotos**, o usário escollhe uma entre as inúmeras fotos disponibilizadas pelo Unsplash em colaboração com o Trello ou clica na **seta à esqueda** para voltar à tela anterior;
    - É possível pesquisar por termos e a aplicação retornará imagens marcadas com os termos pesquisados.

--------------
## Cenário de Filtrar Cartões

**Título:** Pesquisa Filtrada de [Cards]()

**Objetivo:** Filtrar cards através de suas características.

**Contexto:**
- **Pré-condição:** O usuário está procurando por um ou mais cards que atendam às características pesquisadas em uma [board]() à qual o usuário tenha acesso.
- **Pós-condição:** Deverão aparecer na tela apenas os cards que atendam às características solicitadas na filtragem.

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- Usuário faz [Login]();
- Usuário acessa a board onde estão os cards que ele procura;
- Usuário abre o [Menu Lateral]() e seleciona a opção **Filtrar Cartões**;
    - Usuário pode digitar termos contidos nos títulos dos cards que está procurando;
    - Usuário pode selecionar [Etiquetas]() contidas nos cards que está procurando;
    - Usuário pode [membros]() assinalados nos cards que está procurando;
    - Usuário pode selecionar opções de [data de entrega]():
        - Entregas em um dia;
        - Entregas em uma semana;
        - Entregas emm um mês;
        - Em atraso;
        - Sem data de entrega;
        - Data de entrega marcada como concluída;
        - Não marcado como concluído;
    - Usuário pode selecionar se as buscas por etiquetas e membros seguem lógica AND (todos os membros e etiquetas procurados devem estar contido nos cards procurados) ou se seguem lógica OR (qualquer card que contenha um membro ou etiqueta procurados se enquadra na pesquisa).
- Aparece um texto na parte superior da board indicando que a busca está ativada e, por isso, alguns cards podem estar sendo omitidos;
    - Para encerrar a filtragem, o usuário pode clicar no X ao lado deste texto.

--------------
## Cenário de Copiar um Quadro

**Título:** Cópia de [Board]()

**Objetivo:** Criação de um board com algumas características iguais às de um board específico.

**Contexto:**
- **Pré-condição:** O usuário deve ter acesso à board que quer copiar.
- **Pós-condição:** Será criada uma nova board com algumas características trazidas de outra.

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- Usuário faz [Login]();
- Usuário acessa a board que quer copiar;
- Usuário abre o [Menu Lateral]() e seleciona a opção **Mais**;
- Usuário seleciona a opção **Copiar Quadro**;
- Usuário digita um título para o novo Board que será criado;
- Opcionalmente, o usuário escolhe um [time]() do qual faça parte para popular o novo quadro;
- Usuário decide a visibilidade do quadro (se é particular, de visibilidade apenas do time ou se é público);
- Usuário decide se quer copiar, também, os [Cards]() contidos no board atual.
- É criada uma nova board;
 
--------------
## Cenário de Seguir Quadro

**Título:** [Seguir]() uma [Board]()

**Objetivo:** Ser notificado de alterações que aconteçam em uma board

**Contexto:**
- **Pré-condição:** O usuário deve ter acesso à board que quer seguir.
- **Pós-condição:** O usuário será notificado de alterações que ocorrerem na board em questão.

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop ou acesso aplicação mobile conectada à internet.

**Episódios:**
- Usuário faz [Login]();
- Usuário acessa a board que quer seguir;
- Usuário abre o [Menu Lateral]() e seleciona a opção **Seguir**;
- O sistema passa a notificar o usuário em seu e-mail e no espaço de notificações do Trello;
- Aparece um texto no canto superior esquerdo da board indicando que o usuário está seguindo esta board.
- O usuário pode selecionar novamente a opção **Seguir** para parar de seguir, ou clicar no texto recém-aparecido que ascenderá um botão **Parar de seguir**.

--------------
## Cenário de Fechar um Quadro

**Título:** Fechamento de [Board]()

**Objetivo:** Enviar a board para um espaço equivalente à lixeira, onde não são imediatamente excluídos mas não mais dividem espaço com outras boards.

**Contexto:**
- **Pré-condição:** O usuário deve ser criador do board que quer fechar.
- **Pós-condição:** O board deve sair do espaço de boards do usuário, sem necessariamente ser excluído.

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- Usuário faz [Login]();
- Usuário acessa a board que deseja fechar;
- Usuário abre o [Menu Lateral]() e seleciona a opção **Mais**;
- Usuário seleciona a opção **Fechar Quadro...**;
- Usuário clica no botão vermelhor **Fechar**;

------------
## Cenário de Exportar um Quadro para JSON

**Título:** Exportação de [board]() para JSON 

**Objetivo:** Passar algumas informações de à board para o formato JSON.

**Contexto:**
- **Pré-condição:** O usuário deve ter acesso à board que quer exportar.
- **Pós-condição:** A aplicação deverá retornar um código JSON que reflita o atual estado da board.

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- Usuário realiza [Login]();
- Usuário acessa a board desejada;
- Usuário abre o [Menu lateral]();
- Usuário seleciona a opção **Mais**;
- Usuário seleciona a opção **Imprimir e Exportar**;
- Usuário seleciona a opção **Exportar como JSON**;
- A aplicação redireciona para uma página que contém apenas o código JSON da board;

------------
## Cenário de Retirar Membros de um Time

**Título:**
	Retirar membros de um time.
**Objetivo:**
	Retirar um membro de um time.
**Contexto:**
- **Pré-condição:** O usuário deve ser administrador do time e deve ter ao menos um membro além do administrador.
- **Pós-condição:** Usuário retirado deixará de ser membro do time.

**Atores:** Administrador do time, membro do time.

**Recursos:** Conta, time, membro, computador, internet.

**Exceção:** Não há time, não há outro membro.

**Episódios:**
- Administrador entra no Trello.
- Administrador REALIZA LOGIN.
- Se há time, Administrador ACESSA TIME.
- Senão, fluxo encerrado. (exceção)
- Administrador ACESSA LISTA DE MEMBROS.
- Se há membros, Administrador EXCLUI MEMBRO que deseja.
- Senão, fluxo encerrado. (exceção)


------------
## Cenário de Adicionar Descrição de Time

**Título:** Adicionar descrição de time.

**Objetivo:** Adicionar descrição de um time.

**Contexto:**
- **Pré-condição:** O usuário deve ter acesso aos recursos da plataforma.
- **Pós-condição:** Time deverá ser criado e possuir descrição.

**Atores:** Usuário.

**Recursos:** Conta, time, computador, internet.

**Restrição:** O usuário deve estar logado.

**Exceção:** Queda do sistema, falta de internet ou falta de energia.

**Episódios:**
- Usuário entra no Trello.
- Usuário REALIZA LOGIN.
- Se há time, Usuário ACESSA CRIAR UM TIME.
- Usuário ADICIONA NOME.
- Usuário ADICIONA DESCRIÇÃO do time.


------------
## Cenário de Editar Descrição de Time

**Título:** Editar descrição de time.

**Objetivo:** Editar descrição de um time.

**Contexto:**
- **Pré-condição:** O usuário deve ser administrador do time.
- **Pós-condição:** O time deverá possuir uma nova descrição.

**Atores:** Administrador do time.

**Recursos:** Conta, time, computador, internet.

**Restrição:** O time deve existir, o usuário deve ser administrador do time.

**Exceção:** Não há time.

**Episódios:**
- Administrador entra no Trello.
- Administrador REALIZA LOGIN.
- Se há time, Administrador ACESSA TIME.
- Senão, fluxo encerrado. (Exceção)
- Administrador ACESSA EDITAR PERFIL.
- Administrador EDITA DESCRIÇÃO do time.


------------
## Cenário de Editar Visibilidade do Time

**Título:** Editar visibilidade do time.

**Objetivo:** Editar visibilidade de um time.

**Contexto:**
- **Pré-condição:** O usuário deve ser administrador do time.
- **Pós-condição:** O time deverá ter sua visibilidade alterada.

**Atores:** Administrador do time.

**Recursos:** Conta, time, computador, internet.

**Exceção:** Não há time.

**Episódios:**
- Usuário entra no Trello.
- Usuário REALIZA LOGIN.
- Se há time, Usuário ACESSA TIME.
- Senão, fluxo encerrado.  (exceção)
- Usuário ACESSA CONFIGURAÇÕES DO TIME.
- Usuário ACESSA ALTERAR VISIBILIDADE DO TIME.
- Usuário EDITA VISIBILIDADE do time.


------------
## Cenário de Vincular de Time do Slack

**Título:** Vinculação de Time do Slack.

**Objetivo:** Vincular Time com o Slack.

**Contexto:**
- **Pré-condição:** O usuário deve ser administrador do time.
- **Pós-condição:** O time deverá ser vinculado a time do Slack.

**Atores:** Administrador do time.

**Recursos:** Conta, time, computador, internet.

**Restrição:** Administrador deve possuir conta e canal no slack.

**Exceção:** Não há time, não há conta nem canal no slack.

**Episódios:**
- Administrador entra no Trello.
- Administrador REALIZA LOGIN.
- Se há time, Administrador ACESSA TIME.
- Senão, Administrador CRIA TIME. (restrição)
- Administrador ACESSA CONFIGURAÇÕES DO TIME.
- Administrador ACESSA ADD TO SLACK.
- Se há conta no slack, Administrador REALIZA LOGIN em sua conta do slack.
- Senão Administrador cria conta no slack.
- Se há canal no slack do Administrador, Administrador VINCULA TIME COM O SLACK.
- Senão Administrador cria canal no slack e realiza o passo anterior.


------------
## Cenário de Permitir Membro Comentar em um Board 

**Título:** Permitir membro comentar em um board.

**Objetivo:** Permitir membro comentar em um board.

**Contexto:** 
- **Pré-condição:** O usuário deve ser administrador do time.
- **Pós-condição:** Membros poderão comentar em um board.

**Atores:** Administrador do time.

**Recursos:** Conta, time, board, lista, card, comentário, computador, internet.

**Episódios:**
- Administrador entra no Trello.
- Administrador REALIZA LOGIN.
- Se há time, Administrador ACESSA TIME.
- Senão, Administrador CRIA TIME. (restrição)
- Se há board, Administrador ACESSA BOARD do time.
- Senão, Administrador CRIA BOARD do time.
- Administrador ACESSA MENU da board.
- Administrador ACESSA MAIS OPÇÕES DO MENU.
- Administrador ACESSA CONFIGURAÇÕES.
- Administrador ACESSA PERMISSÕES PARA COMENTÁRIOS.
- Administrador SELECIONA MEMBROS.


------------
## Cenário de Negar Membro Ingressar em um Board 

**Título:** Negar membro ingressar em um board.

**Objetivo:** Negar membro ingressar em um board.

**Contexto:** 
- **Pré-condição:** O usuário deve ser administrador do time.
- **Pós-condição:** Membros não poderão ingressar em um Board sem serem convidados.

**Atores:** Administrador do time.

**Recursos:** Conta, time, computador, internet.

**Episódios:**
- Administrador entra no Trello.
- Administrador REALIZA LOGIN.
- Se há time, Administrador ACESSA TIME.
- Senão, Administrador CRIA TIME. (restrição)
- Se há board, Administrador ACESSA BOARD do time.
- Senão, Administrador CRIA BOARD do time. (restrição)
- Administrador ACESSA MENU da board.
- Administrador ACESSA MAIS OPÇÕES DO MENU.
- Administrador ACESSA CONFIGURAÇÕES.
- Se estiver ativo, Administrador CLICA EM PERMITIR INGRESSO DE MEMBROS DO TIME.
- Senão, a permissão já foi negada.

<!-- ----------------------
## Cenário de Fechar um Quadro

**Título:** Fechamento de Quadro

**Objetivo:**

**Contexto:**
- **Pré-condição:**
- **Pós-condição:**

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- Usuário faz [Login]();
- Usuário
------------------ -->