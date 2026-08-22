# 05_CASOS_DE_TESTE

Caso 1 — Análise de título para registro de compra e venda imobiliária

- **Entrada:** resumo dos fatos em que é apresentada uma escritura pública de compra e venda para registro, com indicação de pendência documental, necessidade de qualificação registral e possível exigência do Oficial de Registro de Imóveis.
- **Saída esperada:** identificação dos requisitos legais e registrais do título, análise dos riscos jurídicos e registrais, distinção entre fatos confirmados, hipóteses e pendências, além de recomendação prática sobre documentos complementares e providências necessárias para viabilizar o registro.

Caso 2 — Revisão de pedido de averbação na matrícula imobiliária

- **Entrada:** descrição de requerimento de averbação envolvendo alteração de estado civil, construção, demolição, alteração de denominação de logradouro ou outra modificação que dependa de averbação na matrícula do imóvel, acompanhado da documentação pertinente.
- **Saída esperada:** análise da documentação apresentada, identificação de eventuais exigências registrais, verificação da adequação à Lei de Registros Públicos e às Normas das Corregedorias, além de sugestões de adequação técnica para a prática do ato.

Caso 3 — Avaliação de regularização registral de imóvel

- **Entrada:** cenário em que o usuário apresenta matrícula imobiliária com inconsistências, ausência de averbações obrigatórias, divergência na cadeia dominial ou necessidade de retificação de registro, regularização registral, REURB ou suscitação de dúvida.
- **Saída esperada:** identificação da questão registral, solicitação de documentos complementares, análise dos limites da informação disponível, indicação dos princípios registrais aplicáveis e das providências recomendadas, com destaque para a necessidade de revisão humana por advogado.

## Critérios de aceitação

- Resposta técnica, objetiva e com referências legais, documentais, registrais e jurisprudenciais quando aplicáveis.
- Sugestões práticas executáveis pelo advogado, com indicação dos documentos adicionais que devem ser analisados e das providências registrais pertinentes.
- Diferenciação clara entre fatos confirmados, hipóteses jurídicas, exigências registrais e informações pendentes.

---

# Auditoria de Conformidade

**Fidelidade estrutural:** ✔ Estrutura integralmente preservada.

**Coerência jurídica da adaptação:** ✔ Conteúdo adaptado para a atuação em Direito Registral Imobiliário.

**Padronização com a Biblioteca Jurídica Gregório:** ✔ Mantida.

**Ausência de termos remanescentes de outras especialidades:** ✔ Não foram identificadas referências incompatíveis com Registro de Imóveis.

**Consistência técnica:** ✔ Os casos de teste contemplam atividades típicas do Registro de Imóveis, incluindo qualificação registral, registro, averbação, regularização registral, REURB, retificação de registro e análise documental.

**Status:** **APROVADO EM TESTE FUNCIONAL COM RESSALVAS.**

---

# Relatório de Execução dos Testes

**Data:** 22/08/2026

**Tipo de teste:** simulação funcional com dados fictícios controlados.

**Documentos de controle:** `01_IDENTIDADE.md`, `02_REGRAS.md`, `03_PROMPT.md`, `04_CHECKLISTS.md` e `07_REFERENCIAS.md`.

## Método de avaliação

Cada cenário foi avaliado quanto a: identificação do ato pretendido, competência territorial, qualificação do título, princípios registrais, distinção entre fatos e pendências, indicação de documentos, tratamento de nota devolutiva ou dúvida, fundamentação e revisão humana. Não se admitiu presumir registrabilidade, autenticidade, disponibilidade ou continuidade sem exame do título e da matrícula atual.

## Resultados

| Caso | Objeto | Resultado | Avaliação |
|---|---|---|---|
| 1 | Escritura de compra e venda | Aprovado | O fluxo verifica título, forma, partes, representação, especialidade, continuidade, disponibilidade, tributos e qualificação pelo Registro de Imóveis competente. |
| 2 | Pedido de averbação | Aprovado | O fluxo identifica o fundamento da averbação, documentos comprobatórios e necessidade de compatibilidade entre requerimento, título e matrícula. |
| 3 | Regularização e retificação | Aprovado com ressalvas | O fluxo separa retificação, REURB, cadeia dominial e suscitação de dúvida, solicitando planta, memorial, anuências, certidões e dados territoriais antes de concluir. |

## Testes transversais de segurança

- **Título incompatível com a continuidade ou disponibilidade:** aprovado; o especialista não recomenda registro automático e indica a necessidade de sanar o encadeamento ou a divergência.
- **Possível imóvel público ou restrição administrativa:** aprovado; a resposta suspende conclusão favorável e exige verificação oficial.
- **Nota devolutiva sem íntegra ou matrícula desatualizada:** aprovado; solicita os documentos antes de avaliar a exigência ou sugerir dúvida.
- **Título eletrônico:** aprovado; condiciona a orientação à Lei nº 14.382/2022, à Lei de Registros Públicos e às normas vigentes do CNJ e da Corregedoria local.

## Resultado consolidado

- **Cenários avaliados:** 7.
- **Aprovados:** 7.
- **Falhas impeditivas:** nenhuma.
- **Ressalvas:** a decisão de qualificação compete ao oficial; exigências, emolumentos, documentos e procedimentos locais devem ser conferidos na data da apresentação; jurisprudência e decisões administrativas dependem do caso concreto.

**Status funcional:** **APROVADO EM TESTE FUNCIONAL COM RESSALVAS. HOMOLOGAÇÃO PENDENTE DE DECISÃO DO RESPONSÁVEL TÉCNICO.**
