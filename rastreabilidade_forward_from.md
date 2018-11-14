# Foward From

Para garantir que os requisitos estão sendo cumpridos e que ainda fazem sentido durante a execução da aplicação, eles serão aqui relacionados com as tasks de implementação de cada requisito e com as funcionalidades operando no sistema.

## RQ 15 - Pesquisar cards

- [ ] Desenvolver barra de busca
- [ ] A busca deve mostrar todas os cards com o nome relacionado
- [ ] Deverá haver acesso ao card pela pesquisa

![pesquisar_cards](imagens/foward/Pesquisar&#32;Card.gif)

## RQ 16 - Anexar cards a outros cards

- [ ] Botão para anexar card, boards, links, arquivos e power-ups em um card
- [ ] Deve exibir uma barra de busca / um espaço para colar o link que deseja ser anexado
- [ ] Escrever o nome do card faz com que ele apareça, facilitando a questão de anexar
- [ ] Após o anexo deve ser exibido no card o que foi anexado (card), e quem anexou

![anexar_card](imagens/foward/Anexar&#32;card&#32;a&#32;outro&#32;card.gif)

## RQ 17 - Anexar boards a cards

- [ ] Botão para anexar card, boards, links, arquivos e power-ups em um card
- [ ] Deve exibir uma barra de busca / um espaço para colar o link que deseja ser anexado
- [ ] Escrever o nome do card faz com que ele apareça, facilitando a questão de anexar
- [ ] Após o anexo deve ser exibido no card o que foi anexado (board), e quem anexou

![anexar_board](imagens/foward/Anexar&#32;boards&#32;a&#32;cards.gif)

## RQ 18 - Seguir um Card

- [ ] Criar um botão dentro de card 
- [ ] Deve ser discreto 
- [ ] Deve fornecer feedback visual sobre estar seguindo
- [ ] Permite ao usuário receber notificações sobre o card que está sendo seguido

![seguir_card](imagens/foward/Seguir&#32;um&#32;card.gif)

## RQ 19 - Criar card através de e-mails

- [ ] Fornecer um link para o usuário
- [ ] Link viincula o quadro como um email para o board
- [ ] O card pode ser criado através desse link
- [ ] O link funciona como um email do quadro

![criar_card_email](imagens/foward/Criando&#32;quadro&#32;a&#32;partir&#32;do&#32;email.gif)

## RQ 20 - Login

- [ ] Mostrar na tela inicial o botão do login com email e senha
- [ ] Move o usuário para dentro da aplicação após a inserção do email e da senha

![login](imagens/foward/Login.gif)

## RQ 21 - Login com o Google

- [ ] Mostrar o botão com nome e logo do Google na tela inicial da aplicação
- [ ] Botão disponibiliza possíveis contas para login
- [ ] Ao clicar, e se usuário tiver conta, ele tem acesso a aplicação

![login_com_google](imagens/foward/Login&#32;com&#32;Google.gif)

## RQ 29 - Gestão de visibilidade do Board

- [ ] Criar opção onde o administrador de um board pode gerenciar quem pode ver determinado Board
- [ ] Criar lógica onde o sistema pode distinguir diferentes tipos de usuários dentro de um Board

![visibilidade_board](imagens/foward/RQ29.PNG)

## RQ 30 - Adição de times aos Boards

- [ ] Adicionar opção de "Alterar time" nas configurações de um Board
- [ ] Dar opções de times a adicionar, mostrando apenas os times em que o usuário está participando
- [ ] Adicionar todos os membros do time selecionado naquele Board

![time_board](imagens/foward/RQ30_1.PNG)

## RQ 31 - Adicionar membro a Board

- [ ] Adicionar ícone que demonstre a ação de adicionar um membro ao Board
- [ ] Mostrar um Input onde pode ser digitado o nome ou o email do usuário a ser adicionado
- [ ] Criar a opção da criação de um link onde usuários podem entrar no Board a partir dele
- [ ] Criar Input onde será a descrição do convite que o convidade receberá

![membro_board](imagens/foward/RQ31.PNG)

## RQ 32 - Alterar plano de fundo

- [ ] Criar opção de alterar tela de fundo no menu do Board
- [ ] Criar opção de cores para o plano de fundo
- [ ] Criar opção de fotos (planos de fundos padrões)
- [ ] Criar opção de planos de fundos personalizados para membros do Business Class

![wallpaper_board](imagens/foward/RQ32_1.PNG)
![wallpaper_board](imagens/foward/RQ32_2.PNG)

## RQ 33 - Oferecer biblioteca de imagens para plano de fundo

- [ ] Selecionar imagens para servirem como plano de fundo padrões dos Boards
- [ ] Adicionar as imagens dentro da opção de fotos de plano de fund

![fotos_board](imagens/foward/RQ33.PNG)

## RQ 34 - Interações com ferramentas externas

- [ ] Criar opções de Power-Ups no menu do Board
- [ ] Mostrar todos os Power-Ups disponíveis
- [ ] Criar um input para pesquisar dentro dos Power-Ups
- [ ] Criar categorias de Power-Ups

![powerups_board](imagens/foward/RQ34_1.PNG)
![powerups_board](imagens/foward/RQ34_2.PNG)

## RQ 35 - Copiar Board

- [ ] Criar opção de Copiar Board dentro do menu do Board
- [ ] Dar a opção de escolher um nome para o novo Board
- [ ] Dar a opção de escolher um time para ser adicionado esse novo Board
- [ ] Criar a opção de alterar a visibilidade do Board(privado, público, etc)
- [ ] Checklist de manter os cards do Board copiado

![copiar_board](imagens/foward/RQ35_1.PNG)
![copiar_board](imagens/foward/RQ35_2.PNG)
![copiar_board](imagens/foward/RQ35_3.PNG)

## RQ 44 - Descrição das Imagens no HTML

O Trello não contém imagens siginificativas. As imagens que podem ser 

## RQ 45 - Modo daltônico

- [ ] Criar opção de ativação/desativação do modo daltônico em Opções do Usuário
- [ ] Criação de padrões visuais através das quais seja possível identificar labels sem a necessidade de distinção de cor

![modo_daltonico](imagens/foward/modo_daltonismo.png)

## RQ 46 - Alto contraste entre texto e fundo

Validar todas as cores entre texto e fundo
- [ ] Todo texto em negrito ou de tamanho acima de 24 deve ter taxa de contraste entre o fundo de 4.5:1 ou maior
- [ ] Todos os demais textos devem ter contraste 7.0:1 ou maior

Algumas cores do site não cumprem o requisito, como a label amarela (imagem acima das labels) com texto branco.

## RQ 47 - Elaboração da Política de Privacidade

Explicar
- [ ] Quais informações são coletadas do usuário
- [ ] O acontece com as informações coletadas
- [ ] Quem tem acesso às informações coletadas
- [ ] Como são armazenadas as informações coletadas
- [ ] Como acessar e controlar as informações coletadas
- [ ] Como as informações coletadas são transferidas internacionalmente
- [ ] Outras informações importantes acerca de privacidade

![politica_de_privacidade](imagens/foward/privacidade.png)

O termo completo pode ser encontrado [aqui](https://trello.com/privacy)

## RQ 48 - Manter sessão

- [ ] Salvar a sessão localmente

![gif_manter_sessao](imagens/foward/manter_sessao.gif)

Como pode-se observar pela animação, sair da página não desloga o usuário. Esse foi um exemplo de curta duração, mas enquanto o navegador manter os dados do usuários.

## RQ 49 - Responsividade de acordo com tamanho de tela

- [ ] Utilização de features CSS para que os elementos possam flutuar na tela

![gif_responsividade](imagens/foward/responsividade.gif)

## RQ 50 - Detecção de Idioma

- [ ] Detectar idioma do sistema do usuário
- [ ] Definir idioma através da geolocalização por IP (entre os idiomas disponíveis)

Como a detecção de idioma depende do usuário do sistema, não foi possível capturar em imagem a troca do idioma acontecendo.

## RQ 51 - Botão Home

- [ ] Inserir botão no header que leve à página inicial
- [ ] O botão não deve ter cor, apenas clarear o fundo

![botao_home](imagens/foward/botao_home.gif)