<div align="center">

# Andrick Rodrigues

**Engenheiro de Software | Engenharia de Dados & IA Aplicada**

Desenvolvimento de software orientado a produto, integração de modelos de linguagem (LLMs),<br>
arquiteturas de dados escaláveis, pipelines RAG e implementação determinística de regras de negócio em código.

[![Portfólio](https://img.shields.io/badge/Portfólio-000000?style=flat-square&logo=vercel&logoColor=white)](https://andrick-dev-portfolio.vercel.app/pt)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/andrick-rodrigues)
[![E-mail](https://img.shields.io/badge/E--mail-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:andrickneer@gmail.com)

</div>

---

### Sobre

- Co-fundador na **Nhandu**: desenvolvimento de agentes de IA para WhatsApp e automação de fluxos operacionais para pequenas e médias empresas.
- Dados no Colégio Santo Antônio: modelagem relacional, extração de dados via SQL e construção de relatórios e painéis analíticos no Power BI.
- Pesquisa e Desenvolvimento (Iniciação Científica) na UniFio (2024–2026): modelagem matemática e simulação computacional de Fluxo de Potência Ótimo (OPF) para sistemas elétricos, migrando o motor de cálculo de MATLAB para Python.
- Bacharel em Engenharia de Software (UniFio) | Ourinhos, SP | Português nativo | Inglês B2.

---

### Stack Tecnológica & Ferramentas

**Modelos de Linguagem & Plataformas**
<p align="left">
  <img src="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/dark/openai.png" height="42" alt="OpenAI" title="OpenAI" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/light/claude-color.png" height="42" alt="Claude" title="Claude" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/light/gemini-color.png" height="42" alt="Gemini" title="Gemini" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/light/deepseek-color.png" height="42" alt="DeepSeek" title="DeepSeek" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/dark/perplexity.png" height="42" alt="Perplexity" title="Perplexity" />
</p>

**Engenharia de IA & Agentes**
<p align="left">
  <img src="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/light/langchain-color.png" height="42" alt="LangChain" title="LangChain" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/light/langgraph-color.png" height="42" alt="LangGraph" title="LangGraph" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/dark/mcp.png" height="42" alt="MCP" title="MCP" />
</p>

**Linguagens & Back-end**
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=py,fastapi,django,ts,nodejs,java,spring,kotlin" alt="Python, FastAPI, Django, TypeScript, Node.js, Java, Spring, Kotlin" />
  </a>
</p>

**Dados, Analytics & Machine Learning**
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=postgres,mysql,sqlite,redis,sklearn" alt="PostgreSQL, MySQL, SQLite, Redis, scikit-learn" />
  </a>
  <a href="https://powerbi.microsoft.com">
    <img src="https://raw.githubusercontent.com/simple-icons/simple-icons/develop/icons/powerbi.svg" height="42" alt="Power BI" title="Power BI" />
  </a>
</p>

**Front-end & Aplicações**
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=nextjs,react,tailwind,electron,html,css" alt="Next.js, React, Tailwind, Electron, HTML, CSS" />
  </a>
</p>

**Infraestrutura, Cloud & Mensageria**
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=aws,azure,docker,githubactions,git,linux,vercel,supabase,rabbitmq" alt="AWS, Azure, Docker, GitHub Actions, Git, Linux, Vercel, Supabase, RabbitMQ" />
  </a>
</p>

**Ferramentas de Desenvolvimento & Gestão Ágil**
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=vscode,postman,notion,github" alt="VS Code, Postman, Notion, GitHub" />
  </a>
  <a href="https://github.com/features/copilot">
    <img src="https://raw.githubusercontent.com/simple-icons/simple-icons/develop/icons/githubcopilot.svg" height="40" alt="GitHub Copilot" title="GitHub Copilot" />
  </a>&nbsp;&nbsp;
  <a href="https://trello.com">
    <img src="https://raw.githubusercontent.com/simple-icons/simple-icons/develop/icons/trello.svg" height="40" alt="Trello" title="Trello" />
  </a>
</p>

---

### Projetos em Destaque

#### [emporio-musica-agent](https://github.com/AndrickDev/emporio-musica-agent)
Agente de atendimento para e-commerce com determinismo na execução de regras de negócio.
- Implementação de function calling com 9 ferramentas para consulta de catálogo, carrinho e pedidos.
- Cálculos de desconto progressivo e parcelamento tratados diretamente no código Python, prevenindo erros numéricos do modelo.
- Validação de identificação do cliente e tratamento de dados conforme diretrizes da LGPD.
- Cobertura com 42 testes offline e suite de avaliação com o modelo em produção (11 de 11 casos aprovados).

`Python` `FastAPI` `Gemini API` `Function Calling` `SQLite` `pytest`

#### [case-datarisk](https://github.com/AndrickDev/case-datarisk)
Pipeline de modelagem para risco de crédito e previsão de inadimplência.
- Auditoria exploratória com identificação e correção de data leakage por identificador de cliente (ajuste de AUC aparente de 0,93 para o patamar real de 0,82).
- Estruturação de validação com divisão por grupo (`GroupKFold`, AUC 0,80) e divisão out-of-time (AUC 0,90).
- Análise de interpretabilidade com SHAP, monitoramento de drift populacional e transformação de variáveis com Weight of Evidence (WOE).
- API REST para escoragem em tempo real com FastAPI, conteinerizada em Docker e validada por 30 testes unitários.

`Python` `scikit-learn` `LightGBM` `SHAP` `FastAPI` `Docker` `pytest`

#### [Teseo](https://github.com/AndrickDev/tcc-assist)
Plataforma SaaS para suporte à escrita acadêmica em conformidade com as normas ABNT.
- Monorepo full-stack composto por aplicação Next.js e microsserviço de busca em FastAPI.
- Pipeline de RAG híbrido utilizando pgvector para busca semântica integrado à API do OpenAlex para recuperação de metadados de artigos científicos.
- Gerenciamento de limites de requisição e cotas de uso por tier via Redis.
- Esteira de integração contínua (CI/CD) automatizada com GitHub Actions e deploy na Vercel.

`Next.js` `FastAPI` `PostgreSQL` `pgvector` `Redis` `RAG` `Vercel`

---

### Outros Projetos

| Projeto | Escopo Técnico | Stack |
|:---|:---|:---|
| **[IC_PY](https://github.com/AndrickDev/IC_PY)** | Otimização não-linear de Fluxo de Potência Ótimo (OPF) migrada de MATLAB para Python, mantendo desvio residual entre 0,1% e 0,2% no caso teste IEEE 14-bus. | Python, SciPy, Pyomo, SymPy |
| **TrackPet (TCC)** | Plataforma de rastreamento animal desenvolvida sob princípios de Arquitetura Hexagonal (Ports & Adapters), Domain-Driven Design (DDD) e mensageria assíncrona. | Java, Spring Boot, RabbitMQ, MySQL, Docker |
| **[Nebula](https://github.com/MateusMunhoz/Nebula)** | Aplicação desktop para comunicação P2P com transmissão de áudio em tempo real e compartilhamento de tela. | Electron, WebRTC, Node.js |
| **[Chamada Fio](https://github.com/AndrickDev/acadly-fio)** | Protótipo mobile de registro de presença por proximidade, com 10 regras de validação antifraude e 26 testes unitários. | Android, Kotlin, REST APIs |
| **[OurinhosPlay](https://github.com/AndrickDev/OurinhosPlay)** | Aplicativo mobile para organização de jogos e agendamento de quadras com tratamento de concorrência de reservas. | Kotlin, Supabase, PostgreSQL |
