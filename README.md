<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1f2e,100:0f3460&height=200&section=header&text=Savio%20%7C%20Gmax-13&fontSize=52&fontColor=58a6ff&animation=fadeIn&fontAlignY=38&desc=ML%20Engineer%20%7C%20Cybersecurity%20%7C%20Full-Stack%20Dev&descAlignY=58&descSize=18&descColor=8b949e" />
</p>

<p align="center">
  <a href="https://github.com/Gmax-13">
    <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=18&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&multiline=true&width=600&height=80&lines=Building+AI+that+protects+people+🛡️;ML+%2B+Cybersecurity+%2B+Full-Stack;Turning+ideas+into+deployable+systems+🚀" alt="Typing SVG" />
  </a>
</p>

---

<img align="right" alt="Coding" width="360" src="https://raw.githubusercontent.com/abhisheknaiidu/abhisheknaiidu/master/code.gif"/>

### 👾 About Me

```yaml
name: Savio
alias: Gmax-13
location: Mumbai, India 🇮🇳
role: Engineering Student

focus:
  - Machine Learning for Cybersecurity
  - Full-Stack Web Development
  - AI-Powered Systems

currently_building:
  - PhishGuard — AI phishing detection Chrome extension
  - ML ensemble models for real-world threat analysis

interests:
  - Applied ML & NLP
  - Security & Privacy Tech
  - System Design
  - Creative Modding Projects
```

<br clear="right"/>

---

### 🧰 Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white"/>
</p>
<p align="left">
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white"/>
</p>
<p align="left">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white"/>
  <img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
</p>

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Gmax-13&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9&include_all_commits=true&count_private=true" width="48%" alt="GitHub Stats"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Gmax-13&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=58a6ff&ring=58a6ff&fire=ff7b72&currStreakLabel=58a6ff" width="48%" alt="GitHub Streak"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Gmax-13&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&langs_count=8" width="48%" alt="Top Languages"/>
  <img src="https://github-profile-trophy.vercel.app/?username=Gmax-13&theme=algolia&no-bg=true&no-frame=true&column=4&margin-w=8" width="48%" alt="Trophies"/>
</p>

---

### 🐍 Contribution Snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Gmax-13/Gmax-13/output/github-contribution-grid-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Gmax-13/Gmax-13/output/github-contribution-grid-snake.svg"/>
    <img alt="Snake animation" src="https://raw.githubusercontent.com/Gmax-13/Gmax-13/output/github-contribution-grid-snake.svg"/>
  </picture>
</p>

> **Note:** To enable the snake animation, add the GitHub Action below to your repo at `.github/workflows/snake.yml`

<details>
<summary>🔧 Snake GitHub Action Setup</summary>

```yaml
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    timeout-minutes: 5

    steps:
      - name: Generate snake SVG
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

</details>

---

### 🔬 Projects

| Repository | Description | Stack |
|------------|-------------|-------|
| 🛡️ **[PhishGuard](https://github.com/Gmax-13/PhishGuard)** | Ensemble-based phishing email detection Chrome extension | JavaScript |
| ⚙️ **[Phishguard-backend](https://github.com/Gmax-13/Phishguard-backend)** | Flask backend powering the PhishGuard inference pipeline | Python |
| 🔍 **[prior-art-search](https://github.com/Gmax-13/prior-art-search)** | Patent prior art search tool for feasibility analysis | Python |
| 🏥 **[Interpro_WEBdev_team-4](https://github.com/Gmax-13/Interpro_WEBdev_team-4)** | Internship project — Clinic Appointment Website | JavaScript |
| 💊 **[HealthHorizon](https://github.com/Gmax-13/HealthHorizon)** | 2nd Year Mini Project | CSS |
| 🪟 **[My_Portfolio](https://github.com/Gmax-13/My_Portfolio)** | My Status Window...A Peek into my Existence | — |

---

### 📈 Activity Graph

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Gmax-13&bg_color=0d1117&color=58a6ff&line=1f6feb&point=58a6ff&area=true&area_color=1f6feb&hide_border=true" width="95%" alt="Activity Graph"/>
</p>

---

### 🤝 Connect

<p align="center">
  <a href="https://github.com/Gmax-13">
    <img src="https://img.shields.io/badge/GitHub-Gmax--13-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  <a href="https://huggingface.co/savizzz-35">
    <img src="https://img.shields.io/badge/HuggingFace-savizzz--35-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Gmax-13&label=Profile+Views&color=58a6ff&style=for-the-badge" alt="Profile Views"/>
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f3460,50:1a1f2e,100:0d1117&height=120&section=footer&text=Keep+Building.+Keep+Breaking.+Keep+Shipping.&fontSize=16&fontColor=8b949e&animation=fadeIn&fontAlignY=65" />
</p>
