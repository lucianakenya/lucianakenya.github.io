---
layout: single
author_profile: true
title: "Lucy Nyambura | Network & Cloud Engineer"
permalink: /
description: "Network Engineer | DevOps | Cloud Infrastructure | Automation"
classes: wide
---

<style>
/* Minimal Landing - Hero Focus */
:root {
  --primary: #1e40af;
  --accent: #3b82f6;
  --bg: #f8fafc;
}

* { box-sizing: border-box; margin: 0; padding: 0; }

body {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
  background: var(--bg);
  color: #1f2937;
  line-height: 1.7;
  overflow-x: hidden;
}

/* Hero */
.hero {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 2rem;
  background: linear-gradient(135deg, #1e3a8a 0%, #3b82f6 50%, #1e40af 100%);
  color: white;
  position: relative;
  overflow: hidden;
}

.hero::before {
  content: '';
  position: absolute;
  inset: 0;
  background: 
    radial-gradient(circle at 25% 25%, rgba(255,255,255,0.15) 0%, transparent 40%),
    radial-gradient(circle at 75% 75%, rgba(255,255,255,0.1) 0%, transparent 40%);
}

.hero-content { 
  position: relative; 
  z-index: 1; 
  max-width: 800px;
  animation: fadeInUp 1s ease-out;
}

@keyframes fadeInUp {
  from { opacity: 0; transform: translateY(30px); }
  to { opacity: 1; transform: translateY(0); }
}

.hero h1 {
  font-size: clamp(2.8rem, 7vw, 5rem);
  font-weight: 800;
  margin-bottom: 1rem;
  letter-spacing: -0.025em;
  background: linear-gradient(135deg, white 0%, rgba(255,255,255,0.9) 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.hero-subtitle {
  font-size: clamp(1.3rem, 3.5vw, 2.2rem);
  font-weight: 300;
  margin-bottom: 1.5rem;
  opacity: 0.95;
  letter-spacing: 0.025em;
}

.hero-tagline {
  font-size: clamp(1.1rem, 2.5vw, 1.4rem);
  opacity: 0.85;
  max-width: 600px;
  margin: 0 auto 3.5rem;
  font-weight: 300;
}

/* CTA Buttons */
.cta-group {
  display: flex;
  gap: 1.5rem;
  justify-content: center;
  flex-wrap: wrap;
  margin-bottom: 2rem;
}

.cta-btn {
  padding: 1.2rem 2.8rem;
  border-radius: 50px;
  text-decoration: none;
  font-weight: 600;
  font-size: 1.1rem;
  transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
  border: 2px solid transparent;
  position: relative;
  overflow: hidden;
}

.cta-primary {
  background: rgba(255,255,255,0.95);
  color: var(--primary);
  box-shadow: 0 10px 40px rgba(255,255,255,0.4);
}

.cta-primary:hover {
  background: white;
  transform: translateY(-5px) scale(1.03);
  box-shadow: 0 25px 50px rgba(255,255,255,0.6);
}

.cta-secondary {
  background: transparent;
  color: rgba(255,255,255,0.95);
  backdrop-filter: blur(20px);
}

.cta-secondary:hover {
  background: rgba(255,255,255,0.2);
  transform: translateY(-4px);
}

/* Scroll Indicator */
.scroll-hint {
  position: absolute;
  bottom: 3rem;
  left: 50%;
  transform: translateX(-50%);
  animation: bounce 2s infinite;
}

.scroll-hint span {
  display: block;
  width: 2px;
  height: 40px;
  background: rgba(255,255,255,0.6);
  border-radius: 2px;
  animation: scrollPulse 2s infinite;
}

@keyframes bounce {
  0%, 20%, 50%, 80%, 100% { transform: translateX(-50%) translateY(0); }
  40% { transform: translateX(-50%) translateY(-10px); }
  60% { transform: translateX(-50%) translateY(-5px); }
}

@keyframes scrollPulse {
  0%, 100% { opacity: 0.6; transform: scaleY(1); }
  50% { opacity: 1; transform: scaleY(1.2); }
}

/* Quick Links */
.quick-links {
  position: absolute;
  top: 2rem;
  right: 2rem;
  display: flex;
  gap: 1rem;
}

.quick-link {
  color: rgba(255,255,255,0.8);
  text-decoration: none;
  font-size: 0.95rem;
  font-weight: 500;
  padding: 0.5rem 1rem;
  border-radius: 20px;
  backdrop-filter: blur(10px);
  transition: all 0.3s ease;
}

.quick-link:hover {
  color: white;
  background: rgba(255,255,255,0.15);
}

@media (max-width: 768px) {
  .quick-links { 
    position: static; 
    justify-content: center; 
    margin-top: 2rem; 
  }
  
  .cta-group { flex-direction: column; align-items: center; gap: 1rem; }
  
  .scroll-hint { display: none; }
}
</style>

<div class="hero">
  <div class="quick-links">
    <a href="/resume" class="quick-link">Resume</a>
    <a href="/projects" class="quick-link">Projects</a>
    <a href="/contact" class="quick-link">Contact</a>
  </div>
  
  <div class="hero-content">
    <h1>Lucy Nyambura</h1>
    <h2 class="hero-subtitle">Network Engineer • Cloud • DevOps</h2>
    <p class="hero-tagline">Automating ISP networks | Building secure cloud infrastructure | Delivering scalable solutions</p>
    
  <div class="cta-group">
    <a href="/projects" class="cta-btn cta-primary">See My Work</a>
    <a href="/contact" class="cta-btn cta-secondary">Let's Talk</a>
  </div>
  </div>
  
  <div class="scroll-hint">
    <span></span>
  </div>
</div>
