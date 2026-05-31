 Hi, I'm Tarun Narayanashetti 👋

<pre>
████████╗ █████╗ ██████╗ ██╗   ██╗███╗   ██╗
╚══██╔══╝██╔══██╗██╔══██╗██║   ██║████╗  ██║
   ██║   ███████║██████╔╝██║   ██║██╔██╗ ██║
   ██║   ██╔══██║██╔══██╗██║   ██║██║╚██╗██║
   ██║   ██║  ██║██║  ██║╚██████╔╝██║ ╚████║
   ╚═╝   ╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝ ╚═╝  ╚═══╝
</pre>

## About Me:

- Full Stack Developer passionate about turning ideas into real products.
- I love building, breaking, learning, and rebuilding things better.
- Currently improving Data Structures, Algorithms, System Design, and Backend Engineering.
- Building production-level applications with modern web technologies.
- Interested in scalable systems, clean architecture, and solving meaningful problems.
- Constantly learning through projects, coding platforms, and developer communities.
- Open to Full Stack Developer opportunities.

## Skill Set:

<table><tr><td valign="top" width="33%">

### Frontend

<div align="center">

<img src="https://skillicons.dev/icons?i=html,css,js,ts,react,nextjs,tailwind&perline=4" />

</div>

</td><td valign="top" width="33%">

### Backend & Database

<div align="center">

<img src="https://skillicons.dev/icons?i=nodejs,express,mongodb,redis&perline=4" />

</div>

</td><td valign="top" width="33%">

### Tools

<div align="center">

<img src="https://skillicons.dev/icons?i=git,github,docker,aws,vscode,vercel&perline=4" />

</div>

</td></tr></table>


## 🚀 Featured Project

### DevTinder

A developer networking platform helping developers connect and collaborate.

- Authentication and authorization
- Scalable REST APIs
- Database design
- Full stack deployment

**Tech:** React • Node.js • Express • MongoDB

🌐 Portfolio: https://tarunn.xyz

💻 GitHub: https://github.com/ofctarun/DevTinder


## Connect with me:

<div align="center">

<a href="https://github.com/ofctarun">
<img src="https://img.shields.io/badge/GitHub-ofctarun-black?style=flat&logo=github"/>
</a>

<a href="https://tarunn.xyz">
<img src="https://img.shields.io/badge/Portfolio-tarunn.xyz-blue?style=flat"/>
</a>

</div>


## Github Stats:

<p align="center">

<a href="https://github.com/ofctarun">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=ofctarun&show_icons=true&theme=onedark&include_all_commits=true&count_private=true&hide_border=true"/>

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ofctarun&layout=compact&theme=onedark&hide_border=true"/>

</a>

</p>


<p align="center">

<img width="80%" src="https://github-readme-streak-stats.herokuapp.com/?user=ofctarun&theme=onedark&hide_border=true"/>

</p>


<p align="center">

<img height=250 src="https://github-readme-activity-graph.vercel.app/graph?username=ofctarun&theme=github-dark"/>

</p>


<div align="center">

<img src="https://komarev.com/ghpvc/?username=ofctarun&style=for-the-badge&color=orange"/>

</div>


<h2 align="center">💻 Check Out My Repos ⬇️</h2>
"""

out = "/mnt/data/Tarun_GitHub_README.md"
pypandoc.convert_text(content, "md", format="md", outputfile=out, extra_args=["--standalone"])
print(out)
