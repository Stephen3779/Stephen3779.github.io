---
layout: page
title: "Projects"
icon: fas fa-code
order: 3
permalink: /projects/
---

<style>
/* 🎨 Overall layout */
.projects-page {
  background: linear-gradient(135deg, #f8faff, #eef5ff);
  padding: 40px 20px;
  border-radius: 12px;
  animation: fadeIn 1s ease-in-out;
}

/* 🧱 Project cards */
.project-card {
  background: #ffffff;
  border-radius: 15px;
  box-shadow: 0 6px 18px rgba(0, 0, 0, 0.05);
  padding: 25px;
  margin-bottom: 25px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project-card:hover {
  transform: translateY(-6px);
  box-shadow: 0 10px 25px rgba(0, 120, 215, 0.15);
}

/* 🏷 Titles and text */
.project-card h3 {
  color: #0078D7;
  font-weight: 700;
  margin-bottom: 10px;
}

.project-card p {
  color: #333;
  line-height: 1.7;
}

/* 🔗 Buttons */
.project-links a {
  display: inline-block;
  margin: 8px 6px 0 0;
  padding: 10px 20px;
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

/* ✨ Animation */
@keyframes fadeIn {
  from { opacity: 0; transform: translateY(15px); }
  to { opacity: 1; transform: translateY(0); }
}
</style>

<div class="projects-page">

<h1 align="center">🚀 My Featured Projects</h1>

<p align="center" style="max-width: 650px; margin: 10px auto 40px; color: #555;">
A collection of my best work — showcasing creativity, functionality, and problem-solving with clean code and modern design.
</p>

<!-- 🔹 Smart Visitor Management System -->
<div class="project-card">
  <h3>🔹 Smart Visitor Management System</h3>
  <p>
    A full-stack PHP + MySQL system that manages visitor check-ins, driver tracking, departmental notifications,
    and SMS alerts — featuring real-time approvals and checkouts. Built with AdminLTE and Bootstrap for responsive UI.
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
    A smart, conversational assistant powered by OpenAI APIs and JavaScript. Designed to automate customer inquiries, 
    enhance interactivity, and integrate seamlessly into PHP web dashboards.
  </p>
  <div class="project-links">
    <a href="#" class="view">🧠 Live Demo</a>
    <a href="https://github.com/Stephen3779/nextjs-ai-chatbot" class="github" target="_blank">💻 GitHub Repo</a>
  </div>
</div>

<!-- 🔹 Internet Banking Portal -->
<div class="project-card">
  <h3>🏦 Internet Banking Portal</h3>
  <p>
    A simulated banking platform with Admin, Staff, and Client roles. Implements account management, 
    client onboarding, and transaction tracking using PHP, MySQL, and Bootstrap. 
    Designed to demonstrate secure, role-based access systems.
  </p>
  <div class="project-links">
    <a href="#" class="view">💰 Explore Project</a>
    <a href="https://github.com/Stephen3779/anga-safiri-vms" class="github" target="_blank">💻 GitHub Repo</a>
  </div>
</div>

<!-- 🔹 Hoodhub Modern Solutions -->
<div class="project-card">
  <h3>🌐 Hoodhub Modern Solutions</h3>
  <p>
    A digital transformation suite for small businesses — built with PHP and MySQL. 
    Features client management, role-based dashboards, and smart analytics.
  </p>
  <div class="project-links">
    <a href="#" class="view">🚀 View Project</a>
    <a href="https://github.com/Stephen3779/hoodhub" class="github" target="_blank">💻 GitHub Repo</a>
  </div>
</div>

<p align="center" style="margin-top: 40px; color: #777;">
✨ More exciting projects are under development — stay tuned!
</p>

</div>
