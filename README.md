<div align="center">

<!-- HERO SECTION -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:0d1117&height=200&section=header&text=Vijay%20M&fontSize=60&fontColor=58a6ff&animation=fadeIn&fontAlignY=35&desc=Systems%20Engineer%20%E2%80%A2%20AI%20Architect%20%E2%80%A2%20Builder&descSize=18&descAlignY=55&descAlign=50"/>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vijay-m-7a0975346)&nbsp;
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:vijaym2k6@gmail.com)&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/vijaym2k6)

</div>

---

### About

I build **AI-powered systems** that move beyond demos into production reality.

My work focuses on **cognitive autonomy**, **real-time perception**, and **backend infrastructure** — with emphasis on safety, explainability, and systems that hold up under pressure.

Currently preparing for **Google Summer of Code 2026** and contributing to open-source developer tooling.

---

## Featured Systems

<table>
<tr>
<td width="50%" valign="top">

### 🧠 NAVIRA
**Cognitive Digital Autonomy Engine**

Converts ambiguous human intent into safe, explainable task execution through a reasoning-first pipeline.

`Python` `Azure` `LLMs` `Cosmos DB`

<details>
<summary><b>Architecture</b></summary>

```
User Intent
    │
    ▼
┌─────────────┐    ┌─────────────┐    ┌─────────────┐
│   Intent    │───▶│    Risk     │───▶│  Execution  │
│   Parser    │    │  Evaluator  │    │   Planner   │
└─────────────┘    └─────────────┘    └─────────────┘
                          │
                          ▼
              ┌───────────────────────┐
              │  Explainability Layer │
              └───────────────────────┘
```

**Key Features:**
- Reasoning transparency before action
- Risk-aware execution planning
- Full audit trail for all decisions
- Production-ready core architecture

</details>

