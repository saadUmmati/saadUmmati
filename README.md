<p align="center">
  <img src="https://github.com/saadummati.png" width="140" alt="Muhammad Saad Ahmed"/>
</p>

<h1 align="center">Muhammad Saad Ahmed</h1>
<h3 align="center">AI Automation Engineer</h3>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&duration=2800&pause=900&color=FFFFFF&background=27152BFF&center=true&vCenter=true&width=620&height=50&lines=I+build+agents+that+reason%2C+act+%26+ship;n8n+%C2%B7+LangChain+%C2%B7+On-Device+ML+%C2%B7+Android" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AI%20Engineer-HashDev%20Solutions-27152B?style=for-the-badge&labelColor=000000&logoColor=FFFFFF"/>
  <img src="https://img.shields.io/badge/Co--Founder%20%26%20COO-SHS%20Creators-27152B?style=for-the-badge&labelColor=000000&logoColor=FFFFFF"/>
  <img src="https://img.shields.io/badge/Certified-Google%20PMLE%20%7C%20AWS%20ML%20Specialty-27152B?style=for-the-badge&labelColor=000000&logoColor=FFFFFF"/>
</p>

<p align="center">
  <a href="https://saadai.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=FFFFFF"/></a>
  <a href="https://www.linkedin.com/in/muhammadsaadahmed"><img src="https://img.shields.io/badge/LinkedIn-000000?style=for-the-badge&logo=linkedin&logoColor=FFFFFF"/></a>
  <a href="mailto:msaadisiddiqui@gmail.com"><img src="https://img.shields.io/badge/Email-000000?style=for-the-badge&logo=gmail&logoColor=FFFFFF"/></a>
  <a href="https://github.com/saadummati"><img src="https://img.shields.io/github/followers/saadummati?label=Follow&style=for-the-badge&color=27152B&labelColor=000000&logo=github&logoColor=FFFFFF"/></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=saadummati&label=Profile%20Views&color=27152B&style=for-the-badge&labelColor=000000" alt="Profile Views"/>
</p>

<br/>

## About Me

```python
class SaadAhmed:
    def __init__(self):
        self.role              = "AI Automation Engineer @ HashDev Solutions"   # since Jul 2026
        self.also              = "Co-Founder & COO @ SHS Creators"
        self.education          = "BSCS, National University of Technology"     # graduated Jun 2025
        self.certifications    = ["Google Professional ML Engineer", "AWS ML Specialty"]
        self.prior              = "AI Systems Engineer Intern @ CloudGate Technologies"  # Mar–Jul 2026
        self.based_in            = "Wah Cantt, Pakistan"
        self.open_to             = "Full-time remote AI/ML Engineering roles — US · UK · EU"

    def what_i_do(self):
        return (
            "Design agentic pipelines that call tools, chain reasoning steps, "
            "and automate real business workflows — then take that same rigor "
            "onto Android, shipping ML models that run fully on-device."
        )

saad = SaadAhmed()
```

Two threads run through everything I build: **agentic automation** — pipelines that don't just answer, they act — and **on-device intelligence** — running real ML models on a phone with no server in the loop.

### Currently Building
- Agentic AI pipelines with **n8n + LangChain + OpenAI API** for Google Workspace, education-sector, and lead-gen automations at HashDev
- On-device semantic clustering for Android using **DINOv2 + CLIP embeddings**
- Growing **SHS Creators** as Co-Founder/COO alongside the day job

---

## Flagship Work

<details open>
<summary><b>ClipGallery — On-Device Semantic Photo Clustering (Android)</b></summary>
<br/>

A native Android gallery app that groups photos by what's in them — entirely on-device, no cloud calls.

- **Problem:** stock gallery apps sort by date/folder only; semantic grouping usually means shipping photos to a server.
- **What I built:** a Kotlin/XML app on MVVM, using **DINOv2-small (ONNX, INT8-quantized)** to embed images on-device, then clustering with **average-linkage** (moved off single-linkage after it produced degenerate mega-clusters). Cluster labels are generated automatically using **CLIP text embeddings** matched against the visual centroid.
- **Hard parts:** a null-centroid persistence bug was silently breaking incremental re-clustering on relaunch; threshold calibration needed real tuning since a fixed distance cutoff clustered very differently across photo libraries; scoped-storage deletion had to work correctly from API 21 through 34.
- **Also shipped:** a 30-day recycle bin before permanent deletion.
- **Stack:** `Kotlin` · `XML` · `MVVM` · `ONNX Runtime` · `DINOv2` · `CLIP` · `WorkManager` · `Hilt`

</details>

<details open>
<summary><b>HashDev Agentic Automations — Production AI Workflows</b></summary>
<br/>

At HashDev Solutions (AI/software company across Pakistan, US, and UK — SaaS, AI automation, RAG, LLM agents), I build the agent layer that turns LLM output into completed business tasks.

- **What I build:** agentic pipelines combining **n8n**, **LangChain**, and the **OpenAI API** — Google Workspace automation, education-sector tooling (auto-generated quizzes, research task automation), lead-generation systems, marketing automation, and recurring daily business-task automation.
- **Why it matters:** every pipeline calls real tools and produces a real side effect — a doc gets created, a lead gets scored and routed, a quiz gets generated and delivered.
- **Stack:** `n8n` · `LangChain` · `OpenAI API` · `Google Workspace APIs`

