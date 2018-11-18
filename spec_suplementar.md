---
layout: default
title: Especificação Suplementar
category: Modelagem
---

Autor: Filipe Toyoshima

# Documento de Especificação Suplementar

Este documento tem por finalidade a descrição mais elaborada de requisitos não funcionais encontrados ao longo da elaboração da documentação de análise de requisitos da aplicação Trello.

### Finalidade e Escopo

O objetivo do documento é cobrir os todos os requisitos não funcionais levantados nessa documentação até o dia 17 de Novembro de 2018.

### Visão Geral

Os requisitos estão aqui separados por Funcionalidade, Usabilidade, Confiabilidade, Desempenho, Suportabilidade, Sistemas de Ajuda, Segurança.

Embora sejam anexados pelas categorias descritas acima, mantém-se as indexações padronizadas pela wiki, tornando mais fácil a visualização dele ao longo da documentação.

### Referências

Todas as referências de conteúdo estão linkadas ao longo do documento.

A formatação deste documento foi baseada no [template](http://www.funpar.ufpr.br:8080/rup/webtmpl/templates/req/rup_sspec.htm#2.%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20Functionality) da Fundação da Universidade Federal do Paraná. Algumas alterações foram feitas para melhor adequação à realidade na qual as especificações aqui descritas se enquadram.

---

## Funcionalidades

Acredita-se que todos os requisitos funcionais estão suficientemente modelados através de histórias de usuário descritas no [Backlog do Produto](product%20backlog.html).

---

## Usabilidade

Através do [NFR de Usabilidade](nfr.html#usabilidade) foi possível modelar alguns dos requisitos que o sistema teria de atender para que esse importante critério pudesse ser considerado atendido pela equipe.

Aqui serão descritas as operacionalizações identificadas no NFR, pois esse é o nível do diagrama que reflete a implementação pelos desenvolvedores do sistema.

### RQ49 - Responsividade com Tamanho de Tela

Para atender de maneira dinâmica a variedade de tamanhos de tela que se encontram hoje no mercado, é necessário que a estrutura CSS das telas seja construída de maneira a responder uniformemente a cada configuração dimensional.

### RQ50 - Detecção de Idioma

Visando ser uma plataforma mudialmente utilizada, o Trello dispõe de vários idiomas. Entretanto, o usuário que abrir o sistema pela primeira vez pode não ser familiarizado com o idioma nativo da aplicação, o que talvez até o impossibilite de encontrar a opção de trocar o idioma do sistema para um com o qual se sinta confortável. Para evitar esse problema, é necessário que o Trello seja capaz de identificar o idioma local do usuário, configurando o sistema para este idioma automaticamente, caso ele esteja disponível.

### RQ65 - Informar possíveis Interações

Baseando-se nas [Heurísticas de Nielsen](https://www.nngroup.com/articles/ten-usability-heuristics/), pensou-se em passar feedback ao usuário através de animações na interface. Ou seja, toda vez que o usuário passa o cursor por um elemento com o qual possa interagir, esse elemento deve reagir de alguma forma, de modo a dar a entender que o usuário pode realizar alguma ação.

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

---

## Desempenho

### RQ62 - Capacidade de Usuários

Em 2017, [o Trello atingiu 25 milhões de usuários](https://blog.trello.com/25-million-users). Ainda deve-se levar em consideração que, além dos usuários, o sistema também é utilizado por inúmeros robôs que automatizam cargas de trabalho repetitivas, podendo cada um deles gerar até 10 requisições por segundo, em média. O sistema deve ser apto a manter essa carga de trabalho fluindo ininterruptamente.

---

## Suportabilidade

### RQ63 - Compatibilidade com navegadores mais comuns

Como a aplicação será executada em um navegador web, é necessário que testes sejam realizados nos navegadores mais comuns no mercado. Segundo [pesquisa](http://gs.statcounter.com/browser-market-share/desktop/worldwide) realizada pela gs.statcounter.com, segue lista dos navegadores mais utilizados em desktop:

| Navegador | Taxa de Uso |
|  -----: | :------ |
|  Chrome | 69.56% |
| Firefox | 10.17% |
| Internet Explorer | 6.02% |
|  Safari | 5.63% |
|    Edge | 4.22% |

Para que se garanta compatibilidade com pelo menos 95% do público, deve-se haver garantia de que a aplicação funcionará sem problemas pelo menos nesses 5 navegadores.

---

## Sistemas de Ajuda

### RQ54 - Documentação de Ajuda

Embora tenha aparecido no [NFR de Usabilidade](nfr.html#usabilidade), este é um requisito que faz mais sentido nesse tópico. A documentação de ajuda deve seguir como um tutorial passo a passo que cubra, pelo menos, as seguintes funcionalidades:

- Criar board
- Adicionar Listas
- Adicionar Cards
    - Adicionar descrição aos Cards
    - Comentar nos cards
    - Adicionar membros aos cards
- Convidar Membros
- Gestão de Visibilidade
- Alterar plano de fundo da board

Esses tutoriais devem seguir em texto, com prints ilustrativos, demonstrando onde fica cada botão, E com vídeo que demontre, de maneira explicativa, o uso de cada um dos pontos destacados.

### RQ64 - Exibição de Dicas Rápidas

A leitura de documentação pode ser um meio até evitado pelos usuários por terem uma carga muito massante de informação. Uma maneira mais adequada e rápida de passar, mesmo que pouco a pouco, o potencial da aplicação é o de Dicas Rápidas. Esse botão mostrará alguma funcionalidade útil, porém pouco aparente, da ferramente. Pode exibir também alguma documentação interessante que não está necessariamente presente no tutorial descrito anteriormente, mas que ainda agrega conhecimento sobre a aplicação para o usuário.

---

## Segurança

Todos os detalhes sobre a segurança e proteção de dados do Trello podem ser encontrados na [documentação de segurança](https://trello.com/legal/security), a partir da qual foram levantados os requisitos deste tópico, que também foram modelados no [NFR de Segurança](nfr.html#segurança).

### RQ55 - Segurança Akamai

O sistema deve usar Akamai para proteção DDoS e aplicação web de firewall. Acredita-se que, para usuários gerais, isto é, os que não são Business Class e portanto não pagam por proteção adicional, a segurança Akamai já será suficiente para manter os dados seguros.

### RQ56 - Replicação de Serviço Crítico

Todo e qualquer serviço considerado crítico dentro do Trello deve manter um um serviço secundário replicado rodando simultaneamente com dados espelhados em uma zona de disponibilidade diferente do serviço de nuvem contratado.

### RQ57 - Encriptação in-Transit

O sistema deve usar a Transport Layer Security (TLS) padrão para criar uma conexão segura, utilizando AES (Advanced Encryptation Standard) de 128 bits. Esse protocolo de segurança deve ser usado para toda e qualquer informação que circule na rede do Trello, seja web, iOS ou Android. Todas as conexões devem ser feitas de maneira segura com HTTPS.

### RQ58 - Encriptação at-Rest

Para os usuários Enterprise Class, deve também ser utilizada a encriptação at-Rest, no mesmo modelo de AES, porém de 256bit. Essa criptografia será aplicada aos arquivos anexados aos cards para os usuários que tiverem direito a essa camada adicional de proteção.

---