---
layout: page
title: "Home"
permalink: /
---

<style>
/* 🌈 Background + animation */
body {
  background: linear-gradient(135deg, #e3f2fd, #f8f9fa);
  font-family: 'Inter', sans-serif;
}

/* Centered intro block */
.home-intro {
  text-align: center;
  margin-top: 50px;
  margin-bottom: 80px;
  animation: fadeIn 1.2s ease-in-out;
}

/* Profile image style */
.home-intro img {
  border-radius: 50%;
  width: 160px;
  box-shadow: 0 8px 25px rgba(0, 120, 215, 0.3);
  transition: transform 0.3s ease;
}

.home-intro img:hover {
  transform: scale(1.05);
}

/* Headings */
.home-intro h1 {
  margin-top: 25px;
  color: #0078D7;
  font-weight: 700;
  font-size: 2.4rem;
}

/* Tagline */
.home-intro p {
  font-size: 18px;
  max-width: 650px;
  margin: 15px auto;
  color: #333;
  line-height: 1.7;
}

/* Buttons */
.home-buttons a {
  display: inline-block;
  margin: 8px;
  padding: 12px 26px;
  border-radius: 10px;
  font-weight: 600;
  text-decoration: none;
  transition: all 0.3s ease;
}

.home-buttons a.primary {
  background: #0078D7;
  color: #fff;
  box-shadow: 0 4px 10px rgba(0, 120, 215, 0.3);
}

.home-buttons a.primary:hover {
  background: #005fa3;
  transform: translateY(-3px);
}

.home-buttons a.secondary {
  background: #fff;
  color: #0078D7;
  border: 2px solid #0078D7;
}

.home-buttons a.secondary:hover {
  background: #0078D7;
  color: #fff;
  transform: translateY(-3px);
}

/* Animations */
@keyframes fadeIn {
  from { opacity: 0; transform: translateY(20px); }
  to { opacity: 1; transform: translateY(0); }
}
</style>

<div class="home-intro">
  <img src="/assets/img/profile.jpg" alt="Stephen Mutunga">

  <h1>👋 Hi, I'm <strong>Stephen Mutunga</strong></h1>

  <p>
    A <strong>Full-Stack Developer</strong> and <strong>AI Systems Enthusiast</strong> passionate about 
    building intelligent, scalable web applications that simplify real-world processes.
  </p>

  <div class="home-buttons">
    <a href="/projects/" class="primary">🚀 View My Projects</a>
    <a href="/about/" class="primary">👤 About Me</a>
    <a href="/cv/" class="secondary">📄 View My CV</a>
  </div>
</div>

---

## 🌟 Featured Highlights

<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; margin-top: 40px;">

<div style="flex: 1; min-width: 250px; background: #ffffff; padding: 20px; border-radius: 12px; box-shadow: 0 4px 15px rgba(0,0,0,0.05);">
  <h3>💡 Innovative Systems</h3>
  <p>From visitor tracking to smart automation — I build systems that bring real-world value and operational efficiency.</p>
</div>

<div style="flex: 1; min-width: 250px; background: #ffffff; padding: 20px; border-radius: 12px; box-shadow: 0 4px 15px rgba(0,0,0,0.05);">
  <h3>⚙️ AI & Automation</h3>
  <p>Integrating machine learning and natural language AI into responsive, data-driven platforms.</p>
</div>

<div style="flex: 1; min-width: 250px; background: #ffffff; padding: 20px; border-radius: 12px; box-shadow: 0 4px 15px rgba(0,0,0,0.05);">
  <h3>🌐 Modern Web Design</h3>
  <p>Creating seamless user experiences using Bootstrap, AdminLTE, and responsive design best practices.</p>
</div>

</div>

---

<div align="center" style="margin-top: 60px;">
  <h2>📫 Let's Connect</h2>
  <p>
    <a href="mailto:stevemuiwa736@gmail.com">📧 Email</a> |
    <a href="https://github.com/Stephen3779" target="_blank">💻 GitHub</a> |
    <a href="https://linkedin.com/in/stephenmutunga" target="_blank">🔗 LinkedIn</a>
  </p>
</div>