[![View](https://img.shields.io/badge/View_Repository-161b22?style=flat-square)](https://github.com/vijaym2k6/NAVIRA)

</td>
<td width="50%" valign="top">

### 🛡️ DroneGuard-AI
**GPS Spoof Detection & Defense**

Multi-sensor fusion system that protects autonomous drones from GPS spoofing attacks through cross-validation.

`Python` `FastAPI` `React` `WebSocket`

<details>
<summary><b>Architecture</b></summary>

```
┌─────┐  ┌─────┐  ┌─────┐  ┌─────┐
│ GPS │  │ IMU │  │BARO │  │ VIO │
└──┬──┘  └──┬──┘  └──┬──┘  └──┬──┘
   │        │        │        │
   └────────┴────┬───┴────────┘
                 ▼
        ┌─────────────────┐
        │ Fusion Validator│
        │ Anomaly Detect  │
        └────────┬────────┘
                 ▼
   ┌─────────────────────────────┐
   │ ALERT │ OVERRIDE │ LOG ALL │
   └─────────────────────────────┘
```

**Key Features:**
- Real-time multi-source validation
- Autonomous safe-mode fallback
- Live WebSocket visualization
- Sensor disagreement scoring

</details>

[![View](https://img.shields.io/badge/View_Repository-161b22?style=flat-square)](https://github.com/vijaym2k6/DroneGuard-AI)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🖐️ Jarvis Neural Interface
**Gesture-Controlled 3D Visualization**

Hand gesture-driven exploration of neural network architectures in real-time 3D space.

`React` `Three.js` `MediaPipe` `WebGL`

<details>
<summary><b>Architecture</b></summary>

```
┌─────────────┐     ┌─────────────┐
│   Camera    │────▶│  MediaPipe  │
│    Feed     │     │   Hands     │
└─────────────┘     └──────┬──────┘
                           │
                           ▼
                   ┌─────────────┐
                   │   Gesture   │
                   │   Mapper    │
                   └──────┬──────┘
                          │
                          ▼
                  ┌──────────────┐
                  │  Three.js    │
                  │  3D Scene    │
                  └──────────────┘
```

**Gesture Controls:**
- ✋ Open Palm → Rotate View
- ✊ Closed Fist → Select Node
- 🤏 Pinch → Zoom
- 👆 Point → Inspect Layer

</details>

[![View](https://img.shields.io/badge/View_Repository-161b22?style=flat-square)](https://github.com/vijaym2k6/Jarvis-Neural-Interface-AI)

</td>
<td width="50%" valign="top">

### ♻️ WasteVision-AI
**Real-Time Waste Classification**

Computer vision pipeline for automated waste sorting using detection + persistent tracking.

`Python` `YOLOv8` `DeepSORT` `OpenCV`

<details>
<summary><b>Architecture</b></summary>

```
Video Frame
     │
     ▼
┌─────────────┐    ┌─────────────┐
│   YOLOv8    │───▶│  DeepSORT   │
│  Detection  │    │  Tracking   │
└─────────────┘    └──────┬──────┘
                          │
                          ▼
              ┌─────────────────────┐
              │  Classification     │
              │  + Persistence ID   │
              └─────────────────────┘
```

**Key Features:**
- Real-time object detection
- Persistent ID tracking across frames
- Multi-class waste categorization
- Optimized for embedded deployment

</details>

[![View](https://img.shields.io/badge/View_Repository-161b22?style=flat-square)](https://github.com/vijaym2k6/WasteVision-AI)

</td>
</tr>
</table>

---

## Technical Focus

<table>
<tr>
<td align="center" width="25%">
<img src="https://img.shields.io/badge/Backend-161b22?style=for-the-badge" alt="Backend"/>
<br/><br/>
<b>FastAPI</b> · <b>Flask</b><br/>
<b>Node.js</b> · <b>WebSocket</b>
</td>
<td align="center" width="25%">
<img src="https://img.shields.io/badge/AI%2FML-161b22?style=for-the-badge" alt="AI/ML"/>
<br/><br/>
<b>LLMs</b> · <b>YOLOv8</b><br/>
<b>TensorFlow</b> · <b>MediaPipe</b>
</td>
<td align="center" width="25%">
<img src="https://img.shields.io/badge/Infrastructure-161b22?style=for-the-badge" alt="Infrastructure"/>
<br/><br/>
<b>Docker</b> · <b>Azure</b><br/>
<b>Kubernetes</b> · <b>CI/CD</b>
</td>
<td align="center" width="25%">
<img src="https://img.shields.io/badge/Languages-161b22?style=for-the-badge" alt="Languages"/>
<br/><br/>
<b>Python</b> · <b>TypeScript</b><br/>
<b>JavaScript</b>
</td>
</tr>
</table>

<br/>

<details>
<summary><b>Engineering Philosophy</b></summary>

<br/>

| Principle | Practice |
|:----------|:---------|
| **Safety First** | Risk evaluation before execution. Systems fail gracefully. |
| **Explainability** | Every decision has a traceable reason. No black boxes in production. |
| **Reliability** | Code that survives edge cases, not just happy paths. |
| **Documentation** | If it's not documented, it doesn't exist. |

<br/>

```
build → break → understand → document → repeat
```

</details>

---

## Metrics

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=vijaym2k6&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9" alt="GitHub Stats"/>
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=vijaym2k6&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&langs_count=6" alt="Top Languages"/>

</div>

---

<div align="center">

### Let's Build Something

I'm interested in systems-level open source, AI safety, and developer infrastructure.

If you're working on something that needs to scale past demos, let's talk.

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vijay-m-7a0975346)&nbsp;&nbsp;
[![Email](https://img.shields.io/badge/vijaym2k6@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:vijaym2k6@gmail.com)

<br/>

<img src="https://komarev.com/ghpvc/?username=vijaym2k6&style=flat-square&color=161b22&labelColor=0d1117&label=visitors" alt="Profile Views"/>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:0d1117&height=100&section=footer"/>