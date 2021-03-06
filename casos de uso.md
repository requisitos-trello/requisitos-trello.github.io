---
layout: default
title: Casos de Uso
category: Modelagem
---

[Lista de Autores do artefato](/artefatos.html)

# Casos de uso
Diagramas de casos de uso, ou diagramas comportamentais na documentação UML, são responsáveis por descrever as principais funcionalidades do sistema e a interação dessas funcionalidades com os usuários do próprio sistema.
Para tal, o diagrama dispõe de atores que representam usuários ou sistemas que interagem com o sistema em questão, elipses que representam ações e relações entre as elipses, que podem ser do tipo include ou extend.

## Diagramas:

### UC01 Fazer Login

![Caso 1](imagens/casos de uso/UC01.png)

#### UC01 - Fazer Login

|  |  |
|  ------: | :------ |
|  **Descrição** | Tem como objetivo Ter acesso a seus boards e times. |
| **Atores** | Usuário |
| **Pré Condições** | Usuário deve possuir cadastro no sistema. |
| **Fluxo Principal** | **FP01 - Fazer Login**<br>1. Abre a página inicial do trello.<br>2. Usuário clica no botão “Fazer Login”.<br>3. Usuário informa seu e-mail e senha.<br>4. Usuário clica no botão “Fazer Login”.<br>5. Caso de uso encerrado. |
| **Fluxos Alternativos** | **FA01 - Alterar senha [UC03]**<br>1. Abre a página de Login.<br>2. Usuário clica no link “Esqueceu sua senha?”.<br>3. Usuário digita seu “Email”.<br>4. Usuário clica no botão “Enviar”.<br>5. Usuário recebe um e-mail para redefinir sua senha. <br>6. Usuário abre o e-mail recebido.<br>7. Usuário clica no botão “Redefinir Senha”.<br>8. Usuário insere a nova senha.<br>9. Usuário insere a nova senha novamente.<br>10. Usuário clica no botão ‘Enviar’.<br>11. Usuário retorna para o primeiro passo do fluxo principal.<br>**FA02 - Fazer Login com o Google**<br>1. Abre a página inicial do trello.<br>2. Usuário clica no botão “Fazer Login”.<br>3. Usuário clica no botão “Fazer Login com o Google”.<br>4. Usuário insere o endereço de e-mail ou telefone.<br>5. Usuário clica no botão “Próxima”.<br>6. Usuário insere a senha.<br>7. Usuário clica no botão “Próxima”.<br>8. Usuário estará logado na aplicação.<br>9. Caso de uso encerrado. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Usuário estará logado no sistema. |


### UC02 Cadastro

![Caso 2](imagens/casos de uso/UC02.png)

#### UC02 - Cadastro

|  |  |
|  ------: | :------ |
|  **Descrição** | Tem como objetivo criar uma nova conta no sistema. |
| **Atores** | Usuário |
| **Pré Condições** | Usuário deve possuir email. |
| **Fluxo Principal** | **FP01 - Cadastro**<br>1. Abre a página inicial do trello.<br>2. Usuário clica no botão “Cadastre-se”.<br>3. Usuário informa seu nome, e-mail e senha.<br>4. Usuário clica no botão “Criar Nova Conta”.<br>5. Caso de uso encerrado. |
| **Fluxos Alternativos** | **FA01 - Fazer Cadastro com o Google**<br>1. Abre a página de Login.<br>2. Usuário clica no botão “Cadastre-se”.<br>3. Usuário clica no botão “Cadastre-se com o Google”.<br>4. Usuário insere o endereço de e-mail.<br>5. Usuário clica no botão “Próxima”. <br>6. Usuário insere a senha.<br>7. Usuário clica no botão “Próxima”.<br>8. Caso de uso encerrado. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Usuário terá criado uma nova conta no sistema. |


### UC03 Alterar Senha

![Caso 3](imagens/casos de uso/UC03.png)

#### UC03 - Alterar Senha

|  |  |
|  ------: | :------ |
|  **Descrição** | Tem como objetivo alterar senha de uma conta existente. |
| **Atores** | Usuário |
| **Pré Condições** | Usuário deve possuir uma conta. |
| **Fluxo Principal** | **FP01 - Alterar Senha**<br>1. Abre a página inicial do trello.<br>2. Usuário clica no seu avatar.<br>3. Usuário clica em “Configurações”.<br>4. Usuário clica em “Alterar Senha…”.<br>5. Usuário informa sua senha atual e sua nova senha.<br>6. Usuário clica no botão “Salvar”.<br>7. Caso de uso encerrado. |
| **Fluxos Alternativos** | **FA01 - Esqueci minha senha**<br>1. Abre a página de Login.<br>2. Usuário clica no link “Esqueceu sua senha?”.<br>3. Usuário digita seu “Email”.<br>4. Usuário clica no botão “Enviar”.<br>5. Usuário recebe um e-mail para redefinir sua senha. <br>6. Usuário abre o e-mail recebido.<br>7. Usuário clica no botão “Redefinir Senha”.<br>8. Usuário insere a nova senha.<br>9. Usuário insere a nova senha novamente.<br>10. Usuário clica no botão ‘Enviar’.<br>11. Caso de uso encerrado. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Usuário terá alterado a senha de sua conta no sistema. |


### UC04 Alterar Configurações

![Caso 4](imagens/casos de uso/UC04.png)

#### UC04 - Alterar Configurações

