---
layout: single
author_profile: true
description: "LUCY NYAMBURA - DevOps & Automation | Network Engineer | Cloud Computing | Cyber Security"
classes: wide
---

<style>
:root {
  --primary: #667eea;
  --accent: #764ba2;
  --bg-page: #fafafa;
  --card-bg: #ffffff;
  --text-primary: #222;
  --text-secondary: #555;
  --border: #e0e0e0;
  --shadow: 0 8px 25px rgba(0,0,0,0.08);
}

@media (prefers-color-scheme: dark) {
  :root {
    --bg-page: #0f172a;
    --card-bg: #1e293b;
    --text-primary: #f1f5f9;
    --text-secondary: #cbd5e1;
    --border: #334155;
    --shadow: 0 8px 25px rgba(0,0,0,0.5);
  }
}

body {
  background: var(--bg-page);
  color: var(--text-primary);
  font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
  line-height: 1.6;
  margin: 0;
  padding: 0;
  scroll-behavior: smooth;
}

/* HERO */
.hero {
  text-align: center;
  padding: 6rem 1rem 4rem 1rem;
  background: var(--card-bg);
  color: var(--text-primary);
  border-radius: 16px;
  max-width: 900px;
  margin: 0 auto 4rem auto;
  box-shadow: var(--shadow);
  position: relative;
}

.hero h1 {
  font-size: 3rem;
  margin-bottom: 0.5rem;
}

.hero h2 {
  font-size: 1.5rem;
  opacity: 0.9;
  margin-bottom: 1.2rem;
}

.hero p {
  font-size: 1.1rem;
  max-width: 650px;
  margin: 0 auto;
  opacity: 0.85;
}

/* SKILLS PREVIEW */
.skills-preview {
  max-width: 1000px;
  margin: 0 auto 4rem auto;
  padding: 0 1rem;
}

.skills-preview h2 {
  text-align: center;
  font-size: 2rem;
  margin-bottom: 2rem;
  color: var(--primary);
}

.skills-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1.5rem;
}

.skill-card {
  background: var(--card-bg);
  padding: 1.5rem;
  border-radius: 16px;
  text-align: center;
  box-shadow: var(--shadow);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.skill-card:hover {
  transform: translateY(-6px);
  box-shadow: 0 12px 35px rgba(0,0,0,0.15);
}

.skill-card i {
  font-size: 2rem;
  color: var(--primary);
  margin-bottom: 0.5rem;
}

.skill-card p {
  margin: 0;
  font-size: 0.95rem;
  color: var(--text-secondary);
}

/* PROJECTS PREVIEW */
.projects-preview {
  max-width: 1000px;
  margin: 0 auto 4rem auto;
  padding: 0 1rem;
}

.projects-preview h2 {
  text-align: center;
  font-size: 2rem;
  margin-bottom: 2rem;
  color: var(--primary);
}

.project-card {
  background: var(--card-bg);
  padding: 1.5rem;
  border-radius: 16px;
  box-shadow: var(--shadow);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  text-align: center;
}

.project-card:hover {
  transform: translateY(-6px);
  box-shadow: 0 12px 35px rgba(0,0,0,0.15);
}

.project-card h3 {
  margin-bottom: 0.6rem;
  color: var(--text-primary);
}

.project-card p {
  color: var(--text-secondary);
  font-size: 0.95rem;
}

.cta-button {
  display: inline-block;
  margin-top: 1rem;
  padding: 0.8rem 2rem;
  background: var(--primary);
  color: white;
  border-radius: 12px;
  text-decoration: none;
  font-weight: 600;
  transition: all 0.3s ease;
}

.cta-button:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 20px rgba(0,0,0,0.2);
}

/* FOOTNOTE */
.page-footnote {
  text-align: center;
  font-size: 0.9rem;
  color: var(--text-secondary);
  margin-top: 6rem;
  padding: 1rem;
  border-top: 1px solid var(--border);
}
</style>

<div class="hero">
  <h1>🌟 Lucy Nyambura</h1>
  <h2>Network Engineer • DevOps • Cloud Infrastructure</h2>
  <p>4+ years building secure networks, automating infrastructure, and deploying scalable cloud solutions</p>
</div>

<section class="skills-preview" id="skills">
  <h2>Technical Skills & Expertise</h2>
  <div class="skills-grid">
    <div class="skill-card">
      <i class="fas fa-network-wired"></i>
      <p>IP Routing: OSPF, BGP</p>
    </div>
    <div class="skill-card">
      <i class="fas fa-cloud"></i>
      <p>AWS Cloud: EC2, VPC, IAM, S3</p>
    </div>
    <div class="skill-card">
      <i class="fas fa-code"></i>
      <p>Python & Bash Scripting</p>
    </div>
    <div class="skill-card">
      <i class="fas fa-cogs"></i>
      <p>Terraform & Cloud Automation</p>
    </div>
    <div class="skill-card">
      <i class="fas fa-shield-alt"></i>
      <p>Cloud Security & Compliance</p>
    </div>
    <div class="skill-card">
      <i class="fas fa-chart-line"></i>
      <p>Capacity Planning & Service Reliability</p>
    </div>
  </div>
</section>

<section class="projects-preview" id="projects">
  <h2>Featured Projects</h2>
  <p style="text-align:center; color:var(--text-secondary); max-width:700px; margin:0 auto 2rem;">
    Highlights from my work in networking, cloud infrastructure, and DevOps automation.
  </p>
  <div class="skills-grid">
    <div class="project-card">
      <h3>Nokia ONT Provisioning</h3>
      <p>Bash script automating Wi-Fi setup and VLAN assignments</p>
    </div>
    <div class="project-card">
      <h3>Linux EC2 Setup</h3>
      <p>Provisioned EC2 instances and configured networking securely</p>
    </div>
    <div class="project-card">
      <h3>CI/CD Pipeline</h3>
      <p>Built full DevOps workflow with Python & GitHub Actions</p>
    </div>
  </div>
  <p style="text-align:center; margin-top:1rem;">
    <a href="/projects/" class="cta-button">View All Projects</a>
  </p>
</section>

<div class="page-footnote">
  &copy; {{ site.time | date: "%Y" }} Lucy Nyambura • Showcasing professional expertise in networking, cloud, and DevOps
</div>
