<div align="center">

<!-- Animated SVG Header -->
<svg width="800" height="200" viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg">
  <!-- Background -->
  <defs>
    <linearGradient id="bg-gradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0D1117;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#1a1a2e;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#16213e;stop-opacity:1" />
    </linearGradient>
    
    <!-- Neural network pattern -->
    <pattern id="neural-pattern" x="0" y="0" width="100" height="100" patternUnits="userSpaceOnUse">
      <circle cx="20" cy="20" r="2" fill="#00D4FF" opacity="0.3">
        <animate attributeName="opacity" values="0.3;0.8;0.3" dur="2s" repeatCount="indefinite"/>
      </circle>
      <circle cx="80" cy="30" r="1.5" fill="#7c3aed" opacity="0.4">
        <animate attributeName="opacity" values="0.4;0.9;0.4" dur="3s" repeatCount="indefinite"/>
      </circle>
      <circle cx="50" cy="70" r="1.8" fill="#ec4899" opacity="0.3">
        <animate attributeName="opacity" values="0.3;0.7;0.3" dur="2.5s" repeatCount="indefinite"/>
      </circle>
      <!-- Connecting lines -->
      <line x1="20" y1="20" x2="50" y2="70" stroke="#00D4FF" stroke-width="0.5" opacity="0.2">
        <animate attributeName="opacity" values="0.1;0.4;0.1" dur="4s" repeatCount="indefinite"/>
      </line>
      <line x1="50" y1="70" x2="80" y2="30" stroke="#7c3aed" stroke-width="0.5" opacity="0.2">
        <animate attributeName="opacity" values="0.1;0.4;0.1" dur="3.5s" repeatCount="indefinite"/>
      </line>
    </pattern>
    
    <!-- Code particles -->
    <g id="code-particle">
      <text font-family="JetBrains Mono, monospace" font-size="8" fill="#00FF88" opacity="0.4">
        <tspan x="0" y="0">{}</tspan>
      </text>
    </g>
  </defs>
  
  <!-- Background with pattern -->
  <rect width="800" height="200" fill="url(#bg-gradient)"/>
  <rect width="800" height="200" fill="url(#neural-pattern)" opacity="0.6"/>
  
  <!-- Animated code particles -->
  <use href="#code-particle" x="100" y="50">
    <animateTransform attributeName="transform" type="translate" 
      values="100,50; 120,45; 100,50" dur="3s" repeatCount="indefinite"/>
  </use>
  <use href="#code-particle" x="200" y="80">
    <animateTransform attributeName="transform" type="translate" 
      values="200,80; 185,85; 200,80" dur="4s" repeatCount="indefinite"/>
  </use>
  <use href="#code-particle" x="300" y="30">
    <animateTransform attributeName="transform" type="translate" 
      values="300,30; 315,25; 300,30" dur="2.5s" repeatCount="indefinite"/>
  </use>
  
  <!-- Main Title -->
  <text x="400" y="80" font-family="JetBrains Mono, monospace" font-size="36" font-weight="700" 
        text-anchor="middle" fill="url(#title-gradient)">
    <tspan>Hey, I'm Beckett</tspan>
    <animate attributeName="opacity" values="0;1;1;1" dur="2s" fill="freeze"/>
  </text>
  
  <!-- Subtitle -->
  <text x="400" y="110" font-family="JetBrains Mono, monospace" font-size="18" 
        text-anchor="middle" fill="#00D4FF">
    <tspan>AI Problem Solver</tspan>
    <animate attributeName="opacity" values="0;0;1;1" dur="3s" fill="freeze"/>
  </text>
  
  <!-- Animated underline -->
  <line x1="250" y1="120" x2="550" y2="120" stroke="#00D4FF" stroke-width="2" opacity="0">
    <animate attributeName="opacity" values="0;0;0;1" dur="4s" fill="freeze"/>
    <animate attributeName="stroke-dasharray" values="0,300;300,0" dur="2s" begin="3s" fill="freeze"/>
  </line>
  
  <!-- Subtitle text -->
  <text x="400" y="150" font-family="system-ui, sans-serif" font-size="14" 
        text-anchor="middle" fill="#a0a0a0">
    <tspan>Full-Stack Developer building AI-powered solutions with an end-to-end mindset</tspan>
    <animate attributeName="opacity" values="0;0;0;0;1" dur="5s" fill="freeze"/>
  </text>
  
  <!-- Title gradient definition -->
  <defs>
    <linearGradient id="title-gradient" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00D4FF;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#7c3aed;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#ec4899;stop-opacity:1" />
    </linearGradient>
  </defs>
</svg>

![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=00FF88&center=true&vCenter=true&width=500&lines=const+solve+%3D+(problem)+%3D%3E+buildEndToEnd(AI))

</div>

---

## 🚀 What I Do

I'm a developer who combines **AI capabilities** with **full-stack development** to solve real problems. I believe the best solutions come from understanding challenges deeply and building complete systems that actually work.

<table>
<tr>
<td width="50%">

**🎯 Problem-First Approach**
- Start with understanding the real challenge
- Design complete, thoughtful solutions  
- Build from frontend to AI backend
- Deploy systems that make an impact

</td>
<td width="50%">

**⚡ Tech Stack**
- **Frontend:** React, Next.js, React Native, TypeScript
- **Backend:** Node.js, Python, Django, WebSockets
- **AI/ML:** LangGraph, OpenAI APIs, ML Models
- **Tools:** Docker, Git, Chrome Extensions

</td>
</tr>
</table>

---

## 💻 Featured Projects

| Project | Description | Tech |
|---------|-------------|------|
| **🤖 AI Chess Tutor** | ML-powered chess improvement platform | AI/ML, Education |
| **⚡ Real-time Chess API** | WebSocket multiplayer chess system | TypeScript, WebSockets, Docker |
| **🎣 Fishing Community App** | React Native social platform with maps | React Native, Maps, Social |
| **🗂️ Context Cabinets** | Chrome extension with AI-powered search | Chrome Extension, AI, Sync |
| **🛠️ Git CLI Assistant** | LangGraph-powered code assistance tool | CLI, LangGraph, Git |

---

## 📊 GitHub Stats

<div align="center">

![GitHub stats](https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=yourusername&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117)

</div>

---

## 🔗 Connect

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-00D4FF?style=for-the-badge&logo=googlechrome&logoColor=white)](https://beckettfrey.com)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your-email@example.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourprofile)

*Building solutions that bridge ideas and reality* 🚀

</div>
