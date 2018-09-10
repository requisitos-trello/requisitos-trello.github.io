---
layout: default
title: Backlog
category: Artefatos
---

Segue na tabela p backlog levantado pelas técnicas de elicitação e entendimento do problema.

Aqui utilizando-se da técnica MoSCoW (Must, Should, Could, Would)

|  Código | Nome | MoSCoW |
|  ------: | :------ | :------ |
|  1 | Integração com outras ferramentas (Power-Ups) | Should |
|  2 | CRUD de Board | Must |
|  3 | CRUD de Card | Must |
|  4 | CRUD da Lista | Must |
|  5 | CRUD de Checklist em Cards | Must |
|  6 | Compartilhamento de Boards | Must |
|  7 | Etiquetar o card | Should |
|  8 | Convidar pessoas | Could |
|  9 | Notificar prazos | Should |
|  10 | Criar uma Data de Entrega para uma Card | Should |
|  11 | Assinalar uma tarefa a si mesmo ou outros membros do Board | Should |
|  12 | Seguir uma tarefa | Should |
|  13 | Notificar seguidores sobre alterações na tarefa | Should |
|  14 | CRUD de Comentários | Should |
|  15 | Criar conta no Trello | Must |
|  16 | Recuperar conta | Must |
|  17 | Adicionar descrição a tarefas | Must |
|  18 | Incluir anexos em cards (Computador, Google Drive, Dropbox, Box, OneDrive) | Could |
|  19 | Colocar stickers no card | Would |
|  20 | Mover Card | Must |
|  21 | Copiar um Card | Should |
|  22 | Arquivar um Card | Must |
|  23 | Imprimir um Card | Would |
|  24 | Exportar por JSON um Card | Would |
|  25 | Gerar feed de atividades da board | Could |
|  26 | Rastrear alterações no card | Could |
|  27 | Copiar Lista | Could |
|  28 | Mover Lista | Must |
|  29 | Mover todos os Cards de uma Lista | Could |
|  30 | Arquivar todos os Cards de uma Lista | Could |
|  31 | Arquivar uma Lista | Should |
|  32 | Filtrar Cards | Should |
|  33 | Sair de um Board | Must |
|  34 | Seguir um Board | Could |
|  35 | Copiar um Board | Would |
|  36 | Mencionar um Card em um comentário | Could |
|  37 | Mencionar um membro de um comentário | Should |
|  38 | Incluir anexos em comentários | Could |
|  39 | Responder um comentário | Would |
|  40 | Incluir emoji em um comentário | Would |

A segunda tabela utiliza-se da técnica de First Things First. A equipe estimou **Benefício Relativo**, **Penalidade Relativa**, **Custo de Implementação** e **Risco de Implementação**. Após as estimativas, benefício e penalidade foramm somados em **Valor**, e então foi calculado o valor relativo ao total da coluna, obtendo assim o **Valor %**. Em seguida, o mesmo procedimento de percentual foi feito com as colunas de Custo e Risco, obtendo **Custo %** e **Risco %**. Finalmente, calculamos a prioridade com a equação **Valor% / (Custo% + Risco%)**. Segue o resultado ordenado por prioridade. 

