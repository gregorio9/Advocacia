# Template de Especialista Jurídico

Objetivo e Finalidade
- Finalidade: Repositório padronizado para elaboração, revisão, análise e validação de documentos jurídicos (contratos, peças processuais), pesquisas e fluxos de trabalho do Escritório José Luiz Gregório, assegurando governança, rastreabilidade e reutilização de conhecimento.
- Objetivo do template: Fornecer um esqueleto reutilizável e versionado para criar novos especialistas que padronizem entregáveis, reduzam riscos e acelerem a adoção em automações e práticas do escritório.

Regra obrigatória
- Todo novo especialista deverá obrigatoriamente ser criado a partir deste template.

Estrutura de arquivos e função de cada um
- `01_IDENTIDADE.md`: perfil do especialista — nome, áreas, qualificações, tom e jurisdição.
- `02_REGRAS.md`: guardrails e limites operacionais — confidencialidade, escopo, formato de resposta e proibições.
- `03_PROMPT.md`: prompt base parametrizável e variações de uso.
- `04_CHECKLISTS.md`: checklists práticos para revisão antes da entrega.
- `05_CASOS_DE_TESTE.md`: casos de teste com entradas, saídas esperadas e critérios de aceitação.
- `06_HISTORICO.md`: changelog com data, autor e descrição das alterações.
- `07_REFERENCIAS.md`: fontes legislativas, jurisprudenciais e doutrinárias recomendadas.
- `README.md` (este): instruções de uso, fluxo e padrões aplicáveis.

Fluxo obrigatório de trabalho
- Planejamento: definir escopo, público, jurisdição e versão; preencher `01_IDENTIDADE.md`.
- Apresentação do plano: documentar e apresentar o plano de criação/ajuste do especialista para stakeholders relevantes.
- Aprovação: obter aprovação explícita (issue, PR aprovada ou autorização por escrito) antes de prosseguir.
- Execução: implementar o prompt e variações; preencher `05_CASOS_DE_TESTE.md` e `04_CHECKLISTS.md`.
- Revisão: revisão humana obrigatória por advogado qualificado; aplicar checklist e registrar em `06_HISTORICO.md`.
- Git:
	- `git status` — revisar alterações locais.
	- `git add <arquivos>` — stage de arquivos aprovados.
	- `git commit -m "feat: adiciona/atualiza especialista X — motivo"` — mensagem clara.
	- `git push origin main` — após revisão e aprovação.

Regras de autorização
- Nunca alterar conteúdos dos arquivos do especialista sem autorização expressa do responsável (autorização registrada em issue/PR ou por escrito).
- Antes de qualquer alteração em documentos jurídicos ou arquivos da biblioteca, o especialista deverá apresentar um plano resumido das modificações pretendidas e aguardar autorização expressa para executá-las.
- Nenhum documento jurídico poderá ser alterado automaticamente sem autorização expressa do responsável; alterações automatizadas exigem aprovação prévia e registro.

Padrão de qualidade esperado
- Fundamentação jurídica com referências verificáveis.
- Coerência jurídica.
- Coerência lógica.
- Ausência de contradições.
- Linguagem clara e adequada ao público.
- Fundamentação atualizada (incluir data das fontes).
- Auditabilidade: histórico de alterações e autoria registrados.
- Testabilidade: casos de teste com resultados reproduzíveis.

Forma correta de utilização dentro do VS Code
- Abrir workspace raiz e navegar até `10_Prompts/00_TEMPLATE_ESPECIALISTA`.
- Edição controlada: revisar todas as alterações localmente antes do `commit` e do `push`; garantir que revisões humanas foram feitas antes de subir alterações.
- Extensões recomendadas: Markdown linter, GitLens e spellcheck.
- Uso do template: usar `03_PROMPT.md` como base e salvar variações em arquivos versionados.
- Verificação local: executar validações manuais dos `05_CASOS_DE_TESTE.md` e inspecionar diffs no painel Git do VS Code antes do commit.
