# Ficha de captura da fonte

- **source_status:** accessible
- **data da captura:** 2026-08-06
- **URL exata do editor/fonte:** https://chatgpt.com/gpts/editor/g-6a7259cd04a48191a3bb1c2833b0ca2f
- **nome de distribuição da cópia no catálogo:** Agente da Reforma Tributária | Oficial (copy)
- **nome histórico observado no editor:** Agente Reforma — Sala Secreta (até 07/08)
- **proveniência de identidade:** os dois nomes apontam para o mesmo GPT ID
  `g-6a7259cd04a48191a3bb1c2833b0ca2f`, o mesmo agente lógico
  `ac.reforma-tributaria` e o mesmo repositório canônico; “Sala Secreta” foi
  apenas um nome temporário de exibição, não um segundo agente.
- **distribuição observada:** publicado — qualquer pessoa com um link
- **responsável:** Academia-de-Contadores
- **método de recuperação:** inspeção somente leitura da configuração no editor autenticado; nenhuma conversa pública foi usada.
- **status de recuperação:** nome, descrição, instruções, starters, metadados do Knowledge, modelo e capacidades acessíveis; conteúdo dos anexos e configuração de autenticação/endpoint não recuperados.

## Campos acessíveis

- **Descrição:** Acesso temporário até 07/08/2026 para participantes da Sala Secreta, com consulta ao corpus RAG e respostas revisáveis.
- **Quebra-gelos:** `Me ajude com uma projeção tributária`; `Responda esta dúvida de um cliente`; `Me ajude a estudar a Reforma`; `Vale a pena ficar no Simples para este cliente?`.
- **Modelo recomendado:** Nenhum modelo recomendado, os usuários usarão qualquer modelo que preferirem.
- **Busca na web:** ativada.
- **Geração de imagens:** ativada.
- **Intérprete de código/análise de dados:** ativado.
- **Actions:** a interface mostrou somente a opção de criar nova Action; esquema, autenticação e endpoint não ficaram visíveis.
- **Knowledge (somente nomes e tipos visíveis):**
  - `01-INSTRUCOES-GPT-ACTIONS-RAG (1).md`
  - `03-GAPS-CRITICOS-ANTES-DOS-240-TESTES (1).md`
  - `02-REQUISITOS-RETRIEVAL (1).md`
  - `06-MAPA-SIMPLES-CREDITOS-SPLIT-CASHBACK (1).md`
  - `08-GUIA-REFORMA-SEM-SURTO-DAY (1).md`
  - `07-REGRAS-DE-NAO-CALCULAR (1).md`
  - `04-MAPA-COBERTURA-LEGAL-E-ARTIGOS (1).md`
  - `05-MAPA-DFE-XML-ERP (1).md`

## Mapeamento canônico

- **Objetivos:** descrição do editor e escopo expresso nas instruções; ver `objectives/`.
- **Identidade:** trecho explícito de identidade capturado; ver `identity/identity.md`.
- **Soul/tom:** source_status: unavailable; o editor não expõe campo Soul separado; ver `identity/soul.md`.
- **Instruções:** campo integral, sem wrapper específico do GPT Builder, em `instructions/system.md`.
- **Guardrails:** índice das seções `Fontes`, `Guardrails` em `instructions/guardrails.md`; o texto normativo permanece em `instructions/system.md` para evitar duplicação.
- **Workflows:** índice das seções `Uso obrigatorio da Action`, `Auto-revisao antes de responder`, `Fluxo Day`, `Projecoes e regimes`, `DFe/XML/Classificacao` em `instructions/workflows/main.md`.
- **Skills:** padrões comportamentais estão no campo de instruções e em nomes de anexos; os corpos dos anexos não foram acessados, portanto nenhuma skill independente foi inventada.
- **Conectores:** a instrução exige `searchDayRagCorpus`; o runtime/corpus permanece externo e sem segredo versionado.
- **Knowledge:** somente metadados de nomes/tipos; corpos, corpus, índices e exports não foram copiados.

## Dados omitidos

Foram deliberadamente omitidos tokens, credenciais, autenticação, endpoints privados,
conversas de usuários, dados de clientes, logs, arquivos anexos, corpus, índices RAG
e qualquer duplicação específica da plataforma. A linha de instrução destinada ao
campo “Instructions” do GPT Builder e títulos equivalentes foram removidos como
wrapper de plataforma; o comportamento substantivo foi preservado.
