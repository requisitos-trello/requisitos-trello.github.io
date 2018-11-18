# Backward From

## Técnica de elicitação

| **Sigla** | **Técnica de elicitação** |
|  :------: | :------: |
| LD | Leitura de Documentação |
| BS | Brainstorm |
| IP | Introspecção |
| PT | Protótipo |
| EN | Entrevista |
| QT | Questionário |

## Modelagem

| **Sigla** | **Modelagem** |
|  :------: | :------: |
| CN | Cenário |
| RP | Rich Picture |
| LX | Léxico |
| UC | Caso de uso |
| ES | Especificação Suplementar |

## Tabela

|  **ID** | **Tema** | **Nome** | **Documento Fonte** | **Técnica de elicitação** | **Modelagem** |
|  :------: | :------: | :------: | :------: | :------: | :------: |
|  RQ01 | Aplicativo | Compatibilidade com atalhos de teclado | US1 | [LD](leituradocumentacao.html) | [NFR](nfr.html#acessibilidade) |
|  RQ02 | Card | CRUD de cartões | US2 |  [BS](brainstorming.html), [IP](instrospeccao.html#gertrude), [PT](prototipo.html), [LD](leituradocumentacao.html) | [RP](rich pictures.html), [UC13](casos de uso.html#uc13), [UC22](casos de uso.html#uc22), [CN25](cenarios.html#cn25), [CN26](cenarios.html#cn26), [LX03](lexicos.html#lx03) |
|  RQ03 | Card | Suporte à deadlines nos cartões | US3 |  [LD](leituradocumentacao.html), [IP](instrospeccao.html#casamento) | [RP](rich-pictures.html), [UC29](casos de uso.html#uc29), [LX13](lexicos.html#lx13) |
|  RQ04 | Card | Criação de descrição nos cartões | US4 | [LD](leituradocumentacao.html), [IP](instrospeccao.html) | [UC26](casos de uso.html#uc26), [LX03](lexicos.html#lx03) |
|  RQ05 | Card | Criação de checklists nos cartões | US5 | [PT](prototipo.html), [LD](leituradocumentacao.html), [IP](instrospeccao.html#casamento) | [UC27](casos de uso.html#uc27), [LX23](lexicos.html#lx23-check-list), [iStar04](istar.html#sd04---card) |
|  RQ06 | Card | Armazenamentos de anexos nos cartões | US6 | [EN](entrevista.html), [LD](leituradocumentacao.html) | [UC32](casos de uso.html#uc32), [LX10](lexicos.html#lx10-anexo) |
|  RQ07 | Card | Comentários nos cartões | US7 | [LD](leituradocumentacao.html), [BS](brainstorming.html) | [UC30](casos de uso.html#uc30), [CN53](cenarios.html#cn53), [LX03](lexicos.html#lx03-card), [iStar04](istar.html#sd04---card) |
|  RQ08 | Card | Criação de cartões em massa | US8 | [LD](leituradocumentacao.html) | [LX03](lexicos.html#lx03-card) |
|  RQ09 | Card | Mencionar usuários em comentários | US9 | [LD](leituradocumentacao.html), [BS](brainstorming.html) | [LX03](lexicos.html#lx03-card), [LX16](lexicos.html#lx16-usuário) |
|  RQ10 | Card | Delegar cards a usuários | US1 | [LD](leituradocumentacao.html), [IP](instrospeccao.html#natal) | [LX06](lexicos.html#lx06) |
|  RQ11 | Card | Notificar prazos de entrega próximos a usuários assinalados | US11 | [Questionário](questionário.html), [EN](entrevista.html), [LD](leituradocumentacao.html), [BS](brainstorming.html), [IP](instrospeccao.html#natal) | [NFR](nfr.html#usabilidade-mobile), [UC04](casos de uso.html#uc04), [LX11](lexicos.html#lx11-notificar) |
|  RQ12 | Card | Marcar data de entrega como concluída | US12 | [LD](leituradocumentacao.html), [BS](brainstorming.html) | [UC15](casos de uso.html#uc15), [LX13](lexicos.html#lx13-duedate) |
|  RQ13 | Card | Compatibilidade com markdown nas descrições dos cards | US13 | [LD](leituradocumentacao.html) | [LX03](lexicos.html#lx03-card) |
|  RQ14 | Card | Adição de etiquetas aos cards | US14 | [LD](leituradocumentacao.html) | [UC28](casos de uso.html#uc28), [LX26](lexicos.html#lx26-label) |
|  RQ15 | Card | Pesquisar cartões | US15 | [LD](leituradocumentacao.html) | [NFR](nfr.html#usabilidade), [UC25](casos de uso.html#uc25), [LX03](lexicos.html#lx03-card), [iStar05](istar.html#sd05---filtrar-card) |
|  RQ16 | Card | Anexar cartões a outros cartões | US16 | [LD](leituradocumentacao.html) | [CN31](cenarios.html#cn31), [LX03](lexicos.html#lx03-card), [LX10](lexicos.html#lx10-anexo), [iStar04](istar.html#sd04---card) |
|  RQ17 | Card | Anexar quadros a cartões | US17 | [PT](prototipo.html), [LD](leituradocumentacao.html) | [CN31](cenarios.html#cn31), [LX03](lexicos.html#lx03-card), [LX10](lexicos.html#lx10-anexo), [iStar04](istar.html#sd04---card) |
|  RQ18 | Card | Seguir um cartão | US18 | [LD](leituradocumentacao.html), [BS](brainstorming.html) | [CN28](cenarios.html#cn28), [LX03](lexicos.html#lx03-card), [LX21](lexicos.html#lx21-seguir), [iStar04](istar.html#sd04---card) |
|  RQ19 | Card | Criar card através de e-mails | US19 | [LX](lexicos.html#lx03-card) | [LX03](lexicos.html#lx03-card) |
|  RQ20 | Conta | Login | US20 | - | [UC01](casos de uso.html#uc01), [CN01](cenarios.html#cn01), [LX17](lexicos.html#lx17-login) |
|  RQ21 | Conta | Login com o Google | US21 | - | [NFR](nfr.html#privacidade), [UC01](casos de uso.html#uc01), [CN02](cenarios.html#cn02), [LX17](lexicos.html#lx17-login) |
|  RQ22 | Conta | Cadastrar | US22 | [BS](brainstorming.html)| [UC02](casos de uso.html#uc02), [CN03](cenarios.html#cn03) |
|  RQ23 | Conta | Cadastrar com o Google | US23 | - | [UC02](casos de uso.html#uc02), [CN03](cenarios.html#cn03) |
|  RQ24 | Conta | Alterar senha | US24 | - | [UC03](casos de uso.html#uc03), [CN04](cenarios.html#cn04) |
|  RQ25 | Lista | CRUD de listas | US25 | [BS](brainstorming.html), [LD](leituradocumentacao.html), [IP](instrospeccao.html#gertrude) | [UC11](casos de uso.html#uc11), [CN40](cenarios.html#cn40), [LX02](lexicos.html#lx02-lista) |
|  RQ26 | Lista | Seguir uma lista | US26 | [LD](leituradocumentacao.html), [IP](instrospeccao.html#judiscleidson) | [LX02](lexicos.html#lx02-lista), [LX21](lexicos.html#lx21-seguir) |
|  RQ27 | Quadro | CRUD de Quadros | US27 |  [BS](brainstorming.html), [PT](prototipo.html), [LD](leituradocumentacao.html), [IP](instrospeccao.html#gertrude) | [RP](rich-pictures.html), [UC09](casos de uso.html#uc09), [CN44](cenarios.html#cn44), [LX01](lexicos.html#lx01-board), [iStar02](istar.html#sd02---board) |
|  RQ28 | Quadro | Convite para membros do quadro | US28 | [BS](brainstorming.html), [LD](leituradocumentacao.html) | [UC08](casos de uso.html#uc08), [UC09](casos de uso.html#uc09), [LX01](lexicos.html#lx01-board) |
|  RQ29 | Quadro | Gestão de visibilidade do quadro | US29 | [LD](leituradocumentacao.html) | [UC07](casos de uso.html#uc07), [LX01](lexicos.html#lx01-board), [iStar02](istar.html#sd02---board) |
|  RQ30 | Quadro | Adição de times à quadros | US30 | [LD](leituradocumentacao.html) | [LX01](lexicos.html#lx01-board), [LX11](lexicos.html#lx11-time) |
|  RQ31 | Quadro | Adicionar membro a quadro | US31 | [LD](leituradocumentacao.html) | [UC04](casos de uso.html#uc04),[LX01](lexicos.html#lx01-board), [LX19](lexicos.html#lx19-membro) |
|  RQ32 | Quadro | Alterar plano de fundo | US32 |  [LD](leituradocumentacao.html) | [RP](rich-pictures.html), [UC09](casos de uso.html#uc09), [CN44](cenarios.html#cn44) |
|  RQ33 | Quadro | Oferecer biblioteca de imagens para plano de fundo | US33 | [LD](leituradocumentacao.html) | [UC09](casos de uso.html#uc09) |
|  RQ34 | Quadro | Interações com ferramentas externas | US34 | [BS](brainstorming.html), [QT](questionário.html), [EN](entrevista.html), [LD](leituradocumentacao.html) | [LX16](lexicos.html#lx16-usuário) |
|  RQ35 | Quadro | Copiar quadro | US35 | [LD](leituradocumentacao.html), [BS](brainstorming.html) | [CN14](cenarios.html#cn14), [LX01](lexicos.html#lx01-board), [LX15](lexicos.html#lx15-copiar) |
|  RQ36 | Quadro | Seguir um quadro | US36 | [LD](leituradocumentacao.html), [BS](brainstorming.html) | [UC11](casos de uso.html#uc11), [CN15](cenarios.html#cn15), [LX01](lexicos.html#lx01-board), [LX21](lexicos.html#lx21-seguir), [iStar02](istar.html#sd02---board) |
|  RQ37 | Quadro | Favoritar quadros | US37 | [LD](leituradocumentacao.html) | [LX01](lexicos.html#lx01-board) |
|  RQ38 | Time | CRUD de times | US38 | [LD](leituradocumentacao.html) | [RP](rich-pictures.html), [UC05](casos de uso.html#uc05), [LX11](lexicos.html#lx11-time), [iStar01](istar.html#sd01---time) |
|  RQ39 | Time | Visualizar membros de um time | US39 |  [LD](leituradocumentacao.html) | [RP](rich-pictures.html), [UC07](casos de uso.html#uc07), [LX11](lexicos.html#lx11-time), [LX19](lexicos.html#lx19-membro), [iStar01](istar.html#sd01---time) |
|  RQ40 | Time | Editar visibilidade do time | US40 | [LD](leituradocumentacao.html) | [UC07](casos de uso.html#uc07), [CN20](cenarios.html#cn20), [LX11](lexicos.html#lx11-time), [iStar01](istar.html#sd01---time) |
|  RQ41 | Time | Gerenciar administradores do time | US41 | [LD](leituradocumentacao.html) | [RP](rich-pictures.html), [LX11](lexicos.html#lx11-time), [LX04](lexicos.html#lx04-administrador), [iStar01](istar.html#sd01---time) |
|  RQ42 | Time | Detalhar time | US42 | [LD](leituradocumentacao.html) | [RP](rich-pictures.html), [UC07](casos de uso.html#uc07), [CN19](cenarios.html#cn19), [LX11](lexicos.html#lx11-time), [iStar01](istar.html#sd01---time) |
|  RQ43 | Time | Gerenciar membros de um time | US43 | [IP](instrospeccao.html#natal), [LD](leituradocumentacao.html) | [RP](rich-pictures.html), [UC07](casos de uso.html#uc07), [LX11](lexicos.html#lx11-time), [LX19](lexicos.html#lx19-membro), [iStar01](istar.html#sd01---time) |
| RQ44 | Acessibilidade  | Descrição de imagens no HTML                 | US44 | - | [NFR](nfr.html#acessibilidade) |
| RQ45 | Acessibilidade  | Modo daltônico                               | US45 | - | [NFR](nfr.html#acessibilidade) |
| RQ46 | Acessibilidade  | Alto contraste entre texto e fundo           | US46 | - | [NFR](nfr.html#acessibilidade) |
| RQ47 | Privacidade     | Elaboração da Política de Privacidade        | US47 | - | [NFR](nfr.html#privacidade) |
| RQ48 | Usabilidade     | Manter sessão                                | US48 | - | [NFR](nfr.html#usabilidade) |
| RQ49 | Usabilidade     | Responsividade de acordo com tamanho de tela | US49 | - | [NFR](nfr.html#usabilidade) |
| RQ50 | Usabilidade     | Detecção de Idioma                           | US50 | - | [NFR](nfr.html#usabilidade) |
| RQ51 | Usabilidade     | Botão Home                                   | US51 | - | [NFR](nfr.html#usabilidade) |
| RQ52 | Usabilidade     | Pesquisa de Qualquer Coisa                   | US52 | - | [NFR](nfr.html#usabilidade) |
| RQ53 | Usabilidade     | Aba de notificações                          | US53 | - | [NFR](nfr.html#usabilidade) |
| RQ54 | Usabilidade     | Documentação de Ajuda                        | US54 | - | [NFR](nfr.html#usabilidade) |
| RQ55 | Segurança       | Certificação Akamai                          | US55 | - | [NFR](nfr.html#segurança) |
| RQ56 | Segurança       | Servidores Secundários AWS                   | US56 | - | [NFR](nfr.html#segurança) |
| RQ57 | Segurança       | Encriptação in-Transit                       | US57 | - | [NFR](nfr.html#segurança) |
| RQ58 | Segurança       | Encriptação at-Rest                          | US58 | - | [NFR](nfr.html#segurança) |
| RQ59 | Desemepenho     | Limitar requisições                          | US59 | [LD](leituradocumentacao.html) (Rate Limits) | [ES](spec_suplementar.html#desempenho)      |
| RQ60 | Desemepenho     | Limitar cards por lista                      | US60 | [LD](leituradocumentacao.html) (Limits)      | [ES](spec_suplementar.html#desempenho)      |
| RQ61 | Desemepenho     | Limitar cards por board                      | US61 | [LD](leituradocumentacao.html) (Limits)      | [ES](spec_suplementar.html#desempenho)      |                                            
| RQ62 | Suportabilidade | Compatibilidade com Navegadores mais Comuns  | US62 | Pesquisa de Mercado                   | [ES](spec_suplementar.html#suportabilidade) |
