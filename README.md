<!-- Profile Views + Open to Work -->
<p align="left">
  <img src="https://komarev.com/ghpvc/?username=Pateldevlop&color=0e75b6&style=flat-square&label=Profile+Views" alt="Profile Views" />
  <img src="https://img.shields.io/badge/Open%20to%20Work-Remote%20%7C%20Freelance%20%7C%20Onsite-brightgreen?style=flat-square" alt="Open to Work" />
</p>

<!-- Typing Animation -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=58A6FF&width=500&lines=Hey%2C+I'm+Vikas+Patel+%F0%9F%91%8B;Full-Stack+Software+Engineer;PHP+%7C+Laravel+%7C+Node.js+%7C+Docker;Open+to+Remote+%26+Freelance+Work)](https://git.io/typing-svg)

---

# Hey, I'm Vikas Patel 👋

Full-Stack Software Engineer based in India — I build things for the web that actually work.  
I've spent years shipping production-grade applications using **PHP, Laravel, Node.js, and Docker**,  
working across startups and agencies, turning messy requirements into clean, maintainable code.

Whether it's a REST API at 2am or a CI/CD pipeline that finally stops breaking on Fridays — I'm your person.

---

## 🛠️ What I Work With

[![My Skills](https://skillicons.dev/icons?i=php,laravel,nodejs,mysql,docker,git,html,css,bootstrap,js,github,githubactions)](https://skillicons.dev)

### 🔧 Backend
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![CodeIgniter](https://img.shields.io/badge/CodeIgniter-EF4223?style=flat-square&logo=codeigniter&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20API-005571?style=flat-square&logo=fastapi&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

### 🎨 Frontend
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=flat-square&logo=bootstrap&logoColor=white)

### 🗄️ Database
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=flat-square&logo=mysql&logoColor=white)

### ⚙️ DevOps & Tooling
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=Pateldevlop&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&rank_icon=github" alt="Vikas's GitHub Stats" height="170" />
  &nbsp;&nbsp;
  <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=Pateldevlop&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages" height="170" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=Pateldevlop&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

---

## 📈 Contribution Activity

[![Vikas's Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=Pateldevlop&theme=tokyo-night&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

---

## 🚀 What I'm Currently Working On

- Deepening my Docker + CI/CD workflow for faster, cleaner deployments
- Building full-stack projects with Laravel + Node.js to keep both sides sharp
- Exploring scalable backend architecture patterns

---

## 💼 What I'm Open To

I'm actively looking for:

- 🌍 **Remote roles** — full-time or contract, timezone-flexible
- 💻 **Freelance projects** — web apps, APIs, backend systems, or long-term product work
- 🏢 **Onsite opportunities** — open to relocation for the right role

I work well independently and inside teams. I read documentation before asking questions. I write code I'd be comfortable reviewing six months later.

---

## 📌 A Few Projects

> *(More coming soon — actively updating this section)*

| Project | Stack | Description |
|---|---|---|
| [php-master-guide](https://github.com/Pateldevlop/php-master-guide) | PHP | Step-by-step PHP developer reference |
| [patel.github.io](https://github.com/Pateldevlop/patel.github.io) | HTML/CSS | Personal web presence |
| [javascript-master-guide](https://github.com/Pateldevlop/javascript-master-guide) | JavaScript | JS concepts from basics to advanced |

> 🔨 More original projects coming soon — actively building.

---

## 🐍 Contribution Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/Pateldevlop/Pateldevlop/output/snake.svg" alt="Snake animation" />
</p>

<details>
<summary>⚙️ How to activate the snake (one-time setup)</summary>
<br>

1. Go to your `Pateldevlop/Pateldevlop` repo → **Actions** tab → **New workflow** → **Set up a workflow yourself**
2. Name the file `snake.yml` and paste this content:

```yaml
name: Generate Snake
on:
  schedule: [{cron: "0 0 * * *"}]
  workflow_dispatch:
jobs:
  snake:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: Pateldevlop
          outputs: dist/snake.svg
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

3. Click **Commit changes**, then go back to Actions → click **Generate Snake** → **Run workflow**
4. Done — the animation will update automatically every day after that.

</details>

---

## 📫 Let's Connect

If you've got a project, a role, or just want to talk shop — reach out.  
I reply. I'm easy to work with. Let's build something.

<p align="left">
  <a href="https://www.linkedin.com/in/vikas-patel-703152218">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;
  <a href="https://twitter.com/vpateldev">
    <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter" />
  </a>
  &nbsp;
  <a href="https://github.com/Pateldevlop">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

---

<p align="center">
  <img src="https://img.shields.io/badge/Open%20to%20Work-Remote%20%7C%20Freelance%20%7C%20Onsite-brightgreen?style=for-the-badge" alt="Open to Work" />
</p>

<p align="center"><i>Open to work · Available now · Let's talk</i></p>

