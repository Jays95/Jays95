<div align="center">
  <!-- ✨ Enhanced Typing Animation Header -->
  <h1 class="typing-header">Hi, I'm Jayson Ranck 👋</h1>
  <h3 class="subtitle">Flask | AI Developer | Problem Solver | Welcome to my GitHub space! 🚀</h3>

  <!-- 🌠 Hero Animation -->
  <img src="https://media.giphy.com/media/LmN0CkbY2tXqE/giphy.gif" width="400" alt="Dynamic Developer Animation" class="hero-animation"/>
</div>

<style>
  /* General Styles */
  body {
    background: linear-gradient(135deg, #1a1a2e 0%, #16213e 100%);
    color: #e0e0e0;
    font-family: 'Poppins', sans-serif;
    margin: 0;
    padding: 20px;
    overflow-x: hidden;
  }

  /* Typing Header Animation */
  .typing-header {
    font-size: 2.5rem;
    font-weight: 600;
    color: #F76308;
    overflow: hidden;
    white-space: nowrap;
    border-right: 4px solid #F76308;
    animation: typing 4s steps(30, end) infinite, blink-caret 0.75s step-end infinite;
    margin: 20px 0;
  }

  .subtitle {
    font-size: 1.2rem;
    color: #ffffff;
    opacity: 0;
    animation: fadeIn 2s ease-in forwards 1s;
  }

  /* Hero Animation */
  .hero-animation {
    border-radius: 15px;
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.3);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    animation: slideIn 1s ease-out;
  }

  .hero-animation:hover {
    transform: scale(1.05);
    box-shadow: 0 12px 30px rgba(0, 0, 0, 0.5);
  }

  /* Section Animations */
  .section {
    opacity: 0;
    transform: translateY(20px);
    animation: fadeInUp 1s ease-out forwards;
    animation-delay: calc(0.2s * var(--section-order));
    margin: 40px 0;
  }

  /* Badge and Icon Hover Effects */
  img[src*="shields.io"], img[src*="skillicons.dev"], img[src*="github-readme-stats"], img[src*="github-profile-trophy"], img[src*="github-contributor-stats"], img[src*="visitcount"] {
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }

  img:hover {
    transform: scale(1.1);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
  }

  /* Particle Background */
  #particles-js {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: -1;
  }

  /* Keyframes */
  @keyframes typing {
    0% { width: 0; }
    50% { width: 100%; }
    100% { width: 0; }
  }

  @keyframes blink-caret {
    50% { border-color: transparent; }
  }

  @keyframes fadeIn {
    to { opacity: 1; }
  }

  @keyframes fadeInUp {
    to { opacity: 1; transform: translateY(0); }
  }

  @keyframes slideIn {
    from { transform: translateY(50px); opacity: 0; }
    to { transform: translateY(0); opacity: 1; }
  }

  /* Responsive Design */
  @media (max-width: 600px) {
    .typing-header { font-size: 1.8rem; }
    .subtitle { font-size: 1rem; }
    .hero-animation { width: 100%; max-width: 300px; }
  }
</style>

<!-- Particle.js for Background Animation -->
<script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
<script>
  particlesJS('particles-js', {
    particles: {
      number: { value: 80, density: { enable: true, value_area: 800 } },
      color: { value: '#F76308' },
      shape: { type: 'circle' },
      opacity: { value: 0.5, random: true },
      size: { value: 3, random: true },
      line_linked: { enable: false },
      move: { enable: true, speed: 2, direction: 'none', random: true }
    },
    interactivity: {
      detect_on: 'canvas',
      events: { onhover: { enable: true, mode: 'repulse' }, onclick: { enable: true, mode: 'push' } },
      modes: { repulse: { distance: 100 }, push: { particles_nb: 4 } }
    }
  });
</script>

<div id="particles-js"></div>

---

# 💫 About Me:
<div class="section" style="--section-order: 1;">
🚀 I thrive on **structure and challenge**. Currently building a **Flask-based AI app** to make user experiences more engaging.  
🧠 Love solving problems, breaking them down into clean paths forward.  
⚾ When I’m not coding, I’m watching baseball or working on my swing.
</div>

---

## 🌐 Connect with Me:
<div class="section" style="--section-order: 2;" align="center">
  <a href="https://www.linkedin.com/in/jayson-ranck-88a1a5253/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
</div>

---

## 💻 Tech Stack:
<div class="section" style="--section-order: 3;" align="center">
  <img src="https://skillicons.dev/icons?i=python,flask,django,fastapi,jinja,react,nodejs&theme=dark" />
  <br/>
  <img src="https://skillicons.dev/icons?i=mysql,sqlite,supabase,firebase,docker,git,github&theme=dark" />
  <br/>
  <img src="https://skillicons.dev/icons?i=figma,canva,postman,vscode&theme=dark" />
</div>

---

## 📊 GitHub Stats:
<div class="section" style="--section-order: 4;" align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Jays95&theme=tokyonight&show_icons=true&hide_border=false&border_radius=10" width="350"/>
  <img src="https://streak-stats.demolab.com/?user=Jays95&theme=tokyonight&hide_border=false&border_radius=10" width="350"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Jays95&layout=compact&theme=tokyonight&hide_border=false&border_radius=10" width="350"/>
</div>

---

## 🏆 GitHub Trophies:
<div class="section" style="--section-order: 5;" align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Jays95&theme=radical&no-frame=false&no-bg=false&margin-w=10"/>
</div>

---

### 🔝 Top Contributed Repos:
<div class="section" style="--section-order: 6;" align="center">
  <img src="https://github-contributor-stats.vercel.app/api?username=Jays95&limit=5&theme=onedark&combine_all_yearly_contributions=true"/>
</div>

---

## 🔢 Visitor Counter:
<div class="section" style="--section-order: 7;" align="center">
  <a href="https://visitcount.itsvg.in" target="_blank">
    <img src="https://visitcount.itsvg.in/api?id=Jays95&label=👀 Visitors&color=1&icon=2&pretty=true" alt="Visitor Count Badge" />
  </a>
</div>

---

## 💰 Support Me:
<div class="section" style="--section-order: 8;" align="center">
  <a href="https://paypal.me/jayson.ranckjay@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Donate-PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white" alt="PayPal"/>
  </a>
</div>

<!-- Made with ❤️ by Jayson | GPRM: https://gprm.itsvg.in -->
