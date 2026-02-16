---
title: "Contact Me"
layout: single
permalink: /contact/
author_profile: true
classes: wide
---

<style>
/* Contact Page Styles */
.contact-hero {
  text-align: center;
  padding: 4rem 1rem 3rem;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  margin: -2rem -2rem 3rem -2rem;
}

.contact-hero h1 {
  font-size: 2.8rem;
  margin-bottom: 0.5rem;
  font-weight: 700;
}

.contact-hero p {
  font-size: 1.2rem;
  opacity: 0.95;
  max-width: 600px;
  margin: 0 auto;
}

.contact-main {
  max-width: 900px;
  margin: 0 auto 4rem;
  padding: 0 1rem;
}

.contact-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 2rem;
  margin: 3rem 0;
}

.contact-card {
  background: #fff;
  padding: 2rem;
  border-radius: 16px;
  box-shadow: 0 8px 25px rgba(0,0,0,0.08);
  border: 1px solid rgba(0,122,204,0.1);
  text-align: center;
  transition: all 0.3s ease;
  height: 100%;
}

.contact-card:hover {
  transform: translateY(-6px);
  box-shadow: 0 16px 40px rgba(0,0,0,0.12);
  border-color: #007acc;
}

.contact-icon {
  font-size: 3rem;
  margin-bottom: 1rem;
  display: block;
}

.contact-card h3 {
  color: #222;
  font-size: 1.3rem;
  margin-bottom: 1rem;
  font-weight: 600;
}

.contact-card a {
  color: #007acc;
  text-decoration: none;
  font-weight: 500;
  font-size: 1.1rem;
  display: block;
  padding: 0.5rem 0;
  transition: color 0.3s ease;
}

.contact-card a:hover {
  color: #005f99;
}

.contact-form-container {
  background: #fff;
  padding: 2.5rem;
  border-radius: 16px;
  box-shadow: 0 8px 25px rgba(0,0,0,0.08);
  border: 1px solid rgba(0,122,204,0.1);
  margin: 2rem 0;
}

.contact-form-container h2 {
  text-align: center;
  color: #222;
  margin-bottom: 2rem;
  font-size: 1.6rem;
}

.form-group {
  margin-bottom: 1.5rem;
}

.form-group label {
  display: block;
  margin-bottom: 0.5rem;
  font-weight: 600;
  color: #333;
  font-size: 0.95rem;
}

.form-group input,
.form-group textarea {
  width: 100%;
  padding: 1rem 1.2rem;
  border: 2px solid #e1e5e9;
  border-radius: 10px;
  font-size: 1rem;
  background: #f8fafc;
  transition: all 0.3s ease;
  font-family: inherit;
}

.form-group input:focus,
.form-group textarea:focus {
  outline: none;
  border-color: #007acc;
  background: #fff;
  box-shadow: 0 0 0 3px rgba(0,122,204,0.1);
}

.form-group textarea {
  resize: vertical;
  min-height: 120px;
}

.submit-btn {
  background: linear-gradient(135deg, #007acc, #005f99);
  color: white;
  padding: 1rem 2.5rem;
  border: none;
  border-radius: 10px;
  font-size: 1.1rem;
  font-weight: 600;
  cursor: pointer;
  width: 100%;
  transition: all 0.3s ease;
  text-transform: uppercase;
  letter-spacing: 0.5px;
}

.submit-btn:hover {
  transform: translateY(-2px);
  box-shadow: 0 10px 25px rgba(0,122,204,0.3);
}

.submit-btn:active {
  transform: translateY(0);
}

.success-message,
.error-message {
  padding: 1rem;
  border-radius: 10px;
  margin: 1rem 0;
  text-align: center;
  font-weight: 500;
}

.success-message {
  background: #d4edda;
  color: #155724;
  border: 1px solid #c3e6cb;
}

.error-message {
  background: #f8d7da;
  color: #721c24;
  border: 1px solid #f5c6cb;
}

/* Responsive */
@media (max-width: 768px) {
  .contact-hero {
    margin: -1rem -1rem 2rem -1rem;
    padding: 2.5rem 1rem;
  }
  
  .contact-hero h1 { font-size: 2.2rem; }
  
  .contact-card,
  .contact-form-container {
    padding: 1.5rem;
  }
  
  .contact-grid { gap: 1.5rem; }
}
</style>

<div class="contact-hero">
  <h1>📬 Let's Connect</h1>
  <p>Whether you have a project idea, need network expertise, or want to collaborate on cloud infrastructure, I'm here to help.</p>
</div>

<div class="contact-main">
  <div class="contact-grid">
    <div class="contact-card">
      <span class="contact-icon">📧</span>
      <h3>Email</h3>
      <a href="mailto:nyamburalucy678@gmail.com">nyamburalucy678@gmail.com</a>
    </div>

  <div class="contact-card">
    <span class="contact-icon">💻</span>
    <h3>GitHub</h3>
    <a href="https://github.com/lucianakenya/" target="_blank">github.com/lucianakenya</a>
  </div>

  <div class="contact-card">
    <span class="contact-icon">💼</span>
    <h3>LinkedIn</h3>
    <a href="https://www.linkedin.com/in/lucy-nyambura-5704a1232/" target="_blank">Lucy Nyambura</a>
  </div>

  <div class="contact-card">
    <span class="contact-icon">📱</span>
    <h3>Phone</h3>
    <p>+254 703 498 550</p>
  </div>
  </div>

  <div class="contact-form-container">
    <h2>📝 Send Message</h2>
    <form action="https://formspree.io/f/mykdjewk" method="POST" class="contact-form">
      <div class="form-group">
        <label for="name">Your Name</label>
        <input type="text" id="name" name="name" required>
      </div>

  <div class="form-group">
    <label for="email">Your Email</label>
    <input type="email" id="email" name="_replyto" required>
  </div>

  <div class="form-group">
    <label for="message">Your Message</label>
    <textarea id="message" name="message" placeholder="Tell me about your project or question..." required></textarea>
  </div>

  <button type="submit" class="submit-btn">Send Message</button>
</form>
  </div>
</div>
