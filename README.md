<div align="center">

<!-- Visitor Counter -->
<img src="https://komarev.com/ghpvc/?username=Abilash-Kumar18&label=Profile%20Views&color=7DF9FF&style=for-the-badge" alt="profile views" />

<!-- Space Header -->
<img src="https://capsule-render.vercel.app/api?type=waving&height=220&text=Abilash%20Kumar&fontAlign=50&fontAlignY=40&color=0:0f0c29,50:302b63,100:24243e&fontColor=E0E7FF&desc=Building%20Ideas%20Across%20the%20Galaxy%20🚀&descAlign=50&descAlignY=65" width="100%" />

<!-- Typing animation -->
<img src="https://readme-typing-svg.demolab.com?font=Orbitron&weight=600&size=24&duration=3000&pause=800&color=7DF9FF&center=true&vCenter=true&width=900&lines=Full+Stack+Developer+%F0%9F%9A%80;AI+%26+Automation+Enthusiast+%F0%9F%A4%96;Crafting+Modern+Web+Experiences+%E2%9C%A8;Always+Learning%2C+Always+Building+%F0%9F%8C%9F" alt="Typing Animation" />

</div>

---

## 🌌 About Me

<img src="https://media.giphy.com/media/3o7TKsQ8UQ9wL4yNxe/giphy.gif" width="100%" height="220"/>

- 🔭 Building modern web apps and AI-powered products  
- 🌱 Learning advanced full-stack systems, automation & agents  
- 🧠 Love solving real-world problems with clean UX  
- 📫 Reach me at **[abilaashkumar578@gmail.com](mailto:abilaashkumar578@gmail.com)**

---

## 🌠 Top Projects (Mission Log)

<img src="https://media.giphy.com/media/l0HlBO7eyXzSZkJri/giphy.gif" width="100%" height="200"/>

### 1) 🛰️ Portfolio Website
- 🔗 Live: [my-portfolio-theta-plum-8uceafob31.vercel.app](https://my-portfolio-theta-plum-8uceafob31.vercel.app/)
- 📦 Repo: [Abilash-Kumar18/my-portfolio](https://github.com/Abilash-Kumar18/my-portfolio)
- 🧩 Stack: React, Vite, CSS Modules

### 2) 🤖 Innovix HR Agent
- AI-powered HR assistant for workflow automation and support.

### 3) 🎫 College Event Management
- Platform to manage college events, registrations, and schedules.

### 4) 🌾 Krishi Sakhi
- Agriculture-focused app for farmer support and practical digital tools.

### 5) 🔁 n8n Chatbot
- Automated chatbot using **n8n** workflows and integrations.

---

## 🛠️ Tech Stack

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-0B0F1A?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![HTML5](https://img.shields.io/badge/HTML5-0B0F1A?style=for-the-badge&logo=html5&logoColor=E34F26)
![CSS3](https://img.shields.io/badge/CSS3-0B0F1A?style=for-the-badge&logo=css3&logoColor=1572B6)
![React](https://img.shields.io/badge/React-0B0F1A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-0B0F1A?style=for-the-badge&logo=vite&logoColor=646CFF)
![Node.js](https://img.shields.io/badge/Node.js-0B0F1A?style=for-the-badge&logo=node.js&logoColor=5FA04E)
![Git](https://img.shields.io/badge/Git-0B0F1A?style=for-the-badge&logo=git&logoColor=F05032)
![GitHub](https://img.shields.io/badge/GitHub-0B0F1A?style=for-the-badge&logo=github&logoColor=ffffff)
![n8n](https://img.shields.io/badge/n8n-0B0F1A?style=for-the-badge&logo=n8n&logoColor=EA4B71)

</div>

---

## 📊 Galactic Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Abilash-Kumar18&show_icons=true&theme=tokyonight&hide_border=true&bg_color=00000000&title_color=7DF9FF&icon_color=7DF9FF&text_color=C9D1D9" />
<img height="170" src="https://github-readme-streak-stats.herokuapp.com?user=Abilash-Kumar18&theme=tokyonight&hide_border=true&background=00000000&ring=7DF9FF&fire=7DF9FF&currStreakLabel=7DF9FF" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Abilash-Kumar18&layout=compact&theme=tokyonight&hide_border=true&bg_color=00000000&title_color=7DF9FF&text_color=C9D1D9" />

</div>

---

## 🐍 Contribution Snake Animation

<div align="center">

![snake gif](https://github.com/Abilash-Kumar18/Abilash-Kumar18/blob/output/github-contribution-grid-snake-dark.svg)

</div>

> ⚠️ To make the snake animation work, add this GitHub Action in your profile repository:

````yaml name=.github/workflows/snake.yml
name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 5

    steps:
      - name: Generate snake game from contribution graph
        uses: Platane/snk@v3
        with:
          github_user_name: Abilash-Kumar18
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push snake animation to output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
