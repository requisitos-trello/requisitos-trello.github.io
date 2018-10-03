---
layout: default
title: Casos de Uso
category: Modelagem
---

# Casos de uso
Diagramas de casos de uso, ou diagramas comportamentais na documentação UML, são responsáveis por descrever as principais funcionalidades do sistema e a interação dessas funcionalidades com os usuários do próprio sistema.
Para tal, o diagrama dispõe de atores que representam usuários ou sistemas que interagem com o sistema em questão, elipses que representam ações e relações entre as elipses, que podem ser do tipo include ou extend.

## Diagramas:

### Caso 1: Fazer Login

![Caso 1](imagens/casos de uso/UC01.png)

### UC01 - Fazer Login

|  |  |
|  ------: | :------ |
|  **Descrição** | Tem como objetivo Ter acesso a seus boards e times. |
| **Atores** | Usuário |
| **Pré Condições** | Usuário deve possuir cadastro no sistema. |
| **Fluxo Principal** | **FP01 - Fazer Login**<br>1. Abre a página inicial do trello.<br>2. Usuário clica no botão “Fazer Login”.<br>3. Usuário informa seu e-mail e senha.<br>4. Usuário clica no botão “Fazer Login”.<br>5. Caso de uso encerrado. |
| **Fluxos Alternativos** | **FA01 - Alterar senha [UC03]**<br>1. Abre a página de Login.<br>2. Usuário clica no link “Esqueceu sua senha?”.<br>3. Usuário digita seu “Email”.<br>4. Usuário clica no botão “Enviar”.<br>5. Usuário recebe um e-mail para redefinir sua senha. <br>6. Usuário abre o e-mail recebido.<br>7. Usuário clica no botão “Redefinir Senha”.<br>8. Usuário insere a nova senha.<br>9. Usuário insere a nova senha novamente.<br>10. Usuário clica no botão ‘Enviar’.<br>11. Usuário retorna para o primeiro passo do fluxo principal.<br>**FA02 - Fazer Login com o Google**<br>1. Abre a página inicial do trello.<br>2. Usuário clica no botão “Fazer Login”.<br>3. Usuário clica no botão “Fazer Login com o Google”.<br>4. Usuário insere o endereço de e-mail ou telefone.<br>5. Usuário clica no botão “Próxima”.<br>6. Usuário insere a senha.<br>7. Usuário clica no botão “Próxima”.<br>8. Usuário estará logado na aplicação.<br>9. Caso de uso encerrado. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Usuário estará logado no sistema. |


### Caso 2: Cadastro

![Caso 2](imagens/casos de uso/UC02.png)

### UC02 - Cadastro

|  |  |
|  ------: | :------ |
|  **Descrição** | Tem como objetivo criar uma nova conta no sistema. |
| **Atores** | Usuário |
| **Pré Condições** | Usuário deve possuir email. |
| **Fluxo Principal** | **FP01 - Cadastro**<br>1. Abre a página inicial do trello.<br>2. Usuário clica no botão “Cadastre-se”.<br>3. Usuário informa seu nome, e-mail e senha.<br>4. Usuário clica no botão “Criar Nova Conta”.<br>5. Caso de uso encerrado. |
| **Fluxos Alternativos** | **FA01 - Fazer Cadastro com o Google**<br>1. Abre a página de Login.<br>2. Usuário clica no botão “Cadastre-se”.<br>3. Usuário clica no botão “Cadastre-se com o Google”.<br>4. Usuário insere o endereço de e-mail.<br>5. Usuário clica no botão “Próxima”. <br>6. Usuário insere a senha.<br>7. Usuário clica no botão “Próxima”.<br>8. Caso de uso encerrado. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Usuário terá criado uma nova conta no sistema. |


### Caso 3: Alterar Senha

![Caso 3](imagens/casos de uso/UC03.png)

### UC03 - Alterar Senha

