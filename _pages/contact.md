---
title: "Contact Me"
layout: single
permalink: /contact/
author_profile: true
classes: wide
---

<div class="contact-container">

  <h1>📬 Contact Me</h1>
  <p>I’d love to hear from you! Whether you have a question, a project idea, or want to collaborate, feel free to reach out.</p>

  <section class="contact-section">
    <h2>📧 Email</h2>
    <p><a href="mailto:nyamburalucy678@gmail.com">nyamburalucy678@gmail.com</a></p>
  </section>

  <section class="contact-section">
    <h2>🔗 LinkedIn</h2>
    <p><a href="https://www.linkedin.com/in/lucy-nyambura-5704a1232/" target="_blank">Lucy Nyambura</a></p>
  </section>

  <section class="contact-section">
    <h2>💻 GitHub</h2>
    <p><a href="https://github.com/lucianakenya/" target="_blank">github.com/lucianakenya</a></p>
  </section>

  <section class="contact-section">
    <h2>📝 Send a Message</h2>
    <form action="https://formspree.io/f/mykdjewk" method="POST" class="contact-form">
      <label for="name">Your Name:</label><br>
      <input type="text" id="name" name="name" required><br><br>

  <label for="email">Your Email:</label><br>
  <input type="email" id="email" name="_replyto" required><br><br>

  <label for="message">Message:</label><br>
  <textarea id="message" name="message" rows="5" required></textarea><br><br>

  <button type="submit">Send</button>
</form>
  </section>

</div>

<style>
/* Container styling */
.contact-container {
  max-width: 900px;
  margin: 2rem auto;
  padding: 1.5rem 2rem;
  background-color: #fdfdfd;
  border-radius: 10px;
  box-shadow: 0 6px 15px rgba(0,0,0,0.05);
}

/* Section spacing */
.contact-section {
  margin-top: 2rem;
}

/* Section headers */
.contact-section h2 {
  font-size: 1.4em;
  color: #007acc;
  margin-bottom: 0.5rem;
}

/* Links */
.contact-section a {
  color: #007acc;
  text-decoration: none;
}

.contact-section a:hover {
  text-decoration: underline;
}

/* Form styling */
.contact-form input,
.contact-form textarea {
  width: 100%;
  max-width: 600px;
  padding: 0.6rem 0.8rem;
  border: 1px solid #ccc;
  border-radius: 6px;
  margin-top: 0.3rem;
  font-size: 1em;
  color: #333;
  background-color: #f9f9f9;
  transition: border-color 0.2s ease, box-shadow 0.2s ease;
}

.contact-form input:focus,
.contact-form textarea:focus {
  outline: none;
  border-color: #007acc;
  box-shadow: 0 0 5px rgba(0, 122, 204, 0.3);
  background-color: #fff;
}

.contact-form button {
  background-color: #007acc;
  color: #fff;
  padding: 0.6rem 1.2rem;
  border: none;
  border-radius: 5px;
  font-size: 1em;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.contact-form button:hover {
  background-color: #005f99;
}

.contact-form label {
  font-weight: 600;
}

/* Responsive */
@media (max-width: 768px) {
  .contact-container {
    padding: 1rem 1.2rem;
  }
}
</style>
