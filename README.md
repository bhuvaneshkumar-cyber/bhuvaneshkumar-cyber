<!-- ░░ HERO ░░ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=venom&color=0:0f0c29,50:302b63,100:00c6ff&height=260&section=header&text=Bhuvanesh%20Kumar%20R&fontSize=56&fontColor=ffffff&fontAlignY=38&desc=Vision%20%C3%97%20Language%20%C3%97%20Cloud&descAlignY=60&descSize=20&animation=fadeIn&stroke=00c6ff&strokeWidth=1" width="100%"/>
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2800&pause=900&color=00C6FF&center=true&vCenter=true&width=680&height=50&lines=%3E+loading+model%3A+bhuvanesh-kumar-r+...;Teaching+machines+to+see%2C+read+and+ship;Developer+%40+Foxefy+%E2%80%94+Vision-Language+Models;Integrated+M.Tech+Data+Science+%40+VIT+Chennai;Models+belong+in+products%2C+not+notebooks." alt="typing intro"/>
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/bhuvanesh-kumar-r/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:bhuvanesh200768@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/status-open_to_internships-00c6ff?style=for-the-badge&labelColor=302b63"/>
  <img src="https://komarev.com/ghpvc/?username=bhuvaneshkumar-cyber&style=for-the-badge&color=302b63&label=VIEWS"/>
</p>

<p align="center">
  <i>I build AI that leaves the notebook: models that watch posture, catch traffic violations,<br/>
  fact-check videos as they play and write up clinical notes, then I deploy them to the cloud.</i>
</p>

<br/>

<!-- ░░ MODEL CARD + BENCHMARKS ░░ -->
<table>
<tr>
<td width="56%" valign="top">

<h3>🧬 Model Card</h3>
<sub><i>if I were on the Hub, this is the card you'd read</i></sub>

```yaml
model_id:      bhuvanesh-kumar-r
version:       2026.10  # still fine-tuning
architecture:  data-scientist ⊕ full-stack-builder
base_model:    Integrated M.Tech · Data Science
               @ VIT Chennai
fine_tuned_on:
  - Vision-Language Models   # Developer @ Foxefy
  - Cyber-physical systems   # Research Intern @ CCPS
  - 10+ hackathons
modalities:    [vision, language, cloud]
communities:
  - AI/ML     @ Microsoft Innovations Club
  - Cloud & DevOps @ GDG on Campus
  - Rotaract
intended_use:
  - AI/ML & full-stack internships
  - research collaborations
  - hackathon teams
known_limitations:
  - cannot ignore a hackathon sign-up form
```

</td>
<td width="44%" valign="top">

<h3>🏆 Benchmarks</h3>
<sub><i>evaluated on real leaderboards</i></sub>

| Eval | Score |
|:--|:--:|
| **Pythonix 2026** | 🥇 1st |
| **Samhita'26** @ MIT | 🥈 2nd + cash prize |
| **GDG** Cloud & DevOps | Top 5% of 3,000+ |
| **CCPS** Research | Intern '26 |
| ISRO Bharatiya Antariksh Hackathon | ✔ competed |
| BLACKBOX CTF | ✔ competed |
| I2X '26 Pitchathon | ✔ pitched |
| MongoDB Skill Badge | ✔ CRUD |

<sub>🥈 Samhita: a privacy-preserving audit prototype for enterprise data compliance and third-party auditing, designed and deployed in an 8-hour sprint.</sub>

</td>
</tr>
</table>

<!-- ░░ PROJECTS ░░ -->
<h2 align="center">🧪 Multimodal Outputs</h2>
<p align="center"><sub><i>things I've shipped, sorted by how they perceive the world</i></sub></p>

<h3>👁️ It sees</h3>
<table>
<tr>
<td width="50%" valign="top">

#### [PoseGuard](https://github.com/bhuvaneshkumar-cyber/Posture-detection)
Real-time posture correction for yoga and fitness.

- YOLO11-m + RTMPose-m keypoints → 57-D biomechanical features
- **GA-PQNet**: a graph-attention posture-quality net with per-joint explainability and uncertainty
- ONNX pipeline at 30+ FPS on a Tesla T4

`PyTorch` `RTMPose` `YOLO11` `ONNX`

</td>
<td width="50%" valign="top">

#### [AI Traffic Police](https://github.com/bhuvaneshkumar-cyber/AI-Traffic-CV-model)
End-to-end traffic monitoring and violation detection.

- YOLOv8 detection + ByteTrack persistent IDs
- Wrong-way and overspeed detection, tripwire counts, density heatmaps
- Live Streamlit control dashboard

`YOLOv8` `ByteTrack` `OpenCV` `Streamlit`

</td>
</tr>
</table>

<h3>💬 It reads, listens & talks</h3>
<table>
<tr>
<td width="33%" valign="top">

#### [Real-Time Fact Checker](https://github.com/bhuvaneshkumar-cyber/Real-Time-Fact-Checker)
A Chrome extension that fact-checks what's said *while you watch*.

- YouTube captions, any tab's audio, or selected text
- Whisper in the browser, Llama on your machine. Nothing leaves it.
- True / False / Misleading verdicts with clickable timestamps

`Ollama` `transformers.js` `FastAPI`

</td>
<td width="33%" valign="top">

#### [ClinDoc AI](https://github.com/bhuvaneshkumar-cyber/SIH-Hackathon)
Ambient clinical documentation, a prototype for SIH 2026.

