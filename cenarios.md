---
layout: default
title: Cenários
category: Modelagem
---

# Cenários

------------
## Cenário de imprimir Board

**Título:** Impressão de [Board]() 

**Objetivo:** Passar algumas informações de à Board para uma folha de papel.

**Contexto:**
- **Pré-condição:** O Usuário deve ter acesso à Board que quer imprimir.
- **Pós-condição:** A aplicação deverá comunicar ao browser que uma impressão está sendo solicitada.

**Atores:** Usuário

**Recursos:** Dispositivo desktop com browser compatível com os recursos do Trello e com acesso à impressora, além da impressora devidamente preparada para impressão.

**Episódios:**
- Usuário realiza [Login]();
- Usuário acessa a Board desejada;
- Usuário abre o [Menu lateral]();
- Usuário seleciona a opção **Mais**;
- Usuário seleciona a opção **Imprimir e Exportar**;
- Usuário seleciona a opção **Imprimir...**;
- A aplicação converte a Board para um formato imprimível;
- Browser faz a comunicação com o Sistema Operacional, que por sua vez comunica-se com a impressora.

--------------
## Cenário de adicionar Stickers

**Título:** Adição de [Stickers]()

**Objetivo:** Adição de elementos visuais que facilitem a orientação intuitiva e visual do Usuário pela [Board]().

**Contexto:**
- **Pré-condição:** O Usuário deve ter acesso à Board na qual quer adicionar stickers.
- **Pós-condição:** Um sticker deve ser adicionado a um Card na Board em questão.

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser em um dispositivo desktop.

**Episódios:**
- Usuário faz [Login]();
- Usuário acessa a Board desejada;
- Usuário abre o [Menu Lateral]();
- Usuário seleciona a opção **Stickers**;
- Usuário clica e arrasta o Sticker desejado até o Card desejado;

--------------
## Cenário de editar/remover Stickers

**Título:** Edição de [Stickers]()

**Objetivo:** Editar o estado atual de sticker previamente adicionado.

**Contexto:**
- **Pré-condição:** Deve existir um sticker em uma [Board]() com o acesso do Usuário que queira remover ou editar este mesmo sticker.
- **Pós-condição:** O sticker não mais estará onde está.

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- Usuário faz [Login]();
- Usuário acessa a Board em questão;
- Usuário clica com o botão direito do mouse no [Card]() de onde quer mover o sticker;
- Usuário clica com o botão esquerdo do mouse no sticker que quer editar;
- Usuário seleciona uma das opções: **Girar**, **Mover** ou **Remover** segundo sua vontade;
- Em caso de **Girar** ou **Mover**, o Usuário clica e segura com o botão esquerdo do mouse, movendo o cursos até que o sticker alcance a posição desejada;

--------------
## Cenário de Alterar Tela de Fundo

**Título:** Alteração da Tela de Fundo de uma [Board]()

**Objetivo:** Criação de uma identidade visual para a Board em questão.

**Contexto:**
- **Pré-condição:** O Usuário deve ter acesso à Board a qual quer alterar o plano de fundo.
- **Pós-condição:** A tela de fundo dessa Board será alterada.

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- Usuário faz [Login]();
- Usuário acessa a Board cujo plano quer alterar;
- Usuário abre o [Menu Lateral]();
- Usuário seleciona a opção **Alterar Tela de Fundo**;
- Usuário seleciona entre as opções **Cores** ou **Fotos**;
    - Caso o Board seja de um time [Business Class](), a opção **Personalizar** também estará disponível;
- Caso tenha selecionado **Cores**, o Usuário escolhe uma entre as nove cores disponíveis, ou clica na **seta à esqueda** para voltar à tela anterior;
- Caso tenha selecionado **Fotos**, o usário escollhe uma entre as inúmeras fotos disponibilizadas pelo Unsplash em colaboração com o Trello ou clica na **seta à esqueda** para voltar à tela anterior;
    - É possível pesquisar por termos e a aplicação retornará imagens marcadas com os termos pesquisados.

--------------
## Cenário de Filtrar Cartões

**Título:** Pesquisa Filtrada de [Cards]()

**Objetivo:** Filtrar cards através de suas características.

