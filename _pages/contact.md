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
  --bg-page: #f8fafc;
  --card-bg: #ffffff;
  --text-primary: #1f2937;
  --text-secondary: #6b7280;
  --border: #e2e8f0;
  --shadow: 0 10px 40px rgba(0,0,0,0.08);
  --shadow-hover: 0 20px 60px rgba(0,0,0,0.12);
}

body {
  background: var(--bg-page);
  font-family: system-ui, sans-serif;
  margin: 0;
  padding: 0;
}

/* HERO SECTION */
.hero-section {
  text-align: center;
  padding: 3rem 2rem;
  border-radius: 20px;
  background: var(--card-bg);
  box-shadow: var(--shadow);
  margin-bottom: 3rem;
}

.hero-section h1 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
  color: var(--primary);
}

.hero-section p {
  font-size: 1.1rem;
  color: var(--text-secondary);
  max-width: 600px;
  margin: 0 auto;
}

/* CONTACT GRID */
.contact-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
  margin-bottom: 3rem;
}

.contact-card {
  background: var(--card-bg);
  padding: 2rem 1.5rem;
  border-radius: 16px;
  border: 1px solid var(--border);
  text-align: center;
  transition: all 0.3s ease;
  position: relative;
}

.contact-card:hover {
  transform: translateY(-8px);
  box-shadow: var(--shadow-hover);
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
  background: var(--card-bg);
  padding: 2.5rem 2rem;
  border-radius: 20px;
  border: 1px solid var(--border);
  box-shadow: var(--shadow);
}

.form-container h2 {
  text-align: center;
  margin-bottom: 1.5rem;
  color: var(--text-primary);
}

.form-group {
  position: relative;
  margin-bottom: 1.5rem;
}

.form-group input,
.form-group textarea {
  width: 100%;
  padding: 1rem 1rem;
  border: 2px solid var(--border);
  border-radius: 12px;
  font-size: 1rem;
  background: var(--bg-page);
}

.form-group input:focus,
.form-group textarea:focus {
  outline: none;
  border-color: var(--primary);
}

.form-group label {
  position: absolute;
  top: 1rem;
  left: 1rem;
  font-size: 0.9rem;
  color: var(--text-secondary);
  pointer-events: none;
  transition: 0.3s ease all;
}

.form-group input:focus + label,
.form-group input:valid + label,
.form-group textarea:focus + label,
.form-group textarea:valid + label {
  top: -0.5rem;
  left: 0.8rem;
  font-size: 0.75rem;
  color: var(--primary);
  background: var(--card-bg);
  padding: 0 0.2rem;
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
  transition: 0.3s ease all;
}

.submit-button:hover {
  transform: translateY(-2px);
  box-shadow: var(--shadow-hover);
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
