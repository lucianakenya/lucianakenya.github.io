---
title: "Resume"
layout: single
permalink: /resume/
author_profile: true
classes: wide
---

<section class="resume-intro">
  <h1>📄 My Resume</h1>
  <p>Looking to collaborate or hire? Download my resume or explore my experience and skills below.</p>
  <a href="{{ '/assets/resume.pdf' | relative_url }}" class="btn--resume" target="_blank" download>Download PDF</a>
</section>

<hr>

<section class="resume-section">
  <h2>🧑‍💼 Professional Summary</h2>
  <div class="highlight-block">
    Results-driven <strong>Network &amp; Cloud Engineer</strong> with 3+ years of experience in network automation, cloud infrastructure, DevOps, and IT operations. Skilled in <strong>Python, Bash, Terraform, Ansible, AWS, Azure, Linux</strong>, and committed to building scalable, secure, and efficient infrastructure solutions.
  </div>
</section>

<section class="resume-section">
  <h2>💼 Experience Highlights</h2>
  <div class="experience-grid">
    <div class="experience-card">
      <h3>Customer Network Engineer – Liquid Intelligent Technologies</h3>
      <p>Automated provisioning of Nokia and VSOL ONTs, monitored network performance, and resolved customer connectivity issues efficiently.</p>
    </div>

  <div class="experience-card">
    <h3>Cloud &amp; DevOps Projects</h3>
    <p>Provisioned AWS EC2 instances, configured VPC networking, implemented CI/CD workflows with GitHub Actions, and automated health checks using Ansible.</p>
  </div>

  <div class="experience-card">
    <h3>Automation &amp; Scripting</h3>
    <p>Developed Python and Bash scripts for network audits, reporting, and remote device configuration.</p>
  </div>
  </div>
</section>

<section class="resume-section">
  <h2>🧠 Skills Snapshot</h2>
  <div class="skills-grid">
    <div class="skill-card">
      <h4>Networking</h4>
      <p>Routing &amp; Switching, VPN, Firewalls, TR-069 provisioning, VLAN management</p>
    </div>

  <div class="skill-card">
    <h4>Cloud &amp; DevOps</h4>
    <p>AWS (EC2, VPC), Azure Fundamentals, Terraform, Ansible, CI/CD pipelines</p>
  </div>

  <div class="skill-card">
    <h4>Automation &amp; Scripting</h4>
    <p>Python, Bash, Pandas, Linux CLI tools, Excel reporting</p>
  </div>

  <div class="skill-card">
    <h4>Monitoring &amp; Troubleshooting</h4>
    <p>Network monitoring, log analysis, performance optimization</p>
  </div>
  </div>
</section>

<style>
:root {
  --accent: #007acc;
  --accent-dark: #005f99;
  --card-border: #e0e0e0;
  --card-shadow: rgba(0, 0, 0, 0.05);
  --text-muted: #555;
}

.resume-intro {
  text-align: center;
  margin-bottom: 2rem;
}

.btn--resume {
  display: inline-block;
  margin-top: 1rem;
  padding: 0.6rem 1.2rem;
  background-color: var(--accent);
  color: #fff;
  border-radius: 6px;
  text-decoration: none;
  font-weight: bold;
}

.btn--resume:hover {
  background-color: var(--accent-dark);
}

.resume-section {
  margin-bottom: 3rem;
}

.highlight-block {
  background-color: #f9f9f9;
  border-left: 4px solid var(--accent);
  padding: 1.2rem;
  border-radius: 8px;
  box-shadow: 0 4px 12px var(--card-shadow);
}

.experience-grid,
.skills-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.8rem;
  margin-top: 1rem;
}

.experience-card,
.skill-card {
  background-color: #fff;
  border: 1px solid var(--card-border);
  border-radius: 8px;
  padding: 1rem;
  box-shadow: 0 3px 6px var(--card-shadow);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.experience-card:hover,
.skill-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
}

.experience-card h3,
.skill-card h4 {
  margin: 0 0 0.6rem;
  color: var(--accent);
}

.experience-card p,
.skill-card p {
  margin: 0;
  color: var(--text-muted);
  font-size: 0.95em;
}

@media (max-width: 768px) {
  .experience-grid,
  .skills-grid {
    grid-template-columns: 1fr;
  }
}
</style>
