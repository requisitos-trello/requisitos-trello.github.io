---
layout: default
title: Cenários
category: Modelagem
---

# Cenários

------------
## Cenário de Login

**Título:** [Login]() comum 

**Objetivo:** Logar em uma conta do trello.

**Contexto:**
- **Pré-condição:** O usuário precisará possuir uma conta na plataforma Trello e
possuir um dispositivo com acesso a internet.
- **Pós-condição:** O usuário estará logado na aplicação, com acesso a seus
boards

**Atores:** Usuário

**Recursos:** Dispositivo com acesso a um navegador ou ao aplicativo Trello, ambos devem
possuir conexão a internet.

**Episódios:**
- Usuário entra na tela de [Login]() da aplicação;
- Usuário insere o endereço de e-mail de sua conta;
- Usuário insere a senha de sua conta;
- Usuário clica no botão ‘Fazer Login’;
- Usuário estará logado na aplicação.

------------
## Cenário de Login

**Título:** [Login]() com o Google

**Objetivo:** Logar no Trello através de sua conta Google.

**Contexto:**
- **Pré-condição:** ​ O usuário precisará possuir uma conta Google e possuir um
dispositivo com acesso a internet.
- **Pós-condição:** O usuário estará logado na aplicação, com acesso a seus
[Boards](lexicos.html#board)

**Atores:** Usuário

**Recursos:** Dispositivo com acesso a um navegador ou ao aplicativo Trello, ambos devem
possuir conexão a internet.

**Episódios:**
- Usuário entra na tela de [Login]() da aplicação;
- Usuário clica em ‘Fazer Login com o Google’;
- Usuário insere o endereço de e-mail ou telefone;
- Usuário clica no botão ‘Próxima’;
- Usuário insere a senha;
- Usuário clica no botão ‘Próxima’;
- Usuário estará logado na aplicação.

------------
## Cenário de Cadastro

**Título:** Cadastrar no Trello.

**Objetivo:** Cadastrar uma nova conta na plataforma Trello.

**Contexto:**
- **Pré-condição:** O usuário precisará possuir um dispositivo com acesso a
internet e um e-mail não cadastrado no sistema do Trello.
- **Pós-condição:** O usuário terá cadastrado uma nova conta e
automaticamente estará logado na aplicação.

**Atores:** Usuário

**Recursos:** Dispositivo com acesso a um navegador ou ao aplicativo Trello, ambos devem
possuir conexão a internet.

**Episódios:**
- Usuário entra na tela de cadastro da aplicação;
- Usuário insere o seu nome;
- Usuário insere o endereço de e-mail desejado;
- Usuário insere a senha desejada;
- Usuário clica no botão ‘Criar Nova Conta’;
- Usuário estará cadastrado e logado na aplicação.

------------
## Cenário de Alterar Senha

**Título:**  ​Alterar senha.

**Objetivo:** Alterar senha de uma conta existente da plataforma Trello.

**Contexto:**
- **Pré-condição:** O usuário precisará possuir um dispositivo com acesso a
internet e uma conta cadastrada no sistema do Trello.
- **Pós-condição:** O usuário terá alterado a senha de sua conta.

**Atores:** Usuário

**Recursos:** Dispositivo com acesso a um navegador ou ao aplicativo Trello, ambos devem
possuir conexão a internet.

**Episódios:**
- Usuário entra na tela de ’Esqueceu sua senha?’;
- Usuário insere o endereço de e-mail de sua conta;
- Usuário clica no botão ‘Enviar’;
- Usuário recebe um e-mail para redefinir sua senha;
- Usuário abre o e-mail recebido;
- Usuário clica no botão ‘Redefinir Senha’;
- Usuário insere a nova senha;
- Usuário insere a nova senha novamente;
- Usuário clica no botão ‘Enviar’.

------------
## Cenário alterar configurações de Notificação

**Título:**  ​Alterar configurações de [Notificação](lexicos.html#notificar).

**Objetivo:** ​Alterar configurações de [Notificação](lexicos.html#notificar) da sua conta Trello.

**Contexto:**
- **Pré-condição:** O usuário precisará possuir um dispositivo com acesso a
internet e estar logado em sua conta Trello.
- **Pós-condição:** O usuário terá alterado as configurações de [Notificação](lexicos.html#notificar) de
sua conta.

**Atores:** Usuário

**Recursos:** Dispositivo com acesso a um navegador ou ao aplicativo Trello, ambos devem
possuir conexão a internet.

**Episódios:**
- Usuário entra na tela em suas notificações;
- Usuário clica em ‘Alterar Frequência de [Notificação](lexicos.html#notificar) por Email’;
- Usuário seleciona uma das três opções: Nunca, Periodicamente e
Instantaneamente;
- Usuário terá alterado a frequência de notificações por e-mail;
- Usuário clica em ‘Permitir [Notificação](lexicos.html#notificar) da Área de Trabalho’;
- Usuário terá permitido a aplicação a exibir [Notificação](lexicos.html#notificar) da Área de Trabalho.

------------
## Cenário ver notificações

**Título:**  ​Ver [Notificações](lexicos.html#notificar).

**Objetivo:** ​Ver [Notificações](lexicos.html#notificar) da sua conta Trello.

**Contexto:**
- **Pré-condição:** O usuário precisará possuir um dispositivo com acesso a
internet e estar logado em sua conta Trello.
- **Pós-condição:** O usuário terá visto as [Notificações](lexicos.html#notificar) de sua conta, caso
exista.

**Atores:** Usuário

**Recursos:** Dispositivo com acesso a um navegador ou ao aplicativo Trello, ambos devem
possuir conexão a internet.

**Episódios:**
- Usuário abre a página inicial;
- Usuário clica na imagem de um sino na parte superior direita de sua tela;
- Usuário entra na tela de suas [Notificações](lexicos.html#notificar);
- Usuário vê suas [Notificações](lexicos.html#notificar), caso exista alguma notificação não lida.

------------
## Cenário criar time

**Título:** ​Criar [Time](lexicos.html#time).

**Objetivo:** ​Criar um [Time](lexicos.html#time) na plataforma Trello.

**Contexto:**
- **Pré-condição:** ​ O usuário precisará possuir um dispositivo com acesso a
internet e estar logado em sua conta Trello.
- **Pós-condição:** ​O usuário terá criado um novo [Time](lexicos.html#time).

**Atores:** ​Usuário.

**Recursos:** ​Dispositivo com acesso a um navegador ou ao aplicativo Trello, ambos devem
possuir conexão a internet.

**Episódios:**
- Usuário abre a página inicial;
- Usuário clica em ‘Criar um time’;
- Usuário insere o nome do [Time](lexicos.html#time);
- Usuário insere a descrição do [Time](lexicos.html#time) (opcional);
- Usuário clica no botão ‘Criar’;
- Usuário terá criado um novo [Time](lexicos.html#time).

------------
## Cenário convidar usuários para um time

**Título:** ​Convidar usuários para um [Time](lexicos.html#time).

**Objetivo:** ​Convidar usuários da plataforma Trello para participar de um [Time](lexicos.html#time).

**Contexto:**
- **Pré-condição:** ​ O usuário precisará possuir um dispositivo com acesso a
internet e estar logado em sua conta Trello.
- **Pós-condição:** ​O usuário terá convidado um ou mais usuários para seu [Time](lexicos.html#time).

**Atores:** ​Usuário.

**Recursos:** ​Dispositivo com acesso a um navegador ou ao aplicativo Trello, ambos devem
possuir conexão a internet.

**Episódios:**
- Usuário abre a página do [Time](lexicos.html#time);
- Usuário clica no botão ‘Membros’;
- Usuário insere o nome do usuário a ser convidado;
- Usuário clica no botão ‘Convidar para o Time’;
- Usuário terá convidado um usuário para seu [Time](lexicos.html#time).

------------
## Cenário de imprimir Board

**Título:** Impressão de [Board](lexicos.html#board) 

**Objetivo:** Passar algumas informações de à [Board](lexicos.html#board) para uma folha de papel.

**Contexto:**
- **Pré-condição:** O Usuário deve ter acesso à [Board](lexicos.html#board) que quer imprimir.
- **Pós-condição:** A aplicação deverá comunicar ao browser que uma impressão está sendo solicitada.

**Atores:** Usuário

**Recursos:** Dispositivo desktop com browser compatível com os recursos do Trello e com acesso à impressora, além da impressora devidamente preparada para impressão.

**Episódios:**
- Usuário realiza [Login]();
- Usuário acessa a [Board](lexicos.html#board) desejada;
- Usuário abre o [Menu lateral]();
- Usuário seleciona a opção **Mais**;
- Usuário seleciona a opção **Imprimir e Exportar**;
- Usuário seleciona a opção **Imprimir...**;
- A aplicação converte a [Board](lexicos.html#board) para um formato imprimível;
- Browser faz a comunicação com o Sistema Operacional, que por sua vez comunica-se com a impressora.

--------------
## Cenário de adicionar [Stickers](lexicos.html#sticker)

**Título:** Adição de [Stickers](lexicos.html#sticker)

**Objetivo:** Adição de elementos visuais que facilitem a orientação intuitiva e visual do Usuário pela [Board](lexicos.html#board).

**Contexto:**
- **Pré-condição:** O Usuário deve ter acesso à [Board](lexicos.html#board) na qual quer adicionar [stickers](lexicos.html#sticker).
- **Pós-condição:** Um [sticker](lexicos.html#sticker) deve ser adicionado a um [Card](lexicos.html#card) na [Board](lexicos.html#board) em questão.

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser em um dispositivo desktop.

**Episódios:**
- Usuário faz [Login]();
- Usuário acessa a [Board](lexicos.html#board) desejada;
- Usuário abre o [Menu Lateral]();
- Usuário seleciona a opção **[Stickers](lexicos.html#sticker)**;
- Usuário clica e arrasta o Sticker desejado até o [Card](lexicos.html#card) desejado;

--------------
## Cenário de editar/remover [Stickers](lexicos.html#sticker)

**Título:** Edição de [Stickers](lexicos.html#sticker)

**Objetivo:** Editar o estado atual de [sticker](lexicos.html#sticker) previamente adicionado.

**Contexto:**
- **Pré-condição:** Deve existir um [sticker](lexicos.html#sticker) em uma [Board](lexicos.html#board) com o acesso do Usuário que queira remover ou editar este mesmo [sticker](lexicos.html#sticker).
- **Pós-condição:** O [sticker](lexicos.html#sticker) não mais estará onde está.

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- Usuário faz [Login]();
- Usuário acessa a [Board](lexicos.html#board) em questão;
- Usuário clica com o botão direito do mouse no [Card](lexicos.html#card)  de onde quer mover o [sticker](lexicos.html#sticker);
- Usuário clica com o botão esquerdo do mouse no [sticker](lexicos.html#sticker) que quer editar;
- Usuário seleciona uma das opções: **Girar**, **Mover** ou **Remover** segundo sua vontade;
- Em caso de **Girar** ou **Mover**, o Usuário clica e segura com o botão esquerdo do mouse, movendo o cursos até que o [sticker](lexicos.html#sticker) alcance a posição desejada;

--------------
## Cenário de Alterar Tela de Fundo

**Título:** Alteração da Tela de Fundo de uma [Board](lexicos.html#board)

**Objetivo:** Criação de uma identidade visual para a [Board](lexicos.html#board) em questão.

**Contexto:**
- **Pré-condição:** O Usuário deve ter acesso à [Board](lexicos.html#board) a qual quer alterar o plano de fundo.
- **Pós-condição:** A tela de fundo dessa [Board](lexicos.html#board) será alterada.

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- Usuário faz [Login]();
- Usuário acessa a [Board](lexicos.html#board) cujo plano quer alterar;
- Usuário abre o [Menu Lateral]();
- Usuário seleciona a opção **Alterar Tela de Fundo**;
- Usuário seleciona entre as opções **Cores** ou **Fotos**;
    - Caso o [Board](lexicos.html#board) seja de um [time](lexicos.html#time) [Business Class](), a opção **Personalizar** também estará disponível;
- Caso tenha selecionado **Cores**, o Usuário escolhe uma entre as nove cores disponíveis, ou clica na **seta à esqueda** para voltar à tela anterior;
- Caso tenha selecionado **Fotos**, o usário escollhe uma entre as inúmeras fotos disponibilizadas pelo Unsplash em colaboração com o Trello ou clica na **seta à esqueda** para voltar à tela anterior;
    - É possível pesquisar por termos e a aplicação retornará imagens marcadas com os termos pesquisados.

--------------
## Cenário de Filtrar Cartões

**Título:** Pesquisa Filtrada de [Cards]()

**Objetivo:** Filtrar cards através de suas características.

**Contexto:**
- **Pré-condição:** O Usuário está procurando por um ou mais cards que atendam às características pesquisadas em uma [Board](lexicos.html#board) à qual o Usuário tenha acesso.
- **Pós-condição:** Deverão aparecer na tela apenas os cards que atendam às características solicitadas na filtragem.

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- Usuário faz [Login]();
- Usuário acessa a [Board](lexicos.html#board) onde estão os cards que ele procura;
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
    - Usuário pode selecionar se as buscas por etiquetas e membros seguem lógica AND (todos os membros e etiquetas procurados devem estar contido nos cards procurados) ou se seguem lógica OR (qualquer [Card](lexicos.html#card) que contenha um membro ou etiqueta procurados se enquadra na pesquisa).
- Aparece um texto na parte superior da [Board](lexicos.html#board) indicando que a busca está ativada e, por isso, alguns cards podem estar sendo omitidos;
    - Para encerrar a filtragem, o Usuário pode clicar no X ao lado deste texto.

--------------
## Cenário de [Copiar](lexico.html#copiar) um Quadro

**Título:** Cópia de [Board](lexicos.html#board)

**Objetivo:** Criação de um [Board](lexicos.html#board) com algumas características iguais às de um [Board](lexicos.html#board) específico.

**Contexto:**
- **Pré-condição:** O Usuário deve ter acesso à [Board](lexicos.html#board) que quer [copiar](lexico.html#copiar).
- **Pós-condição:** Será criada uma nova [Board](lexicos.html#board) com algumas características trazidas de outra.

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- Usuário faz [Login]();
- Usuário acessa a [Board](lexicos.html#board) que quer [copiar](lexico.html#copiar);
- Usuário abre o [Menu Lateral]() e seleciona a opção **Mais**;
- Usuário seleciona a opção **Copiar Quadro**;
- Usuário digita um título para o novo [Board](lexicos.html#board) que será criado;
- Opcionalmente, o Usuário escolhe um [time](lexicos.html#time) do qual faça parte para popular o novo quadro;
- Usuário decide a visibilidade do quadro (se é particular, de visibilidade apenas do [time](lexicos.html#time) ou se é público);
- Usuário decide se quer [copiar](lexico.html#copiar), também, os [Cards]() contidos no [Board](lexicos.html#board) atual.
- É criada uma nova [Board](lexicos.html#board);
 
--------------
## Cenário de Seguir Quadro

**Título:** [Seguir]() uma [Board](lexicos.html#board)

**Objetivo:** Ser [notificado](lexico.html#notificar) de alterações que aconteçam em uma [Board](lexicos.html#board)

**Contexto:**
- **Pré-condição:** O Usuário deve ter acesso à [Board](lexicos.html#board) que quer seguir.
- **Pós-condição:** O Usuário será [notificado](lexico.html#notificar) de alterações que ocorrerem na [Board](lexicos.html#board) em questão.

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop ou acesso aplicação mobile conectada à internet.

**Episódios:**
- Usuário faz [Login]();
- Usuário acessa a [Board](lexicos.html#board) que quer seguir;
- Usuário abre o [Menu Lateral]() e seleciona a opção **Seguir**;
- O sistema passa a [notificar](lexico.html#notificar) o Usuário em seu e-mail e no espaço de [notificações](lexico.html#notificar) do Trello;
- Aparece um texto no canto superior esquerdo da [Board](lexicos.html#board) indicando que o Usuário está seguindo esta [Board](lexicos.html#board).
- O Usuário pode selecionar novamente a opção **Seguir** para parar de seguir, ou clicar no texto recém-aparecido que ascenderá um botão **Parar de seguir**.

--------------
## Cenário de Fechar um Quadro

**Título:** Fechamento de [Board](lexicos.html#board)

**Objetivo:** Enviar a [Board](lexicos.html#board) para um espaço equivalente à lixeira, onde não são imediatamente excluídos mas não mais dividem espaço com outras Boards.

**Contexto:**
- **Pré-condição:** O Usuário deve ser criador do [Board](lexicos.html#board) que quer fechar.
- **Pós-condição:** O [Board](lexicos.html#board) deve sair do espaço de Boards do Usuário, sem necessariamente ser excluído.

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- Usuário faz [Login]();
- Usuário acessa a [Board](lexicos.html#board) que deseja fechar;
- Usuário abre o [Menu Lateral]() e seleciona a opção **Mais**;
- Usuário seleciona a opção **Fechar Quadro...**;
- Usuário clica no botão vermelhor **Fechar**;

------------
## Cenário de Exportar um Quadro para JSON

**Título:** Exportação de [Board](lexicos.html#board) para JSON 

**Objetivo:** Passar algumas informações de à [Board](lexicos.html#board) para o formato JSON.

**Contexto:**
- **Pré-condição:** O Usuário deve ter acesso à [Board](lexicos.html#board) que quer exportar.
- **Pós-condição:** A aplicação deverá retornar um código JSON que reflita o atual estado da [Board](lexicos.html#board).

**Atores:** Usuário

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- Usuário realiza [Login]();
- Usuário acessa a [Board](lexicos.html#board) desejada;
- Usuário abre o [Menu lateral]();
- Usuário seleciona a opção **Mais**;
- Usuário seleciona a opção **Imprimir e Exportar**;
- Usuário seleciona a opção **Exportar como JSON**;
- A aplicação redireciona para uma página que contém apenas o código JSON da [Board](lexicos.html#board);

------------
## Cenário de Retirar Membros de um [Time](lexicos.html#time)

**Título:** Retirar membros de um [time](lexicos.html#time).

**Objetivo:** Com isto é possível remover um membro de um [time](lexicos.html#time).

**Contexto:**
- **Pré-condição:** O usuário deve ser [administrador](lexicos.html#administrador) do [Time](lexicos.html#time) e deve ter ao menos um membro além do [administrador](lexicos.html#administrador).
- **Pós-condição:** Usuário retirado deixará de ser membro do [time](lexicos.html#time).

**Atores:** [Administrador](lexicos.html#administrador) do [time](lexicos.html#time), membro do [time](lexicos.html#time).

**Recursos:** Conta, [time](lexicos.html#time), membro, computador, internet.

**Episódios:**
- [Administrador](lexicos.html#administrador) entra no Trello.
- [Administrador](lexicos.html#administrador) realiza [LOGIN]().
- Se há [time](lexicos.html#time), [Administrador](lexicos.html#administrador) acessa [time](lexicos.html#time).
- Senão, fluxo encerrado. (exceção)
- [Administrador](lexicos.html#administrador) acessa lista de membros.
- Se há membros, [Administrador](lexicos.html#administrador) EXCLUI MEMBRO que deseja.
- Senão, fluxo encerrado. (exceção)


------------
## Cenário de Adicionar Descrição de [Time](lexicos.html#time)

**Título:** Adicionar descrição de [time](lexicos.html#time).

**Objetivo:** Permita a adição de descrição de um [time](lexicos.html#time).

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

**Objetivo:** permite a edição da descrição de um [time](lexicos.html#time).

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

**Objetivo:** Permita a edição da visibilidade de um [time](lexicos.html#time).

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

**Objetivo:** Com isto [usuário](lexicos.html#usuario) pode Vincular [Time](lexicos.html#time) com o Slack.

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
## Cenário de Permitir Membro Comentar em um [Board](lexicos.html#board) 

**Título:** Permitir membro comentar em um [Board](lexicos.html#board).

**Objetivo:** Permitir a alteração das permissões de membro com relação a comentar em um [Board](lexicos.html#board).

**Contexto:** 
- **Pré-condição:** O usuário deve ser [administrador](lexicos.html#administrador) do [time](lexicos.html#time).
- **Pós-condição:** Membros poderão comentar em um [Board](lexicos.html#board).

**Atores:** [Administrador](lexicos.html#administrador) do [time](lexicos.html#time).

**Recursos:** Conta, [time](lexicos.html#time), [Board](lexicos.html#board), [Lista](lexicos.html#lista), card, comentário, computador, internet.

**Episódios:**
- [Administrador](lexicos.html#administrador) entra no Trello.
- [Administrador](lexicos.html#administrador) REALIZA LOGIN.
- Se há [time](lexicos.html#time), [Administrador](lexicos.html#administrador) ACESSA TIME.
- Senão, [Administrador](lexicos.html#administrador) CRIA TIME. (restrição)
- Se há [Board](lexicos.html#board), [Administrador](lexicos.html#administrador) ACESSA BOARD do [time](lexicos.html#time).
- Senão, [Administrador](lexicos.html#administrador) CRIA BOARD do [time](lexicos.html#time).
- [Administrador](lexicos.html#administrador) ACESSA MENU da [Board](lexicos.html#board).
- [Administrador](lexicos.html#administrador) ACESSA MAIS OPÇÕES DO MENU.
- [Administrador](lexicos.html#administrador) ACESSA CONFIGURAÇÕES.
- [Administrador](lexicos.html#administrador) ACESSA PERMISSÕES PARA COMENTÁRIOS.
- [Administrador](lexicos.html#administrador) SELECIONA MEMBROS.


------------
## Cenário de Negar Membro Ingressar em um [Board](lexicos.html#board) 

**Título:** Negar membro ingressar em um [Board](lexicos.html#board).

**Objetivo:** Altera a permissão de um membro de time de ingressar em um [Board](lexicos.html#board).

**Contexto:** 
- **Pré-condição:** O usuário deve ser [administrador](lexicos.html#administrador) do [time](lexicos.html#time).
- **Pós-condição:** Membros não poderão ingressar em um [Board](lexicos.html#board) sem serem convidados.

**Atores:** [Administrador](lexicos.html#administrador) do [time](lexicos.html#time).

**Recursos:** Conta, [time](lexicos.html#time), computador, internet.

**Episódios:**
- [Administrador](lexicos.html#administrador) entra no Trello.
- [Administrador](lexicos.html#administrador) REALIZA LOGIN.
- Se há [time](lexicos.html#time), [Administrador](lexicos.html#administrador) ACESSA TIME.
- Senão, [Administrador](lexicos.html#administrador) CRIA TIME. (restrição)
- Se há [Board](lexicos.html#board), [Administrador](lexicos.html#administrador) ACESSA BOARD do [time](lexicos.html#time).
- Senão, [Administrador](lexicos.html#administrador) CRIA BOARD do [time](lexicos.html#time). (restrição)
- [Administrador](lexicos.html#administrador) ACESSA MENU da [Board](lexicos.html#board).
- [Administrador](lexicos.html#administrador) ACESSA MAIS OPÇÕES DO MENU.
- [Administrador](lexicos.html#administrador) ACESSA CONFIGURAÇÕES.
- Se estiver ativo, [Administrador](lexicos.html#administrador) CLICA EM PERMITIR INGRESSO DE MEMBROS DO TIME.
- Senão, a permissão já foi negada.
## Cenário de Ver Lista

**Título:** Ver [Lista](lexicos.html#lista) 

**Objetivo:** Mostrar o conteúdo de uma [Lista](lexicos.html#lista) para o [Usuário]().

**Contexto:**
- **Pré-condição:** O [Usuário]() deve ter acesso à [Lista](lexicos.html#lista) que quer visualizar.
- **Pós-condição:** A aplicação deverá mostrar a [Lista](lexicos.html#lista) para o [Usuário]().

**Atores:** [Usuário]()

**Restrições** 

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() realiza [LOGIN]();
- Se não há [Board](lexicos.html#board), [Usuário]() realiza [CRIAR BOARD]();
- [Usuário]() realiza [VER BOARD]();
- Se não há [Lista](lexicos.html#lista), [Usuário]() realiza [CRIAR LISTA]();
- [Usuário]() realiza [VER LIST]();
- A aplicação mostra a [Lista](lexicos.html#lista) desejada para o [Usuário]().


------------
# Cards

## Cenário de Criar Card

**Título:** Criar [Card](lexicos.html#card)  

**Objetivo:** Criar um novo [Card](lexicos.html#card)  para armazenar dados dentro de uma [Lista](lexicos.html#lista).

**Contexto:**
- **Pré-condição:** O [Usuário]() deve ter acesso à [Lista](lexicos.html#lista) onde quer criar o [Card](lexicos.html#card) .
- **Pós-condição:** A aplicação deverá criar o [Card](lexicos.html#card)  dentro da [Lista](lexicos.html#lista) para o [Usuário]().

**Atores:** [Usuário]()

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() realiza [LOGIN]();
- Se não há [Board](lexicos.html#board), [Usuário]() realiza [CRIAR BOARD]();
- [Usuário]() realiza [VER BOARD]();
- Se não há [Lista](lexicos.html#lista), [Usuário]() realiza [CRIAR LISTA]();
- [Usuário]() realiza [VER LISTA]();
- [Usuário]() realiza [CRIAR CARD]()
- A aplicação mostra a [Lista](lexicos.html#lista) desejada para o [Usuário]().

------------
## Cenário de Modificar Card

**Título:** Modificar [Card](lexicos.html#card)  

**Objetivo:** Modificar um [Card](lexicos.html#card)  existente para atualizar os seus dados dentro de uma [Lista](lexicos.html#lista).

**Contexto:**
- **Pré-condição:** O [Usuário]() deve ter acesso à [Lista](lexicos.html#lista) onde está o [Card](lexicos.html#card) .
- **Pós-condição:** A aplicação deverá atualizar o [Card](lexicos.html#card)  com os novos dados.

**Atores:** [Usuário]()

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() realiza [LOGIN]();
- Se não há [Board](lexicos.html#board), [Usuário]() realiza [CRIAR BOARD]();
- [Usuário]() realiza [VER BOARD]();
- Se não há [Lista](lexicos.html#lista), [Usuário]() realiza [CRIAR LISTA]();
- [Usuário]() realiza [VER LISTA]();
- Se não há [Card](lexicos.html#card) , [Usuário](), realiza [CRIAR CARD]();
- [Usuário]() realiza [VER CARD]();
- [Usuário]() realiza [MODIFICAR CARD]();
- A aplicação mostra uma janela de edição para o [Card](lexicos.html#card)  desejado para o [Usuário]().

------------
## Cenário de Ver Card

**Título:** Ver [Card](lexicos.html#card)  

**Objetivo:** Visualizar um [Card](lexicos.html#card)  existente para mostrar o seu conteúdo para o [Usuário]().

**Contexto:**
- **Pré-condição:** O [Usuário]() deve ter acesso à [Lista](lexicos.html#lista) onde está o [Card](lexicos.html#card) .
- **Pós-condição:** A aplicação deverá mostrar o [Card](lexicos.html#card)  com seu conteúdo.

**Atores:** [Usuário]()

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() realiza [LOGIN]();
- Se não há [Board](lexicos.html#board), [Usuário]() realiza [CRIAR BOARD]();
- [Usuário]() realiza [VER BOARD]();
- Se não há [Lista](lexicos.html#lista), [Usuário]() realiza [CRIAR LISTA]();
- [Usuário]() realiza [VER LISTA]();
- Se não há [Card](lexicos.html#card) , [Usuário](), realiza [CRIAR CARD]();
- [Usuário]() realiza [VER CARD]();
- A aplicação mostra uma janela com os dados do [Card](lexicos.html#card)  desejado para o [Usuário]().

------------
## Cenário de Modificar Card

**Título:** Modificar [Card](lexicos.html#card)  

**Objetivo:** Modificar um [Card](lexicos.html#card)  existente para atualizar os seus dados dentro de uma [Lista](lexicos.html#lista).

**Contexto:**
- **Pré-condição:** O [Usuário]() deve ter acesso à [Lista](lexicos.html#lista) onde está o [Card](lexicos.html#card) .
- **Pós-condição:** A aplicação deverá atualizar o [Card](lexicos.html#card)  com os novos dados.

**Atores:** [Usuário]()

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() realiza [LOGIN]();
- Se não há [Board](lexicos.html#board), [Usuário]() realiza [CRIAR BOARD]();
- [Usuário]() realiza [VER BOARD]();
- Se não há [Lista](lexicos.html#lista), [Usuário]() realiza [CRIAR LISTA]();
- [Usuário]() realiza [VER LISTA]();
- Se não há [Card](lexicos.html#card) , [Usuário](), realiza [CRIAR CARD]();
- [Usuário]() realiza [VER CARD]();
- [Usuário]() realiza [MODIFICAR CARD]();
- A aplicação mostra uma janela de edição para o [Card](lexicos.html#card)  desejado para o [Usuário]().

------------
## Cenário de Modificar Card

**Título:** Modificar [Card](lexicos.html#card)  

**Objetivo:** Modificar um [Card](lexicos.html#card)  existente para atualizar os seus dados dentro de uma [Lista](lexicos.html#lista).

**Contexto:**
- **Pré-condição:** O [Usuário]() deve ter acesso à [Lista](lexicos.html#lista) onde está o [Card](lexicos.html#card) .
- **Pós-condição:** A aplicação deverá atualizar o [Card](lexicos.html#card)  com os novos dados.

**Atores:** [Usuário]()

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() realiza [LOGIN]();
- Se não há [Board](lexicos.html#board), [Usuário]() realiza [CRIAR BOARD]();
- [Usuário]() realiza [VER BOARD]();
- Se não há [Lista](lexicos.html#lista), [Usuário]() realiza [CRIAR LISTA]();
- [Usuário]() realiza [VER LISTA]();
- Se não há [Card](lexicos.html#card) , [Usuário](), realiza [CRIAR CARD]();
- [Usuário]() realiza [VER CARD]();
- [Usuário]() realiza [MODIFICAR CARD]();
- A aplicação mostra uma janela de edição para o [Card](lexicos.html#card)  desejado para o [Usuário]().

------------
## Cenário de Seguir Card

**Título:** Seguir [Card](lexicos.html#card)  

**Objetivo:** Seguir um [Card](lexicos.html#card)  existente para ser [notificado](lexico.html#notificar) de mudanças por meios de [notificações](lexico.html#notificar) para o [Usuário]().

**Contexto:**
- **Pré-condição:** O [Usuário]() deve ter acesso à [Lista](lexicos.html#lista) onde está o [Card](lexicos.html#card) .
- **Pós-condição:** A aplicação deverá [notificar](lexico.html#notificar) o [usuáro]() quando o [Card](lexicos.html#card)  for modificado.

**Atores:** [Usuário]()

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() realiza [LOGIN]();
- Se não há [Board](lexicos.html#board), [Usuário]() realiza [CRIAR BOARD]();
- [Usuário]() realiza [VER BOARD]();
- Se não há [Lista](lexicos.html#lista), [Usuário]() realiza [CRIAR LISTA]();
- [Usuário]() realiza [VER LISTA]();
- Se não há [Card](lexicos.html#card) , [Usuário](), realiza [CRIAR CARD]();
- [Usuário]() realiza [VER CARD]();
- [Usuário]() realiza [SEGUIR CARD]() pressionando o botão seguir;
- A aplicação retorna à tela de [VER CARD]().

------------
## Cenário de [Arquivar](lexicos.html#arquivar) Card

**Título:** [Arquivar](lexicos.html#arquivar) [Card](lexicos.html#card)  

**Objetivo:** [Arquivar](lexicos.html#arquivar) um [Card](lexicos.html#card)  existente para removê-lo de uma [Lista](lexicos.html#lista) sem perder seus dados.

**Contexto:**
- **Pré-condição:** O [Usuário]() deve ter acesso à [Lista](lexicos.html#lista) onde está o [Card](lexicos.html#card) .
- **Pós-condição:** A aplicação deverá [Arquivar](lexicos.html#arquivar) o [Card](lexicos.html#card)  selecionado.

**Atores:** [Usuário]()

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() realiza [LOGIN]();
- Se não há [Board](lexicos.html#board), [Usuário]() realiza [CRIAR BOARD]();
- [Usuário]() realiza [VER BOARD]();
- Se não há [Lista](lexicos.html#lista), [Usuário]() realiza [CRIAR LISTA]();
- [Usuário]() realiza [VER LISTA]();
- Se não há [Card](lexicos.html#card) , [Usuário](), realiza [CRIAR CARD]();
- [Usuário]() realiza [VER CARD]();
- [Usuário]() realiza [ARQUIVAR CARD]() pressionando o botão [Arquivar](lexicos.html#arquivar);
- A aplicação retorna à tela de [VER LISTA]().

------------
## Cenário de Personalizar Label

**Título:** Personalizar [Label]() 

**Objetivo:** Personalizar a [Label]() atribuído à um [Card](lexicos.html#card) para diferenciar ou destacá-lo em relação aos outros.

**Contexto:**
- **Pré-condição:** O [Usuário]() deve ter acesso à [Lista](lexicos.html#lista) onde está o [Card](lexicos.html#card) .
- **Pós-condição:** A aplicação deverá mostrar o [Card](lexicos.html#card)  com seu novo [Label]().

**Atores:** [Usuário]()

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() realiza [LOGIN]();
- Se não há [Board](lexicos.html#board), [Usuário]() realiza [CRIAR BOARD]();
- [Usuário]() realiza [VER BOARD]();
- Se não há [Lista](lexicos.html#lista), [Usuário]() realiza [CRIAR LISTA]();
- [Usuário]() realiza [VER LISTA]();
- Se não há [Card](lexicos.html#card) , [Usuário](), realiza [CRIAR CARD]();
- [Usuário]() realiza [VER CARD]();
- [Usuário]() realiza [PERSONALIZAR Label]();
- A aplicação mostra uma janela com opções de persnoalização para o [Label]() para o [Usuário]().

------------
## Cenário de Adicionar [Anexo](lexicos.html#anexo) em um card

**Título:** Adicionar [Anexo](lexicos.html#anexo) em um [Card](lexicos.html#card) 

**Objetivo:** Adicionar um [anexo](lexicos.html#anexo) em um [Card](lexicos.html#card)  do Trello.

**Contexto:**
- **Pré-condição:**  O [Usuário]() precisará possuir um dispositivo com acesso a internet, estar logado em sua conta Trello e possuir um [Card](lexicos.html#card)  em uma [Lista](lexicos.html#lista).
- **Pós-condição:** : O [Usuário]() terá adicionado um [anexo](lexicos.html#anexo) a um [Card](lexicos.html#card) .

**Atores:** [Usuário]()

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() entra na tela onde tem o [Card](lexicos.html#card)  desejado.
- [Usuário]() clica no [Card](lexicos.html#card) . 
- No campo ‘Adicionar ao cartão’, o [Usuário]() clica na opção ‘anexo’. 
- [Usuário]() seleciona o local onde o [anexo](lexicos.html#anexo) está. 
- [Usuário]() seleciona o [anexo](lexicos.html#anexo). 
- [Usuário]() clica no botão ‘anexar’. 
- [Usuário]() terá anexado algo ao [Card](lexicos.html#card)  selecionado. 

------------
## Cenário de Mover um [Card](lexicos.html#card) para outra list 

**Título:** Mover um [Card](lexicos.html#card)  para outra [Lista](lexicos.html#lista)

**Objetivo:** Mover um [Card](lexicos.html#card)  de uma [Lista](lexicos.html#lista) para outra no Trello. 

**Contexto:**
- **Pré-condição:**  O usuário precisará possuir um dispositivo com acesso a internet, estar logado em sua conta Trello, possuir um [Card](lexicos.html#card)  em uma [Lista](lexicos.html#lista) e uma outra [Lista](lexicos.html#lista) que será o destino do [Card](lexicos.html#card) . 
- **Pós-condição:** : O [Usuário]() terá movido um [Card](lexicos.html#card)  de uma [Lista](lexicos.html#lista) para outra.

**Atores:** [Usuário]()

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() entra na tela onde tem o [Card](lexicos.html#card)  desejado.
- [Usuário]() clica no [Card](lexicos.html#card) . 
- No campo ‘Adicionar ao cartão’, o [Usuário]() clica na opção ‘anexo’. 
- [Usuário]() seleciona o local onde o [anexo](lexicos.html#anexo) está. 
- [Usuário]() seleciona o [anexo](lexicos.html#anexo). 
- [Usuário]() clica no botão ‘anexar’. 
- [Usuário]() terá anexado algo ao [Card](lexicos.html#card)  selecionado. 
- [Usuário]() entra na tela onde tem o [Card](lexicos.html#card)  desejado.
- [Usuário]() clica no [Card](lexicos.html#card)  e segura o botão do mouse. 
- [Usuário]() arrasta o [Card](lexicos.html#card)  para a [Lista](lexicos.html#lista) desejada. 
- [Usuário]() terá movido o [Card](lexicos.html#card)  de uma [Lista](lexicos.html#lista) para outra. 


------------
## Cenário de Responder um comentário no card

**Título:** Responder um comentário no [Card](lexicos.html#card) 

**Objetivo:** Responder um comentário em um [Card](lexicos.html#card)  do Trello. 

**Contexto:**
- **Pré-condição:**  O [Usuário]() precisará possuir um dispositivo com acesso a internet, estar logado em sua conta Trello e possuir um [Card](lexicos.html#card)  em uma [Lista](lexicos.html#lista).
- **Pós-condição:** : O usuário terá respondido um comentário em um [Card](lexicos.html#card) . 

**Atores:** [Usuário]()

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() entra na tela onde tem o [Card](lexicos.html#card)  desejado.
- [Usuário]() clica no [Card](lexicos.html#card) . 
- [Usuário]() acha o comentário que deseja responder. 
- [Usuário]() clica no botão ‘responder’ abaixo do comentário. 
- [Usuário]() escreve a resposta que deseja.
- [Usuário]() clica no botão ‘salvar’.
- [Usuário]() terá respondido o comentário selecionado.

------------
## Cenário de Excluir comentário no card

**Título:** Excluir comentário no [Card](lexicos.html#card) 

**Objetivo:** Excluir um comentário em um [Card](lexicos.html#card) do Trello. 

**Contexto:**
- **Pré-condição:**  O [Usuário]() precisará possuir um dispositivo com acesso a internet, estar logado em sua conta Trello, possuir um [Card](lexicos.html#card)  em uma [Lista](lexicos.html#lista) e ter feito um comentário neste [Card](lexicos.html#card) . 
- **Pós-condição:** : O [Usuário]() terá excluído um comentário em um [Card](lexicos.html#card) . 

**Atores:** [Usuário]()

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() entra na tela onde tem o [Card](lexicos.html#card)  desejado.
- [Usuário]() clica no [Card](lexicos.html#card) . 
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

**Título:** Compartilhar [Card](lexicos.html#card) 

**Objetivo:** Compartilhar um [Card](lexicos.html#card)  do Trello. 

**Contexto:**
- **Pré-condição:**  O [Usuário]() precisará possuir um dispositivo com acesso a internet, estar logado em sua conta Trello e possuir um [Card](lexicos.html#card)  em uma [Lista](lexicos.html#lista). 
- **Pós-condição:** : O [Usuário]() terá compartilhado um [Card](lexicos.html#card) . 

**Atores:** [Usuário]()

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() entra na tela onde tem o [Card](lexicos.html#card)  desejado. 
- [Usuário]() clica no [Card](lexicos.html#card) . 
- [Usuário]() clica na opção ‘Compartilhar e mais...’. 
- [Usuário]() escolhe como deseja compartilhar o [Card](lexicos.html#card) . 
- Ao selecionar uma das opções, o [Usuário]() terá um referencial do [Card](lexicos.html#card) de acordo com a opção escolhida. 

------------
## Cenário de Exibir detalhes do card

**Título:** Exibir detalhes do [Card](lexicos.html#card) 

**Objetivo:** Exibir detalhes de um [Card](lexicos.html#card)  do Trello. 

**Contexto:**
- **Pré-condição:**  O [Usuário]() precisará possuir um dispositivo com acesso a internet, estar logado em sua conta Trello e possuir um [Card](lexicos.html#card)  em uma [Lista](lexicos.html#lista). 
- **Pós-condição:** : O usuário terá visualizado detalhes do [Card](lexicos.html#card) . 

**Atores:** [Usuário]()

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário]() entra na tela onde tem o [Card](lexicos.html#card)  desejado. 
- [Usuário]() clica no [Card](lexicos.html#card) .
- [Usuário]() terá aberto os detalhes do [Card](lexicos.html#card) .

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