|  |  |
|  ------: | :------ |
|  **Descrição** | Tem como objetivo alterar senha de uma conta existente. |
| **Atores** | Usuário |
| **Pré Condições** | Usuário deve possuir uma conta. |
| **Fluxo Principal** | **FP01 - Alterar Senha**<br>1. Abre a página inicial do trello.<br>2. Usuário clica no seu avatar.<br>3. Usuário clica em “Configurações”.<br>4. Usuário clica em “Alterar Senha…”.<br>5. Usuário informa sua senha atual e sua nova senha.<br>6. Usuário clica no botão “Salvar”.<br>7. Caso de uso encerrado. |
| **Fluxos Alternativos** | **FA01 - Esqueci minha senha**<br>1. Abre a página de Login.<br>2. Usuário clica no link “Esqueceu sua senha?”.<br>3. Usuário digita seu “Email”.<br>4. Usuário clica no botão “Enviar”.<br>5. Usuário recebe um e-mail para redefinir sua senha. <br>6. Usuário abre o e-mail recebido.<br>7. Usuário clica no botão “Redefinir Senha”.<br>8. Usuário insere a nova senha.<br>9. Usuário insere a nova senha novamente.<br>10. Usuário clica no botão ‘Enviar’.<br>11. Caso de uso encerrado. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Usuário terá alterado a senha de sua conta no sistema. |


### Caso 4: Alterar Configurações

![Caso 4](imagens/casos de uso/UC04.png)

### UC04 - Alterar Configurações

|  |  |
|  ------: | :------ |
|  **Descrição** | Tem como objetivo alterar configurações, tanto do trello quanto da conta. |
| **Atores** | Usuário |
| **Pré Condições** | Usuário deve possuir uma conta. |
| **Fluxo Principal** | **FP01 - Alterar Configurações**<br>1. Abre a página inicial do trello estando logado.<br>2. Usuário clica no seu avatar.<br>3. Usuário clica em “Configurações”.<br>4. Caso de uso encerrado. |
| **Fluxos Alternativos** | **FA01 - Alterar nome**<br>1. A partir do passo 3 do fluxo principal.<br>2. Usuário clica no link “Alterar Nome, Iniciais ou Biografia...”.<br>3. Usuário digita os dados a serem editados.<br>4. Usuário clica no botão “Salvar”.<br>5. Caso de uso encerrado.<br>**FA02 - Alterar Senha [UC04]**<br>1. A partir do passo 3 do fluxo principal.<br>2. Usuário clica no link “Alterar Senha...”.<br>3. Usuário digita os dados exigidos.<br>4. Usuário clica no botão “Salvar”.<br>5. Caso de uso encerrado.<br>**FA03 - Alterar avatar**<br>1. A partir do passo 3 do fluxo principal.<br>2. Usuário clica no link “Alterar Avatar...”.<br>3. Usuário escolhe a nova imagem.<br>4. Caso de uso encerrado.<br>**FA04 - Alterar email**<br>1. A partir do passo 3 do fluxo principal.<br>2. Usuário clica no link “Alterar Email...”<br>3. Usuário digita o novo email.<br>4. Usuário clica no botão “Alterar E-mail”.<br>5. Caso de uso encerrado.<br>**FA05 - Adicionar novo email**<br>1. A partir do passo 3 do fluxo principal.<br>2. Usuário clica no botão “Adicionar novo endereço de email”.<br>3. Usuário digita o novo email.<br>4. Usuário clica no botão “Enviar Email de Confirmação”.<br>5. Caso de uso encerrado.<br>**FA06 - Alterar frequência de email de notificação**<br>1. A partir do passo 3 do fluxo principal.<br>2. Usuário clica no botão “Alterar frequência de email de notificação”.<br>3. Usuário escolhe a opção desejada.<br>4. Caso de uso encerrado.<br>**FA07 - Permitir notificações da Área de Trabalho**<br>1. A partir do passo 3 do fluxo principal.<br>2. Usuário clica no botão “Permitir Notificações da Área de Trabalho”.<br>3. Caso de uso encerrado. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Usuário terá alterado as configurações de sua conta no sistema. |


### Caso 5: Criar time

![Caso 5](imagens/casos de uso/caso5.png)

#### UC01 - Criar time