**Contexto:**
- **Pré-condição:** O Usuário está procurando por um ou mais cards que atendam às características pesquisadas em uma [Board]() à qual o Usuário tenha acesso.
- **Pós-condição:** Deverão aparecer na tela apenas os cards que atendam às características solicitadas na filtragem.

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- Usuário faz [Login]();
- Usuário acessa a Board onde estão os cards que ele procura;
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
    - Usuário pode selecionar se as buscas por etiquetas e membros seguem lógica AND (todos os membros e etiquetas procurados devem estar contido nos cards procurados) ou se seguem lógica OR (qualquer Card que contenha um membro ou etiqueta procurados se enquadra na pesquisa).
- Aparece um texto na parte superior da Board indicando que a busca está ativada e, por isso, alguns cards podem estar sendo omitidos;
    - Para encerrar a filtragem, o Usuário pode clicar no X ao lado deste texto.

--------------
## Cenário de Copiar um Quadro

**Título:** Cópia de [Board]()

**Objetivo:** Criação de um Board com algumas características iguais às de um Board específico.

**Contexto:**
- **Pré-condição:** O Usuário deve ter acesso à Board que quer copiar.
- **Pós-condição:** Será criada uma nova Board com algumas características trazidas de outra.

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- Usuário faz [Login]();
- Usuário acessa a Board que quer copiar;
- Usuário abre o [Menu Lateral]() e seleciona a opção **Mais**;
- Usuário seleciona a opção **Copiar Quadro**;
- Usuário digita um título para o novo Board que será criado;
- Opcionalmente, o Usuário escolhe um [time]() do qual faça parte para popular o novo quadro;
- Usuário decide a visibilidade do quadro (se é particular, de visibilidade apenas do time ou se é público);
- Usuário decide se quer copiar, também, os [Cards]() contidos no Board atual.
- É criada uma nova Board;
 
--------------
## Cenário de Seguir Quadro

**Título:** [Seguir]() uma [Board]()

**Objetivo:** Ser notificado de alterações que aconteçam em uma Board

**Contexto:**
- **Pré-condição:** O Usuário deve ter acesso à Board que quer seguir.
- **Pós-condição:** O Usuário será notificado de alterações que ocorrerem na Board em questão.

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop ou acesso aplicação mobile conectada à internet.

**Episódios:**
- Usuário faz [Login]();
- Usuário acessa a Board que quer seguir;
- Usuário abre o [Menu Lateral]() e seleciona a opção **Seguir**;
- O sistema passa a notificar o Usuário em seu e-mail e no espaço de notificações do Trello;
- Aparece um texto no canto superior esquerdo da Board indicando que o Usuário está seguindo esta Board.
- O Usuário pode selecionar novamente a opção **Seguir** para parar de seguir, ou clicar no texto recém-aparecido que ascenderá um botão **Parar de seguir**.

--------------
## Cenário de Fechar um Quadro

**Título:** Fechamento de [Board]()

**Objetivo:** Enviar a Board para um espaço equivalente à lixeira, onde não são imediatamente excluídos mas não mais dividem espaço com outras Boards.

**Contexto:**
- **Pré-condição:** O Usuário deve ser criador do Board que quer fechar.
- **Pós-condição:** O Board deve sair do espaço de Boards do Usuário, sem necessariamente ser excluído.

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- Usuário faz [Login]();
- Usuário acessa a Board que deseja fechar;
- Usuário abre o [Menu Lateral]() e seleciona a opção **Mais**;
- Usuário seleciona a opção **Fechar Quadro...**;
- Usuário clica no botão vermelhor **Fechar**;

------------
## Cenário de Exportar um Quadro para JSON

**Título:** Exportação de [Board]() para JSON 

**Objetivo:** Passar algumas informações de à Board para o formato JSON.

**Contexto:**
- **Pré-condição:** O Usuário deve ter acesso à Board que quer exportar.
- **Pós-condição:** A aplicação deverá retornar um código JSON que reflita o atual estado da Board.

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- Usuário realiza [Login]();
- Usuário acessa a Board desejada;
- Usuário abre o [Menu lateral]();
- Usuário seleciona a opção **Mais**;
- Usuário seleciona a opção **Imprimir e Exportar**;
- Usuário seleciona a opção **Exportar como JSON**;
- A aplicação redireciona para uma página que contém apenas o código JSON da Board;

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
## Cenário de Ver List

**Título:** Ver [List]() 

**Objetivo:** Mostrar o conteúdo de uma [List]() para o [Usuário]().

