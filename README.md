<h1 align="center">Hi, I'm Cem 👋</h1>

<h3 align="center">Mathematician & Software Developer</h3>

<p align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=F7B924&center=true&vCenter=true&width=650&lines=BSc+Mathematics+%2B+Associate+Degree+in+Computer+Science;Building+desktop+applications+with+Python+and+Kivy;Linux+%2F+CachyOS+%2F+KDE+Plasma+user;Open-source+enthusiast+%F0%9F%9A%80"
    alt="Typing introduction"
  />
</p>

<p align="center">
  <a href="https://www.instagram.com/superuser.d0/">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/>
  </a>
  <a href="https://www.youtube.com/channel/UCZ5prMIm2jaertl7gSgGY_w">
    <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube"/>
  </a>
</p>

---

### 👨‍🎓 About Me

* 🎓 I am pursuing a **BSc in Mathematics** alongside an **Associate Degree in Computer Science**.
* 🧮 I enjoy applying mathematical thinking to software architecture, problem-solving, and system design.
* 🐍 My primary programming language is **Python**.
* 🖥️ I am also working with **MATLAB** and **Microsoft SQL Server** for numerical computing and database development.
* 🐧 My daily operating system is **CachyOS**, an Arch-based Linux distribution, running **KDE Plasma**.
* 🌱 I am continuously improving my knowledge of software engineering, application architecture, testing, and open-source development.
* 👾 Pac-Man is my personal symbol — you can see why below.

---

### 🛠️ Featured Project

<table>
<tr>
<td width="140" align="center">
  <img
    src="https://raw.githubusercontent.com/github/explore/main/topics/python/python.png"
    width="60"
    alt="Python logo"
  />
</td>
<td>

#### 📊 [Archlence](https://github.com/superuser-d0/archlence)

A privacy-focused, **local-first personal finance and portfolio management application**.

Archlence is built with **Python** and **Kivy** and is designed around a reliable ledger architecture, intelligent caching, and local data ownership.

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![Kivy](https://img.shields.io/badge/-Kivy-000000?style=flat-square\&logo=python\&logoColor=white)
![Local First](https://img.shields.io/badge/-Local--First-2EA44F?style=flat-square)
![Privacy Focused](https://img.shields.io/badge/-Privacy%20Focused-8A2BE2?style=flat-square)
![Desktop](https://img.shields.io/badge/-Desktop%20Application-555555?style=flat-square)
![Open Source](https://img.shields.io/badge/-Open%20Source-F7B924?style=flat-square\&logo=opensourceinitiative\&logoColor=black)

</td>
</tr>
</table>

---

### 🧰 Technologies & Tools

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Kivy-000000?style=for-the-badge&logo=python&logoColor=white" alt="Kivy"/>
  <img src="https://img.shields.io/badge/MATLAB-E86D13?style=for-the-badge&logo=mathworks&logoColor=white" alt="MATLAB"/>
  <img src="https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" alt="Microsoft SQL Server"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
  <img src="https://img.shields.io/badge/Arch%20Linux-1793D1?style=for-the-badge&logo=archlinux&logoColor=white" alt="Arch Linux"/>
  <img src="https://img.shields.io/badge/KDE%20Plasma-1D99F3?style=for-the-badge&logo=kde&logoColor=white" alt="KDE Plasma"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</p>

---

### 📈 GitHub Statistics

<p align="center">
  <img
    height="165"
    src="https://github-readme-stats.vercel.app/api?username=superuser-d0&show_icons=true&theme=radical&hide_border=true&count_private=true"
    alt="Cem's GitHub statistics"
  />
  <img
    height="165"
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=superuser-d0&layout=compact&theme=radical&hide_border=true"
    alt="Most used programming languages"
  />
</p>

<p align="center">
  <img
    src="https://streak-stats.demolab.com?user=superuser-d0&theme=radical&hide_border=true"
    alt="GitHub contribution streak"
  />
</p>

---

### 👾 Pac-Man Contribution Graph

> Since Pac-Man is my personal symbol, it only makes sense for him to consume my GitHub contribution history. 😄
>
> The animation below transforms my GitHub contribution graph into a Pac-Man game.

<p align="center">
  <img
    src="https://raw.githubusercontent.com/superuser-d0/superuser-d0/output/pacman-contribution-graph.svg"
    alt="Pac-Man contribution graph"
  />
</p>

<details>
<summary>🔧 How can I enable this animation?</summary>

<br>

This graphic is automatically generated using a GitHub Actions workflow.

To add it to the `superuser-d0/superuser-d0` repository:

1. Create the following file:

   ```text
   .github/workflows/pacman.yml
   ```

2. Add the workflow below:

```yaml
name: Generate Pac-Man contribution graph

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

permissions:
  contents: write

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - name: Generate contribution graph
        uses: Platane/snk@v3
        with:
          github_user_name: superuser-d0
          outputs: |
            dist/pacman-contribution-graph.svg?palette=github-dark

      - name: Publish generated files
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

3. Run the workflow manually once from the **Actions** tab.

4. After the workflow completes, an `output` branch will be created automatically.

5. The image URL used in this README already points to that branch and will update whenever the workflow runs.

</details>

---

<p align="center">
  <i>“Code without mathematics is a journey without a map.”</i>
</p>
