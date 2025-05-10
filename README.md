## Olá, tudo bem? 👋

- 🔭 Faço Engenharia de Software
- 🎒 Estudo na UniCEUB
- 📚 Estou estudando algumas linguagens de programação
- 🖥️ Sempre em busca de aprender algo novo! 
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=gabxnz&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&title_color=cccccc&text_color=cccccc&icon_color=cccccc&bg_color=000000&locale=en&hide_border=false" height="150" alt="stats graph"  />
  <img src="https://streak-stats.demolab.com?user=gabxnz&locale=en&mode=daily&title_color=cccccc&text_color=cccccc&ring=cccccc&fire=cccccc&currStreakLabel=cccccc&sideNums=cccccc&sideLabels=cccccc&dates=cccccc&background=000000&hide_border=false&border_radius=4" height="152" alt="streak graph"  />
</div>

name: Generate Snake Animation

on:
  schedule:
    - cron: "0 0 * * *" # Roda todo dia à meia-noite
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: Platane/snk@v3
        with:
          github_user_name: gabxnz
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Commit animation
        uses: EndBug/add-and-commit@v9
        with:
          message: "generated snake animation"
          add: "dist/*.svg"

## Linguagens em aprendizado  
<span>
  <img height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" style="display: inline;">
  <img height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/c/c-original.svg" style="display: inline;">
</span>  

## Meios de contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gabxnz)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/gabxnz__)




