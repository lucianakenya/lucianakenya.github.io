---
title: "My Projects"
layout: single
permalink: /projects/
author_profile: true
classes: wide
---

<style>
:root {
  --primary: #2563eb;
  --accent: #3b82f6;

  /* Light Mode */
  --bg-page: #f8fafc;
  --card-bg: #ffffff;
  --text-primary: #111827;
  --text-secondary: #4b5563;
  --border: #e5e7eb;
  --shadow-hover: 0 20px 60px rgba(0,0,0,0.12);
}

/* 🌙 Dark Mode */
@media (prefers-color-scheme: dark) {
  :root {
    --bg-page: #0f172a;
    --card-bg: #1e293b;
    --text-primary: #f1f5f9;
    --text-secondary: #cbd5e1;
    --border: #334155;
    --shadow-hover: 0 20px 60px rgba(0,0,0,0.6);
  }
}

body {
  background: var(--bg-page);
}

/* HERO */
.projects-hero {
  text-align: center;
  padding: 4rem 2rem;
  background: linear-gradient(135deg, var(--primary), var(--accent));
  border-radius: 24px;
  color: white;
  margin: 0 -2rem 4rem;
}

.projects-hero h1 {
  font-size: 2.6rem;
  margin-bottom: 1rem;
}

.projects-hero p {
  font-size: 1.15rem;
  opacity: 0.95;
}

/* TABS */
.category-tabs {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  justify-content: center;
  margin-bottom: 3rem;
}

.category-tab {
  background: var(--card-bg);
  color: var(--text-secondary);
  padding: 0.7rem 1.4rem;
  border: 1px solid var(--border);
  border-radius: 40px;
  cursor: pointer;
  transition: 0.3s ease;
}

.category-tab.active,
.category-tab:hover {
  background: var(--primary);
  color: white;
  border-color: var(--primary);
}

/* GRID */
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  gap: 2rem;
  margin-bottom: 4rem;
}

