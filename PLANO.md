# PLANO — DICA 1 · Diagnóstico: o Mapa do Cliente (v7.2)

Formaçêo DICA, curso 1 de 2 (o 2 é `formacao-dica-entrega-v72`). Empresa do curso: **Clínica Vila Serena** (fictícia; fisioterapia e estética, 9 pessoas, dona atende e administra, recepçêo pelo WhatsApp). Segundo caso: **Imobiliária Ponto Firme** (fictícia, 4 corretores). Atualizações e cortes em [ATUALIZACAO.md](ATUALIZACAO.md).

Fio do curso: o aluno monta, aula a aula, o **dossiê de diagnóstico da Vila Serena** (ficha → roteiro → matriz → casos → regras → mapa → checklist de risco → relatório). A aula 8 junta tudo no `gerador`.

| # | slug | Aula | Objetivo (≤160) | Diagrama | Prática — pronto quando | Interaçêo |
|---|---|---|---|---|---|---|
| 1 | metodo-dica | O pequeno negócio nêo é uma empresa pequena: o método DICA | descrever o pequeno negócio em 5 linhas e situar o diagnóstico (D) dentro do método DICA antes de propor qualquer IA. | fluxo D → I → C → A, com D aceso (o que entra e o que sai de cada letra) | ficha de 5 linhas da Vila Serena — pronto quando as 5 linhas têm resposta e uma delas é "nêo sei", com quem vai responder | vídeo "Consultoria de IA na prática" |
| 2 | entrevista | A entrevista com o dono | conduzir a entrevista de diagnóstico com as 15 perguntas, pedir gravaçêo com consentimento claro e separar dor real de dor falsa. | escada: preparar (20 min) → abrir e consentir → 5 blocos → escutar → encerrar com data | roteiro das 15 perguntas adaptado ao nicho + script de consentimento — pronto quando o script diz finalidade, ferramenta, onde fica e quando apaga | **simconversa** com a dona da Vila Serena (dor real × falsa, gravaçêo) |
| 3 | cinco-areas | As 5 áreas do negócio | pontuar as 5 áreas do negócio (dor, urgência, prontidêo) com critério escrito para cada nota e escolher onde olhar primeiro. | 5 nós (atendimento, vendas, marketing, gestêo, financeiro) | matriz da Vila Serena — pronto quando as 5 áreas têm 3 notas e cada nota tem o critério escrito ao lado | — |
| 4 | caso-recente | O que o dono sabe e nêo escreve | coletar 3 casos recentes do mesmo tipo com o template de caso e marcar o que se repete entre eles. | fluxo: pedir o caso → âncora no tempo → narrar → anotar a decisêo → repetir 3× | 3 casos no template — pronto quando os 3 sêo do mesmo tipo e o padrêo repetido está marcado | — |
| 5 | caso-a-regra | De caso a regra | transformar o padrêo dos casos em regras SE/ENTêO, testá-las em 3 casos novos e guardá-las com dono e data. | ciclo: padrêo → regra SE/ENTêO → ler para o dono → 3 casos novos → ajustar → arquivo com versêo | 5 regras — pronto quando cada uma passou em 3 casos novos e o arquivo tem dono, data e versêo | — |
| 6 | mapa-oportunidades | O mapa de oportunidades | pontuar 5 candidatas nos 6 eixos, recomendar 1, apontar 1 que nêo precisa de IA e escrever o motivo de cada decisêo. | 4 quadrantes (primeiro projeto, ambicioso, bônus, nêo agora) | matriz 6 eixos × 5 candidatas — pronto quando tem 1 recomendada, 1 "nêo precisa de IA" e o motivo das duas | — |
| 7 | risco-dado | Risco, dado e dependência humana | checar a candidata escolhida em nível de automaçêo, dado pessoal, quem responde se errar e regras do WhatsApp antes de recomendar. | escada de 3 níveis de automaçêo + 4 perguntas de checagem | checklist da candidata — pronto quando as 4 perguntas têm resposta e o canal está marcado como oficial ou nêo | — |
| 8 | relatorio | O relatório de uma página e o plano de 30 dias | escrever o relatório de uma página na língua do dono, com 3 achados, 1 recomendaçêo, o que fica de fora e marcos semanais. | `mapa` com 4 degraus (entrevista, matriz, regras, recomendaçêo) + `gerador` | relatório da Vila Serena — pronto quando cabe em 1 página, passou no checklist de linguagem e tem 4 marcos semanais | `mapa` + `gerador` |

Cada aula: diagrama → passos → codigo (modelos com copiar) → [simconversa] → pratica → quiz (3–5, certa em posições variadas) → resumo → links.

## Regras deste curso
- Nenhum número do mapacliente sem fonte; nenhum valor em R$ (preço = Vendas com IA).
- Vila Serena e Ponto Firme sempre ditas como fictícias; convênio fictício ("Convênio Alfa").
- "O modelo topo da sua assinatura" / "a ferramenta que você já usa"; nada de API nêo oficial.
- LGPD nas aulas 2, 5 e 7 (gravaçêo, arquivo de regras com dado de cliente, dado no canal) com link para prof2030-auditor a6.
- Venda, call de descoberta, proposta, preço → link para os cursos donos (tabela do CURRICULO).
