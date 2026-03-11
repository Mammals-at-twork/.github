<div align="center">

# 🐾 Mammals@Work

### *Humans & LLMs · Construíndo unha mellor compreensión mutua, un commit de cada vez*

[![GitHub Org](https://img.shields.io/badge/GitHub-Mammals--at--twork-181717?logo=github&logoColor=white)](https://github.com/Mammals-at-twork)
[![Made with ❤️](https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F-red)](https://github.com/Mammals-at-twork)

</div>

---

## 🧠 Sobre o Colectivo

**Mammals@Work** é un colectivo aberto de **seres humanos e modelos de linguaxe de grande porte** colaborando lado a lado para explorar como é a verdadeira cooperación humano-IA na práctica.

Cremos que o mellor software é construído cando a creatividade orgánica e o razoamento de velocidade de máquina se reforzar mutuamente. Cada repositorio aquí é un experimento real desa idea: deseñado, escrito, revisado e entregado por humanos e axentes de IA traballando como pares.

---

## 🎯 Obxectivos

| Obxectivo | Descrición |
|-----------|-----------|
| 🤝 **Sinerxia Humano-IA** | Demostrar que humanos e LLMs poden ser sócios iguais na construción de software de calidade de produción |
| 🔒 **Mentalidade de Seguridade en Primeiro** | Entregar código seguro por defecto, con portóns SAST/DAST automatizados en cada PR |
| 🔊 **Voz para Axentes de IA** | Dar aos LLMs orellas e voz para que fluxos de traballo axencicos poidan se comunicar naturalmente |
| 🌍 **Aberto & Reutilizable** | Lanzar todo como código aberto para que toda a comunidade se beneficie |
| 📈 **Calidade Continua** | Tratar a calidade non como unha fase, senón como unha práctica incorporada en cada fluxo de traballo |

---

## 🚀 Proxectos

### [`voice-4-llms`](https://github.com/Mammals-at-work/voice-4-llms) &nbsp;·&nbsp; 🔊 TTS para Ambientes Axencicos

> *Solución Dockerizada para conversión rápida de texto a fala en ambientes axencicos.*

Un CLI lixeiro baseado en npm que extrae e executa un mecanismo TTS baseado en Docker cun único comando. Deseñado para que axentes LLM e pipelines de automatización poidan xerar fala sen ningunha configuración manual.

```bash
npx @mammals-at-work/voice-4-llms run --text "Hello from the collective" --cache
```

**Destaques**
- Cero configuración: unha chamada `npx` lida con `docker pull` + `docker run`
- Saída almacenable para expresións repetidas
- Funciona en calquera lugar onde Docker está dispoñible (CI, VPS, local)

---

### [`YACS`](https://github.com/Mammals-at-work/YACS) &nbsp;·&nbsp; 🧠 Habilidades do Claude Code &nbsp; [![npm](https://img.shields.io/npm/v/@mammals-at-work/yacs?logo=npm&logoColor=white)](https://www.npmjs.com/package/@mammals-at-work/yacs)

> *Máis Un Repositorio de Habilidades Claude — unha colección de Habilidades para Claude Code que amplan o que podes facer en cada sesión.*

Un paquete de habilidades instalable vía npm para Claude Code. Cada habilidade é unha ferramenta baseada en prompt que Claude invoca automaticamente cando é relevante, ou que chamas manualmente con `/skill-name`. Cobre auditorías de seguridade, deseño de arquitectura, confrontación de ideas, storytelling de datos, gamificación e moito máis — en 6 idiomas.

```bash
npx @mammals-at-work/yacs
```

**Categorías de Habilidades**
| Categoría | Habilidades Exemplo |
|-----------|-------------------|
| 🔒 Calidade & Seguridade | `/owasp-guardian`, `/llm-safety-checks` |
| 💻 Desenvolvemento | `/gamify`, `/tech-debt-hunter` |
| 🏗️ Arquitectura | `/adr-writer`, `/pattern-finder` |
| 🧠 Debate | `/red-team`, `/brainstorm` |
| 📊 Datos | `/data-debate`, `/metric-trap` |

---

### [`paratest`](https://github.com/Mammals-at-work/paratest) &nbsp;·&nbsp; ⚡ Probas Paralelas

> *Executa os teus conxuntos de probas máis rápido dividíndoos entre workers paralelos.*

Unha ferramenta deseñada para acelerar a execución de probas ao distribuír inteligentemente cargas de traballo de proba entre múltiples executores paralelos — reducindo tempos de feedback de CI sen cambiar unha liña de código de proba.

---

### [`auto-ralph`](https://github.com/Mammals-at-work/auto-ralph) &nbsp;·&nbsp; 🤖 Axente de Automatización &nbsp; `🔜 Próximamente`

> *Chegando próximamente — ¡esténte atento!*

---

### [`DevSecOps`](https://github.com/Mammals-at-work/DevSecOps) &nbsp;·&nbsp; 🛡️ Infraestrutura de Seguridade

> *Todos os scripts e ferramentas necesarios para construír o teu propio executor CI auto-hospedado para a mellor experiencia de QA 🏂*

Un kit de infraestrutura de seguridade listo para usar que provisiona ferramentas **SAST + DAST** nun novo VPS Ubuntu. Ideal para equipos que desexan varredura de seguridade de nivel profesional sen caras subscricións de SaaS.

**O que está incluído**
| Capa | Ferramentas |
|-----|------------|
| SAST | Semgrep, SonarQube |
| DAST | OWASP ZAP |
| Varredura de dependencias | OWASP Dependency-Check |
| Fluxos de traballo de CI | GitHub Actions (Pipelines SAST & DAST) |
| Containerización | Pilhas Docker Compose para cada ferramenta |

---

## 🛠️ Pila de Tecnoloxías

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

## ✅ Principios de Calidade

Mantémonos a un alto estándar de calidade en todos os proxectos:

- **🔍 Verificación de seguridade automatizada** — SAST e DAST execútanse en cada solicitude de pull; nada se mestura cun vulnerabilidade crítica coñecida.
- **🐳 Ambientes reproducibles** — Todas as ferramentas son entregadas como containres Docker para que "funciona na miña máquina" nunca sexa unha desculpa.
- **🧪 Cobertura de probas** — Cada proxecto é entregado con probas e CI forza que pasen antes de calquera mestura.
- **📖 Documentación viva** — READMEs e documentación inline son tratados como entregas de primeira clase, non pensamentos posteriores.
- **👁️ Revisión de pares** — Contribuidores humanos e axentes de IA revisan o código un do outro, combinando estilos de razoamento diferentes para mellores resultados.
- **♻️ Pegada mínima** — Preferimos ferramentas pequenas e compostas en lugar de monolitos, e evitamos dependencias innecesarias.

---

## 🤝 Contribuíndo

Acollemoscos con brazos abertos as contribucións de humanos *e* axentes de IA. Abre unha cuestión, inicia unha discusión ou envía unha solicitude de pull en calquera un dos nosos repositorios. Todas as ideas constructivas son válidas.

---

<div align="center">
*"A mellor forma de entender a intelixencia é construír con ela."*
</div>
<div align="center">
*"Todo viaje comienza con una pregunta...¿Cerré la llave del gas?"*
</div>
