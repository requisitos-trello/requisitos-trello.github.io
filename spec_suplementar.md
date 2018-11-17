# Documento de Especificação Suplementar

Este documento tem por finalidade a descrição mais elaborada de requisitos não funcionais encontrados ao longo da elaboração da documentação de análise de requisitos da aplicação Trello.

### Finalidade e Escopo

O objetivo do documento é cobrir os todos os requisitos não funcionais levantados nessa documentação até o dia 17 de Novembro de 2018.

### Visão Geral

Os requisitos estão aqui separados por Funcionalidade, Usabilidade, Desempenho, Portabilidade, Suportabilidade, Restrições de Design, Sistemas de Ajuda.

Embora sejam anexados pelas categorias descritas acima, mantém-se as indexações padronizadas pela wiki, tornando mais fácil a visualização dele ao longo da documentação.

### Referências

Foram usados para a elaboração dos requisitos aqui descritos:

- os [NFRs](nfr.html) levantados durante a fase de modelagem;
- [Guia de uso](https://trello.com/guide?utm_source=trello&utm_medium=inapp&utm_content=header-tips&utm_campaign=guide) do Trello;
- [Documentação de Segurança](http://trello.com/legal/security) do Trello;
- [Guia para Desenvolvedores](https://developers.trello.com/) que queiram integrar aplicações com o Trello

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

## Desempenho

### RQ60 - Distribuição de Servidores

Para garantir que os dados dos usuários estejam sempre acessíveis e que eles não serão perdidos em caso de algum problema grave com servidores do Trello, é necessário configurar uma rede de servidores que sejam capazes de replicar dados entre si, aumentando a disponibilidade e confiabilidade daqueles dados.

### RQ61 - Velocidade de Resposta

O sistema deve ser capaz de receber, pelo menos, 200 requisições por segundo e ainda ser capaz de receber e enviar as informações necessárias dentro do período percebido pelo usuário de 0.5 segundos.

---