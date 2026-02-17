
---
layout: single
author_profile: true
description: "Lucy Nyambura - Network Engineer | DevOps | Cloud Computing"
classes: wide
---

---
layout: single
author_profile: true
title: "Lucy Nyambura | Network & Cloud Engineer"
permalink: /
description: "Network Engineer | DevOps | Cloud Infrastructure | Automation"
classes: wide
---

<style>
/* Optimized Global Styles */
:root {
  --primary: #1e40af;
  --accent: #3b82f6;
  --bg: #f8fafc;
  --card: #ffffff;
  --text: #1f2937;
  --text-muted: #6b7280;
  --border: #e2e8f0;
  --shadow: 0 4px 20px rgba(0,0,0,0.08);
  --shadow-lg: 0 12px 40px rgba(0,0,0,0.12);
}

* { box-sizing: border-box; margin: 0; padding: 0; }

body {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
  background: var(--bg);
  color: var(--text);
  line-height: 1.6;
  overflow-x: hidden;
}

/* Hero Section - Optimized */
.hero {
  position: relative;
  text-align: center;
  padding: 6rem 1rem 4rem;
  background: linear-gradient(135deg, #1e3a8a 0%, #3b82f6 50%, #1e40af 100%);
  color: white;
  overflow: hidden;
  margin-bottom: 4rem;
}

.hero::before {
  content: '';
  position: absolute;
  inset: 0;
  background: radial-gradient(circle at 20% 80%, rgba(120,119,198,0.3) 0%, transparent 50%),
              radial-gradient(circle at 80% 20%, rgba(255,119,198,0.3) 0%, transparent 50%);
  z-index: 0;
}

.hero > * { position: relative; z-index: 1; }

.hero h1 {
  font-size: clamp(2.2rem, 5vw, 3.5rem);
  font-weight: 700;
  margin-bottom: 0.5rem;
  background: linear-gradient(135deg, white 0%, #f0f9ff 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.hero h2 {
  font-size: clamp(1.2rem, 3vw, 1.6rem);
  font-weight: 400;
  margin-bottom: 1rem;
  opacity: 0.95;
}

.hero p {
  font-size: 1.1rem;
  max-width: 650px;
  margin: 0 auto 2rem;
  opacity: 0.9;
}

.cta-buttons {
  display: flex;
  gap: 1rem;
  justify-content: center;
  flex-wrap: wrap;
}

.cta-primary, .cta-secondary {
  padding: 1rem 2rem;
  border-radius: 50px;
  text-decoration: none;
  font-weight: 600;
  font-size: 1rem;
  transition: all 0.3s cubic-bezier(0.4,0,0.2,1);
  border: 2px solid transparent;
}

.cta-primary {
  background: rgba(255,255,255,0.2);
  color: white;
  backdrop-filter: blur(10px);
}

.cta-primary:hover {
  background: rgba(255,255,255,0.3);
  transform: translateY(-3px);
  box-shadow: 0 10px 30px rgba(255,255,255,0.2);
}

.cta-secondary {
  background: transparent;
  color: white;
}

.cta-secondary:hover {
  background: rgba(255,255,255,0.1);
  transform: translateY(-2px);
}

/* Stats Row */
.stats-row {
  display: flex;
  justify-content: center;
  gap: 3rem;
  margin: 3rem 0;
  flex-wrap: wrap;
}

.stat-item {
  text-align: center;
}

.stat-number {
  font-size: 2.5rem;
  font-weight: 700;
  background: linear-gradient(135deg, white 0%, #f0f9ff 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  display: block;
}

.stat-label {
  color: rgba(255,255,255,0.8);
  font-size: 0.95rem;
  margin-top: 0.25rem;
}

/* Skills Section */
.skills-section {
  padding: 4rem 1rem;
  max-width: 1000px;
  margin: 0 auto;
}

.section-title {
  text-align: center;
  font-size: 2.2rem;
  font-weight: 700;
  margin-bottom: 3rem;
  color: var(--text);
}

.skills-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.5rem;
}

.skill-card {
  background: var(--card);
  padding: 2rem;
  border-radius: 20px;
  border: 1px solid var(--border);
  text-align: center;
  transition: all 0.3s ease;
  position: relative;
  overflow: hidden;
}

.skill-card::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  height: 4px;
  background: linear-gradient(90deg, var(--primary), var(--accent));
  transform: scaleX(0);
  transition: transform 0.3s ease;
}

.skill-icon {
  font-size: 3rem;
  margin-bottom: 1rem;
  display: block;
}

.skill-card h3 {
  font-size: 1.3rem;
  margin-bottom: 1rem;
  color: var(--text);
}

.skill-list {
  list-style: none;
  text-align: left;
}

.skill-list li {
  padding: 0.5rem 0;
  color: var(--text-muted);
  position: relative;
  padding-left: 1.5rem;
}

.skill-list li::before {
  content: '▸';
  position: absolute;
  left: 0;
  color: var(--accent);
  font-weight: bold;
}

.skill-card:hover {
  transform: translateY(-8px);
  box-shadow: var(--shadow-lg);
  border-color: var(--accent);
}

.skill-card:hover::before {
  transform: scaleX(1);
}

/* Projects Preview */
.projects-section {
  padding: 4rem 1rem;
  background: rgba(30,64,175,0.02);
}

.project-grid {
  max-width: 1200px;
  margin: 0 auto;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}

.project-card {
  background: var(--card);
  border-radius: 16px;
  padding: 2rem;
  border: 1px solid var(--border);
  transition: all 0.3s ease;
  position: relative;
  overflow: hidden;
}

.project-card::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  height: 3px;
  background: linear-gradient(90deg, var(--primary), var(--accent));
  transform: scaleX(0);
  transition: transform 0.3s ease;
}

