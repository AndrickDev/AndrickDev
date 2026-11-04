<div align="center">

# Andrick Rodrigues

**Engenheiro de Software · Engenharia de Dados & IA Aplicada**

Construo sistemas orientados a produto que integram modelos de linguagem (LLMs),<br>
arquiteturas de dados escaláveis, pipelines RAG e regras de negócio determinísticas em código.

[![Portfólio](https://img.shields.io/badge/Portfólio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://andrick-dev-portfolio.vercel.app/pt)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/andrick-rodrigues)
[![E-mail](https://img.shields.io/badge/E--mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:andrickneer@gmail.com)

</div>

---

### Sobre

- 🚀 Co-fundador na **Nhandu**: Agentes inteligentes de atendimento via WhatsApp, automações transacionais e orquestração de LLMs para PMEs.
- 📊 **Engenharia & Análise de Dados** no Colégio Santo Antônio: Modelagem relacional, estruturação de pipelines SQL e dashboards gerenciais em Power BI.
- 🔬 **Pesquisador de Iniciação Científica (P&D) na UniFio (2024–2026)**: Modelagem matemática e computacional de Fluxo de Potência Ótimo (OPF) para sistemas elétricos (migração MATLAB → Python).
- 🎓 **Bacharel em Engenharia de Software** (UniFio) · Ourinhos, SP · Português (Nativo) · Inglês (B2)

---

### Stack Tecnológica & Ecossistema

**Modelos de Linguagem & Plataformas de IA**
<p align="left">
  <img src="https://img.shields.io/badge/OpenAI_GPT--4o-412991?style=flat-square&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/Anthropic_Claude-D97706?style=flat-square&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/Google_Gemini-8E75C2?style=flat-square&logo=googlegemini&logoColor=white" />
  <img src="https://img.shields.io/badge/DeepSeek_V3_/_R1-4D6BFE?style=flat-square&logo=deepseek&logoColor=white" />
  <img src="https://img.shields.io/badge/Perplexity_AI-20B2AA?style=flat-square&logo=perplexity&logoColor=white" />
</p>

**Engenharia de IA, RAG & Agentes**
<p align="left">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/LangGraph-2C3E50?style=flat-square&logo=diagram-next&logoColor=white" />
  <img src="https://img.shields.io/badge/MCP_(Model_Context_Protocol)-333333?style=flat-square&logo=json&logoColor=white" />
  <img src="https://img.shields.io/badge/RAG_Híbrido-pgvector-336791?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Function_Calling-Eval_Driven_Dev-2ea44f?style=flat-square" />
</p>

**Linguagens & Back-end**
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=py,fastapi,django,ts,nodejs,java,spring,kotlin" />
  </a>
</p>

**Dados, Analytics & Machine Learning**
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=postgres,mysql,sqlite,redis" />
  </a>
</p>
<p align="left">
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/LightGBM-28A745?style=flat-square" />
  <img src="https://img.shields.io/badge/SHAP-Explainable_AI-blueviolet?style=flat-square" />
  <img src="https://img.shields.io/badge/OptBinning-Scorecard_WOE-4B0082?style=flat-square" />
  <img src="https://img.shields.io/badge/Pyomo_/_SciPy-Otimização_Numérica-00599C?style=flat-square" />
</p>

**Front-end & Aplicações**
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=nextjs,react,tailwind,electron,html,css" />
  </a>
</p>

**Cloud, DevOps & Mensageria**
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=aws,azure,docker,githubactions,git,linux,vercel,supabase,rabbitmq" />
  </a>
</p>

**Ferramentas de Desenvolvimento & Gestão Ágil**
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=vscode,postman,notion" />
  </a>
  <img src="https://img.shields.io/badge/GitHub_Copilot-000000?style=flat-square&logo=githubcopilot&logoColor=white" />
  <img src="https://img.shields.io/badge/Trello-0052CC?style=flat-square&logo=trello&logoColor=white" />
</p>

---

### Projetos em Destaque

#### [emporio-musica-agent](https://github.com/AndrickDev/emporio-musica-agent)
**Agente conversacional transacional para e-commerce com determinismo de regras de negócio.**
- Arquitetura baseada em **Function Calling** com 9 ferramentas especializadas em checkout, estoque e consulta de pedidos.
- Cálculos financeiros, descontos progressivos e juros de parcelamento executados rigorosamente em Python (isolados do modelo para evitar alucinações matemáticas).
- Validação de identidade do cliente e sanitização de payloads em conformidade com a LGPD.
- Suite de testes com **42 asserções unitárias/integração** e suite de benchmark contra o modelo real com 100% de precisão (11/11).

`Python` `FastAPI` `Gemini API` `Tool Use / Function Calling` `SQLite` `pytest`

#### [case-datarisk](https://github.com/AndrickDev/case-datarisk)
**Pipeline end-to-end de modelagem de risco de crédito e escoragem antifraude/inadimplência.**
- Auditoria analítica avançada: identificação e eliminação de data leakage crítico por chave de cliente (reduzindo AUC ilusório de 0,93 para o patamar real de 0,82).
- Estruturação de validação cruzada robusta por agrupamento (`GroupKFold`, AUC 0,80) e temporal out-of-time (OOT, AUC 0,90).
- Interpretabilidade de modelos com **SHAP values**, análise de estabilidade populacional (PSI/Drift) e transformação de features via Weight of Evidence (WOE).
- API de escoragem em tempo real com FastAPI conteinerizada em Docker e 30 testes automatizados.

`Python` `scikit-learn` `LightGBM` `SHAP` `FastAPI` `Docker` `pytest`

#### [Teseo](https://github.com/AndrickDev/tcc-assist)
**Plataforma SaaS de assistência à escrita acadêmica com normas ABNT e busca contextual via RAG.**
- Monorepo full-stack integrando Next.js (App Router) e microsserviço de busca semântica em FastAPI.
- Pipeline de **RAG híbrido com pgvector**, correlacionando bases locais e recuperação em tempo real de metadados científicos via API OpenAlex.
- Controle rigoroso de taxa de requisições (*rate limit* e cotas por tier) gerenciado no Redis.
- Deploy automatizado e esteira de CI/CD via GitHub Actions e Vercel.

`Next.js` `FastAPI` `PostgreSQL` `pgvector` `Redis` `RAG` `Vercel` `CI/CD`

---

### Engenharia de Software, Sistemas Distribuídos & Pesquisa

| Repositório / Sistema | Descrição Arquitetural & Escopo Técnico | Principais Tecnologias |
|:---|:---|:---|
| **[IC_PY](https://github.com/AndrickDev/IC_PY)** | Otimização matemática não-linear de Fluxo de Potência Ótimo (OPF) migrado de MATLAB para Python, mantendo desvio residual entre 0,1% e 0,2% no IEEE 14-bus. | `Python`, `SciPy`, `Pyomo`, `SymPy` |
| **TrackPet (TCC)** | Plataforma de telemetria e rastreamento animal com **Arquitetura Hexagonal (Ports & Adapters)**, modelagem orientada a domínio (DDD) e mensageria assíncrona. | `Java`, `Spring Boot`, `RabbitMQ`, `MySQL`, `Docker` |
| **[Nebula / Rezzenha](https://github.com/MateusMunhoz/Nebula)** | Aplicação desktop para comunicação multimídia P2P em tempo real, combinando streaming de áudio com baixa latência e compartilhamento de tela. | `Electron`, `WebRTC`, `Node.js`, `P2P` |
| **[Chamada Fio](https://github.com/AndrickDev/acadly-fio)** | Sistema mobile antifraude para controle presencial acadêmico por proximidade com 10 regras de consistência temporal e 26 testes unitários. | `Kotlin`, `Android SDK`, `REST APIs` |
| **[OurinhosPlay](https://github.com/AndrickDev/OurinhosPlay)** | Aplicação nativa para descoberta de partidas e agendamento de quadras esportivas com gestão transacional de concorrência. | `Kotlin`, `Supabase`, `PostgreSQL` |

---

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AndrickDev&layout=compact&hide_border=true&langs_count=8" height="150" />
</div>