|  |  |
|  ------: | :------ |
|  **Descrição** | Tem como objetivo alterar configurações, tanto do trello quanto da conta. |
| **Atores** | Usuário |
| **Pré Condições** | Usuário deve possuir uma conta. |
| **Fluxo Principal** | **FP01 - Alterar Configurações**<br>1. Abre a página inicial do trello estando logado.<br>2. Usuário clica no seu avatar.<br>3. Usuário clica em “Configurações”.<br>4. Caso de uso encerrado. |
| **Fluxos Alternativos** | **FA01 - Alterar nome**<br>1. A partir do passo 3 do fluxo principal.<br>2. Usuário clica no link “Alterar Nome, Iniciais ou Biografia...”.<br>3. Usuário digita os dados a serem editados.<br>4. Usuário clica no botão “Salvar”.<br>5. Caso de uso encerrado.<br>**FA02 - Alterar Senha [UC04]**<br>1. A partir do passo 3 do fluxo principal.<br>2. Usuário clica no link “Alterar Senha...”.<br>3. Usuário digita os dados exigidos.<br>4. Usuário clica no botão “Salvar”.<br>5. Caso de uso encerrado.<br>**FA03 - Alterar avatar**<br>1. A partir do passo 3 do fluxo principal.<br>2. Usuário clica no link “Alterar Avatar...”.<br>3. Usuário escolhe a nova imagem.<br>4. Caso de uso encerrado.<br>**FA04 - Alterar email**<br>1. A partir do passo 3 do fluxo principal.<br>2. Usuário clica no link “Alterar Email...”<br>3. Usuário digita o novo email.<br>4. Usuário clica no botão “Alterar E-mail”.<br>5. Caso de uso encerrado.<br>**FA05 - Adicionar novo email**<br>1. A partir do passo 3 do fluxo principal.<br>2. Usuário clica no botão “Adicionar novo endereço de email”.<br>3. Usuário digita o novo email.<br>4. Usuário clica no botão “Enviar Email de Confirmação”.<br>5. Caso de uso encerrado.<br>**FA06 - Alterar frequência de email de notificação**<br>1. A partir do passo 3 do fluxo principal.<br>2. Usuário clica no botão “Alterar frequência de email de notificação”.<br>3. Usuário escolhe a opção desejada.<br>4. Caso de uso encerrado.<br>**FA07 - Permitir notificações da Área de Trabalho**<br>1. A partir do passo 3 do fluxo principal.<br>2. Usuário clica no botão “Permitir Notificações da Área de Trabalho”.<br>3. Caso de uso encerrado. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Usuário terá alterado as configurações de sua conta no sistema. |


### UC05: Criar time

![Caso 5](imagens/casos de uso/caso5.png)

#### UC05 - Criar time

|  |  |
|  ------: | :------ |
|  **Descrição** | Tem como objetivo a criação de um time para melhorar a organização de quadros e arquivos que devem pertencer a um grupo específico de usuários. |
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado no sistema. |
| **Fluxo Principal** | **FP01 - Criar time**<br>1. Usuário acessa a opção de criar time.<br>2. Usuário digita o nome do time.<br>3. Usuário clica em no botão "criar". [FA01][FA02]<br>4. Time criado com sucesso. Usuário é redirecionado para página do time. |
| **Fluxos Alternativos** | **FA01 - Adicionar descrição**<br>1. Usuário digita o nome do time.<br>2. Usuário digita descrição do time.<br>3. Usuário clica em no botão "criar".<br> 4. Retorna para UC01 - criar time, passo 3.<br>**FA02 - Acessar informações de business class**<br>1. Usuário clica "saiba mais" no texto referente ao business class.<br>2. Nova guia do navegador é aberta contendo informações referentes ao business class. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Time é criado com informações dadas pelo usuário. |




### UC06: Acessar lista de membros

![Caso 6](imagens/casos de uso/caso6.png)

#### UC06 - Acessar lista de membros

|  |  |
|  ------: | :------ |
|  **Descrição** | Permite ao usuário visualizar todos os membros de um time e suas permissões. |
| **Atores** | Administrador<br>Usuário |
| **Pré Condições** | O administrador do time deve estar logado no sistema.<br>|
| **Fluxo Principal** | **FP01 - Acessar lista de membros**<br>1. Usuário clica no time que deseja visualizar dentre os presentes no menu lateral.<br>2. O usuário clica em membros.<br>3. Sistema mostra lista de membros do time. [FE01][FA01][FA02] |
| **Fluxos Alternativos** | **FA01 - Remover membro**<br>1. O administrador do time clica em remover, logo a frente do nome do usuário e confirma. [FE01].<br>**FA02 - Convidar membro**<br>1. Sistema mostra lista de membros do time.[FE01] <br>2. O administrador do time clica em Convidar membros do time<br>3. Administrador do time digita nome de usuário ou email no formulário<br>4. Administrador clica em Adicionar ao time.[FA03][FA04]<br>4. Lista de membro é atualizada com o(s) novo(s) membro(s).<br>**FA03 - Enviar link de convite** <br>1. Administrador do time clica em criar link.<br>2. Administrador do time clica em copiar.<br>3. Administrador envia link para usuários de sua escolha.<br>**FA04 - Adicionar várias pessoas**<br>1. Administrador do time clica em Adicionar várias pessoas de uma vez.<br>2. Administrador do time insere todos os emails e nomes de usuário que deseja adicionar no time.<br>3. Administrador clica em Adicionar ao time. |
| **Fluxos de Exceção** | [FE01] Não há membros no time |
| **Pós Condições** | Lista de membros do time é acessada pelo usuário |

### UC07: Acessar configurações de time

![Caso 7](imagens/casos%20de%20uso/caso7%20(1).png)

#### UC07 - Acessar configurações de time

