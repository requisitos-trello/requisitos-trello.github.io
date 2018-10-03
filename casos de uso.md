---
layout: default
title: Casos de Uso
category: Modelagem
---

# Casos de uso
Diagramas de casos de uso, ou diagramas comportamentais na documentação UML, são responsáveis por descrever as principais funcionalidades do sistema e a interação dessas funcionalidades com os usuários do próprio sistema.
Para tal, o diagrama dispõe de atores que representam usuários ou sistemas que interagem com o sistema em questão, elipses que representam ações e relações entre as elipses, que podem ser do tipo include ou extend.

## Diagramas:

### Caso 5: Criar time

![Caso 5](imagens/casos de uso/caso5.png)

### UC01 - Criar time

|  |  |
|  ------: | :------ |
|  **Descrição** | Tem como objetivo a criação de um time para melhorar a organização de quadros e arquivos que devem pertencer a um grupo específico de usuários. |
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado  no sistema. |
| **Fluxo Principal** | **FP01 - Criar time**<br>1. Usuário acessa a opção de criar time.<br>2. Usuário digita o nome do time. [UC02][FA01][FA02]<br>3. Time criado com sucesso. Usuário é redirecionado para página do time. |
| **Fluxos Alternativos** | **FA01 - Adicionar descrição**<br>1. Usuário adiciona descrição do time [UC03].<br>**FA02 - Acessar informações de business class**<br>1. Usuário acessa informações do business class [UC04] |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Time é criado com informações dadas pelo usuário. |


### UC02 - Adicionar nome

|  |  |
|  ------: | :------ |
|  **Descrição** | Permite nomear times criados pelo usuário. |
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado  no sistema.<br> Formulário de criação de time deve estar selecionado.|
| **Fluxo Principal** | **FP01 - Adicionar nome**<br>1. Usuário digita o nome do time.<br>2. Usuário clica em no botão "criar".<br> 3. Time criado com sucesso. Usuário é redirecionado para página do time. |
| **Fluxos Alternativos** | Não se aplica. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Time é criado com informações dadas pelo usuário. |


### UC03 - Adicionar descrição

|  |  |
|  ------: | :------ |
|  **Descrição** | Permite adicionar descrição a times criados pelo usuário. |
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado  no sistema.<br> Formulário de criação de time deve estar selecionado.|
| **Fluxo Principal** | **FP01 - Adicionar descrição**<br>1. Usuário digita o nome do time.<br>2. Usuário digita descrição do time.<br>3. Usuário clica em no botão "criar".<br> 4. Time criado com sucesso. Usuário é redirecionado para página do time. |
| **Fluxos Alternativos** | Não se aplica. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Time é criado com informações dadas pelo usuário. |


### UC04 - Acessar informações de business class

|  |  |
|  ------: | :------ |
|  **Descrição** | Permite ter acesso a informações relevantes sobre as vantagens da assinatura do plano de business class. |
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado  no sistema.<br> Formulário de criação de time deve estar selecionado.|
| **Fluxo Principal** | **FP01 - Acessar informações de business class**<br>1. Usuário clica "saiba mais" no texto referente ao business class..<br>2. Nova guia do navegador é aberta contendo informações referentes ao business class.<br> |
| **Fluxos Alternativos** | Não se aplica. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Time é criado com informações dadas pelo usuário. |



### Caso 6: Adicionar/remover membros de time

![Caso 6](imagens/casos de uso/caso6.png)


### Caso 7: Alterar configurações de time

![Caso 7](imagens/casos de uso/caso7.png)


### Caso 8:  Alterar configurações de board

![Caso 8](imagens/casos de uso/caso8.png)


### Caso 10: Board

![Caso 10](imagens/casos de uso/Casos de Uso - Board.png)

### UC01 - Criar Board
### Descrição
- Criar um board para planejamento de projeto ou uso da maneira que melhor se enquadra ao contexto do usuário.

### Atores
- Usuário.

### Pré Condições
- O usuário deve estar logado na aplicação e possuir acesso a internet.

### Pós Condições
- O usuário terá um board para seu projeto, pessoal ou em grupo, para se organizar.
### Fluxo Principal
- O usuário loga na aplicação
- O usuário clical em criar Board

### Fluxos de Exceção
- O usuário ser convidado para um Board.
- O usuário criar um time.

### UC02 - Ver um Board
### Descrição
- Ter uma visão macro do board.

### Atores
- Usuário.

### Pré Condições
- O usuário deve estar logado na aplicação e possuir acesso a internet, possuir ou estar vinculado a um board para visualizá-lo.

### Pós Condições
- O usuário poderá ver o board de forma macro, como cards e colunas vinculadas.

### Fluxo Principal
- O usuário loga na aplicação
- O usuário clical em um board que deseja visualizar
- O usuário visualiza o board

### Fluxos de Exceção
- O usuário ter imprimido o board anteriormente, poderá visualizá-lo sem a necessidade de entrar na aplicação.

### UC03 - Seguir um Board
### Descrição
- Ter um vinculo a um board para poder acompanhar toda e qualquer alteração realizada no board.

### Atores
- Usuário

### Pré Condições
- O usuário deve estar logado na aplicação e possuir acesso a internet, possuir ou estar vinculado a um board.

### Pós Condições
- O usuário poderá receber notificações sempre que ocorrer alguma alteração no board que está seguindo.

