---
title: "My Projects"
layout: single
permalink: /projects/
author_profile: false
classes: wide
---

## Explore My Portfolio of Work

Welcome to my projects page! Here you'll find a showcase of my work in **Networking, Cloud, DevOps & Automation**.

<!-- Category Filter -->
<div class="category-filter">
  <button class="active" data-category="all">All</button>
  <button data-category="networking">Networking</button>
  <button data-category="cloud">Cloud</button>
  <button data-category="devops">DevOps</button>
</div>

<div class="project-grid">

  <!-- Networking Projects -->
  <div class="project-card" data-category="networking">
    <h3>📡 Nokia ONT Provisioning</h3>
    <p>Bash automation for Wi-Fi setup, VLAN assignment, and logging on Nokia ONTs.</p>
    <a href="https://github.com/lucianakenya/nokia-ont-provisioning" target="_blank">Learn More &rarr;</a>
  </div>

  <div class="project-card" data-category="networking">
    <h3>🌐 VSOL ONT Provisioning</h3>
    <p>Python SSH tool for TR-069 configuration on VSOL OLTs.</p>
    <a href="https://github.com/lucianakenya/vsol-ont-automation" target="_blank">Learn More &rarr;</a>
  </div>

  <div class="project-card" data-category="networking">
    <h3>🔧 TR-069 Remote Configurator</h3>
    <p>Python script for remote ACS settings deployment on customer devices.</p>
    <a href="https://github.com/lucianakenya/tr069-configurator" target="_blank">Learn More &rarr;</a>
  </div>

  <div class="project-card" data-category="networking">
    <h3>📊 Power Levels Audit Tool</h3>
    <p>SSH automation to gather ONT status, parse with pandas, export Excel reports.</p>
    <a href="https://github.com/lucianakenya/ont-audit-tool" target="_blank">Learn More &rarr;</a>
  </div>

  <!-- Cloud Projects -->
  <div class="project-card" data-category="cloud">
    <h3>☁️ Linux EC2 Setup</h3>
    <p>Provisioned and configured a secure Linux EC2 instance on AWS.</p>
    <a href="https://github.com/lucianakenya/aws-ec2-setup" target="_blank">Learn More &rarr;</a>
  </div>

  <div class="project-card" data-category="cloud">
    <h3>🌐 Amazon VPC Networking</h3>
    <p>Created VPC resources with subnets, routing tables, and gateways.</p>
    <a href="https://github.com/lucianakenya/aws-vpc-networking" target="_blank">Learn More &rarr;</a>
  </div>

  <div class="project-card" data-category="cloud">
    <h3>🚗 Car Rental Database on EC2</h3>
    <p>MariaDB-powered system hosted on AWS with backup and monitoring setup.</p>
    <a href="https://github.com/lucianakenya/car-rental-db" target="_blank">Learn More &rarr;</a>
  </div>

  <!-- DevOps Projects -->
  <div class="project-card" data-category="devops">
    <h3>🩺 Automated EC2 Health Checks</h3>
    <p>Ansible playbook for EC2 monitoring with email alerts via AWS SES.</p>
    <a href="https://github.com/lucianakenya/ec2-health-checks" target="_blank">Learn More &rarr;</a>
  </div>

  <div class="project-card" data-category="devops">
    <h3>🔄 Terraform Provisioning</h3>
    <p>EC2 provisioning using Terraform for reproducible infrastructure.</p>
    <a href="https://github.com/lucianakenya/terraform-ec2" target="_blank">Learn More &rarr;</a>
  </div>

  <div class="project-card" data-category="devops">
    <h3>⚡ CI/CD Pipeline</h3>
    <p>GitHub Actions for automated testing and deployment pipelines.</p>
    <a href="https://github.com/lucianakenya/ci-cd-pipeline" target="_blank">Learn More &rarr;</a>
  </div>

</div>

<style>
/* Project Grid & Cards */
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin-top: 1.5rem;
}
.project-card {
  background-color: #fff;
  border: 1px solid #e0e0e0;
  border-radius: 8px;
  padding: 1.5rem;
  box-shadow: 0 4px 8px rgba(0,0,0,0.05);
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}
.project-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 6px 12px rgba(0,0,0,0.1);
}
.project-card h3 {
  margin-top: 0;
  margin-bottom: 0.8rem;
  font-size: 1.3em;
}
.project-card h3 a {
  color: #007acc;
  text-decoration: none;
}
.project-card h3 a:hover {
  text-decoration: underline;
}
.project-card p {
  font-size: 0.95em;
  color: #555;
  flex-grow: 1;
  margin-bottom: 1rem;
}
.read-more-btn {
  display: inline-block;
  background-color: #007acc;
  color: white;
  padding: 0.6rem 1.2rem;
  border-radius: 5px;
  text-decoration: none;
  font-weight: bold;
  align-self: flex-start;
  transition: background-color 0.3s ease;
}
.read-more-btn:hover {
  background-color: #005f99;
}

/* Category Filter Buttons */
.category-filter {
  display: flex;
  flex-wrap: wrap;
  gap: 0.6rem;
  justify-content: center;
  margin-bottom: 1rem;
}
.category-filter button {
  background: #e9e9e9;
  border: 1px solid #dcdcdc;
  padding: 0.5rem 1rem;
  border-radius: 25px;
  cursor: pointer;
  font-size: 0.9em;
  font-weight: 500;
  transition: all 0.3s ease;
}
.category-filter button.active,
.category-filter button:hover {
  background: #007acc;
  color: white;
  border-color: #007acc;
}

/* Responsive */
@media (max-width: 768px) {
  .project-grid { grid-template-columns: 1fr; }
}
</style>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const filterButtons = document.querySelectorAll('.category-filter button');
  const projectCards = document.querySelectorAll('.project-card');

  filterButtons.forEach(button => {
    button.addEventListener('click', function() {
      filterButtons.forEach(btn => btn.classList.remove('active'));
      this.classList.add('active');
      const category = this.dataset.category;

      projectCards.forEach(card => {
        if (category === 'all' || card.dataset.category === category) {
          card.style.display = 'flex';
        } else {
          card.style.display = 'none';
        }
      });
    });
  });
});
</script>
