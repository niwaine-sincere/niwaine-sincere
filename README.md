#Hi there 👋<br></br>
 ##I AM NIWAINE SINCERE<br></br>
 *FRONT END DEVELOPER

##🌱 I’m currently expanding skill in;
💻 JavaScript, React, Node.js, databases, Git & GitHub, and modern web development.
Web development projects, open-source projects, student tech projects, and creative applications that solve real-world problems.


## 💻 Programming Languages 
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) 
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) 
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) 
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) 
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

![profile views](https://komarev.com/ghpvc/?username=niwaine-sincere&color=blue)

<!--START_SECTION:waka-->
<!--END_SECTION:waka-->

name: WakaTime Stats
on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  update-readme:
    runs-on: ubuntu-latest

    steps:
      - uses: athul/waka-readme@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
