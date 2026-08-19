# Hi, I'm David Gusmao 👋

**Building systems that tell you why they work.**

Computer Science senior at UCF, graduating December 2026. Project manager and technical lead on a five-person team delivering a permission-aware AI retrieval agent inside a university legal office's enterprise Microsoft 365 tenant, and independently running a study on automated build inference across six build systems and three program corpora.

Most of my work sits on the unglamorous half of AI engineering: deciding what a system must refuse to do, and building the evaluation that says whether it actually refused. Before that, two years of research assistantships in empirical software engineering and human factors.

- 🌐 Portfolio: https://d4davidg.github.io/
- 💼 LinkedIn: https://www.linkedin.com/in/david-e-gusmao/
- 📄 Resume (PDF): https://d4davidg.github.io/downloads/David_Gusmao_Resume.pdf
- 📑 CV (PDF): https://d4davidg.github.io/downloads/David_Gusmao_CV.pdf
- ✉️ Email: davidegusmao@outlook.com

**Looking for:** technical project lead and applied AI research roles.

---

## 🧰 Skills

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?logo=latex&logoColor=white)

**AI & agent engineering**

![Anthropic API](https://img.shields.io/badge/Anthropic%20API-191919?logo=anthropic&logoColor=white)
![OpenAI API](https://img.shields.io/badge/OpenAI%20API-412991?logo=openai&logoColor=white)
![Copilot Studio](https://img.shields.io/badge/Copilot%20Studio-0078D4?logo=microsoft&logoColor=white)
![RAG](https://img.shields.io/badge/Retrieval--Augmented%20Generation-6E56CF)
![Grounding & Citation](https://img.shields.io/badge/Grounding%20%26%20Citation-6E56CF)
![Guardrails](https://img.shields.io/badge/Guardrail%20%26%20Refusal%20Design-6E56CF)

**Evaluation & research methods**

![Eval Suites](https://img.shields.io/badge/Evaluation%20Suites%20%26%20Rubrics-0F766E)
![Regression Testing](https://img.shields.io/badge/Regression%20Testing%20for%20Nondeterminism-0F766E)
![Failure Taxonomy](https://img.shields.io/badge/Failure%20Taxonomy-0F766E)
![Experimental Design](https://img.shields.io/badge/Experimental%20Design-0F766E)

**Web & systems**

![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white)
![SPFx](https://img.shields.io/badge/SharePoint%20Framework-038387?logo=microsoftsharepoint&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![Accessibility](https://img.shields.io/badge/Accessibility-A11y-000000)

---

## 📌 Featured Projects

### ⚖️ Knights Counsel — Permission-Aware AI Retrieval Agent
**Project manager & technical lead** · 5-person team · Jun 2026 – Present
📄 Case study: https://d4davidg.github.io/project-knights-counsel.html

An institutional-memory assistant for a university legal office, deployed inside the client's enterprise Microsoft 365 tenant. It answers from the office's own documents, cites its sources, and declines rather than speculating when retrieval does not supply enough grounding.

- Specified the behavior contract the system must hold to — what it must refuse, when it must decline, and what a citation has to prove
- Designed the two-agent orchestration topology after reversing an earlier six-agent design, and wrote that reversal up as an architecture decision record rather than deleting it
- Built the evaluation suite and the grading rubric used to tell genuine grounding from confident-sounding drift
- Run the project as PM: scope, milestones, decision records, and the client relationship

`Copilot Studio` `SharePoint Online` `Entra ID` `Power Automate` `React` `TypeScript`

> Client work under NDA. The case study covers system design, my role, and evaluation method — no document contents, tenant identifiers, or names other than my own.

---

### 🧱 Build-Recipe Inference Agent — Automated Build Inference
**Independent research project** · May 2026 – Present
📄 Case study: https://d4davidg.github.io/project-build-recipe.html

A containerized LLM agent that works out how to build software it has never seen: which build system, which dependencies, which commands in which order. The agent attempts a build in a clean container, reads the failure, adjusts, and retries — the trace of what finally worked *is* the recipe.

- Structured as a cross-tool comparison across three corpora, because a reported success rate is only interpretable relative to the corpus it was measured on
- Covers six build systems: Autotools, Make, CMake, Maven, Gradle, Ant
- Grounded in ~370 hand-verified build recipes

`Python` `Docker` `Anthropic API` `Linux`

> Status: harness in progress; comparison design complete, results pending.

---

### 🃏 PocketProfessors — MERN Collectible App
**Project manager & front-end developer** · Jul 2025
🌐 Live: http://pocketprofessors.com/ · 📄 Case study: https://d4davidg.github.io/project-pocketprofessors.html · 💻 Repo: https://github.com/jm19pa/Group25-Large-Project-COP4331

A full-stack app where users open packs and collect hand-drawn cards. I owned the pack-opening and collection views, the branding and card art, and the delivery plan.

`React` `TypeScript` `Node.js` `Express` `MongoDB` `JWT`

---

### 🏋️ FitnessFunctions — Role-Based Class Enrollment System
**Solo build** · Nov 2025
📄 Case study: https://d4davidg.github.io/project-fitnessfunctions.html

Separate admin and member dashboards, full CRUD for instructors and classes, and capacity-aware enrollment backed by a relational schema.

`PHP` `MySQL` `JavaScript` `HTML/CSS`

---

### 🦍 CS Majors vs Gorilla — Contact Manager
**Project manager** · Jun 2025
📄 Case study: https://d4davidg.github.io/project-contact-manager.html · 💻 Repo: https://github.com/jm19pa/COP4331-Group16-Small-Project

Contact CRUD with search and form validation over PHP endpoints via `XMLHttpRequest`. My first project-management role, and the reason the Knights Counsel one was not a first attempt.

`JavaScript` `PHP` `AJAX/XHR` `HTML/CSS`

---

### 🌐 This Portfolio
📄 Colophon: https://d4davidg.github.io/project-this-site.html · 💻 Repo: https://github.com/D4DavidG/D4DavidG.github.io

Hand-written HTML and CSS. No framework, no build step, no dependency tree. The colophon covers the accessibility decisions, the per-project accent theming system, and the point at which a build step would start to earn its keep.

---

## 🔬 Research Experience

### Undergraduate Research Assistant — Hardening Build Systems
**University of Central Florida** · Oct 2025 – May 2026
🔗 https://pappasbrent.com/research/hardening-build-systems

- Contributed to empirical research on the security and reliability of open-source software build systems
- Diagnosed build failures by hand across six build systems, including undeclared JDK version requirements and compiler-flag incompatibilities that appear nowhere in the source tree
- Built the tooling that converts raw experimental output into LaTeX-ready tables and pgfplots figures used in project reporting
- Supported reproducible workflows by organizing datasets, validating results, and documenting analysis steps so runs could be repeated by others

The failure categories that came out of this work are what the Build-Recipe project is now built to measure.

### Research Assistant — Human Factors Group Study
**University of Central Florida** · Feb 2025 – May 2026

- Ran experimental sessions for a study of how programmers debug code collaboratively in groups
- Instrumented participants with biometric equipment measuring heart rate, respiration, skin conductance, gaze, and prefrontal cortex blood oxygenation
- Worked under human-subjects research protocol with the associated ethics training completed

---

## ✍️ Writing

Full list: https://d4davidg.github.io/writing.html

- **Knights Counsel: Technical White Paper, v1.0** — co-author; sole author of the system design and behavior specification sections, covering the two-agent orchestration topology, the thirteen numbered behavioral requirements, and the grounding and citation enforcement model *(August 2026)*
- **Knights Counsel: Final Design Document, v2** — contributing author; sole author of the system design section, including the behavior test set and the six-agent to two-agent architecture decision record *(2026)*
- **Architecture decision records** — a running set covering platform selection, delivery surface, access model, session memory, citation rendering, naming enforcement, and fallback strategy

Both documents were produced under NDA and are available on request; a public version would need a redaction pass and sponsor sign-off first.

---

## 🎓 Education & Highlights

**University of Central Florida** — B.S. Computer Science · Expected December 2026 · GPA 3.38

- 🥉 3rd Place — **UCF Horse Plinko Cyber Defense Competition** (Oct 2024)
- 🎓 **Bright Futures Academic Scholarship**
- ✅ Passed the **Computer Science Foundation Exam**
- 📜 Certifications:
  - Human Subjects Research: Social/Behavioral (Group 2)
  - Responsible Conduct of Research (Engineers)
  - Certified Internet Business Associate
  - MTA: Windows OS Fundamentals
  - MTA: Introduction to Programming Using Python
  - American Red Cross Water Safety Instructor

---

## 📊 GitHub Stats

![David's GitHub Stats](https://github-readme-stats.vercel.app/api?username=D4DavidG&show_icons=true&hide_rank=false)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=D4DavidG&layout=compact)

---

## 📫 Contact

- Email: **davidegusmao@outlook.com**
- LinkedIn: **https://www.linkedin.com/in/david-e-gusmao/**
- Portfolio: **https://d4davidg.github.io/**

Thanks for stopping by — feel free to reach out or explore my work!