|  |  |
|  ------: | :------ |
|  **Descrição** | Tem como objetivo a criação de um time para melhorar a organização de quadros e arquivos que devem pertencer a um grupo específico de usuários. |
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado no sistema. |
| **Fluxo Principal** | **FP01 - Criar time**<br>1. Usuário acessa a opção de criar time.<br>2. Aciona UC02 - Adicionar nome. [FA01][FA02]<br>3. Time criado com sucesso. Usuário é redirecionado para página do time. |
| **Fluxos Alternativos** | **FA01 - Adicionar descrição** [UC03].<br>**FA02 - Acessar informações de business class** [UC04] |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Time é criado com informações dadas pelo usuário. |


#### UC02 - Adicionar nome

|  |  |
|  ------: | :------ |
|  **Descrição** | Permite nomear times criados pelo usuário. |
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado no sistema.<br> Formulário de criação de time deve estar selecionado.|
| **Fluxo Principal** | **FP01 - Adicionar nome**<br>1. Usuário digita o nome do time.<br>2. Usuário clica em no botão "criar".<br> 3. Retorna para UC01 - criar time, passo 3. |
| **Fluxos Alternativos** | Não se aplica. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Time é criado com informações dadas pelo usuário. |


#### UC03 - Adicionar descrição

|  |  |
|  ------: | :------ |
|  **Descrição** | Permite adicionar descrição a times criados pelo usuário. |
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado no sistema.<br> Formulário de criação de time deve estar selecionado.|
| **Fluxo Principal** | **FP01 - Adicionar descrição**<br>1. Usuário digita o nome do time.<br>2. Usuário digita descrição do time.<br>3. Usuário clica em no botão "criar".<br> 4. Retorna para UC01 - criar time, passo 3. |
| **Fluxos Alternativos** | Não se aplica. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Time é criado com informações dadas pelo usuário. |


#### UC04 - Acessar informações de business class

|  |  |
|  ------: | :------ |
|  **Descrição** | Permite ter acesso a informações relevantes sobre as vantagens da assinatura do plano de business class. |
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado no sistema.<br> Formulário de criação de time deve estar selecionado.|
| **Fluxo Principal** | **FP01 - Acessar informações de business class**<br>1. Usuário clica "saiba mais" no texto referente ao business class.<br>2. Nova guia do navegador é aberta contendo informações referentes ao business class.<br> |
| **Fluxos Alternativos** | Não se aplica. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Time é criado com informações dadas pelo usuário. |



### Caso 6: Adicionar/remover membros de time

![Caso 6](imagens/casos de uso/caso6.png)

#### UC01 - Acessar lista de membros

|  |  |
|  ------: | :------ |
|  **Descrição** | Permite ao usuário visualizar todos os membros de um time e suas permissões. |
| **Atores** | Administrador<br>Usuário |
| **Pré Condições** | O administrador do time deve estar logado no sistema.<br>|
| **Fluxo Principal** | **FP01 - Acessar lista de membros**<br>1. Usuário clica no time que deseja visualizar dentre os presentes no menu lateral.<br>2. O usuário clica em membros.<br>3. Sistema mostra lista de membros do time. [FE01][FA01][FA02] |
| **Fluxos Alternativos** | **FA01 - Remover membro** [UC02].<br>**FA02 - Convidar membro** [UC03] |
| **Fluxos de Exceção** | Não há membros no time. [UC03] |
| **Pós Condições** | Lista de membros do time é acessada pelo usuário |

#### UC02 - Remover membro

|  |  |
|  ------: | :------ |
|  **Descrição** | Permite ao usuário remover membros de um time. |
| **Atores** | Administrador<br>Usuário |
| **Pré Condições** | O administrador do time deve estar logado no sistema.<br> O usuário deve pertencer ao time.|
| **Fluxo Principal** | **FP01 - Remover membro**<br>1. O administrador do time clica em remover, logo a frente do nome do usuário e confirma. [FE01]<br>2. Sistema retorna mensagem de confirmação de remoção e atuliza lista. |
| **Fluxos Alternativos** | Não se aplica |
| **Fluxos de Exceção** | Não há membros no time. |
| **Pós Condições** | Membro é removido do time e lista de membros é atualizada. |