**Contexto:**
- **Pré-condição:** O [Usuário]() deve ter acesso à [List]() que quer visualizar.
- **Pós-condição:** A aplicação deverá mostrar a [List]() para o [Usuário]().

**Atores:** [Usuário]()

**Restrições** 

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() realiza [LOGIN]();
- Se não há [Board](), [Usuário]() realiza [CRIAR BOARD]();
- [Usuário]() realiza [VER BOARD]();
- Se não há [List](), [Usuário]() realiza [CRIAR LISTA]();
- [Usuário]() realiza [VER LIST]();
- A aplicação mostra a [List]() desejada para o [Usuário]().


------------
# Cards

## Cenário de Criar Card

**Título:** Criar [Card]() 

**Objetivo:** Criar um novo [Card]() para armazenar dados dentro de uma [List]().

**Contexto:**
- **Pré-condição:** O [Usuário]() deve ter acesso à [List]() onde quer criar o [Card]().
- **Pós-condição:** A aplicação deverá criar o [Card]() dentro da [List]() para o [Usuário]().

**Atores:** [Usuário]()

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() realiza [LOGIN]();
- Se não há [Board](), [Usuário]() realiza [CRIAR BOARD]();
- [Usuário]() realiza [VER BOARD]();
- Se não há [List](), [Usuário]() realiza [CRIAR LISTA]();
- [Usuário]() realiza [VER LISTA]();
- [Usuário]() realiza [CRIAR CARD]()
- A aplicação mostra a [Lista]() desejada para o [Usuário]().

------------
## Cenário de Modificar Card

**Título:** Modificar [Card]() 

**Objetivo:** Modificar um [Card]() existente para atualizar os seus dados dentro de uma [List]().

**Contexto:**
- **Pré-condição:** O [Usuário]() deve ter acesso à [List]() onde está o [Card]().
- **Pós-condição:** A aplicação deverá atualizar o [Card]() com os novos dados.

**Atores:** [Usuário]()

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() realiza [LOGIN]();
- Se não há [Board](), [Usuário]() realiza [CRIAR BOARD]();
- [Usuário]() realiza [VER BOARD]();
- Se não há [List](), [Usuário]() realiza [CRIAR LISTA]();
- [Usuário]() realiza [VER LISTA]();
- Se não há [Card](), [Usuário](), realiza [CRIAR CARD]();
- [Usuário]() realiza [VER CARD]();
- [Usuário]() realiza [MODIFICAR CARD]();
- A aplicação mostra uma janela de edição para o [Card]() desejado para o [Usuário]().

------------
## Cenário de Ver Card

**Título:** Ver [Card]() 

**Objetivo:** Visualizar um [Card]() existente para mostrar o seu conteúdo para o [Usuário]().

**Contexto:**
- **Pré-condição:** O [Usuário]() deve ter acesso à [List]() onde está o [Card]().
- **Pós-condição:** A aplicação deverá mostrar o [Card]() com seu conteúdo.

**Atores:** [Usuário]()

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() realiza [LOGIN]();
- Se não há [Board](), [Usuário]() realiza [CRIAR BOARD]();
- [Usuário]() realiza [VER BOARD]();
- Se não há [List](), [Usuário]() realiza [CRIAR LISTA]();
- [Usuário]() realiza [VER LISTA]();
- Se não há [Card](), [Usuário](), realiza [CRIAR CARD]();
- [Usuário]() realiza [VER CARD]();
- A aplicação mostra uma janela com os dados do [Card]() desejado para o [Usuário]().

------------
## Cenário de Modificar Card

**Título:** Modificar [Card]() 

**Objetivo:** Modificar um [Card]() existente para atualizar os seus dados dentro de uma [List]().

**Contexto:**
- **Pré-condição:** O [Usuário]() deve ter acesso à [List]() onde está o [Card]().
- **Pós-condição:** A aplicação deverá atualizar o [Card]() com os novos dados.

**Atores:** [Usuário]()

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() realiza [LOGIN]();
- Se não há [Board](), [Usuário]() realiza [CRIAR BOARD]();
- [Usuário]() realiza [VER BOARD]();
- Se não há [List](), [Usuário]() realiza [CRIAR LISTA]();
- [Usuário]() realiza [VER LISTA]();
- Se não há [Card](), [Usuário](), realiza [CRIAR CARD]();
- [Usuário]() realiza [VER CARD]();
- [Usuário]() realiza [MODIFICAR CARD]();
- A aplicação mostra uma janela de edição para o [Card]() desejado para o [Usuário]().