- Listens to doctor–patient talk and extracts symptoms, diagnoses and medications
- Writes FHIR-compliant notes, discharge summaries and prescriptions
- Drug–drug interaction safety layer

`React` `FastAPI` `scispaCy` `WebSockets`

</td>
<td width="33%" valign="top">

#### [LLM Sandbox CTF](https://github.com/bhuvaneshkumar-cyber/LLMSandBOXCTF)
*Vault Keeper*: talk an LLM out of its secret flag.

- Prompt-injection challenge for GDG and hackathon events
- Guardrails, rate limits and an LLM provider fallback chain
- three.js console, deployed on Render

`FastAPI` `three.js` `TypeScript`

</td>
</tr>
</table>

<h3>📈 It thinks in numbers</h3>
<table>
<tr>
<td width="33%" valign="top">

#### [NUtri-INO](https://github.com/bhuvaneshkumar-cyber/NUtri-INO)
An AI health dashboard, pitched at I2X '26.

- Meal and pantry scanning with Gemini 2.5 Flash
- A Gauss-Jordan optimizer that hits exact macro targets
- Weight forecasts and Pearson lifestyle insights

`Gemini` `NiceGUI` `Flask`

</td>
<td width="33%" valign="top">

#### [GigSave](https://github.com/bhuvaneshkumar-cyber/DataStorm)
Financial resilience for gig workers.

- Auto micro-savings and income smoothing
- An alternative credit score from RandomForest, explained with SHAP
- Upload a statement and get your income and volatility scored

`scikit-learn` `SHAP` `FastAPI` `Supabase`

</td>
<td width="33%" valign="top">

#### [Rhythm Anchor](https://github.com/bhuvaneshkumar-cyber/V-Vortex-)
A non-clinical well-being indicator, built at V-Vortex.

- A Stability Index from IsolationForest anomaly detection
- Doomscroll detection from scroll velocity and time of day
- A Gemini wellness coach

`Streamlit` `scikit-learn` `Altair`

</td>
</tr>
</table>

<!-- ░░ STACK ░░ -->
<h2 align="center">🛠️ The Weights</h2>
<p align="center"><sub><i>the tools my parameters were trained on</i></sub></p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,opencv,sklearn,fastapi,flask,react,vite,ts,js,threejs,mongodb,postgres,mysql,docker,gcp,linux,git&perline=9" />
</p>

<div align="center">

| 👁️ Vision | 💬 Language | 🧮 ML & Data | ☁️ Ship it |
|:---:|:---:|:---:|:---:|
| YOLOv8 · YOLO11 | Gemini API · Ollama | scikit-learn · SHAP | FastAPI · Flask |
| RTMPose · ByteTrack | Whisper · transformers.js | NumPy · Pandas | Streamlit · NiceGUI |
| OpenCV · ONNX | scispaCy · med7 | IsolationForest · RandomForest | WebSockets · Docker · GCP |

</div>

<!-- ░░ TRAINING LOG ░░ -->
<h2 align="center">📉 Training Log</h2>
<p align="center"><sub><i>loss going down, skills going up</i></sub></p>

```bash
$ python train.py --model bhuvanesh-kumar-r --epochs ∞

Epoch 2025  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━  init
  └─ VIT Chennai .................. Integrated M.Tech (Data Science)

Epoch 2026  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━  lr ↑  loss ↓
  ├─ V-Vortex Hackathon ........... shipped Rhythm Anchor
  ├─ I2X Pitchathon ............... pitched NUtri-INO
  ├─ Pythonix ..................... 1st place          ★
  ├─ Samhita'26 @ MIT ............. 2nd place + cash   ★
  ├─ CCPS ......................... research internship
  ├─ ISRO BAH · BLACKBOX CTF ...... competed
  ├─ Innovation Unbound ........... 24-hour hackathon
  ├─ MIC · GDG · Rotaract ......... joined
  └─ Foxefy ....................... developer · Cloud + VLMs

[checkpoint saved]  now training on → vision-language models + cloud
```

<!-- ░░ TELEMETRY ░░ -->
<h2 align="center">📊 Telemetry</h2>

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=bhuvaneshkumar-cyber&show_icons=true&theme=tokyonight&hide_border=true&border_radius=12&count_private=true&include_all_commits=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=bhuvaneshkumar-cyber&layout=compact&theme=tokyonight&hide_border=true&border_radius=12" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=bhuvaneshkumar-cyber&theme=tokyonight&hide_border=true&border_radius=12&ring=00C6FF&fire=00C6FF&currStreakLabel=00C6FF" />
</p>

<!-- Contribution snake: generated by .github/workflows/snake.yml -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/bhuvaneshkumar-cyber/bhuvaneshkumar-cyber/output/github-snake-dark.svg" />
    <img alt="contribution snake" src="https://raw.githubusercontent.com/bhuvaneshkumar-cyber/bhuvaneshkumar-cyber/output/github-snake.svg" />
  </picture>
</p>

<!-- ░░ CONTACT ░░ -->
<h2 align="center">📡 Inference Endpoint</h2>

```python
>>> bhuvanesh.predict("Got a problem involving vision, language, or the cloud?")
"Yes. Let's build it."
```

<p align="center">
  Open to <b>AI/ML & full-stack internships</b>, <b>research collaborations</b> and <b>hackathon teams</b>.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/bhuvanesh-kumar-r/"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:bhuvanesh200768@gmail.com"><img src="https://img.shields.io/badge/Send_a_request-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00c6ff,50:302b63,100:0f0c29&height=120&section=footer" width="100%"/>
</p>
