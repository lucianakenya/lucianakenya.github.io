---
title: "Skills & Certifications"
layout: single
permalink: /skills/
author_profile: true
classes: wide
---

<style>
:root {
  --primary: #2563eb;
  --accent: #3b82f6;
  --bg-light: #f8fafc;
  --bg-dark: #0f172a;
  --card-light: #ffffff;
  --card-dark: #1e293b;
  --text-light: #111827;
  --text-dark: #f1f5f9;
  --text-secondary-light: #4b5563;
  --text-secondary-dark: #cbd5e1;
  --border-light: #e5e7eb;
  --border-dark: #334155;
  --shadow-light: 0 10px 40px rgba(0,0,0,0.08);
  --shadow-dark: 0 10px 40px rgba(0,0,0,0.5);
  --shadow-hover-light: 0 20px 60px rgba(0,0,0,0.12);
  --shadow-hover-dark: 0 20px 60px rgba(0,0,0,0.7);
}

body {
  background: var(--bg-light);
  color: var(--text-light);
  font-family: system-ui, sans-serif;
  transition: all 0.3s ease;
  margin: 0;
  padding: 0;
}

@media (prefers-color-scheme: dark) {
  body {
    background: var(--bg-dark);
    color: var(--text-dark);
  }
}

/* HERO */
.skills-hero {
  text-align: center;
  padding: 3rem 2rem;
  margin-bottom: 3rem;
}
.skills-hero h1 {
  font-size: 2.5rem;
  margin-bottom: 0.8rem;
  color: var(--primary);
}
.skills-hero p {
  font-size: 1.1rem;
  color: var(--text-secondary-light);
}
@media (prefers-color-scheme: dark) {
  .skills-hero p {
    color: var(--text-secondary-dark);
  }
}

/* SKILLS GRID */
.skills-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 2rem;
  max-width: 900px;
  margin: 0 auto 4rem;
}

.skills-grid ul {
  list-style: none;
  padding: 1rem 1.5rem;
  border-radius: 16px;
  background: var(--card-light);
  border: 1px solid var(--border-light);
  box-shadow: var(--shadow-light);
  transition: all 0.3s ease;
}
.skills-grid ul:hover {
  transform: translateY(-6px);
  box-shadow: var(--shadow-hover-light);
}
.skills-grid li {
  margin-bottom: 1rem;
  font-size: 1rem;
}
.skills-grid li i {
  margin-right: 0.7rem;
  color: var(--primary);
}

@media (prefers-color-scheme: dark) {
  .skills-grid ul {
    background: var(--card-dark);
    border: 1px solid var(--border-dark);
    box-shadow: var(--shadow-dark);
  }
  .skills-grid li i {
    color: var(--accent);
  }
}

/* CERTIFICATIONS */
.cert-category {
  max-width: 900px;
  margin: 0 auto 3rem;
}
.cert-category h3 {
  margin-bottom: 1rem;
  color: var(--primary);
  font-size: 1.3rem;
}
.cert-button-group {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  margin-bottom: 2rem;
}
.cert-button {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  padding: 0.7rem 1rem;
  background: var(--card-light);
  border: 1px solid var(--border-light);
  border-radius: 12px;
  color: var(--text-secondary-light);
  text-decoration: none;
  font-weight: 500;
  transition: all 0.3s ease;
}
.cert-button:hover {
  background: var(--primary);
  color: white;
  border-color: var(--primary);
}
.cert-button i {
  font-size: 1rem;
}
@media (prefers-color-scheme: dark) {
  .cert-button {
    background: var(--card-dark);
    border: 1px solid var(--border-dark);
    color: var(--text-secondary-dark);
  }
  .cert-button:hover {
    background: var(--accent);
  }
}

.cert-note {
  text-align: center;
  font-size: 0.95rem;
  color: var(--text-secondary-light);
  margin-top: 1rem;
}
@media (prefers-color-scheme: dark) {
  .cert-note {
    color: var(--text-secondary-dark);
  }
}

/* Responsive */
@media (max-width: 768px) {
  .skills-grid {
    grid-template-columns: 1fr;
  }
  .cert-button-group {
    flex-direction: column;
  }
}
</style>

<div class="skills-hero">
  <h1>💡 Technical Expertise & Certifications</h1>
  <p>Networking, cloud infrastructure, automation, DevOps, and programming skills I excel in</p>
</div>

<div class="skills-grid">
  <ul>
    <li><i class="fas fa-network-wired"></i> IP routing protocols: OSPF, BGP</li>
    <li><i class="fas fa-network-wired"></i> MPLS, fault troubleshooting</li>
    <li><i class="fas fa-tools"></i> Incident management & network performance tools</li>
    <li><i class="fas fa-cloud"></i> AWS: EC2, VPC, IAM, S3</li>
    <li><i class="fas fa-cloud"></i> Hybrid cloud architecture & VPN configuration</li>
    <li><i class="fas fa-shield-alt"></i> Cloud security & compliance</li>
  </ul>
  <ul>
    <li><i class="fas fa-code"></i> Python, Bash scripting</li>
    <li><i class="fas fa-cogs"></i> Terraform & CloudFormation</li>
    <li><i class="fas fa-chart-line"></i> Capacity planning & service reliability</li>
    <li><i class="fas fa-sync-alt"></i> Incident recovery & reporting</li>
    <li><i class="fas fa-headset"></i> IT helpdesk & customer support</li>
    <li><i class="fas fa-database"></i> Project management & basic DB admin</li>
  </ul>
