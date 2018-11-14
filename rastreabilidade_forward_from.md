# Foward From

Para garantir que os requisitos estão sendo cumpridos e que ainda fazem sentido durante a execução da aplicação, eles serão aqui relacionados com as tasks de implementação de cada requisito e com as funcionalidades operando no sistema.

## RQ 08 - Criação de cards em massa

 - [ ] - Criar opção de criação de vários cards quando inserido uma lista de temas na criação de cards
 - [ ] - Criar cards correspondentes aos temas inseridos

 ![Card em massa](imagens/foward/card-em-massa.gif)

## RQ 09 - Mencionar usuários em comentários

 - [ ] - Criar opção de mencionar membros na caixa de comentário
 - [ ] - Mostrar lista de membros do Board quando opção de mencionar for selecionada
 - [ ] - Gerar, na caixa de comentário, referencia à membro(s) selecionado(s)

![mencionar](imagens/foward/mencionar-comentario.gif)

## RQ 10 - Delegar cards a usuários

 - [ ] - Criar opção de 'membros' no menu lateral da página card
 - [ ] - Mostrar lista de membros do Board quando opção 'membros' for selecionada
 - [ ] - Associar membro à card
 - [ ] - Mostrar lista de membros aos quais o card foi delegado no topo da página do card

![delegar](imagens/foward/delegar-card.gif)

## RQ 11 - Notificar prazos de entrega próximos a usuários assinalados

 - [ ] - Criar notificação na aba de notificações da aplicação com informações do card que possui prazo de entrega próximo
 - [ ] - Enviar email com nome do card, link e data de entrega

![modo_daltonico](imagens/foward/entrega-notificacao.png)

## RQ 12 - Marcar data de entrega como concluída

 - [ ] - Criar checklist junto à indicação da data de entrega presente no card
 - [ ] - Mudar cor da área onde se encontra a data de entrega para indicar a mudança de status da mesma

![data entrega](imagens/foward/marcar-entregue.gif)

## RQ 13 - Compatibilidade com markdown nas descrições dos cards

[ ] - Adicionar compilador de markdown à caixa de texto de descrição dos cards

![descricao markdown](imagens/foward/descricao-markdown.gif)

## RQ 14 - Adição de etiquetas aos cards

[ ] - Criar opção 'etiquetas' no menu lateral da página card
[ ] - Mostrar lista de membros do Board quando opção 'etiquetas' for selecionada
[ ] - Associar etiqueta(s) à card
[ ] - Mostrar lista de etiquetas na página do card

![etiqueta](imagens/foward/etiqueta-card.gif)

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