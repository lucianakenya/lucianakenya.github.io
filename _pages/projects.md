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
  --shadow: 0 10px 40px rgba(0,0,0,0.08);
  --shadow-hover: 0 20px 60px rgba(0,0,0,0.12);
}

/* 🌙 Dark Mode Support */
@media (prefers-color-scheme: dark) {
  :root {
    --bg-page: #0f172a;
    --card-bg: #1e293b;
    --text-primary: #f1f5f9;
    --text-secondary: #cbd5e1;
    --border: #334155;
    --shadow: 0 10px 40px rgba(0,0,0,0.5);
    --shadow-hover: 0 20px 60px rgba(0,0,0,0.7);
  }
}

/* Page Background */
body {
  background: var(--bg-page);
}

/* HERO SECTION */
.projects-hero {
  text-align: center;
  padding: 4rem 2rem;
  background: linear-gradient(135deg, var(--primary), var(--accent));
  border-radius: 24px;
  color: white;
  margin: 0 -2rem 4rem;
}

.projects-hero h1 {
  font-size: 2.8rem;
  font-weight: 700;
  margin-bottom: 1rem;
}

.projects-hero p {
  font-size: 1.2rem;
  opacity: 0.95;
}

/* CATEGORY TABS */
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
  font-weight: 500;
  transition: all 0.3s ease;
}

.category-tab.active,
.category-tab:hover {
  background: var(--primary);
  color: white;
  border-color: var(--primary);
}

/* PROJECT GRID */
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  gap: 2rem;
  margin-bottom: 4rem;
}

/* PROJECT CARDS */
.project-card {
  background: var(--card-bg);
  border-radius: 20px;
  padding: 2rem;
  border: 1px solid var(--border);
  transition: all 0.3s ease;
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
  font-size: 2.3rem;
  margin-bottom: 1rem;
}

.project-card h3 {
  font-size: 1.3rem;
  color: var(--text-primary);
  margin-bottom: 0.8rem;
}

.project-card p {
  color: var(--text-secondary);
  line-height: 1.6;
  margin-bottom: 1.5rem;
  font-size: 0.98rem;
}

/* BUTTON */
.project-link {
  display: inline-block;
  background: linear-gradient(135deg, var(--primary), var(--accent));
  color: white;
  padding: 0.65rem 1.3rem;
  border-radius: 10px;
  text-decoration: none;
  font-weight: 600;
  font-size: 0.9rem;
  transition: 0.3s ease;
}

.project-link:hover {
  opacity: 0.9;
  transform: translateY(-2px);
  text-decoration: none;
  color: white;
}

/* CATEGORY STRIPS */
.category-networking { border-left: 4px solid #10b981; }
.category-cloud { border-left: 4px solid #f59e0b; }
.category-devops { border-left: 4px solid #ef4444; }

/* RESPONSIVE */
@media (max-width: 768px) {
  .projects-hero {
    margin: 0 -1rem 3rem;
    padding: 3rem 1.5rem;
  }

  .projects-hero h1 {
    font-size: 2.2rem;
  }

  .project-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="projects-hero">
  <h1>🚀 My Projects</h1>
  <p>Real-world networking automation, cloud infrastructure, and DevOps solutions I've built</p>
</div>

<div class="category-tabs">
  <button class="category-tab active" data-category="all">All Projects</button>
  <button class="category-tab" data-category="networking">Networking</button>
  <button class="category-tab" data-category="cloud">Cloud</button>
  <button class="category-tab" data-category="devops">DevOps</button>
</div>

<div class="project-grid" id="projectGrid">

  <!-- Networking -->
  <div class="project-card category-networking" data-category="networking">
    <div>
      <span class="project-icon">📡</span>
      <h3>Nokia ONT Provisioning</h3>
      <p>Bash automation for Wi-Fi setup, VLAN assignment, and logging across ISP Nokia ONTs.</p>
    </div>
    <a href="https://github.com/lucianakenya/nokia-ont-provisioning" target="_blank" class="project-link">View Code →</a>
  </div>

  <div class="project-card category-networking" data-category="networking">
    <div>
      <span class="project-icon">🌐</span>
      <h3>VSOL ONT Provisioning</h3>
      <p>Python SSH automation for TR-069 configuration and bulk ONT management.</p>
    </div>
    <a href="https://github.com/lucianakenya/vsol-ont-automation" target="_blank" class="project-link">View Code →</a>
  </div>

  <div class="project-card category-networking" data-category="networking">
    <div>
      <span class="project-icon">🔧</span>
      <h3>TR-069 Remote Configurator</h3>
      <p>Python deployment tool with validation and rollback for ACS configuration management.</p>
    </div>
    <a href="https://github.com/lucianakenya/tr069-configurator" target="_blank" class="project-link">View Code →</a>
  </div>

  <!-- Cloud -->
  <div class="project-card category-cloud" data-category="cloud">
    <div>
      <span class="project-icon">☁️</span>
      <h3>Linux EC2 Setup</h3>
      <p>Secure EC2 provisioning with IAM roles, security groups, and automated Linux hardening.</p>
    </div>
    <a href="https://github.com/lucianakenya/aws-ec2-setup" target="_blank" class="project-link">View Code →</a>
  </div>

  <div class="project-card category-cloud" data-category="cloud">
    <div>
      <span class="project-icon">🌐</span>
      <h3>Amazon VPC Networking</h3>
      <p>Complete AWS VPC architecture with public/private subnets and routing controls.</p>
    </div>
    <a href="https://github.com/lucianakenya/aws-vpc-networking" target="_blank" class="project-link">View Code →</a>
  </div>

  <!-- DevOps -->
  <div class="project-card category-devops" data-category="devops">
    <div>
      <span class="project-icon">🩺</span>
      <h3>Automated EC2 Health Checks</h3>
      <p>Ansible playbook for EC2 monitoring with AWS SES alerts and auto-recovery.</p>
    </div>
    <a href="https://github.com/lucianakenya/ec2-health-checks" target="_blank" class="project-link">View Code →</a>
  </div>

  <div class="project-card category-devops" data-category="devops">
    <div>
      <span class="project-icon">🔄</span>
      <h3>Terraform Provisioning</h3>
      <p>Infrastructure as Code for reproducible AWS EC2 deployments with remote state management.</p>
    </div>
    <a href="https://github.com/lucianakenya/terraform-ec2" target="_blank" class="project-link">View Code →</a>
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
