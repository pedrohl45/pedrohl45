<h1 align="center">♱ Pedro Henrique Cabral Leite 🦇</h1>

<p align="center">
  <strong>Estagiário de Desenvolvimento de Software na ITNEX · Backend, DevSecOps & Integração de APIs</strong><br>
  Graduando em Desenvolvimento de Software Multiplataforma (DSM) · Fatec São José dos Campos<br>
  <sub><em>Software Development Intern · Python · TypeScript · MQTT</em></sub>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=3500&pause=1200&color=a87c6f&center=true&vCenter=true&width=560&lines=Backend+%C2%B7+DevSecOps+%C2%B7+Integra%C3%A7%C3%A3o+de+APIs;Python+%C2%B7+TypeScript+%C2%B7+MQTT+%C2%B7+Docker;Estagi%C3%A1rio+dev+na+ITNEX" alt="Backend, Automação e IoT · Python · TypeScript · MQTT · Docker · Estagiário dev na ITNEX" />
</p>

<p align="center">
  <em>« lógica sólida, pipeline seguro e código limpo. longe de hypes, imerso no terminal. »</em>
</p>

<p align="center">
  <a href="https://pedrohl45.github.io"><img src="https://img.shields.io/badge/Portf%C3%B3lio-3b2a22?style=for-the-badge&logo=githubpages&logoColor=d39d90" alt="Portfólio" /></a>
  <a href="https://www.linkedin.com/in/pedrohl45/"><img src="https://img.shields.io/badge/LinkedIn-3b2a22?style=for-the-badge&logo=linkedin&logoColor=d39d90" alt="LinkedIn" /></a>
  <a href="mailto:pedrocabralleite@gmail.com"><img src="https://img.shields.io/badge/Email-3b2a22?style=for-the-badge&logo=gmail&logoColor=d39d90" alt="Email" /></a>
</p>

<p align="center">♱ ──────── ☕ ──────── ♱</p>

### ☕ Sobre mim

- ♱ Estudante de **Desenvolvimento de Software Multiplataforma** na **Fatec São José dos Campos (SP)**, com foco em **backend, integração de APIs e DevSecOps**.
- ♱ Na **ITNEX**, desenvolvo aplicações web (**React** e **TypeScript**), APIs em **Node.js** e **Python (FastAPI)**, integração com o ERP **Datasul (TOTVS)** e projetos de IoT com **ESP32** e **MQTT**, tudo em **Docker** com **PostgreSQL**.
- ♱ Trabalho com **DevOps e DevSecOps**: pipelines de CI/CD e Docker, com segurança no pipeline (scan de segredos com **Gitleaks**, de vulnerabilidades com **Trivy** e de código com **Semgrep**) e imagens rodando sem root.
- ♱ Construo bots e sistemas em **Python** com orientação a objetos, estado isolado por contexto e banco relacional (**MySQL**).
- ♱ Gosto de código legível: **Clean Code**, separação de responsabilidades e, cada vez mais, **testes e CI** desde o começo do projeto.
- ♱ Vivo no terminal: **Ubuntu/Kubuntu** no trabalho, com as cargas pesadas rodando em máquinas **NVIDIA** via **SSH**, e **Arch Linux** em casa, onde registro meus estudos de Shell Script em repositório próprio.
- ♱ Trilha sonora do código: **Post-Punk, Darkwave e Sovietwave**.
- ♱ **Estagiário de desenvolvimento na ITNEX**, aberto a conversar sobre Backend e DevSecOps.

### 💼 Experiência

#### Estagiário de Desenvolvimento de Software · ITNEX
<sub>out/2026 – atual · o código dos projetos de estágio é privado</sub>

**Controle de estoque multidepósito**<br>
Estoque de um cliente em vários depósitos: movimentações, solicitações, aprovação e separação, com acesso por perfil. Integrado ao ERP **Datasul (TOTVS)**.<br>
`TypeScript` `React` `PostgreSQL` `Docker` `Datasul`

