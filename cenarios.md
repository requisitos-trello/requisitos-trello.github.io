---
layout: default
title: Cenários
category: Modelagem
---

# Cenários

------------
## Cenário de imprimir [Board]()

**Título:** Impressão de [Board]() 

**Objetivo:** Passar algumas informações de à [Board]() para uma folha de papel.

**Contexto:**
- **Pré-condição:** O Usuário deve ter acesso à [Board]() que quer imprimir.
- **Pós-condição:** A aplicação deverá comunicar ao browser que uma impressão está sendo solicitada.

**Atores:** Usuário

**Recursos:** Dispositivo desktop com browser compatível com os recursos do Trello e com acesso à impressora, além da impressora devidamente preparada para impressão.

**Episódios:**
- Usuário realiza [Login]();
- Usuário acessa a [Board]() desejada;
- Usuário abre o [Menu lateral]();
- Usuário seleciona a opção **Mais**;
- Usuário seleciona a opção **Imprimir e Exportar**;
- Usuário seleciona a opção **Imprimir...**;
- A aplicação converte a [Board]() para um formato imprimível;
- Browser faz a comunicação com o Sistema Operacional, que por sua vez comunica-se com a impressora.

--------------
## Cenário de adicionar [Stickers](lexicos.html#sticker)

**Título:** Adição de [Stickers](lexicos.html#sticker)

**Objetivo:** Adição de elementos visuais que facilitem a orientação intuitiva e visual do Usuário pela [Board]().

**Contexto:**
- **Pré-condição:** O Usuário deve ter acesso à [Board]() na qual quer adicionar [stickers](lexicos.html#sticker).
- **Pós-condição:** Um [sticker](lexicos.html#sticker) deve ser adicionado a um Card na [Board]() em questão.

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser em um dispositivo desktop.

**Episódios:**
- Usuário faz [Login]();
- Usuário acessa a [Board]() desejada;
- Usuário abre o [Menu Lateral]();
- Usuário seleciona a opção **[Stickers](lexicos.html#sticker)**;
- Usuário clica e arrasta o Sticker desejado até o Card desejado;

--------------
## Cenário de editar/remover [Stickers](lexicos.html#sticker)

**Título:** Edição de [Stickers](lexicos.html#sticker)

**Objetivo:** Editar o estado atual de [sticker](lexicos.html#sticker) previamente adicionado.

**Contexto:**
- **Pré-condição:** Deve existir um [sticker](lexicos.html#sticker) em uma [Board]() com o acesso do Usuário que queira remover ou editar este mesmo [sticker](lexicos.html#sticker).
- **Pós-condição:** O [sticker](lexicos.html#sticker) não mais estará onde está.

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- Usuário faz [Login]();
- Usuário acessa a [Board]() em questão;
- Usuário clica com o botão direito do mouse no [Card]() de onde quer mover o [sticker](lexicos.html#sticker);
- Usuário clica com o botão esquerdo do mouse no [sticker](lexicos.html#sticker) que quer editar;
- Usuário seleciona uma das opções: **Girar**, **Mover** ou **Remover** segundo sua vontade;
- Em caso de **Girar** ou **Mover**, o Usuário clica e segura com o botão esquerdo do mouse, movendo o cursos até que o [sticker](lexicos.html#sticker) alcance a posição desejada;

--------------
## Cenário de Alterar Tela de Fundo

**Título:** Alteração da Tela de Fundo de uma [Board]()

**Objetivo:** Criação de uma identidade visual para a [Board]() em questão.

**Contexto:**
- **Pré-condição:** O Usuário deve ter acesso à [Board]() a qual quer alterar o plano de fundo.
- **Pós-condição:** A tela de fundo dessa [Board]() será alterada.

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- Usuário faz [Login]();
- Usuário acessa a [Board]() cujo plano quer alterar;
- Usuário abre o [Menu Lateral]();
- Usuário seleciona a opção **Alterar Tela de Fundo**;
- Usuário seleciona entre as opções **Cores** ou **Fotos**;
    - Caso o [Board]() seja de um [time](lexicos.html#time) [Business Class](), a opção **Personalizar** também estará disponível;
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
- Usuário acessa a [Board]() onde estão os cards que ele procura;
- Usuário abre o [Menu Lateral]() e seleciona a opção **Filtrar Cartões**;
    - Usuário pode digitar termos contidos nos títulos dos cards que está procurando;
    - Usuário pode selecionar [Etiquetas]() contidas nos cards que está procurando;
    - Usuário pode [membros]() assinalados nos cards que está procurando;
    - Usuário pode selecionar opções de [data de entrega](lexico.html#duedate):
        - Entregas em um dia;
        - Entregas em uma semana;
        - Entregas emm um mês;
        - Em atraso;
        - Sem [data de entrega](lexico.html#duedate);
        - [Data de entrega](lexico.html#duedate) marcada como concluída;
        - Não marcado como concluído;
    - Usuário pode selecionar se as buscas por etiquetas e membros seguem lógica AND (todos os membros e etiquetas procurados devem estar contido nos cards procurados) ou se seguem lógica OR (qualquer Card que contenha um membro ou etiqueta procurados se enquadra na pesquisa).
- Aparece um texto na parte superior da [Board]() indicando que a busca está ativada e, por isso, alguns cards podem estar sendo omitidos;
    - Para encerrar a filtragem, o Usuário pode clicar no X ao lado deste texto.

--------------
## Cenário de [Copiar](lexico.html#copiar) um Quadro

**Título:** Cópia de [Board]()

**Objetivo:** Criação de um [Board]() com algumas características iguais às de um [Board]() específico.

**Contexto:**
- **Pré-condição:** O Usuário deve ter acesso à [Board]() que quer [copiar](lexico.html#copiar).
- **Pós-condição:** Será criada uma nova [Board]() com algumas características trazidas de outra.

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- Usuário faz [Login]();
- Usuário acessa a [Board]() que quer [copiar](lexico.html#copiar);
- Usuário abre o [Menu Lateral]() e seleciona a opção **Mais**;
- Usuário seleciona a opção **Copiar Quadro**;
- Usuário digita um título para o novo [Board]() que será criado;
- Opcionalmente, o Usuário escolhe um [time](lexicos.html#time) do qual faça parte para popular o novo quadro;
- Usuário decide a visibilidade do quadro (se é particular, de visibilidade apenas do [time](lexicos.html#time) ou se é público);
- Usuário decide se quer [copiar](lexico.html#copiar), também, os [Cards]() contidos no [Board]() atual.
- É criada uma nova [Board]();
 
--------------
## Cenário de Seguir Quadro

**Título:** [Seguir]() uma [Board]()

**Objetivo:** Ser [notificado](lexico.html#notificar) de alterações que aconteçam em uma [Board]()

**Contexto:**
- **Pré-condição:** O Usuário deve ter acesso à [Board]() que quer seguir.
- **Pós-condição:** O Usuário será [notificado](lexico.html#notificar) de alterações que ocorrerem na [Board]() em questão.

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop ou acesso aplicação mobile conectada à internet.

**Episódios:**
- Usuário faz [Login]();
- Usuário acessa a [Board]() que quer seguir;
- Usuário abre o [Menu Lateral]() e seleciona a opção **Seguir**;
- O sistema passa a [notificar](lexico.html#notificar) o Usuário em seu e-mail e no espaço de [notificações](lexico.html#notificar) do Trello;
- Aparece um texto no canto superior esquerdo da [Board]() indicando que o Usuário está seguindo esta [Board]().
- O Usuário pode selecionar novamente a opção **Seguir** para parar de seguir, ou clicar no texto recém-aparecido que ascenderá um botão **Parar de seguir**.

--------------
## Cenário de Fechar um Quadro

**Título:** Fechamento de [Board]()

**Objetivo:** Enviar a [Board]() para um espaço equivalente à lixeira, onde não são imediatamente excluídos mas não mais dividem espaço com outras Boards.

**Contexto:**
- **Pré-condição:** O Usuário deve ser criador do [Board]() que quer fechar.
- **Pós-condição:** O [Board]() deve sair do espaço de Boards do Usuário, sem necessariamente ser excluído.

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- Usuário faz [Login]();
- Usuário acessa a [Board]() que deseja fechar;
- Usuário abre o [Menu Lateral]() e seleciona a opção **Mais**;
- Usuário seleciona a opção **Fechar Quadro...**;
- Usuário clica no botão vermelhor **Fechar**;

------------
## Cenário de Exportar um Quadro para JSON

**Título:** Exportação de [Board]() para JSON 

**Objetivo:** Passar algumas informações de à [Board]() para o formato JSON.

**Contexto:**
- **Pré-condição:** O Usuário deve ter acesso à [Board]() que quer exportar.
- **Pós-condição:** A aplicação deverá retornar um código JSON que reflita o atual estado da [Board]().

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- Usuário realiza [Login]();
- Usuário acessa a [Board]() desejada;
- Usuário abre o [Menu lateral]();
- Usuário seleciona a opção **Mais**;
- Usuário seleciona a opção **Imprimir e Exportar**;
- Usuário seleciona a opção **Exportar como JSON**;
- A aplicação redireciona para uma página que contém apenas o código JSON da [Board]();

------------
## Cenário de Retirar Membros de um [Time](lexicos.html#time)

**Título:**
	Retirar membros de um [time](lexicos.html#time).
**Objetivo:**
	Retirar um membro de um [time](lexicos.html#time).
**Contexto:**
- **Pré-condição:** O usuário deve ser [administrador](lexicos.html#administrador) do [Time](lexicos.html#time) e deve ter ao menos um membro além do [administrador](lexicos.html#administrador).
- **Pós-condição:** Usuário retirado deixará de ser membro do [time](lexicos.html#time).

**Atores:** [Administrador](lexicos.html#administrador) do [time](lexicos.html#time), membro do [time](lexicos.html#time).

**Recursos:** Conta, [time](lexicos.html#time), membro, computador, internet.

**Exceção:** Não há [time](lexicos.html#time), não há outro membro.

**Episódios:**
- [Administrador](lexicos.html#administrador) entra no Trello.
- [Administrador](lexicos.html#administrador) REALIZA LOGIN.
- Se há [time](lexicos.html#time), [Administrador](lexicos.html#administrador) ACESSA TIME.
- Senão, fluxo encerrado. (exceção)
- [Administrador](lexicos.html#administrador) ACESSA LISTA DE MEMBROS.
- Se há membros, [Administrador](lexicos.html#administrador) EXCLUI MEMBRO que deseja.
- Senão, fluxo encerrado. (exceção)


------------
## Cenário de Adicionar Descrição de [Time](lexicos.html#time)

**Título:** Adicionar descrição de [time](lexicos.html#time).

**Objetivo:** Adicionar descrição de um [time](lexicos.html#time).

**Contexto:**
- **Pré-condição:** O usuário deve ter acesso aos recursos da plataforma.
- **Pós-condição:** [Time](lexicos.html#time) deverá ser criado e possuir descrição.

**Atores:** Usuário.

**Recursos:** Conta, [time](lexicos.html#time), computador, internet.

**Restrição:** O usuário deve estar logado.

**Exceção:** Queda do sistema, falta de internet ou falta de energia.

**Episódios:**
- Usuário entra no Trello.
- Usuário REALIZA LOGIN.
- Se há [time](lexicos.html#time), Usuário ACESSA CRIAR UM TIME.
- Usuário ADICIONA NOME.
- Usuário ADICIONA DESCRIÇÃO do [time](lexicos.html#time).


------------
## Cenário de Editar Descrição de [Time](lexicos.html#time)

**Título:** Editar descrição de [time](lexicos.html#time).

**Objetivo:** Editar descrição de um [time](lexicos.html#time).

**Contexto:**
- **Pré-condição:** O usuário deve ser [administrador](lexicos.html#administrador) do [time](lexicos.html#time).
- **Pós-condição:** O [time](lexicos.html#time) deverá possuir uma nova descrição.

**Atores:** [Administrador](lexicos.html#administrador) do [time](lexicos.html#time).

**Recursos:** Conta, [time](lexicos.html#time), computador, internet.

**Restrição:** O [time](lexicos.html#time) deve existir, o usuário deve ser [administrador](lexicos.html#administrador) do [time](lexicos.html#time).

**Exceção:** Não há [time](lexicos.html#time).

**Episódios:**
- [Administrador](lexicos.html#administrador) entra no Trello.
- [Administrador](lexicos.html#administrador) REALIZA LOGIN.
- Se há [time](lexicos.html#time), [Administrador](lexicos.html#administrador) ACESSA TIME.
- Senão, fluxo encerrado. (Exceção)
- [Administrador](lexicos.html#administrador) ACESSA EDITAR PERFIL.
- [Administrador](lexicos.html#administrador) EDITA DESCRIÇÃO do [time](lexicos.html#time).


------------
## Cenário de Editar Visibilidade do [Time](lexicos.html#time)

**Título:** Editar visibilidade do [time](lexicos.html#time).

**Objetivo:** Editar visibilidade de um [time](lexicos.html#time).

**Contexto:**
- **Pré-condição:** O usuário deve ser [administrador](lexicos.html#administrador) do [time](lexicos.html#time).
- **Pós-condição:** O [time](lexicos.html#time) deverá ter sua visibilidade alterada.

**Atores:** [Administrador](lexicos.html#administrador) do [time](lexicos.html#time).

**Recursos:** Conta, [time](lexicos.html#time), computador, internet.

**Exceção:** Não há [time](lexicos.html#time).

**Episódios:**
- Usuário entra no Trello.
- Usuário REALIZA LOGIN.
- Se há [time](lexicos.html#time), Usuário ACESSA TIME.
- Senão, fluxo encerrado.  (exceção)
- Usuário ACESSA CONFIGURAÇÕES DO TIME.
- Usuário ACESSA ALTERAR VISIBILIDADE DO TIME.
- Usuário EDITA VISIBILIDADE do [time](lexicos.html#time).


------------
## Cenário de Vincular de [Time](lexicos.html#time) do Slack

**Título:** Vinculação de [Time](lexicos.html#time) do Slack.

**Objetivo:** Vincular [Time](lexicos.html#time) com o Slack.

**Contexto:**
- **Pré-condição:** O usuário deve ser [administrador](lexicos.html#administrador) do [time](lexicos.html#time).
- **Pós-condição:** O [time](lexicos.html#time) deverá ser vinculado a [time](lexicos.html#time) do Slack.

**Atores:** [Administrador](lexicos.html#administrador) do [time](lexicos.html#time).

**Recursos:** Conta, [time](lexicos.html#time), computador, internet.

**Restrição:** [Administrador](lexicos.html#administrador) deve possuir conta e canal no slack.

**Exceção:** Não há [time](lexicos.html#time), não há conta nem canal no slack.

**Episódios:**
- [Administrador](lexicos.html#administrador) entra no Trello.
- [Administrador](lexicos.html#administrador) REALIZA LOGIN.
- Se há [time](lexicos.html#time), [Administrador](lexicos.html#administrador) ACESSA TIME.
- Senão, [Administrador](lexicos.html#administrador) CRIA TIME. (restrição)
- [Administrador](lexicos.html#administrador) ACESSA CONFIGURAÇÕES DO TIME.
- [Administrador](lexicos.html#administrador) ACESSA ADD TO SLACK.
- Se há conta no slack, [Administrador](lexicos.html#administrador) REALIZA LOGIN em sua conta do slack.
- Senão [Administrador](lexicos.html#administrador) cria conta no slack.
- Se há canal no slack do [Administrador](lexicos.html#administrador), [Administrador](lexicos.html#administrador) VINCULA TIME COM O SLACK.
- Senão [Administrador](lexicos.html#administrador) cria canal no slack e realiza o passo anterior.


------------
## Cenário de Permitir Membro Comentar em um [Board]() 

**Título:** Permitir membro comentar em um [board]().

**Objetivo:** Permitir membro comentar em um [board]().

**Contexto:** 
- **Pré-condição:** O usuário deve ser [administrador](lexicos.html#administrador) do [time](lexicos.html#time).
- **Pós-condição:** Membros poderão comentar em um [board]().

**Atores:** [Administrador](lexicos.html#administrador) do [time](lexicos.html#time).

**Recursos:** Conta, [time](lexicos.html#time), [board](), lista, card, comentário, computador, internet.

**Episódios:**
- [Administrador](lexicos.html#administrador) entra no Trello.
- [Administrador](lexicos.html#administrador) REALIZA LOGIN.
- Se há [time](lexicos.html#time), [Administrador](lexicos.html#administrador) ACESSA TIME.
- Senão, [Administrador](lexicos.html#administrador) CRIA TIME. (restrição)
- Se há [board](), [Administrador](lexicos.html#administrador) ACESSA BOARD do [time](lexicos.html#time).
- Senão, [Administrador](lexicos.html#administrador) CRIA BOARD do [time](lexicos.html#time).
- [Administrador](lexicos.html#administrador) ACESSA MENU da [board]().
- [Administrador](lexicos.html#administrador) ACESSA MAIS OPÇÕES DO MENU.
- [Administrador](lexicos.html#administrador) ACESSA CONFIGURAÇÕES.
- [Administrador](lexicos.html#administrador) ACESSA PERMISSÕES PARA COMENTÁRIOS.
- [Administrador](lexicos.html#administrador) SELECIONA MEMBROS.


------------
## Cenário de Negar Membro Ingressar em um [Board]() 

**Título:** Negar membro ingressar em um [board]().

**Objetivo:** Negar membro ingressar em um [board]().

**Contexto:** 
- **Pré-condição:** O usuário deve ser [administrador](lexicos.html#administrador) do [time](lexicos.html#time).
- **Pós-condição:** Membros não poderão ingressar em um [Board]() sem serem convidados.

**Atores:** [Administrador](lexicos.html#administrador) do [time](lexicos.html#time).

**Recursos:** Conta, [time](lexicos.html#time), computador, internet.

**Episódios:**
- [Administrador](lexicos.html#administrador) entra no Trello.
- [Administrador](lexicos.html#administrador) REALIZA LOGIN.
- Se há [time](lexicos.html#time), [Administrador](lexicos.html#administrador) ACESSA TIME.
- Senão, [Administrador](lexicos.html#administrador) CRIA TIME. (restrição)
- Se há [board](), [Administrador](lexicos.html#administrador) ACESSA BOARD do [time](lexicos.html#time).
- Senão, [Administrador](lexicos.html#administrador) CRIA BOARD do [time](lexicos.html#time). (restrição)
- [Administrador](lexicos.html#administrador) ACESSA MENU da [board]().
- [Administrador](lexicos.html#administrador) ACESSA MAIS OPÇÕES DO MENU.
- [Administrador](lexicos.html#administrador) ACESSA CONFIGURAÇÕES.
- Se estiver ativo, [Administrador](lexicos.html#administrador) CLICA EM PERMITIR INGRESSO DE MEMBROS DO TIME.
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

**Objetivo:** Seguir um [Card]() existente para ser [notificado](lexico.html#notificar) de mudanças por meios de [notificações](lexico.html#notificar) para o [Usuário]().

**Contexto:**
- **Pré-condição:** O [Usuário]() deve ter acesso à [List]() onde está o [Card]().
- **Pós-condição:** A aplicação deverá [notificar](lexico.html#notificar) o [usuáro]() quando o [Card]() for modificado.

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
## Cenário de [Arquivar](lexicos.html#arquivar) Card

**Título:** [Arquivar](lexicos.html#arquivar) [Card]() 

**Objetivo:** [Arquivar](lexicos.html#arquivar) um [Card]() existente para removê-lo de uma [List]() sem perder seus dados.

**Contexto:**
- **Pré-condição:** O [Usuário]() deve ter acesso à [List]() onde está o [Card]().
- **Pós-condição:** A aplicação deverá [Arquivar](lexicos.html#arquivar) o [Card]() selecionado.

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
- [Usuário]() realiza [ARQUIVAR CARD]() pressionando o botão [Arquivar](lexicos.html#arquivar);
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

------------
## Cenário de Adicionar [Anexo](lexicos.html#anexo) em um card 

**Título:** Adicionar [Anexo](lexicos.html#anexo) em um [Card]()

**Objetivo:** Adicionar um [anexo](lexicos.html#anexo) em um [Card]() do Trello.

**Contexto:**
- **Pré-condição:**  O [Usuário]() precisará possuir um dispositivo com acesso a internet, estar logado em sua conta Trello e possuir um [Card]() em uma [List]().
- **Pós-condição:** : O [Usuário]() terá adicionado um [anexo](lexicos.html#anexo) a um [Card]().

**Atores:** [Usuário]()

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() entra na tela onde tem o [Card]() desejado.
- [Usuário]() clica no [Card](). 
- No campo ‘Adicionar ao cartão’, o [Usuário]() clica na opção ‘anexo’. 
- [Usuário]() seleciona o local onde o [anexo](lexicos.html#anexo) está. 
- [Usuário]() seleciona o [anexo](lexicos.html#anexo). 
- [Usuário]() clica no botão ‘anexar’. 
- [Usuário]() terá anexado algo ao [Card]() selecionado. 

------------
## Cenário de Mover um card para outra list 

**Título:** Mover um [Card]() para outra [List]()

**Objetivo:** Mover um [Card]() de uma [List]() para outra no Trello. 

**Contexto:**
- **Pré-condição:**  O usuário precisará possuir um dispositivo com acesso a internet, estar logado em sua conta Trello, possuir um [Card]() em uma [List]() e uma outra [List]() que será o destino do [Card](). 
- **Pós-condição:** : O [Usuário]() terá movido um [Card]() de uma [List]() para outra.

**Atores:** [Usuário]()

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() entra na tela onde tem o [Card]() desejado.
- [Usuário]() clica no [Card](). 
- No campo ‘Adicionar ao cartão’, o [Usuário]() clica na opção ‘anexo’. 
- [Usuário]() seleciona o local onde o [anexo](lexicos.html#anexo) está. 
- [Usuário]() seleciona o [anexo](lexicos.html#anexo). 
- [Usuário]() clica no botão ‘anexar’. 
- [Usuário]() terá anexado algo ao [Card]() selecionado. 
- [Usuário]() entra na tela onde tem o [Card]() desejado.
- [Usuário]() clica no [Card]() e segura o botão do mouse. 
- [Usuário]() arrasta o [Card]() para a [List]() desejada. 
- [Usuário]() terá movido o [Card]() de uma [List]() para outra. 


------------
## Cenário de Responder um comentário no card 

**Título:** Responder um comentário no [Card]()

**Objetivo:** Responder um comentário em um [Card]() do Trello. 

**Contexto:**
- **Pré-condição:**  O [Usuário]() precisará possuir um dispositivo com acesso a internet, estar logado em sua conta Trello e possuir um [Card]() em uma [List]().
- **Pós-condição:** : O usuário terá respondido um comentário em um [Card](). 

**Atores:** [Usuário]()

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() entra na tela onde tem o [Card]() desejado.
- [Usuário]() clica no [Card](). 
- [Usuário]() acha o comentário que deseja responder. 
- [Usuário]() clica no botão ‘responder’ abaixo do comentário. 
- [Usuário]() escreve a resposta que deseja.
- [Usuário]() clica no botão ‘salvar’.
- [Usuário]() terá respondido o comentário selecionado.

------------
## Cenário de Excluir comentário no card

**Título:** Excluir comentário no [Card]()

**Objetivo:** Excluir um comentário em um card do Trello. 

**Contexto:**
- **Pré-condição:**  O [Usuário]() precisará possuir um dispositivo com acesso a internet, estar logado em sua conta Trello, possuir um [Card]() em uma [List]() e ter feito um comentário neste [Card](). 
- **Pós-condição:** : O [Usuário]() terá excluído um comentário em um [Card](). 

**Atores:** [Usuário]()

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() entra na tela onde tem o [Card]() desejado.
- [Usuário]() clica no [Card](). 
- [Usuário]() acha o seu comentário que deseja excluir. 
- [Usuário]() clica no botão ‘excluir’ logo abaixo do comentário. 
- [Usuário]() clica no botão ‘Excluir Comentário’. 
- [Usuário]() terá excluído o comentário desejado. 

------------
## Cenário de Usar Power-Up no quadro 

**Título:** Usar Power-Up no quadro

**Objetivo:** Usar um Power-up em um quadro no Trello.

**Contexto:**
- **Pré-condição:**  O [Usuário]() precisará possuir um dispositivo com acesso a internet, estar logado em sua conta Trello e possuir um quadro. 
- **Pós-condição:** : O [Usuário]() terá usado um Power-Up em um quadro. 

**Atores:** [Usuário]()

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() entra no quadro desejado. 
- [Usuário]() clica no botão ‘Mostrar Menu’. 
- [Usuário]() clica na opção ‘Power-Ups’. 
- [Usuário]() usa o campo de pesquisa, se necessário. 
- [Usuário]() clica no botão adicionar no Power-Up desejado. 
- [Usuário]() pode adicionar mais Power-Ups a um mesmo quadro se possuir conta diferente da ‘Grátis’. 
- [Usuário]() terá adicionado um Power-Up a um quadro.

------------
## Cenário de Compartilhar card 

**Título:** Compartilhar [Card]()

**Objetivo:** Compartilhar um [Card]() do Trello. 

**Contexto:**
- **Pré-condição:**  O [Usuário]() precisará possuir um dispositivo com acesso a internet, estar logado em sua conta Trello e possuir um [Card]() em uma [List](). 
- **Pós-condição:** : O [Usuário]() terá compartilhado um [Card](). 

**Atores:** [Usuário]()

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() entra na tela onde tem o [Card]() desejado. 
- [Usuário]() clica no [Card](). 
- [Usuário]() clica na opção ‘Compartilhar e mais...’. 
- [Usuário]() escolhe como deseja compartilhar o [Card](). 
- Ao selecionar uma das opções, o [Usuário]() terá um referencial do card de acordo com a opção escolhida. 

------------
## Cenário de Exibir detalhes do card 

**Título:** Exibir detalhes do [Card]()

**Objetivo:** Exibir detalhes de um [Card]() do Trello. 

**Contexto:**
- **Pré-condição:**  O [Usuário]() precisará possuir um dispositivo com acesso a internet, estar logado em sua conta Trello e possuir um [Card]() em uma [List](). 
- **Pós-condição:** : O usuário terá visualizado detalhes do [Card](). 

**Atores:** [Usuário]()

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() entra na tela onde tem o [Card]() desejado. 
- [Usuário]() clica no [Card]().
- [Usuário]() terá aberto os detalhes do [Card]().

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
