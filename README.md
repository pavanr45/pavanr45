<!-- 🌊 Enhanced Moving Wave Banner with SVG Animation -->
<div align="center">
  <svg viewBox="0 0 1440 320" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="xMidYMid meet">
    <defs>
      <path id="gentle-wave" d="M 0,200 C 300,150 600,250 900,200 C 1200,150 1350,250 1440,200 L 1440,320 L 0,320 Z"/>
    </defs>
    <g class="waves">
      <use href="#gentle-wave" fill="#00c6ff" opacity="0.6" transform="scale(1.1) translate(0, -20)"/>
      <use href="#gentle-wave" fill="#0072ff" opacity="0.4" transform="scale(1.05) translate(0, -10)"/>
      <use href="#gentle-wave" fill="#00eaff" opacity="0.8"/>
    </g>
    <!-- Name Text Overlay -->
    <text x="720" y="120" text-anchor="middle" fill="#ffffff" font-size="60" font-weight="bold" font-family="Arial, sans-serif">
      PAVAN RATHOD
    </text>
    <text x="720" y="160" text-anchor="middle" fill="#ffffff" font-size="20" font-family="Arial, sans-serif" opacity="0.9">
      Full Stack Developer
    </text>
  </svg>
</div>

<style>
@keyframes move-forever {
  0% { transform: translate3d(-90px,0%,0); }
  100% { transform: translate3d(85px,0%,0); }
}
.waves {
  position: relative;
  width: 100%;
  height: 15em;
  margin-bottom: -7px;
}
.waves > use {
  animation: move-forever 2s -2s linear infinite;
}
.waves > use:nth-child(2) {
  animation-delay: -3s;
  animation-duration: 6s;
}
.waves > use:nth-child(3) {
  animation-delay: -4s;
  animation-duration: 3s;
}
</style>[web:1][web:3]

<!-- ✨ Enhanced Glow Effect with Pulse Animation -->
<h2 align="center">
  <span class="glow-text">Full Stack Developer 🚀</span>
</h2>

<style>
.glow-text {
  background: linear-gradient(45deg, #00eaff, #0072ff, #00c6ff, #00eaff);
  background-size: 400% 400%;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  animation: glow 3s ease-in-out infinite alternate, pulse 2s infinite;
  text-shadow: 0 0 20px rgba(0, 234, 255, 0.5);
  font-size: 2.2em;
  font-weight: bold;
}
@keyframes glow {
  0% { background-position: 0% 50%; }
  100% { background-position: 100% 50%; }
}
@keyframes pulse {
  0%, 100% { transform: scale(1); }
  50% { transform: scale(1.05); }
}
@media (max-width: 768px) {
  .glow-text { font-size: 1.8em; }
}
</style>[web:2]

<!-- 📝 Enhanced Typing Effect with Multiple Lines -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?size=28&duration=4000&color=00E7FF&center=true&vCenter=true&width=700&lines=Java+%7C+Spring+Boot+Developer;Full+Stack+Developer+🚀;Intern+at+PitonSystem+Pvt+Ltd;Mastering+Microservices+%26+Cloud;Building+Scalable+Applications;Learning+DevOps+Daily" alt="Typing SVG"/>
</p>

---

## 👨‍💻 About Me  
<div align="center">
  <img src="https://img.shields.io/badge/Status-🔥%20Actively%20Coding-blue?style=for-the-badge&logo=git" alt="Status"/>
</div>

- 💼 **Currently Intern at PitonSystem Pvt Ltd** as **Software Developer**  
  → Building enterprise solutions with **PHP, CakePHP, MySQL, HTML, CSS, JavaScript**  
- 🔭 **Completed 6-month Full Stack Training** at **Kiran Academy** with certification  
- 🌱 **Mastered**: Java, Spring Boot, MySQL, React.js, Angular, REST APIs  
- ☁️ **Exploring**: AWS Cloud, Docker, Kubernetes, Microservices Architecture  
- 📈 **Currently Learning**: DevOps, CI/CD Pipelines, Advanced Spring Security  
- 📨 **Email**: pavan48755@gmail.com  
- ⚡ **Fun Fact**: Cricket enthusiast 🏏 | Code contributor | Problem solver  

---

## 🌐 Connect with Me
<p align="left">
  <a href="https://www.linkedin.com/in/pavanrathod">
    <img src="https://skillicons.dev/icons?i=linkedin" width="60" height="60"/>
  </a>
  <a href="https://github.com/pavanrathod">
    <img src="https://skillicons.dev/icons?i=github" width="60" height="60"/>
  </a>
  <a href="mailto:pavan48755@gmail.com">
    <img src="https://skillicons.dev/icons?i=email" width="60" height="60"/>
  </a>
</p>

---

# 🛠️ Tech Stack  

### **Backend** ⭐⭐⭐⭐⭐
<p align="left">
  <img src="https://skillicons.dev/icons?i=java,spring,hibernate,mysql,redis" width="55"/>
  <img src="https://skillicons.dev/icons?i=php,cakephp,nodejs" width="55"/>
</p>

### **Frontend** ⭐⭐⭐⭐
<p align="left">
  <img src="https://skillicons.dev/icons?i=html,css,js,typescript,bootstrap,tailwind,react,angular" width="55"/>
</p>

### **DevOps & Tools** ⭐⭐⭐
<p align="left">
  <img src="https://skillicons.dev/icons?i=git,github,docker,kubernetes,aws,jenkins" width="55"/>
  <img src="https://skillicons.dev/icons?i= postman,vscode,gradle,maven" width="55"/>
</p>

---

# 🚀 Featured Projects  

### 🔹 **AmazeCare – Healthcare Platform** ⭐  
**Full-stack healthcare system** for **Patients-Doctors-Admin** interaction with appointment booking, medical records, and analytics dashboard.  
**Tech Stack**: Java 17, Spring Boot 3.x, Angular 17, MySQL 8, JWT Auth  
**GitHub**: [Link](https://github.com/pavanrathod/amazecare) | **Demo**: [Live](https://amazecare.pavanrathod.com)  

### 🔹 **Agro Connect – Farmer Marketplace** 🌾  
**Direct farmer-to-customer platform** with real-time pricing, order tracking, and payment integration.  
**Tech Stack**: Spring Boot, React.js, MongoDB, Socket.io, Razorpay  

### 🔹 **Smart Attendance System** 📋  
**AI-powered attendance solution** with facial recognition and real-time reporting.  
**Tech Stack**: Java, Spring Boot, Hibernate, Angular, MySQL, OpenCV  

### 🔹 **Employee Management System** 👥  
**Complete HR solution** with employee onboarding, payroll, and performance tracking.  
**Tech Stack**: Spring Boot, React, PostgreSQL, Keycloak Auth  

---

# 📊 GitHub Stats
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=pavanrathod&show_icons=true&theme=radical&hide_border=true&include_all_commits=true&count_private=true" width="48%"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pavanrathod&layout=compact&theme=radical&hide_border=true" width="48%"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=pavanrathod&theme=radical&hide_border=true"/>
</div>

---

# ✨ AI Experiments  
<div align="center">
  <img src="https://github.com/pavanr45/Pavan/blob/main/fungif1.gif?raw=true" width="350" alt="AI Fun GIF"/>
  <br>🤖 Exploring Generative AI, NLP & Computer Vision
</div>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=pavanrathod&label=Profile%20Views&color=0:00c6ff,100:0072ff&style=flat&font=inter"/>
  <br><sub>Thanks for visiting! ⭐ Star this repo if you found it helpful</sub>
</p>