|  |  |
|  ------: | :------ |
|  **Descrição** | Tem como objetivo permitir o acesso às configurações de um time para alteração ou simples visualização. |
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado no sistema.<br>Usuário deve ser membro do time. |
| **Fluxo Principal** | **FP01 - Acessar configurações de time**<br>1. Usuário clica no time que deseja visualizar dentre os presentes no menu lateral.<br>2. O usuário clica em configurações.<br>3. Sistema mostra configurações do time. [FA01]<br>4. Usuário clica em alterar, que se encontra a frente da visibilidade do time.<br>5. O usuário seleciona a visibilidade que deseja para o time.<br>6. O usuário clica em salvar.<br>7. Usuário clica em add to Slack. [FA02]<br>8. O usuário informa o nome do workspace do slack.<br>9. Sistema retorna página de termos<br>10. Usuário autoriza vinculação. |
| **Fluxos Alternativos** | **FA01 - Editar perfil**<br>1. Usuário clica em editar perfil do time.<br>2. O usuário altera as informações de perfil.<br>3. O usuário clica em salvar.<br>**FA01 - Acessar informações de vinculação** <br>1. Usuário clica em saiba mais na sessão vinculação ao slack.<br>2. Sistema redireciona para página de informações de vinculação ao slack. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Configurações são acessadas pelo usuário. |


### UC08: Acessar board

![Caso 8](imagens/casos de uso/caso8.png)

#### UC08 - Acessar board

|  |  |
|  ------: | :------ |
|  **Descrição** | Tem como objetivo permitir o acesso boards dos quais participa. |
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado no sistema.<br> |
| **Fluxo Principal** | **FP01 - Acessar configurações de time**<br>1. Usuário clica em boards no menu lateral ou no header.<br>2. O sistema retorna lista de boards que o usuário participa.<br>3. Usuário seleciona board. [FE01]<br>4. sistema redireciona para página do board selecionado.<br>5. Usuário clica em mostrar menu caso menu não esteja aberto.<br>6. O sistema retorna relatório de atividades do boards. [FA01][FA02][FA03] |
| **Fluxos Alternativos** | **FA01 - Acessar mais opções do menu**<br>1. Usuário clica em mostrar menu caso menu não esteja aberto.<br>2. Usuário clica em mais.<br>3. O sistema retorna mais opções para o menu[FA04][FA05][FA06].<br>**FA02 - Alterar tela de fundo**<br>1. Usuário clica em mostrar menu caso menu não esteja aberto.<br>2. Usuário clica em Alterar tela de fundo.<br>3. O sistema retorna opções de tela de fundo.<br>4. Usuário seleciona entre as cores e fotos disponíveis..<br>**FA03 - Adicionar/remover power-up**<br>1. Usuário clica em mostrar menu caso menu não esteja aberto.<br>2. Usuário clica em Power-ups.<br>3. O sistema retorna opções de power-ups que podem ser adicionados ao board.<br>4. Usuário seleciona entre os power-ups disponíveis.<br>**FA04 - Editar permissão de adicionar/remover membros**<br>1. Usuário clica em Configurações.<br>2. Usuário clica em Adicionar/remover permissões.<br>3. Usuário seleciona nível de permissão.<br>**FA05 - Editar permissão de comentário**<br>1. Usuário clica em Configurações.<br>2. Usuário clica em permissões para comentários.<br>3. Usuário seleciona nível de permissão.<br>**FA06 - Editar permissão de ingresso de membro**<br>1. Usuário clica em Configurações.<br>2. Usuário altera permissão. |
| **Fluxos de Exceção** | Usuário não participa de nenhum board. |
| **Pós Condições** | Usuário tem acesso aos dados do board. |


### UC09: Criar Board

![Caso 9](imagens/casos de uso/caso9.png)

### UC09 - Criar Board

|  |  |
|  ------: | :------ |
| **Descrição** | Criar um board para planejamento de projeto ou uso da maneira que melhor se enquadra ao contexto do usuário.|
| **Atores** | Usuário.|
| **Pré Condições** | O usuário deve estar logado na aplicação e possuir acesso a internet.|
| **Pós Condições** | O usuário terá um board para seu projeto, pessoal ou em grupo, para se organizar.|
| **Fluxo Principal** |FP01 - Criar Board <br> 1. O usuário loga na aplicação <br> 2. O usuário clica em criar Board
| **Fluxos de Exceção** |1. O usuário ser convidado para um Board. <br> 2. O usuário criar um time.

### UC10 Ver um Board

![Caso 10](imagens/casos de uso/caso10.png)

### UC10 - Ver um Board

|  |  |
|  ------: | :------ |
| **Descrição** | Ter uma visão macro do board.|
| **Atores** | Usuário.|
| **Pré Condições** | O usuário deve estar logado na aplicação e possuir acesso a internet, possuir ou estar vinculado a um board para visualizá-lo.|
| **Pós Condições** | O usuário poderá ver o board de forma macro, como cards e colunas vinculadas.|
| **Fluxo Principal** |FP01 - Criar Board <br> 1. O usuário loga na aplicação <br> 2. O usuário clica em um board que deseja visualizar <br> 3. O usuário visualiza o board
| **Fluxos de Exceção** | O usuário ter imprimido o board anteriormente, poderá visualizá-lo sem a necessidade de entrar na aplicação.|

### UC11 Seguir um Board

![Caso 11](imagens/casos de uso/caso11.png)

### UC11 - Seguir um Board

|  |  |
|  ------: | :------ |
| **Descrição** | Ter um vinculo a um board para poder acompanhar toda e qualquer alteração realizada no board.|
| **Atores** | Usuário|
| **Pré Condições** | O usuário deve estar logado na aplicação e possuir acesso a internet, possuir ou estar vinculado a um board.|
| **Pós Condições** | O usuário poderá receber notificações sempre que ocorrer alguma alteração no board que está seguindo.|
| **Fluxo Principal** |FP01 - Criar Board <br>1. O usuário loga na aplicação <br> 2. O usuário clica em um board <br> 3. O usuário clica em “mais” no menu <br>4. O usuário clica em seguir
| **Fluxos de Exceção** | 1. Falta de internet, fazendo com que apareça a mensagem de erro|

### UC12 Adicionar membros em um Board

![Caso 12](imagens/casos de uso/caso12.png)