### Fluxo Principal
- O usuário loga na aplicação
- O usuário clica em um board
- O usuário clica em “mais” no menu
- O usuário clica em seguir

### Fluxos de Exceção
- Falta de internet, fazendo com que apareça a mensagem de erro

### UC04 - Adicionar membros em um Board
### Descrição
- Vincular membros a que contribuam ou não para o contexto do board.

### Atores
- Usuário

### Pré Condições
- O usuário deve estar logado na aplicação e possuir acesso a internet, possuir ou estar vinculado a um board.

### Pós Condições
- O usuário terá outras pessoas que podem editar e realizar atividades no board e atreladas ao board.

### Fluxo Principal
- O usuário loga na aplicação
- O usuário clica em um board
- O usuário clica em adicionar membros

### Fluxos de Exceção
- Após logar na aplicação o usuário pode criar um time
- O usuário irá poder adicionar os membros e entrar no novo board criado
- Ao clicar em adicionar membros o usuário pode convidar pelo e-mail
- Ao clicar em adicionar membros o usuário pode convidar pela conta trello

### UC05 - Imprimir um Board
### Descrição
- Ter impresso a visão macro de um board.

### Atores
- Usuário

### Pré Condições
- O usuário deve estar logado na aplicação e possuir acesso a internet, ter acesso a uma impressora, possuir ou estar vinculado a um board.

### Pós Condições
- O usuário terá em suas mãos uma versão impressa da versão macro do board.

### Fluxo Principal
- O usuário loga na aplicação
- O usuário clica em um board
- O usuário clica em imprimir board

### Fluxos de Exceção
- Falta de internet, apresentando a mensagem de erro ao usuário
- Falha na conexão com a impresora que irá imprimir o board.

### UC06 - Ser convidado para um Board
### Descrição
- Ter recebido um convite para participação de um board.

### Atores
- Usuário

### Pré Condições
- O usuário deve possuir uma conta de e-mail.

### Pós Condições
- O usuário terá um convite que lhe dá acesso a um board.

### Fluxo Principal
- O usuário confirma o convite

### Fluxos de Exceção
- Falta de internet, apresentando a mensagem de erro ao usuário.
- O usuário não apresenta interesse.

### UC07 - Criar um time
### Descrição
- Ter um time para designar e coordenar tarefas, de acordo com o contexto do usuário.

### Atores
- Usuário

### Pré Condições
- O usuário deve estar logado na aplicação e possuir acesso a internet.

### Pós Condições
- O usuário terá um board com um time vinculado.

### Fluxo Principal
- O usuário loga na aplicação
- O usuário clica em criar um time

### Fluxos de Exceção
- O usuário loga na aplicação
- O usuário clica em um board
- O usuário clica em adicionar membros

### UC08 - Convidar por E-mail
### Descrição
- Ter a possibilidade de convidar mais participantes para contribuírem com o contexto do board.

### Atores
- Usuário

### Pré Condições
- O usuário deve estar logado na aplicação e possuir acesso a internet, possuir ou estar vinculado a um board.

### Pós Condições
- O usuário terá enviado um convite para uma ou mais pessoas de colaboração.

### Fluxo Principal
- O usuário loga na aplicação
- O usuário clica em um board
- O usuário clica em adicionar membros
- O usuário escreve o e-mail do membro que quer adicionar

### Fluxos de Exceção
- Falta de internet, apresentando a mensagem de erro ao usuário.

### UC09 - Convidar pela Conta
### Descrição
- Ter a possibilidade de convidar mais participantes para contribuírem com o contexto do board.

### Atores
- Usuário

### Pré Condições
- O usuário deve estar logado na aplicação e possuir acesso a internet, possuir ou estar vinculado a um board.

### Pós Condições
- O usuário terá enviado um convite para uma ou mais pessoas de colaboração.

### Fluxo Principal
- O usuário loga na aplicação
- O usuário clica em um board
- O usuário clica em adicionar membros
- O usuário escreve nome da conta do membro que quer adicionar

### Fluxos de Exceção
- Falta de internet, apresentando a mensagem de erro ao usuário.

### UC10 - Fechar Board
### Descrição
- Ter a possibilidade de fechar o board, para finalização do projeto que estava em andamento.

### Atores
- Usuário

### Pré Condições
- O usuário deve estar logado na aplicação e possuir acesso a internet, possuir ou estar vinculado a um board para que possa ser fechado.

### Pós Condições
- O usuário terá fechado o board da sua escolha.

### Fluxo Principal
- O usuário loga na aplicação
- O usuário clica em um board
- O usuário clica em fechar board

### Fluxos de Exceção
- Falta de internet, apresentando a mensagem de erro ao usuário.

### UC11 - Vincular Board
### Descrição
- Ter a possibilidade de vincular o board, para outro contexto.

### Atores
- Usuário

### Pré Condições
- O usuário deve estar logado na aplicação e possuir acesso a internet, possuir ou estar vinculado a um board.

### Pós Condições
- O usuário terá vinculado o seu board a um outro contexto, ligando ambos.

### Fluxo Principal
- O usuário loga na aplicação
- O usuário clica em um board
- O usuário gera o link para vincular o board

### Fluxos de Exceção
- Falta de internet, apresentando a mensagem de erro ao usuário.
