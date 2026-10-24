<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20,24,30&height=180&section=header&text=Vishal%20Acharya&fontSize=70&fontAlignY=35&animation=fadeIn&fontColor=gradient" />

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=2800&pause=1000&color=36BCF7&center=true&vCenter=true&repeat=true&width=720&lines=Quantum+Computing+%7C+Machine+Learning+%7C+Security;Post-Quantum+Cryptography+%26+Lattice+Attack+Simulation;Resilient+Systems+for+Emergency+Communication;CSE+%40+VJTI+Mumbai+%7C+Minor+in+Defence+Technology" alt="Typing SVG" /></a>

<br/>

<img src="https://img.shields.io/badge/Focus-Quantum%20%7C%20ML%20%7C%20Security-00D9FF?style=flat-square" />
<img src="https://img.shields.io/badge/VJTI-Mumbai-blueviolet?style=flat-square" />
<img src="https://img.shields.io/badge/Minor-Defence%20Technology-critical?style=flat-square" />
<img src="https://img.shields.io/badge/Open%20to-Research%20Internships-3fb950?style=flat-square" />

<br/><br/>

<a href="https://github.com/vishalacharya09"><img src="https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github" /></a>
<a href="https://linkedin.com/in/vishal-acharya"><img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin" /></a>
<a href="mailto:vishalacharya2108@gmail.com"><img src="https://img.shields.io/badge/-Email-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>

<img src="https://komarev.com/ghpvc/?username=vishalacharya09&label=Profile%20Views&color=36BCF7&style=flat-square" alt="Profile Views" />

</div>

---

## 👨‍💻 About Me

I'm **Vishal Acharya**, a third-year B.Tech CSE student at **VJTI Mumbai** with a **Minor in Defence Technology**. I build things where **quantum computing, machine learning and security** meet, and I'm aiming for ML/security research internships, publications and graduate school.

```python
vishal = {
    "institute": "VJTI Mumbai (B.Tech CSE, Minor in Defence Technology)",
    "location": "Mumbai, India 🇮🇳",
    "research_interests": ["Quantum algorithms", "Post-quantum cryptanalysis",
                           "Multimodal ML", "Agent & systems security"],
    "currently_building": ["DCP/EDCP lattice-attack simulator",
                           "RESCUE: admission control for emergency gateways"],
    "looking_for": "ML / security research internships & collaborations",
    "motto": "Build at the edge, where classical meets quantum",
}
```

---

## 🔭 What I'm Working On Right Now

| | Project | Status |
|:-:|:--|:--|
| 🔬 | **DCP/EDCP Lattice Attack Simulator** (final-year project) | Core engine built; turning it into an interactive web simulator |
| 🚨 | **RESCUE**: completion-backed admission control for emergency communication gateways | Research in progress: simulation harness + PostgreSQL fencing validator |
| 🛡️ | **Prompt-injection benchmark for security-investigation agents** | Planned: adaptive, multilingual (English/Hindi/Marathi), tool-authorization focus |
| 🧠 | **NVIDIA DLI: Fundamentals of Deep Learning** | Transfer learning (VGG16), data augmentation, PyTorch |

---

## 💼 Featured Projects

### 🔬 Research

<details open>
<summary><b>🧮 DCP / EDCP Lattice Attack Simulator</b> — <i>Python · Qiskit · Qiskit-Aer</i></summary>
<br/>

Simulator for the **Dihedral Coset Problem (DCP)** and its extended variant (EDCP), the quantum-sampling step behind toy lattice-attack pipelines.

- DCP state preparation and QFT-based Fourier sampling
- Truncation sweeps, sample-complexity analysis, and noise/scaling experiments
- Generic EDCP engine and a simplified modulus-halving recovery step
- Automated test suite covering each phase
- **Next:** an interactive website to run and visualise the attack pipeline

</details>

<details open>
<summary><b>🚨 RESCUE: Admission Control for Emergency Communication Gateways</b> — <i>Python · PostgreSQL</i></summary>
<br/>

Research on keeping emergency communication systems (floods, earthquakes) responsive under disaster surges *and* adaptive resource-exhaustion DoS.

- Lease-based admission control, owner-confirmed release, executor quarantine and database fencing
- Policy ladder compared across multiple workloads and enforcement levels, with formally stated hypotheses
- Primary metric: legitimate requests completed by their deadline, divided by requests offered
- Simulation harness plus a PostgreSQL logical-decoding fencing checker

