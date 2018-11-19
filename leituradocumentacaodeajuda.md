---
layout: default
title: Leitura de documentação de Ajuda
category: Elicitação
---

[Lista de Autores do artefato](/artefatos.html)

# Leitura da Documentação de Ajuda

Em estudo das técnicas lecionadas em sala de aula, percebe-se uma adequação à situações onde o software sobre o qual se quer levantar requisitos sequer existe. Como, nesse caso, os requisitos levantados são referentes a um produto já consolidado e com extensa documentação de ajuda, esta será a fonte de informações para elicitação neste documento. Os textos como base da elicitação serão os presentes no [Guia](https://trello.com/guide?utm_source=trello&utm_medium=inapp&utm_content=header-tips&utm_campaign=guide) do Trello.

### Trello 101

O primeiro texto é o [Trello 101](https://trello.com/guide/trello-101). Nele são elucidados os primeiros conceitos a respeito do funcionamento da aplicação, através da leitura do texto já se pode destacar:

- CRUD de quadros
- CRUD de listas
- CRUD de cartões

Notam-se algumas outros requisitos também através das ilustrações, mas como essas funcionalidades não estão detalhadas neste texto, deixemos para elicitá-las mais à frente.

### Criar um Quadro

[Nesta etapa do guia](https://trello.com/guide/create-a-board), os processos de criação de quadros, listas e cartões já estão melhor detalhados. Já são citadas algumas funcionalidades mais elaboradas referentes à personalização de cartões e gestão do quadro. Assim, podemos elicitar:

- Suporte à deadlines nos cartões
- Criação de descrição nos cartões
- Criação de checklists nos cartões
- Armazenamentos de anexos nos cartões
- Comentários nos cartões
- Criação de cartões em massa
- Convite para membros do quadro
- Gestão de visibilidade do quadro
- Adição de times à quadros
- CRUD de times

Perceba que o guia menciona a gestão de times, mas ainda não chega a detalhar o processo de criação de times, mas por sua simples existência, supõe-se que seja necessário criar mecanismos que gerencie os times.

### Conhecendo Melhor os Recursos do Trello

A [próxima etapa](https://trello.com/guide/feature-deep-dive) consiste em descrever mais detalhadamente os requisitos já levantados acima. A partir desses detalhes, é possível inferir algumas funcionalidades ainda não citadas:

- Mencionar usuários em comentários
- Delegar cards a usuários
- Notificar prazos de entrega próximos a usuários assinalados
- Marcar data de entrega como concluída
- Integrar Trello com Dropbox
- Integrar Trello com OneDrive
- Integrar Trello com Google Drive
- Integrar Trello com Box
- Gerenciar membros do quadro
- Alterar plano de fundo
- Oferecer biblioteca de imagens para plano de fundo
- Interações com ferramentas externas
- Calendário integrado
- Campos personalizados

Nota-se muitos requisitos referentes à integração, isso evidencia a importância de uma **API aberta** que consiga comunicar com todas estas aplicações e qualquer outra que atenda às demandas de uma API REST. Ao fim do documento, o time decidiu não considerar cada integração como um requisito, pois não é de responsabilidade do Trello desenvolver cada uma destas integrações, apenas possibilitar a comunicação.

### Expandir seu uso do Trello

Este é um [guia voltado a ideias](https://trello.com/guide/expand-your-use-of-trello) sobre como utilizar os recursos já descritos anteriormente. Entretanto, ainda há uma ou outra novidade neste artigo:

- Compatibilidade com markdown nas descrições dos cards
- Adição de etiquetas aos cards
- Pesquisar cartões
- Anexar cartões e quadros a cartões
- Copiar quadro

No texto são mencionados inúmeros *Power-Ups* que podem ajudar no cumprimento das tarefas e dos modelos sugeridos. Esses Power-Ups consistem de integrações com ferramentais externos.

### Colaboração

Novamente, muitos requisitos já mencionados anteriormente estão aparecendo no [guia de colaboração](https://trello.com/guide/collaboration). Algumas novidades são:

- Seguir um cartão
- Seguir uma lista
- Seguir um quadro

O único novo recurso, além de power-ups que não são de responsabilidade unicamente do Trello, foi a possibilidade de seguir elementos dos quadros par que se possa ser avisado de alterações.

### Criando e administrando times

Os próximos dois artigos ([Criar um Time](https://trello.com/guide/create-a-team) e [Administração de Time](https://trello.com/guide/team-administration)) se tratam de como se organizar com outras pessoas no uso colaborativo da ferramenta. Já foi mencionado que times tem que ser criados, mas descreve um pouco melhor como isso acontece. Requisitos necessários para isso, segundo a documentação:

- Visualizar membros de um time
- Editar visibilidade do time
- Gerenciar administradores do time
- Detalhar time
- Gerenciar membros

Percebe-se que são funcionalidades comuns e esperadas do que diz respeito a manter times, por isso é importante documentá-las.

### Dicas do Pro

Aqui temos um [artigo voltado a usos um pouco mais avançados](https://trello.com/guide/pro-tips) da aplicação.

- Compatibilidade com atalhos de teclado
- Transformar e-mail em quadros
- Favoritar quadros
- Visualizar todos os cartões assinalados em uma única página
- Mecanismo de busca por todos os quadros

Após esse artigo, há um outro sobre boas práticas de trabalho em equipe, mas que não mencionam mais novas funcionalidades do Trello.

## Compilado do levantamento

|  **#** | **Nome** |
|  ------ | ------ |
|  1 | CRUD de Quadros |
|  2 | CRUD de listas |
|  3 | CRUD de cartões |
|  4 | Suporte à deadlines nos cartões |
|  5 | Criação de descrição nos cartões |
|  6 | Criação de checklists nos cartões |
|  7 | Armazenamentos de anexos nos cartões |
|  8 | Comentários nos cartões |
|  9 | Criação de cartões em massa |
|  10 | Convite para membros do quadro |
|  11 | Gestão de visibilidade do quadro |
|  12 | Adição de times à quadros |
|  13 | CRUD de times |
|  14 | Mencionar usuários em comentários |
|  15 | Delegar cards a usuários |
|  16 | Notificar prazos de entrega próximos a usuários assinalados |
|  17 | Marcar data de entrega como concluída |
|  18 | Gerenciar membros do quadro |
|  19 | Alterar plano de fundo |
|  20 | Oferecer biblioteca de imagens para plano de fundo |
|  21 | Interações com ferramentas externas |
|  22 | Campos personalizados |
|  23 | Compatibilidade com markdown nas descrições dos cards |
|  24 | Adição de etiquetas aos cards |
|  25 | Pesquisar cartões |
|  26 | Anexar cartões e quadros a cartões |
|  27 | Copiar quadro |
|  28 | Seguir um cartão |
|  29 | Seguir uma lista |
|  30 | Seguir um quadro |
|  31 | Visualizar membros de um time |
|  32 | Editar visibilidade do time |
|  33 | Gerenciar administradores do time |
|  34 | Detalhar time |
|  35 | Gerenciar membros de um time |
|  36 | Compatibilidade com atalhos de teclado |
|  37 | Transformar e-mail em quadros |
|  38 | Favoritar quadros |
|  39 | Visualizar todos os cartões assinalados em uma única página |
|  40 | Mecanismo de busca por todos os quadros |