------------
## Cenário de Modificar Card

**Título:** Modificar [Card]() 

**Objetivo:** Modificar um [Card]() existente para atualizar os seus dados dentro de uma [List]().

**Contexto:**
- **Pré-condição:** O [Usuário]() deve ter acesso à [List]() onde está o [Card]().
- **Pós-condição:** A aplicação deverá atualizar o [Card]() com os novos dados.

**Atores:** [Usuário]()

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() realiza [LOGIN]();
- Se não há [Board](), [Usuário]() realiza [CRIAR BOARD]();
- [Usuário]() realiza [VER BOARD]();
- Se não há [List](), [Usuário]() realiza [CRIAR LISTA]();
- [Usuário]() realiza [VER LISTA]();
- Se não há [Card](), [Usuário](), realiza [CRIAR CARD]();
- [Usuário]() realiza [VER CARD]();
- [Usuário]() realiza [MODIFICAR CARD]();
- A aplicação mostra uma janela de edição para o [Card]() desejado para o [Usuário]().

------------
## Cenário de Seguir Card

**Título:** Seguir [Card]() 

**Objetivo:** Seguir um [Card]() existente para ser notificado de mudanças por meios de notificações para o [Usuário]().

**Contexto:**
- **Pré-condição:** O [Usuário]() deve ter acesso à [List]() onde está o [Card]().
- **Pós-condição:** A aplicação deverá notificar o [usuáro]() quando o [Card]() for modificado.

**Atores:** [Usuário]()

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() realiza [LOGIN]();
- Se não há [Board](), [Usuário]() realiza [CRIAR BOARD]();
- [Usuário]() realiza [VER BOARD]();
- Se não há [List](), [Usuário]() realiza [CRIAR LISTA]();
- [Usuário]() realiza [VER LISTA]();
- Se não há [Card](), [Usuário](), realiza [CRIAR CARD]();
- [Usuário]() realiza [VER CARD]();
- [Usuário]() realiza [SEGUIR CARD]() pressionando o botão seguir;
- A aplicação retorna à tela de [VER CARD]().

------------
## Cenário de Arquivar Card

**Título:** Arquivar [Card]() 

**Objetivo:** Arquivar um [Card]() existente para removê-lo de uma [List]() sem perder seus dados.

**Contexto:**
- **Pré-condição:** O [Usuário]() deve ter acesso à [List]() onde está o [Card]().
- **Pós-condição:** A aplicação deverá arquivar o [Card]() selecionado.

**Atores:** [Usuário]()

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() realiza [LOGIN]();
- Se não há [Board](), [Usuário]() realiza [CRIAR BOARD]();
- [Usuário]() realiza [VER BOARD]();
- Se não há [List](), [Usuário]() realiza [CRIAR LISTA]();
- [Usuário]() realiza [VER LISTA]();
- Se não há [Card](), [Usuário](), realiza [CRIAR CARD]();
- [Usuário]() realiza [VER CARD]();
- [Usuário]() realiza [ARQUIVAR CARD]() pressionando o botão arquivar;
- A aplicação retorna à tela de [VER LISTA]().

------------
## Cenário de Personalizar Label

**Título:** Personalizar [Label]() 

**Objetivo:** Personalizar a [Label]() atribuído à um Card para diferenciar ou destacá-lo em relação aos outros.

**Contexto:**
- **Pré-condição:** O [Usuário]() deve ter acesso à [List]() onde está o [Card]().
- **Pós-condição:** A aplicação deverá mostrar o [Card]() com seu novo [Label]().

**Atores:** [Usuário]()

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() realiza [LOGIN]();
- Se não há [Board](), [Usuário]() realiza [CRIAR BOARD]();
- [Usuário]() realiza [VER BOARD]();
- Se não há [List](), [Usuário]() realiza [CRIAR LISTA]();
- [Usuário]() realiza [VER LISTA]();
- Se não há [Card](), [Usuário](), realiza [CRIAR CARD]();
- [Usuário]() realiza [VER CARD]();
- [Usuário]() realiza [PERSONALIZAR Label]();
- A aplicação mostra uma janela com opções de persnoalização para o [Label]() para o [Usuário]().

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