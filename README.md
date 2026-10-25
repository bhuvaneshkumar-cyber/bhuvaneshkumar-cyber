<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:00c6ff&height=230&section=header&text=Bhuvanesh%20Kumar%20R&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Developer%20at%20Foxefy%20%7C%20Data%20Science%20at%20VIT%20Chennai&descAlignY=60&descSize=18&animation=fadeIn" width="100%"/>
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=3200&pause=1000&color=00C6FF&center=true&vCenter=true&width=700&height=45&lines=Building+AI+systems+that+leave+the+notebook;Cloud+infrastructure+and+vision-language+models+at+Foxefy;Computer+vision+%7C+LLM+applications+%7C+Deployment;Integrated+M.Tech+in+Data+Science+at+VIT+Chennai" alt="Introduction"/>
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/bhuvanesh-kumar-r/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:bhuvanesh200768@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/Chennai%2C_India-302b63?style=for-the-badge&logo=googlemaps&logoColor=white"/>
  <img src="https://komarev.com/ghpvc/?username=bhuvaneshkumar-cyber&style=for-the-badge&color=302b63&label=PROFILE+VIEWS"/>
</p>

<br/>

## About

I'm an Integrated M.Tech student in Computer Science and Engineering (Data Science) at VIT Chennai. I got into AI by building things rather than reading about them. Most of what I know came from hackathons, where an idea has to become a working prototype in 8 or 24 hours.

Along the way I realized the model is the easy part. What interests me is everything around it: the server it runs on, the pipeline that ships it, and the harness that lets an LLM actually do work. That is what I work on at **Foxefy**, a startup where I build cloud infrastructure and vision-language models.

<table>
<tr>
<td width="55%" valign="top">

**Experience**

