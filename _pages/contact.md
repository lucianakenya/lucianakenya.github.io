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
  --primary-dark: #1e3a8a;
  --accent: #3b82f6;
  --bg-light: #f8fafc;
  --card-bg: #ffffff;
  --text-primary: #1f2937;
  --text-secondary: #6b7280;
  --border: #e2e8f0;
  --shadow: 0 10px 40px rgba(0,0,0,0.08);
  --shadow-hover: 0 20px 60px rgba(0,0,0,0.12);
}

.contact-wrapper {
  max-width: 900px;
  margin: 0 auto;
  padding: 2rem 1rem;
}

.hero-section {
  text-align: center;
  padding: 4rem 2rem;
  background: linear-gradient(135deg, var(--primary) 0%, var(--accent) 100%);
  border-radius: 24px;
  color: white;
  margin-bottom: 4rem;
  position: relative;
  overflow: hidden;
}

.hero-section::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%23ffffff' fill-opacity='0.05'%3E%3Ccircle cx='30' cy='30' r='2'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
  pointer-events: none;
}

.hero-section h1 {
  font-size: 2.8rem;
  font-weight: 700;
  margin-bottom: 1rem;
  position: relative;
  z-index: 1;
}

.hero-section p {
  font-size: 1.2rem;
  opacity: 0.95;
  max-width: 600px;
  margin: 0 auto;
  position: relative;
  z-index: 1;
}

.contact-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin-bottom: 4rem;
}

.contact-card {
  background: var(--card-bg);
  padding: 2.5rem 2rem;
  border-radius: 20px;
  border: 1px solid var(--border);
  text-align: center;
  transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
  position: relative;
  overflow: hidden;
}

.contact-card::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  height: 4px;
  background: linear-gradient(90deg, var(--primary), var(--accent));
  transform: scaleX(0);
  transition: transform 0.4s ease;
}

.contact-card:hover {
  transform: translateY(-12px);
  box-shadow: var(--shadow-hover);
  border-color: var(--accent);
}

.contact-card:hover::before {
  transform: scaleX(1);
}

.contact-icon {
  width: 80px;
  height: 80px;
  border-radius: 20px;
  background: linear-gradient(135deg, var(--primary), var(--accent));
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 0 auto 1.5rem;
  font-size: 2rem;
  color: white;
  box-shadow: 0 8px 25px rgba(30, 64, 175, 0.3);
  transition: transform 0.3s ease;
}

.contact-card:hover .contact-icon {
  transform: scale(1.05) rotate(5deg);
}

.contact-card h3 {
  font-size: 1.4rem;
  color: var(--text-primary);
  margin-bottom: 1rem;
  font-weight: 600;
}

.contact-card a,
.contact-card p {
  font-size: 1.1rem;
  color: var(--text-secondary);
  text-decoration: none;
  display: block;
  font-weight: 500;
  transition: color 0.3s ease;
}

.contact-card a:hover {
  color: var(--primary);
}

.form-container {
  background: var(--card-bg);
  padding: 3rem;
  border-radius: 24px;
  border: 1px solid var(--border);
  box-shadow: var(--shadow);
  position: relative;
}

.form-container::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  height: 4px;
  background: linear-gradient(90deg, var(--primary), var(--accent));
}

.form-container h2 {
  text-align: center;
  color: var(--text-primary);
  margin-bottom: 2rem;
  font-size: 1.7rem;
  font-weight: 600;
}

.form-row {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1.5rem;
  margin-bottom: 1.5rem;
}

.form-group {
  position: relative;
}

.form-group label {
  position: absolute;
  top: 1rem;
  left: 1.2rem;
  color: var(--text-secondary);
  font-weight: 500;
  font-size: 0.95rem;
  transition: all 0.3s ease;
  pointer-events: none;
}

.form-group input:focus + label,
.form-group input:valid + label,
.form-group textarea:focus + label,
.form-group textarea:valid + label {
  top: -0.5rem;
  left: 0.8rem;
  font-size: 0.8rem;
  color: var(--primary);
  background: var(--card-bg);
  padding: 0 0.3rem;
}

.form-group input,
.form-group textarea {
  width: 100%;
  padding: 1.2rem 1.2rem 1rem;
  border: 2px solid var(--border);
  border-radius: 14px;
  font-size: 1rem;
  background: var(--bg-light);
  transition: all 0.3s ease;
  font-family: inherit;
}

.form-group input:focus,
.form-group textarea:focus {
  outline: none;
  border-color: var(--primary);
  background: white;
  box-shadow: 0 0 0 4px rgba(30, 64, 175, 0.1);
}

.form-group textarea {
  resize: vertical;
  min-height: 140px;
}

.submit-button {
  background: linear-gradient(135deg, var(--primary), var(--accent));
  color: white;
  padding: 1.2rem 3rem;
  border: none;
  border-radius: 14px;
  font-size: 1.1rem;
  font-weight: 600;
  cursor: pointer;
  width: 100%;
  transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
  text-transform: uppercase;
  letter-spacing: 0.5px;
  position: relative;
  overflow: hidden;
}

.submit-button:hover {
  transform: translateY(-3px);
  box-shadow: 0 15px 35px rgba(30, 64, 175, 0.4);
}

.submit-button:active {
  transform: translateY(-1px);
}

@media (max-width: 768px) {
  .hero-section {
    margin: 0 -1rem 3rem;
    border-radius: 20px 20px 0 0;
    padding: 3rem 1.5rem;
  }
  
  .hero-section h1 { font-size: 2.3rem; }
  
  .form-row {
    grid-template-columns: 1fr;
    gap: 1rem;
  }
  
  .contact-grid {
    grid-template-columns: 1fr;
    gap: 1.5rem;
  }
  
  .form-container,
  .contact-card {
    padding: 2rem 1.5rem;
  }
}
</style>

<div class="contact-wrapper">
  
  <div class="hero-section">
    <h1>📬 Let's Connect</h1>
    <p>Reach out for network engineering, DevOps automation, or cloud infrastructure projects</p>
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
      <div class="form-row">
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
    <textarea id="message" name="message" required placeholder=" "></textarea>
    <label for="message">Your Message</label>
  </div>
  
  <button type="submit" class="submit-button">Get In Touch</button>
</form>
  </div>

</div>
