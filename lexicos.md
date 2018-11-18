---
layout: default
title: Léxicos
category: Modelagem
---

# Léxicos

## LX01 Board

### Noção
- Representa um projeto ou um lugar para rastrear informações
- Contém todas as [Listas](lexicos.html#lista)

### Impacto
- [Usuários](lexicos.html#usuário) podem criar [Boards](lexicos.html#board) para organizar seu projeto
- [Usuários](lexicos.html#usuário) podem criar [Boards](lexicos.html#board) para organizar suas tarefas diárias
- [Usuários](lexicos.html#usuário) podem participar de um [Board](lexicos.html#board) de um projeto existente

### Sinonimo
- Quadro, tabela

--------------

## LX02 Lista

### Noção
- Representa uma coluna de uma tabela
- Onde são colocadas os [Cards](lexicos.html#card)
- Organiza todos os [Cards](lexicos.html#card) de um [Board](lexicos.html#board)

### Impacto
- [Usuários](lexicos.html#usuário) podem criar [Listas](lexicos.html#lista) para organizar seu projeto em colunas de tarefas
- Um [Card](lexicos.html#card) é criado na [Lista](lexicos.html#lista) To Do

### Sinonimo
- List, coluna

--------------

## LX03 Card

### Noção
- Unidade fundamental de um [Board](lexicos.html#board)
- Representa tarefas e/ou ideias
- Pode ser usado como lembretes

### Impacto
- O gerente do projeto cria [Cards](lexicos.html#card) e [delega](lexicos.html#atribuir--delegar-tarefa) ao seus funcionários
- Um [Card](lexicos.html#card) é criado na [Lista](lexicos.html#lista) To Do
- Um [Card](lexicos.html#card) foi [movido](lexicos.html#arrastar-card) a [Lista](lexicos.html#lista) de tarefas concluídas

### Sinonimo
- Tarefa

--------------

## LX04 Administrador

### Noção
- Um papel desempenhado por um usuário em um [Board](lexicos.html#board)
- Usuário que tem acesso às configurações de um [Board](lexicos.html#board)
- Usuário que cria a [Board](lexicos.html#board)
- Usuário dito como administrador por outro administrador

### Impacto
- Administrador pode alterar o [time](lexicos.html#time) que tem acesso àquela board
- Administrador pode ativar e desativar as [Imagens de Capa](lexicos.html#imagem-de-capa) dos [cards](lexicos.html#card)
- Administrador pode conceder e revogar permissões para comentar
- Administrador pode conceder e revogar permissão para [Convidar](lexicos.html#convidar) outros usuários para a Board.

--------------

## LX05 Business Class

### Noção
- Plano que ser comprado para um [time](lexicos.html#time)
- Conjunto de features adicionais que podem ser agregadas à [board](lexicos.html#board) de um [time](lexicos.html#time) específico.
- Aumento da robustez na segurança dos dados

### Impacto
- Quantidade ilimitada de [Power-Ups](lexicos.html#power-up) pode ser usada nas [boards](lexicos.html#board) quando um [time](lexicos.html#time) compra Business Class
- É possível criar [coleções de boards](lexicos.html#coleções)

--------------

## LX06 Atribuir / Delegar tarefa

### Noção
- Relacionar um [Card](lexicos.html#card) com um [membro](lexicos.html#membro) da [Board](lexicos.html#board)

### Impacto
- A foto de perfil do usuário aparece no card
- O usuário passa a [seguir](lexicos.html#seguir) o card
- O usuário é dito como um [membro](lexicos.html#membro) do card

--------------

## LX07 Imagem de Capa

### Noção
- Imagem [anexada](lexicos.html#anexo) ao [Card](lexicos.html#card) que aparece na visão geral da [Board](lexicos.html#board)
- Última imagem anexada a um card
- Imagem escolhida, na secção de Anexos do card, para aparecer como capa

### Impacto
- A visão do card não selecionado comporta a imagem escolhida como capa

--------------

## LX08 Coleções

### Noção
- Criado por usuário bussiness.
- É um conjunto de boards para facilitar organização.

### Impacto
- Coleções de um usuário com conta bussiness permite organizar melhor quadros de um time.
- Coleção de board facilita a visualização geral de um projeto.

### Sinonimo
- Grupos de boards, conjunto de boards

--------------

## LX09 Arquivar

### Noção
- Usuário arquiva card ou [Lista](lexicos.html#lista).
- Arquivar é o ato de retirar um card ou [Lista](lexicos.html#lista) de uma board, porém mantê-lo acessível em um local reservado.

### Impacto
- Usuário pode retirar cards de uma [Lista](lexicos.html#lista) sem excluí-lo.
- Usuário pode retirar [Listas](lexicos.html#lista) de uma board sem ter que excluí-las diretamente.

### Sinonimo
- reter, guardar

--------------

## LX10 Anexo

### Noção
- Arquivo que um usuário adiciona a um card.
- Arquivo encontra-se no card.

### Impacto
- Assim um usuário pode compartilhar dados com outros usuários e adicionar arquivos relevantes a uma atividade.

### Sinonimo
- Anexos

--------------
## LX11 Time

### Sinônimos
- Times, equipe

### Noção
- Conjunto de [Usuários](lexicos.html#usuário) que tem acesso simultâneo à uma [Board](lexicos.html#board) na qual são realizadas tarefas
- Grupo de colaboladores de uma [Board](#board)

### Impacto
- O time pode compor uma [Board](#board);
- O time pode ser atribuída uma [Tarefa](#card)


--------------

## LX12 Sticker

### Sinônimos
- Stickers, emote

### Noção
- Caractere especial utilizado para ilustrar uma mensagem com uma imagem.
- Enfeite usado em comentários.

### Impacto
- O [usuário](lexicos.html#usuário) postou um sticker no comentário.
- O [Card](lexicos.html#card) continha um sticker triste.


--------------

## LX13 Duedate

### Sinônimos
- Deadline, prazo de Entrega, prazo Limite

### Noção
- Termo que referencia o tempo máximo que uma tarefa deve ser cumprida.
- Característica de um [Card](lexicos.html#card).
- Define a posição de um [Card](lexicos.html#card) numa coluna.

### Impacto
- A tarefa foi arquivada pois o duedate expirou.
- A deadline desta tarefa é estipulada para daqui a um mês.


--------------

## LX14 Notificar

### Sinônimo
- Avisar
- Alertar

### Noção
- Ação que tem o objetivo de chamar a atenção de algum usuário sobre uma informação.
- Mostrar visualmente uma informação.

### Impacto
- Avisar o [Usuário](lexicos.html#usuario).
- O [Usuário](lexicos.html#usuario) recebe uma [Notificação](lexicos.html#notificar).


--------------

## LX15 Copiar

### Sinônimo
- clonar

### Noção
- Ação que tem o objetivo de criar um outro objeto a partir de um já existente.

### Impacto
- Copiar [Card](lexicos.html#card)
- Copiar [Lista](lexicos.html#lista)
- Copiar [Board](lexicos.html#board)
--------------
## LX16 Usuário

### Noção
- Pessoa que utiliza o sistema.
- Pessoa cadastrado no sistema.

### Impacto
- Ser usuário permite à pessoa acessa a maioria das ferramentas do sistema.
- Somente usuário pode criar quadros e listas.
- Somente usuário pode criar times

--------------

## LX17 Login

### Noção
- Realizado pelo usuário.
- Permite acesso ao sistema.

### Impacto
- O sistema identifica o usuário após o login.
- O usuário entra no sistema tendo acesso a todas suas informações.

### Sinonimo
- acessar conta
--------------

## LX18 Vincular

### Noção
- Associar pessoa a quadro.
- Ação realizada por usuário.

### Impacto
- Vincular pessoa ao quadro a torna integrante do mesmo.
- Pessoa vinculada tem acesso aos dados do board.

### Sinonimo
- linkar, associar

--------------

## LX19 Membro

### Noção
- Usuário pertencente a um time.

### Impacto
- Vincular pessoa ao quadro a torna integrante do mesmo.
- Pessoa vinculada tem acesso aos dados do board.

### Sinonimo
- integrante

--------------

## LX20 Arrastar Card

### Noção
- Ação que faz você mudar um determinado [Card](lexicos.html#card) de uma [Lista](lexicos.html#lista) para outra.
- Levar uma [Tarefa](lexicos.html#tarefa) de uma fase para outra do [Quadro](lexicos.html#quadros), seja anterior ou posterior.

### Impacto
- [Arrastar](lexicos.html#arrastar) [Card](lexicos.html#card).
- [Arrastar](lexicos.html#arrastar) [Tarefa](lexicos.html#tarefa).
- Quando terminar a [Tarefa](lexicos.html#tarefa) é só [Arrastar](lexicos.html#arrastar) o [Card](lexicos.html#card) para a última [Lista](lexicos.html#lista).

### Sinonimo
- Mover [Card](lexicos.html#card)
- Deslizar [Card](lexicos.html#card)

--------------

## LX21 Seguir

### Noção
- Ação que faz você ter notificações de determinada [Lista](lexicos.html#lista).
- Ação notificará o [Usuário](lexicos.html#usuario) se qualquer outro fizer uma alteração no [Quadro](lexicos.html#quadros).

### Impacto
- [Seguir](lexicos.html#seguir) [Card](lexicos.html#card).
- Para receber notificações basta [Seguir](lexicos.html#seguir) o [Card](lexicos.html#card).

--------------

## LX22 Atividade

###Sinônimo
- [Feed](lexicos.html#atividade)

### Noção
- [Atividade](lexicos.html#atividade) dentro de um [Card](lexicos.html#card) que fala o que determinada pessoa tem pra fazer.
- [Tarefa](lexicos.html#tarefa) para ser feita na [Lista](lexicos.html#lista).
-O que determinado [Usuário](lexicos.html#usuario) precisa fazer em certa [Lista](lexicos.html#lista).

###Impacto
- Preciso saber a [Atividade](lexicos.html#atividade) para concluir.
- Fazer uma [Atividade](lexicos.html#atividade) da [Lista](lexicos.html#lista).
- Fazer algo do [Feed](lexicos.ntml#atividades)
- Adicionar uma [Tarefa](lexicos.html#tarefa) no [Feed](lexicos.ntml#atividades).

--------------


## LX23 Check-list

### Sinônimos
- Lista de tarefas

### Noção
- Objeto que tem o objetivo de listar os requisitos para conclusão de atividade em um card.

### Impacto
- Criar check-list.
- marcar requisito que já foi atendido.

---------------

## LX25 Power-up

### Sinônimos
- Melhoria

### Noção
- Uma possibilidade adicional que pode promover ou não um auxilio na resolução ou desenvolvimento de um card.

### Impacto
- Adicionar power-up
- usar o power-up.

---------------

## LX26 Label

### Sinônimos
- Etiqueta
- Adesivo

### Noção
- Objeto que auxilia na descrição e rastreabilidade, tem como objetivo marcar um card da maneira mais adequada ao usuário.

### Impacto
- Criar etiqueta.
- personalizar etiqueta.
- adicionar etiqueta ao card.

---------------

## LX27 Tarefa

### Sinônimos
- Dever
- Afazer

### Noção
- Designação de um Objetivo para um [Usuário](lexicos.html#usuario).
- Descrição de um determinado objetivo.

### Impacto
- Fazer determinada [Tarefa](lexicos.html#tarefa).
- Cumprir uma [Tarefa](lexicos.html#tarefa).

--------------------------

## LX28 Fechar

### Sinônimos
- Sair

### Noção
- Ação de sair de um modo de visão de uma janela descartando qualquer mudança não salva.

### Impacto
- Fechar o [cartão](lexicos.html#card)
- Fechar o Trello.

--------------------

## LX29 Perfil

### Sinônimos
- Conta
- Perfis

### Noção
- Objeto que armazena as informações pessoais do [usuário](lexicos.html#usuario).
- Objeto que facilita a comunicação entre [usuários](lexicos.html#usuario).

### Impacto
- Criar o perfil
- Entrar no perfil
- Atualizar o perfil.

-----------------------

## LX30 Convidar

## Sinônimos
- Chamar

## Noção
- Ação de propor a um outro [usuário](lexicos.html#usuario) não [membro](lexicos.html#membro), a possibilidade de se tornar [membro](lexicos.html#membro) do [quadro](lexicos.html#quadros) em questão

## Impacto
- Convidar um [membro](lexicos.html#membro)
- Convidar com link.

-----------------

## LX31 Update

## Sinônimos
- Atualizar
- Melhorar

## Noção
- Atualizar projeto
- Melhorar projeto

## Impacto
- Usuários versionam o projeto
- Usuários acompanham o avanço

-----------------

## LX32 Gerente

## Sinônimos
- Líder
- Administrador

## Noção
- Membro com poderes sobre o time;
- Tem visão ampla de projeto;
- Age atribuindo tarefas;
- Age acompanhando tarefas;
- Age auxiliando da melhor forma o desenvolvimento.
## Impacto
- Usuários possuem um apoio no desenvolvimento;
- Usuários recebem tarefas;
- O projeto recebe alguém responsável pelas diretrizes.
