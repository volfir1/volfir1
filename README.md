<div align="center">
 
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 200">
  <style>
    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }
    @keyframes pulse {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.1); }
    }
    @keyframes rotate {
      from { transform: rotate(0deg); }
      to { transform: rotate(360deg); }
    }
    .floating {
      animation: float 3s ease-in-out infinite;
    }
    .pulsing {
      animation: pulse 2s ease-in-out infinite;
    }
    .rotating {
      animation: rotate 10s linear infinite;
      transform-origin: center;
    }
    .text-gradient {
      fill: url(#textGradient);
    }
  </style>
  
  <!-- Gradients -->
  <defs>
    <linearGradient id="textGradient" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#FF2D20"/>
      <stop offset="50%" style="stop-color:#38B2AC"/>
      <stop offset="100%" style="stop-color:#646CFF"/>
      <animate attributeName="x1" values="0%;100%;0%" dur="10s" repeatCount="indefinite" />
      <animate attributeName="x2" values="100%;200%;100%" dur="10s" repeatCount="indefinite" />
    </linearGradient>
  </defs>

  <!-- Background -->
  <rect width="800" height="200" fill="#1a1b1e"/>
  
  <!-- Decorative circles -->
  <g class="rotating">
    <circle cx="700" cy="50" r="20" fill="#FF2D20" opacity="0.3"/>
    <circle cx="660" cy="80" r="15" fill="#38B2AC" opacity="0.3"/>
    <circle cx="730" cy="90" r="10" fill="#646CFF" opacity="0.3"/>
  </g>

  <!-- Main content -->
  <g class="floating">
    <!-- Code symbol -->
    <path d="M100,100 L130,70 L160,100 L130,130 Z" fill="none" stroke="#38B2AC" stroke-width="2"/>
    
    <!-- Controller icon -->
    <path d="M640,100 A30,30 0 1,1 700,100 A30,30 0 1,1 640,100" fill="none" stroke="#FF2D20" stroke-width="2"/>
  </g>

  <!-- Main text -->
  <text x="400" y="100" text-anchor="middle" class="text-gradient" style="font-size: 48px; font-weight: bold;">
    Welcome to My GitHub
  </text>

  <!-- Tech stack icons -->
  <g class="pulsing">
    <circle cx="200" cy="150" r="15" fill="#61DAFB"/> <!-- React -->
    <circle cx="240" cy="150" r="15" fill="#FF2D20"/> <!-- Laravel -->
    <circle cx="280" cy="150" r="15" fill="#38B2AC"/> <!-- Tailwind -->
    <circle cx="320" cy="150" r="15" fill="#F7DF1E"/> <!-- JavaScript -->
  </g>
</svg>


# 👋 Welcome to My GitHub Profile!

### 💫 About Me
 🔭 I'm currently working on ...<br>
 🌱 I'm currently learning Python, React, and Laravel<br>
 👯 I'm looking to collaborate on web development projects<br>
 💬 Ask me about JavaScript, React, and Laravel<br>
 ⚡ Fun fact: I'm an avid gamer across multiple platforms!<br>

### 🌐 Connect With Me
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/_eilst_)
[![Reddit](https://img.shields.io/badge/Reddit-%23FF4500.svg?logo=Reddit&logoColor=white)](https://reddit.com/user/Sparking20)

### 💻 Tech Stack

#### Frontend
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white)
![MUI](https://img.shields.io/badge/MUI-%230081CB.svg?style=for-the-badge&logo=mui&logoColor=white)

#### Backend
![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)

#### Tools & Platforms
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![Chart.js](https://img.shields.io/badge/chart.js-F5788D.svg?style=for-the-badge&logo=chart.js&logoColor=white)
![WordPress](https://img.shields.io/badge/WordPress-%23117AC9.svg?style=for-the-badge&logo=WordPress&logoColor=white)
![Drupal](https://img.shields.io/badge/drupal-%230678BE.svg?style=for-the-badge&logo=drupal&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)
![Insomnia](https://img.shields.io/badge/Insomnia-black?style=for-the-badge&logo=insomnia&logoColor=5849BE)

#### Design
![Adobe](https://img.shields.io/badge/adobe-%23FF0000.svg?style=for-the-badge&logo=adobe&logoColor=white)
![Adobe Photoshop](https://img.shields.io/badge/adobe%20photoshop-%2331A8FF.svg?style=for-the-badge&logo=adobe%20photoshop&logoColor=white)
![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white)
![Dribbble](https://img.shields.io/badge/Dribbble-EA4C89?style=for-the-badge&logo=dribbble&logoColor=white)

#### Gaming
![Steam](https://img.shields.io/badge/steam-%23000000.svg?style=for-the-badge&logo=steam&logoColor=white)
![Xbox](https://img.shields.io/badge/xbox-%23107C10.svg?style=for-the-badge&logo=xbox&logoColor=white)
![Epic Games](https://img.shields.io/badge/epicgames-%23313131.svg?style=for-the-badge&logo=epicgames&logoColor=white)
![Riot Games](https://img.shields.io/badge/riotgames-D32936.svg?style=for-the-badge&logo=riotgames&logoColor=white)
![nVIDIA](https://img.shields.io/badge/nVIDIA-%2376B900.svg?style=for-the-badge&logo=nVIDIA&logoColor=white)

### 📊 GitHub Stats

<img src="https://github-readme-stats.vercel.app/api?username=volfir1&theme=dark&hide_border=false&include_all_commits=true&count_private=true" alt="GitHub Stats" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=volfir1&theme=dark&hide_border=false" alt="GitHub Streak" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=volfir1&theme=dark&hide_border=false&include_all_commits=true&count_private=true&layout=compact" alt="Top Languages" />

### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

---
<img src="https://visitcount.itsvg.in/api?id=volfir1&icon=10&color=8" alt="Profile Views" />

</div>
