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

  --bg-page: #f8fafc;
  --card-bg: #ffffff;
  --text-primary: #111827;
  --text-secondary: #4b5563;
  --border: #e5e7eb;
  --shadow: 0 10px 40px rgba(0,0,0,0.08);
  --shadow-hover: 0 20px 60px rgba(0,0,0,0.12);
}

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

body { 
  background: var(--bg-page); 
  font-family: system-ui, sans-serif; 
  margin:0; padding:0; 
}

/* HERO */
.projects-hero {
  text-align: center;
  padding: 3rem 2rem;
  border-radius: 24px;
}
.projects-hero h1 { font-size: 2.5rem; margin-bottom: 0.8rem; }
.projects-hero p { font-size: 1.1rem; color: var(--text-secondary); }

/* CATEGORY TABS */
.category-tabs {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 1rem;
  margin: 2rem 0;
}
.category-tab {
  background: var(--card-bg);
  color: var(--text-secondary);
  padding: 0.6rem 1.2rem;
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

/* CAROUSEL */
.carousel-wrapper {
  position: relative;
  margin: 2rem 0 4rem;
  overflow: hidden;
}
.project-carousel {
  display: flex;
  gap: 1.5rem;
  scroll-behavior: smooth;
  overflow-x: auto;
  padding-bottom: 1rem;
}
.project-card {
  flex: 0 0 320px;
  background: var(--card-bg);
  border-radius: 20px;
  padding: 1.5rem;
  border: 1px solid var(--border);
  box-shadow: var(--shadow);
  transition: all 0.3s ease;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
.project-card:hover { transform: translateY(-6px); box-shadow: var(--shadow-hover); }
.project-card h3 { margin: 0.5rem 0; color: var(--text-primary); }
.project-card p { color: var(--text-secondary); font-size: 0.95rem; line-height: 1.4; }
.project-link {
  margin-top: 1rem;
  display: inline-block;
  padding: 0.5rem 1rem;
  background: var(--primary);
  color: white;
  border-radius: 10px;
  text-decoration: none;
  font-size: 0.9rem;
}
.project-link:hover { opacity: 0.9; }

/* Carousel Arrows */
.carousel-arrow {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  background: rgba(0,0,0,0.1);
  border: none;
  font-size: 2rem;
  padding: 0.3rem 0.6rem;
  border-radius: 50%;
  cursor: pointer;
  z-index: 10;
}
.carousel-arrow.left { left: 0.5rem; }
.carousel-arrow.right { right: 0.5rem; }

/* Responsive */
@media (max-width: 768px) {
  .project-card { flex: 0 0 260px; }
}
</style>

<div class="projects-hero">
  <h1> My Projects</h1>
  <p>Showcasing real-world networking, cloud, and DevOps solutions I've built with automation and scalability in mind.</p>
</div>

<div class="category-tabs">
  <button class="category-tab active" data-category="all">All</button>
  <button class="category-tab" data-category="networking">Networking</button>
  <button class="category-tab" data-category="cloud">Cloud</button>
  <button class="category-tab" data-category="devops">DevOps</button>
</div>

<div class="carousel-wrapper">
  <button class="carousel-arrow left">&#10094;</button>
  <div class="project-carousel" id="projectCarousel">

  <!-- NETWORKING -->
  <div class="project-card" data-category="networking">
    <h3>Nokia ONT Provisioning</h3>
    <p>Bash script to automate Wi-Fi setup, serial validation, VLAN assignment, and activity logging.</p>
    <a href="https://github.com/lucianakenya/nokia_autoprovisioning" target="_blank" class="project-link">View Project</a>
  </div>
  <div class="project-card" data-category="networking">
    <h3>VSOL ONT Provisioning</h3>
    <p>Python tool for SSH-based TR-069 configuration across VSOL OLTs with secure credential handling.</p>
    <a href="https://github.com/lucianakenya/vsol_provisioning_script" target="_blank" class="project-link">View Project</a>
  </div>
  <div class="project-card" data-category="networking">
    <h3>TR-069 Remote Configurator</h3>
    <p>Python script to remotely apply ACS settings on Nokia/VSOL devices with reachability checks.</p>
    <a href="https://github.com/lucianakenya/configuring_TR-069" target="_blank" class="project-link">View Project</a>
  </div>
  <div class="project-card" data-category="networking">
    <h3>Power Levels Audit Tool</h3>
    <p>SSH automation to collect ONT status, parse with pandas, and export structured Excel reports.</p>
    <a href="https://github.com/lucianakenya/Power_levels_audit" target="_blank" class="project-link">View Project</a>
  </div>

  <!-- CLOUD -->
  <div class="project-card" data-category="cloud">
    <h3>Linux EC2 Setup</h3>
    <p>Provisioned a Linux-based EC2 instance on AWS with secure access and basic configuration.</p>
    <a href="https://medium.com/@nyamburalucy678/launching-an-ec2-instance-19b86f6b4b5b" target="_blank" class="project-link">View Project</a>
  </div>
  <div class="project-card" data-category="cloud">
    <h3>Amazon VPC Networking</h3>
    <p>Created networking resources in an Amazon VPC including subnets, route tables, and gateways.</p>
    <a href="https://medium.com/@nyamburalucy678/creating-networking-resources-in-an-amazon-vpc-5f3df03a03f4" target="_blank" class="project-link">View Project</a>
  </div>
  <div class="project-card" data-category="cloud">
    <h3>Car Rental Database on EC2</h3>
    <p>Built a MariaDB-powered car rental system hosted on AWS EC2 with secure access and backups.</p>
    <a href="https://medium.com/@nyamburalucy678/building-a-car-rental-database-on-aws-ec2-with-mariadb-088835ae54a0" target="_blank" class="project-link">View Project</a>
  </div>
  <div class="project-card" data-category="cloud">
    <h3>AWS CLI & IAM Exploration</h3>
    <p>Installed AWS CLI and explored IAM roles and policies on Amazon Linux and Red Hat EC2 instances.</p>
    <a href="https://medium.com/@nyamburalucy678/installing-aws-cli-and-exploring-iam-on-ec2-amazon-linux-red-hat-d7d954d9e419" target="_blank" class="project-link">View Project</a>
  </div>
  <div class="project-card" data-category="cloud">
    <h3>Hosting a Static Website on S3</h3>
    <p>Hosted a static café website on Amazon S3 with public access and responsive design.</p>
    <a href="https://medium.com/@nyamburalucy678/how-i-hosted-my-caf%C3%A9-website-on-amazon-s3-securely-using-aws-console-and-cli-7498d16cbeee" target="_blank" class="project-link">View Project</a>
  </div>
  <div class="project-card" data-category="cloud">
    <h3>S3 Bucket Security</h3>
    <p>Secured an S3 bucket against accidental deletion and bugs using bucket policies and versioning.</p>
    <a href="https://medium.com/@nyamburalucy678/%EF%B8%8F-how-i-secured-my-s3-bucket-against-accidental-deletion-and-bugs-4aab4a514cc2" target="_blank" class="project-link">View Project</a>
  </div>

  <!-- DEVOPS / AUTOMATION -->
  <div class="project-card" data-category="devops">
    <h3>Automated EC2 Health Checks</h3>
    <p>Ansible playbook to automate EC2 health checks with email alerts via AWS SES.</p>
    <a href="https://medium.com/@nyamburalucy678/how-i-automated-ec2-health-checks-and-email-alerts-with-ansible-and-aws-ses-0f1d4d3c6a49" target="_blank" class="project-link">View Project</a>
  </div>
  <div class="project-card" data-category="devops">
    <h3>Provisioning with Terraform</h3>
    <p>Step-by-step EC2 provisioning using Terraform installed directly on an AWS instance.</p>
    <a href="https://medium.com/@nyamburalucy678/automating-ec2-provisioning-with-terraform-installed-on-ec2-a-step-by-step-guide-c655a7794921" target="_blank" class="project-link">View Project</a>
  </div>
  <div class="project-card" data-category="devops">
    <h3>CI/CD Pipeline</h3>
    <p>Built a complete CI/CD workflow using Python, GitHub Actions, and Notepad (no IDE, no cloud required).</p>
    <a href="https://medium.com/@nyamburalucy678/building-my-first-ci-cd-pipeline-from-scratch-no-ide-no-cloud-just-git-cmd-and-notepad-302eed94ac07" target="_blank" class="project-link">View Project</a>
  </div>
  <div class="project-card" data-category="devops">
    <h3>DevOps Jumpstart Node.js App</h3>
    <p>Deployed a Node.js app on Ubuntu EC2 with GitHub version control and a CI/CD pipeline.</p>
    <a href="https://medium.com/@nyamburalucy678/devops-jumpstart-building-and-deploying-a-node-js-ddbe2cbb6d4b" target="_blank" class="project-link">View Project</a>
  </div>
  <div class="project-card" data-category="devops">
    <h3>Flask Blog Deployment</h3>
    <p>Deployed a Flask blog to AWS Elastic Beanstalk with SQLite and EB CLI version control.</p>
    <a href="https://medium.com/@nyamburalucy678/deploying-a-flask-blog-to-aws-elastic-beanstalk-with-sqlite-5ac12f1d1ebd" target="_blank" class="project-link">View Project</a>
  </div>

  </div>
  <button class="carousel-arrow right">&#10095;</button>
</div>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const tabs = document.querySelectorAll('.category-tab');
  const projects = document.querySelectorAll('.project-card');
  const carousel = document.getElementById('projectCarousel');

  tabs.forEach(tab => {
    tab.addEventListener('click', () => {
      tabs.forEach(t => t.classList.remove('active'));
      tab.classList.add('active');
      const category = tab.dataset.category;

      projects.forEach(p => {
        if (category === 'all' || p.dataset.category === category) {
          p.style.display = 'flex';
        } else {
          p.style.display = 'none';
        }
      });
    });
  });

  const leftArrow = document.querySelector('.carousel-arrow.left');
  const rightArrow = document.querySelector('.carousel-arrow.right');
  leftArrow.addEventListener('click', () => { carousel.scrollBy({ left: -350, behavior: 'smooth' }); });
  rightArrow.addEventListener('click', () => { carousel.scrollBy({ left: 350, behavior: 'smooth' }); });
});
</script>