#### UC03 - Convidar membro

|  |  |
|  ------: | :------ |
|  **Descrição** | Permite ao usuário convidar membros para um time. |
| **Atores** | Administrador<br>Usuário |
| **Pré Condições** | O administrador do time deve estar logado no sistema.<br> O usuário deve possuir conta no trello.|
| **Fluxo Principal** | **FP01 - Convidar membro**<br>1. Sistema mostra lista de membros do time.[FE01] <br>2. O administrador do time clica em Convidar membros do time<br>3. Aciona UC04 - convidar por email/nome de usuário.[FA01][FA02]<br>4. Lista de membro é atualizada com o(s) novo(s) membro(s). |
| **Fluxos Alternativos** | **FA01 - Enviar link de convite** [UC05].<br>**FA02 - Adicionar várias pessoas** [UC06] |
| **Fluxos de Exceção** | Não há membros no time. Redireciona para passo 3. |
| **Pós Condições** | Membro é adicionado ao time. |

#### UC04 - Convidar por email/nome de usuário 

|  |  |
|  ------: | :------ |
|  **Descrição** | Permite ao administrador do time convidar membros para um time através de seu email ou nome de usuário. |
| **Atores** | Administrador<br>Usuário |
| **Pré Condições** | O administrador do time deve estar logado no sistema.<br> O usuário deve possuir conta no trello.|
| **Fluxo Principal** | **FP01 - convidar por email/nome de usuário**<br>1. Administrador do time digita nome de usuário ou email no formulário<br>2. Administrador clica em Adicionar ao time.<br>3. Retorna para UC03 - Convidar membro, passo 4. |
| **Fluxos Alternativos** | Não se aplica. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Membro é adicionado ao time. |

#### UC05 - Enviar link de convite

|  |  |
|  ------: | :------ |
|  **Descrição** | Permite ao administrador do time convidar membros através da criação de link. |
| **Atores** | Administrador<br>Usuário |
| **Pré Condições** | O administrador do time deve estar logado no sistema.<br> O usuário deve possuir conta no trello.|
| **Fluxo Principal** | **FP01 - convidar por email/nome de usuário**<br>1. Administrador do time clica em criar link.<br>2. Administrador do time clica em copiar.<br>3. Administrador envia link para usuários de sua escolha. |
| **Fluxos Alternativos** | Não se aplica. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** |Link de acesso ao grupo é criado. |

#### UC06 - Adicionar várias pessoas

|  |  |
|  ------: | :------ |
|  **Descrição** | Permite ao administrador do time convidar mais de um membro por vez. |
| **Atores** | Administrador<br>Usuário |
| **Pré Condições** | O administrador do time deve estar logado no sistema.<br> O usuário deve possuir conta no trello.|
| **Fluxo Principal** | **FP01 - convidar por email/nome de usuário**<br>1. Administrador do time clica em Adicionar várias pessoas de uma vez.<br>2. Administrador do time insere todos os emails e nomes de usuário que deseja adicionar no time.<br>3. Administrador clica em Adicionar eo time.<br>4. Retorna para UC03 - Convidar membro, passo 4 |
| **Fluxos Alternativos** | Não se aplica. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** |Link de acesso ao grupo é criado. |

### Caso 7: Alterar configurações de time

![Caso 7](imagens/casos de uso/caso7 (1).png)

#### UC01 - Acessar configurações de time

|  |  |
|  ------: | :------ |
|  **Descrição** | Tem como objetivo permitir o acesso às configurações de um time para alteração ou simples visualização. |
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado no sistema.<br>Usuário deve ser membro do time. |
| **Fluxo Principal** | **FP01 - Acessar configurações de time**<br>1. Usuário clica no time que deseja visualizar dentre os presentes no menu lateral.<br>2. O usuário clica em configurações.<br>3. Sistema mostra configurações do time. [FA01]<br>4. Aciona UC03 - Alterar visibilidade do time.<br>5. Aciona UC04 - Vincular time do slack. |
| **Fluxos Alternativos** | **FA01 - Editar perfil** [UC02]. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Configurações são acecssadas pelo usuário. |

