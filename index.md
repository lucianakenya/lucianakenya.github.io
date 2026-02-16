---
layout: single
author_profile: true
description: "LUCY NYAMBURA - DevOps & Automation | Network Engineer | Cloud Computing | Cyber Security"
classes: wide
---

<style>
/* Reset and Base Styles */
* { box-sizing: border-box; margin: 0; padding: 0; }
body { 
  line-height: 1.6; 
  font-family: inherit; 
  background-color: #fafafa; 
  color: #222; 
}

section {
  max-width: 900px;
  margin: 0 auto 2.5rem;
  padding: 0 1rem;
}

h2, h3 {
  color: #222;
  font-weight: 600;
  margin: 2rem 0 1rem 0;
}

p, li {
  margin-bottom: 0.5rem;
  max-width: 750px;
}

/* Hero Section */
.hero {
  text-align: center;
  padding: 3rem 1rem;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  margin-bottom: 3rem;
}

.hero h1 { font-size: 2.5rem; margin-bottom: 0.5rem; }
.hero h2 { font-size: 1.3rem; opacity: 0.9; margin-bottom: 1.5rem; }

/* Carousel Styles */
.carousel-container {
  position: relative;
  overflow: hidden;
  padding: 1rem 0;
  margin: 2rem 0;
}

.carousel {
  display: flex;
  gap: 1.5rem;
  transition: transform 0.5s ease;
  padding: 0 2.5rem;
  will-change: transform;
}

.project-card {
  flex: 0 0 300px;
  background: linear-gradient(145deg, #fff, #f0f0f0);
  border-radius: 12px;
  padding: 1.5rem;
  display: flex;
  flex-direction: column;
  box-shadow: 0 8px 16px rgba(0,0,0,0.1);
  transition: all 0.3s ease;
}

.project-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 12px 24px rgba(0,0,0,0.2);
}

.project-card h3 {
  margin: 0 0 0.8rem 0;
  font-size: 1.2em;
  color: #222;
}

.project-card p {
  font-size: 0.9em;
  flex-grow: 1;
  margin-bottom: 1rem;
  color: #555;
}

.project-card a {
  color: #007acc;
  font-weight: 500;
  text-decoration: none;
  border: 1px solid #007acc;
  padding: 0.5rem 1rem;
  border-radius: 5px;
  transition: all 0.3s ease;
  text-align: center;
}

.project-card a:hover {
  background: #007acc;
  color: white;
}

/* Carousel Navigation */
.carousel-nav {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  background: rgba(255,255,255,0.9);
  border: 1px solid #ddd;
  border-radius: 50%;
  width: 45px;
  height: 45px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 1.5rem;
  cursor: pointer;
  z-index: 10;
  transition: all 0.3s ease;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.carousel-nav:hover { background: #f0f0f0; }
.carousel-nav.left { left: 0.5rem; }
.carousel-nav.right { right: 0.5rem; }

/* Filter Buttons */
.category-filter {
  display: flex;
  flex-wrap: wrap;
  gap: 0.6rem;
  margin-bottom: 1.8rem;
  justify-content: center;
}

.category-filter button {
  background: #e9e9e9;
  border: 1px solid #dcdcdc;
  padding: 0.5rem 1.2rem;
  border-radius: 25px;
  cursor: pointer;
  transition: all 0.3s ease;
  font-size: 0.9em;
  font-weight: 500;
}

.category-filter button.active,
.category-filter button:hover {
  background: #007acc;
  color: white;
  border-color: #007acc;
}

.skills-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.5rem;
  margin: 2rem 0;
}

.skill-card {
  background: white;
  padding: 1.5rem;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.08);
  border-left: 4px solid #007acc;
}

.contact-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1rem;
  margin: 2rem 0;
}

.contact-item {
  background: white;
  padding: 1.5rem;
  border-radius: 10px;
  text-align: center;
  box-shadow: 0 4px 12px rgba(0,0,0,0.08);
  transition: transform 0.3s ease;
}

.contact-item:hover { transform: translateY(-4px); }

