# 💜 Kashish Aggarwal | @kashkeeps

<div align="center">

<!-- Animated Pixel Banner -->
<svg width="800" height="200" viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      @import url('https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap');
      
      .pixel-bg {
        fill: #0a0a0a;
      }
      
      .star {
        fill: #9d4edd;
        animation: twinkle 2s infinite ease-in-out;
      }
      
      .star:nth-child(even) {
        animation-delay: 1s;
      }
      
      .neon-text {
        font-family: 'Press Start 2P', monospace;
        font-size: 24px;
        fill: #9d4edd;
        filter: drop-shadow(0 0 10px #9d4edd);
      }
      
      .subtitle {
        font-family: 'Press Start 2P', monospace;
        font-size: 12px;
        fill: #00ffff;
        filter: drop-shadow(0 0 8px #00ffff);
      }
      
      @keyframes twinkle {
        0%, 100% { opacity: 0.3; }
        50% { opacity: 1; }
      }
      
      @keyframes glow {
        0%, 100% { filter: drop-shadow(0 0 5px #9d4edd); }
        50% { filter: drop-shadow(0 0 20px #9d4edd); }
      }
    </style>
  </defs>
  
  <!-- Background -->
  <rect width="800" height="200" class="pixel-bg"/>
  
  <!-- Twinkling Stars -->
  <rect x="100" y="30" width="4" height="4" class="star"/>
  <rect x="200" y="50" width="4" height="4" class="star"/>
  <rect x="300" y="20" width="4" height="4" class="star"/>
  <rect x="450" y="40" width="4" height="4" class="star"/>
  <rect x="600" y="25" width="4" height="4" class="star"/>
  <rect x="700" y="45" width="4" height="4" class="star"/>
  <rect x="150" y="150" width="4" height="4" class="star"/>
  <rect x="350" y="160" width="4" height="4" class="star"/>
  <rect x="550" y="170" width="4" height="4" class="star"/>
  <rect x="750" y="155" width="4" height="4" class="star"/>
  
  <!-- Main Title -->
  <text x="400" y="80" text-anchor="middle" class="neon-text">KASHISH</text>
  <text x="400" y="120" text-anchor="middle" class="subtitle">dream it, code it, git it girl</text>
</svg>

<!-- Pixel Avatar -->
<div style="margin: 20px 0;">
  <svg width="120" height="120" viewBox="0 0 120 120" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <style>
        .avatar-glow {
          filter: drop-shadow(0 0 15px #9d4edd);
        }
        
        .pixel-face { fill: #ffdbac; }
        .pixel-hair { fill: #8b4513; }
        .pixel-eyes { fill: #000; }
        .pixel-laptop { fill: #2d3748; }
        .pixel-screen { fill: #00ffff; }
        .pixel-cat { fill: #ff69b4; }
      </style>
    </defs>
    
    <!-- Avatar Background -->
    <rect width="120" height="120" fill="#1a1a1a" rx="10" class="avatar-glow"/>
    
    <!-- Girl with Laptop -->
    <!-- Hair -->
    <rect x="40" y="25" width="40" height="30" class="pixel-hair"/>
    
    <!-- Face -->
    <rect x="45" y="35" width="30" height="25" class="pixel-face"/>
    
    <!-- Eyes -->
    <rect x="50" y="40" width="4" height="4" class="pixel-eyes"/>
    <rect x="60" y="40" width="4" height="4" class="pixel-eyes"/>
    
    <!-- Laptop -->
    <rect x="35" y="65" width="50" height="25" class="pixel-laptop"/>
    <rect x="40" y="70" width="40" height="15" class="pixel-screen"/>
    
    <!-- Small Cat -->
    <rect x="90" y="75" width="15" height="10" class="pixel-cat"/>
    <rect x="92" y="72" width="3" height="3" class="pixel-cat"/>
    <rect x="98" y="72" width="3" height="3" class="pixel-cat"/>
  </svg>
</div>

<!-- Typing Animation -->
<div style="font-family: 'Press Start 2P', monospace; color: #00ffff; font-size: 14px; margin: 20px 0;">
  <span id="typing-text">Full Stack Dev</span><span id="cursor" style="animation: blink 1s infinite;">|</span>
</div>

<style>
  @keyframes blink {
    0%, 50% { opacity: 1; }
    51%, 100% { opacity: 0; }
  }
  
  .pixel-card {
    background: linear-gradient(45deg, #1a1a1a, #2d1b69);
    border: 2px solid #9d4edd;
    border-radius: 10px;
    padding: 20px;
    margin: 15px;
    box-shadow: 0 0 20px rgba(157, 78, 221, 0.3);
    transition: all 0.3s ease;
  }
  
  .pixel-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 30px rgba(157, 78, 221, 0.5);
    border-color: #00ffff;
  }
  
  .mood-cat {
    width: 60px;
    height: 60px;
    background: #9d4edd;
    border-radius: 50%;
    margin: 10px;
    display: inline-block;
    transition: all 0.3s ease;
    position: relative;
    cursor: pointer;
  }
  
  .mood-cat:hover {
    transform: scale(1.2);
    box-shadow: 0 0 25px #9d4edd;
  }
  
  .badge {
    background: linear-gradient(45deg, #9d4edd, #00ffff);
    color: #000;
    padding: 8px 16px;
    border-radius: 20px;
    font-family: 'Press Start 2P', monospace;
    font-size: 10px;
    text-decoration: none;
    display: inline-block;
    margin: 5px;
    transition: all 0.3s ease;
    border: 2px solid transparent;
  }
  
  .badge:hover {
    transform: scale(1.1);
    box-shadow: 0 0 15px rgba(157, 78, 221, 0.7);
    border-color: #fff;
  }
  
  .project-card {
    background: linear-gradient(135deg, #1a1a1a, #2d1b69);
    border: 2px solid #00ffff;
    border-radius: 15px;
    padding: 20px;
    margin: 15px;
    box-shadow: 0 0 20px rgba(0, 255, 255, 0.3);
    transition: all 0.3s ease;
    max-width: 300px;
  }
  
  .project-card:hover {
    transform: translateY(-8px) scale(1.02);
    box-shadow: 0 15px 40px rgba(0, 255, 255, 0.5);
    border-color: #9d4edd;
  }
  
  .floating-element {
    position: fixed;
    animation: float 6s ease-in-out infinite;
    z-index: 1000;
  }
  
  @keyframes float {
    0%, 100% { transform: translateY(0px); }
    50% { transform: translateY(-20px); }
  }
  
  .glitch {
    animation: glitch 2s linear infinite;
  }
  
  @keyframes glitch {
    0%, 100% { transform: translate(0); }
    20% { transform: translate(-2px, 2px); }
    40% { transform: translate(-2px, -2px); }
    60% { transform: translate(2px, 2px); }
    80% { transform: translate(2px, -2px); }
  }
</style>

<script>
  // Typing Animation
  const phrases = [
    "Full Stack Dev",
    "Pixel Designer", 
    "Cat Lover",
    "Neon Cat Enthusiast",
    "AI Explorer",
    "Code Dreamer"
  ];
  
  let currentPhrase = 0;
  let currentChar = 0;
  let isDeleting = false;
  
  function typeWriter() {
    const typingElement = document.getElementById('typing-text');
    const current = phrases[currentPhrase];
    
    if (isDeleting) {
      typingElement.textContent = current.substring(0, currentChar - 1);
      currentChar--;
    } else {
      typingElement.textContent = current.substring(0, currentChar + 1);
      currentChar++;
    }
    
    if (!isDeleting && currentChar === current.length) {
      setTimeout(() => isDeleting = true, 2000);
    } else if (isDeleting && currentChar === 0) {
      isDeleting = false;
      currentPhrase = (currentPhrase + 1) % phrases.length;
    }
    
    const speed = isDeleting ? 50 : 100;
    setTimeout(typeWriter, speed);
  }
  
  // Start typing animation
  setTimeout(typeWriter, 1000);
</script>

</div>

---

## 🌟 About Me

<div class="pixel-card">
  
**💜 Passionate about tech, design, and all things whimsical**

**🧠 Interested in generative AI, prompt engineering, and quirky UIs**

**🪐 Inspired by stars, synths, and a little magic**

```python
class KashishAggarwal:
    def __init__(self):
        self.name = "Kashish Aggarwal"
        self.role = "Aspiring Full Stack Developer"
        self.passions = ["coding", "cats", "pixel art", "neon aesthetics"]
        self.currently_learning = ["AI", "Full Stack Development"]
        self.vibe = "dream it, code it, git it girl ✨"
    
    def get_mood(self):
        return "coding with my cat in neon-lit room 🌙"
```

</div>

---

## 🛠️ Tools & Stack

<div class="pixel-card">

```ascii
    ╔═══════════════════════════════════════╗
    ║         KASHISH'S TECH STACK          ║
    ╠═══════════════════════════════════════╣
    ║ Languages: Python 🐍 | C ⚡           ║
    ║ Databases: MySQL 🗄️ | Supabase 🚀     ║
    ║ AI/ML: Gemini AI 🤖 | Prompt Eng 🧠   ║
    ║ Tools: Git | GitHub | Linux | VS Code ║
    ║ Testing: Postman 📮                   ║
    ╚═══════════════════════════════════════╝
```

<div style="margin-top: 20px;">
  <span class="badge">Python</span>
  <span class="badge">C</span>
  <span class="badge">MySQL</span>
  <span class="badge">Supabase</span>
  <span class="badge">Git</span>
  <span class="badge">Linux</span>
  <span class="badge">VS Code</span>
  <span class="badge">Gemini AI</span>
</div>

</div>

---

## 🚀 Featured Projects

<div align="center">
  <div style="display: flex; flex-wrap: wrap; justify-content: center;">
    
    <div class="project-card">
      <h3 style="color: #9d4edd; font-family: 'Press Start 2P', monospace; font-size: 14px;">🌟 Project Alpha</h3>
      <p style="color: #00ffff; font-size: 12px;">AI-powered pixel art generator with neon aesthetics</p>
      <p style="color: #fff; font-size: 10px;">Tech: Python, Gemini AI, CSS</p>
      <a href="#" class="badge">View Project</a>
    </div>
    
    <div class="project-card">
      <h3 style="color: #9d4edd; font-family: 'Press Start 2P', monospace; font-size: 14px;">🎮 Project Beta</h3>
      <p style="color: #00ffff; font-size: 12px;">Retro-style portfolio with interactive elements</p>
      <p style="color: #fff; font-size: 10px;">Tech: HTML, CSS, JavaScript</p>
      <a href="#" class="badge">View Project</a>
    </div>
    
    <div class="project-card">
      <h3 style="color: #9d4edd; font-family: 'Press Start 2P', monospace; font-size: 14px;">🌙 Project Gamma</h3>
      <p style="color: #00ffff; font-size: 12px;">Cat mood tracker with pixel animations</p>
      <p style="color: #fff; font-size: 10px;">Tech: Python, MySQL, CSS</p>
      <a href="#" class="badge">View Project</a>
    </div>
    
  </div>
</div>

---

## 🐱 MoodCat Section

<div align="center" class="pixel-card">
  <h3 style="color: #9d4edd; font-family: 'Press Start 2P', monospace;">Choose Your Mood</h3>
  
  <div class="mood-cat" title="Normal Cat - Just chilling 😺" style="background: linear-gradient(45deg, #9d4edd, #ff69b4);">
    <div style="position: absolute; top: 15px; left: 20px; width: 20px; height: 20px; background: #000; border-radius: 50%;"></div>
    <div style="position: absolute; top: 30px; left: 15px; width: 10px; height: 5px; background: #000; border-radius: 50%;"></div>
    <div style="position: absolute; top: 30px; left: 35px; width: 10px; height: 5px; background: #000; border-radius: 50%;"></div>
  </div>
  
  <div class="mood-cat" title="Sparkle Cat - Feeling magical ✨" style="background: linear-gradient(45deg, #00ffff, #9d4edd);">
    <div style="position: absolute; top: 15px; left: 20px; width: 20px; height: 20px; background: #000; border-radius: 50%;"></div>
    <div style="position: absolute; top: 5px; left: 5px; width: 8px; height: 8px; background: #fff; clip-path: polygon(50% 0%, 61% 35%, 98% 35%, 68% 57%, 79% 91%, 50% 70%, 21% 91%, 32% 57%, 2% 35%, 39% 35%);"></div>
    <div style="position: absolute; top: 40px; right: 10px; width: 6px; height: 6px; background: #fff; clip-path: polygon(50% 0%, 61% 35%, 98% 35%, 68% 57%, 79% 91%, 50% 70%, 21% 91%, 32% 57%, 2% 35%, 39% 35%);"></div>
  </div>
  
  <div class="mood-cat" title="Star Cat - Reaching for the stars 🌟" style="background: linear-gradient(45deg, #ff69b4, #00ffff);">
    <div style="position: absolute; top: 15px; left: 20px; width: 20px; height: 20px; background: #000; border-radius: 50%;"></div>
    <div style="position: absolute; top: 0px; left: 25px; width: 10px; height: 10px; background: #fff; clip-path: polygon(50% 0%, 61% 35%, 98% 35%, 68% 57%, 79% 91%, 50% 70%, 21% 91%, 32% 57%, 2% 35%, 39% 35%);"></div>
  </div>
  
  <p style="color: #00ffff; font-family: 'Press Start 2P', monospace; font-size: 10px; margin-top: 20px;">
    "Every cat has its pixel" - Ancient Developer Wisdom
  </p>
</div>

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=kashkeeps&show_icons=true&theme=tokyonight&border_color=9d4edd&title_color=9d4edd&icon_color=00ffff" alt="Kashish's GitHub Stats" />
  
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kashkeeps&layout=compact&theme=tokyonight&border_color=9d4edd&title_color=9d4edd" alt="Top Languages" />
  
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=kashkeeps&theme=tokyonight&border=9d4edd&stroke=00ffff&ring=9d4edd&fire=ff69b4&currStreakLabel=00ffff" alt="GitHub Streak" />
</div>

---

## 🌐 Live Project Showcase

<div align="center">
  <div class="project-card" style="background: linear-gradient(135deg, #9d4edd, #00ffff); color: #000; max-width: 400px;">
    <h3 style="font-family: 'Press Start 2P', monospace; font-size: 16px;">🚀 LIVE PROJECT</h3>
    <p style="font-size: 12px; margin: 15px 0;">Interactive pixel portfolio with neon aesthetics</p>
    <div style="font-size: 10px; margin: 10px 0;">
      <span style="background: rgba(0,0,0,0.2); padding: 4px 8px; border-radius: 10px; margin: 2px;">HTML</span>
      <span style="background: rgba(0,0,0,0.2); padding: 4px 8px; border-radius: 10px; margin: 2px;">CSS</span>
      <span style="background: rgba(0,0,0,0.2); padding: 4px 8px; border-radius: 10px; margin: 2px;">JavaScript</span>
    </div>
    <a href="#" style="background: #000; color: #00ffff; padding: 10px 20px; text-decoration: none; border-radius: 15px; font-family: 'Press Start 2P', monospace; font-size: 10px; display: inline-block; margin-top: 10px;">VIEW LIVE →</a>
  </div>
</div>

---

## 🎯 Interactive Badges

<div align="center">
  <a href="mailto:your.email@example.com" class="badge">📧 Contact Me</a>
  <a href="#" class="badge">🌐 Portfolio</a>
  <a href="https://github.com/kashkeeps" class="badge">🐱 GitHub</a>
  <a href="#" class="badge">💜 Built with Love</a>
  <a href="#" class="badge">🐍 Python Powered</a>
  <a href="#" class="badge">✨ Pixel Perfect</a>
</div>

---

## 🎭 Easter Egg Zone

<div align="center" class="pixel-card">
  <details>
    <summary style="color: #9d4edd; font-family: 'Press Start 2P', monospace; cursor: pointer;">🎮 Click for Secret</summary>
    <div style="margin-top: 20px;">
      <p style="color: #00ffff; font-family: 'Press Start 2P', monospace; font-size: 12px;">
        "In a world full of websites, be a pixel art masterpiece" 🌌
      </p>
      <div style="margin: 20px 0;">
        <svg width="100" height="50" viewBox="0 0 100 50">
          <rect x="10" y="10" width="80" height="30" fill="#9d4edd" rx="5"/>
          <text x="50" y="30" text-anchor="middle" fill="#000" font-family="Press Start 2P" font-size="8">SECRET</text>
        </svg>
      </div>
    </div>
  </details>
</div>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=9d4edd&height=100&section=footer&text=Thanks%20for%20visiting!&fontSize=24&fontColor=00ffff&animation=twinkling" />
  
  <p style="color: #9d4edd; font-family: 'Press Start 2P', monospace; font-size: 12px; margin-top: 20px;">
    Made with 💜 and lots of ☕ by Kashish
  </p>
  
  <p style="color: #00ffff; font-family: 'Press Start 2P', monospace; font-size: 10px;">
    "Keep coding, keep dreaming, keep being awesome!" ✨
  </p>
</div>

<!-- Floating Elements -->
<div class="floating-element" style="top: 20%; left: 10%; animation-delay: 0s;">🌟</div>
<div class="floating-element" style="top: 60%; right: 15%; animation-delay: 2s;">🐱</div>
<div class="floating-element" style="top: 40%; right: 10%; animation-delay: 4s;">✨</div>
<div class="floating-element" style="top: 80%; left: 20%; animation-delay: 1s;">🌙</div>

<!-- Link to Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&family=VT323&display=swap" rel="stylesheet">

<!-- Visitor Counter -->
<div align="center" style="margin-top: 30px;">
  <img src="https://komarev.com/ghpvc/?username=kashkeeps&color=9d4edd&style=for-the-badge&label=PIXEL+VISITORS" alt="Visitor Count" />
</div>
