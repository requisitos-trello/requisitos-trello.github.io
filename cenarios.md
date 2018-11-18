---
layout: default
title: Cenários
category: Modelagem
---

# Cenários

------------
## CN01 Cenário de Login

**Título:** [Login](lexicos.html#login)  comum 

**Objetivo:** Logar em uma conta do trello.

**Contexto:**
- **Pré-condição:** O [usuário](lexicos.html#usuário) precisará possuir uma conta na plataforma Trello e
possuir um dispositivo com acesso a internet.
- **Pós-condição:** O [usuário](lexicos.html#usuário) estará logado na aplicação, com acesso a seus
[Boards](lexicos.html#board)

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Dispositivo com acesso a um navegador ou ao aplicativo Trello, ambos devem
possuir conexão a internet.

**Episódios:**
- [Usuário](lexicos.html#usuário) entra na tela de [Login](lexicos.html#login)  da aplicação;
- [Usuário](lexicos.html#usuário) insere o endereço de e-mail de sua conta;
- [Usuário](lexicos.html#usuário) insere a senha de sua conta;
- [Usuário](lexicos.html#usuário) clica no botão ‘Fazer [Login](lexicos.html#login) ’;
- [Usuário](lexicos.html#usuário) estará logado na aplicação.

------------
## CN02 Cenário de Login com o Google

**Título:** [Login](lexicos.html#login) com o Google

**Objetivo:** Logar no Trello através de sua conta Google.

**Contexto:**
- **Pré-condição:** ​ O [usuário](lexicos.html#usuário) precisará possuir uma conta Google e possuir um
dispositivo com acesso a internet.
- **Pós-condição:** O [usuário](lexicos.html#usuário) estará logado na aplicação, com acesso a seus
[Boards](lexicos.html#board)

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Dispositivo com acesso a um navegador ou ao aplicativo Trello, ambos devem
possuir conexão a internet.

**Episódios:**
- [Usuário](lexicos.html#usuário) entra na tela de [Login](lexicos.html#login)  da aplicação;
- [Usuário](lexicos.html#usuário) clica em ‘Fazer [Login](lexicos.html#login)  com o Google’;
- [Usuário](lexicos.html#usuário) insere o endereço de e-mail ou telefone;
- [Usuário](lexicos.html#usuário) clica no botão ‘Próxima’;
- [Usuário](lexicos.html#usuário) insere a senha;
- [Usuário](lexicos.html#usuário) clica no botão ‘Próxima’;
- [Usuário](lexicos.html#usuário) estará logado na aplicação.

------------
## CN03 Cenário de Cadastro

**Título:** Cadastrar no Trello.

**Objetivo:** Cadastrar uma nova conta na plataforma Trello.

**Contexto:**
- **Pré-condição:** O [usuário](lexicos.html#usuário) precisará possuir um dispositivo com acesso a
internet e um e-mail não cadastrado no sistema do Trello.
- **Pós-condição:** O [usuário](lexicos.html#usuário) terá cadastrado uma nova conta e
automaticamente estará logado na aplicação.

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Dispositivo com acesso a um navegador ou ao aplicativo Trello, ambos devem
possuir conexão a internet.

**Episódios:**
- [Usuário](lexicos.html#usuário) entra na tela de cadastro da aplicação;
- [Usuário](lexicos.html#usuário) insere o seu nome;
- [Usuário](lexicos.html#usuário) insere o endereço de e-mail desejado;
- [Usuário](lexicos.html#usuário) insere a senha desejada;
- [Usuário](lexicos.html#usuário) clica no botão ‘Criar Nova Conta’;
- [Usuário](lexicos.html#usuário) estará cadastrado e logado na aplicação.

------------
## CN04 Cenário de Alterar Senha

**Título:**  ​Alterar senha.

**Objetivo:** Alterar senha de uma conta existente da plataforma Trello.

**Contexto:**
- **Pré-condição:** O [usuário](lexicos.html#usuário) precisará possuir um dispositivo com acesso a
internet e uma conta cadastrada no sistema do Trello.
- **Pós-condição:** O [usuário](lexicos.html#usuário) terá alterado a senha de sua conta.

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Dispositivo com acesso a um navegador ou ao aplicativo Trello, ambos devem
possuir conexão a internet.

**Episódios:**
- [Usuário](lexicos.html#usuário) entra na tela de ’Esqueceu sua senha?’;
- [Usuário](lexicos.html#usuário) insere o endereço de e-mail de sua conta;
- [Usuário](lexicos.html#usuário) clica no botão ‘Enviar’;
- [Usuário](lexicos.html#usuário) recebe um e-mail para redefinir sua senha;
- [Usuário](lexicos.html#usuário) abre o e-mail recebido;
- [Usuário](lexicos.html#usuário) clica no botão ‘Redefinir Senha’;
- [Usuário](lexicos.html#usuário) insere a nova senha;
- [Usuário](lexicos.html#usuário) insere a nova senha novamente;
- [Usuário](lexicos.html#usuário) clica no botão ‘Enviar’.

------------
## CN05 Cenário alterar configurações de Notificação

**Título:**  ​Alterar configurações de [Notificação](lexicos.html#notificar).

**Objetivo:** ​Alterar configurações de [Notificação](lexicos.html#notificar) da sua conta Trello.

**Contexto:**
- **Pré-condição:** O [usuário](lexicos.html#usuário) precisará possuir um dispositivo com acesso a
internet e estar logado em sua conta Trello.
- **Pós-condição:** O [usuário](lexicos.html#usuário) terá alterado as configurações de [Notificação](lexicos.html#notificar) de
sua conta.

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Dispositivo com acesso a um navegador ou ao aplicativo Trello, ambos devem
possuir conexão a internet.

**Episódios:**
- [Usuário](lexicos.html#usuário) entra na tela em suas notificações;
- [Usuário](lexicos.html#usuário) clica em ‘Alterar Frequência de [Notificação](lexicos.html#notificar) por Email’;
- [Usuário](lexicos.html#usuário) seleciona uma das três opções: Nunca, Periodicamente e
Instantaneamente;
- [Usuário](lexicos.html#usuário) terá alterado a frequência de notificações por e-mail;
- [Usuário](lexicos.html#usuário) clica em ‘Permitir [Notificação](lexicos.html#notificar) da Área de Trabalho’;
- [Usuário](lexicos.html#usuário) terá permitido a aplicação a exibir [Notificação](lexicos.html#notificar) da Área de Trabalho.

------------
## CN06 Cenário ver notificações

**Título:**  ​Ver [Notificações](lexicos.html#notificar).

**Objetivo:** ​Ver [Notificações](lexicos.html#notificar) da sua conta Trello.

**Contexto:**
- **Pré-condição:** O [usuário](lexicos.html#usuário) precisará possuir um dispositivo com acesso a
internet e estar logado em sua conta Trello.
- **Pós-condição:** O [usuário](lexicos.html#usuário) terá visto as [Notificações](lexicos.html#notificar) de sua conta, caso
exista.

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Dispositivo com acesso a um navegador ou ao aplicativo Trello, ambos devem
possuir conexão a internet.

**Episódios:**
- [Usuário](lexicos.html#usuário) abre a página inicial;
- [Usuário](lexicos.html#usuário) clica na imagem de um sino na parte superior direita de sua tela;
- [Usuário](lexicos.html#usuário) entra na tela de suas [Notificações](lexicos.html#notificar);
- [Usuário](lexicos.html#usuário) vê suas [Notificações](lexicos.html#notificar), caso exista alguma notificação não lida.

------------
## CN07 Cenário criar time

**Título:** ​Criar [Time](lexicos.html#time).

**Objetivo:** ​Criar um [Time](lexicos.html#time) na plataforma Trello.

**Contexto:**
- **Pré-condição:** ​ O [usuário](lexicos.html#usuário) precisará possuir um dispositivo com acesso a
internet e estar logado em sua conta Trello.
- **Pós-condição:** ​O [usuário](lexicos.html#usuário) terá criado um novo [Time](lexicos.html#time).

**Atores:** ​[Usuário](lexicos.html#usuário).

**Recursos:** ​Dispositivo com acesso a um navegador ou ao aplicativo Trello, ambos devem
possuir conexão a internet.

**Episódios:**
- [Usuário](lexicos.html#usuário) abre a página inicial;
- [Usuário](lexicos.html#usuário) clica em ‘Criar um time’;
- [Usuário](lexicos.html#usuário) insere o nome do [Time](lexicos.html#time);
- [Usuário](lexicos.html#usuário) insere a descrição do [Time](lexicos.html#time) (opcional);
- [Usuário](lexicos.html#usuário) clica no botão ‘Criar’;
- [Usuário](lexicos.html#usuário) terá criado um novo [Time](lexicos.html#time).

------------
## CN08 Cenário convidar [Usuários](lexicos.html#usuário) para um time

**Título:** ​Convidar [Usuários](lexicos.html#usuário) para um [Time](lexicos.html#time).

**Objetivo:** ​Convidar [Usuários](lexicos.html#usuário) da plataforma Trello para participar de um [Time](lexicos.html#time).

**Contexto:**
- **Pré-condição:** ​ O  [usuário](lexicos.html#usuário)precisará possuir um dispositivo com acesso a
internet e estar logado em sua conta Trello.
- **Pós-condição:** ​O  [usuário](lexicos.html#usuário)terá convidado um ou mais [Usuários](lexicos.html#usuário) para seu [Time](lexicos.html#time).

**Atores:** [Usuário](lexicos.html#usuário)​

**Recursos:** ​Dispositivo com acesso a um navegador ou ao aplicativo Trello, ambos devem
possuir conexão a internet.

**Episódios:**
- [Usuário](lexicos.html#usuário) abre a página do [Time](lexicos.html#time);
- [Usuário](lexicos.html#usuário) clica no botão ‘Membros’;
- [Usuário](lexicos.html#usuário) insere o nome do  [usuário](lexicos.html#usuário)a ser convidado;
- [Usuário](lexicos.html#usuário) clica no botão ‘Convidar para o Time’;
- [Usuário](lexicos.html#usuário) terá convidado um [usuário](lexicos.html#usuário) para seu [Time](lexicos.html#time).

------------
## CN09 Cenário de imprimir Board

**Título:** Impressão de [Board](lexicos.html#board) 

**Objetivo:** Passar algumas informações de à [Board](lexicos.html#board) para uma folha de papel.

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#usuário) deve ter acesso à [Board](lexicos.html#board) que quer imprimir.
- **Pós-condição:** A aplicação deverá comunicar ao browser que uma impressão está sendo solicitada.

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Dispositivo desktop com browser compatível com os recursos do Trello e com acesso à impressora, além da impressora devidamente preparada para impressão.

**Episódios:**
- [Usuário](lexicos.html#usuário) realiza [Login](lexicos.html#login) ;
- [Usuário](lexicos.html#usuário) acessa a [Board](lexicos.html#board) desejada;
- [Usuário](lexicos.html#usuário) abre o [Menu lateral]();
- [Usuário](lexicos.html#usuário) seleciona a opção **Mais**;
- [Usuário](lexicos.html#usuário) seleciona a opção **Imprimir e Exportar**;
- [Usuário](lexicos.html#usuário) seleciona a opção **Imprimir...**;
- A aplicação converte a [Board](lexicos.html#board) para um formato imprimível;
- Browser faz a comunicação com o Sistema Operacional, que por sua vez comunica-se com a impressora.

--------------
## CN10 Cenário de adicionar [Stickers](lexicos.html#sticker)

**Título:** Adição de [Stickers](lexicos.html#sticker)

**Objetivo:** Adição de elementos visuais que facilitem a orientação intuitiva e visual do [Usuário](lexicos.html#usuário) pela [Board](lexicos.html#board).

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#usuário) deve ter acesso à [Board](lexicos.html#board) na qual quer adicionar [stickers](lexicos.html#sticker).
- **Pós-condição:** Um [sticker](lexicos.html#sticker) deve ser adicionado a um [Card](lexicos.html#card) na [Board](lexicos.html#board) em questão.

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Acesso à aplicação web por meio de browser em um dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#usuário) faz [Login](lexicos.html#login) ;
- [Usuário](lexicos.html#usuário) acessa a [Board](lexicos.html#board) desejada;
- [Usuário](lexicos.html#usuário) abre o [Menu Lateral]();
- [Usuário](lexicos.html#usuário) seleciona a opção **[Stickers](lexicos.html#sticker)**;
- [Usuário](lexicos.html#usuário) clica e arrasta o Sticker desejado até o [Card](lexicos.html#card) desejado;

--------------
## CN11 Cenário de editar/remover [Stickers](lexicos.html#sticker)

**Título:** Edição de [Stickers](lexicos.html#sticker)

**Objetivo:** Tornar possível editar a posição ou a exclusão de um [sticker](lexicos.html#sticker) existente num [card](lexicos.html#card)

**Contexto:**
- **Pré-condição:** Deve existir um [sticker](lexicos.html#sticker) em uma [Board](lexicos.html#board) com o acesso do [Usuário](lexicos.html#usuário) que queira remover ou editar este mesmo [sticker](lexicos.html#sticker).
- **Pós-condição:** O [sticker](lexicos.html#sticker) será movido para a nova posição, caso tenha sido movido. Caso removido, o [sticker](lexicos.html#sticker) deixará de existir.

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#usuário) faz [Login](lexicos.html#login) ;
- [Usuário](lexicos.html#usuário) acessa a [Board](lexicos.html#board) em questão;
- [Usuário](lexicos.html#usuário) clica com o botão direito do mouse no [Card](lexicos.html#card)  de onde quer mover o [sticker](lexicos.html#sticker);
- [Usuário](lexicos.html#usuário) clica com o botão esquerdo do mouse no [sticker](lexicos.html#sticker) que quer editar;
- [Usuário](lexicos.html#usuário) seleciona uma das opções: **Girar**, **Mover** ou **Remover** segundo sua vontade;
- Em caso de **Girar** ou **Mover**, o [Usuário](lexicos.html#usuário) clica e segura com o botão esquerdo do mouse, movendo o cursos até que o [sticker](lexicos.html#sticker) alcance a posição desejada;

**Exceção:** Falta de conexão com a internet após tentar adicionar o [sticker](lexicos.html#sticker), queda de energia.

--------------
## CN12 Cenário de Alterar Tela de Fundo

**Título:** Alteração da Tela de Fundo de uma [Board](lexicos.html#board)

**Objetivo:** Possibilitar a personalização da [Board](lexicos.html#board) pelo [Usuário](lexicos.html#usuário) por meio de uma imagem de fundo nova de sua escolha.

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#usuário) deve ter acesso à [Board](lexicos.html#board) a qual quer alterar o plano de fundo.
- **Pós-condição:** A tela de fundo dessa [Board](lexicos.html#board) será alterada.

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#usuário) faz [Login](lexicos.html#login) ;
- [Usuário](lexicos.html#usuário) acessa a [Board](lexicos.html#board) cujo plano quer alterar;
- [Usuário](lexicos.html#usuário) abre o [Menu Lateral]();
- [Usuário](lexicos.html#usuário) seleciona a opção **Alterar Tela de Fundo**;
- [Usuário](lexicos.html#usuário) seleciona entre as opções **Cores** ou **Fotos**;
    - Caso o [Board](lexicos.html#board) seja de um [time](lexicos.html#time) [Business Class](), a opção **Personalizar** também estará disponível;
- Caso tenha selecionado **Cores**, o [Usuário](lexicos.html#usuário) escolhe uma entre as nove cores disponíveis, ou clica na **seta à esqueda** para voltar à tela anterior;
- Caso tenha selecionado **Fotos**, o usário escollhe uma entre as inúmeras fotos disponibilizadas pelo Unsplash em colaboração com o Trello ou clica na **seta à esqueda** para voltar à tela anterior;
    - É possível pesquisar por termos e a aplicação retornará imagens marcadas com os termos pesquisados.

**Exceção:** Imagem inválida (tamanho grande ou pequeno demais ou extensão incompatível), queda de energia ou de queda de conexão com a internet.

--------------
## CN13 Cenário de Filtrar Cartões

**Título:** Pesquisa de [Cards](lexicos.html#card)

**Objetivo:** Pesquisa [cards](lexicos.html#card) em relação ao seu conteúdo de acordo com os termos de pesquisa inseridos.

**Contexto:**
- **Pré-condição:** Pesquisa realizada pelo [Usuário](lexicos.html#usuário) em uma [Board](lexicos.html#board) à qual o [Usuário](lexicos.html#usuário) tenha acesso.
- **Pós-condição:** Deverão aparecer na tela apenas os [cards](lexicos.html#card) que atendam às características solicitadas na pesquisa.

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#usuário) faz [Login](lexicos.html#login) ;
- [Usuário](lexicos.html#usuário) acessa a [Board](lexicos.html#board) onde estão os cards que ele procura;
- [Usuário](lexicos.html#usuário) abre o [Menu Lateral]() e seleciona a opção **Filtrar Cartões**;
    - [Usuário](lexicos.html#usuário) pode digitar termos contidos nos títulos dos cards que está procurando;
    - [Usuário](lexicos.html#usuário) pode selecionar [Etiquetas]() contidas nos cards que está procurando;
    - [Usuário](lexicos.html#usuário) pode [membro](lexicos.html#membro) assinalados nos cards que está procurando;
    - [Usuário](lexicos.html#usuário) pode selecionar opções de [data de entrega](lexico.html#duedate):
        - Entregas em um dia;
        - Entregas em uma semana;
        - Entregas emm um mês;
        - Em atraso;
        - Sem [data de entrega](lexico.html#duedate);
        - [Data de entrega](lexico.html#duedate) marcada como concluída;
        - Não marcado como concluído;
    - [Usuário](lexicos.html#usuário) pode selecionar se as buscas por etiquetas e [membros](lexicos.html#membro) seguem lógica AND (todos os [membros](lexicos.html#membro) e etiquetas procurados devem estar contido nos cards procurados) ou se seguem lógica OR (qualquer [Card](lexicos.html#card) que contenha um membro ou etiqueta procurados se enquadra na pesquisa).
- Aparece um texto na parte superior da [Board](lexicos.html#board) indicando que a busca está ativada e, por isso, alguns cards podem estar sendo omitidos;
    - Para encerrar a filtragem, o [Usuário](lexicos.html#usuário) pode clicar no X ao lado deste texto.

--------------
## CN14 Cenário de [Copiar](lexico.html#copiar) um Quadro

**Título:** Cópia de [Board](lexicos.html#board)

**Objetivo:** Criação de um [Board](lexicos.html#board) com algumas características iguais às de um [Board](lexicos.html#board) específico.

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#usuário) deve ter acesso à [Board](lexicos.html#board) que quer [copiar](lexico.html#copiar).
- **Pós-condição:** Será criada uma nova [Board](lexicos.html#board) com algumas características trazidas de outra.

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#usuário) faz [Login](lexicos.html#login) ;
- [Usuário](lexicos.html#usuário) acessa a [Board](lexicos.html#board) que quer [copiar](lexico.html#copiar);
- [Usuário](lexicos.html#usuário) abre o [Menu Lateral]() e seleciona a opção **Mais**;
- [Usuário](lexicos.html#usuário) seleciona a opção **Copiar Quadro**;
- [Usuário](lexicos.html#usuário) digita um título para o novo [Board](lexicos.html#board) que será criado;
- Opcionalmente, o [Usuário](lexicos.html#usuário) escolhe um [time](lexicos.html#time) do qual faça parte para popular o novo quadro;
- [Usuário](lexicos.html#usuário) decide a visibilidade do quadro (se é particular, de visibilidade apenas do [time](lexicos.html#time) ou se é público);
- [Usuário](lexicos.html#usuário) decide se quer [copiar](lexico.html#copiar), também, os [Cards]() contidos no [Board](lexicos.html#board) atual.
- É criada uma nova [Board](lexicos.html#board);
 
--------------
## CN15 Cenário de Seguir Quadro

**Título:** [Seguir]() uma [Board](lexicos.html#board)

**Objetivo:** Ser [notificado](lexico.html#notificar) de alterações que aconteçam em uma [Board](lexicos.html#board)

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#usuário) deve ter acesso à [Board](lexicos.html#board) que quer seguir.
- **Pós-condição:** O [Usuário](lexicos.html#usuário) será [notificado](lexico.html#notificar) de alterações que ocorrerem na [Board](lexicos.html#board) em questão.

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop ou acesso aplicação mobile conectada à internet.

**Episódios:**
- [Usuário](lexicos.html#usuário) faz [Login](lexicos.html#login) ;
- [Usuário](lexicos.html#usuário) acessa a [Board](lexicos.html#board) que quer seguir;
- [Usuário](lexicos.html#usuário) abre o [Menu Lateral]() e seleciona a opção **Seguir**;
- O sistema passa a [notificar](lexico.html#notificar) o [Usuário](lexicos.html#usuário) em seu e-mail e no espaço de [notificações](lexico.html#notificar) do Trello;
- Aparece um texto no canto superior esquerdo da [Board](lexicos.html#board) indicando que o [Usuário](lexicos.html#usuário) está seguindo esta [Board](lexicos.html#board).
- O [Usuário](lexicos.html#usuário) pode selecionar novamente a opção **Seguir** para parar de seguir, ou clicar no texto recém-aparecido que ascenderá um botão **Parar de seguir**.

--------------
## CN16 Cenário de Fechar um Quadro

**Título:** Fechamento de [Board](lexicos.html#board)

**Objetivo:** Enviar a [Board](lexicos.html#board) para um espaço equivalente à lixeira, onde não são imediatamente excluídos mas não mais dividem espaço com outras[Boards](lexicos.html#board).

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#usuário) deve ser criador do [Board](lexicos.html#board) que quer fechar.
- **Pós-condição:** O [Board](lexicos.html#board) deve sair do espaço de[Boards](lexicos.html#board) do [Usuário](lexicos.html#usuário), sem necessariamente ser excluído.

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#usuário) faz [Login](lexicos.html#login) ;
- [Usuário](lexicos.html#usuário) acessa a [Board](lexicos.html#board) que deseja fechar;
- [Usuário](lexicos.html#usuário) abre o [Menu Lateral]() e seleciona a opção **Mais**;
- [Usuário](lexicos.html#usuário) seleciona a opção **Fechar Quadro...**;
- [Usuário](lexicos.html#usuário) clica no botão vermelhor **Fechar**;

------------
## CN17 Cenário de Exportar um Quadro para JSON

**Título:** Exportação de [Board](lexicos.html#board) para JSON 

**Objetivo:** Passar algumas informações de à [Board](lexicos.html#board) para o formato JSON.

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#usuário) deve ter acesso à [Board](lexicos.html#board) que quer exportar.
- **Pós-condição:** A aplicação deverá retornar um código JSON que reflita o atual estado da [Board](lexicos.html#board).

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#usuário) realiza [Login](lexicos.html#login) ;
- [Usuário](lexicos.html#usuário) acessa a [Board](lexicos.html#board) desejada;
- [Usuário](lexicos.html#usuário) abre o [Menu lateral]();
- [Usuário](lexicos.html#usuário) seleciona a opção **Mais**;
- [Usuário](lexicos.html#usuário) seleciona a opção **Imprimir e Exportar**;
- [Usuário](lexicos.html#usuário) seleciona a opção **Exportar como JSON**;
- A aplicação redireciona para uma página que contém apenas o código JSON da [Board](lexicos.html#board);

------------
## CN18 Cenário de Retirar Membros de um [Time](lexicos.html#time)

**Título:** Retirar [membros](lexicos.html#membro) de um [time](lexicos.html#time).

**Objetivo:** Com isto é possível remover um membro de um [time](lexicos.html#time).

**Contexto:**
- **Pré-condição:** O [usuário](lexicos.html#usuário) deve ser [administrador](lexicos.html#administrador) do [Time](lexicos.html#time) e deve ter ao menos um membro além do [administrador](lexicos.html#administrador).
- **Pós-condição:** [Usuário](lexicos.html#usuário) retirado deixará de ser membro do [time](lexicos.html#time).

**Atores:** [Administrador](lexicos.html#administrador) do [time](lexicos.html#time), membro do [time](lexicos.html#time).

**Recursos:** Conta, [time](lexicos.html#time), membro, computador, internet.

**Episódios:**
- [Administrador](lexicos.html#administrador) entra no Trello.
- [Administrador](lexicos.html#administrador) realiza [Login](lexicos.html#login).
- Se há [time](lexicos.html#time), [Administrador](lexicos.html#administrador) acessa [time](lexicos.html#time).
- Senão, fluxo encerrado. (exceção)
- [Administrador](lexicos.html#administrador) acessa [Lista](lexicos.html#lista) de [membros](lexicos.html#membro).
- Se há [membros](lexicos.html#membro), [Administrador](lexicos.html#administrador) EXCLUI MEMBRO que deseja.
- Senão, fluxo encerrado. (exceção)


------------
## CN19 Cenário de Editar Descrição de [Time](lexicos.html#time)

**Título:** Editar descrição de [time](lexicos.html#time).

**Objetivo:** Permite editar o texto atual da descrição de um [time](lexicos.html#time) a qual o [Usuário](lexicos.html#usuário) tenha acesso.

**Contexto:**
- **Pré-condição:** O [usuário](lexicos.html#usuário) deve ser [administrador](lexicos.html#administrador) do [time](lexicos.html#time).
- **Pós-condição:** O [time](lexicos.html#time) deverá possuir uma nova descrição.

**Atores:** [Administrador](lexicos.html#administrador) do [time](lexicos.html#time).

**Recursos:** Conta, [time](lexicos.html#time), computador, internet.

**Restrição:** O [time](lexicos.html#time) deve existir, o [usuário](lexicos.html#usuário) deve ser [administrador](lexicos.html#administrador) do [time](lexicos.html#time).

**Exceção:** Queda de energia, falta de conexão com a internet ou [usuário](lexicos.html#usuário) não pertence mais ao [time](lexicos.html#time)

**Episódios:**
- [Administrador](lexicos.html#administrador) entra no Trello.
- [Administrador](lexicos.html#administrador) realiza [Login](lexicos.html#login).
- Se há [time](lexicos.html#time), [Administrador](lexicos.html#administrador) acessa time.
- Senão, fluxo encerrado. (Exceção)
- [Administrador](lexicos.html#administrador) acessa editar perfil.
- [Administrador](lexicos.html#administrador) edita descrição do [time](lexicos.html#time).


------------
## CN20 Cenário de Editar Visibilidade do [Time](lexicos.html#time)

**Título:** Editar visibilidade do [time](lexicos.html#time).

**Objetivo:** Permite restringir ou habilitar a visualisação do [time](lexicos.html#time) a um ou mais [Usuários](lexicos.html#usuário) que pertençam à [board](lexicos.html#board) a fim de preservar a privacidade dos [usuários](lexicos.html#usuário) de um [time](lexicos.html#time).

**Contexto:**
- **Pré-condição:** O [usuário](lexicos.html#usuário) deve ser [administrador](lexicos.html#administrador) do [time](lexicos.html#time).
- **Pós-condição:** O [time](lexicos.html#time) deverá ter sua visibilidade alterada.

**Atores:** [Administrador](lexicos.html#administrador) do [time](lexicos.html#time).

**Recursos:** Conta, [time](lexicos.html#time), computador, internet.

**Exceção:** Queda de energia, falta de conexão com a internet.

**Episódios:**
- [Usuário](lexicos.html#usuário) entra no Trello.
- [Usuário](lexicos.html#usuário) realiza [Login](lexicos.html#login).
- Se há [time](lexicos.html#time), [Usuário](lexicos.html#usuário) acessa time.
- Senão, fluxo encerrado.  (exceção)
- [Usuário](lexicos.html#usuário) acessa configurações do time.
- [Usuário](lexicos.html#usuário) acessa alterar visibilidade do time.
- [Usuário](lexicos.html#usuário) edita visibilidade do [time](lexicos.html#time).


------------
## CN21 Cenário de [Vincular](lexicos.html#vincular) [Time](lexicos.html#time) ao Slack

**Título:** [Vinculação](lexicos.html#vincular) [Time](lexicos.html#time) ao Slack.

**Objetivo:** Adicionar interoperabilidade entre o [Time](lexicos.html#time) e a plataforma Slack, habilidando o compartilhamento de dados entre ambas.

**Contexto:**
- **Pré-condição:** O [usuário](lexicos.html#usuário) deve ser [administrador](lexicos.html#administrador) do [time](lexicos.html#time).
- **Pós-condição:** O [time](lexicos.html#time) deverá ser vinculado a [time](lexicos.html#time) do Slack.

**Atores:** [Administrador](lexicos.html#administrador) do [time](lexicos.html#time).

**Recursos:** Conta, [time](lexicos.html#time), computador, internet.

**Restrição:** [Administrador](lexicos.html#administrador) deve possuir conta e canal no slack.

**Exceção:** Não há [time](lexicos.html#time), não há conta nem canal no slack.

**Episódios:**
- [Administrador](lexicos.html#administrador) entra no Trello.
- [Administrador](lexicos.html#administrador) realiza [Login](lexicos.html#login).
- Se há [time](lexicos.html#time), [Administrador](lexicos.html#administrador) acecssa time.
- Senão, [Administrador](lexicos.html#administrador) cria time. (restrição)
- [Administrador](lexicos.html#administrador) acessa configurações do time.
- [Administrador](lexicos.html#administrador) acessa ADD TO SLACK.
- Se há conta no slack, [Administrador](lexicos.html#administrador) realiza [Login](lexicos.html#login) em sua conta do slack.
- Senão [Administrador](lexicos.html#administrador) cria conta no slack.
- Se há canal no slack do [Administrador](lexicos.html#administrador), [Administrador](lexicos.html#administrador) [VINCULA](lexicos.html#vincular) TIME COM O SLACK.
- Senão [Administrador](lexicos.html#administrador) cria canal no slack e realiza o passo anterior.


------------
## CN22 Cenário de Permitir Membro Comentar em um [Board](lexicos.html#board) 

**Título:** Permitir membro comentar em um [Board](lexicos.html#board).

**Objetivo:** Permitir a alteração das permissões de membro com relação a comentar em um [Board](lexicos.html#board).

**Contexto:** 
- **Pré-condição:** O [usuário](lexicos.html#usuário) deve ser [administrador](lexicos.html#administrador) do [time](lexicos.html#time).
- **Pós-condição:** Membros poderão comentar em um [Board](lexicos.html#board).

**Atores:** [Administrador](lexicos.html#administrador) do [time](lexicos.html#time).

**Recursos:** Conta, [time](lexicos.html#time), [Board](lexicos.html#board), [Lista](lexicos.html#lista), card, comentário, computador, internet.

**Episódios:**
- [Administrador](lexicos.html#administrador) entra no Trello.
- [Administrador](lexicos.html#administrador) realiza [Login](lexicos.html#login).
- Se há [time](lexicos.html#time), [Administrador](lexicos.html#administrador) acessa time.
- Senão, [Administrador](lexicos.html#administrador) cria time. (restrição)
- Se há [Board](lexicos.html#board), [Administrador](lexicos.html#administrador) acessa[board](lexicos.html#board) do [time](lexicos.html#time).
- Senão, [Administrador](lexicos.html#administrador) cria [board](lexicos.html#board) do [time](lexicos.html#time).
- [Administrador](lexicos.html#administrador) acessa menu da [Board](lexicos.html#board).
- [Administrador](lexicos.html#administrador) acessa mais opções do menu.
- [Administrador](lexicos.html#administrador) acessa configurações.
- [Administrador](lexicos.html#administrador) acessa permissões para comentários.
- [Administrador](lexicos.html#administrador) seleciona [membros](lexicos.html#membro).


------------
## CN23 Cenário de Negar [Membro](lexicos.html#membro) Ingressar em um [Board](lexicos.html#board) 

**Título:** Negar [membro](lexicos.html#membro) ingressar em um [Board](lexicos.html#board).

**Objetivo:** Altera a permissão de um [membro](lexicos.html#membro) de time de ingressar em um [Board](lexicos.html#board).

**Contexto:** 
- **Pré-condição:** O [usuário](lexicos.html#usuário) deve ser [administrador](lexicos.html#administrador) do [time](lexicos.html#time).
- **Pós-condição:** [membro](lexicos.html#membro)s não poderão ingressar em um [Board](lexicos.html#board) sem serem convidados.

**Atores:** [Administrador](lexicos.html#administrador) do [time](lexicos.html#time).

**Recursos:** Conta, [time](lexicos.html#time), computador, internet.

**Episódios:**
- [Administrador](lexicos.html#administrador) entra no Trello.
- [Administrador](lexicos.html#administrador) realiza [Login](lexicos.html#login).
- Se há [time](lexicos.html#time), [Administrador](lexicos.html#administrador) acessa time.
- Senão, [Administrador](lexicos.html#administrador) CRIA TIME. (restrição)
- Se há [Board](lexicos.html#board), [Administrador](lexicos.html#administrador) acessa [board](lexicos.html#board) do [time](lexicos.html#time).
- Senão, [Administrador](lexicos.html#administrador) cria [board](lexicos.html#board) do [time](lexicos.html#time). (restrição)
- [Administrador](lexicos.html#administrador) acessa menu da [Board](lexicos.html#board).
- [Administrador](lexicos.html#administrador) acessa mais opções do menu.
- [Administrador](lexicos.html#administrador) acessa configurações.
- Se estiver ativo, [Administrador](lexicos.html#administrador) clica em permitir ingresso de [membros](lexicos.html#membro) do time.
- Senão, a permissão já foi negada.

## CN24 Cenário de Ver [Lista](lexicos.html#lista)

**Título:** Ver [Lista](lexicos.html#lista) 

**Objetivo:** Mostrar o conteúdo de uma [Lista](lexicos.html#lista) para o [Usuário](lexicos.html#usuário).

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#usuário) deve ter acesso à [Lista](lexicos.html#lista) que quer visualizar.
- **Pós-condição:** A aplicação deverá mostrar a [Lista](lexicos.html#lista) para o [Usuário](lexicos.html#usuário).

**Atores:** [Usuário](lexicos.html#usuário)

**Restrições** 

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#usuário) realiza [LOGIN](#cenário-de-login);
- Se não há [Board](lexicos.html#board), [Usuário](lexicos.html#usuário) realiza [CRIAR BOARD](#criar-board);
- [Usuário](lexicos.html#usuário) realiza [VER BOARD](#ver-um-board);
- Se não há [Lista](lexicos.html#lista), [Usuário](lexicos.html#usuário) realiza [CRIAR LISTA](#cenário-de-criar-lista);
- [Usuário](lexicos.html#usuário) realiza [VER LISTA](#cenário-de-ver-lista);
- A aplicação mostra a [Lista](lexicos.html#lista) desejada para o [Usuário](lexicos.html#usuário).


------------
# Cards

## CN25 Cenário de Criar Card

**Título:** Criar [Card](lexicos.html#card)  

**Objetivo:** Criar um novo [Card](lexicos.html#card)  para armazenar dados dentro de uma [Lista](lexicos.html#lista).

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#usuário) deve ter acesso à [Lista](lexicos.html#lista) onde quer criar o [Card](lexicos.html#card) .
- **Pós-condição:** A aplicação deverá criar o [Card](lexicos.html#card)  dentro da [Lista](lexicos.html#lista) para o [Usuário](lexicos.html#usuário).

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#usuário) realiza [Login](lexicos.html#login);
- Se não há [Board](lexicos.html#board), [Usuário](lexicos.html#usuário) realiza [CRIAR BOARD](#criar-board);
- [Usuário](lexicos.html#usuário) realiza [VER BOARD](#ver-um-board);
- Se não há [Lista](lexicos.html#lista), [Usuário](lexicos.html#usuário) realiza [CRIAR LISTA](#cenário-de-criar-lista);
- [Usuário](lexicos.html#usuário) realiza [VER LISTA](#cenário-de-ver-lista);
- [Usuário](lexicos.html#usuário) realiza [CRIAR CARD](#cenário-de-criar-card)
- A aplicação mostra a [Lista](lexicos.html#lista) desejada para o [Usuário](lexicos.html#usuário).

------------
## CN26 Cenário de Modificar Card

**Título:** Modificar [Card](lexicos.html#card)  

**Objetivo:** Modificar um [Card](lexicos.html#card)  existente para atualizar os seus dados dentro de uma [Lista](lexicos.html#lista).

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#usuário) deve ter acesso à [Lista](lexicos.html#lista) onde está o [Card](lexicos.html#card) .
- **Pós-condição:** A aplicação deverá atualizar o [Card](lexicos.html#card)  com os novos dados.

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#usuário) realiza [Login](lexicos.html#login);
- Se não há [Board](lexicos.html#board), [Usuário](lexicos.html#usuário) realiza [CRIAR BOARD](#criar-board);
- [Usuário](lexicos.html#usuário) realiza [VER BOARD](#ver-um-board);
- Se não há [Lista](lexicos.html#lista), [Usuário](lexicos.html#usuário) realiza [CRIAR LISTA](cenário-de-criar-lista);
- [Usuário](lexicos.html#usuário) realiza [VER LISTA][cenário-de-ver-lista);
- Se não há [Card](lexicos.html#card) , [Usuário](lexicos.html#usuário), realiza [CRIAR CARD](#cenário-de-criar-card);
- [Usuário](lexicos.html#usuário) realiza [VER CARD](#cenário-de-criar-card);
- [Usuário](lexicos.html#usuário) realiza [MODIFICAR CARD](#cenário-de-modificar-card);
- A aplicação mostra uma janela de edição para o [Card](lexicos.html#card)  desejado para o [Usuário](lexicos.html#usuário).

------------
## CN27 Cenário de Ver Card

**Título:** Ver [Card](lexicos.html#card)  

**Objetivo:** Visualizar um [Card](lexicos.html#card)  existente para mostrar o seu conteúdo para o [Usuário](lexicos.html#usuário).

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#usuário) deve ter acesso à [Lista](lexicos.html#lista) onde está o [Card](lexicos.html#card) .
- **Pós-condição:** A aplicação deverá mostrar o [Card](lexicos.html#card)  com seu conteúdo.

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#usuário) realiza [Login](lexicos.html#login);
- Se não há [Board](lexicos.html#board), [Usuário](lexicos.html#usuário) realiza [CRIAR BOARD](#criar-board);
- [Usuário](lexicos.html#usuário) realiza [VER BOARD](#ver-um-board);
- Se não há [Lista](lexicos.html#lista), [Usuário](lexicos.html#usuário) realiza [CRIAR LISTA](#cenário-de-criar-lista);
- [Usuário](lexicos.html#usuário) realiza [VER LISTA](#cenário-de-ver-lista);
- Se não há [Card](lexicos.html#card) , [Usuário](lexicos.html#usuário), realiza [CRIAR CARD](#cenário-de-criar-card);
- [Usuário](lexicos.html#usuário) realiza [VER CARD](#cenário-de-ver-card);
- A aplicação mostra uma janela com os dados do [Card](lexicos.html#card)  desejado para o [Usuário](lexicos.html#usuário).

------------
## CN28 Cenário de Seguir Card

**Título:** Seguir [Card](lexicos.html#card)  

**Objetivo:** Seguir um [Card](lexicos.html#card)  existente para ser [notificado](lexico.html#notificar) de mudanças por meios de [notificações](lexico.html#notificar) para o [Usuário](lexicos.html#usuário).

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#usuário) deve ter acesso à [Lista](lexicos.html#lista) onde está o [Card](lexicos.html#card) .
- **Pós-condição:** A aplicação deverá [notificar](lexico.html#notificar) o [usuáro]() quando o [Card](lexicos.html#card)  for modificado.

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#usuário) realiza [Login](lexicos.html#login);
- Se não há [Board](lexicos.html#board), [Usuário](lexicos.html#usuário) realiza [CRIAR BOARD](#criar-um-board);
- [Usuário](lexicos.html#usuário) realiza [VER BOARD](#ver-um-board);
- Se não há [Lista](lexicos.html#lista), [Usuário](lexicos.html#usuário) realiza [CRIAR LISTA](#cenário-de-criar-lista);
- [Usuário](lexicos.html#usuário) realiza [VER LISTA](#cenário-de-ver-lista);
- Se não há [Card](lexicos.html#card) , [Usuário](lexicos.html#usuário), realiza [CRIAR CARD](#cenário-de-criar-card);
- [Usuário](lexicos.html#usuário) realiza [VER CARD](#cenário-de-ver-card);
- [Usuário](lexicos.html#usuário) realiza [SEGUIR CARD](#cenário-de-seguir-card) pressionando o botão seguir;
- A aplicação retorna à tela de [VER CARD](#cenário-de-ver-card).

------------
## CN29 Cenário de [Arquivar](lexicos.html#arquivar) Card

**Título:** [Arquivar](lexicos.html#arquivar) [Card](lexicos.html#card)  

**Objetivo:** [Arquivar](lexicos.html#arquivar) um [Card](lexicos.html#card)  existente para removê-lo de uma [Lista](lexicos.html#lista) sem perder seus dados.

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#usuário) deve ter acesso à [Lista](lexicos.html#lista) onde está o [Card](lexicos.html#card) .
- **Pós-condição:** A aplicação deverá [Arquivar](lexicos.html#arquivar) o [Card](lexicos.html#card)  selecionado.

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#usuário) realiza [Login](lexicos.html#login);
- Se não há [Board](lexicos.html#board), [Usuário](lexicos.html#usuário) realiza [CRIAR BOARD](#criar-board);
- [Usuário](lexicos.html#usuário) realiza [VER BOARD](#ver-um-board);
- Se não há [Lista](lexicos.html#lista), [Usuário](lexicos.html#usuário) realiza [CRIAR LISTA](#cenário-de-criar-lista);
- [Usuário](lexicos.html#usuário) realiza [VER LISTA](#cenário-de-ver-lista);
- Se não há [Card](lexicos.html#card) , [Usuário](lexicos.html#usuário), realiza [CRIAR CARD](#cenário-de-criar-card);
- [Usuário](lexicos.html#usuário) realiza [VER CARD](#cenário-de-ver-card);
- [Usuário](lexicos.html#usuário) realiza [ARQUIVAR CARD](#cenário-de-arquivar-card) pressionando o botão [Arquivar](lexicos.html#arquivar);
- A aplicação retorna à tela de [VER LISTA]().

------------
## CN30 Cenário de Personalizar [Label](lexicos.html#label)

**Título:** Personalizar [Label](lexicos.html#label) 

**Objetivo:** Personalizar a [Label](lexicos.html#label) atribuído à um [Card](lexicos.html#card) para diferenciar ou destacá-lo em relação aos outros.

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#usuário) deve ter acesso à [Lista](lexicos.html#lista) onde está o [Card](lexicos.html#card) .
- **Pós-condição:** A aplicação deverá mostrar o [Card](lexicos.html#card)  com seu novo [Label]().

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#usuário) realiza [Login](lexicos.html#login);
- Se não há [Board](lexicos.html#board), [Usuário](lexicos.html#usuário) realiza [CRIAR BOARD](#criar-board);
- [Usuário](lexicos.html#usuário) realiza [VER BOARD](#ver-um-board);
- Se não há [Lista](lexicos.html#lista), [Usuário](lexicos.html#usuário) realiza [CRIAR LISTA](#cenário-de-criar-lista);
- [Usuário](lexicos.html#usuário) realiza [VER LISTA](#cenário-de-ver-lista);
- Se não há [Card](lexicos.html#card) , [Usuário](lexicos.html#usuário), realiza [CRIAR CARD](#cenário-de-criar-card);
- [Usuário](lexicos.html#usuário) realiza [VER CARD](#cenário-de-ver-card);
- [Usuário](lexicos.html#usuário) realiza [PERSONALIZAR LABEL](#cenário-de-personalizar-label);
- A aplicação mostra uma janela com opções de persnoalização para o [Label](lexicos.html#label) para o [Usuário](lexicos.html#usuário).

------------
## CN31 Cenário de Adicionar [Anexo](lexicos.html#anexo) em um card

**Título:** Adicionar [Anexo](lexicos.html#anexo) em um [Card](lexicos.html#card) 

**Objetivo:** Adicionar um [anexo](lexicos.html#anexo) em um [Card](lexicos.html#card)  do Trello.

**Contexto:**
- **Pré-condição:**  O [Usuário](lexicos.html#usuário) precisará possuir um dispositivo com acesso a internet, estar logado em sua conta Trello e possuir um [Card](lexicos.html#card)  em uma [Lista](lexicos.html#lista).
- **Pós-condição:** : O [Usuário](lexicos.html#usuário) terá adicionado um [anexo](lexicos.html#anexo) a um [Card](lexicos.html#card) .

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#usuário) entra na tela onde tem o [Card](lexicos.html#card)  desejado.
- [Usuário](lexicos.html#usuário) clica no [Card](lexicos.html#card) . 
- No campo ‘Adicionar ao cartão’, o [Usuário](lexicos.html#usuário) clica na opção ‘anexo’. 
- [Usuário](lexicos.html#usuário) seleciona o local onde o [anexo](lexicos.html#anexo) está. 
- [Usuário](lexicos.html#usuário) seleciona o [anexo](lexicos.html#anexo). 
- [Usuário](lexicos.html#usuário) clica no botão ‘anexar’. 
- [Usuário](lexicos.html#usuário) terá anexado algo ao [Card](lexicos.html#card)  selecionado. 

------------
## CN32 Cenário de Mover um [Card](lexicos.html#card) para outra list 

**Título:** Mover um [Card](lexicos.html#card)  para outra [Lista](lexicos.html#lista)

**Objetivo:** Mover um [Card](lexicos.html#card)  de uma [Lista](lexicos.html#lista) para outra no Trello. 

**Contexto:**
- **Pré-condição:**  O [usuário](lexicos.html#usuário) precisará possuir um dispositivo com acesso a internet, estar logado em sua conta Trello, possuir um [Card](lexicos.html#card)  em uma [Lista](lexicos.html#lista) e uma outra [Lista](lexicos.html#lista) que será o destino do [Card](lexicos.html#card) . 
- **Pós-condição:** : O [Usuário](lexicos.html#usuário) terá movido um [Card](lexicos.html#card)  de uma [Lista](lexicos.html#lista) para outra.

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#usuário) entra na tela onde tem o [Card](lexicos.html#card)  desejado.
- [Usuário](lexicos.html#usuário) clica no [Card](lexicos.html#card) . 
- No campo ‘Adicionar ao cartão’, o [Usuário](lexicos.html#usuário) clica na opção ‘anexo’. 
- [Usuário](lexicos.html#usuário) seleciona o local onde o [anexo](lexicos.html#anexo) está. 
- [Usuário](lexicos.html#usuário) seleciona o [anexo](lexicos.html#anexo). 
- [Usuário](lexicos.html#usuário) clica no botão ‘anexar’. 
- [Usuário](lexicos.html#usuário) terá anexado algo ao [Card](lexicos.html#card)  selecionado. 
- [Usuário](lexicos.html#usuário) entra na tela onde tem o [Card](lexicos.html#card)  desejado.
- [Usuário](lexicos.html#usuário) clica no [Card](lexicos.html#card)  e segura o botão do mouse. 
- [Usuário](lexicos.html#usuário) arrasta o [Card](lexicos.html#card)  para a [Lista](lexicos.html#lista) desejada. 
- [Usuário](lexicos.html#usuário) terá movido o [Card](lexicos.html#card)  de uma [Lista](lexicos.html#lista) para outra. 


------------
## CN33 Cenário de Responder um comentário no card

**Título:** Responder um comentário no [Card](lexicos.html#card) 

**Objetivo:** Responder um comentário em um [Card](lexicos.html#card)  do Trello. 

**Contexto:**
- **Pré-condição:**  O [Usuário](lexicos.html#usuário) precisará possuir um dispositivo com acesso a internet, estar logado em sua conta Trello e possuir um [Card](lexicos.html#card)  em uma [Lista](lexicos.html#lista).
- **Pós-condição:** : O [usuário](lexicos.html#usuário) terá respondido um comentário em um [Card](lexicos.html#card) . 

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#usuário) entra na tela onde tem o [Card](lexicos.html#card)  desejado.
- [Usuário](lexicos.html#usuário) clica no [Card](lexicos.html#card) . 
- [Usuário](lexicos.html#usuário) acha o comentário que deseja responder. 
- [Usuário](lexicos.html#usuário) clica no botão ‘responder’ abaixo do comentário. 
- [Usuário](lexicos.html#usuário) escreve a resposta que deseja.
- [Usuário](lexicos.html#usuário) clica no botão ‘salvar’.
- [Usuário](lexicos.html#usuário) terá respondido o comentário selecionado.

------------
## CN34 Cenário de Excluir comentário no [Card](lexicos.html#card)

**Título:** Excluir comentário no [Card](lexicos.html#card) 

**Objetivo:** Excluir um comentário em um [Card](lexicos.html#card) do Trello. 

**Contexto:**
- **Pré-condição:**  O [Usuário](lexicos.html#usuário) precisará possuir um dispositivo com acesso a internet, estar logado em sua conta Trello, possuir um [Card](lexicos.html#card)  em uma [Lista](lexicos.html#lista) e ter feito um comentário neste [Card](lexicos.html#card) . 
- **Pós-condição:** : O [Usuário](lexicos.html#usuário) terá excluído um comentário em um [Card](lexicos.html#card) . 

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#usuário) entra na tela onde tem o [Card](lexicos.html#card)  desejado.
- [Usuário](lexicos.html#usuário) clica no [Card](lexicos.html#card) . 
- [Usuário](lexicos.html#usuário) acha o seu comentário que deseja excluir. 
- [Usuário](lexicos.html#usuário) clica no botão ‘excluir’ logo abaixo do comentário. 
- [Usuário](lexicos.html#usuário) clica no botão ‘Excluir Comentário’. 
- [Usuário](lexicos.html#usuário) terá excluído o comentário desejado. 

------------
## CN35 Cenário de Usar Power-Up no quadro 

**Título:** Usar Power-Up no quadro

**Objetivo:** Usar um Power-up em um quadro no Trello.

**Contexto:**
- **Pré-condição:**  O [Usuário](lexicos.html#usuário) precisará possuir um dispositivo com acesso a internet, estar logado em sua conta Trello e possuir um quadro. 
- **Pós-condição:** : O [Usuário](lexicos.html#usuário) terá usado um Power-Up em um quadro. 

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#usuário) entra no quadro desejado. 
- [Usuário](lexicos.html#usuário) clica no botão ‘Mostrar Menu’. 
- [Usuário](lexicos.html#usuário) clica na opção ‘Power-Ups’. 
- [Usuário](lexicos.html#usuário) usa o campo de pesquisa, se necessário. 
- [Usuário](lexicos.html#usuário) clica no botão adicionar no Power-Up desejado. 
- [Usuário](lexicos.html#usuário) pode adicionar mais Power-Ups a um mesmo quadro se possuir conta diferente da ‘Grátis’. 
- [Usuário](lexicos.html#usuário) terá adicionado um Power-Up a um quadro.

------------
## CN36 Cenário de Compartilhar card

**Título:** Compartilhar [Card](lexicos.html#card) 

**Objetivo:** Compartilhar um [Card](lexicos.html#card)  do Trello. 

**Contexto:**
- **Pré-condição:**  O [Usuário](lexicos.html#usuário) precisará possuir um dispositivo com acesso a internet, estar logado em sua conta Trello e possuir um [Card](lexicos.html#card)  em uma [Lista](lexicos.html#lista). 
- **Pós-condição:** : O [Usuário](lexicos.html#usuário) terá compartilhado um [Card](lexicos.html#card) . 

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#usuário) entra na tela onde tem o [Card](lexicos.html#card)  desejado. 
- [Usuário](lexicos.html#usuário) clica no [Card](lexicos.html#card) . 
- [Usuário](lexicos.html#usuário) clica na opção ‘Compartilhar e mais...’. 
- [Usuário](lexicos.html#usuário) escolhe como deseja compartilhar o [Card](lexicos.html#card) . 
- Ao selecionar uma das opções, o [Usuário](lexicos.html#usuário) terá um referencial do [Card](lexicos.html#card) de acordo com a opção escolhida. 

------------
## CN37 Cenário de Exibir detalhes do card

**Título:** Exibir detalhes do [Card](lexicos.html#card) 

**Objetivo:** Exibir detalhes de um [Card](lexicos.html#card)  do Trello. 

**Contexto:**
- **Pré-condição:**  O [Usuário](lexicos.html#usuário) precisará possuir um dispositivo com acesso a internet, estar logado em sua conta Trello e possuir um [Card](lexicos.html#card)  em uma [Lista](lexicos.html#lista). 
- **Pós-condição:** : O [usuário](lexicos.html#usuário) terá visualizado detalhes do [Card](lexicos.html#card) . 

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Acesso à aplicação web por meio de browser compatível instalado em dispositivo desktop.

**Episódios:**
- [Usuário](lexicos.html#usuário) entra na tela onde tem o [Card](lexicos.html#card)  desejado. 
- [Usuário](lexicos.html#usuário) clica no [Card](lexicos.html#card) .
- [Usuário](lexicos.html#usuário) terá aberto os detalhes do [Card](lexicos.html#card) .

------------
## CN38 Cenário de [Vincular](lexicos.html#) ao [Quadro](lexicos.html#quadro)

**Título:** [Vincular](lexicos.html#) a um [Quadro](lexicos.html#quadro). 

**Objetivo:** [Vincular](lexicos.html#) uma pessoa a um [Quadro](lexicos.html#quadro) para visualizar toda a interface do projeto e suas respectivas [Tarefa](lexicos.html#tarefa).

**Contexto:**
- **Pré-condição:**O [Usuário](lexicos.html#usuário) precisa ter uma conta no Trello e estar [Logada](lexicos.html#login), utilizando um dispositivo com acesso a internet, estar [Vinculada](lexicos.html#vincular) à um [Quadro](lexicos.html#quadro). 
- **Pós-condição:** : O [Usuário](lexicos.html#usuário) estará ligado à um [Quadro](lexicos.html#quadro), conseguirá ver [Tarefas](lexicos.html#tarefa) as quais pode fazer/designar.

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Dispositivo compatível com a plataforma Trello, um navegador ou o aplicativo e possuir internet.

**Episódios:**
- [Usuário](lexicos.html#usuário) entra no [Quadro](lexicos.html#quadro). 
- [Usuário](lexicos.html#usuário) escolhe outro [Usuário](lexicos.html#usuário) que deseja [Vincular](lexicos.html#vincular).
- [Usuário](lexicos.html#usuário) adiciona e-mail.
- [Usuário](lexicos.html#usuário) aceita ser [Vinculado](lexicos.html#vincular) pelo e-mail.
- Caso o [Usuário](lexicos.html#usuário) não receba o e-mail, verificar caixa de spam.
-[Usuário](lexicos.html#usuário) copia link para [Vincular](lexicos.html#vincular).
-[Usuário](lexicos.html#usuário) clica no link para se [Vincular](lexicos.html#vincular).

------------
## CN39 Cenário de Alterar permissões de [membros](lexicos.html#membro) no [board](lexicos.html#board)

**Título:** Alterar permissão de um [Membro](lexico.html#tarefa) em um [Board](lexico.html#board).

**Objetivo:** Fazer com que determinado [Membro](lexico.html#tarefa) tenha mais ou menos poder em um determinado [Board](lexico.html#board). 

**Contexto:**
- **Pré-condição:**O [Usuário](lexicos.html#usuário) precisa ter uma conta no Trello e estar [Logada](lexicos.html#login), utilizando um dispositivo com acesso a internet, estar [Vinculada](lexicos.html#vincular) à um [Quadro](lexicos.html#quadro). 
- **Pós-condição:** : O [Usuário](lexicos.html#usuário) terá menos ou mais controle sobre um determinado [Board](lexico.html#board).


**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Dispositivo compatível com a plataforma Trello, um navegador ou o aplicativo e possuir internet.

**Episódios:**
- [Usuário](lexicos.html#usuário) entra no [Quadro](lexicos.html#quadro). 
- [Usuário](lexicos.html#usuário) escolhe outro [Usuário](lexicos.html#usuário) que deseja alterar a permissão.
- [Usuário](lexicos.html#usuário) altera permissão.
- Caso o [Usuário](lexicos.html#usuário) não tenha permissão, ele não conseguirá alterar outras.

------------
## CN40 Cenário de Criar [Lista](lexicos.html#lista)

**Título:** Criar uma [Lista](lexicos.html#lista).

**Objetivo:** Ter um espaço com um tema específico para colocar [Atividades](lexicos.html#atividade). 

**Contexto:**
- **Pré-condição:**O [Usuário](lexicos.html#usuário) precisa ter uma conta no Trello e estar [Logada](lexicos.html#login), utilizando um dispositivo com acesso a internet, estar [vinculada](lexicos.html#vincular) à um [Quadro](lexicos.html#quadro). 
- **Pós-condição:** : O [Usuário](lexicos.html#usuário) terá um espaço [Atribuir](lexicos.html#) [Tarefas](lexicos.html#) de determinado tema ou parte do [Board](lexicos.html#board).


**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Dispositivo compatível com a plataforma Trello, um navegador ou o aplicativo e possuir internet.

**Episódios:**
- [Usuário](lexicos.html#usuário) entra no [Quadro](lexicos.html#quadro). 
- [Usuário](lexicos.html#usuário) aperta em "Adicionar outra [Lista](lexicos.html#lista)".
- [Usuário](lexicos.html#usuário) coloca um nome na [Lista](lexicos.html#lista).

------------
## CN41 Cenário de Alterar nome da [Lista](lexicos.html#lista)

**Título:** alterar o nome de uma [Lista](lexicos.html#lista).

**Objetivo:** Mudar o nome de uma determinada [Lista](lexicos.html#lista) com o objetivo dela. 

**Contexto:**
- **Pré-condição:**O [Usuário](lexicos.html#usuário) precisa ter uma conta no Trello e estar [Logada](lexicos.html#login), utilizando um dispositivo com acesso a internet, estar [vinculada](lexicos.html#vincular) à um [Quadro](lexicos.html#quadro). 
- **Pós-condição:** : O [Usuário](lexicos.html#usuário) saberá onde criar determinado [Card](lexicos;html#usuário), dependendo do seu objetivo.


**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Dispositivo compatível com a plataforma Trello, um navegador ou o aplicativo e possuir internet.

**Episódios:**
- [Usuário](lexicos.html#usuário) entra no [Quadro](lexicos.html#quadro). 
- [Usuário](lexicos.html#usuário) clica no nome da [Lista](lexicos.html#lista).
- [Usuário](lexicos.html#usuário) altera o nome da [Lista](lexicos.html#lista).

------------
## CN42 Cenário de Arquivar [Lista](lexicos.html#lista)

**Título:** [Arquivar](lexicos.html#arquivar) uma [Lista](lexicos.html#lista).

**Objetivo:** [Arquivar](lexicos.html#arquivar) uma determinada [Lista](lexicos.html#lista) que não é necessário.

**Contexto:**
- **Pré-condição:**O [Usuário](lexicos.html#usuário) precisa ter uma conta no Trello e estar [Logada](lexicos.html#login), utilizando um dispositivo com acesso a internet, estar [vinculada](lexicos.html#vincular) à um [Quadro](lexicos.html#quadro). 
- **Pós-condição:** : O [Usuário](lexicos.html#usuário) não terá a [Lista](lexicos.html#lista) visível até que queira.


**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Dispositivo compatível com a plataforma Trello, um navegador ou o aplicativo e possuir internet.

**Episódios:**
- [Usuário](lexicos.html#usuário) entra no [Quadro](lexicos.html#quadro). 
- [Usuário](lexicos.html#usuário) clica nas opções da [Lista](lexicos.html#lista).
- [Usuário](lexicos.html#usuário) clica na opção"Arquivar esta [Lista](lexicos.html#lista)".

------------
## CN43 Cenário de Organizar o quadro em coleções

**Título:** Organizar o [Quadro](lexicos.html#quadro) em [Coleções](lexicos.html#colecao)).

**Objetivo:** Agrupar um conjunto de [Quadro](lexicos.html#quadro).

**Contexto:**
- **Pré-condição:**O [Usuário](lexicos.html#usuário) precisa ter uma conta no Trello e estar [Logada](lexicos.html#login), utilizando um dispositivo com acesso a internet, estar [vinculada](lexicos.html#vincular) à um [Quadro](lexicos.html#quadro). 
- **Pós-condição:** : O [Usuário](lexicos.html#usuário) poderá ter um conjunto de [Quadro](lexicos.html#quadro) com determinado tema.


**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Dispositivo compatível com a plataforma Trello, um navegador ou o aplicativo e possuir internet.

**Episódios:**
- [Usuário](lexicos.html#usuário) entra no menu do Trello. 
- [Usuário](lexicos.html#usuário) clica nas opções de criar [Coleção](lexicos.html#colecao).
- [Usuário](lexicos.html#usuário) adiciona os [Quadros](lexicos.html#lista) desejados.
-Caso não tenha [Quadros](lexicos.html#quadros) o [Usuário](lexicos.html#usuário) terá que criar mais.

----------------
## CN44 Criar Board

**Título:** Criar um [Board](lexicos.html#board).

**Objetivo:** Criar um [Board](lexicos.html#board).

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#usuário) precisa ter uma conta no Trello e estar logado na mesma, utilizando um dispositivo com acesso a internet.
- **Pós-condição:** O [Usuário](lexicos.html#usuário) terá um [Board](lexicos.html#board) para designar, planejar e executar tarefas para seu respectivo time.

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Conta Trello, internet.

**Restrições** O [Usuário](lexicos.html#usuário) precisa ter uma conta Trello com acesso a internet.

**Excessões** Não ter internet na criação do [Board](lexicos.html#board), não ter energia na criação do [Board](lexicos.html#board).

**Episódios:**
- [Usuário](lexicos.html#usuário) entra no Trello;
- [Usuário](lexicos.html#usuário) realiza [Login](lexicos.html#login);
- [Usuário](lexicos.html#usuário) clica no criar [Board](lexicos.html#board);
---------------------------
## CN45 Criar Board do Time

**Título:** Criar um [Board](lexicos.html#board) e alocar time.

**Objetivo:** Criar um [Board](lexicos.html#board) para o time se organizar.

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#usuário) precisa ter uma conta no Trello e estar logado na mesma, utilizando um dispositivo com acesso a internet e ter possíveis membros para adicionar ao time.
- **Pós-condição:** O [Usuário](lexicos.html#usuário) terá um [Board](lexicos.html#board) para designar, planejar e executar tarefas para seu respectivo time.

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Conta Trello, internet, time.

**Restrições** O [Usuário](lexicos.html#usuário) precisa ter uma conta Trello com acesso a internet.

**Excessões** Não ter internet na criação do [Board](lexicos.html#board), não ter energia na criação do [Board](lexicos.html#board), não ter um time para convidar ao [Board](lexicos.html#board).

**Episódios:**
- [Usuário](lexicos.html#usuário) entra no Trello;
- [Usuário](lexicos.html#usuário) realiza [Login](lexicos.html#login);
- [Usuário](lexicos.html#usuário) clica no criar [Board](lexicos.html#board);
- [Usuário](lexicos.html#usuário) adiciona participantes ao [Board](lexicos.html#board);
---------------------------
## CN46 Ver um Board

**Título:** Ver um [Board](lexicos.html#board).

**Objetivo:** Ver um [Board](lexicos.html#board) para acompanhar andamento.

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#usuário) precisa ter uma conta no Trello e estar logado na mesma, utilizando um dispositivo com acesso a internet. E possuir um [Board](lexicos.html#board) que possa ser visualizado.
- **Pós-condição:** O [Usuário](lexicos.html#usuário) poderá ver atividades e descrições a respeito daquele [Board](lexicos.html#board) nos [cards]() levantados.

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Conta Trello, internet, um [Board](lexicos.html#board) para participar.

**Restrições** O [Usuário](lexicos.html#usuário) precisa ter um [Board](lexicos.html#board).

**Excessões** Não ter um [Board](lexicos.html#board) para ser visualizado.

**Episódios:**
- [Usuário](lexicos.html#usuário) entra no Trello;
- [Usuário](lexicos.html#usuário) realiza [Login](lexicos.html#login);
- [Usuário](lexicos.html#usuário) clica no [Board](lexicos.html#board) para visualizar;
- [Usuário](lexicos.html#usuário) visualiza o [Board](lexicos.html#board).
---------------------------
## CN47 Administrar Power-ups

**Título:** Administrar [power-ups](lexicos.html#power-up) em um projeto..

**Objetivo:** Ter uma noção de qual ferramenta caberia para alocação como [power-ups](lexicos.html#power-up).

**Contexto:**
- **Pré-condição:** O [Usuário](lexicos.html#usuário) precisa ter uma conta no Trello e estar logado na mesma, utilizando um dispositivo com acesso a internet. E possuir um [Board](lexicos.html#board) no qual possa ter permissões para tomar decisões de gerente.
- **Pós-condição:** O [Usuário](lexicos.html#usuário) terá um projeto podendo adicionar [power-ups](lexicos.html#power-up) no seu contexto..

**Atores:** [Usuário](lexicos.html#usuário)

**Recursos:** Dispositivo compatível com a plataforma Trello, um navegador ou o aplicativo e possuir internet. Um [Board](lexicos.html#board) no qual possa adicionar [power-ups](lexicos.html#power-up).

**Restrições** O [Usuário](lexicos.html#usuário) precisa ter um [Board](lexicos.html#board) no qual ele possua a posição de administrador, e conta [gold]() no Trello.

**Excessões** Não ter a posição de administrador em um [Board](lexicos.html#board).

**Episódios:**
- [Usuário](lexicos.html#usuário) entra no Trello;
- [Usuário](lexicos.html#usuário) realiza [Login](lexicos.html#login);
- [Usuário](lexicos.html#usuário) clica no [Board](lexicos.html#board) para acessar;
- [Usuário](lexicos.html#usuário) clica no [card](lexicos.html#card) visualizar;
- [Usuário](lexicos.html#usuário) adiciona [power-ups](lexicos.html#power-up) no [card](lexicos.html#card) utilizar;

--------------------
## CN48 Cenário de Adicionar Membros ao Card

**Título:** Adicionar [membros](lexicos.html#membro) em um [card](lexicos.html#card). 

**Objetivo:** Adicionar [membros](lexicos.html#membro) em um [card](lexicos.html#card).

**Contexto:**

- **Pré-condição:** O [Usuário](lexicos.html#usuario) precisará possuir um [card](lexicos.html#card) a ser realizado e [membros](lexicos.html#membro) para serem adicionados.
- **Pós-condição:** O [Usuário](lexicos.html#usuario) terá delegado o [card](lexicos.html#card) para determinado[membro](lexicos.html#membro). 

**Atores:** [Usuário](lexicos.html#usuario) de [Board](lexicos.html#board).

**Recursos:** Conta, [Board](lexicos.html#board), [card](lexicos.html#card), computador, internet.

**Restrição:** Card deve ter sido selecionado pelo [Usuário](lexicos.html#usuario) da [Board](lexicos.html#board).

**Exceção:** Não há [card](lexicos.html#card) para adicionar [membros](lexicos.html#membro). 

**Episódios:**
- [Usuário](lexicos.html#usuario) entra no trello. 
- [Usuário](lexicos.html#usuario) realiza [Login](lexicos.html#login).
- [Usuário](lexicos.html#usuario) visualiza [Board](lexicos.html#board). 
- Se não há board, [Usuário](lexicos.html#usuario) cria [Board](lexicos.html#board). 
- [Usuário](lexicos.html#usuario) visualiza [Lista](lexicos.html#lista). 
- Se não há lista, [Usuário](lexicos.html#usuario) cria [Lista](lexicos.html#lista).
- [Usuário](lexicos.html#usuario) vizualiza card.
- Se não há [card](lexicos.html#card), [Usuário](lexicos.html#usuario) cria [card](lexicos.html#card).
- [Usuário](lexicos.html#usuario) seleciona [card](lexicos.html#card).
- [Usuário](lexicos.html#usuario) clica no botão “Adicionar membros”.
- [Usuário](lexicos.html#usuario) insere nome do [membro](lexicos.html#membro) a ser adicionado.
- [Usuário](lexicos.html#usuario) seleciona [membro](lexicos.html#membro) a ser adicionado.

------------------------

## CN49 Adicionar Descrição ao Card

**Título:** Adicionar descrição ao [card](lexicos.html#card).

**Objetivo:** Adicionar uma descrição ao [card](lexicos.html#card) selecionado.

**Contexto:**

- **Pré-condição:** O [Usuário](lexicos.html#usuario) precisará possuir um [card](lexicos.html#card) sem descrição em uma lista qualquer em sua [Board](lexicos.html#board).
- **Pós-condição:** O [Usuário](lexicos.html#usuario) terá adicionado uma descrição ao card selecionado. 

**Atores:** [Usuário](lexicos.html#usuario) de [Board](lexicos.html#board) 

**Recursos:** Conta, [Board](lexicos.html#board), [card](lexicos.html#card), computador, internet.

**Restrição:** [Card](lexicos.html#card) deve ter sido selecionado pelo usuário da [Board](lexicos.html#board).

**Exceção:** Não há [card](lexicos.html#card) para adicionar descrição.

**Episódios:**

- [Usuário](lexicos.html#usuario) entra no trello. 
- [Usuário](lexicos.html#usuario) realiza [Login](lexicos.html#login).
- [Usuário](lexicos.html#usuario) visualiza [Board](lexicos.html#board). 
- Se não há board, usuário cria [Board](lexicos.html#board). 
- [Usuário](lexicos.html#usuario) visualiza [Lista](lexicos.html#lista). 
- Se não há lista, usuário cria [Lista](lexicos.html#lista).
- [Usuário](lexicos.html#usuario) vizualiza [card](lexicos.html#card).
- Se não há card, usuário cria [card](lexicos.html#card).
- [Usuário](lexicos.html#usuario) seleciona [card](lexicos.html#card).
- Se não há descrição, usuário insere uma descrição.
- [Usuário](lexicos.html#usuario) clica no botão “salvar”.

-------------------------------------

## CN50 Adicionar Checklist

**Título:** Adicionar checklist ao [card](lexicos.html#card). 

**Objetivo:** Adicionar uma checklist a um [card](lexicos.html#card).

**Contexto:** 

- **Pré-condição:** O [Usuário](lexicos.html#usuario) precisará possuir um [card](lexicos.html#card) com subtarefas a serem realizadas.
- **Pós-condição:** O [Usuário](lexicos.html#usuario) terá criado uma checklist com todas as subtarefas a serem realizadas.

**Atores:** [Usuário](lexicos.html#usuario) de [Board](lexicos.html#board).

**Recursos:** Conta, [Board](lexicos.html#board), [card](lexicos.html#card), computador, internet.

**Restrição:** [Card](lexicos.html#card) deve ter sido selecionado pelo usuário da [Board](lexicos.html#board).

**Exceção:**

- Não há [card](lexicos.html#card) para adicionar checklist. 
- [Card](lexicos.html#card) selecionado não dá para ser dividido em subtarefas.

**Episódios:**

- [Usuário](lexicos.html#usuario) entra no trello. 
- [Usuário](lexicos.html#usuario) realiza [Login](lexicos.html#login).
- [Usuário](lexicos.html#usuario) visualiza[Board](lexicos.html#board). 
- Se não há [Board](lexicos.html#board), [Usuário](lexicos.html#usuario) cria [Board](lexicos.html#board). 
- Usuário visualiza [Lista](lexicos.html#lista). 
- Se não há [Lista](lexicos.html#lista), [Usuário](lexicos.html#usuario) cria [Lista](lexicos.html#lista).
- [Usuário](lexicos.html#usuario) vizualiza [card](lexicos.html#card).
- Se não há [card](lexicos.html#card), usuário cria [card](lexicos.html#card).
- [Usuário](lexicos.html#usuario) seleciona [card](lexicos.html#card).
- Se não há checklist, [Usuário](lexicos.html#usuario) clica no botão “Adicionar checklist”.
- [Usuário](lexicos.html#usuario) insere nome das subtarefas a serem realizadas.
- [Usuário](lexicos.html#usuario) para de adicionar subtarefas quando desejar.

--------------------------
## CN51 Adicionar Etiqueta ao Card 
**Título:** Adicionar etiqueta em um [card](lexicos.html#card).

**Objetivo:** Adicionar uma etiqueta ao [card](lexicos.html#card) selecionado.

**Contexto:** 

- **Pré-condição:** O [Usuário](lexicos.html#usuario) precisará possuir um card em uma [Lista](lexicos.html#lista) qualquer em sua board.
- **Pós-condição:** O [Usuário](lexicos.html#usuario) terá adicionado uma ou mais etiquetas ao [card](lexicos.html#card) selecionado.

**Atores:**[Usuário](lexicos.html#usuario) de board 

**Recursos:** Conta,[Board](lexicos.html#board), [card](lexicos.html#card), computador, internet.

**Restrição:** [Card](lexicos.html#card) deve ter sido selecionado pelo usuário da [Board](lexicos.html#board).

**Exceção:**

- Não há [card](lexicos.html#card) para adicionar etiqueta. 
- Não é necessário etiquetar o [card](lexicos.html#card).

**Episódios:**

- [Usuário](lexicos.html#usuario) entra no trello. 
- [Usuário](lexicos.html#usuario) realiza [Login](lexicos.html#login).
- [Usuário](lexicos.html#usuario) visualiza [Board](lexicos.html#board). 
- Se não há [Board](lexicos.html#board), usuário cria [Board](lexicos.html#board). 
- [Usuário](lexicos.html#usuario) visualiza [Lista](lexicos.html#lista). 
- Se não há [Lista](lexicos.html#lista), usuário cria [Lista](lexicos.html#lista).
- [Usuário](lexicos.html#usuario) vizualiza [card](lexicos.html#card).
- Se não há [card](lexicos.html#card), usuário cria [card](lexicos.html#card).
- [Usuário](lexicos.html#usuario) seleciona [card](lexicos.html#card).
- [Usuário](lexicos.html#usuario) clica no botão “adicionar etiquetas”.
- [Usuário](lexicos.html#usuario) para de adicionar etiquetas quando desejar.

-----------------------------

## CN52 Adicionar [Deadline](lexico.html#duedate) 

**Título:** Adicionar [deadline](lexico.html#duedate)  em um [card](lexicos.html#card). 

**Objetivo:** Adicionar [deadline](lexico.html#duedate)  a um [card](lexicos.html#card). 

**Contexto:**

- **Pré-condição:** O [usuário](lexicos.html#usuario) precisará possuir um [card](lexicos.html#card) que deve ser realizado até uma data limite.
- **Pós-condição:** O [usuário](lexicos.html#usuario) terá criado uma [data de entrega](lexico.html#duedate)  para o [card](lexicos.html#card). 

**Atores:** [Usuário](lexicos.html#usuario) de [board](lexicos.html#board).

**Recursos:** Conta, [board](lexicos.html#board), [card](lexicos.html#card), computador, internet.

**Restrição:** [Card](lexicos.html#card) deve ter sido selecionado pelo [usuário](lexicos.html#usuario) da [board](lexicos.html#board).

**Exceção:**

- Não há [card](lexicos.html#card) para adicionar [data de entrega](lexico.html#duedate) . 
- Não há tempo limite para se realizar a tarefa do [card](lexicos.html#card).

**Episódios:**

- [Usuário](lexicos.html#usuario) entra no trello. 
- [Usuário](lexicos.html#usuario) realiza [Login](lexicos.html#login).
- [Usuário](lexicos.html#usuario) visualiza [Board](lexicos.html#board). 
- Se não há [Board](lexicos.html#board), [usuário](lexicos.html#usuario) cria [Board](lexicos.html#board). 
- [Usuário](lexicos.html#usuario) visualiza [Lista](lexicos.html#lista). 
- Se não há [Lista](lexicos.html#lista), [usuário](lexicos.html#usuario) cria [Lista](lexicos.html#lista).
- [Usuário](lexicos.html#usuario) vizualiza [card](lexicos.html#card).
- Se não há card,[usuário](lexicos.html#usuario) cria [card](lexicos.html#card).
- [Usuário](lexicos.html#usuario) seleciona [card](lexicos.html#card).
- [Usuário](lexicos.html#usuario) clica no botão “Adicionar [deadline](lexico.html#duedate) ”.
- [Usuário](lexicos.html#usuario) escolhe a data limite da entrega.
- [Usuário](lexicos.html#usuario) clica em “salvar” para manter a [data de entrega](lexico.html#duedate)  escolhida.

---------------------------

## CN53 Adicionar Comentários ao Card

**Título:** Adicionar comentário em um [card](lexicos.html#card). 

**Objetivo:**  Adicionar um comentário em um [card](lexicos.html#card). 

**Contexto:** 

- **Pré-condição:** O [usuário](lexicos.html#usuario) precisará possuir um  [card](lexicos.html#card) em uma [lista](lexicos.html#lista) no trello.
- **Pós-condição:** O[usuário](lexicos.html#usuario) terá postado um comentário em um  [card](lexicos.html#card) específico.

**Atores:** [Usuário](lexicos.html#usuario) de[board](lexicos.html#board).

**Recursos:** Conta, [board](lexicos.html#board),  [card](lexicos.html#card), computador, internet.

**Restrição:** Card deve ter sido selecionado pelo [usuário](lexicos.html#usuario) da [board](lexicos.html#board).

**Exceção:** Não há [card](lexicos.html#card) para adicionar comentários.

**Episódios:**

- [Usuário](lexicos.html#usuario) entra no trello. 
- [Usuário](lexicos.html#usuario) realiza [Login](lexicos.html#login).
- [Usuário](lexicos.html#usuario) visualiza [Board](lexicos.html#board). 
- Se não há [Board](lexicos.html#board), [usuário](lexicos.html#usuario) cria [Board](lexicos.html#board). 
- [Usuário](lexicos.html#usuario) visualiza [lista](lexicos.html#lista). 
- Se não há [lista](lexicos.html#lista), usuário cria [lista](lexicos.html#lista).
- [Usuário](lexicos.html#usuario) vizualiza  [card](lexicos.html#card).
- Se não há  [card](lexicos.html#card), [usuário](lexicos.html#usuario) cria  [card](lexicos.html#card).
- [Usuário](lexicos.html#usuario) seleciona  [card](lexicos.html#card).
- [Usuário](lexicos.html#usuario) visualiza a área “Adicionar comentários”.
- [Usuário](lexicos.html#usuario) escreve um comentário.
- [Usuário](lexicos.html#usuario) clica em “salvar” para manter o comentário feito.

--------------------------

## CN54 Alterar Permissão de Comentário

**Título:** Alterar permissão de comentário. 

**Objetivo:** Alterar quem é permitido comentar em [cards](). 

**Contexto:**

- **Pré-condição:** O [usuário](lexicos.html#usuario) possui um [board](lexicos.html#board) com permissões de comentário indesejadas.
- **Pós-condição:** O [usuário](lexicos.html#usuario) terá alterado as permissões de comentário do [board](lexicos.html#board). 

**Atores:** [Usuário](lexicos.html#usuario) de [board](lexicos.html#board).

**Recursos:** Conta, [board](lexicos.html#board), computador, internet.

**Restrição:** O [usuário](lexicos.html#usuario) deve ser dono do [board](lexicos.html#board) com as permissões de comentário indesejadas.

**Episódios:**

- [Usuário](lexicos.html#usuario) entra no trello. 
- [Usuário](lexicos.html#usuario) realiza [Login](lexicos.html#login).
- [Usuário](lexicos.html#usuario) visualiza [board](lexicos.html#board). 
- Se não há [board](lexicos.html#board), usuário cria [board](lexicos.html#board). 
- [Usuário](lexicos.html#usuario) clica no botão “Mostrar menu”.
- [Usuário](lexicos.html#usuario) clica no botão “Mais”.
- [Usuário](lexicos.html#usuario) clica no botão “Configurações”.
- [Usuário](lexicos.html#usuario) seleciona as “Permissões de comentário”.
- [Usuário](lexicos.html#usuario) escolhe as “Permissões de comentário” desejadas.


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
- [Usuário](lexicos.html#usuário) faz [Login](lexicos.html#login) ;
- Usuário

-------------------------------------------------------

**Cenário de Adicionar Membros ao Card**

**Título:** Adicionar membros em um [card](). 

**Objetivo:** Adicionar membros em um [card]().

**Contexto:**

- **Pré-condição:** O [Usuário](lexicos.html#usuario) precisará possuir um [card]() a ser realizado e membros para serem adicionados.
- **Pós-condição:** O [Usuário](lexicos.html#usuario) terá delegado o [card]() para determinado membro. 

**Atores:** [Usuário](lexicos.html#usuario) de [Board](lexicos.html#board).

**Recursos:** Conta, [Board](lexicos.html#board), [card](), computador, internet.

**Restrição:** Card deve ter sido selecionado pelo [Usuário](lexicos.html#usuario) da [Board](lexicos.html#board).

**Exceção:** Não há [card]() para adicionar membros. 

**Episódios:**
-[Usuário](lexicos.html#usuario) entra no trello. 
-[Usuário](lexicos.html#usuario) realiza [Login](lexicos.html#login).
-[Usuário](lexicos.html#usuario) visualiza [Board](lexicos.html#board). 
-Se não há board, [Usuário](lexicos.html#usuario) cria [Board](lexicos.html#board). 
-[Usuário](lexicos.html#usuario) visualiza [Lista](lexicos.html#lista). 
-Se não há lista, [Usuário](lexicos.html#usuario) cria [Lista](lexicos.html#lista).
-[Usuário](lexicos.html#usuario) vizualiza card.
-Se não há card, [Usuário](lexicos.html#usuario) cria [card]().
-[Usuário](lexicos.html#usuario) seleciona [card]().
-[Usuário](lexicos.html#usuario) clica no botão “Adicionar membros”.
-[Usuário](lexicos.html#usuario) insere nome do membro a ser adicionado.
-[Usuário](lexicos.html#usuario) seleciona membro a ser adicionado.

------------------ -->