#### UC02 - Editar perfil

|  |  |
|  ------: | :------ |
|  **Descrição** | Tem como objetivo editar informações básicas de um time. |
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado no sistema.<br>Usuário deve ser administrador do time. |
| **Fluxo Principal** | **FP01 - Editar perfil**<br>1. Usuário clica em editar perfil do time.<br>2. O usuário altera as informações de perfil.<br>3. O usuário clica em salvar<br>4. Aciona UC01 - Acessar configurações de time, passo 3. |
| **Fluxos Alternativos** | Não se aplica. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Informações de perfil de time devem ser atualizadas. |

#### UC03 - Alterar visibilidade do time

|  |  |
|  ------: | :------ |
|  **Descrição** | Permite alterar nível de visibilidade do time (público ou particular). |
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado no sistema.<br>Usuário deve ser administrador do time. |
| **Fluxo Principal** | **FP01 - Alterar visibilidade do time**<br>1. Usuário clica em alterar, que se encontra a frente da visibilidade do time.<br>2. O usuário seleciona a visibilidade que deseja para o time.<br>3. O usuário clica em salvar<br>4. Aciona UC01 - Acessar configurações de time, passo 3. |
| **Fluxos Alternativos** | Não se aplica. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Visibilidade do time deve ser atualizada. |

#### UC04 - Vincular time do slack

|  |  |
|  ------: | :------ |
|  **Descrição** | Permite vincular time do trello com time do slack, facilitando a comunicação com o grupo. |
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado no sistema.<br>Usuário deve ser administrador do time. |
| **Fluxo Principal** | **FP01 - Vincular time do slack**<br>1. Usuário clica em add to Slack. [FA01]<br>2. O usuário informa o nome do workspace do slack.<br>3. Sistema retorna página de termos<br>4. Usuário autoriza vinculação.<br>5. Aciona UC01 - Acessar configurações de time, passo 3. |
| **Fluxos Alternativos** |  **FA01 - Acessar informações de vinculação** [UC05] |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Time deve ser vinculado ao slack. |

#### UC05 - Acessar informações de vinculação

|  |  |
|  ------: | :------ |
|  **Descrição** | Permite ao usuário entender quais as vantagens de se vincular o time do trello com o time do slack. |
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado no sistema.<br>Usuário deve ser membro do time. |
| **Fluxo Principal** | **FP01 - Acessar informações de vinculação**<br>1. Usuário clica em saiba mais na sessão vinculação ao slack.<br>2. Sistema redireciona para página de informações de vinculação ao slack. |
| **Fluxos Alternativos** | Não se aplica. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Usuário tem acesso a informações relevantes sobre vinculação com trello |


### Caso 8:  Alterar configurações de board

![Caso 8](imagens/casos de uso/caso8.png)

#### UC01 - Acessar board

|  |  |
|  ------: | :------ |
|  **Descrição** | Tem como objetivo permitir o acesso boards dos quais participa. |
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado no sistema.<br> |
| **Fluxo Principal** | **FP01 - Acessar configurações de time**<br>1. Usuário clica em boards no menu lateral ou no header.<br>2. O sistema retorna lista de boards que o usuário participa.<br>3. Usuário seleciona board. [FE01]<br>4. sistema redireciona para página do board selecionado.<br>5. Aciona UC05 - Visualizar atividade. [FA01][FA02][FA03] |
| **Fluxos Alternativos** | **FA01 - Acessar mais opções do menu** [UC02].<br>**FA02 - Alterar tela de fundo** [UC03].<br>**FA01 - Adicionar/remover power-up** [UC04]. |
| **Fluxos de Exceção** | Usuário não participa de nenhum board. |
| **Pós Condições** | Usuário tem acesso aos dados do board. |

#### UC02 - Acessar mais opções do menu

