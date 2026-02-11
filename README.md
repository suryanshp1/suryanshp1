<div align="center">

<!-- Van Gogh Starry Night Animated Header -->
<svg width="100%" height="200" xmlns="http://www.w3.org/2000/svg" style="background: linear-gradient(135deg, #0B1E38 0%, #123f77 50%, #2f3774 100%);">
  <!-- Swirling Sky Pattern -->
  <defs>
    <radialGradient id="starGlow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" style="stop-color:#FFC512;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#F5DB37;stop-opacity:0" />
    </radialGradient>
    
    <!-- Swirling Animation -->
    <style>
      @keyframes swirl {
        0% { transform: rotate(0deg); opacity: 0.6; }
        50% { opacity: 1; }
        100% { transform: rotate(360deg); opacity: 0.6; }
      }
      @keyframes pulse {
        0%, 100% { transform: scale(1); opacity: 0.8; }
        50% { transform: scale(1.2); opacity: 1; }
      }
      @keyframes twinkle {
        0%, 100% { opacity: 0.5; }
        50% { opacity: 1; }
      }
      .swirl { animation: swirl 20s linear infinite; transform-origin: center; }
      .star { animation: pulse 3s ease-in-out infinite; }
      .small-star { animation: twinkle 2s ease-in-out infinite; }
    </style>
  </defs>
  
  <!-- Large Swirling Stars -->
  <circle class="star" cx="15%" cy="30%" r="8" fill="url(#starGlow)">
    <animate attributeName="cy" values="30%;35%;30%" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle class="star" cx="85%" cy="40%" r="6" fill="url(#starGlow)">
    <animate attributeName="cy" values="40%;45%;40%" dur="5s" repeatCount="indefinite"/>
  </circle>
  <circle class="star" cx="50%" cy="25%" r="10" fill="url(#starGlow)">
    <animate attributeName="r" values="10;12;10" dur="3s" repeatCount="indefinite"/>
  </circle>
  
  <!-- Small Twinkling Stars -->
  <circle class="small-star" cx="30%" cy="20%" r="2" fill="#F5DB37"/>
  <circle class="small-star" cx="70%" cy="25%" r="2" fill="#FFC512" style="animation-delay: 0.5s;"/>
  <circle class="small-star" cx="60%" cy="50%" r="2" fill="#E8E163" style="animation-delay: 1s;"/>
  <circle class="small-star" cx="40%" cy="55%" r="2" fill="#F5DB37" style="animation-delay: 1.5s;"/>
  <circle class="small-star" cx="90%" cy="60%" r="2" fill="#FFC512" style="animation-delay: 2s;"/>
  <circle class="small-star" cx="20%" cy="65%" r="2" fill="#E8E163" style="animation-delay: 2.5s;"/>
  
  <!-- Van Gogh Swirls -->
  <g class="swirl" opacity="0.3">
    <path d="M 100,100 Q 120,80 140,100 T 180,100" stroke="#7FC5DC" stroke-width="2" fill="none"/>
    <path d="M 300,120 Q 280,100 260,120 T 220,120" stroke="#4888C8" stroke-width="2" fill="none"/>
  </g>
  
  <!-- Title Text -->
  <text x="50%" y="55%" text-anchor="middle" font-family="Georgia, serif" font-size="42" font-weight="bold" fill="#FFC512" stroke="#DB901C" stroke-width="1">
    👋 Suryansh Pandey
  </text>
  <text x="50%" y="68%" text-anchor="middle" font-family="Georgia, serif" font-size="18" fill="#7FC5DC" font-style="italic">
    Backend Engineer | AI Automation | System Design
  </text>
  <text x="50%" y="80%" text-anchor="middle" font-family="Georgia, serif" font-size="14" fill="#F5DB37">
    ✨ Building scalable APIs & autonomous AI agents ✨
  </text>
</svg>

</div>

---

<!-- Van Gogh Brushstroke Divider -->
<div align="center">
<svg width="100%" height="30" xmlns="http://www.w3.org/2000/svg">
  <path d="M 0,15 Q 50,5 100,15 T 200,15 T 300,15 T 400,15 T 500,15 T 600,15 T 700,15 T 800,15 T 900,15 T 1000,15" 
        stroke="#4888C8" stroke-width="3" fill="none" opacity="0.6"/>
  <path d="M 0,20 Q 50,25 100,20 T 200,20 T 300,20 T 400,20 T 500,20 T 600,20 T 700,20 T 800,20 T 900,20 T 1000,20" 
        stroke="#DB901C" stroke-width="2" fill="none" opacity="0.4"/>
