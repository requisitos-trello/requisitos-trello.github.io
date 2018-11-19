---
layout: default
title: Cenários
category: Modelagem
---

[Lista de Autores do artefato](/artefatos.html)

# Cenários

------------
## CN01 Cenário de Login

**Título:** [Login](lexicos.html#lx17-login)  comum 

**Objetivo:** Logar em uma conta do trello.

**Contexto:**
- **Pré-condição:** O [usuário](lexicos.html#lx16-usuário) precisará possuir uma conta na plataforma Trello e
possuir um dispositivo com acesso a internet.
- **Pós-condição:** O [usuário](lexicos.html#lx16-usuário) estará logado na aplicação, com acesso a seus
[Boards](lexicos.html#lx01-board)

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Dispositivo com acesso a um navegador ou ao aplicativo Trello, ambos devem
possuir conexão a internet.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) entra na tela de [Login](lexicos.html#lx17-login)  da aplicação;
- [Usuário](lexicos.html#lx16-usuário) insere o endereço de e-mail de sua conta;
- [Usuário](lexicos.html#lx16-usuário) insere a senha de sua conta;
- [Usuário](lexicos.html#lx16-usuário) clica no botão ‘Fazer [Login](lexicos.html#lx17-login) ’;
- [Usuário](lexicos.html#lx16-usuário) estará logado na aplicação.

------------
## CN02 Cenário de Login com o Google

**Título:** [Login](lexicos.html#lx17-login) com o Google

**Objetivo:** Logar no Trello através de sua conta Google.

**Contexto:**
- **Pré-condição:** ​ O [usuário](lexicos.html#lx16-usuário) precisará possuir uma conta Google e possuir um
dispositivo com acesso a internet.
- **Pós-condição:** O [usuário](lexicos.html#lx16-usuário) estará logado na aplicação, com acesso a seus
[Boards](lexicos.html#lx01-board)

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Dispositivo com acesso a um navegador ou ao aplicativo Trello, ambos devem
possuir conexão a internet.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) entra na tela de [Login](lexicos.html#lx17-login)  da aplicação;
- [Usuário](lexicos.html#lx16-usuário) clica em ‘Fazer [Login](lexicos.html#lx17-login)  com o Google’;
- [Usuário](lexicos.html#lx16-usuário) insere o endereço de e-mail ou telefone;
- [Usuário](lexicos.html#lx16-usuário) clica no botão ‘Próxima’;
- [Usuário](lexicos.html#lx16-usuário) insere a senha;
- [Usuário](lexicos.html#lx16-usuário) clica no botão ‘Próxima’;
- [Usuário](lexicos.html#lx16-usuário) estará logado na aplicação.

------------
## CN03 Cenário de Cadastro

**Título:** Cadastrar no Trello.

**Objetivo:** Cadastrar uma nova conta na plataforma Trello.

**Contexto:**
- **Pré-condição:** O [usuário](lexicos.html#lx16-usuário) precisará possuir um dispositivo com acesso a
internet e um e-mail não cadastrado no sistema do Trello.
- **Pós-condição:** O [usuário](lexicos.html#lx16-usuário) terá cadastrado uma nova conta e
automaticamente estará logado na aplicação.

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Dispositivo com acesso a um navegador ou ao aplicativo Trello, ambos devem
possuir conexão a internet.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) entra na tela de cadastro da aplicação;
- [Usuário](lexicos.html#lx16-usuário) insere o seu nome;
- [Usuário](lexicos.html#lx16-usuário) insere o endereço de e-mail desejado;
- [Usuário](lexicos.html#lx16-usuário) insere a senha desejada;
- [Usuário](lexicos.html#lx16-usuário) clica no botão ‘Criar Nova Conta’;
- [Usuário](lexicos.html#lx16-usuário) estará cadastrado e logado na aplicação.

------------
## CN04 Cenário de Alterar Senha

**Título:**  ​Alterar senha.

**Objetivo:** Alterar senha de uma conta existente da plataforma Trello.

**Contexto:**
- **Pré-condição:** O [usuário](lexicos.html#lx16-usuário) precisará possuir um dispositivo com acesso a
internet e uma conta cadastrada no sistema do Trello.
- **Pós-condição:** O [usuário](lexicos.html#lx16-usuário) terá alterado a senha de sua conta.

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Dispositivo com acesso a um navegador ou ao aplicativo Trello, ambos devem
possuir conexão a internet.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) entra na tela de ’Esqueceu sua senha?’;
- [Usuário](lexicos.html#lx16-usuário) insere o endereço de e-mail de sua conta;
- [Usuário](lexicos.html#lx16-usuário) clica no botão ‘Enviar’;
- [Usuário](lexicos.html#lx16-usuário) recebe um e-mail para redefinir sua senha;
- [Usuário](lexicos.html#lx16-usuário) abre o e-mail recebido;
- [Usuário](lexicos.html#lx16-usuário) clica no botão ‘Redefinir Senha’;
- [Usuário](lexicos.html#lx16-usuário) insere a nova senha;
- [Usuário](lexicos.html#lx16-usuário) insere a nova senha novamente;
- [Usuário](lexicos.html#lx16-usuário) clica no botão ‘Enviar’.

------------
## CN05 Cenário alterar configurações de Notificação

**Título:**  ​Alterar configurações de [Notificação](lexicos.html#lx14-notificar).

**Objetivo:** ​Alterar configurações de [Notificação](lexicos.html#lx14-notificar) da sua conta Trello.

**Contexto:**
- **Pré-condição:** O [usuário](lexicos.html#lx16-usuário) precisará possuir um dispositivo com acesso a
internet e estar logado em sua conta Trello.
- **Pós-condição:** O [usuário](lexicos.html#lx16-usuário) terá alterado as configurações de [Notificação](lexicos.html#lx14-notificar) de
sua conta.

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Dispositivo com acesso a um navegador ou ao aplicativo Trello, ambos devem
possuir conexão a internet.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) entra na tela em suas notificações;
- [Usuário](lexicos.html#lx16-usuário) clica em ‘Alterar Frequência de [Notificação](lexicos.html#lx14-notificar) por Email’;
- [Usuário](lexicos.html#lx16-usuário) seleciona uma das três opções: Nunca, Periodicamente e
Instantaneamente;
- [Usuário](lexicos.html#lx16-usuário) terá alterado a frequência de notificações por e-mail;
- [Usuário](lexicos.html#lx16-usuário) clica em ‘Permitir [Notificação](lexicos.html#lx14-notificar) da Área de Trabalho’;
- [Usuário](lexicos.html#lx16-usuário) terá permitido a aplicação a exibir [Notificação](lexicos.html#lx14-notificar) da Área de Trabalho.

------------
## CN06 Cenário ver notificações

**Título:**  ​Ver [Notificações](lexicos.html#lx14-notificar).

**Objetivo:** ​Ver [Notificações](lexicos.html#lx14-notificar) da sua conta Trello.

**Contexto:**
- **Pré-condição:** O [usuário](lexicos.html#lx16-usuário) precisará possuir um dispositivo com acesso a
internet e estar logado em sua conta Trello.
- **Pós-condição:** O [usuário](lexicos.html#lx16-usuário) terá visto as [Notificações](lexicos.html#lx14-notificar) de sua conta, caso
exista.

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Dispositivo com acesso a um navegador ou ao aplicativo Trello, ambos devem
possuir conexão a internet.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) abre a página inicial;
- [Usuário](lexicos.html#lx16-usuário) clica na imagem de um sino na parte superior direita de sua tela;
- [Usuário](lexicos.html#lx16-usuário) entra na tela de suas [Notificações](lexicos.html#lx14-notificar);
- [Usuário](lexicos.html#lx16-usuário) vê suas [Notificações](lexicos.html#lx14-notificar), caso exista alguma notificação não lida.

------------
## CN07 Cenário criar time

**Título:** ​Criar [Time](lexicos.html#lx11-time).

**Objetivo:** ​Criar um [Time](lexicos.html#lx11-time) na plataforma Trello.

**Contexto:**
- **Pré-condição:** ​ O [usuário](lexicos.html#lx16-usuário) precisará possuir um dispositivo com acesso a
internet e estar logado em sua conta Trello.
- **Pós-condição:** ​O [usuário](lexicos.html#lx16-usuário) terá criado um novo [Time](lexicos.html#lx11-time).

**Atores:** ​[Usuário](lexicos.html#lx16-usuário).

**Recursos:** ​Dispositivo com acesso a um navegador ou ao aplicativo Trello, ambos devem
possuir conexão a internet.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) abre a página inicial;
- [Usuário](lexicos.html#lx16-usuário) clica em ‘Criar um time’;
- [Usuário](lexicos.html#lx16-usuário) insere o nome do [Time](lexicos.html#lx11-time);
- [Usuário](lexicos.html#lx16-usuário) insere a descrição do [Time](lexicos.html#lx11-time) (opcional);
- [Usuário](lexicos.html#lx16-usuário) clica no botão ‘Criar’;
- [Usuário](lexicos.html#lx16-usuário) terá criado um novo [Time](lexicos.html#lx11-time).

------------
## CN08 Cenário convidar Usuários para um time

**Título:** ​Convidar [Usuários](lexicos.html#lx16-usuário) para um [Time](lexicos.html#lx11-time).

**Objetivo:** ​Convidar [Usuários](lexicos.html#lx16-usuário) da plataforma Trello para participar de um [Time](lexicos.html#lx11-time).

**Contexto:**
- **Pré-condição:** ​ O  [usuário](lexicos.html#lx16-usuário)precisará possuir um dispositivo com acesso a
internet e estar logado em sua conta Trello.
- **Pós-condição:** ​O  [usuário](lexicos.html#lx16-usuário)terá convidado um ou mais [Usuários](lexicos.html#lx16-usuário) para seu [Time](lexicos.html#lx11-time).

**Atores:** [Usuário](lexicos.html#lx16-usuário)​

**Recursos:** ​Dispositivo com acesso a um navegador ou ao aplicativo Trello, ambos devem
possuir conexão a internet.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) abre a página do [Time](lexicos.html#lx11-time);
- [Usuário](lexicos.html#lx16-usuário) clica no botão ‘Membros’;
- [Usuário](lexicos.html#lx16-usuário) insere o nome do  [usuário](lexicos.html#lx16-usuário)a ser convidado;
- [Usuário](lexicos.html#lx16-usuário) clica no botão ‘Convidar para o Time’;
- [Usuário](lexicos.html#lx16-usuário) terá convidado um [usuário](lexicos.html#lx16-usuário) para seu [Time](lexicos.html#lx11-time).

------------
## CN09 Cenário de imprimir Board

**Título:** Impressão de [Board](lexicos.html#lx01-board) 

**Objetivo:** Passar algumas informações de à [Board](lexicos.html#lx01-board) para uma folha de papel.

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#lx16-usuário) deve ter acesso à [Board](lexicos.html#lx01-board) que quer imprimir.
- **Pós-condição:** A aplicação deverá comunicar ao browser que uma impressão está sendo solicitada.

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Dispositivo desktop com browser compatível com os recursos do Trello e com acesso à impressora, além da impressora devidamente preparada para impressão.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) realiza [Login](lexicos.html#lx17-login) ;
- [Usuário](lexicos.html#lx16-usuário) acessa a [Board](lexicos.html#lx01-board) desejada;
- [Usuário](lexicos.html#lx16-usuário) abre o [Menu lateral]();
- [Usuário](lexicos.html#lx16-usuário) seleciona a opção **Mais**;
- [Usuário](lexicos.html#lx16-usuário) seleciona a opção **Imprimir e Exportar**;
- [Usuário](lexicos.html#lx16-usuário) seleciona a opção **Imprimir...**;
- A aplicação converte a [Board](lexicos.html#lx01-board) para um formato imprimível;
- Browser faz a comunicação com o Sistema Operacional, que por sua vez comunica-se com a impressora.

--------------
## CN10 Cenário de adicionar [Stickers](lexicos.html#lx12-sticker)

**Título:** Adição de [Stickers](lexicos.html#lx12-sticker)

**Objetivo:** Adição de elementos visuais que facilitem a orientação intuitiva e visual do [Usuário](lexicos.html#lx16-usuário) pela [Board](lexicos.html#lx01-board).

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#lx16-usuário) deve ter acesso à [Board](lexicos.html#lx01-board) na qual quer adicionar [stickers](lexicos.html#lx12-sticker).
- **Pós-condição:** Um [sticker](lexicos.html#lx12-sticker) deve ser adicionado a um [Card](lexicos.html#lx03-card) na [Board](lexicos.html#lx01-board) em questão.

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Acesso à aplicação web por meio de browser em um dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) faz [Login](lexicos.html#lx17-login) ;
- [Usuário](lexicos.html#lx16-usuário) acessa a [Board](lexicos.html#lx01-board) desejada;
- [Usuário](lexicos.html#lx16-usuário) abre o [Menu Lateral]();
- [Usuário](lexicos.html#lx16-usuário) seleciona a opção **[Stickers](lexicos.html#lx12-sticker)**;
- [Usuário](lexicos.html#lx16-usuário) clica e arrasta o Sticker desejado até o [Card](lexicos.html#lx03-card) desejado;

--------------
## CN11 Cenário de editar/remover [Stickers](lexicos.html#lx12-sticker)

**Título:** Edição de [Stickers](lexicos.html#lx12-sticker)

**Objetivo:** Tornar possível editar a posição ou a exclusão de um [sticker](lexicos.html#lx12-sticker) existente num [card](lexicos.html#lx03-card)

**Contexto:**
- **Pré-condição:** Deve existir um [sticker](lexicos.html#lx12-sticker) em uma [Board](lexicos.html#lx01-board) com o acesso do [Usuário](lexicos.html#lx16-usuário) que queira remover ou editar este mesmo [sticker](lexicos.html#lx12-sticker).
- **Pós-condição:** O [sticker](lexicos.html#lx12-sticker) será movido para a nova posição, caso tenha sido movido. Caso removido, o [sticker](lexicos.html#lx12-sticker) deixará de existir.

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) faz [Login](lexicos.html#lx17-login) ;
- [Usuário](lexicos.html#lx16-usuário) acessa a [Board](lexicos.html#lx01-board) em questão;
- [Usuário](lexicos.html#lx16-usuário) clica com o botão direito do mouse no [Card](lexicos.html#lx03-card)  de onde quer mover o [sticker](lexicos.html#lx12-sticker);
- [Usuário](lexicos.html#lx16-usuário) clica com o botão esquerdo do mouse no [sticker](lexicos.html#lx12-sticker) que quer editar;
- [Usuário](lexicos.html#lx16-usuário) seleciona uma das opções: **Girar**, **Mover** ou **Remover** segundo sua vontade;
- Em caso de **Girar** ou **Mover**, o [Usuário](lexicos.html#lx16-usuário) clica e segura com o botão esquerdo do mouse, movendo o cursos até que o [sticker](lexicos.html#lx12-sticker) alcance a posição desejada;

**Exceção:** Falta de conexão com a internet após tentar adicionar o [sticker](lexicos.html#lx12-sticker), queda de energia.

--------------
## CN12 Cenário de Alterar Tela de Fundo

**Título:** Alteração da Tela de Fundo de uma [Board](lexicos.html#lx01-board)

**Objetivo:** Possibilitar a personalização da [Board](lexicos.html#lx01-board) pelo [Usuário](lexicos.html#lx16-usuário) por meio de uma imagem de fundo nova de sua escolha.

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#lx16-usuário) deve ter acesso à [Board](lexicos.html#lx01-board) a qual quer alterar o plano de fundo.
- **Pós-condição:** A tela de fundo dessa [Board](lexicos.html#lx01-board) será alterada.

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) faz [Login](lexicos.html#lx17-login) ;
- [Usuário](lexicos.html#lx16-usuário) acessa a [Board](lexicos.html#lx01-board) cujo plano quer alterar;
- [Usuário](lexicos.html#lx16-usuário) abre o [Menu Lateral]();
- [Usuário](lexicos.html#lx16-usuário) seleciona a opção **Alterar Tela de Fundo**;
- [Usuário](lexicos.html#lx16-usuário) seleciona entre as opções **Cores** ou **Fotos**;
    - Caso o [Board](lexicos.html#lx01-board) seja de um [time](lexicos.html#lx11-time) [Business Class](lexicos.html#lx05-business-class), a opção **Personalizar** também estará disponível;
- Caso tenha selecionado **Cores**, o [Usuário](lexicos.html#lx16-usuário) escolhe uma entre as nove cores disponíveis, ou clica na **seta à esqueda** para voltar à tela anterior;
- Caso tenha selecionado **Fotos**, o usário escollhe uma entre as inúmeras fotos disponibilizadas pelo Unsplash em colaboração com o Trello ou clica na **seta à esqueda** para voltar à tela anterior;
    - É possível pesquisar por termos e a aplicação retornará imagens marcadas com os termos pesquisados.

**Exceção:** Imagem inválida (tamanho grande ou pequeno demais ou extensão incompatível), queda de energia ou de queda de conexão com a internet.

--------------
## CN13 Cenário de Filtrar Cartões

**Título:** Pesquisa de [Cards](lexicos.html#lx03-card)

**Objetivo:** Pesquisa [cards](lexicos.html#lx03-card) em relação ao seu conteúdo de acordo com os termos de pesquisa inseridos.

**Contexto:**
- **Pré-condição:** Pesquisa realizada pelo [Usuário](lexicos.html#lx16-usuário) em uma [Board](lexicos.html#lx01-board) à qual o [Usuário](lexicos.html#lx16-usuário) tenha acesso.
- **Pós-condição:** Deverão aparecer na tela apenas os [cards](lexicos.html#lx03-card) que atendam às características solicitadas na pesquisa.

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) faz [Login](lexicos.html#lx17-login) ;
- [Usuário](lexicos.html#lx16-usuário) acessa a [Board](lexicos.html#lx01-board) onde estão os cards que ele procura;
- [Usuário](lexicos.html#lx16-usuário) abre o [Menu Lateral]() e seleciona a opção **Filtrar Cartões**;
    - [Usuário](lexicos.html#lx16-usuário) pode digitar termos contidos nos títulos dos cards que está procurando;
    - [Usuário](lexicos.html#lx16-usuário) pode selecionar [Etiquetas]() contidas nos cards que está procurando;
    - [Usuário](lexicos.html#lx16-usuário) pode [membro](lexicos.html#lx19-membro) assinalados nos cards que está procurando;
    - [Usuário](lexicos.html#lx16-usuário) pode selecionar opções de [data de entrega](lexicos.html#lx13-duedate):
        - Entregas em um dia;
        - Entregas em uma semana;
        - Entregas emm um mês;
        - Em atraso;
        - Sem [data de entrega](lexicos.html#lx13-duedate);
        - [Data de entrega](lexicos.html#lx13-duedate) marcada como concluída;
        - Não marcado como concluído;
    - [Usuário](lexicos.html#lx16-usuário) pode selecionar se as buscas por etiquetas e [membros](lexicos.html#lx19-membro) seguem lógica AND (todos os [membros](lexicos.html#lx19-membro) e etiquetas procurados devem estar contido nos cards procurados) ou se seguem lógica OR (qualquer [Card](lexicos.html#lx03-card) que contenha um membro ou etiqueta procurados se enquadra na pesquisa).
- Aparece um texto na parte superior da [Board](lexicos.html#lx01-board) indicando que a busca está ativada e, por isso, alguns cards podem estar sendo omitidos;
    - Para encerrar a filtragem, o [Usuário](lexicos.html#lx16-usuário) pode clicar no X ao lado deste texto.

--------------
## CN14 Cenário de [Copiar](lexicos.html#lx15-copiar) um Quadro

**Título:** Cópia de [Board](lexicos.html#lx01-board)

**Objetivo:** Criação de um [Board](lexicos.html#lx01-board) com algumas características iguais às de um [Board](lexicos.html#lx01-board) específico.

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#lx16-usuário) deve ter acesso à [Board](lexicos.html#lx01-board) que quer [copiar](lexicos.html#lx15-copiar).
- **Pós-condição:** Será criada uma nova [Board](lexicos.html#lx01-board) com algumas características trazidas de outra.

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) faz [Login](lexicos.html#lx17-login) ;
- [Usuário](lexicos.html#lx16-usuário) acessa a [Board](lexicos.html#lx01-board) que quer [copiar](lexicos.html#lx15-copiar);
- [Usuário](lexicos.html#lx16-usuário) abre o [Menu Lateral]() e seleciona a opção **Mais**;
- [Usuário](lexicos.html#lx16-usuário) seleciona a opção **Copiar Quadro**;
- [Usuário](lexicos.html#lx16-usuário) digita um título para o novo [Board](lexicos.html#lx01-board) que será criado;
- Opcionalmente, o [Usuário](lexicos.html#lx16-usuário) escolhe um [time](lexicos.html#lx11-time) do qual faça parte para popular o novo quadro;
- [Usuário](lexicos.html#lx16-usuário) decide a visibilidade do quadro (se é particular, de visibilidade apenas do [time](lexicos.html#lx11-time) ou se é público);
- [Usuário](lexicos.html#lx16-usuário) decide se quer [copiar](lexicos.html#lx15-copiar), também, os [Cards]() contidos no [Board](lexicos.html#lx01-board) atual.
- É criada uma nova [Board](lexicos.html#lx01-board);
 
--------------
## CN15 Cenário de Seguir Quadro

**Título:** [Seguir]() uma [Board](lexicos.html#lx01-board)

**Objetivo:** Ser [notificado](lexico.html#notificar) de alterações que aconteçam em uma [Board](lexicos.html#lx01-board)

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#lx16-usuário) deve ter acesso à [Board](lexicos.html#lx01-board) que quer seguir.
- **Pós-condição:** O [Usuário](lexicos.html#lx16-usuário) será [notificado](lexico.html#notificar) de alterações que ocorrerem na [Board](lexicos.html#lx01-board) em questão.

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop ou acesso aplicação mobile conectada à internet.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) faz [Login](lexicos.html#lx17-login) ;
- [Usuário](lexicos.html#lx16-usuário) acessa a [Board](lexicos.html#lx01-board) que quer seguir;
- [Usuário](lexicos.html#lx16-usuário) abre o [Menu Lateral]() e seleciona a opção **Seguir**;
- O sistema passa a [notificar](lexico.html#notificar) o [Usuário](lexicos.html#lx16-usuário) em seu e-mail e no espaço de [notificações](lexico.html#notificar) do Trello;
- Aparece um texto no canto superior esquerdo da [Board](lexicos.html#lx01-board) indicando que o [Usuário](lexicos.html#lx16-usuário) está seguindo esta [Board](lexicos.html#lx01-board).
- O [Usuário](lexicos.html#lx16-usuário) pode selecionar novamente a opção **Seguir** para parar de seguir, ou clicar no texto recém-aparecido que ascenderá um botão **Parar de seguir**.

--------------
## CN16 Cenário de Fechar um Quadro

**Título:** Fechamento de [Board](lexicos.html#lx01-board)

**Objetivo:** Enviar a [Board](lexicos.html#lx01-board) para um espaço equivalente à lixeira, onde não são imediatamente excluídos mas não mais dividem espaço com outras[Boards](lexicos.html#lx01-board).

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#lx16-usuário) deve ser criador do [Board](lexicos.html#lx01-board) que quer fechar.
- **Pós-condição:** O [Board](lexicos.html#lx01-board) deve sair do espaço de[Boards](lexicos.html#lx01-board) do [Usuário](lexicos.html#lx16-usuário), sem necessariamente ser excluído.

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) faz [Login](lexicos.html#lx17-login) ;
- [Usuário](lexicos.html#lx16-usuário) acessa a [Board](lexicos.html#lx01-board) que deseja fechar;
- [Usuário](lexicos.html#lx16-usuário) abre o [Menu Lateral]() e seleciona a opção **Mais**;
- [Usuário](lexicos.html#lx16-usuário) seleciona a opção **Fechar Quadro...**;
- [Usuário](lexicos.html#lx16-usuário) clica no botão vermelhor **Fechar**;

------------
## CN17 Cenário de Exportar um Quadro para JSON

**Título:** Exportação de [Board](lexicos.html#lx01-board) para JSON 

**Objetivo:** Passar algumas informações de à [Board](lexicos.html#lx01-board) para o formato JSON.

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#lx16-usuário) deve ter acesso à [Board](lexicos.html#lx01-board) que quer exportar.
- **Pós-condição:** A aplicação deverá retornar um código JSON que reflita o atual estado da [Board](lexicos.html#lx01-board).

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) realiza [Login](lexicos.html#lx17-login) ;
- [Usuário](lexicos.html#lx16-usuário) acessa a [Board](lexicos.html#lx01-board) desejada;
- [Usuário](lexicos.html#lx16-usuário) abre o [Menu lateral]();
- [Usuário](lexicos.html#lx16-usuário) seleciona a opção **Mais**;
- [Usuário](lexicos.html#lx16-usuário) seleciona a opção **Imprimir e Exportar**;
- [Usuário](lexicos.html#lx16-usuário) seleciona a opção **Exportar como JSON**;
- A aplicação redireciona para uma página que contém apenas o código JSON da [Board](lexicos.html#lx01-board);

------------
## CN18 Cenário de Retirar Membros de um [Time](lexicos.html#lx11-time)

**Título:** Retirar [membros](lexicos.html#lx19-membro) de um [time](lexicos.html#lx11-time).

**Objetivo:** Com isto é possível remover um membro de um [time](lexicos.html#lx11-time).

**Contexto:**
- **Pré-condição:** O [usuário](lexicos.html#lx16-usuário) deve ser [administrador](lexicos.html#lx04-administrador) do [Time](lexicos.html#lx11-time) e deve ter ao menos um membro além do [administrador](lexicos.html#lx04-administrador).
- **Pós-condição:** [Usuário](lexicos.html#lx16-usuário) retirado deixará de ser membro do [time](lexicos.html#lx11-time).

**Atores:** [Administrador](lexicos.html#lx04-administrador) do [time](lexicos.html#lx11-time), membro do [time](lexicos.html#lx11-time).

**Recursos:** Conta, [time](lexicos.html#lx11-time), membro, computador, internet.

**Episódios:**
- [Administrador](lexicos.html#lx04-administrador) entra no Trello.
- [Administrador](lexicos.html#lx04-administrador) realiza [Login](lexicos.html#lx17-login).
- Se há [time](lexicos.html#lx11-time), [Administrador](lexicos.html#lx04-administrador) acessa [time](lexicos.html#lx11-time).
- Senão, fluxo encerrado. (exceção)
- [Administrador](lexicos.html#lx04-administrador) acessa [Lista](lexicos.html#lx02-lista) de [membros](lexicos.html#lx19-membro).
- Se há [membros](lexicos.html#lx19-membro), [Administrador](lexicos.html#lx04-administrador) EXCLUI MEMBRO que deseja.
- Senão, fluxo encerrado. (exceção)


------------
## CN19 Cenário de Editar Descrição de [Time](lexicos.html#lx11-time)

**Título:** Editar descrição de [time](lexicos.html#lx11-time).

**Objetivo:** Permite editar o texto atual da descrição de um [time](lexicos.html#lx11-time) a qual o [Usuário](lexicos.html#lx16-usuário) tenha acesso.

**Contexto:**
- **Pré-condição:** O [usuário](lexicos.html#lx16-usuário) deve ser [administrador](lexicos.html#lx04-administrador) do [time](lexicos.html#lx11-time).
- **Pós-condição:** O [time](lexicos.html#lx11-time) deverá possuir uma nova descrição.

**Atores:** [Administrador](lexicos.html#lx04-administrador) do [time](lexicos.html#lx11-time).

**Recursos:** Conta, [time](lexicos.html#lx11-time), computador, internet.

**Restrição:** O [time](lexicos.html#lx11-time) deve existir, o [usuário](lexicos.html#lx16-usuário) deve ser [administrador](lexicos.html#lx04-administrador) do [time](lexicos.html#lx11-time).

**Exceção:** Queda de energia, falta de conexão com a internet ou [usuário](lexicos.html#lx16-usuário) não pertence mais ao [time](lexicos.html#lx11-time)

**Episódios:**
- [Administrador](lexicos.html#lx04-administrador) entra no Trello.
- [Administrador](lexicos.html#lx04-administrador) realiza [Login](lexicos.html#lx17-login).
- Se há [time](lexicos.html#lx11-time), [Administrador](lexicos.html#lx04-administrador) acessa time.
- Senão, fluxo encerrado. (Exceção)
- [Administrador](lexicos.html#lx04-administrador) acessa editar perfil.
- [Administrador](lexicos.html#lx04-administrador) edita descrição do [time](lexicos.html#lx11-time).


------------
## CN20 Cenário de Editar Visibilidade do [Time](lexicos.html#lx11-time)

**Título:** Editar visibilidade do [time](lexicos.html#lx11-time).

**Objetivo:** Permite restringir ou habilitar a visualisação do [time](lexicos.html#lx11-time) a um ou mais [Usuários](lexicos.html#lx16-usuário) que pertençam à [board](lexicos.html#lx01-board) a fim de preservar a privacidade dos [usuários](lexicos.html#lx16-usuário) de um [time](lexicos.html#lx11-time).

**Contexto:**
- **Pré-condição:** O [usuário](lexicos.html#lx16-usuário) deve ser [administrador](lexicos.html#lx04-administrador) do [time](lexicos.html#lx11-time).
- **Pós-condição:** O [time](lexicos.html#lx11-time) deverá ter sua visibilidade alterada.

**Atores:** [Administrador](lexicos.html#lx04-administrador) do [time](lexicos.html#lx11-time).

**Recursos:** Conta, [time](lexicos.html#lx11-time), computador, internet.

**Exceção:** Queda de energia, falta de conexão com a internet.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) entra no Trello.
- [Usuário](lexicos.html#lx16-usuário) realiza [Login](lexicos.html#lx17-login).
- Se há [time](lexicos.html#lx11-time), [Usuário](lexicos.html#lx16-usuário) acessa time.
- Senão, fluxo encerrado.  (exceção)
- [Usuário](lexicos.html#lx16-usuário) acessa configurações do time.
- [Usuário](lexicos.html#lx16-usuário) acessa alterar visibilidade do time.
- [Usuário](lexicos.html#lx16-usuário) edita visibilidade do [time](lexicos.html#lx11-time).


------------
## CN21 Cenário de [Vincular](lexicos.html#lx18-vincular) [Time](lexicos.html#lx11-time) ao Slack

**Título:** [Vinculação](lexicos.html#lx18-vincular) [Time](lexicos.html#lx11-time) ao Slack.

**Objetivo:** Adicionar interoperabilidade entre o [Time](lexicos.html#lx11-time) e a plataforma Slack, habilidando o compartilhamento de dados entre ambas.

**Contexto:**
- **Pré-condição:** O [usuário](lexicos.html#lx16-usuário) deve ser [administrador](lexicos.html#lx04-administrador) do [time](lexicos.html#lx11-time).
- **Pós-condição:** O [time](lexicos.html#lx11-time) deverá ser vinculado a [time](lexicos.html#lx11-time) do Slack.

**Atores:** [Administrador](lexicos.html#lx04-administrador) do [time](lexicos.html#lx11-time).

**Recursos:** Conta, [time](lexicos.html#lx11-time), computador, internet.

**Restrição:** [Administrador](lexicos.html#lx04-administrador) deve possuir conta e canal no slack.

**Exceção:** Não há [time](lexicos.html#lx11-time), não há conta nem canal no slack.

**Episódios:**
- [Administrador](lexicos.html#lx04-administrador) entra no Trello.
- [Administrador](lexicos.html#lx04-administrador) realiza [Login](lexicos.html#lx17-login).
- Se há [time](lexicos.html#lx11-time), [Administrador](lexicos.html#lx04-administrador) acecssa time.
- Senão, [Administrador](lexicos.html#lx04-administrador) cria time. (restrição)
- [Administrador](lexicos.html#lx04-administrador) acessa configurações do time.
- [Administrador](lexicos.html#lx04-administrador) acessa ADD TO SLACK.
- Se há conta no slack, [Administrador](lexicos.html#lx04-administrador) realiza [Login](lexicos.html#lx17-login) em sua conta do slack.
- Senão [Administrador](lexicos.html#lx04-administrador) cria conta no slack.
- Se há canal no slack do [Administrador](lexicos.html#lx04-administrador), [Administrador](lexicos.html#lx04-administrador) [VINCULA](lexicos.html#lx18-vincular) TIME COM O SLACK.
- Senão [Administrador](lexicos.html#lx04-administrador) cria canal no slack e realiza o passo anterior.


------------
## CN22 Cenário de Permitir Membro Comentar em um [Board](lexicos.html#lx01-board) 

**Título:** Permitir membro comentar em um [Board](lexicos.html#lx01-board).

**Objetivo:** Permitir a alteração das permissões de membro com relação a comentar em um [Board](lexicos.html#lx01-board).

**Contexto:** 
- **Pré-condição:** O [usuário](lexicos.html#lx16-usuário) deve ser [administrador](lexicos.html#lx04-administrador) do [time](lexicos.html#lx11-time).
- **Pós-condição:** Membros poderão comentar em um [Board](lexicos.html#lx01-board).

**Atores:** [Administrador](lexicos.html#lx04-administrador) do [time](lexicos.html#lx11-time).

**Recursos:** Conta, [time](lexicos.html#lx11-time), [Board](lexicos.html#lx01-board), [Lista](lexicos.html#lx02-lista), card, comentário, computador, internet.

**Episódios:**
- [Administrador](lexicos.html#lx04-administrador) entra no Trello.
- [Administrador](lexicos.html#lx04-administrador) realiza [Login](lexicos.html#lx17-login).
- Se há [time](lexicos.html#lx11-time), [Administrador](lexicos.html#lx04-administrador) acessa time.
- Senão, [Administrador](lexicos.html#lx04-administrador) cria time. (restrição)
- Se há [Board](lexicos.html#lx01-board), [Administrador](lexicos.html#lx04-administrador) acessa[board](lexicos.html#lx01-board) do [time](lexicos.html#lx11-time).
- Senão, [Administrador](lexicos.html#lx04-administrador) cria [board](lexicos.html#lx01-board) do [time](lexicos.html#lx11-time).
- [Administrador](lexicos.html#lx04-administrador) acessa menu da [Board](lexicos.html#lx01-board).
- [Administrador](lexicos.html#lx04-administrador) acessa mais opções do menu.
- [Administrador](lexicos.html#lx04-administrador) acessa configurações.
- [Administrador](lexicos.html#lx04-administrador) acessa permissões para comentários.
- [Administrador](lexicos.html#lx04-administrador) seleciona [membros](lexicos.html#lx19-membro).


------------
## CN23 Cenário de Negar [Membro](lexicos.html#lx19-membro) Ingressar em um [Board](lexicos.html#lx01-board) 

**Título:** Negar [membro](lexicos.html#lx19-membro) ingressar em um [Board](lexicos.html#lx01-board).

**Objetivo:** Altera a permissão de um [membro](lexicos.html#lx19-membro) de time de ingressar em um [Board](lexicos.html#lx01-board).

**Contexto:** 
- **Pré-condição:** O [usuário](lexicos.html#lx16-usuário) deve ser [administrador](lexicos.html#lx04-administrador) do [time](lexicos.html#lx11-time).
- **Pós-condição:** [membro](lexicos.html#lx19-membro)s não poderão ingressar em um [Board](lexicos.html#lx01-board) sem serem convidados.

**Atores:** [Administrador](lexicos.html#lx04-administrador) do [time](lexicos.html#lx11-time).

**Recursos:** Conta, [time](lexicos.html#lx11-time), computador, internet.

**Episódios:**
- [Administrador](lexicos.html#lx04-administrador) entra no Trello.
- [Administrador](lexicos.html#lx04-administrador) realiza [Login](lexicos.html#lx17-login).
- Se há [time](lexicos.html#lx11-time), [Administrador](lexicos.html#lx04-administrador) acessa time.
- Senão, [Administrador](lexicos.html#lx04-administrador) CRIA TIME. (restrição)
- Se há [Board](lexicos.html#lx01-board), [Administrador](lexicos.html#lx04-administrador) acessa [board](lexicos.html#lx01-board) do [time](lexicos.html#lx11-time).
- Senão, [Administrador](lexicos.html#lx04-administrador) cria [board](lexicos.html#lx01-board) do [time](lexicos.html#lx11-time). (restrição)
- [Administrador](lexicos.html#lx04-administrador) acessa menu da [Board](lexicos.html#lx01-board).
- [Administrador](lexicos.html#lx04-administrador) acessa mais opções do menu.
- [Administrador](lexicos.html#lx04-administrador) acessa configurações.
- Se estiver ativo, [Administrador](lexicos.html#lx04-administrador) clica em permitir ingresso de [membros](lexicos.html#lx19-membro) do time.
- Senão, a permissão já foi negada.

## CN24 Cenário de Ver [Lista](lexicos.html#lx02-lista)

**Título:** Ver [Lista](lexicos.html#lx02-lista) 

**Objetivo:** Mostrar o conteúdo de uma [Lista](lexicos.html#lx02-lista) para o [Usuário](lexicos.html#lx16-usuário).

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#lx16-usuário) deve ter acesso à [Lista](lexicos.html#lx02-lista) que quer visualizar.
- **Pós-condição:** A aplicação deverá mostrar a [Lista](lexicos.html#lx02-lista) para o [Usuário](lexicos.html#lx16-usuário).

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Restrições** 

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) realiza [LOGIN](#cenário-de-login);
- Se não há [Board](lexicos.html#lx01-board), [Usuário](lexicos.html#lx16-usuário) realiza [CRIAR BOARD](#criar-board);
- [Usuário](lexicos.html#lx16-usuário) realiza [VER BOARD](#ver-um-board);
- Se não há [Lista](lexicos.html#lx02-lista), [Usuário](lexicos.html#lx16-usuário) realiza [CRIAR LISTA](#cenário-de-criar-lista);
- [Usuário](lexicos.html#lx16-usuário) realiza [VER LISTA](#cenário-de-ver-lista);
- A aplicação mostra a [Lista](lexicos.html#lx02-lista) desejada para o [Usuário](lexicos.html#lx16-usuário).


------------
# Cards

## CN25 Cenário de Criar Card

**Título:** Criar [Card](lexicos.html#lx03-card)  

**Objetivo:** Criar um novo [Card](lexicos.html#lx03-card)  para armazenar dados dentro de uma [Lista](lexicos.html#lx02-lista).

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#lx16-usuário) deve ter acesso à [Lista](lexicos.html#lx02-lista) onde quer criar o [Card](lexicos.html#lx03-card) .
- **Pós-condição:** A aplicação deverá criar o [Card](lexicos.html#lx03-card)  dentro da [Lista](lexicos.html#lx02-lista) para o [Usuário](lexicos.html#lx16-usuário).

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) realiza [Login](lexicos.html#lx17-login);
- Se não há [Board](lexicos.html#lx01-board), [Usuário](lexicos.html#lx16-usuário) realiza [CRIAR BOARD](#criar-board);
- [Usuário](lexicos.html#lx16-usuário) realiza [VER BOARD](#ver-um-board);
- Se não há [Lista](lexicos.html#lx02-lista), [Usuário](lexicos.html#lx16-usuário) realiza [CRIAR LISTA](#cenário-de-criar-lista);
- [Usuário](lexicos.html#lx16-usuário) realiza [VER LISTA](#cenário-de-ver-lista);
- [Usuário](lexicos.html#lx16-usuário) realiza [CRIAR CARD](#cenário-de-criar-card)
- A aplicação mostra a [Lista](lexicos.html#lx02-lista) desejada para o [Usuário](lexicos.html#lx16-usuário).

------------
## CN26 Cenário de Modificar Card

**Título:** Modificar [Card](lexicos.html#lx03-card)  

**Objetivo:** Modificar um [Card](lexicos.html#lx03-card)  existente para atualizar os seus dados dentro de uma [Lista](lexicos.html#lx02-lista).

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#lx16-usuário) deve ter acesso à [Lista](lexicos.html#lx02-lista) onde está o [Card](lexicos.html#lx03-card) .
- **Pós-condição:** A aplicação deverá atualizar o [Card](lexicos.html#lx03-card)  com os novos dados.

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) realiza [Login](lexicos.html#lx17-login);
- Se não há [Board](lexicos.html#lx01-board), [Usuário](lexicos.html#lx16-usuário) realiza [CRIAR BOARD](#criar-board);
- [Usuário](lexicos.html#lx16-usuário) realiza [VER BOARD](#ver-um-board);
- Se não há [Lista](lexicos.html#lx02-lista), [Usuário](lexicos.html#lx16-usuário) realiza [CRIAR LISTA](cenário-de-criar-lista);
- [Usuário](lexicos.html#lx16-usuário) realiza [VER LISTA][cenário-de-ver-lista);
- Se não há [Card](lexicos.html#lx03-card) , [Usuário](lexicos.html#lx16-usuário), realiza [CRIAR CARD](#cenário-de-criar-card);
- [Usuário](lexicos.html#lx16-usuário) realiza [VER CARD](#cenário-de-criar-card);
- [Usuário](lexicos.html#lx16-usuário) realiza [MODIFICAR CARD](#cenário-de-modificar-card);
- A aplicação mostra uma janela de edição para o [Card](lexicos.html#lx03-card)  desejado para o [Usuário](lexicos.html#lx16-usuário).

------------
## CN27 Cenário de Ver Card

**Título:** Ver [Card](lexicos.html#lx03-card)  

**Objetivo:** Visualizar um [Card](lexicos.html#lx03-card)  existente para mostrar o seu conteúdo para o [Usuário](lexicos.html#lx16-usuário).

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#lx16-usuário) deve ter acesso à [Lista](lexicos.html#lx02-lista) onde está o [Card](lexicos.html#lx03-card) .
- **Pós-condição:** A aplicação deverá mostrar o [Card](lexicos.html#lx03-card)  com seu conteúdo.

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) realiza [Login](lexicos.html#lx17-login);
- Se não há [Board](lexicos.html#lx01-board), [Usuário](lexicos.html#lx16-usuário) realiza [CRIAR BOARD](#criar-board);
- [Usuário](lexicos.html#lx16-usuário) realiza [VER BOARD](#ver-um-board);
- Se não há [Lista](lexicos.html#lx02-lista), [Usuário](lexicos.html#lx16-usuário) realiza [CRIAR LISTA](#cenário-de-criar-lista);
- [Usuário](lexicos.html#lx16-usuário) realiza [VER LISTA](#cenário-de-ver-lista);
- Se não há [Card](lexicos.html#lx03-card) , [Usuário](lexicos.html#lx16-usuário), realiza [CRIAR CARD](#cenário-de-criar-card);
- [Usuário](lexicos.html#lx16-usuário) realiza [VER CARD](#cenário-de-ver-card);
- A aplicação mostra uma janela com os dados do [Card](lexicos.html#lx03-card)  desejado para o [Usuário](lexicos.html#lx16-usuário).

------------
## CN28 Cenário de Seguir Card

**Título:** Seguir [Card](lexicos.html#lx03-card)  

**Objetivo:** Seguir um [Card](lexicos.html#lx03-card)  existente para ser [notificado](lexico.html#notificar) de mudanças por meios de [notificações](lexico.html#notificar) para o [Usuário](lexicos.html#lx16-usuário).

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#lx16-usuário) deve ter acesso à [Lista](lexicos.html#lx02-lista) onde está o [Card](lexicos.html#lx03-card) .
- **Pós-condição:** A aplicação deverá [notificar](lexico.html#notificar) o [usuáro]() quando o [Card](lexicos.html#lx03-card)  for modificado.

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) realiza [Login](lexicos.html#lx17-login);
- Se não há [Board](lexicos.html#lx01-board), [Usuário](lexicos.html#lx16-usuário) realiza [CRIAR BOARD](#criar-um-board);
- [Usuário](lexicos.html#lx16-usuário) realiza [VER BOARD](#ver-um-board);
- Se não há [Lista](lexicos.html#lx02-lista), [Usuário](lexicos.html#lx16-usuário) realiza [CRIAR LISTA](#cenário-de-criar-lista);
- [Usuário](lexicos.html#lx16-usuário) realiza [VER LISTA](#cenário-de-ver-lista);
- Se não há [Card](lexicos.html#lx03-card) , [Usuário](lexicos.html#lx16-usuário), realiza [CRIAR CARD](#cenário-de-criar-card);
- [Usuário](lexicos.html#lx16-usuário) realiza [VER CARD](#cenário-de-ver-card);
- [Usuário](lexicos.html#lx16-usuário) realiza [SEGUIR CARD](#cenário-de-seguir-card) pressionando o botão seguir;
- A aplicação retorna à tela de [VER CARD](#cenário-de-ver-card).

------------
## CN29 Cenário de [Arquivar](lexicos.html#lx09-arquivar) Card

**Título:** [Arquivar](lexicos.html#lx09-arquivar) [Card](lexicos.html#lx03-card)  

**Objetivo:** [Arquivar](lexicos.html#lx09-arquivar) um [Card](lexicos.html#lx03-card)  existente para removê-lo de uma [Lista](lexicos.html#lx02-lista) sem perder seus dados.

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#lx16-usuário) deve ter acesso à [Lista](lexicos.html#lx02-lista) onde está o [Card](lexicos.html#lx03-card) .
- **Pós-condição:** A aplicação deverá [Arquivar](lexicos.html#lx09-arquivar) o [Card](lexicos.html#lx03-card)  selecionado.

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) realiza [Login](lexicos.html#lx17-login);
- Se não há [Board](lexicos.html#lx01-board), [Usuário](lexicos.html#lx16-usuário) realiza [CRIAR BOARD](#criar-board);
- [Usuário](lexicos.html#lx16-usuário) realiza [VER BOARD](#ver-um-board);
- Se não há [Lista](lexicos.html#lx02-lista), [Usuário](lexicos.html#lx16-usuário) realiza [CRIAR LISTA](#cenário-de-criar-lista);
- [Usuário](lexicos.html#lx16-usuário) realiza [VER LISTA](#cenário-de-ver-lista);
- Se não há [Card](lexicos.html#lx03-card) , [Usuário](lexicos.html#lx16-usuário), realiza [CRIAR CARD](#cenário-de-criar-card);
- [Usuário](lexicos.html#lx16-usuário) realiza [VER CARD](#cenário-de-ver-card);
- [Usuário](lexicos.html#lx16-usuário) realiza [ARQUIVAR CARD](#cenário-de-arquivar-card) pressionando o botão [Arquivar](lexicos.html#lx09-arquivar);
- A aplicação retorna à tela de [VER LISTA]().

------------
## CN30 Cenário de Personalizar [Label](lexicos.html#lx26-label)

**Título:** Personalizar [Label](lexicos.html#lx26-label) 

**Objetivo:** Personalizar a [Label](lexicos.html#lx26-label) atribuído à um [Card](lexicos.html#lx03-card) para diferenciar ou destacá-lo em relação aos outros.

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#lx16-usuário) deve ter acesso à [Lista](lexicos.html#lx02-lista) onde está o [Card](lexicos.html#lx03-card) .
- **Pós-condição:** A aplicação deverá mostrar o [Card](lexicos.html#lx03-card)  com seu novo [Label]().

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) realiza [Login](lexicos.html#lx17-login);
- Se não há [Board](lexicos.html#lx01-board), [Usuário](lexicos.html#lx16-usuário) realiza [CRIAR BOARD](#criar-board);
- [Usuário](lexicos.html#lx16-usuário) realiza [VER BOARD](#ver-um-board);
- Se não há [Lista](lexicos.html#lx02-lista), [Usuário](lexicos.html#lx16-usuário) realiza [CRIAR LISTA](#cenário-de-criar-lista);
- [Usuário](lexicos.html#lx16-usuário) realiza [VER LISTA](#cenário-de-ver-lista);
- Se não há [Card](lexicos.html#lx03-card) , [Usuário](lexicos.html#lx16-usuário), realiza [CRIAR CARD](#cenário-de-criar-card);
- [Usuário](lexicos.html#lx16-usuário) realiza [VER CARD](#cenário-de-ver-card);
- [Usuário](lexicos.html#lx16-usuário) realiza [PERSONALIZAR LABEL](#cenário-de-personalizar-label);
- A aplicação mostra uma janela com opções de persnoalização para o [Label](lexicos.html#lx26-label) para o [Usuário](lexicos.html#lx16-usuário).

------------
## CN31 Cenário de Adicionar [Anexo](lexicos.html#lx10-anexo) em um card

**Título:** Adicionar [Anexo](lexicos.html#lx10-anexo) em um [Card](lexicos.html#lx03-card) 

**Objetivo:** Adicionar um [anexo](lexicos.html#lx10-anexo) em um [Card](lexicos.html#lx03-card)  do Trello.

**Contexto:**
- **Pré-condição:**  O [Usuário](lexicos.html#lx16-usuário) precisará possuir um dispositivo com acesso a internet, estar logado em sua conta Trello e possuir um [Card](lexicos.html#lx03-card)  em uma [Lista](lexicos.html#lx02-lista).
- **Pós-condição:** : O [Usuário](lexicos.html#lx16-usuário) terá adicionado um [anexo](lexicos.html#lx10-anexo) a um [Card](lexicos.html#lx03-card) .

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) entra na tela onde tem o [Card](lexicos.html#lx03-card)  desejado.
- [Usuário](lexicos.html#lx16-usuário) clica no [Card](lexicos.html#lx03-card) . 
- No campo ‘Adicionar ao cartão’, o [Usuário](lexicos.html#lx16-usuário) clica na opção ‘anexo’. 
- [Usuário](lexicos.html#lx16-usuário) seleciona o local onde o [anexo](lexicos.html#lx10-anexo) está. 
- [Usuário](lexicos.html#lx16-usuário) seleciona o [anexo](lexicos.html#lx10-anexo). 
- [Usuário](lexicos.html#lx16-usuário) clica no botão ‘anexar’. 
- [Usuário](lexicos.html#lx16-usuário) terá anexado algo ao [Card](lexicos.html#lx03-card)  selecionado. 

------------
## CN32 Cenário de Mover um [Card](lexicos.html#lx03-card) para outra [lista](lexicos.html#lx02-lista) 

**Título:** Mover um [Card](lexicos.html#lx03-card)  para outra [Lista](lexicos.html#lx02-lista)

**Objetivo:** Mover um [Card](lexicos.html#lx03-card)  de uma [Lista](lexicos.html#lx02-lista) para outra no Trello. 

**Contexto:**
- **Pré-condição:**  O [usuário](lexicos.html#lx16-usuário) precisará possuir um dispositivo com acesso a internet, estar logado em sua conta Trello, possuir um [Card](lexicos.html#lx03-card)  em uma [Lista](lexicos.html#lx02-lista) e uma outra [Lista](lexicos.html#lx02-lista) que será o destino do [Card](lexicos.html#lx03-card) . 
- **Pós-condição:** : O [Usuário](lexicos.html#lx16-usuário) terá movido um [Card](lexicos.html#lx03-card)  de uma [Lista](lexicos.html#lx02-lista) para outra.

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) entra na tela onde tem o [Card](lexicos.html#lx03-card)  desejado.
- [Usuário](lexicos.html#lx16-usuário) clica no [Card](lexicos.html#lx03-card) . 
- No campo ‘Adicionar ao cartão’, o [Usuário](lexicos.html#lx16-usuário) clica na opção ‘anexo’. 
- [Usuário](lexicos.html#lx16-usuário) seleciona o local onde o [anexo](lexicos.html#lx10-anexo) está. 
- [Usuário](lexicos.html#lx16-usuário) seleciona o [anexo](lexicos.html#lx10-anexo). 
- [Usuário](lexicos.html#lx16-usuário) clica no botão ‘anexar’. 
- [Usuário](lexicos.html#lx16-usuário) terá anexado algo ao [Card](lexicos.html#lx03-card)  selecionado. 
- [Usuário](lexicos.html#lx16-usuário) entra na tela onde tem o [Card](lexicos.html#lx03-card)  desejado.
- [Usuário](lexicos.html#lx16-usuário) clica no [Card](lexicos.html#lx03-card)  e segura o botão do mouse. 
- [Usuário](lexicos.html#lx16-usuário) arrasta o [Card](lexicos.html#lx03-card)  para a [Lista](lexicos.html#lx02-lista) desejada. 
- [Usuário](lexicos.html#lx16-usuário) terá movido o [Card](lexicos.html#lx03-card)  de uma [Lista](lexicos.html#lx02-lista) para outra. 


------------
## CN33 Cenário de Responder um comentário no card

**Título:** Responder um comentário no [Card](lexicos.html#lx03-card) 

**Objetivo:** Responder um comentário em um [Card](lexicos.html#lx03-card)  do Trello. 

**Contexto:**
- **Pré-condição:**  O [Usuário](lexicos.html#lx16-usuário) precisará possuir um dispositivo com acesso a internet, estar logado em sua conta Trello e possuir um [Card](lexicos.html#lx03-card)  em uma [Lista](lexicos.html#lx02-lista).
- **Pós-condição:** : O [usuário](lexicos.html#lx16-usuário) terá respondido um comentário em um [Card](lexicos.html#lx03-card) . 

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) entra na tela onde tem o [Card](lexicos.html#lx03-card)  desejado.
- [Usuário](lexicos.html#lx16-usuário) clica no [Card](lexicos.html#lx03-card) . 
- [Usuário](lexicos.html#lx16-usuário) acha o comentário que deseja responder. 
- [Usuário](lexicos.html#lx16-usuário) clica no botão ‘responder’ abaixo do comentário. 
- [Usuário](lexicos.html#lx16-usuário) escreve a resposta que deseja.
- [Usuário](lexicos.html#lx16-usuário) clica no botão ‘salvar’.
- [Usuário](lexicos.html#lx16-usuário) terá respondido o comentário selecionado.

------------
## CN34 Cenário de Excluir comentário no [Card](lexicos.html#lx03-card)

**Título:** Excluir comentário no [Card](lexicos.html#lx03-card) 

**Objetivo:** Excluir um comentário em um [Card](lexicos.html#lx03-card) do Trello. 

**Contexto:**
- **Pré-condição:**  O [Usuário](lexicos.html#lx16-usuário) precisará possuir um dispositivo com acesso a internet, estar logado em sua conta Trello, possuir um [Card](lexicos.html#lx03-card)  em uma [Lista](lexicos.html#lx02-lista) e ter feito um comentário neste [Card](lexicos.html#lx03-card) . 
- **Pós-condição:** : O [Usuário](lexicos.html#lx16-usuário) terá excluído um comentário em um [Card](lexicos.html#lx03-card) . 

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) entra na tela onde tem o [Card](lexicos.html#lx03-card)  desejado.
- [Usuário](lexicos.html#lx16-usuário) clica no [Card](lexicos.html#lx03-card) . 
- [Usuário](lexicos.html#lx16-usuário) acha o seu comentário que deseja excluir. 
- [Usuário](lexicos.html#lx16-usuário) clica no botão ‘excluir’ logo abaixo do comentário. 
- [Usuário](lexicos.html#lx16-usuário) clica no botão ‘Excluir Comentário’. 
- [Usuário](lexicos.html#lx16-usuário) terá excluído o comentário desejado. 

------------
## CN35 Cenário de Usar Power-Up no quadro 

**Título:** Usar Power-Up no quadro

**Objetivo:** Usar um Power-up em um quadro no Trello.

**Contexto:**
- **Pré-condição:**  O [Usuário](lexicos.html#lx16-usuário) precisará possuir um dispositivo com acesso a internet, estar logado em sua conta Trello e possuir um quadro. 
- **Pós-condição:** : O [Usuário](lexicos.html#lx16-usuário) terá usado um Power-Up em um quadro. 

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) entra no quadro desejado. 
- [Usuário](lexicos.html#lx16-usuário) clica no botão ‘Mostrar Menu’. 
- [Usuário](lexicos.html#lx16-usuário) clica na opção ‘Power-Ups’. 
- [Usuário](lexicos.html#lx16-usuário) usa o campo de pesquisa, se necessário. 
- [Usuário](lexicos.html#lx16-usuário) clica no botão adicionar no Power-Up desejado. 
- [Usuário](lexicos.html#lx16-usuário) pode adicionar mais Power-Ups a um mesmo quadro se possuir conta diferente da ‘Grátis’. 
- [Usuário](lexicos.html#lx16-usuário) terá adicionado um Power-Up a um quadro.

------------
## CN36 Cenário de Compartilhar card

**Título:** Compartilhar [Card](lexicos.html#lx03-card) 

**Objetivo:** Compartilhar um [Card](lexicos.html#lx03-card)  do Trello. 

**Contexto:**
- **Pré-condição:**  O [Usuário](lexicos.html#lx16-usuário) precisará possuir um dispositivo com acesso a internet, estar logado em sua conta Trello e possuir um [Card](lexicos.html#lx03-card)  em uma [Lista](lexicos.html#lx02-lista). 
- **Pós-condição:** : O [Usuário](lexicos.html#lx16-usuário) terá compartilhado um [Card](lexicos.html#lx03-card) . 

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) entra na tela onde tem o [Card](lexicos.html#lx03-card)  desejado. 
- [Usuário](lexicos.html#lx16-usuário) clica no [Card](lexicos.html#lx03-card) . 
- [Usuário](lexicos.html#lx16-usuário) clica na opção ‘Compartilhar e mais...’. 
- [Usuário](lexicos.html#lx16-usuário) escolhe como deseja compartilhar o [Card](lexicos.html#lx03-card) . 
- Ao selecionar uma das opções, o [Usuário](lexicos.html#lx16-usuário) terá um referencial do [Card](lexicos.html#lx03-card) de acordo com a opção escolhida. 

------------
## CN37 Cenário de Exibir detalhes do card

**Título:** Exibir detalhes do [Card](lexicos.html#lx03-card) 

**Objetivo:** Exibir detalhes de um [Card](lexicos.html#lx03-card)  do Trello. 

**Contexto:**
- **Pré-condição:**  O [Usuário](lexicos.html#lx16-usuário) precisará possuir um dispositivo com acesso a internet, estar logado em sua conta Trello e possuir um [Card](lexicos.html#lx03-card)  em uma [Lista](lexicos.html#lx02-lista). 
- **Pós-condição:** : O [usuário](lexicos.html#lx16-usuário) terá visualizado detalhes do [Card](lexicos.html#lx03-card) . 

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) entra na tela onde tem o [Card](lexicos.html#lx03-card)  desejado. 
- [Usuário](lexicos.html#lx16-usuário) clica no [Card](lexicos.html#lx03-card) .
- [Usuário](lexicos.html#lx16-usuário) terá aberto os detalhes do [Card](lexicos.html#lx03-card) .

------------
## CN38 Cenário de [Vincular](lexicos.html#) ao [Quadro](lexicos.html#quadro)

**Título:** [Vincular](lexicos.html#) a um [Quadro](lexicos.html#quadro). 

**Objetivo:** [Vincular](lexicos.html#) uma pessoa a um [Quadro](lexicos.html#quadro) para visualizar toda a interface do projeto e suas respectivas [Tarefa](lexicos.html#lx27-tarefa).

**Contexto:**
- **Pré-condição:**O [Usuário](lexicos.html#lx16-usuário) precisa ter uma conta no Trello e estar [Logada](lexicos.html#lx17-login), utilizando um dispositivo com acesso a internet, estar [Vinculada](lexicos.html#lx18-vincular) à um [Quadro](lexicos.html#quadro). 
- **Pós-condição:** : O [Usuário](lexicos.html#lx16-usuário) estará ligado à um [Quadro](lexicos.html#quadro), conseguirá ver [Tarefas](lexicos.html#lx27-tarefa) as quais pode fazer/designar.

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Dispositivo compatível com a plataforma Trello, um navegador ou o aplicativo e possuir internet.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) entra no [Quadro](lexicos.html#quadro). 
- [Usuário](lexicos.html#lx16-usuário) escolhe outro [Usuário](lexicos.html#lx16-usuário) que deseja [Vincular](lexicos.html#lx18-vincular).
- [Usuário](lexicos.html#lx16-usuário) adiciona e-mail.
- [Usuário](lexicos.html#lx16-usuário) aceita ser [Vinculado](lexicos.html#lx18-vincular) pelo e-mail.
- Caso o [Usuário](lexicos.html#lx16-usuário) não receba o e-mail, verificar caixa de spam.
-[Usuário](lexicos.html#lx16-usuário) copia link para [Vincular](lexicos.html#lx18-vincular).
-[Usuário](lexicos.html#lx16-usuário) clica no link para se [Vincular](lexicos.html#lx18-vincular).

------------
## CN39 Cenário de Alterar permissões de [membros](lexicos.html#lx19-membro) no [board](lexicos.html#lx01-board)

**Título:** Alterar permissão de um [Membro](lexico.html#tarefa) em um [Board](lexico.html#board).

**Objetivo:** Fazer com que determinado [Membro](lexico.html#tarefa) tenha mais ou menos poder em um determinado [Board](lexico.html#board). 

**Contexto:**
- **Pré-condição:**O [Usuário](lexicos.html#lx16-usuário) precisa ter uma conta no Trello e estar [Logada](lexicos.html#lx17-login), utilizando um dispositivo com acesso a internet, estar [Vinculada](lexicos.html#lx18-vincular) à um [Quadro](lexicos.html#quadro). 
- **Pós-condição:** : O [Usuário](lexicos.html#lx16-usuário) terá menos ou mais controle sobre um determinado [Board](lexico.html#board).


**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Dispositivo compatível com a plataforma Trello, um navegador ou o aplicativo e possuir internet.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) entra no [Quadro](lexicos.html#quadro). 
- [Usuário](lexicos.html#lx16-usuário) escolhe outro [Usuário](lexicos.html#lx16-usuário) que deseja alterar a permissão.
- [Usuário](lexicos.html#lx16-usuário) altera permissão.
- Caso o [Usuário](lexicos.html#lx16-usuário) não tenha permissão, ele não conseguirá alterar outras.

------------
## CN40 Cenário de Criar [Lista](lexicos.html#lx02-lista)

**Título:** Criar uma [Lista](lexicos.html#lx02-lista).

**Objetivo:** Ter um espaço com um tema específico para colocar [Atividades](lexicos.html#lx22-atividade). 

**Contexto:**
- **Pré-condição:**O [Usuário](lexicos.html#lx16-usuário) precisa ter uma conta no Trello e estar [Logada](lexicos.html#lx17-login), utilizando um dispositivo com acesso a internet, estar [vinculada](lexicos.html#lx18-vincular) à um [Quadro](lexicos.html#quadro). 
- **Pós-condição:** : O [Usuário](lexicos.html#lx16-usuário) terá um espaço [Atribuir](lexicos.html#) [Tarefas](lexicos.html#) de determinado tema ou parte do [Board](lexicos.html#lx01-board).


**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Dispositivo compatível com a plataforma Trello, um navegador ou o aplicativo e possuir internet.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) entra no [Quadro](lexicos.html#quadro). 
- [Usuário](lexicos.html#lx16-usuário) aperta em "Adicionar outra [Lista](lexicos.html#lx02-lista)".
- [Usuário](lexicos.html#lx16-usuário) coloca um nome na [Lista](lexicos.html#lx02-lista).

------------
## CN41 Cenário de Alterar nome da [Lista](lexicos.html#lx02-lista)

**Título:** alterar o nome de uma [Lista](lexicos.html#lx02-lista).

**Objetivo:** Mudar o nome de uma determinada [Lista](lexicos.html#lx02-lista) com o objetivo dela. 

**Contexto:**
- **Pré-condição:**O [Usuário](lexicos.html#lx16-usuário) precisa ter uma conta no Trello e estar [Logada](lexicos.html#lx17-login), utilizando um dispositivo com acesso a internet, estar [vinculada](lexicos.html#lx18-vincular) à um [Quadro](lexicos.html#quadro). 
- **Pós-condição:** : O [Usuário](lexicos.html#lx16-usuário) saberá onde criar determinado [Card](lexicos;html#usuário), dependendo do seu objetivo.


**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Dispositivo compatível com a plataforma Trello, um navegador ou o aplicativo e possuir internet.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) entra no [Quadro](lexicos.html#quadro). 
- [Usuário](lexicos.html#lx16-usuário) clica no nome da [Lista](lexicos.html#lx02-lista).
- [Usuário](lexicos.html#lx16-usuário) altera o nome da [Lista](lexicos.html#lx02-lista).

------------
## CN42 Cenário de Arquivar [Lista](lexicos.html#lx02-lista)

**Título:** [Arquivar](lexicos.html#lx09-arquivar) uma [Lista](lexicos.html#lx02-lista).

**Objetivo:** [Arquivar](lexicos.html#lx09-arquivar) uma determinada [Lista](lexicos.html#lx02-lista) que não é necessário.

**Contexto:**
- **Pré-condição:**O [Usuário](lexicos.html#lx16-usuário) precisa ter uma conta no Trello e estar [Logada](lexicos.html#lx17-login), utilizando um dispositivo com acesso a internet, estar [vinculada](lexicos.html#lx18-vincular) à um [Quadro](lexicos.html#quadro). 
- **Pós-condição:** : O [Usuário](lexicos.html#lx16-usuário) não terá a [Lista](lexicos.html#lx02-lista) visível até que queira.


**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Dispositivo compatível com a plataforma Trello, um navegador ou o aplicativo e possuir internet.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) entra no [Quadro](lexicos.html#quadro). 
- [Usuário](lexicos.html#lx16-usuário) clica nas opções da [Lista](lexicos.html#lx02-lista).
- [Usuário](lexicos.html#lx16-usuário) clica na opção"Arquivar esta [Lista](lexicos.html#lx02-lista)".

------------
## CN43 Cenário de Organizar o quadro em coleções

**Título:** Organizar o [Quadro](lexicos.html#quadro) em [Coleções](lexicos.html#colecao)).

**Objetivo:** Agrupar um conjunto de [Quadro](lexicos.html#quadro).

**Contexto:**
- **Pré-condição:**O [Usuário](lexicos.html#lx16-usuário) precisa ter uma conta no Trello e estar [Logada](lexicos.html#lx17-login), utilizando um dispositivo com acesso a internet, estar [vinculada](lexicos.html#lx18-vincular) à um [Quadro](lexicos.html#quadro). 
- **Pós-condição:** : O [Usuário](lexicos.html#lx16-usuário) poderá ter um conjunto de [Quadro](lexicos.html#quadro) com determinado tema.


**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Dispositivo compatível com a plataforma Trello, um navegador ou o aplicativo e possuir internet.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) entra no menu do Trello. 
- [Usuário](lexicos.html#lx16-usuário) clica nas opções de criar [Coleção](lexicos.html#colecao).
- [Usuário](lexicos.html#lx16-usuário) adiciona os [Quadros](lexicos.html#lx02-lista) desejados.
-Caso não tenha [Quadros](lexicos.html#quadros) o [Usuário](lexicos.html#lx16-usuário) terá que criar mais.

----------------
## CN44 Criar Board

**Título:** Criar um [Board](lexicos.html#lx01-board).

**Objetivo:** Criar um [Board](lexicos.html#lx01-board).

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#lx16-usuário) precisa ter uma conta no Trello e estar logado na mesma, utilizando um dispositivo com acesso a internet.
- **Pós-condição:** O [Usuário](lexicos.html#lx16-usuário) terá um [Board](lexicos.html#lx01-board) para designar, planejar e executar tarefas para seu respectivo time.

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Conta Trello, internet.

**Restrições** O [Usuário](lexicos.html#lx16-usuário) precisa ter uma conta Trello com acesso a internet.

**Excessões** Não ter internet na criação do [Board](lexicos.html#lx01-board), não ter energia na criação do [Board](lexicos.html#lx01-board).

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) entra no Trello;
- [Usuário](lexicos.html#lx16-usuário) realiza [Login](lexicos.html#lx17-login);
- [Usuário](lexicos.html#lx16-usuário) clica no criar [Board](lexicos.html#lx01-board);

---------------------------

## CN45 Criar Board do Time

**Título:** Criar um [Board](lexicos.html#lx01-board) e alocar time.

**Objetivo:** Criar um [Board](lexicos.html#lx01-board) para o time se organizar.

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#lx16-usuário) precisa ter uma conta no Trello e estar logado na mesma, utilizando um dispositivo com acesso a internet e ter possíveis membros para adicionar ao time.
- **Pós-condição:** O [Usuário](lexicos.html#lx16-usuário) terá um [Board](lexicos.html#lx01-board) para designar, planejar e executar tarefas para seu respectivo time.

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Conta Trello, internet, time.

**Restrições** O [Usuário](lexicos.html#lx16-usuário) precisa ter uma conta Trello com acesso a internet.

**Excessões** Não ter internet na criação do [Board](lexicos.html#lx01-board), não ter energia na criação do [Board](lexicos.html#lx01-board), não ter um time para convidar ao [Board](lexicos.html#lx01-board).

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) entra no Trello;
- [Usuário](lexicos.html#lx16-usuário) realiza [Login](lexicos.html#lx17-login);
- [Usuário](lexicos.html#lx16-usuário) clica no criar [Board](lexicos.html#lx01-board);
- [Usuário](lexicos.html#lx16-usuário) adiciona participantes ao [Board](lexicos.html#lx01-board);
---------------------------
## CN46 Ver um Board

**Título:** Ver um [Board](lexicos.html#lx01-board).

**Objetivo:** Ver um [Board](lexicos.html#lx01-board) para acompanhar andamento.

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#lx16-usuário) precisa ter uma conta no Trello e estar logado na mesma, utilizando um dispositivo com acesso a internet. E possuir um [Board](lexicos.html#lx01-board) que possa ser visualizado.
- **Pós-condição:** O [Usuário](lexicos.html#lx16-usuário) poderá ver atividades e descrições a respeito daquele [Board](lexicos.html#lx01-board) nos [cards]() levantados.

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Conta Trello, internet, um [Board](lexicos.html#lx01-board) para participar.

**Restrições** O [Usuário](lexicos.html#lx16-usuário) precisa ter um [Board](lexicos.html#lx01-board).

**Excessões** Não ter um [Board](lexicos.html#lx01-board) para ser visualizado.

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) entra no Trello;
- [Usuário](lexicos.html#lx16-usuário) realiza [Login](lexicos.html#lx17-login);
- [Usuário](lexicos.html#lx16-usuário) clica no [Board](lexicos.html#lx01-board) para visualizar;
- [Usuário](lexicos.html#lx16-usuário) visualiza o [Board](lexicos.html#lx01-board).
---------------------------
## CN47 Administrar Power-ups

**Título:** Administrar [power-ups](lexicos.html#lx25-power-up) em um projeto..

**Objetivo:** Ter uma noção de qual ferramenta caberia para alocação como [power-ups](lexicos.html#lx25-power-up).

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#lx16-usuário) precisa ter uma conta no Trello e estar logado na mesma, utilizando um dispositivo com acesso a internet. E possuir um [Board](lexicos.html#lx01-board) no qual possa ter permissões para tomar decisões de gerente.
- **Pós-condição:** O [Usuário](lexicos.html#lx16-usuário) terá um projeto podendo adicionar [power-ups](lexicos.html#lx25-power-up) no seu contexto..

**Atores:** [Usuário](lexicos.html#lx16-usuário)

**Recursos:** Dispositivo compatível com a plataforma Trello, um navegador ou o aplicativo e possuir internet. Um [Board](lexicos.html#lx01-board) no qual possa adicionar [power-ups](lexicos.html#lx25-power-up).

**Restrições** O [Usuário](lexicos.html#lx16-usuário) precisa ter um [Board](lexicos.html#lx01-board) no qual ele possua a posição de administrador, e conta [gold]() no Trello.

**Excessões** Não ter a posição de administrador em um [Board](lexicos.html#lx01-board).

**Episódios:**
- [Usuário](lexicos.html#lx16-usuário) entra no Trello;
- [Usuário](lexicos.html#lx16-usuário) realiza [Login](lexicos.html#lx17-login);
- [Usuário](lexicos.html#lx16-usuário) clica no [Board](lexicos.html#lx01-board) para acessar;
- [Usuário](lexicos.html#lx16-usuário) clica no [card](lexicos.html#lx03-card) visualizar;
- [Usuário](lexicos.html#lx16-usuário) adiciona [power-ups](lexicos.html#lx25-power-up) no [card](lexicos.html#lx03-card) utilizar;

--------------------
## CN48 Cenário de Adicionar Membros ao Card

**Título:** Adicionar [membros](lexicos.html#lx19-membro) em um [card](lexicos.html#lx03-card). 

**Objetivo:** Adicionar [membros](lexicos.html#lx19-membro) em um [card](lexicos.html#lx03-card).

**Contexto:**

- **Pré-condição:** O [Usuário](lexicos.html#usuario) precisará possuir um [card](lexicos.html#lx03-card) a ser realizado e [membros](lexicos.html#lx19-membro) para serem adicionados.
- **Pós-condição:** O [Usuário](lexicos.html#usuario) terá delegado o [card](lexicos.html#lx03-card) para determinado[membro](lexicos.html#lx19-membro). 

**Atores:** [Usuário](lexicos.html#usuario) de [Board](lexicos.html#lx01-board).

**Recursos:** Conta, [Board](lexicos.html#lx01-board), [card](lexicos.html#lx03-card), computador, internet.

**Restrição:** Card deve ter sido selecionado pelo [Usuário](lexicos.html#usuario) da [Board](lexicos.html#lx01-board).

**Exceção:** Não há [card](lexicos.html#lx03-card) para adicionar [membros](lexicos.html#lx19-membro). 

**Episódios:**
- [Usuário](lexicos.html#usuario) entra no trello. 
- [Usuário](lexicos.html#usuario) realiza [Login](lexicos.html#lx17-login).
- [Usuário](lexicos.html#usuario) visualiza [Board](lexicos.html#lx01-board). 
- Se não há board, [Usuário](lexicos.html#usuario) cria [Board](lexicos.html#lx01-board). 
- [Usuário](lexicos.html#usuario) visualiza [Lista](lexicos.html#lx02-lista). 
- Se não há lista, [Usuário](lexicos.html#usuario) cria [Lista](lexicos.html#lx02-lista).
- [Usuário](lexicos.html#usuario) vizualiza card.
- Se não há [card](lexicos.html#lx03-card), [Usuário](lexicos.html#usuario) cria [card](lexicos.html#lx03-card).
- [Usuário](lexicos.html#usuario) seleciona [card](lexicos.html#lx03-card).
- [Usuário](lexicos.html#usuario) clica no botão “Adicionar membros”.
- [Usuário](lexicos.html#usuario) insere nome do [membro](lexicos.html#lx19-membro) a ser adicionado.
- [Usuário](lexicos.html#usuario) seleciona [membro](lexicos.html#lx19-membro) a ser adicionado.

------------------------

## CN49 Adicionar Descrição ao Card

**Título:** Adicionar descrição ao [card](lexicos.html#lx03-card).

**Objetivo:** Adicionar uma descrição ao [card](lexicos.html#lx03-card) selecionado.

**Contexto:**

- **Pré-condição:** O [Usuário](lexicos.html#usuario) precisará possuir um [card](lexicos.html#lx03-card) sem descrição em uma lista qualquer em sua [Board](lexicos.html#lx01-board).
- **Pós-condição:** O [Usuário](lexicos.html#usuario) terá adicionado uma descrição ao card selecionado. 

**Atores:** [Usuário](lexicos.html#usuario) de [Board](lexicos.html#lx01-board) 

**Recursos:** Conta, [Board](lexicos.html#lx01-board), [card](lexicos.html#lx03-card), computador, internet.

**Restrição:** [Card](lexicos.html#lx03-card) deve ter sido selecionado pelo usuário da [Board](lexicos.html#lx01-board).

**Exceção:** Não há [card](lexicos.html#lx03-card) para adicionar descrição.

**Episódios:**

- [Usuário](lexicos.html#usuario) entra no trello. 
- [Usuário](lexicos.html#usuario) realiza [Login](lexicos.html#lx17-login).
- [Usuário](lexicos.html#usuario) visualiza [Board](lexicos.html#lx01-board). 
- Se não há board, usuário cria [Board](lexicos.html#lx01-board). 
- [Usuário](lexicos.html#usuario) visualiza [Lista](lexicos.html#lx02-lista). 
- Se não há lista, usuário cria [Lista](lexicos.html#lx02-lista).
- [Usuário](lexicos.html#usuario) vizualiza [card](lexicos.html#lx03-card).
- Se não há card, usuário cria [card](lexicos.html#lx03-card).
- [Usuário](lexicos.html#usuario) seleciona [card](lexicos.html#lx03-card).
- Se não há descrição, usuário insere uma descrição.
- [Usuário](lexicos.html#usuario) clica no botão “salvar”.

-------------------------------------

## CN50 Adicionar [Checklist](lexicos.html#lx23-check-list)

**Título:** Adicionar [checklist](lexicos.html#lx23-check-list) ao [card](lexicos.html#lx03-card). 

**Objetivo:** Adicionar uma [checklist](lexicos.html#lx23-check-list) a um [card](lexicos.html#lx03-card).

**Contexto:** 

- **Pré-condição:** O [Usuário](lexicos.html#usuario) precisará possuir um [card](lexicos.html#lx03-card) com subtarefas a serem realizadas.
- **Pós-condição:** O [Usuário](lexicos.html#usuario) terá criado uma [checklist](lexicos.html#lx23-check-list) com todas as subtarefas a serem realizadas.

**Atores:** [Usuário](lexicos.html#usuario) de [Board](lexicos.html#lx01-board).

**Recursos:** Conta, [Board](lexicos.html#lx01-board), [card](lexicos.html#lx03-card), computador, internet.

**Restrição:** [Card](lexicos.html#lx03-card) deve ter sido selecionado pelo usuário da [Board](lexicos.html#lx01-board).

**Exceção:**

- Não há [card](lexicos.html#lx03-card) para adicionar [checklist](lexicos.html#lx23-check-list). 
- [Card](lexicos.html#lx03-card) selecionado não dá para ser dividido em subtarefas.

**Episódios:**

- [Usuário](lexicos.html#usuario) entra no trello. 
- [Usuário](lexicos.html#usuario) realiza [Login](lexicos.html#lx17-login).
- [Usuário](lexicos.html#usuario) visualiza[Board](lexicos.html#lx01-board). 
- Se não há [Board](lexicos.html#lx01-board), [Usuário](lexicos.html#usuario) cria [Board](lexicos.html#lx01-board). 
- Usuário visualiza [Lista](lexicos.html#lx02-lista). 
- Se não há [Lista](lexicos.html#lx02-lista), [Usuário](lexicos.html#usuario) cria [Lista](lexicos.html#lx02-lista).
- [Usuário](lexicos.html#usuario) vizualiza [card](lexicos.html#lx03-card).
- Se não há [card](lexicos.html#lx03-card), usuário cria [card](lexicos.html#lx03-card).
- [Usuário](lexicos.html#usuario) seleciona [card](lexicos.html#lx03-card).
- Se não há [checklist](lexicos.html#lx23-check-list), [Usuário](lexicos.html#usuario) clica no botão “Adicionar [checklist](lexicos.html#lx23-check-list)”.
- [Usuário](lexicos.html#usuario) insere nome das subtarefas a serem realizadas.
- [Usuário](lexicos.html#usuario) para de adicionar subtarefas quando desejar.

--------------------------
## CN51 Adicionar Etiqueta ao Card 
**Título:** Adicionar etiqueta em um [card](lexicos.html#lx03-card).

**Objetivo:** Adicionar uma etiqueta ao [card](lexicos.html#lx03-card) selecionado.

**Contexto:** 

- **Pré-condição:** O [Usuário](lexicos.html#usuario) precisará possuir um card em uma [Lista](lexicos.html#lx02-lista) qualquer em sua board.
- **Pós-condição:** O [Usuário](lexicos.html#usuario) terá adicionado uma ou mais etiquetas ao [card](lexicos.html#lx03-card) selecionado.

**Atores:**[Usuário](lexicos.html#usuario) de board 

**Recursos:** Conta,[Board](lexicos.html#lx01-board), [card](lexicos.html#lx03-card), computador, internet.

**Restrição:** [Card](lexicos.html#lx03-card) deve ter sido selecionado pelo usuário da [Board](lexicos.html#lx01-board).

**Exceção:**

- Não há [card](lexicos.html#lx03-card) para adicionar etiqueta. 
- Não é necessário etiquetar o [card](lexicos.html#lx03-card).

**Episódios:**

- [Usuário](lexicos.html#usuario) entra no trello. 
- [Usuário](lexicos.html#usuario) realiza [Login](lexicos.html#lx17-login).
- [Usuário](lexicos.html#usuario) visualiza [Board](lexicos.html#lx01-board). 
- Se não há [Board](lexicos.html#lx01-board), usuário cria [Board](lexicos.html#lx01-board). 
- [Usuário](lexicos.html#usuario) visualiza [Lista](lexicos.html#lx02-lista). 
- Se não há [Lista](lexicos.html#lx02-lista), usuário cria [Lista](lexicos.html#lx02-lista).
- [Usuário](lexicos.html#usuario) vizualiza [card](lexicos.html#lx03-card).
- Se não há [card](lexicos.html#lx03-card), usuário cria [card](lexicos.html#lx03-card).
- [Usuário](lexicos.html#usuario) seleciona [card](lexicos.html#lx03-card).
- [Usuário](lexicos.html#usuario) clica no botão “adicionar etiquetas”.
- [Usuário](lexicos.html#usuario) para de adicionar etiquetas quando desejar.

-----------------------------

## CN52 Adicionar Deadline

**Título:** Adicionar [deadline](lexicos.html#lx13-duedate)  em um [card](lexicos.html#lx03-card). 

**Objetivo:** Adicionar [deadline](lexicos.html#lx13-duedate)  a um [card](lexicos.html#lx03-card). 

**Contexto:**

- **Pré-condição:** O [usuário](lexicos.html#usuario) precisará possuir um [card](lexicos.html#lx03-card) que deve ser realizado até uma data limite.
- **Pós-condição:** O [usuário](lexicos.html#usuario) terá criado uma [data de entrega](lexicos.html#lx13-duedate)  para o [card](lexicos.html#lx03-card). 

**Atores:** [Usuário](lexicos.html#usuario) de [board](lexicos.html#lx01-board).

**Recursos:** Conta, [board](lexicos.html#lx01-board), [card](lexicos.html#lx03-card), computador, internet.

**Restrição:** [Card](lexicos.html#lx03-card) deve ter sido selecionado pelo [usuário](lexicos.html#usuario) da [board](lexicos.html#lx01-board).

**Exceção:**

- Não há [card](lexicos.html#lx03-card) para adicionar [data de entrega](lexicos.html#lx13-duedate) . 
- Não há tempo limite para se realizar a tarefa do [card](lexicos.html#lx03-card).

**Episódios:**

- [Usuário](lexicos.html#usuario) entra no trello. 
- [Usuário](lexicos.html#usuario) realiza [Login](lexicos.html#lx17-login).
- [Usuário](lexicos.html#usuario) visualiza [Board](lexicos.html#lx01-board). 
- Se não há [Board](lexicos.html#lx01-board), [usuário](lexicos.html#usuario) cria [Board](lexicos.html#lx01-board). 
- [Usuário](lexicos.html#usuario) visualiza [Lista](lexicos.html#lx02-lista). 
- Se não há [Lista](lexicos.html#lx02-lista), [usuário](lexicos.html#usuario) cria [Lista](lexicos.html#lx02-lista).
- [Usuário](lexicos.html#usuario) vizualiza [card](lexicos.html#lx03-card).
- Se não há card,[usuário](lexicos.html#usuario) cria [card](lexicos.html#lx03-card).
- [Usuário](lexicos.html#usuario) seleciona [card](lexicos.html#lx03-card).
- [Usuário](lexicos.html#usuario) clica no botão “Adicionar [deadline](lexicos.html#lx13-duedate) ”.
- [Usuário](lexicos.html#usuario) escolhe a data limite da entrega.
- [Usuário](lexicos.html#usuario) clica em “salvar” para manter a [data de entrega](lexicos.html#lx13-duedate)  escolhida.

---------------------------

## CN53 Adicionar Comentários ao Card

**Título:** Adicionar comentário em um [card](lexicos.html#lx03-card). 

**Objetivo:**  Adicionar um comentário em um [card](lexicos.html#lx03-card). 

**Contexto:** 

- **Pré-condição:** O [usuário](lexicos.html#usuario) precisará possuir um  [card](lexicos.html#lx03-card) em uma [lista](lexicos.html#lx02-lista) no trello.
- **Pós-condição:** O[usuário](lexicos.html#usuario) terá postado um comentário em um  [card](lexicos.html#lx03-card) específico.

**Atores:** [Usuário](lexicos.html#usuario) de[board](lexicos.html#lx01-board).

**Recursos:** Conta, [board](lexicos.html#lx01-board),  [card](lexicos.html#lx03-card), computador, internet.

**Restrição:** Card deve ter sido selecionado pelo [usuário](lexicos.html#usuario) da [board](lexicos.html#lx01-board).

**Exceção:** Não há [card](lexicos.html#lx03-card) para adicionar comentários.

**Episódios:**

- [Usuário](lexicos.html#usuario) entra no trello. 
- [Usuário](lexicos.html#usuario) realiza [Login](lexicos.html#lx17-login).
- [Usuário](lexicos.html#usuario) visualiza [Board](lexicos.html#lx01-board). 
- Se não há [Board](lexicos.html#lx01-board), [usuário](lexicos.html#usuario) cria [Board](lexicos.html#lx01-board). 
- [Usuário](lexicos.html#usuario) visualiza [lista](lexicos.html#lx02-lista). 
- Se não há [lista](lexicos.html#lx02-lista), usuário cria [lista](lexicos.html#lx02-lista).
- [Usuário](lexicos.html#usuario) vizualiza  [card](lexicos.html#lx03-card).
- Se não há  [card](lexicos.html#lx03-card), [usuário](lexicos.html#usuario) cria  [card](lexicos.html#lx03-card).
- [Usuário](lexicos.html#usuario) seleciona  [card](lexicos.html#lx03-card).
- [Usuário](lexicos.html#usuario) visualiza a área “Adicionar comentários”.
- [Usuário](lexicos.html#usuario) escreve um comentário.
- [Usuário](lexicos.html#usuario) clica em “salvar” para manter o comentário feito.

--------------------------

## CN54 Alterar Permissão de Comentário

**Título:** Alterar permissão de comentário. 

**Objetivo:** Alterar quem é permitido comentar em [cards](lexicos.html#lx03-card). 

**Contexto:**

- **Pré-condição:** O [usuário](lexicos.html#usuario) possui um [board](lexicos.html#lx01-board) com permissões de comentário indesejadas.
- **Pós-condição:** O [usuário](lexicos.html#usuario) terá alterado as permissões de comentário do [board](lexicos.html#lx01-board). 

**Atores:** [Usuário](lexicos.html#usuario) de [board](lexicos.html#lx01-board).

**Recursos:** Conta, [board](lexicos.html#lx01-board), computador, internet.

**Restrição:** O [usuário](lexicos.html#usuario) deve ser dono do [board](lexicos.html#lx01-board) com as permissões de comentário indesejadas.

**Episódios:**

- [Usuário](lexicos.html#usuario) entra no trello. 
- [Usuário](lexicos.html#usuario) realiza [Login](lexicos.html#lx17-login).
- [Usuário](lexicos.html#usuario) visualiza [board](lexicos.html#lx01-board). 
- Se não há [board](lexicos.html#lx01-board), usuário cria [board](lexicos.html#lx01-board). 
- [Usuário](lexicos.html#usuario) clica no botão “Mostrar menu”.
- [Usuário](lexicos.html#usuario) clica no botão “Mais”.
- [Usuário](lexicos.html#usuario) clica no botão “Configurações”.
- [Usuário](lexicos.html#usuario) seleciona as “Permissões de comentário”.
- [Usuário](lexicos.html#usuario) escolhe as “Permissões de comentário” desejadas.
  

- --------------------------

## CN55 Observar Board

**Título:** Observar um Board.

**Objetivo:** Observar um [board](lexicos.html#lx01-board). 

**Contexto:**

- **Pré-condição:** O [usuário](lexicos.html#usuario) precisa ter uma conta trello estar logado e na mesma, e ter acesso a internet.
- **Pós-condição:** O [usuário](lexicos.html#usuario) terá um [board](lexicos.html#lx01-board) para acompanhar e receber notificações quanto ao progresso e desenvolvimento do mesmo. 

**Atores:** [Usuário](lexicos.html#usuario).

**Recursos:** Dispositivo compatível com a plataforma Trello,
um navegador ou o aplicativo, possuir internet, um [board](lexicos.html#lx01-board), criado[board](lexicos.html#lx01-board), computador.

**Episódios:**

- [Usuário](lexicos.html#usuario) deseja seguir de perto o desenvolvimento do [board](lexicos.html#lx01-board). 
- [Usuário](lexicos.html#usuario) deseja acompanhar o andamento do [board](lexicos.html#lx01-board). 
- [Usuário](lexicos.html#usuario) deseja observar o avanço da equipe no [board](lexicos.html#lx01-board). 

- --------------------------

## CN56 Adicionar Membros ao Board

**Título:** Adicionar membros a um Board.

**Objetivo:** Adicionar participantes para ver ou auxiliar no progresso de um [board](lexicos.html#lx01-board). 

**Contexto:**

- **Pré-condição:** O [usuário](lexicos.html#usuario) precisa ter uma conta no Trello e estar logado na mesma, utilizando um dispositivo com acesso a internet. E ter um [board](lexicos.html#lx01-board) no qual ele possa adicionar pessoas.
- **Pós-condição:** O [usuário](lexicos.html#usuario)  pode ter adicionado mais pessoas para ver ou auxiliar o progresso de [card](lexicos.html#lx03-card) daquele[board](lexicos.html#lx01-board) para acompanhar e receber notificações quanto ao progresso e desenvolvimento do mesmo. 

**Atores:** [Usuário](lexicos.html#usuario).

**Recursos:** Dispositivo compatível com a plataforma Trello, um navegador ou o aplicativo, possuir internet, um [board](lexicos.html#lx01-board), criado[board](lexicos.html#lx01-board), computador.

**Episódios:**

- [Usuário](lexicos.html#usuario) abre o Trello. 
- [Usuário](lexicos.html#usuario) faz login. 
- [Usuário](lexicos.html#usuario) clica em um [board](lexicos.html#lx01-board) se houver um.
- [Usuário](lexicos.html#usuario) envia convites para outros membros participarem do [board](lexicos.html#lx01-board) se houver um.

- --------------------------

## CN57 Criar Time do Business Class

**Título:**  Criar um time do Business Class.

**Objetivo:** Criar um [board](lexicos.html#lx01-board) para o time se organizar, onde o time irá possuir maior segurança e controles admnistrativos.

**Contexto:**

- **Pré-condição:** O [usuário](lexicos.html#usuario) precisa ter uma conta no Trello e estar logado na mesma, utilizando um dispositivo com acesso a internet. e ter pago uma
taxa referente ao plano.
- **Pós-condição:** O [usuário](lexicos.html#usuario) terá um [board](lexicos.html#lx01-board) para designar, planejar e executar tarefas para seu respectivo time, além de power-ups ilimitados ao seu projeto e mais segurança além de controles admnistrativos melhores. 

**Atores:** [Usuário](lexicos.html#usuario).

**Recursos:** Dispositivo compatível com a plataforma Trello, um navegador ou o aplicativo, possuir internet, computador.

**Episódios:**

- [Usuário](lexicos.html#usuario) abre o Trello. 
- [Usuário](lexicos.html#usuario) faz login. 
- [Usuário](lexicos.html#usuario) clica em criar time business class.
- [Usuário](lexicos.html#usuario) adicionar informações ao [board](lexicos.html#lx01-board).
- [Usuário](lexicos.html#usuario) personaliza [board](lexicos.html#lx01-board).
- [Usuário](lexicos.html#usuario) adiciona membros ao [board](lexicos.html#lx01-board).
- [Usuário](lexicos.html#usuario) envia convites.


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
- [Usuário](lexicos.html#lx16-usuário) faz [Login](lexicos.html#lx17-login) ;
- Usuário

-------------------------------------------------------

**Cenário de Adicionar Membros ao Card**

**Título:** Adicionar membros em um [card](). 

**Objetivo:** Adicionar membros em um [card]().

**Contexto:**

- **Pré-condição:** O [Usuário](lexicos.html#usuario) precisará possuir um [card]() a ser realizado e membros para serem adicionados.
- **Pós-condição:** O [Usuário](lexicos.html#usuario) terá delegado o [card]() para determinado membro. 

**Atores:** [Usuário](lexicos.html#usuario) de [Board](lexicos.html#lx01-board).

**Recursos:** Conta, [Board](lexicos.html#lx01-board), [card](), computador, internet.

**Restrição:** Card deve ter sido selecionado pelo [Usuário](lexicos.html#usuario) da [Board](lexicos.html#lx01-board).

**Exceção:** Não há [card]() para adicionar membros. 

**Episódios:**
-[Usuário](lexicos.html#usuario) entra no trello. 
-[Usuário](lexicos.html#usuario) realiza [Login](lexicos.html#lx17-login).
-[Usuário](lexicos.html#usuario) visualiza [Board](lexicos.html#lx01-board). 
-Se não há board, [Usuário](lexicos.html#usuario) cria [Board](lexicos.html#lx01-board). 
-[Usuário](lexicos.html#usuario) visualiza [Lista](lexicos.html#lx02-lista). 
-Se não há lista, [Usuário](lexicos.html#usuario) cria [Lista](lexicos.html#lx02-lista).
-[Usuário](lexicos.html#usuario) vizualiza card.
-Se não há card, [Usuário](lexicos.html#usuario) cria [card]().
-[Usuário](lexicos.html#usuario) seleciona [card]().
-[Usuário](lexicos.html#usuario) clica no botão “Adicionar membros”.
-[Usuário](lexicos.html#usuario) insere nome do membro a ser adicionado.
-[Usuário](lexicos.html#usuario) seleciona membro a ser adicionado.

------------------ -->
