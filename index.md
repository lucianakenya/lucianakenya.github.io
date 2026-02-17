---
layout: single
author_profile: true
description: "LUCY NYAMBURA - DevOps & Automation | Network Engineer | Cloud Computing | Cyber Security"
classes: wide
---

<style>
/* Global Styles */
body {
  font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
  background: #f5f7fa;
  color: #222;
  margin: 0;
  line-height: 1.6;
}

/* Hero Section */
.hero {
  position: relative;
  text-align: center;
  padding: 8rem 1rem 6rem 1rem;
  background: url('https://images.unsplash.com/photo-1522202176988-66273c2fd55f?auto=format&fit=crop&w=1950&q=80') center/cover no-repeat;
  color: white;
  overflow: hidden;
}

.hero::before {
  content: '';
  position: absolute;
  inset: 0;
  background: rgba(0,0,0,0.4); /* dark overlay to enhance readability */
  z-index: 0;
}

.hero h1, .hero h2, .hero p {
  position: relative;
  z-index: 1;
}

.hero h1 {
  font-size: 3rem;
  margin-bottom: 0.5rem;
}

.hero h2 {
  font-size: 1.6rem;
  font-weight: 400;
  margin-bottom: 1rem;
  opacity: 0.9;
}

.hero p {
  font-size: 1.1rem;
  max-width: 600px;
  margin: 0 auto;
  opacity: 0.85;
}

/* Floating Accent Circles */
.hero .accent-circle {
  position: absolute;
  border-radius: 50%;
  background: #667eea33;
  z-index: 0;
}
.hero .circle1 { width: 200px; height: 200px; top: 30px; left: -50px; }
.hero .circle2 { width: 150px; height: 150px; bottom: 50px; right: -30px; }

/* Skills Section */
#skills {
  text-align: center;
  padding: 4rem 1rem;
}

#skills h2 {
  font-size: 2rem;
  margin-bottom: 2rem;
  color: #333;
}

.skills-grid {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 1rem;
}

.skills-grid li {
  list-style: none;
  background: #fff;
  padding: 0.8rem 1rem;
  border-radius: 40px;
  box-shadow: 0 6px 18px rgba(0,0,0,0.08);
  display: flex;
  align-items: center;
  font-weight: 500;
  font-size: 0.95rem;
  gap: 0.5rem;
  transition: transform 0.3s, box-shadow 0.3s;
}

.skills-grid li:hover {
  transform: translateY(-4px);
  box-shadow: 0 12px 28px rgba(0,0,0,0.12);
}

/* Projects Section Preview */
#projects-preview {
  text-align: center;
  padding: 4rem 1rem;
}

#projects-preview h2 {
  font-size: 2rem;
  margin-bottom: 2rem;
}

.project-card {
  background: #fff;
  border-radius: 20px;
  box-shadow: 0 8px 24px rgba(0,0,0,0.08);
  padding: 1.5rem;
  margin: 1rem;
  transition: transform 0.3s, box-shadow 0.3s;
}

.project-card:hover {
  transform: translateY(-6px);
  box-shadow: 0 14px 36px rgba(0,0,0,0.12);
}

.project-card h3 {
  margin-bottom: 0.5rem;
  color: #333;
}

.project-card p {
  font-size: 0.95rem;
  color: #555;
  margin-bottom: 1rem;
}

.project-link {
  text-decoration: none;
  color: #667eea;
  font-weight: 600;
  transition: color 0.3s;
}

.project-link:hover {
  color: #764ba2;
}

/* Contact Section CTA */
#contact-cta {
  text-align: center;
  padding: 4rem 1rem;
}

#contact-cta h2 {
  font-size: 2rem;
  margin-bottom: 1rem;
  color: #333;
}

#contact-cta p {
  font-size: 1.1rem;
  color: #555;
  margin-bottom: 2rem;
}

#contact-cta a {
  background: #667eea;
  color: white;
  padding: 0.9rem 2rem;
  border-radius: 50px;
  text-decoration: none;
  font-weight: 600;
  transition: background 0.3s, transform 0.3s;
}

#contact-cta a:hover {
  background: #764ba2;
  transform: translateY(-3px);
}

/* Responsive */
@media (max-width: 768px) {
  .hero h1 { font-size: 2.3rem; }
  .hero h2 { font-size: 1.3rem; }
  .skills-grid { flex-direction: column; align-items: center; }
  .project-card { margin: 1rem auto; width: 90%; }
}
</style>

<!-- Hero -->
<div class="hero">
  <div class="accent-circle circle1"></div>
  <div class="accent-circle circle2"></div>
  <h1>🌟 Lucy Nyambura</h1>
  <h2>Network Engineer • DevOps • Cloud Infrastructure</h2>
  <p>4+ years building secure networks, automating infrastructure, and deploying scalable cloud solutions</p>
</div>

<!-- Skills -->
<section id="skills">
  <h2>Technical Expertise</h2>
  <ul class="skills-grid">
    <li><i class="fas fa-network-wired"></i> IP Routing: OSPF, BGP</li>
    <li><i class="fas fa-network-wired"></i> MPLS, fault troubleshooting</li>
    <li><i class="fas fa-cloud"></i> AWS: EC2, VPC, IAM, S3</li>
    <li><i class="fas fa-code"></i> Python, Bash scripting</li>
    <li><i class="fas fa-cogs"></i> Terraform & CloudFormation</li>
    <li><i class="fas fa-shield-alt"></i> Cloud security & compliance</li>
  </ul>
</section>

<!-- Projects Preview -->
<section id="projects-preview">
  <h2>Featured Projects</h2>
  <div class="project-card">
    <h3>Nokia ONT Provisioning</h3>
    <p>Bash script to automate Wi-Fi setup, serial validation, VLAN assignment, and activity logging.</p>
    <a href="https://github.com/lucianakenya/nokia_autoprovisioning" class="project-link" target="_blank">View Project</a>
  </div>
  <div class="project-card">
    <h3>Linux EC2 Setup</h3>
    <p>Provisioned a Linux-based EC2 instance on AWS with secure access and configuration.</p>
    <a href="https://medium.com/@nyamburalucy678/launching-an-ec2-instance-19b86f6b4b5b" class="project-link" target="_blank">View Project</a>
  </div>
  <p style="margin-top: 1.5rem;"><a href="/projects" class="project-link">See all projects →</a></p>
</section>

<!-- Contact CTA -->
<section id="contact-cta">
  <h2>Let's Collaborate!</h2>
  <p>Reach out for network engineering, DevOps automation, or cloud infrastructure projects</p>
  <a href="/contact">Contact Me</a>
</section>

