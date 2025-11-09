<div align="center" style="background-color:#0d1117; color:white; padding:40px; border-radius:20px;">
  
  <h1>👋 Hi, I'm <span style="color:#58a6ff;">Belal Nasser</span></h1>
  <h3>
    <span id="typing" style="color:#8b949e;">Building Robust Back-End Solutions...</span>
  </h3>

  <p><em>"Keep building, keep learning."</em></p>

  <br>

  <h2>🧠 About Me</h2>
  <p>
    I'm a passionate <strong>Back-End Software Engineer</strong> who loves crafting scalable systems and secure APIs. <br>
    Currently pursuing my degree in <strong>Computer Science and Mathematics</strong> at <strong>Al-Azhar University</strong>.
  </p>

  <br>

  <h2>⚙️ Tech Stack</h2>
  <p>
    <img src="https://skillicons.dev/icons?i=java,spring,python,django,cpp,js,vue,tailwind,html,css,mysql,postgresql,linux,git" alt="tech stack" />
  </p>

  <br>

  <h2>🌍 Networking & Security</h2>
  <p>
    <a href="https://tryhackme.com/p/011022bn" target="_blank" style="margin: 10px;">
      <img src="https://img.shields.io/badge/TryHackMe-011022bn-red?style=for-the-badge&logo=tryhackme" alt="TryHackMe" />
    </a>
    <a href="https://academy.hackthebox.com/dashboard" target="_blank" style="margin: 10px;">
      <img src="https://img.shields.io/badge/Hack%20The%20Box-Belal11-brightgreen?style=for-the-badge&logo=hackthebox" alt="HackTheBox" />
    </a>
  </p>

  <br>

  <h2>📊 GitHub Stats</h2>
  <p>
    <img src="https://github-readme-stats.vercel.app/api?username=Belal303111&show_icons=true&theme=tokyonight" alt="Belal's GitHub Stats" />
  </p>
  <p>
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=Belal303111&theme=tokyonight" alt="GitHub Streak" />
  </p>
  <p>
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Belal303111&layout=compact&theme=tokyonight" alt="Top Languages" />
  </p>

  <br>

  <h2>💼 Connect with Me</h2>
  <p>
    <a href="https://www.linkedin.com/in/belal-nasser-3306972a5" target="_blank" style="margin: 10px;">
      <img src="https://img.shields.io/badge/LinkedIn-Belal%20Nasser-blue?style=for-the-badge&logo=linkedin" />
    </a>
    <a href="mailto:011022bn@gmail.com" target="_blank" style="margin: 10px;">
      <img src="https://img.shields.io/badge/Gmail-011022bn%40gmail.com-red?style=for-the-badge&logo=gmail" />
    </a>
  </p>

  <br>

  <h2>🚀 Featured Project</h2>
  <p>
    <a href="https://github.com/Belal303111/AirBnB_clone_v2" target="_blank">
      <img src="https://img.shields.io/badge/AirBnB_Clone-%230A66C2.svg?&style=for-the-badge&logo=github&logoColor=white" alt="AirBnB Clone" />
    </a>
  </p>

  <br>

  <p style="color:#8b949e;">© 2025 Belal Nasser | Crafted with ❤️ and Code</p>

</div>

<script>
const typingText = ["Building Robust Back-End Solutions...", "Crafting Secure APIs...", "Empowering Systems with Java & Spring Boot..."]; 
let count = 0, index = 0, currentText = '', letter = '';
(function type(){
  if (count === typingText.length) count = 0;
  currentText = typingText[count];
  letter = currentText.slice(0, ++index);
  document.getElementById('typing').textContent = letter;
  if (letter.length === currentText.length){
    count++; index = 0;
    setTimeout(type, 1500);
  } else {
    setTimeout(type, 100);
  }
})();
</script>
