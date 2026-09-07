<table align="center" border="0" frame="void" rules="none" style="border: none; border-collapse: collapse; border-spacing: 0;">
  <tr>
    <td valign="middle" width="60%" style="border: none; border-style: none;">
      <h1 style="font-size: 6%; line-height: 1.1; margin: 0;">Muhammad Saad Ahmed</h1>
      <h3 style="font-size: 28px; margin-top: 12px; font-weight: 500;">AI Automation Engineer</h3>
    </td>
    <td align="right" valign="middle" width="40%" style="border: none; border-style: none;">
      <img src="https://github.com/saadUmmati/saadUmmati/blob/main/saad.jpg" width="420" alt="Muhammad Saad Ahmed"/>
    </td>
  </tr>
</table>

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

## TECH STACK

### 👨‍💻 Languages
<br/>
<table align="center">
    <tr>
        <td align="center" width="90">
            <img src="https://skillicons.dev/icons?i=kotlin&theme=dark" alt="icon" width="65" height="65" />
            <br>Kotlin
        </td>        
        <td align="center" width="90">
            <img src="https://techstack-generator.vercel.app/cpp-icon.svg" alt="icon" width="65" height="65" />
            <br>CPP
        </td>        
        <td align="center" width="90">
            <img src="https://techstack-generator.vercel.app/python-icon.svg" alt="icon" width="65" height="65" />
            <br>Python
        </td>
        <td align="center" width="90">
            <img src="https://techstack-generator.vercel.app/js-icon.svg" alt="icon" width="65" height="65" />
            <br>JavaScript
        </td>
        <td align="center" width="90">
            <img src="https://techstack-generator.vercel.app/java-icon.svg" alt="icon" width="65" height="65" />
            <br>Java
        </td>
    </tr>
</table>

### 🧠 AI / ML
<br/>
<table align="center">
    <tr>
        <td align="center" width="90">
            <img src="https://hdrobots.com/wp-content/uploads/2025/01/yolo-logo.svg" width="48" height="48" alt="PyTorch" />
            <br>Yolo
        </td>
        <td align="center" width="90">
            <img src="https://storage.googleapis.com/kaggle-organizations/3837/thumbnail-2.png" width="48" height="48" alt="PyTorch" />
            <br>Dinov2
        </td>        
        <td align="center" width="90">
            <img src="https://files.svgcdn.io/simple-icons/onnx.png" width="48" height="48" alt="PyTorch" />
            <br>ONNX
        </td>
        <td align="center" width="90">
            <img src="https://skillicons.dev/icons?i=pytorch" width="48" height="48" alt="PyTorch" />
            <br>PyTorch
        </td>
        <td align="center" width="90">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/scikitlearn/scikitlearn-original.svg" width="48" height="48" alt="scikit-learn" />
            <br>Scikit-Learn
        </td>
        <td align="center" width="90">
            <img src="https://skillicons.dev/icons?i=opencv" width="48" height="48" alt="OpenCV" />
            <br>OpenCV
        </td>
        <td align="center" width="90">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" width="48" height="48" alt="NumPy" />
            <br>NumPy
        </td>
        <td align="center" width="90">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width="48" height="48" alt="Pandas" />
            <br>Pandas
        </td>
        <td align="center" width="90">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matplotlib/matplotlib-original.svg" width="48" height="48" alt="Matplotlib" />
            <br>Matplotlib
        </td>
              <td align="center" width="90">
            <img src="https://skillicons.dev/icons?i=fastapi" width="48" height="48" alt="FastAPI" />
            <br>FastAPI
        </td>
        <td align="center" width="90">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/streamlit/streamlit-original.svg" width="48" height="48" alt="Streamlit" />
            <br>Streamlit
        </td>
    </tr>
</table>