blockquote {
  border-left: 4px solid #007acc;
  padding-left: 1.5rem;
  color: #555;
  font-style: italic;
  margin: 2rem 0;
  background: #f8f9fa;
  padding: 1.5rem;
  border-radius: 8px;
}

/* Responsive */
@media (max-width: 768px) {
  .project-card { flex: 0 0 280px; }
  .carousel { gap: 1rem; padding: 0 2rem; }
  .hero h1 { font-size: 2rem; }
  .category-filter { flex-direction: column; align-items: center; }
}
</style>

<div class="hero">
  <h1>🌟 Lucy Nyambura</h1>
  <h2>Network Engineer • DevOps • Cloud Infrastructure</h2>
  <p>4+ years building secure networks, automating infrastructure, and deploying scalable cloud solutions</p>
</div>

## 🚀 Featured Projects

<div class="projects-section">
  <div class="category-filter">
    <button class="active" data-category="all">All Projects</button>
    <button data-category="networking">Networking</button>
    <button data-category="cloud">Cloud</button>
    <button data-category="devops">DevOps</button>
  </div>

  <div class="carousel-container">
    <div class="carousel" id="projectCarousel">
      <!-- Networking Projects -->
      <div class="project-card" data-category="networking">
        <h3>📡 Nokia ONT Provisioning</h3>
        <p>Bash automation for Wi-Fi setup, VLAN assignment, and logging on Nokia ONTs.</p>
        <a href="https://github.com/lucianakenya/nokia-ont-provisioning" target="_blank">View Code →</a>
      </div>

  <div class="project-card" data-category="networking">
    <h3>🌐 VSOL ONT Provisioning</h3>
    <p>Python SSH tool for TR-069 configuration on VSOL OLTs.</p>
    <a href="https://github.com/lucianakenya/vsol-ont-automation" target="_blank">View Code →</a>
  </div>

  <div class="project-card" data-category="networking">
    <h3>🔧 TR-069 Remote Configurator</h3>
    <p>Python script for remote ACS settings deployment on customer devices.</p>
    <a href="https://github.com/lucianakenya/tr069-configurator" target="_blank">View Code →</a>
  </div>

  <div class="project-card" data-category="networking">
    <h3>📊 Power Levels Audit Tool</h3>
    <p>SSH automation to gather ONT status, parse with pandas, export Excel reports.</p>
    <a href="https://github.com/lucianakenya/ont-audit-tool" target="_blank">View Code →</a>
  </div>

  <!-- Cloud Projects -->
  <div class="project-card" data-category="cloud">
    <h3>☁️ Linux EC2 Setup</h3>
    <p>Provisioned and configured a secure Linux EC2 instance on AWS.</p>
    <a href="https://github.com/lucianakenya/aws-ec2-setup" target="_blank">View Code →</a>
  </div>

  <div class="project-card" data-category="cloud">
    <h3>🌐 Amazon VPC Networking</h3>
    <p>Created VPC resources with subnets, routing tables, and gateways.</p>
    <a href="https://github.com/lucianakenya/aws-vpc-networking" target="_blank">View Code →</a>
  </div>

  <div class="project-card" data-category="cloud">
    <h3>🚗 Car Rental Database on EC2</h3>
    <p>MariaDB-powered system hosted on AWS with backup and monitoring setup.</p>
    <a href="https://github.com/lucianakenya/car-rental-db" target="_blank">View Code →</a>
  </div>

  <!-- DevOps Projects -->
  <div class="project-card" data-category="devops">
    <h3>🩺 Automated EC2 Health Checks</h3>
    <p>Ansible playbook for EC2 monitoring with email alerts via AWS SES.</p>
    <a href="https://github.com/lucianakenya/ec2-health-checks" target="_blank">View Code →</a>
  </div>

  <div class="project-card" data-category="devops">
    <h3>🔄 Terraform Provisioning</h3>
    <p>EC2 provisioning using Terraform for reproducible infrastructure.</p>
    <a href="https://github.com/lucianakenya/terraform-ec2" target="_blank">View Code →</a>
  </div>

  <div class="project-card" data-category="devops">
    <h3>⚡ CI/CD Pipeline</h3>
    <p>GitHub Actions for automated testing and deployment pipelines.</p>
    <a href="https://github.com/lucianakenya/ci-cd-pipeline" target="_blank">View Code →</a>
  </div>