**Painel de gestão à vista**<br>
Painel de TV com as 8 etapas do fluxo do produto e tela de consulta com busca e filtros.<br>
`React` `Vite` `Node.js` `PostgreSQL`

**Projeto interno de IoT**<br>
Dispositivos com ESP32-S3 que se comunicam por Bluetooth LE e enviam dados por MQTT a um backend em Python.<br>
`Python` `FastAPI` `MQTT` `ESP32` `BLE`

**Monitoramento de sensores BLE**<br>
Leitura de temperatura, umidade e bateria de sensores Bluetooth no ESP32-S3, enviada por MQTT a um coletor e exibida em painel web.<br>
`C++` `MQTT` `SQLite` `Docker`

### 📜 Projetos em destaque

**[tayama-fatec-bot](https://github.com/pedrohl45/tayama-fatec-bot)** · [site ↗](https://pedrohl45-tayama-fatec-bot.vercel.app)<br>
Gestão acadêmica no Discord: grade filtrada por curso e semestre, notas, faltas, cálculo da média necessária, alerta de frequência em risco, DPs e dispensas. Dados em **MySQL** (colunas JSON para DPs), painel administrativo e site em SPA com player de áudio contínuo.<br>
`Python` `Discord.py` `MySQL` `HTML/CSS/JS`

**[automacao-fatec](https://github.com/pedrohl45/automacao-fatec)**<br>
Sincroniza materiais e prazos do **Microsoft Teams** com **Google Drive e Google Agenda**: preserva a hierarquia de pastas, não reenvia arquivos já copiados, trata paginação e erros 429/5xx e atualiza o evento quando o prazo muda. Testes com **pytest**, lint com **ruff** e **CI no GitHub Actions**.<br>
`Python 3.11+` `Graph API` `Google APIs` `OAuth2` `pytest`

**[yamada-music-bot](https://github.com/pedrohl45/yamada-music-bot)** · [site ↗](https://yamada-music-bot-site.vercel.app)<br>
Bot de música para Discord com slash commands, fila isolada por servidor, carregamento rápido de playlists grandes (extração *flat*) e desconexão inteligente quando fica sozinho no canal.<br>
`Python` `Discord.py` `FFmpeg` `yt-dlp`

**[AvoCredit](https://github.com/fatec-sjc-404-team/API-DSM-1SEMESTRE-2026)** · [site ↗](https://api-dsm-1-semestre-2026.vercel.app)<br>
Projeto integrado do 1º semestre (Fatec): sistema para analistas de crédito que calcula o **potencial de crédito** de regiões e estados do Norte e Nordeste com dados públicos do **BCB/BACEN, IBGE, SPA e Data Senado**. Quatro indicadores (recuperação rápida, crédito caro, dívida saudável x crítica e apostas), gráficos com **Chart.js** e filtros salvos. Scrum e Jira.<br>
`Python` `Flask` `Chart.js` `Google Colab` `Scrum`

<sub>Também por aqui: **[estudos-linux](https://github.com/pedrohl45/estudos-linux)** (20 exercícios de Shell Script e o setup em Arch Linux) · **[portfólio](https://github.com/pedrohl45/pedrohl45.github.io)** (código do meu site)</sub>

<p align="center">♱ ──────── 🕯️ ──────── ♱</p>

### 🕯️ Estudando agora

| Tema | Onde eu pratico | Status |
|:---|:---|:---|
| Backend em Python (FastAPI) | ITNEX | ![construindo](https://img.shields.io/badge/-construindo-a87c6f?style=flat-square) |
| Integração de APIs (Graph, Google, OAuth2) | `automacao-fatec` | ![aplicando](https://img.shields.io/badge/-aplicando-a87c6f?style=flat-square) |
| DevSecOps: segurança no CI (Gitleaks, Trivy, Semgrep) | ITNEX | ![construindo](https://img.shields.io/badge/-construindo-a87c6f?style=flat-square) |
| TypeScript e React | ITNEX | ![aplicando](https://img.shields.io/badge/-aplicando-a87c6f?style=flat-square) |
| MQTT, BLE e ESP32 (IoT) | ITNEX | ![aprofundando](https://img.shields.io/badge/-aprofundando-a87c6f?style=flat-square) |
| Docker e Docker Compose | ITNEX | ![aplicando](https://img.shields.io/badge/-aplicando-a87c6f?style=flat-square) |
| Testes e CI (pytest, ruff, GitHub Actions) | `automacao-fatec` | ![aplicando](https://img.shields.io/badge/-aplicando-a87c6f?style=flat-square) |
| Shell Script e Arch Linux | `estudos-linux` | ![estudando](https://img.shields.io/badge/-estudando-a87c6f?style=flat-square) |
| SQL e estruturas de dados | estudo próprio | ![estudando](https://img.shields.io/badge/-estudando-a87c6f?style=flat-square) |

### 🗝️ Arsenal técnico

**Dia a dia**<br>
<img src="https://img.shields.io/badge/Python-3b2a22?style=for-the-badge&logo=python&logoColor=d39d90" alt="Python" />
<img src="https://img.shields.io/badge/TypeScript-3b2a22?style=for-the-badge&logo=typescript&logoColor=d39d90" alt="TypeScript" />
<img src="https://img.shields.io/badge/React-3b2a22?style=for-the-badge&logo=react&logoColor=d39d90" alt="React" />
<img src="https://img.shields.io/badge/Node.js-3b2a22?style=for-the-badge&logo=nodedotjs&logoColor=d39d90" alt="Node.js" />
<img src="https://img.shields.io/badge/PostgreSQL-3b2a22?style=for-the-badge&logo=postgresql&logoColor=d39d90" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/Docker-3b2a22?style=for-the-badge&logo=docker&logoColor=d39d90" alt="Docker" />
<img src="https://img.shields.io/badge/Git-3b2a22?style=for-the-badge&logo=git&logoColor=d39d90" alt="Git" />
<img src="https://img.shields.io/badge/Ubuntu-3b2a22?style=for-the-badge&logo=ubuntu&logoColor=d39d90" alt="Ubuntu" />

**Segurança e CI**<br>
<img src="https://img.shields.io/badge/GitHub_Actions-3b2a22?style=for-the-badge&logo=githubactions&logoColor=d39d90" alt="GitHub Actions" />
<img src="https://img.shields.io/badge/Gitleaks-3b2a22?style=for-the-badge" alt="Gitleaks" />
<img src="https://img.shields.io/badge/Trivy-3b2a22?style=for-the-badge" alt="Trivy" />
<img src="https://img.shields.io/badge/Semgrep-3b2a22?style=for-the-badge" alt="Semgrep" />
<img src="https://img.shields.io/badge/pytest-3b2a22?style=for-the-badge&logo=pytest&logoColor=d39d90" alt="pytest" />

**Integração e IoT**<br>
<img src="https://img.shields.io/badge/FastAPI-3b2a22?style=for-the-badge&logo=fastapi&logoColor=d39d90" alt="FastAPI" />
<img src="https://img.shields.io/badge/MQTT-3b2a22?style=for-the-badge&logo=mqtt&logoColor=d39d90" alt="MQTT" />
<img src="https://img.shields.io/badge/ESP32-3b2a22?style=for-the-badge&logo=espressif&logoColor=d39d90" alt="ESP32" />
<img src="https://img.shields.io/badge/Zabbix-3b2a22?style=for-the-badge&logo=zabbix&logoColor=d39d90" alt="Zabbix" />

**Também já usei em projetos:** Flask · Pandas · MySQL · SQLite · Discord.py · Google APIs · Playwright · Shell Script · JavaScript · Arch Linux · Scrum e Jira

<p align="center">♱ ──────── 🤎 ──────── ♱</p>

<div align="center">
  <sub><i>less noise, more code · pedro henrique © 2026</i></sub>
</div>
