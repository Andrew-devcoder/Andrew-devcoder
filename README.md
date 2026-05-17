### Hallo 👋

<div align="center">
  <a href="https://github.com/Andrew-devcoder" >
    <img height="160em" src="https://stats-andrew-devcoder.vercel.app/api?username=Andrew-devcoder&show_icons=true&theme=radical&include_all_commits=true&count_private=true"/>
    <img height="160em" src="https://stats-andrew-devcoder.vercel.app/api/top-langs/?username=Andrew-devcoder&layout=compact&langs_count=7&theme=radical"/>
  </a>
</div>

<div style="display: block"><br>
  
  [![My Skills](https://skillicons.dev/icons?i=html,css,scss,js,ts,tailwind,bootstrap,gulp,yarn,git,gitlab,react,vite,npm,firebase,figma,vscode,netlify,lua,nestjs,postman,postgres,angular,nextjs,docker,kubernetes,linux,debian,nginx,redis)](https://skillicons.dev) 
  
</div>



  ##
 
<div> 
  <a href = "mailto:andrii.kovpak.de@gmail.com"><img align="right" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/andrii-kovpak-dev" target="_blank"><img align="right"  src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
  <a href="https://t.me/Andeveloper" target="_blank"><img align="right" src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" target="_blank"></a>
</div>


<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/Andrii-Kovpak-dev/Andrii-Kovpak-dev/output/github-contribution-grid-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/Andrii-Kovpak-dev/Andrii-Kovpak-dev/output/github-contribution-grid-snake.svg"
  />
  <img
    alt="github contribution grid snake animation"
    src="https://raw.githubusercontent.com/Andrii-Kovpak-dev/Andrii-Kovpak-dev/output/github-contribution-grid-snake.svg"
  />
</picture>


## 📂 Projects

# [Iren App](https://iren.andrii-kovpak.dev/)

[iren.andrii-kovpak.dev](https://iren.andrii-kovpak.dev/)

Iren App is a private calendar web application created for personal workday tracking.

The project was built for my girlfriend, who needed a simple way to record her working days, working hours, and comments for each day. The app also allows exporting monthly information as a PDF file.

Each user must sign in before using the application. This keeps every user's data private and connected to their own account. The data is stored in a database and can be accessed from any device.

## Main Features

- Google authentication
- Personal calendar for each user
- Workday and working-hours tracking
- Daily comments and notes
- Monthly PDF export
- Data storage in MongoDB
- Responsive web interface

## Tech Stack

- Next.js
- TypeScript
- Tailwind CSS
- MongoDB
- NextAuth / Google Auth
- Redux Toolkit
- Docker

## Deployment

The application is deployed through an automated pipeline:

GitHub Actions → Docker image → GHCR.io → Flux → k3s
