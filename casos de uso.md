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

### UC...
### Descrição
digitetextodigitetextodigitetextodigitetextodigitetexto

### Atores
digitetextodigitetextodigitetextodigitetextodigitetexto

### Pré Condições
digitetextodigitetextodigitetextodigitetextodigitetexto

### Pós Condições
digitetextodigitetextodigitetextodigitetextodigitetexto

### Fluxo Principal
digitetextodigitetextodigitetextodigitetextodigitetexto

### Fluxos de Exceção
digitetextodigitetextodigitetextodigitetextodigitetexto

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
