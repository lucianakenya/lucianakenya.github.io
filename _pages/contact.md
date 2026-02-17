---
title: "Contact Me"
layout: single
permalink: /contact/
author_profile: true
classes: wide
---

<style>
:root {
  --primary: #1e40af;
  --accent: #3b82f6;
  --bg-light: #f8fafc;
  --bg-dark: #0f172a;
  --card-light: #ffffff;
  --card-dark: #1e293b;
  --text-light: #1f2937;
  --text-dark: #f1f5f9;
  --text-secondary-light: #6b7280;
  --text-secondary-dark: #cbd5e1;
  --border-light: #e2e8f0;
  --border-dark: #334155;
  --shadow-light: 0 10px 40px rgba(0,0,0,0.08);
  --shadow-dark: 0 10px 40px rgba(0,0,0,0.5);
  --shadow-hover-light: 0 20px 60px rgba(0,0,0,0.12);
  --shadow-hover-dark: 0 20px 60px rgba(0,0,0,0.7);
}

body {
  background: var(--bg-light);
  font-family: system-ui, sans-serif;
  margin: 0;
  padding: 0;
  color: var(--text-light);
  transition: all 0.3s ease;
}

@media (prefers-color-scheme: dark) {
  body {
    background: var(--bg-dark);
    color: var(--text-dark);
  }
}

/* HERO SECTION */
.hero-section {
  text-align: center;
  padding: 3rem 2rem;
  border-radius: 20px;
  background: var(--card-light);
  box-shadow: var(--shadow-light);
  margin-bottom: 3rem;
  transition: all 0.3s ease;
}

@media (prefers-color-scheme: dark) {
  .hero-section {
    background: var(--card-dark);
    box-shadow: var(--shadow-dark);
  }
}

.hero-section h1 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
  color: var(--primary);
}

.hero-section p {
  font-size: 1.1rem;
  color: var(--text-secondary-light);
  max-width: 600px;
  margin: 0 auto;
}

@media (prefers-color-scheme: dark) {
  .hero-section p {
    color: var(--text-secondary-dark);
  }
}

/* CONTACT GRID */
.contact-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
  margin-bottom: 3rem;
}

.contact-card {
  background: var(--card-light);
  padding: 2rem 1.5rem;
  border-radius: 16px;
  border: 1px solid var(--border-light);
  text-align: center;
  transition: all 0.3s ease;
  position: relative;
}

@media (prefers-color-scheme: dark) {
  .contact-card {
    background: var(--card-dark);
    border: 1px solid var(--border-dark);
  }
}

.contact-card:hover {
  transform: translateY(-8px);
  box-shadow: var(--shadow-hover-light);
}

@media (prefers-color-scheme: dark) {
  .contact-card:hover {
    box-shadow: var(--shadow-hover-dark);
  }
}

.contact-icon {
  font-size: 2rem;
  width: 60px;
  height: 60px;
  border-radius: 12px;
  background: linear-gradient(135deg, var(--primary), var(--accent));
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 0 auto 1rem;
}

/* FORM */
.form-container {
  background: var(--card-light);
  padding: 2.5rem 2rem;
  border-radius: 20px;
  border: 1px solid var(--border-light);
  box-shadow: var(--shadow-light);
  transition: all 0.3s ease;
}

@media (prefers-color-scheme: dark) {
  .form-container {
    background: var(--card-dark);
    border: 1px solid var(--border-dark);
    box-shadow: var(--shadow-dark);
  }
}

.form-container h2 {
  text-align: center;
  margin-bottom: 1.5rem;
  color: var(--text-light);
}

@media (prefers-color-scheme: dark) {
  .form-container h2 { color: var(--text-dark); }
}

.form-group {
  position: relative;
  margin-bottom: 1.5rem;
}

