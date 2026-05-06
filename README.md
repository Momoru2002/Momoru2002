<!-- =============================================
     GitHub Profile — Muhammad Almas Albirra Hamid
     Username: Momoru2002
============================================= -->

<div align="center">

# ⚔️ Muhammad Almas Albirra Hamid

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=9B00FF&center=true&vCenter=true&width=500&lines=Web+Developer+%F0%9F%9A%80;Full+Stack+Builder+%F0%9F%94%A5;Data+Analyst+Enthusiast+%F0%9F%93%8A;Building+things+that+matter+%E2%9A%94%EF%B8%8F" alt="Typing SVG" />

<br/>

<img src="https://komarev.com/ghpvc/?username=Momoru2002&color=9b00ff&style=flat-square&label=Profile+Views" />
&nbsp;
<img src="https://img.shields.io/github/followers/Momoru2002?color=9b00ff&style=flat-square&label=Followers" />

</div>

---

## 🐉 The Dragon Has Landed

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 200" width="900" height="200">
  <defs>
    <style>
      @keyframes fly {
        0%   { transform: translateX(-120px) translateY(0px); }
        25%  { transform: translateX(150px) translateY(-18px); }
        50%  { transform: translateX(400px) translateY(5px); }
        75%  { transform: translateX(650px) translateY(-12px); }
        100% { transform: translateX(920px) translateY(0px); }
      }
      @keyframes wingFlap {
        0%, 100% { transform: scaleY(1); }
        50%       { transform: scaleY(0.55); }
      }
      @keyframes flameFlicker {
        0%, 100% { opacity: 1; transform: scaleX(1) scaleY(1); }
        33%      { opacity: 0.7; transform: scaleX(1.15) scaleY(0.85); }
        66%      { opacity: 0.9; transform: scaleX(0.9) scaleY(1.1); }
      }
      @keyframes tailWave {
        0%, 100% { d: path("M0,0 Q10,-8 20,-2 Q30,6 40,0 Q50,-6 60,0"); }
        50%       { d: path("M0,0 Q10,8 20,2 Q30,-6 40,0 Q50,6 60,0"); }
      }
      @keyframes glow {
        0%, 100% { filter: drop-shadow(0 0 6px #ff6a00) drop-shadow(0 0 14px #ee0979); }
        50%       { filter: drop-shadow(0 0 12px #ffcc00) drop-shadow(0 0 24px #ff6a00); }
      }

      .dragon-group {
        animation: fly 7s linear infinite;
      }
      .wing-top {
        transform-origin: 42px 52px;
        animation: wingFlap 0.38s ease-in-out infinite;
      }
      .wing-bot {
        transform-origin: 42px 66px;
        animation: wingFlap 0.38s ease-in-out infinite reverse;
      }
      .flame {
        animation: flameFlicker 0.22s ease-in-out infinite;
        transform-origin: 78px 60px;
      }
      .dragon-body {
        animation: glow 1.5s ease-in-out infinite;
      }
    </style>

    <!-- Body gradient -->
    <linearGradient id="bodyGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%"   stop-color="#1a0533"/>
      <stop offset="50%"  stop-color="#6b00b6"/>
      <stop offset="100%" stop-color="#2d0054"/>
    </linearGradient>
    <!-- Wing gradient -->
    <linearGradient id="wingGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%"   stop-color="#9b00ff" stop-opacity="0.9"/>
      <stop offset="100%" stop-color="#3d0080" stop-opacity="0.4"/>
    </linearGradient>
    <!-- Flame gradient -->
    <radialGradient id="flameGrad" cx="50%" cy="70%" r="50%">
      <stop offset="0%"   stop-color="#fff176"/>
      <stop offset="40%"  stop-color="#ff6d00"/>
      <stop offset="100%" stop-color="#b71c1c" stop-opacity="0"/>
    </radialGradient>

    <!-- Scale texture -->
    <pattern id="scales" x="0" y="0" width="6" height="6" patternUnits="userSpaceOnUse">
      <circle cx="3" cy="3" r="2.5" fill="none" stroke="#a060ff" stroke-width="0.4" opacity="0.3"/>
    </pattern>
  </defs>

  <!-- Background -->
  <rect width="900" height="200" fill="#0d001a"/>
  <!-- Stars -->
  <g opacity="0.6">
    <circle cx="50"  cy="20"  r="1"   fill="white"/>
    <circle cx="130" cy="45"  r="0.8" fill="white"/>
    <circle cx="200" cy="10"  r="1.2" fill="white"/>
    <circle cx="310" cy="30"  r="0.7" fill="white"/>
    <circle cx="420" cy="15"  r="1"   fill="white"/>
    <circle cx="500" cy="50"  r="0.8" fill="white"/>
    <circle cx="580" cy="22"  r="1.1" fill="white"/>
    <circle cx="670" cy="38"  r="0.6" fill="white"/>
    <circle cx="760" cy="12"  r="1"   fill="white"/>
    <circle cx="840" cy="55"  r="0.9" fill="white"/>
    <circle cx="880" cy="28"  r="0.7" fill="white"/>
    <circle cx="100" cy="180" r="0.8" fill="white"/>
    <circle cx="350" cy="170" r="1"   fill="white"/>
    <circle cx="600" cy="185" r="0.7" fill="white"/>
    <circle cx="750" cy="175" r="1"   fill="white"/>
  </g>

  <!-- ===== DRAGON GROUP (animates left to right) ===== -->
  <g class="dragon-group" transform="translate(-120, 70)">
    <g class="dragon-body">

      <!-- === TAIL (behind body) === -->
      <g transform="translate(90, 58)">
        <!-- tail segments -->
        <ellipse cx="0"   cy="0"  rx="9"  ry="5"  fill="url(#bodyGrad)" transform="rotate(-10)"/>
        <ellipse cx="16"  cy="-4" rx="7"  ry="4"  fill="url(#bodyGrad)" transform="rotate(-20)"/>
        <ellipse cx="30"  cy="-10" rx="5" ry="3"  fill="url(#bodyGrad)" transform="rotate(-30)"/>
        <ellipse cx="41"  cy="-18" rx="3" ry="2"  fill="url(#bodyGrad)" transform="rotate(-40)"/>
        <!-- tail spikes -->
        <polygon points="32,-14 36,-22 40,-13" fill="#9b00ff" opacity="0.8"/>
        <polygon points="42,-20 46,-28 48,-18" fill="#9b00ff" opacity="0.7"/>
        <!-- tail tip fork -->
        <polygon points="51,-26 55,-34 53,-25 57,-32 55,-23" fill="#cc44ff" opacity="0.9"/>
      </g>

      <!-- === WINGS === -->
      <!-- Top wing -->
      <g class="wing-top">
        <path d="M42,52 L5,10 L25,45 L0,38 L28,50 L15,55 L42,54 Z"
              fill="url(#wingGrad)" stroke="#9b00ff" stroke-width="0.5"/>
        <!-- wing membranes/ribs -->
        <line x1="42" y1="52" x2="5"  y2="10"  stroke="#cc44ff" stroke-width="0.8" opacity="0.5"/>
        <line x1="42" y1="52" x2="25" y2="45"  stroke="#cc44ff" stroke-width="0.6" opacity="0.4"/>
        <line x1="42" y1="52" x2="0"  y2="38"  stroke="#cc44ff" stroke-width="0.6" opacity="0.4"/>
        <line x1="42" y1="52" x2="15" y2="55"  stroke="#cc44ff" stroke-width="0.5" opacity="0.3"/>
      </g>
      <!-- Bottom wing -->
      <g class="wing-bot">
        <path d="M42,66 L8,100 L28,72 L4,82 L30,68 L18,63 L42,65 Z"
              fill="url(#wingGrad)" stroke="#9b00ff" stroke-width="0.5" opacity="0.85"/>
        <line x1="42" y1="66" x2="8"  y2="100" stroke="#cc44ff" stroke-width="0.8" opacity="0.5"/>
        <line x1="42" y1="66" x2="28" y2="72"  stroke="#cc44ff" stroke-width="0.6" opacity="0.4"/>
        <line x1="42" y1="66" x2="4"  y2="82"  stroke="#cc44ff" stroke-width="0.6" opacity="0.4"/>
      </g>

      <!-- === BODY === -->
      <!-- Main torso -->
      <ellipse cx="55" cy="60" rx="22" ry="14" fill="url(#bodyGrad)" stroke="#9b00ff" stroke-width="0.5"/>
      <ellipse cx="55" cy="60" rx="22" ry="14" fill="url(#scales)" opacity="0.5"/>
      <!-- belly lighter -->
      <ellipse cx="55" cy="62" rx="14" ry="8" fill="#3d0070" opacity="0.5"/>
      <!-- dorsal spikes -->
      <polygon points="40,48 43,38 46,48" fill="#cc44ff" opacity="0.9"/>
      <polygon points="48,46 51,35 54,46" fill="#cc44ff" opacity="0.9"/>
      <polygon points="56,45 59,34 62,45" fill="#cc44ff" opacity="0.9"/>
      <polygon points="64,47 67,37 70,47" fill="#cc44ff" opacity="0.85"/>

      <!-- === NECK === -->
      <path d="M74,55 Q80,50 84,52 Q86,54 82,58 Q78,62 74,65 Z"
            fill="url(#bodyGrad)" stroke="#9b00ff" stroke-width="0.4"/>
      <!-- neck spikes -->
      <polygon points="76,52 78,44 80,52" fill="#cc44ff" opacity="0.8"/>
      <polygon points="80,50 82,42 84,50" fill="#cc44ff" opacity="0.8"/>

      <!-- === HEAD === -->
      <!-- head shape -->
      <path d="M82,50 Q90,44 100,46 Q110,47 112,54 Q113,60 108,65 Q102,70 90,68 Q82,65 80,58 Z"
            fill="url(#bodyGrad)" stroke="#9b00ff" stroke-width="0.5"/>
      <path d="M82,50 Q90,44 100,46 Q110,47 112,54 Q113,60 108,65 Q102,70 90,68 Q82,65 80,58 Z"
            fill="url(#scales)" opacity="0.4"/>
      <!-- snout -->
      <path d="M108,52 Q118,50 122,55 Q118,62 108,62 Z"
            fill="url(#bodyGrad)" stroke="#9b00ff" stroke-width="0.4"/>
      <!-- nostril -->
      <circle cx="116" cy="56" r="1.5" fill="#1a0533"/>
      <circle cx="119" cy="55" r="1"   fill="#1a0533"/>
      <!-- eye -->
      <circle cx="98" cy="53" r="4"   fill="#ff6d00"/>
      <circle cx="98" cy="53" r="2.5" fill="#1a0533"/>
      <circle cx="99" cy="52" r="1"   fill="white" opacity="0.8"/>
      <!-- eye slit -->
      <ellipse cx="98" cy="53" rx="0.8" ry="2.3" fill="#000"/>
      <!-- head horn -->
      <path d="M92,46 Q90,36 94,30 Q96,40 97,46 Z" fill="#cc44ff" stroke="#9b00ff" stroke-width="0.4"/>
      <path d="M100,45 Q100,37 103,33 Q104,40 104,45 Z" fill="#cc44ff" opacity="0.8"/>
      <!-- jaw -->
      <path d="M108,62 Q118,64 122,60 Q120,66 112,68 Q104,70 100,68 Z"
            fill="#2d0054" stroke="#9b00ff" stroke-width="0.3"/>
      <!-- teeth -->
      <polygon points="110,62 112,68 114,62" fill="white" opacity="0.9"/>
      <polygon points="114,62 116,67 118,62" fill="white" opacity="0.9"/>
      <polygon points="118,62 119,65 120,62" fill="white" opacity="0.7"/>

      <!-- === FLAME === -->
      <g class="flame" transform="translate(122, 55)">
        <!-- outer flame -->
        <path d="M0,0 Q8,-10 14,-5 Q18,-15 22,-8 Q26,-18 28,-6 Q32,-12 30,2 Q28,10 20,12 Q10,14 2,8 Z"
              fill="url(#flameGrad)" opacity="0.9"/>
        <!-- inner bright core -->
        <path d="M4,2 Q10,-4 16,0 Q20,-8 22,2 Q20,8 14,10 Q8,10 4,6 Z"
              fill="#fff176" opacity="0.7"/>
        <!-- sparks -->
        <circle cx="18" cy="-14" r="1.5" fill="#ffcc00" opacity="0.8"/>
        <circle cx="26" cy="-10" r="1"   fill="#ff6d00" opacity="0.7"/>
        <circle cx="8"  cy="-8"  r="1.2" fill="#ffcc00" opacity="0.6"/>
        <circle cx="30" cy="-4"  r="0.8" fill="#fff176" opacity="0.9"/>
      </g>

      <!-- === FRONT CLAWS (tiny) === -->
      <g transform="translate(66, 68)">
        <ellipse cx="0" cy="0" rx="5" ry="3" fill="url(#bodyGrad)"/>
        <line x1="-3" y1="3" x2="-5" y2="8"  stroke="#cc44ff" stroke-width="1.2" stroke-linecap="round"/>
        <line x1="0"  y1="3" x2="-1" y2="9"  stroke="#cc44ff" stroke-width="1.2" stroke-linecap="round"/>
        <line x1="3"  y1="3" x2="4"  y2="8"  stroke="#cc44ff" stroke-width="1.2" stroke-linecap="round"/>
      </g>
      <!-- Hind claw -->
      <g transform="translate(48, 72)">
        <ellipse cx="0" cy="0" rx="5" ry="3" fill="url(#bodyGrad)"/>
        <line x1="-3" y1="3" x2="-5" y2="9"  stroke="#cc44ff" stroke-width="1.2" stroke-linecap="round"/>
        <line x1="0"  y1="3" x2="-1" y2="9"  stroke="#cc44ff" stroke-width="1.2" stroke-linecap="round"/>
        <line x1="3"  y1="3" x2="3"  y2="9"  stroke="#cc44ff" stroke-width="1.2" stroke-linecap="round"/>
      </g>

    </g>
  </g>

  <!-- Ground atmospheric glow -->
  <ellipse cx="450" cy="195" rx="420" ry="10" fill="#6b00b6" opacity="0.08"/>
</svg>

## 👨‍💻 About Me

```ts
const almas = {
  name     : "Muhammad Almas Albirra Hamid",
  alias    : "Momoru",
  location : "Indonesia 🇮🇩",
  learning : ["Next.js", "NestJS", "AWS", "Data Analytics"],
  goals    : "Build useful products & ship consistently",
  funFact  : "I enjoy turning weird ideas into small tools/apps 🎲",
  quote    : "Build something crazy every day. 🔥",
};
```

---

## 🧰 Tech Stack

<div align="center">

**Frontend**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)

**Languages**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

**Tools & Cloud**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</div>

---

## ⚡ Featured Projects

<div align="center">

| Project | Description | Stack |
|---------|-------------|-------|
| 🧠 **LifeOS App** | Personal productivity OS — manage your life in one place | Next.js, NestJS |
| 📊 **Dashboard UI** | Analytics dashboard with rich data visualizations | React, Tailwind |
| 🌐 **Portfolio** | Personal site showcasing projects & skills | Next.js, TypeScript |
| ✅ **Todo App** | Clean, minimal task management app | React, Node.js |

</div>

---

## 📊 GitHub Stats

<div align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=Momoru2002&show_icons=true&theme=tokyonight&hide_border=true&ring_color=9b00ff&title_color=9b00ff" alt="GitHub Stats"/>
  &nbsp;
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Momoru2002&layout=compact&theme=tokyonight&hide_border=true&title_color=9b00ff" alt="Top Languages"/>
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=Momoru2002&theme=tokyonight&hide_border=true&ring=9b00ff&fire=ff6a00&currStreakLabel=9b00ff" alt="GitHub Streak"/>
</div>

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Momoru2002&theme=tokyonight&column=7&margin-w=8&margin-h=8&no-frame=true" alt="Trophies"/>
</div>

---

## 🌌 Contribution Activity

<picture>
  <source media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/Momoru2002/Momoru2002/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/Momoru2002/Momoru2002/output/github-contribution-grid-snake.svg">
  <img alt="Contribution Snake" src="https://raw.githubusercontent.com/Momoru2002/Momoru2002/output/github-contribution-grid-snake.svg"/>
</picture>

> ⚠️ **Note:** Snake animation requires a GitHub Actions workflow — see setup below.

---

## 🔗 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muhammad-almas-albirra-hamid-3812202b8)
[![Twitter / X](https://img.shields.io/badge/X_(Twitter)-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/Mr_Momoru)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:seriesmomoru@gmail.com)
[![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/users/monarch7894)

</div>

---

<div align="center">

*"Build something crazy every day."* 🐉

</div>