| Role | Organization | Period |
|:--|:--|:--|
| Full-time Developer | [Foxefy](https://www.linkedin.com/company/foxefy/) | Sep 2026 – Present |
| Research Intern | Centre for Cyber Physical Systems, VIT Chennai | Summer 2026 |
| Member, AI/ML Department | Microsoft Innovations Club, VIT Chennai | Sep 2026 – Present |
| Member, Cloud & DevOps Department | GDG on Campus, VIT Chennai | Sep 2026 – Present |
| Member, PRO Team | Rotaract Club of VIT Chennai | Jul 2026 – Present |

</td>
<td width="45%" valign="top">

**Education**

**Vellore Institute of Technology, Chennai**<br/>
Integrated M.Tech, CSE (Data Science)<br/>
2025 – 2030 · CGPA 8

**Vidya Mandir, Chennai**<br/>
Higher Secondary (CBSE), Computer Science<br/>
2025 · 90.2%

**Certifications**<br/>
MongoDB: CRUD Operations<br/>
MongoDB: Indexing Design Fundamentals

</td>
</tr>
</table>

## Projects

### Computer Vision

<table>
<tr>
<td width="50%" valign="top">

#### [PoseGuard](https://github.com/bhuvaneshkumar-cyber/Posture-detection)
Real-time posture monitoring and correction for yoga and fitness.

- YOLO11-m person detection with RTMPose-m keypoints (SimCC decoding)
- 57-dimensional biomechanical features: joint angles, limb symmetry, center of mass
- GA-PQNet, a graph-attention network that scores posture quality with per-joint attention and uncertainty estimates
- ONNX inference at 30+ FPS on a Tesla T4, with CI on GitHub Actions

`PyTorch` `MMPose` `Ultralytics` `ONNX Runtime` `OpenCV`

</td>
<td width="50%" valign="top">

#### [AI Traffic Police](https://github.com/bhuvaneshkumar-cyber/AI-Traffic-CV-model)
Real-time traffic management and violation detection.

- YOLOv8 multi-class vehicle detection with ByteTrack persistent tracking
- Wrong-way and overspeed detection with snapshot evidence
- Bi-directional tripwire counting and traffic density heatmaps
- Live Streamlit dashboard for video feeds and alerts, with ONNX export

`Ultralytics` `Supervision` `OpenCV` `Shapely` `Streamlit`

</td>
</tr>
</table>

### LLM and Language Systems

<table>
<tr>
<td width="33%" valign="top">

#### [Real-Time Fact Checker](https://github.com/bhuvaneshkumar-cyber/Real-Time-Fact-Checker)
A Chrome extension that fact-checks what is being said while you watch.

- Reads YouTube captions, any tab's audio, or selected text
- Transcribes locally with Whisper and judges claims with a local LLM, with optional web search
- True, False, Misleading or Unverifiable verdicts with clickable timestamps

`Manifest V3` `FastAPI` `Ollama` `transformers.js`

</td>
<td width="33%" valign="top">

#### [ClinDoc AI](https://github.com/bhuvaneshkumar-cyber/SIH-Hackathon)
Ambient clinical documentation assistant built for Smart India Hackathon 2026.

- Streams consultation audio over WebSockets
- Extracts symptoms, diagnoses and medications with scispaCy and med7
- Generates HL7 FHIR R4 notes, with drug interaction checks and JWT auth

`React` `TypeScript` `FastAPI` `spaCy`

</td>
<td width="33%" valign="top">

#### [LLM Sandbox CTF](https://github.com/bhuvaneshkumar-cyber/LLMSandBOXCTF)
A prompt-injection capture-the-flag platform for hackathons and GDG events.

- An LLM persona guards a hidden flag that players try to extract
- Per-user rate limits, admin access control and an OpenRouter-to-Gemini fallback chain
- three.js interface, containerized and deployed on Render with PostgreSQL

`FastAPI` `SQLAlchemy` `three.js` `Docker`

</td>
</tr>
</table>

### Applied Machine Learning

<table>
<tr>
<td width="33%" valign="top">

#### [NUtri-INO](https://github.com/bhuvaneshkumar-cyber/NUtri-INO)
AI health ecosystem pitched at the I2X '26 Pitchathon.

- Gemini 2.5 Flash turns meal and pantry photos into structured macro data
- Gauss-Jordan elimination solves for exact macronutrient targets
- Linear-regression weight forecasts and Pearson-correlation lifestyle insights

`NiceGUI` `Flask` `Gemini API` `NumPy`

</td>
<td width="33%" valign="top">

#### [GigSave](https://github.com/bhuvaneshkumar-cyber/DataStorm)
Financial resilience platform for gig workers.

- Automatic micro-savings through round-ups and income smoothing
- Alternative credit score from a rule engine and RandomForest, explained with SHAP
- Scores income and volatility from uploaded PDF, CSV, Excel or Word statements

`FastAPI` `scikit-learn` `SHAP` `React` `Supabase`

</td>
<td width="33%" valign="top">

#### [Rhythm Anchor](https://github.com/bhuvaneshkumar-cyber/V-Vortex-)
Non-clinical mental well-being indicator built at the V-Vortex Hackathon.

- Stability Index from Isolation Forest anomaly detection and lifestyle factors
- Doomscroll detection from scroll velocity and time of day
- Conversational wellness coach powered by Gemini 2.5 Flash

`Streamlit` `scikit-learn` `Altair` `Gemini API`

</td>
</tr>
</table>

## Hackathons and Recognition

| Event | Organizer | Outcome | Date |
|:--|:--|:--|:--|
| Innovation Unbound '26 | CodeChef Club, VIT Chennai | 24-hour fintech hackathon at technoVIT '26; qualified for the final round | Aug 2026 |
| Bharatiya Antariksh Hackathon 2026 | ISRO | Participant | Jul 2026 |
| BLACKBOX CTF | CodeChef Club, VIT Chennai | Competed in a capture-the-flag security challenge | Jul 2026 |
| Samhita '26 Hackathon | MIT, Anna University | **2nd place**: privacy-preserving audit prototype for enterprise data compliance, built in 8 hours | Mar 2026 |
| Prayatna '26 Prayacthon | MIT, Anna University | VISION-ZERO, an Edge-AI prototype for privacy-safe fleet tracking under the DPDP Act; recognized by Tekion executives | Mar 2026 |
| Pythonix 2026 | CADS, VIT Chennai | **1st place** | Mar 2026 |
| I2X Pitchathon | SCOPE, VIT Chennai | Pitched NUtri-INO | Feb 2026 |
| V-Vortex Hackathon | SCOPE, VIT Chennai | Built Rhythm Anchor | Jan 2026 |
| GDG on Campus, Cloud & DevOps | GDG VIT Chennai | Selected in the top 5% of 3,000+ applicants | 2026 |

## Technical Skills

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,c,cpp,java,r,ts,js,html,css,pytorch,tensorflow,sklearn,opencv,fastapi,flask,django,react,vite,threejs,postgres,supabase,sqlite,mysql,mongodb,redis,cassandra,docker,githubactions,git,linux&perline=10" />
</p>

| Area | Tools and technologies |
|:--|:--|
| **Languages** | Python, C, C++, Java, R, SQL, TypeScript, JavaScript, HTML, CSS |
| **Machine Learning** | PyTorch, TensorFlow, scikit-learn, SHAP, Isolation Forest, Random Forest, regression and correlation analysis |
| **Computer Vision** | OpenCV, Ultralytics YOLOv8 and YOLO11, MMPose (RTMPose), MMDetection, Supervision (ByteTrack), ONNX, ONNX Runtime, Shapely |
| **LLMs and NLP** | Google Gemini API, Ollama, OpenRouter, OpenAI SDK, Whisper via transformers.js, spaCy, scispaCy, med7 |
| **Data and Visualization** | NumPy, Pandas, SciPy, SymPy, Matplotlib, Seaborn, Plotly, Altair, Recharts, TensorBoard |
| **Document Processing** | pdfplumber, PyMuPDF, python-docx, openpyxl, Tesseract OCR |
| **Backend and APIs** | FastAPI, Flask, Django, Uvicorn, Pydantic, SQLAlchemy, REST APIs, WebSockets, JWT |
| **Frontend** | React, Vite, three.js, anime.js, NiceGUI, Streamlit, Chrome Extensions (Manifest V3) |
| **Databases** | PostgreSQL, Supabase, SQLite, MySQL, Oracle SQL, MongoDB, Redis, Cassandra, HBase |
| **Big Data** | Hadoop (HDFS, MapReduce), Spark |
| **Cloud and DevOps** | Docker, Docker Compose, Render, GitHub Actions, Git, Linux, pytest |
| **Foundations** | Data Structures, Object-Oriented Programming, Operating Systems, Computer Networks, Computer Organization and Architecture, Linear Algebra |

## GitHub Activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=bhuvaneshkumar-cyber&show_icons=true&theme=tokyonight&hide_border=true&border_radius=10&count_private=true&include_all_commits=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=bhuvaneshkumar-cyber&layout=compact&theme=tokyonight&hide_border=true&border_radius=10" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=bhuvaneshkumar-cyber&theme=tokyonight&hide_border=true&border_radius=10&ring=00C6FF&fire=00C6FF&currStreakLabel=00C6FF" />
</p>

<!-- Contribution snake: generated by .github/workflows/snake.yml -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/bhuvaneshkumar-cyber/bhuvaneshkumar-cyber/output/github-snake-dark.svg" />
    <img alt="Contribution snake" src="https://raw.githubusercontent.com/bhuvaneshkumar-cyber/bhuvaneshkumar-cyber/output/github-snake.svg" />
  </picture>
</p>

## Get in Touch

I'm open to **research collaborations**, **internships** and **hackathon teams**, especially work involving computer vision, language models or cloud deployment.

<p align="center">
  <a href="https://www.linkedin.com/in/bhuvanesh-kumar-r/"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:bhuvanesh200768@gmail.com"><img src="https://img.shields.io/badge/Send_an_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00c6ff,50:302b63,100:0f0c29&height=110&section=footer" width="100%"/>
</p>
