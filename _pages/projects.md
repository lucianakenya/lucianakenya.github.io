---
title: "My Projects"
layout: single
permalink: /projects/
author_profile: true
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

  <!-- Example Project Card -->
  <div class="project-card" data-category="networking">
    <h3>📡 Nokia ONT Provisioning</h3>
    <p>Bash automation for Wi-Fi setup, VLAN assignment, and logging on Nokia ONTs.</p>
    <a href="https://github.com/lucianakenya/nokia-ont-provisioning" target="_blank">Learn More &rarr;</a>
  </div>
  <!-- Add all other project cards here, same structure -->

</div>

<style>
/* Font & Base Styles */
body {
  font-family: 'Inter', 'Roboto', sans-serif;
  background-color: #f9f9f9;
  color: #333;
  line-height: 1.6;
}
h2, h3 { color: #222; font-weight: 600; }
p { color: #555; }

/* Project Grid & Cards */
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}
.project-card {
  background: #ffffff;
  border-radius: 10px;
  padding: 1.5rem;
  box-shadow: 0 6px 15px rgba(0,0,0,0.07);
  display: flex;
  flex-direction: column;
  transition: all 0.3s ease;
}
.project-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 25px rgba(0,0,0,0.12);
}
.project-card h3 {
  margin-top: 0;
  margin-bottom: 0.8rem;
  font-size: 1.3em;
}
.project-card h3 a {
  color: #007acc;
  text-decoration: none;
  font-weight: 600;
}
.project-card h3 a:hover { text-decoration: underline; }
.project-card p { font-size: 0.95em; margin-bottom: 1rem; }
.read-more-btn {
  display: inline-block;
  background: linear-gradient(135deg,#667eea,#764ba2);
  color: white;
  padding: 0.6rem 1.2rem;
  border-radius: 6px;
  text-decoration: none;
  font-weight: 600;
  align-self: flex-start;
  transition: all 0.3s ease;
}
.read-more-btn:hover {
  background: linear-gradient(135deg,#5a6dd6,#603f9f);
  transform: translateY(-2px);
}

/* Category Filter Buttons */
.category-filter {
  display: flex;
  flex-wrap: wrap;
  gap: 0.8rem;
  justify-content: center;
  margin-bottom: 2rem;
}
.category-filter button {
  background: #e0e0e0;
  border: none;
  padding: 0.5rem 1.2rem;
  border-radius: 25px;
  cursor: pointer;
  font-size: 0.95em;
  font-weight: 500;
  transition: all 0.3s ease;
}
.category-filter button.active,
.category-filter button:hover {
  background: #007acc;
  color: white;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
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
        card.style.display = (category === 'all' || card.dataset.category === category) ? 'flex' : 'none';
      });
    });
  });
});
</script>