### 🗄️ Databases
<br/>
<table align="center">
    <tr>
        <td align="center" width="90">
            <img src="https://techstack-generator.vercel.app/mysql-icon.svg" alt="icon" width="65" height="65" />
            <br>MySQL
        </td>
        <td align="center" width="90">
            <img src="https://skillicons.dev/icons?i=mongodb" width="48" height="48" alt="MongoDB" />
            <br>MongoDB
        </td>
        <td align="center" width="90">
            <img src="https://skillicons.dev/icons?i=sqlite" width="48" height="48" alt="SQLite" />
            <br>SQLite
        </td>
        <td align="center" width="90">
            <img src="https://skillicons.dev/icons?i=supabase" width="48" height="48" alt="Postgres" />
            <br>Supabase
        </td>
              <td align="center" width="90">
            <img src="https://skillicons.dev/icons?i=firebase" width="48" height="48" alt="Postgres" />
            <br>Firebase
        </td>
    </tr>
</table>

### ☁️ Cloud & DevOps
<br/>
<table align="center">
    <tr>
        <td align="center" width="90">
            <img src="https://techstack-generator.vercel.app/aws-icon.svg" alt="icon" width="65" height="65" />
            <br>AWS
        </td>
        <td align="center" width="90">
            <img src="https://skillicons.dev/icons?i=vercel" width="48" height="48" alt="Vercel" />
            <br>Vercel
        </td>
        <td align="center" width="90">
            <img src="https://skillicons.dev/icons?i=googlecloud" width="48" height="48" alt="Netlify" />
            <br>Google Cloud
        </td>
    </tr>
</table>

### 🧰 Tools
<br/>
<table align="center">
    <tr>
        <td align="center" width="90">
            <img src="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/dark/n8n.png" width="48" height="48" alt="PyTorch" />
            <br>n8n
        </td>
        <td align="center" width="90">
            <img src="https://www.kaggle.com/static/images/site-logo.svg" width="48" height="48" alt="Git" />
            <br>Kaggle
        </td>
        <td align="center" width="90">
            <img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" width="48" height="48" alt="Git" />
            <br>HuggingFace
        </td>
        <td align="center" width="90">
            <img src="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/dark/lovable-color.png" width="48" height="48" alt="Git" />
            <br>Lovable
        </td>
        <td align="center" width="90">
            <img src="https://svgstack.com/media/img/bolt-ai-logo-uEH0165212.webp" width="48" height="48" alt="Git" />
            <br>Blot.new
        </td>
        <td align="center" width="90">
            <img src="https://media.licdn.com/dms/image/v2/D560BAQG5wmEaqHfmDg/company-logo_400_400/B56ZqUSJh0I4Ac-/0/1763424377586/google_antigravity_logo?e=1790208000&v=beta&t=OutwEZGfq8XXKBc8Y6jJxobtqg1ZGrt4DeX8O2zW_WM" width="48" height="48" alt="Git" />
            <br>AntiGravity
        </td>  
      <td align="center" width="90">
            <img src="https://thumb.wikimedia.org/wikipedia/commons/thumb/b/b0/Claude_AI_symbol.svg/1280px-Claude_AI_symbol.svg.png" width="48" height="48" alt="Git" />
            <br>Claude
        </td>
        <td align="center" width="90">
            <img src="https://skillicons.dev/icons?i=git" width="48" height="48" alt="Git" />
            <br>Git
        </td>
        <td align="center" width="90">
            <img src="https://skillicons.dev/icons?i=github" width="48" height="48" alt="GitHub" />
            <br>GitHub
        </td>
        <td align="center" width="90">
            <img src="https://assets.streamlinehq.com/image/private/w_300,h_300,ar_1/f_auto/v1/icons/logos/langchain-ipuhh4qo1jz5ssl4x0g2a.png/langchain-dp1uxj2zn3752pntqnpfu2.png?_a=DATAiZAAZAA0" width="48" height="48" alt="Postman" />
            <br>LangChain
        </td>
    </tr>
</table>


---

## GitHub Analytics

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=saadummati&theme=dracula" alt="Profile Summary"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=saadummati&hide_border=true&background=000000&ring=27152B&fire=FFFFFF&currStreakLabel=FFFFFF&sideLabels=FFFFFF&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=27152B" alt="GitHub Streak" height="165"/>
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