|  |  |
|  ------: | :------ |
|  **Descrição** | Tem como objetivo permitir o acesso a configurações do board selecionado. |
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado no sistema. |
| **Fluxo Principal** | **FP01 - Acessar mais opções do menu**<br>1. Usuário clica em mostrar menu caso menu não esteja aberto.<br>2. Usuário clica em mais.<br>3. O sistema retorna mais opções para o menu |
| **Fluxos Alternativos** | Não se aplica. |
| **Fluxos de Exceção** | Usuário não participa de nenhum board. |
| **Pós Condições** | Usuário tem acesso aos dados do board. |

#### UC03 - Alterar tela de fundo

|  |  |
|  ------: | :------ |
|  **Descrição** | Tem como objetivo permitir a estilização do board. |
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado no sistema.<br>O usuário deve ser membro do board. |
| **Fluxo Principal** | **FP01 - Alterar tela de fundo**<br>1. Usuário clica em mostrar menu caso menu não esteja aberto.<br>2. Usuário clica em Alterar tela de fundo.<br>3. O sistema retorna opções de tela de fundo.<br>4. Usuário seleciona entre as cores e fotos disponíveis. |
| **Fluxos Alternativos** | Não se aplica. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Tela de fundo do board é alterada. |

#### UC04 - Adicionar/remover power-ups

|  |  |
|  ------: | :------ |
|  **Descrição** | Tem como objetivo editar os power-ups de um board. |
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado no sistema.<br>O usuário deve ser membro do board. |
| **Fluxo Principal** | **FP01 - Adicionar/remover power-ups**<br>1. Usuário clica em mostrar menu caso menu não esteja aberto.<br>2. Usuário clica em Power-ups.<br>3. O sistema retorna opções de power-ups que podem ser adicionados ao board.<br>4. Usuário seleciona entre os power-ups disponíveis. |
| **Fluxos Alternativos** | Não se aplica. |
| **Fluxos de Exceção** | Não se aplica. |
| **Pós Condições** | Power-ups do board são atualizados. |


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

## UC08 - Convidar por E-mail
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

## UC10 - Fechar Board
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


## UC22 - Modificar um Card

