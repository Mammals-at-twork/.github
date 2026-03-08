<div align="center">

# 🐾 Mammals@Work

### *Humans & LLMs · Building a better mutual understanding, one commit at a time*

[![GitHub Org](https://img.shields.io/badge/GitHub-Mammals--at--twork-181717?logo=github&logoColor=white)](https://github.com/Mammals-at-twork)
[![Made with ❤️](https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F-red)](https://github.com/Mammals-at-twork)

</div>

---

## 🧠 About the Collective

**Mammals@Work** is an open collective of **human beings and large language models** collaborating side-by-side to explore what genuine human–AI cooperation looks like in practice.

We believe that the best software is built when organic creativity and machine-speed reasoning reinforce each other. Every repository here is a real experiment in that idea: designed, written, reviewed, and shipped by both humans and AI agents working as peers.

---

## 🎯 Goals

| Goal | Description |
|------|-------------|
| 🤝 **Human–AI synergy** | Demonstrate that humans and LLMs can be equal partners in building production-quality software |
| 🔒 **Security-first mindset** | Ship code that is secure by default, with automated SAST/DAST gates on every PR |
| 🔊 **Voice for AI agents** | Give LLMs ears and a voice so agentic workflows can communicate naturally |
| 🌍 **Open & reusable** | Release everything as open-source so the whole community benefits |
| 📈 **Continuous quality** | Treat quality not as a phase but as a practice embedded in every workflow |

---

## 🚀 Projects

### [`voice-4-llms`](https://github.com/Mammals-at-twork/voice-4-llms) &nbsp;·&nbsp; 🔊 TTS for Agentic Environments

> *Dockerized solution for quick Text-to-Speech in agentic environments.*

A lightweight **npm CLI** that pulls and runs a Docker-based TTS engine with a single command. Designed so that LLM agents and automation pipelines can generate speech without any manual setup.

```bash
npx @mammals-at-work/voice-4-llms run --text "Hello from the collective" --cache
```

**Highlights**
- Zero-config: one `npx` call handles `docker pull` + `docker run`
- Cacheable output for repeated utterances
- Works anywhere Docker is available (CI, VPS, local)

---

### [`DevSecOps`](https://github.com/Mammals-at-twork/DevSecOps) &nbsp;·&nbsp; 🛡️ Security Infrastructure

> *All the scripts and tools needed to build your own CI self-hosted runner for the best QA experience 🏂*

A turnkey security infrastructure kit that provisions **SAST + DAST** tooling on a fresh Ubuntu VPS. Ideal for teams that want professional-grade security scanning without expensive SaaS subscriptions.

**What's included**
| Layer | Tools |
|-------|-------|
| SAST | Semgrep, SonarQube |
| DAST | OWASP ZAP |
| Dependency scanning | OWASP Dependency-Check |
| CI workflows | GitHub Actions (SAST & DAST pipelines) |
| Containerisation | Docker Compose stacks for every tool |

---

## 🛠️ Tech Stack

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?logo=gnubash&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?logo=sonarqube&logoColor=white)
![Semgrep](https://img.shields.io/badge/Semgrep-1B2D55?logo=semgrep&logoColor=white)
![OWASP ZAP](https://img.shields.io/badge/OWASP%20ZAP-000000?logo=owasp&logoColor=white)

</div>

---

## ✅ Quality Principles

We hold ourselves to a high quality bar across every project:

- **🔍 Automated security scanning** — SAST and DAST run on every pull request; nothing merges with a known critical vulnerability.
- **🐳 Reproducible environments** — All tooling ships as Docker containers so "works on my machine" is never an excuse.
- **🧪 Test coverage** — Each project ships with tests and CI enforces they pass before any merge.
- **📖 Living documentation** — READMEs and inline docs are treated as first-class deliverables, not afterthoughts.
- **👁️ Peer review** — Both human contributors and AI agents review each other's code, combining different reasoning styles for better outcomes.
- **♻️ Minimal footprint** — We prefer small, composable tools over monoliths, and avoid unnecessary dependencies.

---

## 🤝 Contributing

We welcome contributions from humans *and* AI agents. Open an issue, start a discussion, or submit a pull request in any of our repositories. All constructive ideas are fair game.

---

<div align="center">

*"The best way to understand intelligence is to build with it."*

</div>