| Código | Nome                                                                       | Benefício | Penalidade | Valor | Valor % | Custo | Custo % | Risco | Risco % | Prioridade | 
|--------:|----------------------------------------------------------------------------|:-----------:|:---------------------:|:-------:|:------------------:|:--------------------------:|:------------------:|:-------:|:------------------:|:------------| 
| 15     | Criar conta no Trello                                                      | 9         | 9                   | 18    | 3,99%            | 2                        | 1,42%            | 2     | 1,55%            | 1,3443     | 
| 33     | Sair de um Board                                                           | 7         | 8                   | 15    | 3,33%            | 2                        | 1,42%            | 2     | 1,55%            | 1,1203     | 
| 2      | CRUD de Board                                                              | 9         | 9                   | 18    | 3,99%            | 3                        | 2,13%            | 2     | 1,55%            | 1,0851     | 
| 3      | CRUD de Card                                                               | 9         | 9                   | 18    | 3,99%            | 3                        | 2,13%            | 2     | 1,55%            | 1,0851     | 
| 7      | Etiquetar o card                                                           | 6         | 4                   | 10    | 2,22%            | 2                        | 1,42%            | 1     | 0,78%            | 1,0108     | 
| 4      | CRUD da Lista                                                              | 9         | 7                   | 16    | 3,55%            | 3                        | 2,13%            | 2     | 1,55%            | 0,9646     | 
| 28     | Mover Lista                                                                | 9         | 7                   | 16    | 3,55%            | 3                        | 2,13%            | 2     | 1,55%            | 0,9646     | 
| 6      | Compartilhamento de Boards                                                 | 9         | 8                   | 17    | 3,77%            | 3                        | 2,13%            | 3     | 2,33%            | 0,8464     | 
| 20     | Mover Card                                                                 | 9         | 8                   | 17    | 3,77%            | 3                        | 2,13%            | 3     | 2,33%            | 0,8464     | 
| 10     | Criar uma Data de Entrega para uma Card                                    | 9         | 4                   | 13    | 2,88%            | 3                        | 2,13%            | 2     | 1,55%            | 0,7837     | 
| 5      | CRUD de Checklist em Cards                                                 | 9         | 6                   | 15    | 3,33%            | 4                        | 2,84%            | 2     | 1,55%            | 0,7581     | 
| 17     | Adicionar descrição a tarefas                                            | 8         | 7                   | 15    | 3,33%            | 3                        | 2,13%            | 3     | 2,33%            | 0,7469     | 
| 12     | Seguir uma tarefa                                                          | 8         | 4                   | 12    | 2,66%            | 3                        | 2,13%            | 2     | 1,55%            | 0,7234     | 
| 11     | Assinalar uma tarefa a si mesmo ou outros membros do Board                 | 8         | 5                   | 13    | 2,88%            | 3                        | 2,13%            | 3     | 2,33%            | 0,6473     | 
| 16     | Recuperar conta                                                            | 9         | 8                   | 17    | 3,77%            | 4                        | 2,84%            | 4     | 3,10%            | 0,6348     | 
| 14     | CRUD de Comentários                                                       | 7         | 5                   | 12    | 2,66%            | 3                        | 2,13%            | 3     | 2,33%            | 0,5975     | 
| 9      | Notificar prazos                                                           | 9         | 4                   | 13    | 2,88%            | 4                        | 2,84%            | 3     | 2,33%            | 0,5584     | 
| 22     | Arquivar um Card                                                           | 8         | 7                   | 15    | 3,33%            | 3                        | 2,13%            | 5     | 3,88%            | 0,554      | 
| 27     | Copiar Lista                                                               | 4         | 4                   | 8     | 1,77%            | 3                        | 2,13%            | 2     | 1,55%            | 0,4823     | 
| 13     | Notificar seguidores sobre alterações na tarefa                          | 8         | 4                   | 12    | 2,66%            | 4                        | 2,84%            | 4     | 3,10%            | 0,4481     | 
| 21     | Copiar um Card                                                             | 7         | 2                   | 9     | 2,00%            | 3                        | 2,13%            | 3     | 2,33%            | 0,4481     | 
| 24     | Exportar por JSON um Card                                                  | 4         | 6                   | 10    | 2,22%            | 3                        | 2,13%            | 4     | 3,10%            | 0,4241     | 
| 37     | Mencionar um membro de um comentário                                      | 7         | 4                   | 11    | 2,44%            | 5                        | 3,55%            | 3     | 2,33%            | 0,4154     | 
| 32     | Filtrar Cards                                                              | 7         | 5                   | 12    | 2,66%            | 5                        | 3,55%            | 4     | 3,10%            | 0,4003     | 
| 31     | Arquivar uma Lista                                                         | 7         | 5                   | 12    | 2,66%            | 4                        | 2,84%            | 5     | 3,88%            | 0,3964     | 
| 25     | Gerar feed de atividades da board                                          | 7         | 4                   | 11    | 2,44%            | 5                        | 3,55%            | 4     | 3,10%            | 0,3669     | 
| 1      | Integração com outras ferramentas (Power-Ups)                            | 7         | 4                   | 11    | 2,44%            | 2                        | 1,42%            | 7     | 5,43%            | 0,3563     | 
| 29     | Mover todos os Cards de uma Lista                                          | 4         | 3                   | 7     | 1,55%            | 4                        | 2,84%            | 2     | 1,55%            | 0,3538     | 
| 26     | Rastrear alterações no card                                              | 6         | 5                   | 11    | 2,44%            | 5                        | 3,55%            | 5     | 3,88%            | 0,3286     | 
| 36     | Mencionar um Card em um comentário                                        | 5         | 3                   | 8     | 1,77%            | 5                        | 3,55%            | 3     | 2,33%            | 0,3021     | 
| 34     | Seguir um Board                                                            | 6         | 2                   | 8     | 1,77%            | 4                        | 2,84%            | 4     | 3,10%            | 0,2987     | 
| 8      | Convidar pessoas                                                           | 3         | 2                   | 5     | 1,11%            | 2                        | 1,42%            | 3     | 2,33%            | 0,2961     | 
| 18     | Incluir anexos em cards (Computador, Google Drive, Dropbox, Box, OneDrive) | 7         | 3                   | 10    | 2,22%            | 4                        | 2,84%            | 6     | 4,65%            | 0,2961     | 
| 38     | Incluir anexos em comentários                                             | 6         | 3                   | 9     | 2,00%            | 7                        | 4,96%            | 4     | 3,10%            | 0,2474     | 
| 30     | Arquivar todos os Cards de uma Lista                                       | 5         | 4                   | 9     | 2,00%            | 5                        | 3,55%            | 6     | 4,65%            | 0,2434     | 
| 39     | Responder um comentário                                                   | 4         | 2                   | 6     | 1,33%            | 3                        | 2,13%            | 5     | 3,88%            | 0,2216     | 
| 19     | Colocar stickers no card                                                   | 2         | 2                   | 4     | 0,89%            | 3                        | 2,13%            | 3     | 2,33%            | 0,1992     | 
| 40     | Incluir emoji em um comentário                                            | 1         | 1                   | 2     | 0,44%            | 3                        | 2,13%            | 1     | 0,78%            | 0,1528     | 
| 23     | Imprimir um Card                                                           | 2         | 1                   | 3     | 0,67%            | 4                        | 2,84%            | 2     | 1,55%            | 0,1516     | 
| 35     | Copiar um Board                                                            | 1         | 2                   | 3     | 0,67%            | 4                        | 2,84%            | 3     | 2,33%            | 0,1289     | 
