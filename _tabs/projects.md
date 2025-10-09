---
layout: page
title: "Projects"
icon: fas fa-code
order: 3
permalink: /projects/
---

<style>
/* 🎨 Page Background */
.projects-page {
  background: linear-gradient(145deg, #f8faff, #eef5ff);
  padding: 40px 20px 60px;
  border-radius: 16px;
  animation: fadeIn 1s ease-in-out;
}

/* ✨ Animation */
@keyframes fadeIn {
  from { opacity: 0; transform: translateY(20px); }
  to { opacity: 1; transform: translateY(0); }
}

/* 🧱 Project Cards */
.project-card {
  background: linear-gradient(160deg, #ffffff, #f2f8ff);
  border-radius: 15px;
  box-shadow: 0 8px 20px rgba(0, 120, 215, 0.08);
  padding: 30px;
  margin-bottom: 30px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}
.project-card:hover {
  transform: translateY(-6px);
  box-shadow: 0 10px 25px rgba(0, 120, 215, 0.2);
}

/* 🏷 Titles and Text */
.project-card h3 {
  color: #0078D7;
  font-weight: 700;
  margin-bottom: 12px;
  font-size: 1.4rem;
}
.project-card p {
  color: #333;
  line-height: 1.7;
  font-size: 1.02rem;
}

/* 🔗 Buttons */
.project-links {
  margin-top: 18px;
}
.project-links a {
  display: inline-block;
  margin: 6px 8px 0 0;
  padding: 10px 22px;
  border-radius: 8px;
  text-decoration: none;
  font-weight: 600;
  transition: all 0.3s ease;
}
.project-links a.view {
  background: #0078D7;
  color: #fff;
}
.project-links a.view:hover {
  background: #005fa3;
}
.project-links a.github {
  border: 2px solid #0078D7;
  color: #0078D7;
  background: #fff;
}
.project-links a.github:hover {
  background: #0078D7;
  color: #fff;
}
</style>

<div class="projects-page">

<h1 align="center" style="color:#0078D7; font-weight:800; font-size:2rem; margin-bottom:10px;">
🚀 My Featured Projects
</h1>

<p align="center" style="max-width:700px; margin:10px auto 45px; color:#555; font-size:1.05rem;">
A collection of my top professional and academic builds — showcasing innovation, scalability, and a touch of AI-driven design.
</p>

<!-- 🔹 Smart Visitor Management System -->
<div class="project-card">
  <h3>🔹 Smart Visitor Management System</h3>
  <p>
    A full-stack PHP + MySQL web app for managing visitor check-ins, driver tracking, and departmental notifications.
    Includes real-time SMS alerts, visitor approval flows, and analytics dashboards built with AdminLTE and Bootstrap.
  </p>
  <div class="project-links">
    <a href="#" class="view">🌐 View Demo</a>
    <a href="https://github.com/Stephen3779/KCAA" class="github" target="_blank">💻 GitHub Repo</a>
  </div>
</div>

<!-- 🔹 AI Chatbot Integration -->
<div class="project-card">
  <h3>🤖 AI Chatbot Integration</h3>
  <p>
    A conversational AI assistant using OpenAI API and JavaScript — integrated into a PHP web dashboard. 
    Automates customer support, improves user experience, and demonstrates real-world AI deployment.
  </p>
  <div class="project-links">
    <a href="#" class="view">🧠 Try the Chatbot</a>
    <a href="https://github.com/Stephen3779/nextjs-ai-chatbot" class="github" target="_blank">💻 GitHub Repo</a>
  </div>
</div>

<!-- 🔹 Internet Banking Portal -->
<div class="project-card">
  <h3>🏦 Internet Banking Portal</h3>
  <p>
    A role-based PHP + MySQL banking simulation system featuring Admin, Staff, and Client dashboards. 
    Implements secure authentication, account management, and transaction history with responsive design.
  </p>
  <div class="project-links">
    <a href="#" class="view">💰 Explore System</a>
    <a href="https://github.com/Stephen3779/anga-safiri-vms" class="github" target="_blank">💻 GitHub Repo</a>
  </div>
</div>

<!-- 🔹 Hoodhub Modern Solutions -->
<div class="project-card">
  <h3>🌐 Hoodhub Modern Solutions</h3>
  <p>
    A business modernization suite built with PHP and MySQL. Features client management, dynamic roles, and 
    integrated analytics. Designed for scalability and simple deployment for small enterprises.
  </p>
  <div class="project-links">
    <a href="#" class="view">🚀 Visit Project</a>
    <a href="https://github.com/Stephen3779/hoodhub" class="github" target="_blank">💻 GitHub Repo</a>
  </div>
</div>

<p align="center" style="margin-top: 50px; color:#777; font-style:italic;">
✨ More exciting projects are on the way — innovation never sleeps.
</p>

</div>