</details>

<details open>
<summary><b>RUHEA — AI Virtual Try-On for E-Commerce (MERN)</b></summary>
<br/>

An AI-assisted e-commerce platform for Ruhea Scents and Fragrances with a live virtual try-on system.

- **What I built:** integrated **CATVTON**, a virtual try-on diffusion model, directly into a live MERN storefront, letting shoppers preview products on themselves before buying.
- **Outcome:** contributed to **60% faster feature delivery** on the platform.
- **Stack:** `MongoDB` · `Express` · `React` · `Node.js` · `CATVTON`

</details>

<details open>
<summary><b>YOLOv8 Helmet Detection — Computer Vision Safety Model</b></summary>
<br/>

A custom-trained YOLOv8 object detection model for identifying helmet compliance from image/video input.

- **What I built:** trained and tuned a YOLOv8 model for helmet detection, from data prep through inference.
- **Stack:** `YOLOv8` · `Python` · `OpenCV`

</details>

---

## Tech Stack

**Languages**

<p align="left"><img src="https://skillicons.dev/icons?i=python,kotlin,js&theme=dark" /></p>

**AI · Agentic Automation**

<p align="left">
  <img src="https://img.shields.io/badge/n8n-27152B?style=for-the-badge&logo=n8n&logoColor=FFFFFF"/>
  <img src="https://img.shields.io/badge/LangChain-27152B?style=for-the-badge&logoColor=FFFFFF"/>
  <img src="https://img.shields.io/badge/OpenAI%20API-27152B?style=for-the-badge&logo=openai&logoColor=FFFFFF"/>
  <img src="https://img.shields.io/badge/Hugging%20Face-27152B?style=for-the-badge&logoColor=FFFFFF"/>
</p>

**On-Device ML & Computer Vision**

<p align="left">
  <img src="https://img.shields.io/badge/ONNX%20Runtime-27152B?style=for-the-badge&logo=onnx&logoColor=FFFFFF"/>
  <img src="https://img.shields.io/badge/YOLOv8-27152B?style=for-the-badge&logoColor=FFFFFF"/>
  <img src="https://img.shields.io/badge/DINOv2-27152B?style=for-the-badge&logoColor=FFFFFF"/>
  <img src="https://img.shields.io/badge/CLIP-27152B?style=for-the-badge&logoColor=FFFFFF"/>
  <img src="https://skillicons.dev/icons?i=opencv&theme=dark" />
</p>

**Web & App Development**

<p align="left"><img src="https://skillicons.dev/icons?i=react,nodejs,express,fastapi,mongodb,androidstudio&theme=dark" /></p>

**Cloud & Tools**

<p align="left">
  <img src="https://skillicons.dev/icons?i=git,github,vercel,postman,figma&theme=dark" />
  <img src="https://img.shields.io/badge/Render-27152B?style=for-the-badge&logo=render&logoColor=FFFFFF"/>
</p>

---

## GitHub Analytics

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=saadummati&theme=dracula" alt="Profile Summary"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=saadummati&show_icons=true&hide_border=true&bg_color=000000&title_color=FFFFFF&icon_color=27152B&text_color=FFFFFF&border_color=27152B&rank_icon=github" alt="GitHub Stats" height="165"/>
  <img src="https://streak-stats.demolab.com/?user=saadummati&hide_border=true&background=000000&ring=27152B&fire=FFFFFF&currStreakLabel=FFFFFF&sideLabels=FFFFFF&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=27152B" alt="GitHub Streak" height="165"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=saadummati&bg_color=000000&color=FFFFFF&line=27152B&point=FFFFFF&area=true&hide_border=true" alt="Activity Graph" width="90%"/>
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=saadummati&theme=dracula&no-frame=true&row=1&column=7&margin-w=8" alt="Trophies"/>
</p>

---

## Contribution Calendar, in 3D

<p align="center">
  <img src="https://raw.githubusercontent.com/saadummati/saadummati/main/profile-3d-contrib/profile-night-green.svg" alt="3D Contribution Graph"/>
</p>

---

## My AI Agent, Automating My Commit History

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/saadummati/saadummati/output/pacman-contribution-graph-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/saadummati/saadummati/output/pacman-contribution-graph.svg">
    <img alt="Pac-Man contribution graph" src="https://raw.githubusercontent.com/saadummati/saadummati/output/pacman-contribution-graph-dark.svg">
  </picture>
</p>

---

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark&quote=The%20future%20isn't%20AI%20that%20just%20thinks.%20It's%20AI%20that%20thinks%2C%20acts%2C%20and%20automates.&author=Muhammad+Saad+Ahmed" alt="Quote"/>
</p>

<h3 align="center">Let's Connect</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/muhammadsaadahmed"><img src="https://img.shields.io/badge/Connect%20on%20LinkedIn-000000?style=for-the-badge&logo=linkedin&logoColor=FFFFFF"/></a>
  <a href="mailto:msaadisiddiqui@gmail.com"><img src="https://img.shields.io/badge/Say%20Hello-000000?style=for-the-badge&logo=gmail&logoColor=FFFFFF"/></a>
  <a href="https://saadai.vercel.app/"><img src="https://img.shields.io/badge/View%20Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=FFFFFF"/></a>
</p>

<p align="center"><b>Crafted with precision, automated with passion.</b></p>
