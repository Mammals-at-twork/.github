<div align="center">

# 🐾 Mammals@Work

### *Humans & LLMs · Construindo um entendimento mútuo melhor, um commit de cada vez*

[![GitHub Org](https://img.shields.io/badge/GitHub-Mammals--at--twork-181717?logo=github&logoColor=white)](https://github.com/Mammals-at-twork)
[![Made with ❤️](https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F-red)](https://github.com/Mammals-at-twork)

</div>

---

## 🧠 Sobre o Coletivo

**Mammals@Work** é um coletivo aberto de **seres humanos e modelos de linguagem de grande porte** colaborando lado a lado para explorar como é a verdadeira cooperação humano-IA na prática.

Acreditamos que o melhor software é construído quando a criatividade orgânica e o raciocínio de velocidade de máquina se reforçam mutuamente. Cada repositório aqui é um experimento real dessa ideia: projetado, escrito, revisado e entregue por humanos e agentes de IA trabalhando como pares.

---

## 🎯 Objetivos

| Objetivo | Descrição |
|----------|-----------|
| 🤝 **Sinergia Humano-IA** | Demonstrar que humanos e LLMs podem ser parceiros iguais na construção de software de qualidade de produção |
| 🔒 **Mentalidade de Segurança em Primeiro** | Entregar código seguro por padrão, com portões SAST/DAST automatizados em cada PR |
| 🔊 **Voz para Agentes de IA** | Dar aos LLMs ouvidos e voz para que fluxos de trabalho agêncicos possam se comunicar naturalmente |
| 🌍 **Aberto & Reutilizável** | Lançar tudo como código aberto para que toda a comunidade se beneficie |
| 📈 **Qualidade Contínua** | Tratar qualidade não como uma fase, mas como uma prática incorporada em cada fluxo de trabalho |

---

## 🚀 Projetos

### [`voice-4-llms`](https://github.com/Mammals-at-work/voice-4-llms) &nbsp;·&nbsp; 🔊 TTS para Ambientes Agêncicos

> *Solução Dockerizada para conversão rápida de texto em fala em ambientes agêncicos.*

Um CLI leve baseado em npm que extrai e executa um mecanismo TTS baseado em Docker com um único comando. Projetado para que agentes LLM e pipelines de automação possam gerar fala sem nenhuma configuração manual.

```bash
npx @mammals-at-work/voice-4-llms run --text "Hello from the collective" --cache
```

**Destaques**
- Zero configuração: uma chamada `npx` lida com `docker pull` + `docker run`
- Saída cacheável para expressões repetidas
- Funciona em qualquer lugar onde Docker está disponível (CI, VPS, local)

---

### [`YACS`](https://github.com/Mammals-at-work/YACS) &nbsp;·&nbsp; 🧠 Habilidades do Claude Code &nbsp; [![npm](https://img.shields.io/npm/v/@mammals-at-work/yacs?logo=npm&logoColor=white)](https://www.npmjs.com/package/@mammals-at-work/yacs)

> *Mais Um Repositório de Habilidades Claude — uma coleção de Habilidades para Claude Code que expandem o que você pode fazer em cada sessão.*

Um pacote de habilidades instalável via npm para Claude Code. Cada habilidade é uma ferramenta baseada em prompt que Claude invoca automaticamente quando relevante, ou que você chama manualmente com `/skill-name`. Cobre auditorias de segurança, design de arquitetura, confrontação de ideias, storytelling de dados, gamificação e muito mais — em 6 idiomas.

```bash
npx @mammals-at-work/yacs
```

**Categorias de Habilidades**
| Categoria | Habilidades Exemplo |
|-----------|-------------------|
| 🔒 Qualidade & Segurança | `/owasp-guardian`, `/llm-safety-checks` |
| 💻 Desenvolvimento | `/gamify`, `/tech-debt-hunter` |
| 🏗️ Arquitetura | `/adr-writer`, `/pattern-finder` |
| 🧠 Debate | `/red-team`, `/brainstorm` |
| 📊 Dados | `/data-debate`, `/metric-trap` |

---

### [`paratest`](https://github.com/Mammals-at-work/paratest) &nbsp;·&nbsp; ⚡ Testes Paralelos

> *Execute seus conjuntos de testes mais rápido dividindo-os entre workers paralelos.*

Uma ferramenta projetada para acelerar a execução de testes ao distribuir inteligentemente cargas de trabalho de teste entre múltiplos executores paralelos — reduzindo tempos de feedback de CI sem alterar uma linha de código de teste.

---

### [`auto-ralph`](https://github.com/Mammals-at-work/auto-ralph) &nbsp;·&nbsp; 🤖 Agente de Automação &nbsp; `🔜 Em Breve`

> *Chegando em breve — fique atento!*

---

### [`DevSecOps`](https://github.com/Mammals-at-work/DevSecOps) &nbsp;·&nbsp; 🛡️ Infraestrutura de Segurança

> *Todos os scripts e ferramentas necessários para construir seu próprio executor CI auto-hospedado para a melhor experiência de QA 🏂*

Um kit de infraestrutura de segurança pronto para uso que provisiona ferramentas **SAST + DAST** em um novo VPS Ubuntu. Ideal para equipes que desejam varredura de segurança de nível profissional sem caras assinaturas de SaaS.

**O que está incluído**
| Camada | Ferramentas |
|--------|------------|
| SAST | Semgrep, SonarQube |
| DAST | OWASP ZAP |
| Varredura de dependências | OWASP Dependency-Check |
| Fluxos de trabalho de CI | GitHub Actions (Pipelines SAST & DAST) |
| Containerização | Pilhas Docker Compose para cada ferramenta |

---

## 🛠️ Pilha de Tecnologias

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

## ✅ Princípios de Qualidade

Nos mantemos a um alto padrão de qualidade em todos os projetos:

- **🔍 Verificação de segurança automatizada** — SAST e DAST rodam em cada solicitação de pull; nada é mesclado com uma vulnerabilidade crítica conhecida.
- **🐳 Ambientes reproduzíveis** — Todas as ferramentas são entregues como contêineres Docker para que "funciona na minha máquina" nunca seja uma desculpa.
- **🧪 Cobertura de testes** — Cada projeto é entregue com testes e CI força que passem antes de qualquer mesclagem.
- **📖 Documentação ativa** — READMEs e documentação inline são tratados como entregas de primeira classe, não pensamentos posteriores.
- **👁️ Revisão de pares** — Contribuidores humanos e agentes de IA revisam o código um do outro, combinando estilos de raciocínio diferentes para melhores resultados.
- **♻️ Pegada mínima** — Preferimos ferramentas pequenas e compostas em vez de monolitos, e evitamos dependências desnecessárias.

---

## 🤝 Contribuindo

Acolhemos contribuições de humanos *e* agentes de IA. Abra uma questão, inicie uma discussão ou envie uma solicitação de pull em qualquer um de nossos repositórios. Todas as ideias construtivas são válidas.

---

<div align="center">
*"A melhor maneira de entender a inteligência é construir com ela."*
</div>
<div align="center">
*"Todo viaje comienza con una pregunta...¿Cerré la llave del gas?"*
</div>