</div>

<button class="carousel-nav left" onclick="scrollCarousel(-1)">‹</button>
<button class="carousel-nav right" onclick="scrollCarousel(1)">›</button>
  </div>
</div>

## 🛠 Key Expertise

<div class="skills-grid">
  <div class="skill-card">
    <h3>🌐 Networking</h3>
    <ul>
      <li>ONT provisioning (Nokia, VSOL)</li>
      <li>VPN configuration & routing</li>
      <li>Network monitoring & auditing</li>
      <li>TR-069 ACS management</li>
    </ul>
  </div>

  <div class="skill-card">
    <h3>☁️ Cloud Infrastructure</h3>
    <ul>
      <li>AWS EC2, VPC, RDS</li>
      <li>Azure fundamentals (AZ-900)</li>
      <li>Backup & disaster recovery</li>
      <li>Cloud security best practices</li>
    </ul>
  </div>

  <div class="skill-card">
    <h3>🤖 DevOps & Automation</h3>
    <ul>
      <li>Python & Bash scripting</li>
      <li>Terraform Infrastructure as Code</li>
      <li>Ansible configuration management</li>
      <li>GitHub Actions CI/CD</li>
    </ul>
  </div>
</div>

## 📞 Let's Connect

<div class="contact-grid">
  <div class="contact-item">
    <h3>📧 Email</h3>
    <p><a href="mailto:nyamburalucy678@gmail.com">nyamburalucy678@gmail.com</a></p>
  </div>
  <div class="contact-item">
    <h3>📱 Phone</h3>
    <p>+254 703 498 550</p>
  </div>
  <div class="contact-item">
    <h3>💻 GitHub</h3>
    <p><a href="https://github.com/lucianakenya" target="_blank">lucianakenya</a></p>
  </div>
  <div class="contact-item">
    <h3>💼 LinkedIn</h3>
    <p><a href="https://www.linkedin.com/in/lucy-nyambura-5704a1232" target="_blank">Lucy Nyambura</a></p>
  </div>
</div>

> **"Networks are like puzzles and I enjoy solving them with code and creativity."**

<script>
document.addEventListener('DOMContentLoaded', function() {
  const carousel = document.getElementById('projectCarousel');
  const projectCards = Array.from(carousel.children);
  const filterButtons = document.querySelectorAll('.category-filter button');
  let currentIndex = 0;
  const cardsPerView = window.innerWidth > 768 ? 3 : 1;

  function updateCarouselPosition() {
    const visibleCards = projectCards.filter(card => card.style.display !== 'none');
    const cardWidth = visibleCards[0]?.offsetWidth || 300;
    const gap = 24; // 1.5rem gap
    const totalShift = (cardWidth + gap) * currentIndex;
    carousel.style.transform = `translateX(-${totalShift}px)`;
  }

  window.scrollCarousel = function(direction) {
    const visibleCards = projectCards.filter(card => card.style.display !== 'none');
    const maxIndex = Math.max(0, visibleCards.length - cardsPerView);
    
    currentIndex += direction;
    currentIndex = Math.max(0, Math.min(currentIndex, maxIndex));
    updateCarouselPosition();
  };

  // Filter functionality
  filterButtons.forEach(button => {
    button.addEventListener('click', function() {
      filterButtons.forEach(btn => btn.classList.remove('active'));
      this.classList.add('active');

      const category = this.dataset.category;
      currentIndex = 0;

      projectCards.forEach(card => {
        if (category === 'all' || card.dataset.category === category) {
          card.style.display = 'flex';
        } else {
          card.style.display = 'none';
        }
      });
      
      updateCarouselPosition();
    });
  });

  // Touch/swipe support for mobile
  let startX = 0;
  carousel.addEventListener('touchstart', e => startX = e.touches[0].clientX);
  carousel.addEventListener('touchend', e => {
    const endX = e.changedTouches[0].clientX;
    if (startX - endX > 50) scrollCarousel(1);
    if (endX - startX > 50) scrollCarousel(-1);
  });

  updateCarouselPosition();
});
</script>