</svg>
</div>

## 🎨 About Me

<table>
<tr>
<td width="60%">

🧠 **Passionate Creator** focused on:
- **AI-driven automation** that transforms workflows
- **Backend development** with Python & FastAPI mastery
- **Cybersecurity** & DevSecOps innovation
- Built my own **SAST agent** for intelligent code analysis

💡 **Philosophy**: *"Like Van Gogh painted emotions, I code experiences that empower."*

🌏 **Currently seeking**: Remote roles in backend systems, AI agents, or data engineering

</td>
<td width="40%" align="center">

<!-- Van Gogh Inspired Badge -->
<svg width="150" height="150" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <radialGradient id="nightGlow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" style="stop-color:#4888C8;stop-opacity:0.8" />
      <stop offset="100%" style="stop-color:#123f77;stop-opacity:1" />
    </radialGradient>
  </defs>
  <circle cx="75" cy="75" r="70" fill="url(#nightGlow)" stroke="#FFC512" stroke-width="3"/>
  <text x="50%" y="45%" text-anchor="middle" font-size="40" fill="#FFC512">👨‍💻</text>
  <text x="50%" y="65%" text-anchor="middle" font-size="14" fill="#F5DB37" font-weight="bold">CREATIVE</text>
  <text x="50%" y="75%" text-anchor="middle" font-size="12" fill="#7FC5DC">ENGINEER</text>
</svg>

</td>
</tr>
</table>

---

<!-- Van Gogh Brushstroke Divider -->
<div align="center">
<svg width="100%" height="25" xmlns="http://www.w3.org/2000/svg">
  <path d="M 0,12 Q 60,18 120,12 T 240,12 T 360,12 T 480,12 T 600,12 T 720,12 T 840,12 T 960,12 T 1080,12" 
        stroke="#556B2F" stroke-width="3" fill="none" opacity="0.5"/>
</svg>
</div>

## 🧰 Artist's Toolkit (Tech Stack)

<div align="center">

| 🎨 **Craft** | 🖌️ **Tools & Pigments** |
|:------------|:------------------------|
| **Languages** | <img src="https://img.shields.io/badge/Python-123f77?style=for-the-badge&logo=python&logoColor=FFC512"/> <img src="https://img.shields.io/badge/JavaScript-DB901C?style=for-the-badge&logo=javascript&logoColor=0B1E38"/> |
| **Backend Canvas** | <img src="https://img.shields.io/badge/FastAPI-4888C8?style=for-the-badge&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/Flask-556B2F?style=for-the-badge&logo=flask&logoColor=F5DB37"/> <img src="https://img.shields.io/badge/Node.js-2f3774?style=for-the-badge&logo=node.js&logoColor=7FC5DC"/> |
| **AI Brushes** | <img src="https://img.shields.io/badge/LangChain-FFC512?style=for-the-badge&logo=chainlink&logoColor=0B1E38"/> <img src="https://img.shields.io/badge/OpenAI-123f77?style=for-the-badge&logo=openai&logoColor=F5DB37"/> |
| **Data Palettes** | <img src="https://img.shields.io/badge/PostgreSQL-4888C8?style=for-the-badge&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/MongoDB-556B2F?style=for-the-badge&logo=mongodb&logoColor=7FC5DC"/> <img src="https://img.shields.io/badge/Redis-DB901C?style=for-the-badge&logo=redis&logoColor=white"/> |
| **DevOps Studio** | <img src="https://img.shields.io/badge/Docker-2f3774?style=for-the-badge&logo=docker&logoColor=7FC5DC"/> <img src="https://img.shields.io/badge/AWS-123f77?style=for-the-badge&logo=amazon-aws&logoColor=FFC512"/> <img src="https://img.shields.io/badge/GitHub_Actions-0B1E38?style=for-the-badge&logo=github-actions&logoColor=F5DB37"/> |
| **Security Varnish** | <img src="https://img.shields.io/badge/SAST-DB901C?style=for-the-badge&logo=security&logoColor=white"/> <img src="https://img.shields.io/badge/Pytest-4888C8?style=for-the-badge&logo=pytest&logoColor=white"/> |

</div>

---