### UC12 - Adicionar membros em um Board

|  |  |
|  ------: | :------ |
| **Descrição** | Vincular membros a que contribuam ou não para o contexto do board.|
| **Atores** | Usuário|
| **Pré Condições** | O usuário deve estar logado na aplicação e possuir acesso a internet, possuir ou estar vinculado a um board.|
| **Pós Condições** | O usuário terá outras pessoas que podem editar e realizar atividades no board e atreladas ao board.|
| **Fluxo Principal** |FP01 - Criar Board <br> 1. O usuário loga na aplicação <br> 2. O usuário clica em um board <br> 3. O usuário clica em adicionar membros|
| **Fluxos de Exceção** |1. Após logar na aplicação o usuário pode criar um time <br> 2. O usuário irá poder adicionar os membros e entrar no novo board criado <br> 3. Ao clicar em adicionar membros o usuário pode convidar pelo e-mail <br> 4. Ao clicar em adicionar membros o usuário pode convidar pela conta trello|

### UC13 Imprimir um Board

![Caso 13](imagens/casos de uso/)

### UC13 - Imprimir um Board

|  |  |
|  ------: | :------ |
| **Descrição** | Ter impresso a visão macro de um board.|
| **Atores** | Usuário|
| **Pré Condições** | O usuário deve estar logado na aplicação e possuir acesso a internet, ter acesso a uma impressora, possuir ou estar vinculado a um board.|
| **Pós Condições** | O usuário terá em suas mãos uma versão impressa da versão macro do board.
| **Fluxo Principal** |FP01 - Criar Board <br> 1. O usuário loga na aplicação <br> 2. O usuário clica em um board <br> 3. O usuário clica em imprimir board.|
| **Fluxos de Exceção** |1. Falta de internet, apresentando a mensagem de erro ao usuário <br> 2.Falha na conexão com a impressora que irá imprimir o board.|

### UC14 Ser convidado para um Board

![Caso 14](imagens/casos de uso/)

### UC14 - Ser convidado para um Board

|  |  |
|  ------: | :------ |
| **Descrição** |Ter recebido um convite para participação de um board.|
| **Atores** |Usuário|
| **Pré Condições** | O usuário deve possuir uma conta de e-mail.|
| **Pós Condições** |O usuário terá um convite que lhe dá acesso a um board.|
| **Fluxo Principal** |FP01 - Criar Board <br>1. O usuário confirma o convite|
| **Fluxos de Exceção** | 1. Falta de internet, apresentando a mensagem de erro ao usuário. <br> 2. O usuário não apresenta interesse.|

### UC15 Criar um time

![Caso 15](imagens/casos de uso/)

### UC15 - Criar um time

|  |  |
|  ------: | :------ |
| **Descrição** |Ter um time para designar e coordenar tarefas, de acordo com o contexto do usuário.|
| **Atores** |Usuário|
| **Pré Condições** |O usuário deve estar logado na aplicação e possuir acesso a internet.|
| **Pós Condições** |O usuário terá um board com um time vinculado.|
| **Fluxo Principal** |FP01 - Criar Board <br> 1. O usuário loga na aplicação <br> 2. O usuário clica em criar um time|
| **Fluxos de Exceção** | 1. O usuário loga na aplicação <br> 2. O usuário clica em um board <br> 3. O usuário clica em adicionar membros|

### UC16 Convidar por E-mail

![Caso 16](imagens/casos de uso/)

## UC16 - Convidar por E-mail

|  |  |
|  ------: | :------ |
| **Descrição** | Ter a possibilidade de convidar mais participantes para contribuírem com o contexto do board.|
| **Atores** |Usuário|
| **Pré Condições** |O usuário deve estar logado na aplicação e possuir acesso a internet, possuir ou estar vinculado a um board.|
| **Pós Condições** |O usuário terá enviado um convite para uma ou mais pessoas de colaboração.|
| **Fluxo Principal** |FP01 - Criar Board <br> 1. O usuário loga na aplicação <br> 2. O usuário clica em um board <br> 3. O usuário clica em adicionar membros <br> 4. O usuário escreve o e-mail do membro que quer adicionar|
| **Fluxos de Exceção** | 1. Falta de internet, apresentando a mensagem de erro ao usuário.|

### UC17 Convidar pela Conta

![Caso 17](imagens/casos de uso/)

### UC17 - Convidar pela Conta

|  |  |
|  ------: | :------ |
| **Descrição** | Ter a possibilidade de convidar mais participantes para contribuírem com o contexto do board.|
| **Atores** |Usuário|
| **Pré Condições** | O usuário deve estar logado na aplicação e possuir acesso a internet, possuir ou estar vinculado a um board.|
| **Pós Condições** |O usuário terá enviado um convite para uma ou mais pessoas de colaboração.|
| **Fluxo Principal** |FP01 - Criar Board <br>1. O usuário loga na aplicação <br>2. O usuário clica em um board <br>3. O usuário clica em adicionar membros <br>4. O usuário escreve nome da conta do membro que quer adicionar|
| **Fluxos de Exceção** |1. Falta de internet, apresentando a mensagem de erro ao usuário.|

### UC18 Fechar Board

![Caso 18](imagens/casos de uso/)

### UC18 - Fechar Board

|  |  |
|  ------: | :------ |
| **Descrição** |Ter a possibilidade de fechar o board, para finalização do projeto que estava em andamento.|
| **Atores** |Usuário|
| **Pré Condições** |O usuário deve estar logado na aplicação e possuir acesso a internet, possuir ou estar vinculado a um board para que possa ser fechado.|
| **Pós Condições** | O usuário terá fechado o board da sua escolha.|
| **Fluxo Principal** |FP01 - Criar Board <br> 1. O usuário loga na aplicação <br> 2. O usuário clica em um board <br> 3. O usuário clica em fechar board|
| **Fluxos de Exceção** |1. Falta de internet, apresentando a mensagem de erro ao usuário.|

