---
layout: default
title: Leitura de documentação da API
category: Elicitação
---

[Lista de Autores do artefato](/artefatos.html)

# Leitura da Documentação da API

Durante a modelagem de requisitos da [Especificação Suplementar](spec_suplementar.html), mais especificamente nas partes de [Desepenho](spec_suplementar.html#desempenho) e [Confiabiliadade](spec_suplementar.html#confiabilidade), notou-se a falta de Requisitos não funcionais relativos a esses pontos.

Pesquisando a respeito do que o Trello disponibilizava publicamente a respeito de como sua infraestrutura funciona, foram encontrados alguns limites que têm como finalidade uma melhor garantia de que a API não será sobrecarregada e de que os espeços de armazenamentos serão superlotados desnecessariamente.

As especificações dos limites encontram-se na Documentação da API, mas seções de [Limite](https://developers.trello.com/docs/limits) e [Limite de Requisições](https://developers.trello.com/docs/rate-limits).

Foram levantados então:

|  **#** | **Nome** |
|  ------ | ------ |
|  1 | Limitar Requisições |
|  2 | Limitar Objetos por Board |

Foi decisão da equipe conter a elicitação de requisitos sobre a API nesse ponto, pois eles se referem muito mais às interações com ferramentas dos desenvolvedores externos do que com o usuário final. Esse fragmento do sistema contituiria um serviço à parte, para o qual seria feito um estudo de requisitos próprio.