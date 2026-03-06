# 💫 About Me:
Hi 👋 I'm Dev — a Computer Science student focused on building real-world software, intelligent systems, and automation-driven solutions.<br>I believe in long-term skill building, deep problem-solving, and creating impact through technology.<br><br>🔭 I’m currently working on • Building strong foundations in Data Structures & Algorithms<br>• Developing Python-based systems and automation tools<br>• Exploring algorithmic trading systems and financial data analysis<br>• Creating real-world projects to strengthen problem-solving skills<br><br><br>🙋🏻 I’m looking to collaborate on • Open-source projects (Python / Backend / Automation)<br>• Hackathons and problem-driven software ideas<br>• Systems involving data, APIs, or performance optimization<br><br><br>🤝 I’m looking for help with • System design and scalable architectures<br>• Advanced DSA & competitive programming<br>• Deploying full-stack projects efficiently<br><br>🌱 I’m currently learning • Python (Advanced), Data Structures & Algorithms<br>• Web Development (HTML, CSS, JavaScript, React basics)<br>• Backend concepts, APIs, and databases<br>• Basics of AI/ML and automation systems<br><br>💬 Ask me about • C++ & Python fundamentals<br>• DSA learning strategies<br>• Hackathon preparation<br>• Building projects as a student<br><br>⚡ Fun fact I’m more interested in mastering hard skills than chasing quick comfort.<br><br>🎯 Long-Term Focus • Build intelligent systems (AI + automation inspired)<br>• Design high-performance, reliable software<br>• Create tools that solve real problems, not just demo projects<br>📫 Connect with Me<br>🔗 LinkedIn: [![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?logo=linkedin)](https://www.linkedin.com/in/dev-vaishnav-dev1369)<br>📧 Email: devvaishnav2007@gmail.com<br>🌐 Portfolio: Coming soon<br>• Open to learning, collaboration, and growth


## 🌐 Socials:
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/dev.sync.11x8) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/dev-vaishnav-dev1369) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:devvaishnav2007@gmail.com) 

# 💻 Tech Stack:
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E) ![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=flat&logo=c%2B%2B&logoColor=white) ![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white) ![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=flat&logo=bootstrap&logoColor=white) ![Django](https://img.shields.io/badge/django-%23092E20.svg?style=flat&logo=django&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=flat&logo=mongodb&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=flat&logo=postgresql&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=flat&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=flat&logo=pandas&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=flat&logo=Matplotlib&logoColor=black) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=flat&logo=github&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat&logo=git&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat&logo=docker&logoColor=white)
# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=systemetic-dev&theme=dark&hide_border=false&include_all_commits=true&count_private=false)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=systemetic-dev&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=systemetic-dev&theme=dark&hide_border=false&include_all_commits=true&count_private=false&layout=compact)

### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight)

---
[![](https://visitcount.itsvg.in/api?id=systemetic-dev&icon=0&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->


- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9

  env:
    # a github token is required to fetch the contribution calendar from github API
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
