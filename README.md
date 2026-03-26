<div align="center">

<!-- HEADER — Typing SVG -->
[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=30&pause=1000&color=58A6FF&center=true&vCenter=true&random=false&width=700&height=60&lines=16+y%2Fo+Full-Stack+Developer;AI+%7C+iOS+%7C+Trading+%7C+Engineering;I+build+things+that+solve+real+problems.)](https://git.io/typing-svg)

<br>

<!-- SOCIAL BADGES -->
[![Profile Views](https://komarev.com/ghpvc/?username=Cyberfilo&color=58A6FF&style=for-the-badge&label=PROFILE+VIEWS)](https://github.com/Cyberfilo)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/filippomenghi)
<!-- ↑ Update this URL once your LinkedIn is live -->

</div>

---

## About Me

I'm **Filippo**, a 16-year-old developer based in Milan, Italy. I work across full-stack development, AI systems, native iOS apps, and algorithmic trading — and I've been building seriously for the past four years. My strongest areas are multi-model AI orchestration, Python-based ML pipelines, and Swift/iOS development. Most of what I build sits at the intersection of AI and real-world utility: trading bots that execute autonomously, tools that route requests to the right model, apps that feel native and fast. I move quickly, pick up new stacks when a project needs it, and care more about shipping something that works than following a conventional path.

**Currently focused on:** Multi-model AI routing & agentic workflows · Native iOS apps with AI integration · ML-driven algorithmic trading · MCP tool development

<br>

---

## Featured Projects

<table>
<tr>

<td width="50%" valign="top">

### Sniper V3 — Algorithmic Trading Bot
> *XAUUSD scalping system with ML-driven execution*

A 10-layer autonomous trading architecture for gold scalping on 5m–15m timeframes.

**Architecture highlights:**
- **Regime Detection** — Classifies market state (trending/ranging/volatile) in real-time
- **ML Ensemble** — LightGBM + CatBoost with isotonic-calibrated meta-learner
- **ATR-Adaptive Trailing** — Dynamic stop-loss and take-profit adjustment
- **Kelly-Fractional Sizing** — Mathematically optimal position sizing per trade
- **Multi-Tier Circuit Breakers** — Portfolio-level risk management with heat caps
- **Concept Drift Detection** — ADWIN + DDM + KS test triggers auto-retrain

`Python` `MQL5` `LightGBM` `CatBoost` `SQLite` `MetaTrader 5`

</td>

<td width="50%" valign="top">

### Betterdock — Multi-Model AI Router
> *Dynamic model selection for optimal AI responses*

A platform that routes each user request to the best AI model instead of locking into one assistant. Model choice becomes dynamic and performance-driven.

**Key concepts:**
- **Query Classification** — Categorizes incoming prompts by complexity and domain
- **Benchmark-Based Routing** — Selects the optimal model per task from a pool of providers
- **Context Handoff** — Maintains conversation continuity across model switches
- **Performance Tracking** — Logs and compares model outputs for continuous optimization

`Python` `Multi-Model APIs` `Routing Logic` `Benchmarking`

</td>

</tr>
<tr>

<td width="50%" valign="top">

### MyLiveGPT — iOS Voice AI App
> *Real-time GPT voice interaction on iOS*

Native iOS application enabling live voice conversations with GPT-4 through a custom WebSocket backend.

**Key features:**
- Real-time voice-to-text-to-voice pipeline
- Custom WebSocket backend for low-latency streaming
- Bespoke design system (custom colors, typography)
- Native Swift UI with hand-crafted visual identity

`Swift` `WebSockets` `OpenAI API` `iOS`

</td>

<td width="50%" valign="top">

### MusicMind MCP — Apple Music AI Intelligence
> *AI-powered music analysis & smart playlist generation*

An MCP server giving Claude deep, intelligent access to Apple Music — taste profiling, adaptive recommendations, and smart playlist generation.

**Key features:**
- **Library Analysis** — Scans listening data for taste profiling
- **Attribute Matching** — Maps track characteristics to user preferences
- **NLP Playlist Generation** — Natural-language request parsing for playlists
- **MCP Architecture** — Seamlessly integrates with Claude and agentic workflows

`Python` `Apple Music SDK` `MCP` `NLP`

</td>

</tr>
<tr>

<td width="50%" valign="top">

### PowairX — F1 in Schools Engineering
> *Computational Fluid Dynamics & race car development*

Aerodynamic development pipeline for a miniature F1 car, including full CFD simulation and wind-tunnel validation.

**Engineering stack:**
- **OpenFOAM** — snappyHexMesh + simpleFoam for external aerodynamics
- **ANSYS Fluent** — Comparative CFD analysis and validation
- **Rhino 3D** — Geometry modeling and surface preparation
- Drag reduction and downforce optimization studies

`OpenFOAM` `ANSYS` `Rhino 3D` `Linux` `ParaView`

</td>

<td width="50%" valign="top">

### GPTChart — AI Trading Dashboard
> *AI-assisted chart analysis with strategy presets*

A visual dashboard for AI-powered trading analysis with strategy presets, symbol selection, and structured execution plans.

**Key features:**
- **Chart Image → Analysis Pipeline** — Vision AI interprets chart screenshots into structured trade decisions
- **Strategy Presets** — Pre-built analysis templates for different market conditions
- **Persistent History** — Tracks past analyses for pattern review
- **Structured Output** — Generates risk levels, triggers, and execution frameworks

`Python` `Streamlit` `AI APIs` `Vision Models`

</td>

</tr>
</table>

<br>

---

## Other Work & Experiments

| Project | Description | Stack |
|---------|-------------|-------|
| **PromptPort** | Universal interface for accessing, comparing, and switching between AI models in one workflow. Dispatcher layer chooses the best model per task. | `Web App` `API Aggregation` `AI Routing` |
| **Local AI Proxy** | Local backend layer that standardizes requests to AI services — input normalization, endpoint abstraction, consistent output reshaping. | `Python` `FastAPI` `API Proxying` |
| **Trading Signal Bot** | Reactive algo bot that monitors markets continuously and generates structured trade signals with entry/exit levels and confirmation logic. | `Python` `yfinance` `Telegram` |
| **PowairX Website** | Professional team website for F1 in Schools — branded sections, sponsor visibility, and polished presentation. | `HTML` `CSS` `JavaScript` |
| **gRPC-Web Binary Decoder** | Decoding workflow for turning opaque serialized API responses into readable structured data via protobuf reconstruction. | `JavaScript` `protobufjs` |
| **CFD Case Generator** | Ready-to-run OpenFOAM simulation file generator to accelerate reproducible CFD testing without manual setup each time. | `OpenFOAM` `Linux` |
| **Swift App Experiments** | Collection of iOS app prototypes — ML image classification, native utility apps, and productized AI experiences. | `Swift` `Xcode` `CoreML` |
| **STL Repair Workflow** | Geometry-repair pipeline for turning broken meshes into simulation-ready or print-ready files (non-manifold cleanup, boolean fixes). | `Rhino 3D` `CAD` |
| **3D Print Optimizer** | Weight optimization tool comparing slicer-estimated vs. real printed weight, with infill tuning and surface/weight tradeoff evaluation. | `Python` `Slicer Data` |
| **Claude Code Skills** | Custom skills for Claude Code — session tracking (GSD Retrospective), note formatting, task orchestration, and AI-detection analysis. | `Claude Code` `Agentic AI` |

<br>

---

## Tech Stack

<div align="center">

#### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-FA7343?style=for-the-badge&logo=swift&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![MQL5](https://img.shields.io/badge/MQL5-4A76A8?style=for-the-badge&logo=metatrader5&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

#### ML & Data
![LightGBM](https://img.shields.io/badge/LightGBM-023047?style=for-the-badge&logo=microsoft&logoColor=white)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=for-the-badge&logo=catboost&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

#### Engineering & Simulation
![OpenFOAM](https://img.shields.io/badge/OpenFOAM-1E8BC3?style=for-the-badge&logoColor=white)
![ANSYS](https://img.shields.io/badge/ANSYS-FFB71B?style=for-the-badge&logo=ansys&logoColor=black)
![Rhino3D](https://img.shields.io/badge/Rhino_3D-801010?style=for-the-badge&logoColor=white)
![ParaView](https://img.shields.io/badge/ParaView-CC2927?style=for-the-badge&logoColor=white)

#### Frameworks & Tools
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![macOS](https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=apple&logoColor=white)

#### Platforms
![MetaTrader 5](https://img.shields.io/badge/MetaTrader_5-4A76A8?style=for-the-badge&logoColor=white)
![Xcode](https://img.shields.io/badge/Xcode-147EFB?style=for-the-badge&logo=xcode&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-191919?style=for-the-badge&logoColor=white)
![Multipass](https://img.shields.io/badge/Multipass-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

</div>

<br>

---

## GitHub Overview

<div align="center">

<!-- Top Languages — looks good regardless of contribution volume -->
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Cyberfilo&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58A6FF&text_color=c9d1d9&langs_count=8" alt="Top Languages" height="180"/>

<br><br>

<!-- Trophies — selective display of relevant ones -->
[![Trophies](https://github-profile-trophy.vercel.app/?username=Cyberfilo&theme=algolia&no-frame=true&no-bg=true&column=4&margin-w=15&title=Repositories,Commits,MultipleLang,PullRequest)](https://github.com/Cyberfilo)

</div>

<!--
Most of my work lives in private repos, local projects, and client work
that isn't on GitHub. The repos here represent what I've chosen to open-source
or share publicly — they're a fraction of the full picture.
-->

<br>

---

## What I'm Working On

```
AI Orchestration   →  Multi-model routing, agentic workflows, MCP tools
iOS Development    →  Native Swift apps with AI integration
Sniper V3          →  Backtesting pipeline & ML ensemble optimization
PowairX            →  Full-car CFD mesh refinement in OpenFOAM
```

<br>

---

<div align="center">

### Let's Connect

*Open to collaborating on AI systems, trading tools, iOS apps, or anything that ships fast and breaks conventions.*

<br>

[![Email](https://img.shields.io/badge/filippo@menghi.dev-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:filippo@menghi.dev)
&nbsp;
[![menghi.dev](https://img.shields.io/badge/menghi.dev-0d1117?style=for-the-badge&logo=googlechrome&logoColor=58A6FF)](https://menghi.dev)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/filippomenghi)
<!-- ↑ Update LinkedIn URL once your profile is live -->

<br>

*CV available on request — or check [menghi.dev](https://menghi.dev) for the full portfolio.*

<br><br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=58A6FF&height=80&section=footer" width="100%"/>

</div>