/* CARD */
.project-card {
  background: var(--card-bg);
  border-radius: 18px;
  padding: 2rem;
  border: 1px solid var(--border);
  transition: 0.3s ease;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.project-card:hover {
  transform: translateY(-8px);
  box-shadow: var(--shadow-hover);
  border-color: var(--primary);
}

.project-icon {
  font-size: 2rem;
  margin-bottom: 1rem;
}

.project-card h3 {
  color: var(--text-primary);
  margin-bottom: 0.8rem;
}

.project-card p {
  color: var(--text-secondary);
  line-height: 1.6;
  font-size: 0.95rem;
}

/* BUTTON */
.project-link {
  display: inline-block;
  background: linear-gradient(135deg, var(--primary), var(--accent));
  color: white;
  padding: 0.6rem 1.2rem;
  border-radius: 10px;
  text-decoration: none;
  font-weight: 600;
  font-size: 0.9rem;
  margin-top: 1rem;
}

.project-link:hover {
  opacity: 0.9;
  color: white;
  text-decoration: none;
}

/* CATEGORY STRIP */
.category-networking { border-left: 4px solid #10b981; }
.category-cloud { border-left: 4px solid #f59e0b; }
.category-devops { border-left: 4px solid #ef4444; }
.category-other { border-left: 4px solid #8b5cf6; }

@media (max-width: 768px) {
  .projects-hero {
    margin: 0 -1rem 3rem;
    padding: 3rem 1.5rem;
  }
}
</style>

<div class="projects-hero">
  <h1>🚀 My Projects</h1>
  <p>Networking automation, cloud architecture, and DevOps solutions built in real-world environments</p>
</div>

<div class="category-tabs">
  <button class="category-tab active" data-category="all">All</button>
  <button class="category-tab" data-category="networking">Networking</button>
  <button class="category-tab" data-category="cloud">Cloud</button>
  <button class="category-tab" data-category="devops">DevOps</button>
</div>

<div class="project-grid">

  <!-- Networking -->
  <div class="project-card category-networking" data-category="networking">
    <div>
      <span class="project-icon">📡</span>
      <h3>Nokia ONT Auto-Provisioning</h3>
      <p>Bash automation for Wi-Fi configuration, VLAN assignment, serial validation, and structured activity logging across ISP environments.</p>
    </div>
    <a href="https://github.com/lucianakenya/nokia_autoprovisioning" target="_blank" class="project-link">View Code →</a>
  </div>

  <div class="project-card category-networking" data-category="networking">
    <div>
      <span class="project-icon">🌐</span>
      <h3>VSOL ONT Provisioning Tool</h3>
      <p>Python SSH automation for TR-069 configuration across VSOL OLTs with secure credential handling and bulk operations.</p>
    </div>
    <a href="https://github.com/lucianakenya/vsol_provisioning_script" target="_blank" class="project-link">View Code →</a>
  </div>

  <div class="project-card category-networking" data-category="networking">
    <div>
      <span class="project-icon">📊</span>
      <h3>Power Levels Audit Tool</h3>
      <p>SSH-based ONT diagnostics tool that parses output with Pandas and exports structured Excel reports for analysis.</p>
    </div>
    <a href="https://github.com/lucianakenya/Power_levels_audit" target="_blank" class="project-link">View Code →</a>
  </div>

  <!-- Cloud -->
  <div class="project-card category-cloud" data-category="cloud">
    <div>
      <span class="project-icon">☁️</span>
      <h3>Linux EC2 Deployment</h3>
      <p>Provisioned and secured EC2 instances with IAM roles, security groups, and system hardening best practices.</p>
    </div>
    <a href="https://medium.com/@nyamburalucy678/launching-an-ec2-instance-19b86f6b4b5b" target="_blank" class="project-link">Read Article →</a>
  </div>

  <div class="project-card category-cloud" data-category="cloud">
    <div>
      <span class="project-icon">🌍</span>
      <h3>Amazon VPC Architecture</h3>
      <p>Designed public/private subnet architecture with routing tables, internet gateways, and security controls.</p>
    </div>
    <a href="https://medium.com/@nyamburalucy678/creating-networking-resources-in-an-amazon-vpc-5f3df03a03f4" target="_blank" class="project-link">Read Article →</a>
  </div>

  <!-- DevOps -->
  <div class="project-card category-devops" data-category="devops">
    <div>
      <span class="project-icon">🩺</span>
      <h3>Automated EC2 Health Checks</h3>
      <p>Ansible playbook for monitoring EC2 CPU, memory, and disk usage with AWS SES alert notifications.</p>
    </div>
    <a href="https://medium.com/@nyamburalucy678/how-i-automated-ec2-health-checks-and-email-alerts-with-ansible-and-aws-ses-0f1d4d3c6a49" target="_blank" class="project-link">Read Article →</a>
  </div>

  <div class="project-card category-devops" data-category="devops">
    <div>
      <span class="project-icon">🔄</span>
      <h3>Terraform EC2 Provisioning</h3>
      <p>Infrastructure as Code solution for reproducible EC2 deployments using modular Terraform configurations.</p>
    </div>
    <a href="https://medium.com/@nyamburalucy678/automating-ec2-provisioning-with-terraform-installed-on-ec2-a-step-by-step-guide-c655a7794921" target="_blank" class="project-link">Read Article →</a>
  </div>

</div>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const tabs = document.querySelectorAll('.category-tab');
  const projects = document.querySelectorAll('.project-card');

  tabs.forEach(tab => {
    tab.addEventListener('click', () => {
      tabs.forEach(t => t.classList.remove('active'));
      tab.classList.add('active');

      const category = tab.dataset.category;

      projects.forEach(project => {
        if (category === 'all' || project.dataset.category === category) {
          project.style.display = 'flex';
        } else {
          project.style.display = 'none';
        }
      });
    });
  });
});
</script>