</div>

<section id="certifications">
  <h2 class="section-title">Certifications</h2>

  <div class="cert-category">
    <h3>🌩️ Cloud</h3>
    <div class="cert-button-group">
      <a href="https://www.credly.com/badges/69ca0447-1d22-4be9-80af-5b0af3901223/linked_in_profile" target="_blank" class="cert-button">
        <i class="fas fa-certificate"></i> Microsoft AZ-900 Azure Fundamentals
      </a>
      <a href="https://catalog-education.oracle.com/ords/certview/sharebadge?id=19D5D32885915EFC7FFB5A9E8EC90026D4CAFA90CD21F1635F698DB9E6281A22" target="_blank" class="cert-button">
        <i class="fas fa-certificate"></i> Oracle Cloud Infrastructure 2025 Foundations (1Z0-1085-25)
      </a>
      <a href="https://www.credly.com/badges/69ca0447-1d22-4be9-80af-5b0af3901223/linked_in_profile" target="_blank" class="cert-button">
        <i class="fas fa-certificate"></i> AWS Certified Cloud Practitioner CLF-C02
      </a>
    </div>
  </div>

  <div class="cert-category">
    <h3>🧠 AI & Data</h3>
    <div class="cert-button-group">
      <a href="https://catalog-education.oracle.com/ords/certview/sharebadge?id=19D5D32885915EFC7FFB5A9E8EC90026D4CAFA90CD21F1635F698DB9E6281A22" target="_blank" class="cert-button">
        <i class="fas fa-certificate"></i> Oracle Data Platform 2025 Foundations (1Z0-1195-25)
      </a>
      <a href="https://catalog-education.oracle.com/ords/certview/sharebadge?id=6794E05D118E457AFDC4E5C6173FCD19C774D20AED86F6BB56D4CE5B993FFAAE" target="_blank" class="cert-button">
        <i class="fas fa-certificate"></i> Oracle AI Foundations Associate (1Z0-1122-25)
      </a>
    </div>
  </div>

  <div class="cert-category">
    <h3>🔌 Networking</h3>
    <div class="cert-button-group">
      <a href="https://www.linkedin.com/posts/lucy-nyambura-5704a1232_junipernetworksproducts-share-7115932203666092032-VUYw?utm_source=share&utm_medium=member_desktop&rcm=ACoAADoXw-QBakTUAl0UhfLAPr_ovPqs2Djkkr0" target="_blank" class="cert-button">
        <i class="fas fa-certificate"></i> Juniper Network JNCIA JN0-104
      </a>
    </div>
  </div>

  <p class="cert-note">
    📌 You can also view all certification badges and verification links directly on my
    <a href="https://www.linkedin.com/in/lucy-nyambura-5704a1232" target="_blank">LinkedIn profile</a>.
  </p>
</section>
<section id="lab-challenges">
  <h2 class="section-title">🔬 Lab Challenges & Practical Training</h2>

  <div class="cert-category">
    <h3>🛡️ Hack The Box Academy</h3>
    <div class="cert-button-group">
      <a href="https://academy.hackthebox.com/achievement/badge/b0945e4d-f228-11f0-9254-bea50ffe6cb4" target="_blank" class="cert-button">
        <i class="fas fa-flask"></i> Linux Fundamentals
      </a>
      <a href="https://academy.hackthebox.com/achievement/badge/996b074f-036d-11f1-9254-bea50ffe6cb4" target="_blank" class="cert-button">
        <i class="fas fa-flask"></i> Network Enumeration with Nmap
      </a>
      <a href="https://academy.hackthebox.com/achievement/badge/264e7011-00f0-11f1-9254-bea50ffe6cb4" target="_blank" class="cert-button">
        <i class="fas fa-flask"></i> Introduction to Networking
      </a>
      <a href="https://academy.hackthebox.com/achievement/badge/35a1795e-f12d-11f0-9254-bea50ffe6cb4" target="_blank" class="cert-button">
        <i class="fas fa-flask"></i> Windows Fundamentals
      </a>
      <a href="https://academy.hackthebox.com/achievement/badge/3c16345e-f15e-11f0-9254-bea50ffe6cb4" target="_blank" class="cert-button">
        <i class="fas fa-flask"></i> Introduction to Web Applications
      </a>
      <a href="https://academy.hackthebox.com/achievement/badge/1d7aa8f1-0a49-11f1-9254-bea50ffe6cb4" target="_blank" class="cert-button">
        <i class="fas fa-flask"></i> Vulnerability Assessment
      </a>
    </div>
  </div>

  <p class="cert-note">
    🧪 Continuous hands-on cybersecurity training through real-world lab simulations, network enumeration, vulnerability analysis, and system exploitation.
  </p>
</section>
