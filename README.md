<div align="center">

# Andrick Rodrigues

**Engenharia de dados e IA aplicada**

Construo sistemas que colocam modelos de linguagem dentro do produto,<br>
com regras de negócio em código, testes e avaliação.

[![Portfólio](https://img.shields.io/badge/Portfólio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://andrick-dev-portfolio.vercel.app/pt)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/andrick-rodrigues)
[![E-mail](https://img.shields.io/badge/E--mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:andrickneer@gmail.com)

</div>

---

### Sobre

- Fundando a **Nhandu**, com sócios: agentes de IA no WhatsApp e automação para pequenas e médias empresas
- Dados no Colégio Santo Antônio: modelagem relacional SQL e painéis analíticos em Power BI para tomada de decisão da gestão
- Iniciação científica na UniFio (2024–2026): modelagem matemática e otimização em sistemas elétricos de potência (OPF)
- Bacharel em Engenharia de Software (UniFio) · Ourinhos, SP · Português nativo · Inglês B2

### Tecnologias

**Modelos de IA & Motores de Busca**

<picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/dark/openai.png" /><img src="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/light/openai.png" height="40" alt="OpenAI / GPT" title="OpenAI / GPT" /></picture>&nbsp;&nbsp;<img src="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/light/claude-color.png" height="40" alt="Claude" title="Claude" />&nbsp;&nbsp;<img src="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/light/gemini-color.png" height="40" alt="Gemini" title="Gemini" />&nbsp;&nbsp;<picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/dark/deepseek.png" /><img src="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/light/deepseek-color.png" height="40" alt="DeepSeek" title="DeepSeek" /></picture>&nbsp;&nbsp;<picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/dark/perplexity.png" /><img src="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/light/perplexity-color.png" height="40" alt="Perplexity" title="Perplexity" /></picture>

**Engenharia de IA & Agentes**

<img src="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/light/langchain-color.png" height="40" alt="LangChain" title="LangChain" />&nbsp;&nbsp;<img src="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/light/langgraph-color.png" height="40" alt="LangGraph" title="LangGraph" />&nbsp;&nbsp;<picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/dark/mcp.png" /><img src="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/light/mcp.png" height="40" alt="MCP" title="MCP" /></picture>

*Conceitos centrais:* RAG (Retrieval-Augmented Generation), Function Calling / Tool Use, Model Context Protocol (MCP), Avaliação de LLMs e Engenharia de Prompt.

**Dados, BI & Machine Learning**

<a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=py,sklearn,postgres,sqlite,redis" /></a>

*Stack analítica & ML:* Pandas, NumPy, LightGBM, SHAP, OptBinning, pgvector, Power BI e DAX.

**Back-end & Desenvolvimento**

<a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=fastapi,django,ts,nextjs,react,nodejs,prisma,java,spring,kotlin,electron" /></a>

**Cloud, DevOps & Infraestrutura**

<a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=aws,azure,docker,githubactions,git,linux,vercel,supabase" /></a>

**Produtividade, IA no Dev & Gestão Ágil**

<a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=githubcopilot,notion,trello,vscode" /></a>

---

### Projetos em destaque

#### [emporio-musica-agent](https://github.com/AndrickDev/emporio-musica-agent)
Agente autônomo de atendimento para loja de instrumentos. Utiliza function calling com 9 ferramentas e executa regras de negócio determinísticas (preço, descontos progressivos e parcelamento) diretamente em código Python, blindando o LLM contra alucinações de cálculo. Implementa consulta de pedidos com autenticação segura e mascaramento de dados (LGPD), além de pipeline de avaliação com 42 testes offline e suite de validação em produção.

`Python` `Gemini` `Function calling` `FastAPI` `SQLite` `LangChain`

#### [case-datarisk](https://github.com/AndrickDev/case-datarisk)
Modelagem de risco de crédito e previsão de inadimplência. Identificou e corrigiu data leakage crítico por ID de cliente durante auditoria exploratória. Implementou validação cruzada out-of-time (AUC 0,90) e por grupo (AUC 0,80), interpretabilidade com SHAP, monitoramento de feature drift e deploy de API REST para escoragem em tempo real com suite de 30 testes automatizados.

`Python` `scikit-learn` `LightGBM` `FastAPI` `SHAP` `Docker`

#### [Teseo](https://github.com/AndrickDev/tcc-assist)
Plataforma SaaS para assistência à escrita acadêmica em conformidade com as normas ABNT. Arquitetura monorepo com pipeline RAG híbrido consultando embeddings vetoriais via `pgvector` e metadados científicos do OpenAlex. Controle de rate limit e cotas por tier com Redis, autenticação robusta e CI/CD automatizado via GitHub Actions e Vercel.

`Next.js` `FastAPI` `PostgreSQL` `pgvector` `Redis` `RAG` `Vercel`

### Outros projetos

| Projeto | Descrição | Stack |
|---|---|---|
| [Nebula](https://github.com/MateusMunhoz/Nebula) | Transmissão de áudio e tela P2P em tempo real para grupos (coautor, foco em arquitetura e signaling) | Electron, WebRTC, Node.js |
| [Chamada Fio](https://github.com/AndrickDev/acadly-fio) | Sistema antifraude de presença por proximidade para instituições de ensino, com 10 regras de validação | Android, Kotlin, REST API |
| [OurinhosPlay](https://github.com/AndrickDev/OurinhosPlay) | Plataforma de agendamento esportivo local e gestão de quadras com prevenção de conflitos de horário | Kotlin, Supabase, PostgreSQL |
| [IC_PY](https://github.com/AndrickDev/IC_PY) | Otimização matemática de Fluxo de Potência Ótimo (OPF) migrado de MATLAB para Python, com desvio de 0,1% a 0,2% | Python, SciPy, Pyomo |
| TrackPet (TCC) | API de monitoramento e telemetria de animais domésticos estruturada sob Arquitetura Hexagonal e DDD | Java, Spring Boot, MySQL, Docker |

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AndrickDev&layout=compact&hide_border=true&langs_count=6" height="150" />

</div>
