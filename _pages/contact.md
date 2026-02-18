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
  --bg: #f8fafc;
  --card: #ffffff;
  --text: #1f2937;
  --text-sub: #6b7280;
  --border: #e2e8f0;
  --shadow: 0 10px 40px rgba(0,0,0,0.08);
  --shadow-hover: 0 20px 60px rgba(0,0,0,0.12);
}

@media (prefers-color-scheme: dark) {
  :root {
    --bg: #0f172a;
    --card: #1e293b;
    --text: #f1f5f9;
    --text-sub: #cbd5e1;
    --border: #334155;
    --shadow: 0 10px 40px rgba(0,0,0,0.5);
    --shadow-hover: 0 20px 60px rgba(0,0,0,0.7);
  }
}

body {
  background: var(--bg);
  color: var(--text);
  font-family: system-ui, sans-serif;
  margin: 0;
}

/* ANIMATIONS */
@keyframes fadeUp {
  from { opacity: 0; transform: translateY(20px); }
  to   { opacity: 1; transform: translateY(0); }
}

.hero-section,
.contact-grid,
.form-container {
  animation: fadeUp 0.5s ease both;
}

.contact-grid { animation-delay: 0.1s; }
.form-container { animation-delay: 0.2s; }

/* HERO */
.hero-section {
  text-align: center;
  padding: 3rem 2rem;
  border-radius: 20px;
  background: var(--card);
  box-shadow: var(--shadow);
  margin-bottom: 3rem;
}

.hero-section h1 {
  font-size: 2.5rem;
  margin: 0 0 1rem;
  color: var(--primary);
}

.hero-section p {
  font-size: 1.1rem;
  color: var(--text-sub);
  max-width: 600px;
  margin: 0 auto;
}

/* GRID */
.contact-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 1.5rem;
  margin-bottom: 3rem;
}

.contact-card {
  background: var(--card);
  padding: 2rem 1.5rem;
  border-radius: 16px;
  border: 1px solid var(--border);
  text-align: center;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.contact-card:hover {
  transform: translateY(-6px);
  box-shadow: var(--shadow-hover);
}

.contact-card h3 { margin: 0.75rem 0 0.4rem; }

.contact-card a,
.contact-card p {
  color: var(--text-sub);
  font-size: 0.95rem;
  margin: 0;
  word-break: break-word;
}

.contact-card a:hover { color: var(--accent); }

.contact-icon {
  font-size: 1.5rem;
  width: 56px;
  height: 56px;
  border-radius: 12px;
  background: linear-gradient(135deg, var(--primary), var(--accent));
  color: #fff;
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 0 auto;
}

/* FORM */
.form-container {
  background: var(--card);
  padding: 2.5rem 2rem;
  border-radius: 20px;
  border: 1px solid var(--border);
  box-shadow: var(--shadow);
}

.form-container h2 {
  text-align: center;
  margin: 0 0 1.5rem;
  color: var(--text);
}

.form-row {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1rem;
}

.form-group {
  position: relative;
  margin-bottom: 1.5rem;
}

.form-group input,
.form-group textarea {
  width: 100%;
  padding: 1rem;
  border: 2px solid var(--border);
  border-radius: 12px;
  font-size: 1rem;
  background: var(--bg);
  color: var(--text);
  transition: border-color 0.25s ease, box-shadow 0.25s ease;
  box-sizing: border-box;
}

.form-group textarea {
  min-height: 140px;
  resize: vertical;
}

.form-group input:focus,
.form-group textarea:focus {
  outline: none;
  border-color: var(--primary);
  box-shadow: 0 0 0 4px rgba(30,64,175,0.12);
}

.form-group label {
  position: absolute;
  top: 1rem;
  left: 1rem;
  font-size: 0.9rem;
  color: var(--text-sub);
  pointer-events: none;
  transition: top 0.25s ease, font-size 0.25s ease, color 0.25s ease, background 0.25s ease;
}

.form-group input:focus + label,
.form-group input:not(:placeholder-shown) + label,
.form-group textarea:focus + label,
.form-group textarea:not(:placeholder-shown) + label {
  top: -0.55rem;
  left: 0.75rem;
  font-size: 0.72rem;
  color: var(--primary);
  background: var(--card);
  padding: 0 0.25rem;
}

.submit-button {
  width: 100%;
  padding: 1rem;
  background: linear-gradient(135deg, var(--primary), var(--accent));
  color: #fff;
  font-size: 1rem;
  font-weight: 600;
  border: none;
  border-radius: 12px;
  cursor: pointer;
  transition: transform 0.25s ease, box-shadow 0.25s ease;
}

.submit-button:hover {
  transform: translateY(-2px);
  box-shadow: 0 12px 30px rgba(30,64,175,0.3);
}

.submit-button:active { transform: translateY(0); }

/* RESPONSIVE */
@media (max-width: 640px) {
  .hero-section h1 { font-size: 1.9rem; }
  .form-row { grid-template-columns: 1fr; }
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
      <a href="https://github.com/lucianakenya/" target="_blank" rel="noopener">lucianakenya</a>
    </div>
    <div class="contact-card">
      <div class="contact-icon">💼</div>
      <h3>LinkedIn</h3>
      <a href="https://www.linkedin.com/in/lucy-nyambura-5704a1232/" target="_blank" rel="noopener">Lucy Nyambura</a>
    </div>
    <div class="contact-card">
      <div class="contact-icon">📱</div>
      <h3>Phone</h3>
      <p>+254 703 498 550</p>
    </div>
  </div>

  <div class="form-container">
    <h2>Send a Message</h2>
    <form action="https://formspree.io/f/mykdjewk" method="POST">
      <div class="form-row">
        <div class="form-group">
          <input type="text" id="name" name="name" placeholder=" " required>
          <label for="name">Your Name</label>
        </div>
        <div class="form-group">
          <input type="email" id="email" name="_replyto" placeholder=" " required>
          <label for="email">Your Email</label>
        </div>
      </div>
      <div class="form-group">
        <textarea id="message" name="message" placeholder=" " required></textarea>
        <label for="message">Your Message</label>
      </div>
      <button type="submit" class="submit-button">Get In Touch</button>
    </form>
  </div>

</div>