.project-icon {
  font-size: 2rem;
  margin-bottom: 1rem;
  display: block;
}

.project-card h3 {
  font-size: 1.3rem;
  margin-bottom: 0.75rem;
  color: var(--text);
}

.project-card p {
  color: var(--text-muted);
  margin-bottom: 1.5rem;
  line-height: 1.6;
}

.project-link {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  color: var(--primary);
  text-decoration: none;
  font-weight: 600;
}

.project-link:hover {
  color: var(--accent);
}

.project-card:hover {
  transform: translateY(-6px);
  box-shadow: var(--shadow-lg);
}

.project-card:hover::before {
  transform: scaleX(1);
}

/* CTA Section */
.cta-section {
  padding: 4rem 1rem;
  text-align: center;
  max-width: 800px;
  margin: 0 auto;
}

.cta-section h2 {
  font-size: 2.2rem;
  margin-bottom: 1rem;
  color: var(--text);
}

.cta-section p {
  font-size: 1.1rem;
  color: var(--text-muted);
  margin-bottom: 2rem;
}

.cta-button {
  display: inline-block;
  background: linear-gradient(135deg, var(--primary), var(--accent));
  color: white;
  padding: 1.1rem 2.5rem;
  border-radius: 50px;
  text-decoration: none;
  font-weight: 600;
  font-size: 1.1rem;
  transition: all 0.3s ease;
  box-shadow: 0 8px 25px rgba(30,64,175,0.3);
}

.cta-button:hover {
  transform: translateY(-3px);
  box-shadow: 0 15px 35px rgba(30,64,175,0.4);
  text-decoration: none;
  color: white;
}

/* Responsive */
@media (max-width: 768px) {
  .stats-row { gap: 2rem; }
  .skills-grid { grid-template-columns: 1fr; }
  .project-grid { grid-template-columns: 1fr; }
  .cta-buttons { flex-direction: column; align-items: center; }
}
</style>

<div class="hero">
  <h1>🌟 Lucy Nyambura</h1>
  <h2>Network Engineer • DevOps • Cloud Infrastructure</h2>
  <p>4+ years building secure networks, automating infrastructure, and deploying scalable cloud solutions for ISPs</p>
  
  <div class="cta-buttons">
    <a href="/projects" class="cta-primary">View Projects</a>
    <a href="/contact" class="cta-secondary">Contact Me</a>
  </div>
  
  <div class="stats-row">
    <div class="stat-item">
      <span class="stat-number">4+</span>
      <span class="stat-label">Years Experience</span>
    </div>
    <div class="stat-item">
      <span class="stat-number">50+</span>
      <span class="stat-label">Projects Delivered</span>
    </div>
    <div class="stat-item">
      <span class="stat-number">10K+</span>
      <span class="stat-label">Devices Automated</span>
    </div>
  </div>
</div>

<section class="skills-section">
  <h2 class="section-title">🛠 Technical Expertise</h2>
  <div class="skills-grid">
    <div class="skill-card">
      <span class="skill-icon">🌐</span>
      <h3>Networking</h3>
      <ul class="skill-list">
        <li>ONT Provisioning (Nokia, VSOL)</li>
        <li>IP Routing: OSPF, BGP, MPLS</li>
        <li>VLAN & QoS Configuration</li>
        <li>Fault Troubleshooting</li>
      </ul>
    </div>
    
  <div class="skill-card">
    <span class="skill-icon">☁️</span>
    <h3>Cloud Infrastructure</h3>
    <ul class="skill-list">
      <li>AWS EC2, VPC, RDS, S3</li>
      <li>Azure Fundamentals (AZ-900)</li>
      <li>Security Groups & IAM</li>
      <li>Backup & Disaster Recovery</li>
    </ul>
  </div>
  
  <div class="skill-card">
    <span class="skill-icon">⚙️</span>
    <h3>DevOps & Automation</h3>
    <ul class="skill-list">
      <li>Python & Bash Scripting</li>
      <li>Terraform IaC</li>
      <li>Ansible Configuration</li>
      <div class="skill-list">
      <li>GitHub Actions CI/CD</li>
    </ul>
  </div>
  </div>
</section>

<section class="projects-section">
  <div style="max-width: 1200px; margin: 0 auto;">
    <h2 class="section-title" style="text-align: center; margin-bottom: 2rem;">🚀 Featured Projects</h2>
    <div class="project-grid">
      <div class="project-card">
        <span class="project-icon">📡</span>
        <h3>Nokia ONT Provisioning</h3>
        <p>Bash automation for Wi-Fi setup, serial validation, VLAN assignment, and activity logging across ISP networks.</p>
        <a href="https://github.com/lucianakenya/nokia_autoprovisioning" class="project-link" target="_blank">View Code →</a>
      </div>
      
  <div class="project-card">
    <span class="project-icon">☁️</span>
    <h3>Linux EC2 Deployment</h3>
    <p>Secure Linux EC2 instance with VPC networking, IAM roles, security groups, and automated configuration.</p>
    <a href="https://medium.com/@nyamburalucy678/launching-an-ec2-instance-19b86f6b4b5b" class="project-link" target="_blank">View Guide →</a>
  </div>
  
  <div class="project-card">
    <span class="project-icon">🔄</span>
    <h3>Terraform IaC</h3>
    <p>Infrastructure as Code for reproducible AWS deployments with remote state and modular architecture.</p>
    <a href="/projects/#terraform" class="project-link">View Project →</a>
  </div>
</div>
  </div>
</section>

<section class="cta-section">
  <h2>Ready to Build Something Amazing?</h2>
  <p>Let's collaborate on your next network, cloud, or automation project</p>
  <a href="/contact" class="cta-button">Get In Touch</a>
</section>