<!-- Van Gogh Brushstroke Divider -->
<div align="center">
<svg width="100%" height="30" xmlns="http://www.w3.org/2000/svg">
  <path d="M 0,15 Q 40,8 80,15 T 160,15 T 240,15 T 320,15 T 400,15 T 480,15 T 560,15 T 640,15 T 720,15 T 800,15 T 880,15 T 960,15 T 1040,15" 
        stroke="#7FC5DC" stroke-width="4" fill="none" opacity="0.6"/>
  <path d="M 0,22 Q 40,28 80,22 T 160,22 T 240,22 T 320,22 T 400,22 T 480,22 T 560,22 T 640,22 T 720,22 T 800,22" 
        stroke="#FFC512" stroke-width="2" fill="none" opacity="0.5"/>
</svg>
</div>

## 🖼️ Gallery of Creations (Featured Projects)

<!-- Project 1: Bluesky eBook Generator -->
<div align="center">
<table>
<tr>
<td width="70%">

### 🧩 [Bluesky eBook Generator AI Agent](https://github.com/suryanshp1/bluesky-ebook-generator-ai-agent)

**An autonomous masterpiece** that generates eBooks and posts interactive threads to Bluesky with minimal human touch.

🛠️ **Palette**: FastAPI · LangChain · OpenAI API · PDFKit  
🚀 **Vision**: Automates creative workflows with AI-driven storytelling

> *"Creativity automated, like brush meeting canvas."*

</td>
<td width="30%" align="center">

<svg width="120" height="120" xmlns="http://www.w3.org/2000/svg">
  <rect width="120" height="120" fill="#123f77" stroke="#FFC512" stroke-width="4" rx="10"/>
  <text x="50%" y="50%" text-anchor="middle" font-size="50" fill="#7FC5DC">📚</text>
  <circle cx="20" cy="20" r="5" fill="#FFC512">
    <animate attributeName="opacity" values="0.5;1;0.5" dur="2s" repeatCount="indefinite"/>
  </circle>
</svg>

</td>
</tr>
</table>
</div>

---

<!-- Project 2: SAST Agent -->
<div align="center">
<table>
<tr>
<td width="30%" align="center">

<svg width="120" height="120" xmlns="http://www.w3.org/2000/svg">
  <rect width="120" height="120" fill="#2f3774" stroke="#DB901C" stroke-width="4" rx="10"/>
  <text x="50%" y="50%" text-anchor="middle" font-size="50" fill="#F5DB37">🔒</text>
  <circle cx="100" cy="20" r="5" fill="#DB901C">
    <animate attributeName="opacity" values="0.5;1;0.5" dur="2.5s" repeatCount="indefinite"/>
  </circle>
</svg>

</td>
<td width="70%">

### 🔍 [Python SAST Agent](https://github.com/suryanshp1/python-SAST-agent)

**Security as art** - An autonomous agent performing static analysis, detecting vulnerabilities, and raising **auto-fix PRs**.

🧠 **Technique**: GitHub API + Python AST parsing  
🔒 **Purpose**: Early prototype for intelligent DevSecOps automation

> *"Guarding code integrity with the precision of a master's brushstroke."*

</td>
</tr>
</table>
</div>

---

<!-- Project 3: Medical Chatbot -->
<div align="center">
<table>
<tr>
<td width="70%">

### 💬 [End-to-End Medical Chatbot](https://github.com/suryanshp1/End-to-end-medical-chatbot)

**Compassionate AI** - A conversational assistant for basic medical queries using advanced NLP models.

🩺 **Foundation**: FastAPI · Hugging Face Transformers · DialogFlow  
💡 **Impact**: Making healthcare insights accessible through intelligent conversation

> *"Technology that heals through understanding."*

</td>
<td width="30%" align="center">

<svg width="120" height="120" xmlns="http://www.w3.org/2000/svg">
  <rect width="120" height="120" fill="#4888C8" stroke="#556B2F" stroke-width="4" rx="10"/>
  <text x="50%" y="50%" text-anchor="middle" font-size="50" fill="#FFC512">🩺</text>
  <circle cx="100" cy="100" r="5" fill="#7FC5DC">
    <animate attributeName="opacity" values="0.5;1;0.5" dur="3s" repeatCount="indefinite"/>
  </circle>
</svg>

</td>
</tr>
</table>
</div>

---

<!-- Project 4: AI Web Scraper -->
<div align="center">
<table>
<tr>
<td width="30%" align="center">