### UC19 Vincular Board

![Caso 19](imagens/casos de uso/)

### UC19 - Vincular Board

|  |  |
|  ------: | :------ |
| **Descrição** |Ter a possibilidade de vincular o board, para outro contexto.|
| **Atores** |Usuário|
| **Pré Condições** |O usuário deve estar logado na aplicação e possuir acesso a internet, possuir ou estar vinculado a um board.|
| **Pós Condições** |O usuário terá vinculado o seu board a um outro contexto, ligando ambos.|
| **Fluxo Principal** |FP01 - Criar Board <br> 1. O usuário loga na aplicação <br> 2. O usuário clica em um board <br> 3. O usuário gera o link para vincular o board|
| **Fluxos de Exceção** |1. Falta de internet, apresentando a mensagem de erro ao usuário.|

### UC20 Arquivar uma lista

![Caso 20](imagens/casos de uso/UC20.png)

###  UC20 - Arquivar uma lista

|  |  |
|  ------: | :------ |
|  **Descrição** | Tem como objetivo o arquivamento de uma lista para melhorar a organização de quadros, e remediar a poluição visual causada por listas desnecessárias. |
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado no sistema.<br>O tooltip de ações da lista deve estar selecionado. |
| **Fluxo Principal** | **FP01 - Arquivar Lista**<br>1. Usuário acessa as opções da lista.<br>2. Usuário clica em “Arquivar Lista”.<br>3. Lista arquivada com sucesso. Tooltip de ações da lista e fechado.<br> |
| **Fluxos Alternativos** | Não se aplica. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | A lista em questão é arquivada pelo usuário. |

### UC22 Modificar um Card

![Caso 22](imagens/casos de uso/)

### UC22 - Modificar um Card

