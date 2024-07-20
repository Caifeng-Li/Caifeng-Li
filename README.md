## Hi there 👋

<!--
**Caifeng-Li/Caifeng-Li** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
- 😄 I’m Caifeng Li (github: @Caifeng-Li; ResearchGate: https://www.researchgate.net/profile/Caifeng-Li).
- 💞️ At present, I am a Ph.D. student and majoring in Statistics.
- 🌱 My research interests are Statistical Genetics, Computational biology, and Machine Learning.
- 📫 E-mail: caifeng.li2023@gmail.com

- ![](https://github-readme-stats.vercel.app/api?username=Caifeng-Li)
- ![](https://github-readme-stats.vercel.app/api?username=Caifeng-Li&theme=dark)

name: WakaTime Readme

on:
  push:
    branches:
      - master
  schedule:
    - cron: '0 19 * * *'

jobs:
  update-readme:
    runs-on: ubuntu-latest
    steps:
      - uses: athul/waka-readme@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}