</details>

<details>
<summary><b>🛡️ Adaptive Multilingual Prompt-Injection Benchmark</b> — <i>planned · Python · SQLite · Pydantic · Docker</i></summary>
<br/>

A benchmark for **cybersecurity investigation agents** with provenance-aware tool authorization.

- One agent, three SOC-style tools (SIEM search, threat-intel lookup, ticket creation), synthetic data only
- English, Hindi and Marathi injections; static vs adaptive attackers
- Defences compared: none / classifier / policy layer / layered
- Reference frameworks: AgentDojo, AgentLAB

</details>

### 🤖 Machine Learning & Security

<details>
<summary><b>📰 Cross-Modal Fake News Thumbnail Detection</b> — <i>PyTorch · CLIP · Streamlit · FastAPI</i></summary>
<br/>

Detects misleading thumbnail/headline pairs by modelling image-text consistency.

- **CLIP ViT-B/32** encoders with **cross-modal attention**
- **Monte Carlo Dropout** for uncertainty estimates
- Streamlit front end backed by a FastAPI inference service
- Team project

</details>

<details>
<summary><b>🦠 Behavioral Ransomware Detection</b> — <i>Python · watchdog · psutil</i></summary>
<br/>

Detects ransomware by *what it does* rather than by signatures.

- Filesystem monitoring with `watchdog`, process telemetry with `psutil`
- **Shannon-entropy** analysis of written files plus **Z-score** filtering to cut false positives
- Two-person project

</details>

<details>
<summary><b>📏 CamRuler: Real-Time Object Measurement</b> — <i>Python · OpenCV</i></summary>
<br/>

Measures real-world object dimensions from a live camera feed.

- OpenCV computer-vision pipeline
- Written up as an IEEE-style review paper
- Team project

</details>

### ⚛️ Quantum Computing

<table>
<tr>
<td width="50%" valign="top">

**⚛️ Quantum Prisoner's Dilemma** <br/>
<sub>Python · Qiskit · NumPy · Streamlit · Plotly</sub>

EWL protocol over entangled qubits. The quantum "Q" strategy moves the equilibrium from the classical (1,1) to the optimal (3,3).

- 3D interactive payoff surface
- Depolarizing-noise and decoherence simulation
- Vectorised NumPy `einsum` backend
- Cyberpunk terminal UI and CLI mode