| **Descrição** | Eu, como usuário, desejo poder modificar um ou mais atributos de um card existente.
| **Atores** | Usuário
| **Pré Condições** | O usuário deve estar logado na aplicação, possuir acesso a internet, possuir ou estar vinculado a um board, lista e card.
| **Pós Condições** | O usuário terá modificado algum atributo do card selecionado caso o modifique.
| **Fluxo Principal** | O usuário loga na aplicação. <br> O usuário clica em um card. <br> O usuário escolhe um dos atributos a ser modificado.
| **Fluxos Alternativos** | [UC25-Adicionar Membro](#uc25---adicionar-membro-a-um-card) <br> [UC26-Adicionar Descrição](#uc26---adicionar-descrição-a-um-card) <br> [UC27-Adicionar Checklist](#uc27---adicionar-check-list-a-um-card) <br> [UC28-Adicionar Etiqueta](#uc28---adicionar-etiqueta-a-um-card) <br> [UC29-Adicionar Deadline](#uc29---adicionar-deadline-a-um-card) <br> [UC32-Adicionar Anexo](#uc32---adicionar-anexo-a-um-card) <br> [UC35-Adicionar Power-Up](#uc35---adicionar-power-up)
| **Fluxos de Exceção** | Falta de internet, apresentando a mensagem de erro ao usuário.

## UC25 - Adicionar Membro a um Card

| **Descrição** | Ter a possibilidade de adicionar um membro a um card existente.
| **Atores** | Usuário.
| **Pré Condições** | O usuário deve estar logado na aplicação, possuir acesso a internet, possuir ou estar vinculado a um board, lista e card.
| **Pós Condições** | O usuário terá adicionado um novo membro caso o tenha feito.
| **Fluxo Principal** | O usuário loga na aplicação. <br> O usuário clica em um card. <br> O usuário clica em 'Adicionar Membro ao Card'. <br> O usuário escolhe o membro da board a ser adicionado ao card.
| **Fluxos de Exceção** |Falta de internet, apresentando a mensagem de erro ao usuário.


## UC26 - Adicionar Descrição a um Card

| **Descrição** | Ter a possibilidade de adicionar a descrição a um card.
| **Atores** | Usuário.
| **Pré Condições** | O usuário deve estar logado na aplicação, possuir acesso a internet, possuir ou estar vinculado a um board, lista e card.
| **Pós Condições** | O usuário terá adicionado uma nova descrição caso o tenha feito.
| **Fluxo Principal** | O usuário loga na aplicação. <br> O usuário clica em um card. <br> O usuário clica em 'Adicionar Descrição ao Card'. <br> O usuário insere a nova descrição do card.
| **Fluxos de Exceção** |Falta de internet, apresentando a mensagem de erro ao usuário.


## UC27 - Adicionar Check-list a um Card

|  ------: | :------ |
| **Descrição** | Ter a possibilidade de adicionar a checklist a um card.
| **Atores** | Usuário.
| **Pré Condições** | O usuário deve estar logado na aplicação, possuir acesso a internet, possuir ou estar vinculado a um board, lista e card.
| **Pós Condições** | O usuário terá adicionado uma nova check-list caso a tenha feito.
| **Fluxo Principal** | O usuário loga na aplicação. <br> O usuário clica em um card. <br> O usuário clica em 'Adicionar Check-list ao Card'. <br> O usuário insere a nova check-list ao card.
| **Fluxos de Exceção** | Falta de internet, apresentando a mensagem de erro ao usuário.


## UC28 - Adicionar Etiqueta a um Card

|  ------: | :------ |
| **Descrição** | Ter a possibilidade de adicionar a etiqueta a um card existente.
| **Atores** | Usuário.
| **Pré Condições** | O usuário deve estar logado na aplicação, possuir acesso a internet, possuir ou estar vinculado a um board, lista e card.
| **Pós Condições** | O usuário terá adicionado uma nova etiqueta caso a tenha feito.
| **Fluxo Principal** | O usuário loga na aplicação. <br> O usuário clica em um card. <br> O usuário clica em 'Adicionar Etiqueta ao Card'. <br> O usuário insere a nova etiqueta ao card.
| **Fluxos de Exceção** | Falta de internet, apresentando a mensagem de erro ao usuário.


## UC29 - Adicionar Deadline a um Card

|  ------: | :------ |
| **Descrição** | Ter a possibilidade de adicionar a deadline a um card existente.
| **Atores** | Usuário.
| **Pré Condições** | O usuário deve estar logado na aplicação, possuir acesso a internet, possuir ou estar vinculado a um board, lista e card.
| **Pós Condições** | O usuário terá adicionado uma nova deadline caso a tenha feito.
| **Fluxo Principal** | O usuário loga na aplicação. <br> O usuário clica em um card. <br> O usuário clica em 'Adicionar Deadline ao Card'. <br> O usuário insere a nova deadline ao card.
| **Fluxos de Exceção** | Falta de internet, apresentando a mensagem de erro ao usuário.


## UC30 - Adicionar Comentário a um Card

|  ------: | :------ |
| **Descrição** | Ter a possibilidade de adicionar um comentário a um card.
| **Atores** | Usuário.
| **Pré Condições** | O usuário deve estar logado na aplicação, possuir acesso a internet, possuir ou estar vinculado a um board, lista e card.
| **Pós Condições** | O usuário terá adicionado um novo comentário caso a tenha feito.
| **Fluxo Principal** | O usuário loga na aplicação. <br> O usuário clica em um card. <br> O usuário clica no ícone de balão de fala. <br> O usuário insere o comentário.
| **Fluxos Alternativos** | O usuário loga na aplicação. <br> O usuário clica em um card. <br> O usuário clica no ícone de balão de fala. <br> O usuário clica em um comentário já existente. <br> O usuário insere um novo comentário respondendo o anterior.
| **Fluxos de Exceção** | Falta de internet, apresentando a mensagem de erro ao usuário.


### UC31 - Alterar permissão de comentário

|  |  |
|  ------: | :------ |
|  **Descrição** | Ter a possibilidade de alterar quem pode comentar em cards de um board.
|
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado na aplicação e possuir acesso a internet e possuir um board.|
| **Fluxo Principal** | 1. O usuário loga na aplicação<br>2. O usuário clica em um board<br>3. O usuário clica no botão 'Mostrar menu'. <br>4. O usuário clica no botão 'Mais'. <br>5. O usuário clica no botão 'Configurações'. <br>6. O usuário seleciona as 'Permissões de comentário'. <br>7. O usuário escolhe as 'Permissões de comentário' desejadas.|
| **Fluxos Alternativos** | Não se aplica. |
| **Fluxos de Exceção** | Falta de internet, apresentando a mensagem de erro ao usuário.|
| **Pós Condições** | O usuário terá gerenciado quem pode comentar cards em um determinado board.|


## UC32 - Adicionar Anexo a um Card

|  ------: | :------ |
| **Descrição** | Ter a possibilidade de adicionar um anexo a um card.
| **Atores** | Usuário.
| **Pré Condições** | O usuário deve estar logado na aplicação, possuir acesso a internet, possuir ou estar vinculado a um board, lista e card.
| **Pós Condições** | O usuário terá adicionado um novo anexo caso a tenha feito.
| **Fluxo Principal** | O usuário loga na aplicação. <br> O usuário clica em um card. <br>O usuário clica em  'Adicionar Anexo' <br> O usuário insere o arquivo desejado.
| **Fluxos de Exceção** | Falta de internet, apresentando a mensagem de erro ao usuário.


### UC33 - Mover um card para outra list

|  |  |
|  ------: | :------ |
|  **Descrição** | Ter a possibilidade de mover um card de uma lista para outra, para outro contexto.|
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado na aplicação e possuir acesso a internet, possuir ou estar vinculado a um board, e este board possuir 2 ou mais listas com ao menos 1 card em alguma delas.|
| **Fluxo Principal** | 1. O usuário loga na aplicação.<br>2. O usuário clica em um board.<br>3. O usuário arrasta o card desejado para outra lista.|
| **Fluxos Alternativos** | Não se aplica. |
| **Fluxos de Exceção** | Falta de internet, apresentando a mensagem de erro ao usuário.|
| **Pós Condições** | O usuário terá movido o card a uma outra lista.|


### UC34 - Compartilhar card

|  |  |
|  ------: | :------ |
|  **Descrição** | Ter a possibilidade de compartilhar um card.|
| **Atores** | Usuário |
| **Pré Condições** | O usuário deve estar logado na aplicação e possuir acesso a internet, possuir ou estar vinculado a um board, e este board possuir 1 ou mais listas com ao menos 1 card em alguma delas.|
| **Fluxo Principal** | 1. O usuário loga na aplicação.<br>2. O usuário clica em um board.<br>3. O usuário clica no card desejado. .<br>4. O usuário clica na opção 'Compartilhar e mais...'. .<br>5. O usuário terá um referencial do card .|
| **Fluxos Alternativos** | Não se aplica. |
| **Fluxos de Exceção** | Falta de internet, apresentando a mensagem de erro ao usuário.|
| **Pós Condições** | O usuário terá compartilhado o card. |


## UC35 - Adicionar Power-Up

|  ------: | :------ |
| **Descrição** | Ter a possibilidade de adicionar um power-up a um card.
| **Atores** | Usuário.
| **Pré Condições** | O usuário deve estar logado na aplicação, possuir acesso a internet, possuir ou estar vinculado a um board, lista e card.
| **Pós Condições** | O usuário terá adicionado um novo power-up no card.
| **Fluxo Principal** | O usuário loga na aplicação. <br> O usuário clica em um card. <br> O usuário clica em  'Adicionar Powe-Up' <br> O usuário seleciona o power-up desejado.
| **Fluxos de Exceção** | Falta de internet, apresentando a mensagem de erro ao usuário. <br> Caso não seja o primeiro power-up no card e o usuário não esteja em algum plano pago, não é possível adicionar outro power-up.
