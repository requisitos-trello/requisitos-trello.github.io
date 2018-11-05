# Cenários

## Adicionar Stickers

### Ponto de vista 1 (Lucas Vitor)

A aplicação da técnica possui fluxo bem definido e condizente com a realidade da aplicação, título descritivo, objetivo claro, consegue deixar claro quais são as restrições e contexto do cenário. Possuindo somente a grande falha de não explicitar as exceções presentes no fluxo.

### Ponto de vista 2 (Filipe Toyoshima)

Todos os pontos da metodologia são abordados muito bem, com exceção da parte de exceções, o que é perdoável, visto que apenas exceções gerais, como falta de energia no servidor, são aplicáveis.

### Conclusão

Aqui existe o consenso de que, apesar da falta de exceções no fluxo do cenário, a técnica foi bem aplicada.

## Editar/Remover Stickers

### Ponto de vista 1 (Lucas Vitor)

Possui objetivo claro e título significativo, além de um fluxo relativamente claro e correto, possui um contexto condizente com o da aplicação, porém possui uma pós-condição um pouco ambígua, o que pode dificultar o entendimento do que se espera como produto final da aplicação do fluxo do presente cenário.

### Ponto de vista 2 (Filipe Toyoshima)

O objetivo apenas repete a mesma ideia do título. É possível que explicar os motivos de se tirar um sticker do lugar sejam bem óbvios, mas o formato da documentação pede essa informação. Novamente não há exceções expostas no documento, muito provável que não houvessem.

### Conclusão

No geral, está bom, mas faltam alguns consertos. Basta apenas consertar a ambiguidade da pós-condição e especificar melhor o objetivo.

## Alterar tela de fundo

### Ponto de vista 1 (Lucas Vitor)

O cenário em questão apresenta objetivo não muito claro e não apresenta exceções, mas consegue ter um contexto claro, um fluxo claro e título significativo, o que pode reduzir o ponto negativo de um objetivo ambíguo.

### Ponto de vista 2 (Filipe Toyoshima)

É interessante o objetivo ressaltar a criação da identidade visual. A palavra “tela” pode ser substituída pela palavra “imagem” em todas as vezes em que se refere ao fundo da Board, é mais específico e claro. Não há exceção descrita, o que pode ser uma falha visto que este cenário depende de um serviço externo para utilização de imagens que não estão sob o domínio do Trello.

### Conclusão

Falta um estudo mais aprofundado de exceções. O objetivo levanta um ponto interessante, mas não deixa este ponto claro o suficiente, convém descrever melhor a questão de o usuário ter uma intuição visual frente à imagem de fundo. O resto do documento se mantém claro.

## Filtrar Cartões

### Ponto de vista 1 (Lucas Vitor)

Possui um título, fluxo e objetivos bons, porém o contexto deixa a desejar, principalmente no ponto de pré-condições que é confuso e bastante ambígua. No mais, atende aos padrões exigidos.

### Ponto de vista 2 (Filipe Toyoshima)

Título confuso: “Pesquisa Filtrada de Cards”. Existe uma “Pesquisa não filtrada”? Objetivo raso, poderia discorrer mais sobre as razões de filtrar os cards da Board. Condições bem estabelecidas, até suprem um pouco os problemas anteriores (mas que ainda têm que ser corrigidos!). Os episódios se mostram um pouco complexos demais, mas é compreensível dada a variedade de opções desse cenário.

### Conclusão

Pré-condição é confusa e prolixa, podendo descrever o mesmo contexto de maneira mais simples. O título, embora compreensivo, soa estranho.

## Adicionar Descrição de um Time

### Ponto de vista 1 (Lucas Vitor)

Título condizente com o cenário, porém é um cenário irrelevante para o contexto da elicitação. Objetivo raso, não acrescenta muita coisa ao cenário. Em síntese, o cenário em questão não deveria fazer parte da documentação.

### Ponto de vista 2 (Filipe Toyoshima)

Título não condiz com o que deve ser feito, dá a impressão de que o time já existe e a descrição não. O objetivo diz praticamente a mesma coisa. O objetivo deveria dizer as razões para adicionar uma descrição ao time! Qual seria intenção do usuário com essa função? Esse cenário, na verdade, nem deveria existir. Ele devia ser parte de “Criar um time”.

### Conclusão

Exclua isso e adicione essa parte ao cenário de criação de time.

## Editar Descrição de Time

### Ponto de vista 1 (Lucas Vitor)

Título explicativo, com atores bem definidos e contexto com precondições e pós-condições condizentes com o cenário, porém existe o uso errado de exceções, e o objetivo é raso, não acrescentando muito ao título.

### Ponto de vista 2 (Filipe Toyoshima)

Título bom mas objetivo igual ao título, quando deveria ser mais  específico a respeito das motivações de se editar descrição do time, mesmo que sejam óbvias, o documento existe para especificá-las. Já que time consta como recurso, não precisa ser especificado como restrição.

### Conclusão

No geral, muito bom, apenas alguns erros: uso errado de exceções e objetivo raso. 

## Editar visibilidade do Time

### Ponto de vista 1 (Lucas Vitor)

Objetivo raso, não acrescenta nada ao título, e possui erro na utilização de exceções, porém possui um bom contexto, com pré e poś condições condizentes com o cenário, além de um fluxo claro e condizente com a realidade da aplicação.

### Ponto de vista 2 (Filipe Toyoshima)

É possível ter uma boa compreensão com o título, mas o objetivo apenas repete a ideia, sem acrescentar nada. O mesmo pode ser dito da pós-condição. Existe uma exceção sobre a falta de um recurso anteriormente descrito, o que é redundante. O fluxo, tirando esse último problema descrito, está claro e descreve bem os passos do usuário.

### Conclusão

O objetivo deve ser corrigido a justificar e dar um fim à alteração da visibilidade. A pós-condição, embora condizente, também não adiciona muito. Uso equivocado de exceções. Possui um fluxo bem claro.

## Cenário de Vincular Time ao Slack

### Ponto de vista 1 (Lucas Vitor)

Erro de digitação no título, provavelmente devido ao léxico ao qual está vinculado, objetivo pouco explicativo, o que acaba por não acrescentar muita informação ao título. Porém há um bom uso de fluxos alternativos, um fluxo principal claro e objetivo e um contexto condizente com o esperado.

### Ponto de vista 2 (Filipe Toyoshima)

Na wiki, o header possui erro de digitação: “Cenário de Vincular de Time do Slack”.  Objetivo redundante e pouco descritivo, não fala sobre os benefícios de se vincular ao Slack. A restrição podia ser descrita como um recurso, já que a API do slack vai ser consumida pela do Trello. Certamente existem exceções não descritas, visto que há a interação com um serviço externo.

### Conclusão

Erro no header da wiki. Objetivo pouco descritivo. Uso equivocado de restrição, que deveria ser um recurso. Faltam algumas exceções, e algumas descritas não deviam ser exceções, por já estarem descritas como recursos.