[![Repo](https://img.shields.io/badge/View-Repository-181717?style=flat-square&logo=github)](https://github.com/vishalacharya09/quantum-prisoners-dilemma)

</td>
<td width="50%" valign="top">

**🔐 Quantum Secret Sharing (HBB)** <br/>
<sub>Python · Qiskit</sub>

Full Hillery-Bužek-Berthiaume protocol.

- GHZ state distribution, Bell-measurement encoding, collaborative decoding
- Attack simulator: Intercept-and-Resend, Entangle-and-Measure
- Lightweight 3-qubit bit-flip error-correction wrapper

[![Repo](https://img.shields.io/badge/View-Repository-181717?style=flat-square&logo=github)](https://github.com/vishalacharya09/quantum-secret-sharing)

</td>
</tr>
<tr>
<td colspan="2" valign="top">

**🌌 Interactive Quantum Journey** <br/>
<sub>Educational platform built for the VJTI community</sub>

</td>
</tr>
</table>

### 🌐 Full-Stack & AI Apps

<table>
<tr>
<td width="50%" valign="top">

**💬 MuseBot** <br/>
<sub>FastAPI · React · Anthropic API</sub>

A chatbot built for my portfolio and for learning LLM application design.

</td>
<td width="50%" valign="top">

**✈️ CerebroX: AI Travel Planner** <br/>
<sub>Python · NLP · Pandas · Flask</sub>

An NLP intent classifier turns preferences, budget and location into day-by-day itineraries.

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<details open>
<summary><b>💻 Languages</b></summary>
<br/>

![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Q#](https://img.shields.io/badge/-Q%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

</details>

<details open>
<summary><b>⚛️ Quantum</b></summary>
<br/>

![Qiskit](https://img.shields.io/badge/-Qiskit-6929C4?style=for-the-badge&logo=ibm&logoColor=white)
![Qiskit Aer](https://img.shields.io/badge/-Qiskit%20Aer-6929C4?style=for-the-badge)

**Concepts:** HBB Secret Sharing · EWL Game Theory · GHZ States · Fourier Sampling / QFT · Dihedral Coset Problem · Noise & Decoherence · Error Correction · NMR Quantum Processing

</details>

<details open>
<summary><b>🤖 AI / ML</b></summary>
<br/>

![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

**Concepts:** CLIP · Cross-modal attention · Transfer learning (VGG16) · MC Dropout · NLP intent classification

</details>

<details>
<summary><b>🌐 Backend, Apps & Data</b></summary>
<br/>

![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/-Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/-Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

</details>

<details>
<summary><b>🔧 Tools & Platforms</b></summary>
<br/>

![Git](https://img.shields.io/badge/-Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github)
![VS Code](https://img.shields.io/badge/-VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Kali Linux](https://img.shields.io/badge/-Kali%20Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white)
![GCP](https://img.shields.io/badge/-Google%20Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Cisco Packet Tracer](https://img.shields.io/badge/-Cisco%20Packet%20Tracer-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)

</details>

---

## 🧭 How My Work Connects

```mermaid
graph LR
    A[⚛️ Quantum Algorithms] --> B[🧮 DCP/EDCP & Lattice Attacks]
    A --> C[🔐 Secret Sharing & Game Theory]
    D[🤖 Machine Learning] --> E[📰 Multimodal Fake-News Detection]
    D --> F[🛡️ Agent Security Benchmark]
    G[🛡️ Defence & Security] --> H[🦠 Ransomware Detection]
    G --> I[🚨 Resilient Emergency Systems]
    B --> J[🎓 Research & Publications]
    E --> J
    F --> J
    I --> J

    style A fill:#6929C4,stroke:#1f6feb,stroke-width:2px,color:#fff
    style D fill:#EE4C2C,stroke:#1f6feb,stroke-width:2px,color:#fff
    style G fill:#0A66C2,stroke:#1f6feb,stroke-width:2px,color:#fff
    style J fill:#3fb950,stroke:#1f6feb,stroke-width:2px,color:#000
```

---

## 🔬 Research Exposure

| | Event | Highlights |
|:-:|:--|:--|
| 🏛️ | **I-HUB Quantum Technology Foundation, IISER Pune** *(Apr 2026)* | Live **NMR-based quantum information processing**, the "Genetic Coffee" experiment and quantum hardware platforms, seeing qubit control and decoherence outside of simulation. |

---

## 🎯 Goals & Learning

<table align="center">
<tr>
<td valign="top" width="33%">

### 🎯 Goals

- [x] Quantum protocol implementations
- [x] I-HUB research visit
- [x] Multimodal ML project (CLIP)
- [ ] Publish a research paper
- [ ] Contribute to Qiskit (open source)
- [ ] Cloud certification (AWS / GCP)

</td>
<td valign="top" width="33%">

### 📚 Currently Learning

- Post-quantum cryptanalysis
- Deep learning with PyTorch (NVIDIA DLI)
- Agent security & prompt injection
- Quantum error correction
- Defence technology (minor)

</td>
<td valign="top" width="33%">

### 🎮 Interests

- Quantum computing
- Cybersecurity / CTFs
- Competitive programming
- Open source
- Music 🎵

</td>
</tr>
</table>

---

## 📊 GitHub Analytics

<p align="center">
  <img height="180" src="https://github-readme-stats.vercel.app/api?username=vishalacharya09&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=1f6feb&text_color=c9d1d9"/>
  <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=vishalacharya09&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&langs_count=8"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=vishalacharya09&theme=tokyonight&hide_border=true&background=0d1117" alt="GitHub Streak"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=vishalacharya09&theme=tokyo-night&hide_border=true&bg_color=0d1117&area=true" alt="Contribution graph"/>
</p>

---

## 🤝 Let's Connect

I'm happy to talk about quantum algorithms, post-quantum security, ML research, or collaborations and internships.

<div align="center">

<a href="https://linkedin.com/in/vishal-acharya"><img src="https://img.shields.io/badge/LinkedIn-Let's_Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:vishalacharya2108@gmail.com"><img src="https://img.shields.io/badge/Email-Drop_a_Message-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://github.com/vishalacharya09"><img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" /></a>

<br/><br/>

**"The quantum world doesn't follow your intuition, so build intuition for the quantum world."**

![Footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20,24,30&height=120&section=footer)

![Last Updated](https://img.shields.io/badge/Last%20Updated-October%202026-success?style=flat-square)

</div>