<svg width="120" height="120" xmlns="http://www.w3.org/2000/svg">
  <rect width="120" height="120" fill="#556B2F" stroke="#7FC5DC" stroke-width="4" rx="10"/>
  <text x="50%" y="50%" text-anchor="middle" font-size="50" fill="#E8E163">🕸️</text>
  <circle cx="20" cy="100" r="5" fill="#4888C8">
    <animate attributeName="opacity" values="0.5;1;0.5" dur="3.5s" repeatCount="indefinite"/>
  </circle>
</svg>

</td>
<td width="70%">

### 🕸️ [AI Web Scraper](https://github.com/suryanshp1/ai-webscrapper)

**Intelligent extraction** - LLM-powered scraper that extracts structured insights from dynamic web pages.

⚙️ **Brushwork**: Selenium + Ollama + Prompt-based classification  
🎯 **Innovation**: Turning unstructured web data into actionable knowledge

> *"Capturing the essence of information, like light on water."*

</td>
</tr>
</table>
</div>

---

<!-- Van Gogh Brushstroke Divider -->
<div align="center">
<svg width="100%" height="30" xmlns="http://www.w3.org/2000/svg">
  <path d="M 0,15 Q 50,20 100,15 T 200,15 T 300,15 T 400,15 T 500,15 T 600,15 T 700,15 T 800,15 T 900,15" 
        stroke="#DB901C" stroke-width="3" fill="none" opacity="0.6"/>
  <path d="M 0,22 Q 50,17 100,22 T 200,22 T 300,22 T 400,22 T 500,22 T 600,22 T 700,22 T 800,22 T 900,22" 
        stroke="#FFC512" stroke-width="2" fill="none" opacity="0.5"/>
</svg>
</div>

## 🌐 Letters to the World (Connect With Me)

<div align="center">

<!-- Van Gogh Inspired Contact Section -->
<table>
<tr>
<td align="center" width="33%">

<svg width="80" height="80" xmlns="http://www.w3.org/2000/svg">
  <circle cx="40" cy="40" r="35" fill="#123f77" stroke="#FFC512" stroke-width="3"/>
  <text x="50%" y="60%" text-anchor="middle" font-size="35" fill="#7FC5DC">💼</text>
</svg>

**[LinkedIn](https://www.linkedin.com/in/suryanshp1/)**  
<sub>Professional Canvas</sub>

</td>
<td align="center" width="33%">

<svg width="80" height="80" xmlns="http://www.w3.org/2000/svg">
  <circle cx="40" cy="40" r="35" fill="#DB901C" stroke="#4888C8" stroke-width="3"/>
  <text x="50%" y="60%" text-anchor="middle" font-size="35" fill="#F5DB37">✉️</text>
</svg>

**[Email](mailto:suryanshp1@gmail.com)**  
<sub>Direct Correspondence</sub>

</td>
<td align="center" width="33%">

<svg width="80" height="80" xmlns="http://www.w3.org/2000/svg">
  <circle cx="40" cy="40" r="35" fill="#2f3774" stroke="#7FC5DC" stroke-width="3"/>
  <text x="50%" y="60%" text-anchor="middle" font-size="35" fill="#FFC512">🐙</text>
</svg>

**[GitHub](https://github.com/suryanshp1)**  
<sub>Code Gallery</sub>

</td>
</tr>
</table>

</div>

---

<!-- Van Gogh Signature Footer -->
<div align="center">
<svg width="100%" height="100" xmlns="http://www.w3.org/2000/svg" style="background: linear-gradient(135deg, #0B1E38 0%, #123f77 100%);">
  <!-- Animated Stars Footer -->
  <circle cx="10%" cy="30%" r="3" fill="#FFC512">
    <animate attributeName="opacity" values="0.4;1;0.4" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="90%" cy="40%" r="3" fill="#F5DB37">
    <animate attributeName="opacity" values="0.4;1;0.4" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="50%" cy="20%" r="4" fill="#E8E163">
    <animate attributeName="opacity" values="0.4;1;0.4" dur="2.5s" repeatCount="indefinite"/>
  </circle>
  
  <!-- Quote -->
  <text x="50%" y="60%" text-anchor="middle" font-family="Georgia, serif" font-size="18" fill="#7FC5DC" font-style="italic">
    "Code that scales, systems that adapt, AI that empowers"
  </text>
  <text x="50%" y="80%" text-anchor="middle" font-family="Georgia, serif" font-size="12" fill="#4888C8">
    ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  </text>
</svg>
</div>

<div align="center">
<sub>🎨 Inspired by Vincent van Gogh's <i>Starry Night</i> · Crafted with passion & precision</sub>
</div>
