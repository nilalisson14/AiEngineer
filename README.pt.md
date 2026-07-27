# Portfólio de Applied AI Engineering · Nil Alisson

> 🇧🇷 Português · [🇺🇸 English version](https://github.com/nilalisson14/AiEngineer/blob/main/README.en.md)

**Applied AI Engineer** com base em Engenharia de Requisitos — mais de 9 anos na interseção entre negócio, tecnologia e produtos digitais, hoje aplicados à construção de sistemas de IA em domínios regulados. Projeto, desenvolvo e avalio agentes de IA (RAG, LangChain/LangGraph, MCP), com foco em auditabilidade, conformidade e mensuração objetiva de qualidade — não em prova de conceito descartável.

Minha vantagem não é ser o melhor em ML puro: é entender, na prática, o que torna um sistema de IA confiável o suficiente para operar em ambientes de alta criticidade (saúde regulada, energia, setor público). Isso vem de 9+ anos traduzindo regras de negócio ambíguas em requisitos testáveis — a mesma disciplina que hoje aplico a prompts, pipelines de RAG e avaliação de agentes.

---

## Sobre este repositório

Reúne **projetos reais e cases anonimizados** da minha atuação em IA aplicada, organizados por área de competência. Cada projeto descreve contexto, stack, decisões técnicas e resultado.
> **Nota de anonimização:** cases derivados de contexto profissional referem clientes de forma genérica (ex.: "agência reguladora de saúde"). Nomes, credenciais, endpoints e dados operacionais foram removidos. Os projetos autorais (ReqGuard, RAG Provider Benchmark, hr-policy-agent-mcp) são código público e auditável.

---

## Índice por competência

### 🔹 [01 · IA Generativa & Agentes](https://github.com/nilalisson14/reqguard)
RAG, orquestração de agentes e engenharia de prompts aplicados a domínios regulados.

- **[ReqGuard](https://github.com/nilalisson14/reqguard)** — sistema de IA para análise de requisitos e conformidade regulatória: RAG, LangChain, LangGraph, ChromaDB, Google Gemini API, avaliação RAGAS e servidores MCP
- **[hr-policy-agent-mcp](https://github.com/nilalisson14/hr-policy-agent-mcp)** — agente de IA para consulta de políticas de RH, em produção (API + demo web)
- Agentes conversacionais (Typebot + ChatGPT) — definição de personas, tom, regras de negócio e fluxos de conversa para atendimento

### 🔹 [02 · Avaliação de IA & RAG](https://github.com/nilalisson14/rag-provider-benchmark)
Mensuração objetiva de qualidade — o que diferencia um agente demo de um agente confiável.

- **[RAG Provider Benchmark](https://github.com/nilalisson14/rag-provider-benchmark)** — comparação entre Gemini via Vertex AI e Gemini API standalone usando métricas RAGAS; validação de estabilidade operacional para projetos de baixo orçamento
- Avaliação sênior de respostas de LLMs (SxS) e fact-checking estruturado — identificação de alucinações e inconsistências, documentação de padrões de erro para RLHF (Turing, Outlier AI)

### 🔹 [03 · Engenharia de Requisitos Regulatórios](https://github.com/nilalisson14/BusinessAnalyst)
**A base que sustenta tudo acima.** Em domínios regulados, o gargalo de um sistema de IA quase nunca é o modelo — é a ambiguidade nos requisitos que ele deveria satisfazer. 9+ anos elicitando, especificando e auditando requisitos em ambientes onde erro tem custo institucional real (saúde pública, energia, fazenda estadual) é o que diferencia um agente que "funciona numa demo" de um agente que passa por auditoria e vai para produção.

- **Discovery e elicitação em ambientes de múltiplos stakeholders** — mais de 50 sistemas regulatórios críticos de saúde pública (ANVISA), incluindo o discovery do SNCR (Sistema Nacional de Controle de Receituário)
- **Requisitos testáveis e rastreáveis** — histórias de usuário com critérios de aceite em BDD/Gherkin e UAT, aplicados a sistemas fiscais (SEFAZ-PB) e corporativos de energia (Petrobras/SIGITEC)
- **Governança e conformidade ponta a ponta** — modelagem de processos (BPMN/Bizagi), contratos de API REST e coordenação de UAT/QA em ambiente aderente à LGPD
- **A mesma disciplina aplicada a IA:** prompt engineering tratado como engenharia de requisitos — especificação de comportamento esperado, critérios de aceite para respostas de agente, e rastreabilidade entre regra de negócio, prompt e output do modelo. É essa disciplina, não o framework de IA em si, que sustenta auditabilidade em produção
- Ver [portfólio completo de Engenharia de Requisitos](https://github.com/nilalisson14/BusinessAnalyst) para os cases institucionais detalhados, com contexto, escopo e resultado de cada um

### 🔹 [04 · Estudos de caso: RE + IA de ponta a ponta na AWS](https://github.com/nilalisson14/case-ba-re-aws-genai)
Série de estudos de caso documentando a evolução de um sistema de IA regulatório, capítulo a capítulo — da elicitação de requisitos à arquitetura de agente.

- **[case-ba-re-aws-genai](https://github.com/nilalisson14/case-ba-re-aws-genai)** *(Capítulo 1)* — RAG regulatório na AWS (Bedrock + S3 Vectors, Titan Embeddings V2) para análise documental em ambiente regulado, com rastreabilidade completa de requisito a resposta
- **[case-ai-agent-mcp-guardrails](https://github.com/nilalisson14/case-ai-agent-mcp-guardrails)** *(Capítulo 2 — planejado, execução ainda não iniciada)* — evolução direta de uma lacuna documentada no Capítulo 1: um Bedrock Agent que verifica conformidade regulatória com ferramentas determinísticas (action groups), recusa decisões regulatórias por guardrail configurado (não só instrução de prompt), exposto via MCP

### 🔹 [Produto próprio: SaaS de Agentes de IA](https://github.com/nilalisson14/Professional-AI-Framework)
- **Professional AI Framework** — plataforma para criação de agentes de IA com landing pages (FastAPI, PostgreSQL, ChromaDB, Nginx, VPS Oracle Cloud)

---

## Trajetória resumida

| Período   | Papel                                                        | Domínio                    |
| --------- | ------------------------------------------------------------- | --------------------------- |
| 2025–atual | Applied AI Engineer (projetos autorais)                      | RAG, agentes, avaliação     |
| 2024–2026 | GenAI aplicada em Engenharia de Requisitos (saúde regulada)  | Vigilância sanitária        |
| 2024–2026 | Consultor GenAI — prompts, agentes conversacionais, avaliação de LLMs | IA aplicada (freelance) |
| 2021–2024 | Analista de Requisitos (energia, fazendário)                 | PD&I, tributário            |
| 2018–2021 | Analista de Requisitos → Coordenador de TI                    | Educação                    |

A trajetória mostra a transição de engenharia de requisitos em ambientes regulados para engenharia de IA aplicada — carregando a mesma disciplina de auditabilidade e mensuração de qualidade.

---

## Formação e certificações

- **Mestrando em Ciência da Computação** (UFPB) — pesquisa em LLMs aplicados à Engenharia de Requisitos
- **MBA em Governança de TI**
- **Bacharel em Sistemas de Informação** (UFPB)
- AWS Cloud Practitioner · Scrum Foundation (SFPC) · GenAI for Startups (AWS Bedrock)

## Competências técnicas

**IA Generativa & Agentes**
`LangChain` / `LangGraph` — frameworks para orquestrar chamadas a LLMs e construir agentes com múltiplos passos (planejar → chamar ferramenta → executar → validar), em vez de um único prompt isolado.
`RAG` (Retrieval-Augmented Generation) — arquitetura que busca informação relevante numa base de conhecimento antes de gerar a resposta, reduzindo alucinação e permitindo que o agente responda com base em documentos reais (normas, políticas, requisitos).
`MCP` (Model Context Protocol) — protocolo padrão para conectar um agente de IA a ferramentas e fontes de dados externas de forma segura e reutilizável.

**APIs de IA**
`OpenAI API` · `Anthropic Claude` · `Google Gemini API` / `Vertex AI` — integração direta com os principais provedores de modelos de linguagem, incluindo a via empresarial (Vertex AI), mais estável para ambientes de produção com orçamento controlado.

**Avaliação de IA**
`RAGAS` — framework que mede objetivamente a qualidade de um sistema RAG (precisão da resposta, relevância do que foi recuperado, fidelidade ao contexto) em vez de avaliar "no olho".
`SxS` (avaliação side-by-side) e `fact-checking estruturado` — comparação sistemática de respostas de diferentes modelos/versões contra critérios de qualidade, usada para identificar alucinação e inconsistência antes de ir para produção.

**Dados & Busca Semântica**
`ChromaDB` — banco de dados vetorial: armazena texto convertido em vetores numéricos para permitir busca por significado, não só por palavra-chave (a base técnica de qualquer RAG).
`pandas` — biblioteca padrão em Python para manipulação e análise de dados tabulares.

**Backend & Integração**
`Python` · `FastAPI` (framework para construir APIs) · `PostgreSQL` (banco de dados relacional) · `REST APIs` e `webhooks` (padrões de integração entre sistemas).

**Cloud & Infraestrutura**
`AWS` (Cloud Practitioner certificado) · `Google Cloud` (Vertex AI) · `Oracle Cloud` · `Nginx` (servidor web) · `systemd` (gerenciamento de serviços em produção) · `GitHub Actions` (automação de testes e deploy — CI/CD).

**Requisitos & Governança**
Discovery · requisitos funcionais e não funcionais · critérios de aceite (BDD/UAT) · conformidade e auditabilidade em ambientes regulados — a disciplina que garante que qualquer sistema acima, incluindo os de IA, atenda ao que o negócio realmente precisa e resista a auditoria.

---

## Contato

🌐 [nilalisson.com.br/portfolio](https://nilalisson.com.br/portfolio) · 💼 [linkedin.com/in/po-alisson](https://linkedin.com/in/po-alisson) · ✉️ <nilalisson@gmail.com>
