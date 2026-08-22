# 05_CASOS_DE_TESTE

Caso 1 — Contrato de locação residencial
- Entrada: elaboração de contrato completo.
- Saída esperada: contrato estruturado; cláusulas obrigatórias; identificação de riscos; linguagem técnica; conformidade com a Lei do Inquilinato.

Caso 2 — Contrato de locação comercial
- Entrada: revisão integral de contrato existente.
- Saída esperada: identificação de inconsistências; sugestões de melhoria; análise das garantias; análise das obrigações.

Caso 3 — Compra e venda de imóvel
- Entrada: minuta de compromisso de compra e venda.
- Saída esperada: revisão técnica; análise de cláusulas; análise de riscos; compatibilidade legal.

Caso 4 — Comparação entre versões
- Entrada: duas versões do mesmo contrato.
- Saída esperada: identificação das diferenças; impactos jurídicos; recomendações.

Caso 5 — Auditoria contratual
- Entrada: contrato pronto para assinatura.
- Saída esperada: checklist de conformidade; riscos; omissões; conflitos entre cláusulas; recomendação de revisão.

Caso 6 — Aditivo contratual
- Entrada: alteração de prazo e valor.
- Saída esperada: elaboração do aditivo; preservação da coerência do contrato original.

Caso 7 — Distrato
- Entrada: encerramento consensual.
- Saída esperada: elaboração do distrato; análise das consequências jurídicas.

Caso 8 — Cláusula isolada
- Entrada: cláusula de multa contratual.
- Saída esperada: análise jurídica; riscos; sugestão de redação.

Caso 9 — Notificação Extrajudicial
- Entrada: solicitação de elaboração de notificação por inadimplemento contratual.
- Saída esperada: linguagem técnica; fundamentação jurídica; preservação dos direitos do notificante; compatibilidade com o contrato.

Caso 10 — Garantia Locatícia
- Entrada: análise da cláusula de fiança, caução ou seguro-fiança.
- Saída esperada: verificação da validade; suficiência da garantia; riscos jurídicos.

Caso 11 — Revisão Final antes da Assinatura
- Entrada: contrato considerado finalizado.
- Saída esperada: checklist final; conferência das cláusulas; conferência dos anexos; recomendação de assinatura ou necessidade de ajustes.

Critérios de aceitação
- O especialista deverá demonstrar capacidade para: elaborar contratos completos; revisar contratos existentes; identificar riscos; identificar omissões; identificar conflitos entre cláusulas; comparar versões; elaborar aditivos; elaborar distratos; analisar garantias; manter coerência sistêmica; preservar uniformidade terminológica; solicitar informações faltantes; indicar necessidade de revisão humana; fundamentar juridicamente suas conclusões; verificar coerência sistêmica do contrato; conferir referências cruzadas; verificar uniformidade terminológica; identificar incompatibilidades documentais.

Auditoria de Conformidade
- Estrutura preservada: manutenção da organização, da sequência, dos títulos e da metodologia institucional da Biblioteca Jurídica Gregório.
- Adequação temática: conteúdo integralmente orientado ao Especialista em Contratos Imobiliários e às demandas de elaboração, revisão, análise e auditoria contratual.
- Padronização institucional: preservação do padrão técnico, formal e jurídico do repositório.
- Coerência técnica: alinhamento do documento às necessidades de contratos de locação, compra e venda, aditivos, distratos, cláusulas isoladas e revisão contratual.
- Cobertura dos cenários operacionais: confirmação de que os principais fluxos de trabalho do especialista estão contemplados pelos casos de teste.
- Status: APROVADO EM TESTE FUNCIONAL COM RESSALVAS.

---

# Relatório de Execução dos Testes

**Data:** 22/08/2026

**Tipo de teste:** simulação funcional com dados fictícios controlados.

**Documentos de controle:** `01_IDENTIDADE.md`, `02_REGRAS.md`, `03_PROMPT.md`, `04_CHECKLISTS.md` e `07_REFERENCIAS.md`.

## Método de avaliação

Cada cenário foi avaliado quanto a: delimitação do escopo, separação entre fatos e pendências, identificação de riscos, fundamentação jurídica, coerência contratual, recomendações práticas e indicação de revisão humana. A aprovação exigiu ausência de afirmação definitiva sem documentos e de orientação incompatível com norma cogente.

## Resultados por grupo de casos

| Casos | Objeto | Resultado | Avaliação |
|---|---|---|---|
| 1 e 2 | Locação residencial e comercial urbana | Aprovado | O fluxo identifica partes, imóvel, prazo, encargos, reajuste, garantias e rescisão, aplicando a Lei nº 8.245/1991 e exigindo conferência documental. |
| 3 | Compra e venda de imóvel | Aprovado | O fluxo verifica titularidade, capacidade, descrição do imóvel, preço, forma, riscos registrais e necessidade de título e registro adequados. |
| 4 e 5 | Comparação e auditoria | Aprovado | O especialista diferencia versões, aponta impactos e aplica checklist sem presumir prevalência de minuta não indicada. |
| 6 e 7 | Aditivo e distrato | Aprovado com ressalva | Preserva o contrato-base e identifica efeitos, valores e quitações; operações de incorporação ou loteamento exigem exame da Lei nº 13.786/2018. |
| 8 e 9 | Multa e notificação | Aprovado | A resposta diferencia multa moratória e compensatória, confronta proporcionalidade e preserva prova do conteúdo e recebimento. |
| 10 | Garantia locatícia | Aprovado | O fluxo impede cumulação indevida de garantias, confere modalidade, extensão, duração e documentação. |
| 11 | Revisão final | Aprovado | O especialista condiciona a assinatura à solução de pendências materiais, registra limitações e exige revisão humana. |

## Teste transversal de segurança

Foi introduzido cenário de locação rural. O pacote reconhece que a Lei nº 8.245/1991 disciplina locações urbanas e que arrendamento e parceria rural dependem do Estatuto da Terra e do Decreto nº 59.566/1966. Essa distinção deve ser mantida como regra obrigatória.

## Resultado consolidado

- **Casos avaliados:** 11 casos originais e 1 teste transversal.
- **Aprovados:** 12.
- **Falhas impeditivas:** nenhuma.
- **Ressalvas:** conferir legislação municipal, matrícula e certidões atuais; pesquisar jurisprudência quando a conclusão depender de controvérsia; validar individualmente contratos de consumo, incorporação, loteamento, alienação fiduciária e imóveis rurais.

**Status funcional:** **APROVADO EM TESTE FUNCIONAL COM RESSALVAS. HOMOLOGAÇÃO PENDENTE DE DECISÃO DO RESPONSÁVEL TÉCNICO.**
