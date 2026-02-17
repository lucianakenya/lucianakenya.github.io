---
layout: single
author_profile: true
title: "Lucy Nyambura | Network & Cloud Engineer"
permalink: /
description: "Network Engineer | DevOps | Cloud Infrastructure | Automation"
classes: wide
---

<style>
:root {
  --primary: #3b82f6;
  --accent: #60a5fa;
  --bg: #0f172a;
  --text-light: #f8fafc;
  --text-muted: rgba(248,250,252,0.7);
}

* { box-sizing: border-box; margin: 0; padding: 0; }

body {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
  background: var(--bg);
  color: var(--text-light);
  line-height: 1.7;
  overflow-x: hidden;
}

/* Hero / About Me */
.hero {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 2rem;
  background: linear-gradient(135deg, #1e293b 0%, #0f172a 100%);
  position: relative;
  overflow: hidden;
}

.hero::before {
  content: '';
  position: absolute;
  inset: 0;
  background: 
    radial-gradient(circle at 20% 30%, rgba(255,255,255,0.05) 0%, transparent 50%),
    radial-gradient(circle at 80% 70%, rgba(255,255,255,0.03) 0%, transparent 50%);
  z-index: 0;
}

.hero-content { 
  position: relative; 
  z-index: 1; 
  max-width: 750px;
  animation: fadeInUp 1s ease-out;
}

@keyframes fadeInUp {
  from { opacity: 0; transform: translateY(30px); }
  to { opacity: 1; transform: translateY(0); }
}

.hero h1 {
  font-size: clamp(2.8rem, 7vw, 4rem);
  font-weight: 800;
  margin-bottom: 1rem;
  letter-spacing: -0.025em;
  background: linear-gradient(135deg, var(--primary), var(--accent));
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.hero-text {
  font-size: clamp(1.1rem, 2.5vw, 1.4rem);
  opacity: 0.85;
  margin-bottom: 3rem;
  font-weight: 300;
  color: var(--text-muted);
}

/* CTA Buttons */
.cta-group {
  display: flex;
  gap: 1.5rem;
  justify-content: center;
  flex-wrap: wrap;
}

.cta-btn {
  padding: 1rem 2.5rem;
  border-radius: 50px;
  text-decoration: none;
  font-weight: 600;
  font-size: 1rem;
  transition: all 0.3s ease;
  border: 2px solid transparent;
  position: relative;
  overflow: hidden;
}

.cta-primary {
  background: var(--primary);
  color: var(--text-light);
  box-shadow: 0 10px 30px rgba(59,130,246,0.4);
}

.cta-primary:hover {
  transform: translateY(-4px) scale(1.05);
  box-shadow: 0 20px 50px rgba(59,130,246,0.6);
}

.cta-secondary {
  background: transparent;
  color: var(--primary);
  border: 2px solid var(--primary);
}

.cta-secondary:hover {
  background: rgba(59,130,246,0.15);
  transform: translateY(-3px);
}

/* Scroll Hint */
.scroll-hint {
  position: absolute;
  bottom: 2.5rem;
  left: 50%;
  transform: translateX(-50%);
  animation: bounce 2s infinite;
}

.scroll-hint span {
  display: block;
  width: 2px;
  height: 40px;
  background: var(--text-muted);
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
  color: var(--text-muted);
  text-decoration: none;
  font-size: 0.95rem;
  font-weight: 500;
  padding: 0.5rem 1rem;
  border-radius: 20px;
  backdrop-filter: blur(10px);
  transition: all 0.3s ease;
}

.quick-link:hover {
  color: var(--text-light);
  background: rgba(255,255,255,0.1);
}

/* Responsive */
@media (max-width: 768px) {
  .quick-links { 
    position: static; 
    justify-content: center; 
    margin-top: 1.5rem; 
  }
  
  .cta-group { flex-direction: column; align-items: center; gap: 1rem; }
  .scroll-hint { display: none; }
}
</style>
  
  <div class="hero-content">
    <h3>Hi, I'm Lucy</h3>
    <p class="hero-text">
      I am a Network Engineer with over 4 years of experience designing, securing, and optimizing enterprise infrastructure. Specializing in Cisco and Junos routing platforms, network automation, and cloud computing, I have a proven track record of reducing downtime by 47% through proactive network optimization. My expertise covers a broad range of tools, scripting languages, and automation frameworks to deliver resilient, high-performance network solutions tailored for hybrid cloud and on-premises environments. From provisioning Optical Network Terminals (ONTs) and configuring complex cloud networks to restoring service reliability, I approach each challenge with precision, adaptability, and a focus on operational excellence.

My expertise spans tooling, scripting, and automation to deliver resilient, high-performance network solutions across hybrid environments. Whether it's provisioning ONTs, configuring cloud networks, or restoring service reliability, I bring precision and adaptability to every challenge.
    </p>
    
  <div class="cta-group">
    <a href="/projects" class="cta-btn cta-primary">See My Work</a>
    <a href="/contact" class="cta-btn cta-secondary">Let's Talk</a>
  </div>
  </div>
  
  <div class="scroll-hint">
    <span></span>
  </div>
</div>