|  |  |
|  ------: | :------ |
| **Descrição** | Ter a possibilidade de modificar um card existente.
| **Atores** | Usuário
| **Pré Condições** | O usuário deve estar logado na aplicação, possuir acesso a internet, possuir ou estar vinculado a um board, lista e card.
| **Pós Condições** | O usuário terá modificado algum atributo do card selecionado caso o modifique.
| **Fluxo Principal** | O usuário loga na aplicação. <br> O usuário clica em um card. <br> O usuário escolhe um dos atributos a ser modificado.
| **Fluxos Alternativos** | [UC26-Adicionar Membro](#uc26-adicionar-membro-a-um-card) <br> [UC27-Adicionar Descrição](#uc27-adicionar-descrição-a-um-card) <br> [UC28-Adicionar Checklist](#uc28-adicionar-check-list-a-um-card) <br> [UC29-Adicionar Etiqueta](#uc29-adicionar-etiqueta-a-um-card) <br> [UC30-Adicionar Deadline](#uc30-adicionar-deadline-a-um-card) <br> [UC33-Adicionar Anexo](#uc33-adicionar-anexo-a-um-card) <br> [UC36-Adicionar Power-Up](#uc36-adicionar-power-up)
| **Fluxos de Exceção** | Falta de internet, apresentando a mensagem de erro ao usuário.

### UC23 Personalizar etiqueta

![Caso 23](imagens/casos de uso/UC23.png)

###   UC23 - Personalizar etiqueta

|  |  |
|  ------: | :------ |
|  **Descrição** | Tem como objetivo personalizar uma etiqueta para facilitar seu entendimento. |
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado no sistema.<br>Página de etiquetas deve estar selecionada. |
| **Fluxo Principal** | **FP01 - Personalizar Etiqueta**<br>1. Usuário clica em “Mostrar Menu”.<br>2. Usuário clica em “Etiquetas”.<br>3. Usuário clica em no botão de personalização de etiquetas.<br> 4. Usuário digita um nome e escolhe uma cor, depois clica em “salvar”.<br> 5. Etiqueta personalizada com sucesso, usuário é redirecionado para página principal das etiquetas. |
| **Fluxos Alternativos** | **FA01 - Personalizar Etiqueta pelo Card**<br>1. Usuário seleciona um card.<br>2. Usuário clica em “Etiquetas”.<br>3. Usuário clica em no botão de personalização de etiquetas.<br> 4. Usuário digita um nome e escolhe uma cor, depois clica em “salvar”.<br> 5. Etiqueta personalizada com sucesso, usuário é redirecionado para página principal das etiquetas. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Etiqueta é personalizada para facilitar o seu entendimento. |

### UC24 Arquivar um Card

![Caso 24](imagens/casos de uso/UC24.png)

###   UC24 - Arquivar um Card

|  |  |
|  ------: | :------ |
|  **Descrição** | Tem como objetivo o arquivamento de um card para melhorar a organização de quadros e listas, remediando assim a poluição visual causada por cards desnecessários. |
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado no sistema.<br>O Usuário deve estar em um Board. |
| **Fluxo Principal** | **FP01 - Arquivar Card**<br>1. Usuário seleciona card.<br>2. Usuário clica em arquivar card.<br>3. Card arquivado com sucesso.<br>  |
| **Fluxos Alternativos** | **FA01 - Arquivar Card pelas Opções**<br>1. Usuário clica no botão de opções do card.<br>2. Usuário clica em arquivar card.<br>3. Card arquivado com sucesso.<br> |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Card é arquivado pelo usuário.|

### UC25 Seguir um Card

![Caso 25](imagens/casos de uso/UC25.png)

###   UC25 - Seguir um Card

|  |  |
|  ------: | :------ |
|  **Descrição** | Tem como objetivo Seguir um card para ser notificado de quando acontecem ações envolvendo o card seguido. |
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado no sistema.<br>Card deve estar selecionado. |
| **Fluxo Principal** | **FP01 - Seguir Card**<br>1. Usuário seleciona card.<br>2. Usuário clica em “Seguir”. <br>3. Card sendo seguido com sucesso.<br>  |
| **Fluxos Alternativos** | Não se aplica. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Card passa a ser seguido pelo usuário.|

### UC26 Adicionar Membro a um Card

![Caso 26](imagens/casos de uso/)

### UC26 - Adicionar Membro a um Card

|  ------: | :------ |
| **Descrição** | Ter a possibilidade de adicionar um membro a um card existente.
| **Atores** | Usuário.
| **Pré Condições** | O usuário deve estar logado na aplicação, possuir acesso a internet, possuir ou estar vinculado a um board, lista e card.
| **Pós Condições** | O usuário terá adicionado um novo membro caso o tenha feito.
| **Fluxo Principal** | O usuário loga na aplicação. <br> O usuário clica em um card. <br> O usuário clica em 'Adicionar Membro ao Card'. <br> O usuário escolhe o membro da board a ser adicionado ao card.
| **Fluxos de Exceção** |Falta de internet, apresentando a mensagem de erro ao usuário.

### UC27 Adicionar Descrição a um Card

![Caso 27](imagens/casos de uso/)

### UC27 - Adicionar Descrição a um Card

|  ------: | :------ |
| **Descrição** | Ter a possibilidade de adicionar a descrição a um card.
| **Atores** | Usuário.
| **Pré Condições** | O usuário deve estar logado na aplicação, possuir acesso a internet, possuir ou estar vinculado a um board, lista e card.
| **Pós Condições** | O usuário terá adicionado uma nova descrição caso o tenha feito.
| **Fluxo Principal** | O usuário loga na aplicação. <br> O usuário clica em um card. <br> O usuário clica em 'Adicionar Descrição ao Card'. <br> O usuário insere a nova descrição do card.
| **Fluxos de Exceção** |Falta de internet, apresentando a mensagem de erro ao usuário.

### UC28 Adicionar Check-list a um Card

![Caso 28](imagens/casos de uso/)

### UC28 - Adicionar Check-list a um Card

|  ------: | :------ |
| **Descrição** | Ter a possibilidade de adicionar a checklist a um card.
| **Atores** | Usuário.
| **Pré Condições** | O usuário deve estar logado na aplicação, possuir acesso a internet, possuir ou estar vinculado a um board, lista e card.
| **Pós Condições** | O usuário terá adicionado uma nova check-list caso a tenha feito.
| **Fluxo Principal** | O usuário loga na aplicação. <br> O usuário clica em um card. <br> O usuário clica em 'Adicionar Check-list ao Card'. <br> O usuário insere a nova check-list ao card.
| **Fluxos de Exceção** | Falta de internet, apresentando a mensagem de erro ao usuário.


### UC29 Adicionar Etiqueta a um Card

![Caso 29](imagens/casos de uso/)

### UC29 - Adicionar Etiqueta a um Card

|  ------: | :------ |
| **Descrição** | Ter a possibilidade de adicionar a etiqueta a um card existente.
| **Atores** | Usuário.
| **Pré Condições** | O usuário deve estar logado na aplicação, possuir acesso a internet, possuir ou estar vinculado a um board, lista e card.
| **Pós Condições** | O usuário terá adicionado uma nova etiqueta caso a tenha feito.
| **Fluxo Principal** | O usuário loga na aplicação. <br> O usuário clica em um card. <br> O usuário clica em 'Adicionar Etiqueta ao Card'. <br> O usuário insere a nova etiqueta ao card.
| **Fluxos de Exceção** | Falta de internet, apresentando a mensagem de erro ao usuário.


### UC30 Adicionar Deadline a um Card

![Caso 30](imagens/casos de uso/)

### UC30 - Adicionar Deadline a um Card

|  ------: | :------ |
| **Descrição** | Ter a possibilidade de adicionar a deadline a um card existente.
| **Atores** | Usuário.
| **Pré Condições** | O usuário deve estar logado na aplicação, possuir acesso a internet, possuir ou estar vinculado a um board, lista e card.
| **Pós Condições** | O usuário terá adicionado uma nova deadline caso a tenha feito.
| **Fluxo Principal** | O usuário loga na aplicação. <br> O usuário clica em um card. <br> O usuário clica em 'Adicionar Deadline ao Card'. <br> O usuário insere a nova deadline ao card.
| **Fluxos de Exceção** | Falta de internet, apresentando a mensagem de erro ao usuário.

### UC31 Adicionar Comentário a um Card

![Caso 31](imagens/casos de uso/)

### UC31 - Adicionar Comentário a um Card

|  ------: | :------ |
| **Descrição** | Ter a possibilidade de adicionar um comentário a um card.
| **Atores** | Usuário.
| **Pré Condições** | O usuário deve estar logado na aplicação, possuir acesso a internet, possuir ou estar vinculado a um board, lista e card.
| **Pós Condições** | O usuário terá adicionado um novo comentário caso a tenha feito.
| **Fluxo Principal** | O usuário loga na aplicação. <br> O usuário clica em um card. <br> O usuário clica no ícone de balão de fala. <br> O usuário insere o comentário.
| **Fluxos Alternativos** | O usuário loga na aplicação. <br> O usuário clica em um card. <br> O usuário clica no ícone de balão de fala. <br> O usuário clica em um comentário já existente. <br> O usuário insere um novo comentário respondendo o anterior.
| **Fluxos de Exceção** | Falta de internet, apresentando a mensagem de erro ao usuário.


### UC32 Alterar permissão de comentário

![Caso 32](imagens/casos de uso/caso32.png)

### UC32 - Alterar permissão de comentário

|  |  |
|  ------: | :------ |
|  **Descrição** | Ter a possibilidade de alterar quem pode comentar em cards de um board.|
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado na aplicação e possuir acesso a internet e possuir um board.|
| **Fluxo Principal** | 1. O usuário loga na aplicação<br>2. O usuário clica em um board<br>3. O usuário clica no botão 'Mostrar menu'. <br>4. O usuário clica no botão 'Mais'. <br>5. O usuário clica no botão 'Configurações'. <br>6. O usuário seleciona as 'Permissões de comentário'. <br>7. O usuário escolhe as 'Permissões de comentário' desejadas.|
| **Fluxos Alternativos** | Não se aplica. |
| **Fluxos de Exceção** | Falta de internet, apresentando a mensagem de erro ao usuário.|
| **Pós Condições** | O usuário terá gerenciado quem pode comentar cards em um determinado board.|


### UC33 Adicionar Anexo a um Card

![Caso 33](imagens/casos de uso/)

### UC33 - Adicionar Anexo a um Card

|  ------: | :------ |
| **Descrição** | Ter a possibilidade de adicionar um anexo a um card.
| **Atores** | Usuário.
| **Pré Condições** | O usuário deve estar logado na aplicação, possuir acesso a internet, possuir ou estar vinculado a um board, lista e card.
| **Pós Condições** | O usuário terá adicionado um novo anexo caso a tenha feito.
| **Fluxo Principal** | O usuário loga na aplicação. <br> O usuário clica em um card. <br>O usuário clica em  'Adicionar Anexo' <br> O usuário insere o arquivo desejado.
| **Fluxos de Exceção** | Falta de internet, apresentando a mensagem de erro ao usuário.

### UC34 Mover um card para outra list

![Caso 34](imagens/casos de uso/caso34.png)

### UC34 - Mover um card para outra list

|  |  |
|  ------: | :------ |
|  **Descrição** | Ter a possibilidade de mover um card de uma lista para outra, para outro contexto.|
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado na aplicação e possuir acesso a internet, possuir ou estar vinculado a um board, e este board possuir 2 ou mais listas com ao menos 1 card em alguma delas.|
| **Fluxo Principal** | 1. O usuário loga na aplicação.<br>2. O usuário clica em um board.<br>3. O usuário arrasta o card desejado para outra lista.|
| **Fluxos Alternativos** | Não se aplica. |
| **Fluxos de Exceção** | Falta de internet, apresentando a mensagem de erro ao usuário.|
| **Pós Condições** | O usuário terá movido o card a uma outra lista.|

### UC35 Compartilhar card

![Caso 35](imagens/casos de uso/caso35.png)

### UC35 - Compartilhar card

|  |  |
|  ------: | :------ |
|  **Descrição** | Ter a possibilidade de compartilhar um card.|
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado na aplicação e possuir acesso a internet, possuir ou estar vinculado a um board, e este board possuir 1 ou mais listas com ao menos 1 card em alguma delas.|
| **Fluxo Principal** | 1. O usuário loga na aplicação.<br>2. O usuário clica em um board.<br>3. O usuário clica no card desejado. .<br>4. O usuário clica na opção 'Compartilhar e mais...'. .<br>5. O usuário terá um referencial do card .|
| **Fluxos Alternativos** | Não se aplica. |
| **Fluxos de Exceção** | Falta de internet, apresentando a mensagem de erro ao usuário.|
| **Pós Condições** | O usuário terá compartilhado o card. |

### UC36 Adicionar power-up

![Caso 36](imagens/casos de uso/)

### UC36 - Adicionar power-up

|  |  |
|  ------: | :------ |
| **Descrição** | Ter a possibilidade de adicionar um power-up a um card.
| **Atores** | Usuário.
| **Pré Condições** | O usuário deve estar logado na aplicação, possuir acesso a internet, possuir ou estar vinculado a um board, lista e card.
| **Pós Condições** | O usuário terá adicionado um novo power-up no card.
| **Fluxo Principal** | O usuário loga na aplicação. <br> O usuário clica em um card. <br> O usuário clica em  'Adicionar Powe-Up' <br> O usuário seleciona o power-up desejado.
| **Fluxos de Exceção** | Falta de internet, apresentando a mensagem de erro ao usuário. <br> Caso não seja o primeiro power-up no card e o usuário não esteja em algum plano pago, não é possível adicionar outro power-up.


### UC37 Criar Lista

![Caso 37](imagens/casos de uso/caso018.png)

### UC37 - Criar Lista

|  |  |
|  ------: | :------ |
|  **Descrição** | Tem como objetivo criar uma nova lista para colocar cards. |
| **Atores** | Usuário |
| **Pré Condições** | Usuário deve possuir uma conta do trello e estar vinculado a um board. |
| **Fluxo Principal** | **FP01 - Cadastro**<br>1. Abre a página inicial do trello.<br>2. Usuário clica no botão “Adicionar outra lista”.<br>3. Usuário informa o nome da lista desejada.<br>4. Caso de uso encerrado. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Usuário terá criado uma nova lista para colocar novos cards. |

### UC38 Alterar nome de uma lista

![Caso 38](imagens/casos de uso/caso019.png)

### UC38 - Alterar nome de uma lista

|  |  |
|  ------: | :------ |
|  **Descrição** | Tem como objetivo alterar o nome de uma lista. |
| **Atores** | Usuário |
| **Pré Condições** | Usuário deve possuir email, estar vinculado a um board e ter uma lista no board. |
| **Fluxo Principal** | **FP01 - Cadastro**<br>1. Abre a página inicial do trello.<br>2. Usuário clica no nome da lista atual.<br>3. Usuário informa o novo nome da lista desejada.<br>4. Caso de uso encerrado. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Usuário terá outro nome para uma determinada lista. |

### UC39 Criar card

![Caso 39](imagens/casos de uso/caso021.png)

### UC39 - Criar card

|  |  |
|  ------: | :------ |
|  **Descrição** | Tem como objetivo criar um card. |
| **Atores** | Usuário |
| **Pré Condições** | Usuário deve possuir email, estar vinculado a um board e ter no mínimo uma lista. |
| **Fluxo Principal** | **FP01 - Cadastro**<br>1. Abre a página inicial do trello.<br>2. Usuário clica em "adicionar um cartão".<br>3. Usuário informa o novo nome do cartão desejado.<br>4. Usuário adiciona descrição do card. <br>5. Caso de uso encerrado. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Usuário terá um card com descrição de uma tarefa. |

------------

### UC40: Atualizar time para Business Class

![Caso 40](imagens/casos%20de%20uso/business.png)

### UC40 - Adicionar power-up

|  |  |
|  ------: | :------ |
|  **Descrição** | Aqui o usuário deseja atualizar o plano do seu time para Business Class. |
| **Atores** | Usuário |
| **Pré Condições** | Usuário deve possuir cadastro no sistema.<br>Usuário deve possuir um time |
| **Fluxo Principal** | **FP01 - Atualizar para Business Class**<br>1. O usuário seleciona um time para atualizá-lo para business class<br>2. Usuário abre a de atualização para business class.<br>3. Usuário escolhe um plano de pagamento, anual ou mensal<br>4. Usuário insere as informações do cartão de crédito. |
| **Fluxos Alternativos** | **FA01 - Alterar senha [UC01]**<br>1. Usuário cria um time para que iniciar como Business Class<br>2. Continua do Passo 2 do FP01<br>**FA02 - Usuário inicia da página do Business Class**<br>1. Usuário começa na página de informações do business class<br>2. Usuário visualiza estudos de caso de empresas de sucesso que utilizaram o Trello<br>3. Usuário pode voltar a suas boards<br>**FA03 - Usuário**|
| **Fluxos de Exceção** | **FE01 - Informações erradas do cartão de crédito**<br>1. [FP01.4] Usuário insere informações de cartão de crédito que não conferem<br>2. Mensagem de erro é exibida ao usuário|
| **Pós Condições** | O time escolhido/ criado pelo usuário será convertido para business class e terá direito às vantagens do plano. |

### UC41: Filtrar cartões

![Caso 41](imagens/casos%20de%20uso/filtro.png)

### UC41 - Adicionar power-up

|  |  |
|  ------: | :------ |
|  **Descrição** | Tem-se como objetivo aqui a exibição apenas de cards que batam com características desejadas pelo usuário. |
| **Atores** | Usuário |
| **Pré Condições** | Usuário deve possuir cadastro no sistema.<br>Usuário deve ter acesso a um board populado |
| **Fluxo Principal** | **FP01 - Filtrar Cartões**<br>1. O usuário abre as opções da board<br>2. O usuário clica em "Filtrar"<br>3. O usuário seleciona as opções de filtragem (FAs de 01 a 04, os quais necessariamente voltam ao fluxo principal neste ponto)<br>4. O usuário decide se filtragens por etiquetas e por usuários devem seguir lógica E (apenas cards com *todos* os usuários e etiquetas pesquisados aparecem na pesquisa) ou se deve seguir lógica OU (batem com a pesquisa cards que satisfaçam *qualquer* um dos atributos pesquisados, etiquetas ou usuários)<br>5. O sistema exibe apenas os cards que batem com a pesquisa|
| **Fluxos Alternativos** | **FA01 - Buscar por títulos**<br>1. O usuário digita o título pelo qual procura<br>**FA02 - Buscar por etiquetas**<br>1. O usuário seleciona as etiquetas que deseja<br>**FA03 - Busca por membros assinalados**<br>1. O usuário seleciona os membros que devem estar nos cards que procura<br>**FA04 - Busca por data de entrega**<br>1. O usuário escolhe uma opção de data de entrega a qual procura, a partir daqui, surge um, e apenas um, dos fluxos alternativos de 05 a 11.<br>**FA05 - Entregas em um dia**<br>1. O usuário seleciona a opção de datas de entrega em um dia<br>**FA06 - Entregas em uma semana**<br>1. O usuário seleciona a opção de datas de entrega em uma semana<br>**FA07 - Entregas em um mês**<br>1. O usuário seleciona a opção de datas de entrega em um mês<br>**FA08 - Entregas atrasadas**<br>1. O usuário seleciona a opção de cards não marcados como concluídos e que a data de entregue já tenha passado<br>**FA09 - Sem data de entrega**<br>1. O usuário seleciona a opção de cards sem data de entrega especificada<br>**FA10 - Entregas concluídas**<br>1. O usuário seleciona a opção de cards marcados como concluídos<br>**FA11 - Entregas não concluídas**<br>1. O usuário seleciona a opção de cards ainda não marcados como concluídos|
| **Fluxos de Exceção** | Não se aplica |
| **Pós Condições** | 1. O quadro irá exibir apenas cards que satisfaçam os critérios da pesquisa<br>2. Haverá uma opção no canto superior da tela que avisa que o modo de pesquisa está ativo e que oferece a opção de desativar |

### UC42 Exportar um board para JSON

![Caso 41](imagens/casos%20de%20uso/json.png)

### UC42 - Exportar um board para JSON

|  |  |
|  ------: | :------ |
|  **Descrição** | Tem como objetivo passar um board para código JSON. |
| **Atores** | Usuário |
| **Pré Condições** | Usuário deve possuir email e estar vinculado a um
board. |
| **Fluxo Principal** | **FP01 - Filtrar Cartões**<br>1. Abre a página inicial do trello.<br/>2. Usuário abre o menu lateral.<br/>3. Usuário seleciona a opção “Mais”.<br/>4. Usuário seleciona a opção “Imprimir e Exportar”.<br/>5. Usuário seleciona a opção “Exportar como JSON”.<br/>5. Caso de uso encerrado.|
| **Fluxos de Exceção** | Não se aplica |
| **Pós Condições** | 1. Usuário uma página que contém apenas o código JSON do Board. |
