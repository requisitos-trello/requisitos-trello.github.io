---
layout: default
title: Especificação Suplementar
category: Modelagem
---

# Documento de Especificação Suplementar

Este documento tem por finalidade a descrição mais elaborada de requisitos não funcionais encontrados ao longo da elaboração da documentação de análise de requisitos da aplicação Trello.

### Finalidade e Escopo

O objetivo do documento é cobrir os todos os requisitos não funcionais levantados nessa documentação até o dia 17 de Novembro de 2018.

### Visão Geral

Os requisitos estão aqui separados por Funcionalidade, Usabilidade, Confiabilidade, Desempenho, Suportabilidade, Restrições de Design, Sistemas de Ajuda.

Embora sejam anexados pelas categorias descritas acima, mantém-se as indexações padronizadas pela wiki, tornando mais fácil a visualização dele ao longo da documentação.

### Referências

Todas as referências de conteúdo estão linkadas ao longo do documento.

A formatação deste documento foi baseada no [template](http://www.funpar.ufpr.br:8080/rup/webtmpl/templates/req/rup_sspec.htm#2.%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20Functionality) da Fundação da Universidade Federal do Paraná. Algumas alterações foram feitas para melhor adequação à realidade na qual as especificações aqui descritas se enquadram.

---

## Funcionalidades

Acredita-se que todos os requisitos funcionais estão suficientemente modelados através de histórias de usuário descritas no [Backlog do Produto](!!!!!PENDENCIA!!!!!).

---

## Usabilide

Através do [NFR de Usabilidade](nfr.html#usabilidade) foi possível modelar alguns dos requisitos que o sistema teria de atender para que esse importante critério pudesse ser considerado atendido pela equipe.

Aqui serão descritas as operacionalizações identificadas no NFR, pois esse é o nível do diagrama que reflete a implementação pelos desenvolvedores do sistema.

### RQ49 - Responsividade com Tamanho de Tela

Para atender de maneira dinâmica a variedade de tamanhos de tela que se encontram hoje no mercado, é necessário que a estrutura CSS das telas seja construída de maneira a responder uniformemente a cada configuração dimensional.

### RQ50 - Detecção de Idioma

Visando ser uma plataforma mudialmente utilizada, o Trello dispõe de vários idiomas. Entretanto, o usuário que abrir o sistema pela primeira vez pode não ser familiarizado com o idioma nativo da aplicação, o que talvez até o impossibilite de encontrar a opção de trocar o idioma do sistema para um com o qual se sinta confortável. Para evitar esse problema, é necessário que o Trello seja capaz de identificar o idioma local do usuário, configurando o sistema para este idioma automaticamente, caso ele esteja disponível.

---

## Confiabilidade

### RQ60 - Limitar Requisições

Para garantir que o sistema não será sobrecarregado pelas aplicações externas, a API deve impor um limite de requisições por chave da API e por token.

- Limite de 300 requisições a cada 10 segundos por chave de API
- Limite de 100 requisições a cada 10 segundos por token

Esses limites podem ser encontrados na [Documentação da API](https://developers.trello.com/docs/rate-limits).

### RQ61 - Limitar Objetos por Board

Como medida de segurança para evitar que aplicações externas consumam armazenamento demasiado dos sistemas do Trello, exite uma série de limitações sobre quantos objetos podem estar relacionados a um board. É necessário enviar uma requisição de aviso para que as aplicações possam ser preparadas para a ocasião de lotação do limite.

|  Objeto | Limite | Warning |
|  ------: | :------: | :------: |
|  Membros | 1520 | 1440 |
|  Cards Abertos | 4750 | 4500 |
|  Cards (incluindo arquivados) | 1900000 | 1800000 |
|  Checklists | 15200 | 14400 |
|  Labels | 950 | 900 |
|  Listas | 475 | 450 |
|  Listas (incluindo arquivadas) | 2850 | 2700 |

Esses limites podem ser encontrados na [Documentação da API](https://developers.trello.com/docs/limits).

### RQ62 - Capacidade de Usuários

Em 2017, [o Trello atingiu 25 milhões de usuários](https://blog.trello.com/25-million-users). Ainda deve-se levar em consideração que, além dos usuários, o sistema também é utilizado por inúmeros robôs que automatizam cargas de trabalho repetitivas, podendo cada um deles gerar até 10 requisições por segundo, em média. O sistema deve ser apto a manter essa carga de trabalho fluindo ininterruptamente.

---

## Desempenho

### Tem nada ainda

---

## Suportabilidade

### RQ63 - Compatibilidade com navegadores mais comuns

Como a aplicação será executada em um navegador web, é necessário que testes sejam realizados nos navegadores mais comuns no mercado. Segundo [pesquisa](http://gs.statcounter.com/browser-market-share/desktop/worldwide) realisada pela gs.statcounter.com, segue lista dos navegadores mais utilizados em desktop:

| Navegador | Taxa de Uso |
|  -----: | :------ |
|  Chrome | 69.56% |
| Firefox | 10.17% |
| Internet Explorer | 6.02% |
|  Safari | 5.63% |
|    Edge | 4.22% |

Para que se garanta compatibilidade com pelo menos 95% do público, deve-se haver garantia de que a aplicação funcionará sem problemas pelo menos nesses 5 navegadores.