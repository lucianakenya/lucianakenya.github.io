---
title: "My Projects"
layout: single
permalink: /projects/
author_profile: true
classes: wide
---

<style>
:root {
  --primary: #1e40af;
  --accent: #3b82f6;
  --bg-light: #f8fafc;
  --card-bg: #ffffff;
  --text-primary: #1f2937;
  --text-secondary: #6b7280;
  --border: #e2e8f0;
  --shadow: 0 10px 40px rgba(0,0,0,0.08);
  --shadow-hover: 0 20px 60px rgba(0,0,0,0.12);
}

.projects-hero {
  text-align: center;
  padding: 4rem 2rem;
  background: linear-gradient(135deg, var(--primary) 0%, var(--accent) 50%, #10b981 100%);
  border-radius: 24px;
  color: white;
  margin: 0 -2rem 4rem;
  position: relative;
  overflow: hidden;
}

.projects-hero::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%23ffffff' fill-opacity='0.1'%3E%3Ccircle cx='30' cy='30' r='2'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
}

.projects-hero h1 {
  font-size: 3rem;
  font-weight: 700;
  margin-bottom: 1rem;
  position: relative;
  z-index: 1;
}

.projects-hero p {
  font-size: 1.25rem;
  opacity: 0.95;
  max-width: 600px;
  margin: 0 auto;
  position: relative;
  z-index: 1;
}

.category-tabs {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  justify-content: center;
  margin-bottom: 3rem;
}

.category-tab {
  background: var(--bg-light);
  color: var(--text-secondary);
  padding: 0.75rem 1.5rem;
  border: 2px solid var(--border);
  border-radius: 50px;
  cursor: pointer;
  font-weight: 500;
  transition: all 0.3s ease;
  font-size: 0.95rem;
}

.category-tab.active,
.category-tab:hover {
  background: var(--primary);
  color: white;
  border-color: var(--primary);
  transform: translateY(-2px);
}

.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(380px, 1fr));
  gap: 2rem;
  margin-bottom: 4rem;
}

.project-card {
  background: var(--card-bg);
  border-radius: 20px;
  padding: 2.5rem 2rem;
  border: 1px solid var(--border);
  transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
  position: relative;
  overflow: hidden;
  height: 100%;
}

.project-card::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  height: 4px;
  background: linear-gradient(90deg, var(--primary), var(--accent));
  transform: scaleX(0);
  transition: transform 0.4s ease;
}

.project-card:hover {
  transform: translateY(-12px);
  box-shadow: var(--shadow-hover);
  border-color: var(--accent);
}

.project-card:hover::before {
  transform: scaleX(1);
}

.project-icon {
  font-size: 2.5rem;
  margin-bottom: 1.5rem;
  display: block;
}

.project-card h3 {
  font-size: 1.4rem;
  color: var(--text-primary);
  margin-bottom: 1rem;
  font-weight: 600;
  line-height: 1.3;
}

.project-card p {
  color: var(--text-secondary);
  line-height: 1.7;
  margin-bottom: 1.5rem;
  font-size: 1rem;
}

.project-link {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  background: linear-gradient(135deg, var(--primary), var(--accent));
  color: white;
  padding: 0.75rem 1.5rem;
  border-radius: 12px;
  text-decoration: none;
  font-weight: 600;
  font-size: 0.95rem;
  transition: all 0.3s ease;
  box-shadow: 0 4px 15px rgba(30, 64, 175, 0.2);
}

.project-link:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 25px rgba(30, 64, 175, 0.3);
  text-decoration: none;
  color: white;
}

