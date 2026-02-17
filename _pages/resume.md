---
title: "Resume"
layout: single
permalink: /resume/
author_profile: true
classes: wide
---

<section class="resume-hero">
  <h1>📄 Resume</h1>
  <p class="subtitle">
    Network & Cloud Engineer focused on automation, infrastructure, and scalable systems.
  </p>
  <a href="{{ '/assets/resume.pdf' | relative_url }}" 
     class="btn--resume" 
     target="_blank" 
     download>
     Download PDF
  </a>
</section>

<hr class="divider">

<section class="resume-section">
  <h2>Professional Summary</h2>
  <p class="summary">
    Results-driven <strong>Network & Cloud Engineer</strong> with 3+ years of experience in 
    network automation, cloud infrastructure, DevOps, and IT operations. 
    Experienced in <strong>Python, Terraform, AWS, Azure, Linux, and CI/CD pipelines</strong>, 
    building secure and scalable systems.
  </p>
</section>

<section class="resume-section">
  <h2>Experience</h2>

  <div class="timeline-item">
    <h3>Customer Network Engineer</h3>
    <span class="company">Liquid Intelligent Technologies</span>
    <p>
      Automated provisioning of ONTs, improved network monitoring processes, 
      and resolved enterprise connectivity issues across large-scale infrastructure.
    </p>
  </div>

  <div class="timeline-item">
    <h3>Cloud & DevOps Projects</h3>
    <p>
      Deployed AWS EC2 instances, configured VPC networking, implemented CI/CD 
      workflows with GitHub Actions, and automated infrastructure using Terraform and Ansible.
    </p>
  </div>

</section>

<section class="resume-section">
  <h2>Core Skills</h2>

  <div class="skills-grid">
    <div>
      <h4>Networking</h4>
      <p>Routing & Switching, VPN, Firewalls, VLANs</p>
    </div>

    <div>
      <h4>Cloud & DevOps</h4>
      <p>AWS, Azure, Terraform, CI/CD</p>
    </div>

    <div>
      <h4>Automation</h4>
      <p>Python, Bash, Ansible</p>
    </div>

    <div>
      <h4>Monitoring</h4>
      <p>Log analysis, performance tuning, troubleshooting</p>
    </div>
  </div>
</section>

<style>
:root {
  --accent: #007acc;
  --accent-soft: rgba(0, 122, 204, 0.08);
  --text-dark: #1f2933;
  --text-muted: #6b7280;
}

/* HERO */
.resume-hero {
  text-align: center;
  margin-bottom: 3rem;
}

.resume-hero h1 {
  font-size: 2.2rem;
  margin-bottom: 0.5rem;
}

.subtitle {
  color: var(--text-muted);
  margin-bottom: 1.2rem;
}

.btn--resume {
  display: inline-block;
  padding: 0.65rem 1.4rem;
  background: var(--accent);
  color: white;
  border-radius: 30px;
  text-decoration: none;
  font-weight: 500;
  transition: 0.3s ease;
}

.btn--resume:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 18px rgba(0, 122, 204, 0.25);
}

/* DIVIDER */
.divider {
  border: none;
  height: 1px;
  background: #e5e7eb;
  margin: 2rem 0;
}

/* SECTIONS */
.resume-section {
  margin-bottom: 3rem;
}

.resume-section h2 {
  margin-bottom: 1.2rem;
  font-weight: 600;
  position: relative;
}

.resume-section h2::after {
  content: "";
  width: 40px;
  height: 3px;
  background: var(--accent);
  display: block;
  margin-top: 6px;
  border-radius: 3px;
}

/* SUMMARY */
.summary {
  max-width: 750px;
  line-height: 1.7;
  color: var(--text-dark);
}

/* TIMELINE STYLE */
.timeline-item {
  margin-bottom: 2rem;
  padding-left: 1rem;
  border-left: 3px solid var(--accent-soft);
}

.timeline-item h3 {
  margin: 0;
}

.company {
  font-size: 0.9rem;
  color: var(--text-muted);
  display: block;
  margin-bottom: 0.5rem;
}

/* SKILLS */
.skills-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 2rem;
}

.skills-grid h4 {
  margin-bottom: 0.4rem;
  color: var(--accent);
}

.skills-grid p {
  color: var(--text-muted);
  margin: 0;
}

/* MOBILE */
@media (max-width: 768px) {
  .resume-hero h1 {
    font-size: 1.8rem;
  }
}
</style>
