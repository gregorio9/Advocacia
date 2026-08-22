# 05_CASOS_DE_TESTE

## 1. Objetivo

O presente documento tem por objetivo validar o correto funcionamento do especialista jurídico, verificando sua capacidade de interpretar fatos, identificar questões jurídicas, fundamentar respostas, indicar limitações e produzir orientações técnicas compatíveis com a Biblioteca Jurídica Gregório.

Os casos de teste servem para homologar o especialista antes de sua utilização e sempre que ocorrerem alterações relevantes no template ou no respectivo especialista.

---

## 2. Casos de Teste

### Caso 1 — Análise Jurídica

**Entrada**

Resumo de fatos, documento ou situação jurídica envolvendo matéria compatível com a área de atuação do especialista.

**Saída esperada**

- identificação da questão jurídica principal;
- identificação dos fatos relevantes;
- fundamentação jurídica adequada;
- indicação dos riscos identificados;
- orientação prática compatível com os fatos apresentados.

---

### Caso 2 — Pesquisa Jurídica

**Entrada**

Pergunta jurídica objetiva.

**Saída esperada**

- resposta fundamentada;
- indicação dos dispositivos legais aplicáveis;
- utilização de jurisprudência, quando pertinente e verificável;
- indicação das referências utilizadas.

---

### Caso 3 — Informações Insuficientes

**Entrada**

Caso propositalmente incompleto ou com informações insuficientes para formação de conclusão segura.

**Saída esperada**

- identificação das informações insuficientes;
- indicação das pendências relevantes;
- solicitação de esclarecimentos;
- ausência de conclusões baseadas em suposições.

---

## 3. Critérios de Aceitação

O especialista será considerado aprovado quando, sempre que aplicável:

- apresentar resposta clara, objetiva e coerente;
- identificar corretamente as questões jurídicas;
- fundamentar adequadamente suas conclusões;
- utilizar referências compatíveis com `07_REFERENCIAS.md`;
- indicar limitações da análise quando existirem;
- não inventar dispositivos legais, precedentes ou referências;
- apresentar orientações práticas compatíveis com os fatos informados.

---

## 4. Casos Específicos do Especialista

Cada especialista poderá possuir casos adicionais específicos de sua área de atuação, complementando este documento sem alterar sua estrutura geral.

---

## 5. Regra Final

Os casos de teste previstos neste documento constituem o padrão mínimo de validação dos especialistas da Biblioteca Jurídica Gregório.

A aprovação nos testes não dispensa revisão técnica do advogado responsável nem substitui a análise jurídica do caso concreto.
