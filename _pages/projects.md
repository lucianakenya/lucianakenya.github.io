---
title: "My Projects"
layout: single
permalink: /projects/
author_profile: false
classes: wide
---

## Explore My Portfolio of Work

Welcome to my projects page! Here you'll find a detailed showcase of my work in **Networking, Cloud, DevOps & Automation**, and more. Each project highlights a specific problem, the technologies used, and the solutions implemented.

<div class="project-grid">
{% assign sorted_projects = site.projects | sort: "date" | reverse %}
{% for project in sorted_projects %}
  <div class="project-card">
    <h3><a href="{{ project.url | relative_url }}">{{ project.title }}</a></h3>
    <p class="project-category">{{ project.category }}</p>
    <p>{{ project.description | markdownify | strip_html | truncatewords: 30 }}</p>
    <a href="{{ project.url | relative_url }}" class="read-more-btn">Learn More &rarr;</a>
  </div>
{% endfor %}
</div>

<style>
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}

.project-card {
  background-color: #ffffff;
  border: 1px solid #e0e0e0;
  border-radius: 8px;
  padding: 1.5rem;
  box-shadow: 0 4px 8px rgba(0,0,0,0.05);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
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

.project-category {
  font-size: 0.9em;
  color: #777;
  margin-bottom: 0.8rem;
  text-transform: uppercase;
  letter-spacing: 0.05em;
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
  transition: background-color 0.3s ease;
  align-self: flex-start;
}

.read-more-btn:hover {
  background-color: #005f99;
}

@media (max-width: 768px) {
  .project-grid {
    grid-template-columns: 1fr;
  }
}
</style>