.category-networking { border-left: 4px solid #10b981; }
.category-cloud { border-left: 4px solid #f59e0b; }
.category-devops { border-left: 4px solid #ef4444; }

@media (max-width: 768px) {
  .projects-hero {
    margin: 0 -1rem 3rem;
    padding: 3rem 1.5rem;
  }
  
  .projects-hero h1 { font-size: 2.3rem; }
  
  .project-grid {
    grid-template-columns: 1fr;
    gap: 1.5rem;
  }
  
  .category-tabs {
    flex-direction: column;
    align-items: center;
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

  <!-- Networking Projects -->
  <div class="project-card category-networking" data-category="networking">
    <span class="project-icon">📡</span>
    <h3>Nokia ONT Provisioning</h3>
    <p>Bash automation for Wi-Fi setup, VLAN assignment, and comprehensive logging on Nokia ONTs across ISP networks.</p>
    <a href="https://github.com/lucianakenya/nokia-ont-provisioning" target="_blank" class="project-link">View Code →</a>
  </div>

  <div class="project-card category-networking" data-category="networking">
    <span class="project-icon">🌐</span>
    <h3>VSOL ONT Provisioning</h3>
    <p>Python SSH tool for TR-069 configuration management on VSOL OLTs with error handling and bulk operations.</p>
    <a href="https://github.com/lucianakenya/vsol-ont-automation" target="_blank" class="project-link">View Code →</a>
  </div>

  <div class="project-card category-networking" data-category="networking">
    <span class="project-icon">🔧</span>
    <h3>TR-069 Remote Configurator</h3>
    <p>Python script for remote ACS settings deployment with validation and rollback capabilities for customer devices.</p>
    <a href="https://github.com/lucianakenya/tr069-configurator" target="_blank" class="project-link">View Code →</a>
  </div>

  <!-- Cloud Projects -->
  <div class="project-card category-cloud" data-category="cloud">
    <span class="project-icon">☁️</span>
    <h3>Linux EC2 Setup</h3>
    <p>Secure Linux EC2 instance provisioning with security groups, IAM roles, and automated configuration management.</p>
    <a href="https://github.com/lucianakenya/aws-ec2-setup" target="_blank" class="project-link">View Code →</a>
  </div>

  <div class="project-card category-cloud" data-category="cloud">
    <span class="project-icon">🌐</span>
    <h3>Amazon VPC Networking</h3>
    <p>Complete VPC architecture with public/private subnets, NAT gateways, routing tables, and security controls.</p>
    <a href="https://github.com/lucianakenya/aws-vpc-networking" target="_blank" class="project-link">View Code →</a>
  </div>

  <!-- DevOps Projects -->
  <div class="project-card category-devops" data-category="devops">
    <span class="project-icon">🩺</span>
    <h3>Automated EC2 Health Checks</h3>
    <p>Ansible playbook for continuous EC2 monitoring with AWS SES email alerts and automated recovery actions.</p>
    <a href="https://github.com/lucianakenya/ec2-health-checks" target="_blank" class="project-link">View Code →</a>
  </div>

  <div class="project-card category-devops" data-category="devops">
    <span class="project-icon">🔄</span>
    <h3>Terraform Provisioning</h3>
    <p>Infrastructure as Code for reproducible EC2 deployments with modules, variables, and remote state management.</p>
    <a href="https://github.com/lucianakenya/terraform-ec2" target="_blank" class="project-link">View Code →</a>
  </div>

</div>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const tabs = document.querySelectorAll('.category-tab');
  const projects = document.querySelectorAll('.project-card');
  const grid = document.getElementById('projectGrid');

  tabs.forEach(tab => {
    tab.addEventListener('click', () => {
      // Update active tab
      tabs.forEach(t => t.classList.remove('active'));
      tab.classList.add('active');

      const category = tab.dataset.category;
      
      // Filter projects
      projects.forEach(project => {
        if (category === 'all' || project.dataset.category === category) {
          project.style.display = 'block';
          project.style.opacity = '0';
          project.style.transform = 'translateY(20px)';
          
          // Animate in
          setTimeout(() => {
            project.style.transition = 'all 0.4s ease';
            project.style.opacity = '1';
            project.style.transform = 'translateY(0)';
          }, 50);
        } else {
          project.style.display = 'none';
        }
      });

      // Reset grid layout
      grid.style.height = 'auto';
      setTimeout(() => {
        grid.style.transition = 'height 0.3s ease';
      }, 100);
    });
  });
});
</script>