.form-group input,
.form-group textarea {
  width: 100%;
  padding: 1rem 1rem;
  border: 2px solid var(--border-light);
  border-radius: 12px;
  font-size: 1rem;
  background: var(--bg-light);
  color: var(--text-light);
  transition: all 0.3s ease;
}

@media (prefers-color-scheme: dark) {
  .form-group input,
  .form-group textarea {
    background: var(--bg-dark);
    color: var(--text-dark);
    border: 2px solid var(--border-dark);
  }
}

.form-group input:focus,
.form-group textarea:focus {
  outline: none;
  border-color: var(--primary);
  box-shadow: 0 0 0 4px rgba(30,64,175,0.15);
}

.form-group label {
  position: absolute;
  top: 1rem;
  left: 1rem;
  font-size: 0.9rem;
  color: var(--text-secondary-light);
  pointer-events: none;
  transition: 0.3s ease all;
}

@media (prefers-color-scheme: dark) {
  .form-group label { color: var(--text-secondary-dark); }
}

.form-group input:focus + label,
.form-group input:valid + label,
.form-group textarea:focus + label,
.form-group textarea:valid + label {
  top: -0.5rem;
  left: 0.8rem;
  font-size: 0.75rem;
  color: var(--primary);
  background: var(--card-light);
  padding: 0 0.2rem;
}

@media (prefers-color-scheme: dark) {
  .form-group input:focus + label,
  .form-group input:valid + label,
  .form-group textarea:focus + label,
  .form-group textarea:valid + label {
    background: var(--card-dark);
  }
}

.submit-button {
  width: 100%;
  padding: 1rem;
  background: linear-gradient(135deg, var(--primary), var(--accent));
  color: white;
  font-size: 1rem;
  font-weight: 600;
  border: none;
  border-radius: 12px;
  cursor: pointer;
  transition: all 0.3s ease;
}

.submit-button:hover {
  transform: translateY(-2px);
  box-shadow: 0 15px 35px rgba(30,64,175,0.3);
}

/* RESPONSIVE */
@media (max-width: 768px) {
  .hero-section h1 { font-size: 2rem; }
  .contact-grid { grid-template-columns: 1fr; }
}
</style>

<div class="contact-wrapper">

  <div class="hero-section">
    <h1>📬 Let's Connect</h1>
    <p>Reach out for network engineering, DevOps automation, or cloud infrastructure projects.</p>
  </div>

  <div class="contact-grid">
    <div class="contact-card">
      <div class="contact-icon">📧</div>
      <h3>Email</h3>
      <a href="mailto:nyamburalucy678@gmail.com">nyamburalucy678@gmail.com</a>
    </div>

    <div class="contact-card">
      <div class="contact-icon">💻</div>
      <h3>GitHub</h3>
      <a href="https://github.com/lucianakenya/" target="_blank">lucianakenya</a>
    </div>

    <div class="contact-card">
      <div class="contact-icon">💼</div>
      <h3>LinkedIn</h3>
      <a href="https://www.linkedin.com/in/lucy-nyambura-5704a1232/" target="_blank">Lucy Nyambura</a>
    </div>

    <div class="contact-card">
      <div class="contact-icon">📱</div>
      <h3>Phone</h3>
      <p>+254 703 498 550</p>
    </div>
  </div>

  <div class="form-container">
    <h2>Send Message</h2>
    <form action="https://formspree.io/f/mykdjewk" method="POST">
      <div class="form-row" style="display: grid; grid-template-columns: 1fr 1fr; gap: 1rem;">
        <div class="form-group">
          <input type="text" id="name" name="name" required>
          <label for="name">Your Name</label>
        </div>
        <div class="form-group">
          <input type="email" id="email" name="_replyto" required>
          <label for="email">Your Email</label>
        </div>
      </div>
      <div class="form-group">
        <textarea id="message" name="message" required></textarea>
        <label for="message">Your Message</label>
      </div>
      <button type="submit" class="submit-button">Get In Touch</button>
    </form>
  </div>

</div>
