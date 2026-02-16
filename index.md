---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
---
---
layout: single
author_profile: true
description: "LUCY NYAMBURA - Full Stack Dev | Network Engineer | Cloud Computing"
classes: wide
---

<style>
/* General Body */
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
  margin-top: 2rem;
  margin-bottom: 1rem;
}

p, li {
  margin-bottom: 0.5rem;
  max-width: 750px;
}

ul {
  padding-left: 1.3em;
  margin-bottom: 1.2rem;
}

/* Carousel */
.carousel-container {
  position: relative;
  overflow: hidden;
  padding: 1rem 0;
}

.carousel {
  display: flex;
  gap: 1.5rem;
  transition: transform 0.5s ease;
  padding: 0 1rem;
  will-change: transform;
}

.project-card {
  flex: 0 0 auto;
  width: 300px;
  background: linear-gradient(145deg, #fff, #f0f0f0);
  border-radius: 12px;
  padding: 1.5rem;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  box-shadow: 0 8px 16px rgba(0,0,0,0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 12px 24px rgba(0,0,0,0.2);
}

.project-card h3 {
  margin-top: 0;
  font-size: 1.2em;
  margin-bottom: 0.8rem;
}

.project-card p {
  font-size: 0.9em;
  flex-grow: 1;
  margin-bottom: 1rem;
}

.project-card a {
  color: #007acc;
  font-weight: 500;
  text-decoration: none;
  display: inline-block;
}

.project-card a:hover {
  text-decoration: underline;
}

.carousel-nav {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  background-color: rgba(255,255,255,0.8);
  border: 1px solid #ddd;
  border-radius: 50%;
  padding: 0.7rem 1rem;
  font-size: 1.5rem;
  cursor: pointer;
  z-index: 10;
  transition: background-color 0.3s, border-color 0.3s;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.carousel-nav:hover {
  background-color: #f0f0f0;
  border-color: #ccc;
}

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
  transition: background 0.3s, color 0.3s, border-color 0.3s;
  font-size: 0.9em;
}

.category-filter button.active {
  background: #007acc;
  color: white;
  border-color: #007acc;
}

.category-filter button:hover {
  background: #dcdcdc;
}

blockquote {
  border-left: 4px solid #007acc;
  padding-left: 1rem;
  color: #555;
  font-style: italic;
  margin: 2rem 0;
}
</style>

---

🌟 Welcome to My Portfolio

Hello! I'm **Lucy Nyambura**, a Network Engineer and Cloud Developer specializing in networking, automation, and cloud infrastructure. I design, implement, and optimize networks while building robust cloud and automation solutions.

With 3 years of experience in network monitoring, VPN configuration, and cloud deployment, I excel at solving technical challenges efficiently.

---

🚀 Featured Projects

<section class="projects-section">
  <div class="category-filter">
    <button class="active" data-category="all">All</button>
    <button data-category="networking">Networking</button>
    <button data-category="cloud">Cloud Projects</button>
    <button data-category="devops">DevOps & Automation</button>
  </div>

  <div class="carousel-container">
    <div class="carousel" id="projectCarousel">

      <!-- Networking Projects -->
      <div class="project-card" data-category="networking">
        <h3>Nokia ONT Provisioning</h3>
        <p>Bash automation for Wi‑Fi setup, VLAN assignment, and logging on Nokia ONTs.</p>
        <a href="https://lucy-portfolio-ebon.vercel.app/" target="_blank">View Project &rarr;</a>
      </div>

      <div class="project-card" data-category="networking">
        <h3>VSOL ONT Provisioning</h3>
        <p>Python SSH tool for TR‑069 configuration on VSOL OLTs.</p>
        <a href="https://lucy-portfolio-ebon.vercel.app/" target="_blank">View Project &rarr;</a>
      </div>

      <div class="project-card" data-category="networking">
        <h3>TR‑069 Remote Configurator</h3>
        <p>Python script for remote ACS settings deployment on customer devices.</p>
        <a href="https://lucy-portfolio-ebon.vercel.app/" target="_blank">View Project &rarr;</a>
      </div>

      <div class="project-card" data-category="networking">
        <h3>Power Levels Audit Tool</h3>
        <p>SSH automation to gather ONT status, parse with pandas, and export Excel reports.</p>
        <a href="https://lucy-portfolio-ebon.vercel.app/" target="_blank">View Project &rarr;</a>
      </div>

      <!-- Cloud Projects -->
      <div class="project-card" data-category="cloud">
        <h3>Linux EC2 Setup</h3>
        <p>Provisioned and configured a secure Linux EC2 instance on AWS.</p>
        <a href="https://lucy-portfolio-ebon.vercel.app/" target="_blank">View Project &rarr;</a>
      </div>

      <div class="project-card" data-category="cloud">
        <h3>Amazon VPC Networking</h3>
        <p>Created VPC resources with subnets, routing tables, and gateways.</p>
        <a href="https://lucy-portfolio-ebon.vercel.app/" target="_blank">View Project &rarr;</a>
      </div>

      <div class="project-card" data-category="cloud">
        <h3>Car Rental Database on EC2</h3>
        <p>MariaDB-powered system hosted on AWS with backup and monitoring setup.</p>
        <a href="https://lucy-portfolio-ebon.vercel.app/" target="_blank">View Project &rarr;</a>
      </div>

      <!-- DevOps & Automation -->
      <div class="project-card" data-category="devops">
        <h3>Automated EC2 Health Checks</h3>
        <p>Ansible playbook for EC2 monitoring with email alerts via AWS SES.</p>
        <a href="https://lucy-portfolio-ebon.vercel.app/" target="_blank">View Project &rarr;</a>
      </div>

      <div class="project-card" data-category="devops">
        <h3>Provisioning with Terraform</h3>
        <p>EC2 provisioning using Terraform executed on AWS for reproducible infrastructure.</p>
        <a href="https://lucy-portfolio-ebon.vercel.app/" target="_blank">View Project &rarr;</a>
      </div>

      <div class="project-card" data-category="devops">
        <h3>Continuous Integration & Deployment</h3>
        <p>CI/CD workflow implementation using GitHub Actions for automated deployments.</p>
        <a href="https://lucy-portfolio-ebon.vercel.app/" target="_blank">View Project &rarr;</a>
      </div>

    </div>

    <button class="carousel-nav left" onclick="scrollCarousel(-1)">&lt;</button>
    <button class="carousel-nav right" onclick="scrollCarousel(1)">&gt;</button>
  </div>
</section>

<p style="text-align:center; margin-top:2rem;">
  For more projects, visit the <a href="{{ '/projects/' | relative_url }}">Projects page</a>.
</p>

---

🌟 Key Expertise Areas

<section>
<h3>🌐 Networking & Cloud</h3>
<ul>
  <li>Network monitoring, VPN setup, routing, and firewall configuration.</li>
  <li>Cloud deployment and automation in AWS and Azure.</li>
  <li>Infrastructure troubleshooting and optimization.</li>
</ul>

<h3>🤖 Automation & Scripting</h3>
<ul>
  <li>Python scripting for network maintenance, reporting, and process automation.</li>
  <li>Automating deployments and resource monitoring in cloud environments.</li>
</ul>
</section>

---

🤝 Let's Connect!

<ul>
  <li><strong>Email:</strong> <a href="mailto:nyamburalucy678@gmail.com">nyamburalucy678@gmail.com</a></li>
  <li><strong>Phone:</strong> +254 703 498 550</li>
  <li><strong>GitHub:</strong> <a href="https://github.com/lucianakenya" target="_blank">github.com/lucianakenya</a></li>
  <li><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/lucy-nyambura-5704a1232" target="_blank">linkedin.com/in/lucy-nyambura-5704a1232</a></li>
</ul>

<blockquote>
  <strong>“Networks are like puzzles and I enjoy solving them with code and creativity.”</strong>
</blockquote>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const carousel = document.getElementById('projectCarousel');
  const projectCards = Array.from(carousel.children);
  const filterButtons = document.querySelectorAll('.category-filter button');
  let currentIndex = 0;
  const cardsPerView = 3;

  const updateCarousel = () => {
    const cardWidth = projectCards[0].offsetWidth;
    const gap = parseFloat(getComputedStyle(carousel).gap);
    const shift = (cardWidth + gap) * currentIndex;
    carousel.style.transform = `translateX(-${shift}px)`;
  };

  window.scrollCarousel = (direction) => {
    const totalCards = projectCards.filter(c => c.style.display !== 'none').length;
    const maxIndex = Math.max(0, totalCards - cardsPerView);
    currentIndex = Math.min(Math.max(currentIndex + direction, 0), maxIndex);
    updateCarousel();
  };

  filterButtons.forEach(button => {
    button.addEventListener('click', function() {
      filterButtons.forEach(btn => btn.classList.remove('active'));
      this.classList.add('active');
      const category = this.dataset.category;
      currentIndex = 0;
      projectCards.forEach(card => {
        card.style.display = (category === 'all' || card.dataset.category === category) ? 'flex' : 'none';
      });
      updateCarousel();
    });
  });

  updateCarousel();
});
</script>

