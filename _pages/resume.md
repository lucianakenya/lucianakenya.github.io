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
  <a href="{{ '/assets/resume.pdf.pdf' | relative_url }}" class="btn--primary" target="_blank" download>Download PDF</a>
</section>

<hr>

<section class="resume-section">
  <h2>🧑‍💼 Professional Summary</h2>
  <div class="highlight-block">
    Results-driven <strong>Network & Cloud Engineer</strong> with 4+ years of experience in network automation, cloud infrastructure, DevOps, and IT operations. Skilled in <strong>Python, Bash, Terraform, Ansible, AWS, Azure, Linux</strong>, and committed to building scalable, secure, and efficient infrastructure solutions.
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
      <h3>Cloud & DevOps Projects</h3>
      <p>Provisioned AWS EC2 instances, configured VPC networking, implemented CI/CD workflows with GitHub Actions, and automated health checks using Ansible.</p>
    </div>
    <div class="experience-card">
      <h3>Automation & Scripting</h3>
      <p>Developed Python and Bash scripts for network audits, reporting, and remote device configuration.</p>
    </div>
  </div>
</section>

<section class="resume-section">
  <h2>🧠 Skills Snapshot</h2>
  <div class="skills-grid">
    <div class="skill-card">
      <h4>Networking</h4>
      <p>Routing & Switching, VPN, Firewalls, TR-069 provisioning, VLAN management</p>
    </div>
    <div class="skill-card">
      <h4>Cloud & DevOps</h4>
      <p>AWS (EC2, VPC), Azure Fundamentals, Terraform, Ansible, CI/CD pipelines</p>
    </div>
    <div class="skill-card">
      <h4>Automation & Scripting</h4>
      <p>Python, Bash, Pandas, Linux CLI tools, Excel reporting</p>
    </div>
    <div class="skill-card">
      <h4>Monitoring & Troubleshooting</h4>
      <p>Network monitoring, log analysis, performance optimization</p>
    </div>
  </div>
</section>

<style>
/* Base styling */
.resume-intro {
  text-align: center;
  margin-bottom: 2rem;
}
.resume-intro .btn--primary {
  display: inline-block;
  margin-top: 1rem;
  padding: 0.6rem 1.2rem;
  background-color: #007acc;
  color: #fff;
  border-radius: 6px;
  text-decoration: none;
  font-weight: bold;
}
.resume-intro .btn--primary:hover {
  background-color: #005f99;
}

.resume-section {
  margin-bottom: 3rem;
}

.highlight-block {
  background-color: #f9f9f9;
  border-left: 4px solid #007acc;
  padding: 1.2rem;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.05);
}

.experience-grid, .skills-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.8rem;
  margin-top: 1rem;
}

.experience-card, .skill-card {
  background-color: #fff;
  border: 1px solid #e0e0e0;
  border-radius: 8px;
  padding: 1rem;
  box-shadow: 0 3px 6px rgba(0,0,0,0.05);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}
.experience-card:hover, .skill-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 6px 12px rgba(0,0,0,0.1);
}

.experience-card h3, .skill-card h4 {
  margin-top: 0;
  margin-bottom: 0.6rem;
  color: #007acc;
}

.experience-card p, .skill-card p {
  margin: 0;
  color: #555;
  font-size: 0.95em;
}

/* Responsive */
@media (max-width: 768px) {
  .experience-grid, .skills-grid {
    grid-template-columns: 1fr;
  }
}
</style>
