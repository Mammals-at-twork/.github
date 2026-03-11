<div align="center">

# 🐾 Mammals@Work

### *Humans & LLMs · Construint una millor comprensió mútua, un commit a la vegada*

[![GitHub Org](https://img.shields.io/badge/GitHub-Mammals--at--twork-181717?logo=github&logoColor=white)](https://github.com/Mammals-at-twork)
[![Made with ❤️](https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F-red)](https://github.com/Mammals-at-twork)

</div>

---

## 🧠 Sobre el Col·lectiu

**Mammals@Work** és un col·lectiu obert de **éssers humans i models de llenguatge de gran escala** col·laborant costat a costat per explorar com és la veritable cooperació humà-IA en la pràctica.

Creiem que el millor software es construeix quan la creativitat orgànica i el raonament de velocitat de màquina es reforçen mútuament. Cada repositori aquí és un experiment real d'aquesta idea: dissenyat, escrit, revisat i entregat per humans i agents d'IA treballant com a iguals.

---

## 🎯 Objectius

| Objectiu | Descripció |
|----------|-----------|
| 🤝 **Sinergia Humà-IA** | Demostrar que els humans i els LLMs poden ser socis iguals en la construcció de software de qualitat de producció |
| 🔒 **Mentalitat de Seguretat Primer** | Entregar codi segur per defecte, amb portes SAST/DAST automatitzades en cada PR |
| 🔊 **Veu per a Agents d'IA** | Donar als LLMs orelles i veu perquè els fluxos de treball agèntics puguin comunicar-se naturalment |
| 🌍 **Obert & Reutilitzable** | Alliberar tot com a codi obert perquè tota la comunitat en beneficiï |
| 📈 **Qualitat Contínua** | Tractar la qualitat no com una fase, sinó com una pràctica incrustada en cada flux de treball |

---

## 🚀 Projectes

### [`voice-4-llms`](https://github.com/Mammals-at-work/voice-4-llms) &nbsp;·&nbsp; 🔊 TTS per a Entorns Agèntics

> *Solució Dockeritzada per a conversió ràpida de text a veu en entorns agèntics.*

Una CLI lleugera basada en npm que extreu i executa un motor TTS basat en Docker amb una única comanda. Dissenyada perquè els agents LLM i els pipelines d'automatització puguin generar veu sense cap configuració manual.

```bash
npx @mammals-at-work/voice-4-llms run --text "Hello from the collective" --cache
```

**Destacats**
- Zero configuració: una crida `npx` gestiona `docker pull` + `docker run`
- Sortida cacheable per a expressió repetida
- Funciona a qualsevol lloc on Docker estigui disponible (CI, VPS, local)

---

### [`YACS`](https://github.com/Mammals-at-work/YACS) &nbsp;·&nbsp; 🧠 Habilitats de Claude Code &nbsp; [![npm](https://img.shields.io/npm/v/@mammals-at-work/yacs?logo=npm&logoColor=white)](https://www.npmjs.com/package/@mammals-at-work/yacs)

> *Un Altre Repositori de Habilitats Claude — una col·lecció de Habilitats per a Claude Code que amplien el que pots fer en cada sessió.*

Un paquet de habilitats instal·lable via npm per a Claude Code. Cada habilitat és una eina basada en prompts que Claude invoca automàticament quan és rellevant, o que cridades manualment amb `/skill-name`. Cobreix auditories de seguretat, disseny d'arquitectura, confrontació d'idees, storytelling de dades, gamificació i molt més — en 6 idiomes.

```bash
npx @mammals-at-work/yacs
```

**Categories de Habilitats**
| Categoria | Habilitats Exemple |
|-----------|-------------------|
| 🔒 Qualitat & Seguretat | `/owasp-guardian`, `/llm-safety-checks` |
| 💻 Desenvolupament | `/gamify`, `/tech-debt-hunter` |
| 🏗️ Arquitectura | `/adr-writer`, `/pattern-finder` |
| 🧠 Debat | `/red-team`, `/brainstorm` |
| 📊 Dades | `/data-debate`, `/metric-trap` |

---

### [`paratest`](https://github.com/Mammals-at-work/paratest) &nbsp;·&nbsp; ⚡ Proves Paral·leles

> *Executa les teves suites de proves més ràpid dividint-les entre workers paral·lels.*

Una eina dissenyada per accelerar l'execució de proves distribuint intel·ligentment les càrregues de treball de prova entre múltiples executors paral·lels — reduint els temps de feedback de CI sense canviar una sola línia de codi de prova.

---

### [`auto-ralph`](https://github.com/Mammals-at-work/auto-ralph) &nbsp;·&nbsp; 🤖 Agent d'Automatització &nbsp; `🔜 Pròximament`

> *Properament — estigues atent!*

---

### [`DevSecOps`](https://github.com/Mammals-at-work/DevSecOps) &nbsp;·&nbsp; 🛡️ Infraestructura de Seguretat

> *Tots els scripts i eines necessaris per construir el teu propi executor CI auto-allotjat per a la millor experiència de QA 🏂*

Un kit d'infraestructura de seguretat llestos per a ús que aprovisiona eines **SAST + DAST** en un nou VPS Ubuntu. Ideal per a equips que volen escaneig de seguretat de nivell professional sense costoses subscripcions de SaaS.

**Què s'inclou**
| Capa | Eines |
|-----|------|
| SAST | Semgrep, SonarQube |
| DAST | OWASP ZAP |
| Escanneig de dependències | OWASP Dependency-Check |
| Fluxos de treball de CI | GitHub Actions (Pipelines SAST & DAST) |
| Containerització | Piles Docker Compose per a cada eina |

---

## 🛠️ Pila Tecnològica

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

## ✅ Principis de Qualitat

Ens mantenim a una barra d'alta qualitat en tots els projectes:

- **🔍 Escanneig de seguretat automatitzat** — SAST i DAST s'executen en cada pull request; res no es fusiona amb una vulnerabilitat crítica coneguda.
- **🐳 Entorns reproducibles** — Totes les eines es lliuren com a contenidors Docker perquè "funciona a la meva màquina" mai sigui una excusa.
- **🧪 Cobertura de proves** — Cada projecte es lliura amb proves i CI força que passin abans de qualsevol fusió.
- **📖 Documentació viva** — Els READMEs i la documentació en línia es tracten com a lliuraments de primera classe, no com a pensaments posteriors.
- **👁️ Revisió de parells** — Els contribuidors humans i els agents d'IA es revisen mútuament el codi, combinant diferents estils de raonament per a millors resultats.
- **♻️ Petja mínima** — Preferim eines petites i composables sobre monòlits, i evitem dependències innecessàries.

---

## 🤝 Contribuint

Acollim contribucions de humans *i* agents d'IA. Obriu una qüestió, inicieu una discussió o presenteu una pull request en qualsevol dels nostres repositoris. Totes les idees constructives són vàlides.

---

<div align="center">
*"La millor manera d'entendre la intel·ligència és construir amb ella."*
</div>
<div align="center">
*"Todo viaje comienza con una pregunta...¿Cerré la llave del gas?"*
</div>
