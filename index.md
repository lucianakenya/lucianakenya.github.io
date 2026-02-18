---
layout: single
author_profile: true
title: "Network Engineer | DevOps | Cloud Infrastructure | Automation"
permalink: /
description: "Network Engineer | DevOps | Cloud Infrastructure | Automation"
classes: wide
---

<style>
:root {
  --primary: #3b82f6;
  --accent: #60a5fa;
  --bg: #0f172a;
  --text: #f8fafc;
  --text-muted: rgba(248,250,252,0.7);
}

*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

body {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
  background: var(--bg);
  color: var(--text);
  line-height: 1.7;
  overflow-x: hidden;
}

/* HERO */
.hero {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 2rem;
  position: relative;
  overflow: hidden;
  background: linear-gradient(135deg, #1e293b 0%, #0f172a 100%);
}

/* Subtle ambient glow */
.hero::before,
.hero::after {
  content: '';
  position: absolute;
  border-radius: 50%;
  pointer-events: none;
  z-index: 0;
}

.hero::before {
  width: 600px;
  height: 600px;
  top: -100px;
  left: -150px;
  background: radial-gradient(circle, rgba(59,130,246,0.08) 0%, transparent 70%);
}

.hero::after {
  width: 500px;
  height: 500px;
  bottom: -80px;
  right: -100px;
  background: radial-gradient(circle, rgba(96,165,250,0.06) 0%, transparent 70%);
}

/* CONTENT */
.hero-content {
  position: relative;
  z-index: 1;
  max-width: 780px;
  animation: fadeInUp 0.9s ease-out both;
}

@keyframes fadeInUp {
  from { opacity: 0; transform: translateY(28px); }
  to   { opacity: 1; transform: translateY(0); }
}

.hero-eyebrow {
  display: inline-block;
  font-size: 0.8rem;
  font-weight: 600;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  color: var(--accent);
  margin-bottom: 1.25rem;
  opacity: 0;
  animation: fadeInUp 0.9s 0.15s ease-out forwards;
}

.hero h1 {
  font-size: clamp(2.6rem, 7vw, 4rem);
  font-weight: 800;
  line-height: 1.1;
  letter-spacing: -0.03em;
  margin-bottom: 1.25rem;
  background: linear-gradient(135deg, var(--text) 30%, var(--accent));
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  opacity: 0;
  animation: fadeInUp 0.9s 0.25s ease-out forwards;
}

.hero-text {
  font-size: clamp(1rem, 2.2vw, 1.15rem);
  color: var(--text-muted);
  font-weight: 300;
  max-width: 640px;
  margin: 0 auto 2.5rem;
  opacity: 0;
  animation: fadeInUp 0.9s 0.35s ease-out forwards;
}

/* STATS ROW */
.hero-stats {
  display: flex;
  gap: 2.5rem;
  justify-content: center;
  margin-bottom: 2.5rem;
  opacity: 0;
  animation: fadeInUp 0.9s 0.45s ease-out forwards;
}

.stat { text-align: center; }

.stat-number {
  display: block;
  font-size: 1.6rem;
  font-weight: 700;
  color: var(--accent);
  line-height: 1;
}

.stat-label {
  font-size: 0.75rem;
  color: var(--text-muted);
  text-transform: uppercase;
  letter-spacing: 0.1em;
  margin-top: 0.25rem;
}

/* CTA BUTTONS */
.cta-group {
  display: flex;
  gap: 1rem;
  justify-content: center;
  flex-wrap: wrap;
  opacity: 0;
  animation: fadeInUp 0.9s 0.55s ease-out forwards;
}

.cta-btn {
  padding: 0.85rem 2.2rem;
  border-radius: 50px;
  text-decoration: none;
  font-weight: 600;
  font-size: 0.95rem;
  transition: transform 0.25s ease, box-shadow 0.25s ease, background 0.25s ease;
  border: 2px solid transparent;
}

.cta-primary {
  background: var(--primary);
  color: var(--text);
  box-shadow: 0 8px 24px rgba(59,130,246,0.35);
}

.cta-primary:hover {
  transform: translateY(-3px);
  box-shadow: 0 16px 40px rgba(59,130,246,0.55);
}

.cta-secondary {
  color: var(--primary);
  border-color: var(--primary);
}

.cta-secondary:hover {
  background: rgba(59,130,246,0.12);
  transform: translateY(-3px);
}

/* SCROLL HINT */
.scroll-hint {
  position: absolute;
  bottom: 2rem;
  left: 50%;
  transform: translateX(-50%);
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 0.4rem;
  opacity: 0;
  animation: fadeInUp 1s 1s ease-out forwards;
}

.scroll-hint span {
  display: block;
  width: 1.5px;
  height: 36px;
  background: linear-gradient(to bottom, transparent, var(--text-muted));
  border-radius: 2px;
  animation: scrollPulse 2s 1.2s infinite;
}

@keyframes scrollPulse {
  0%, 100% { opacity: 0.4; transform: scaleY(1); }
  50%       { opacity: 0.9; transform: scaleY(1.15); }
}

/* RESPONSIVE */
@media (max-width: 640px) {
  .hero-stats { gap: 1.5rem; }
  .cta-group  { flex-direction: column; align-items: center; }
  .scroll-hint { display: none; }
}
</style>

<div class="hero">
  <div class="hero-content">


<span class="hero-eyebrow">Network Engineer &amp; Cloud Solutions</span>

<h1>Lucy Nyambura</h1>

<p class="hero-text">
  4+ years designing, securing, and optimizing enterprise networks. Expert in Cisco/Junos routing, 
  automation, and cloud infrastructure—cut downtime 47% through proactive optimizations. 
  Building robust hybrid and on-prem solutions with precision and agility.
</p>

<div class="hero-stats">
  <div class="stat">
    <span class="stat-number">4+</span>
    <span class="stat-label">Years Experience</span>
  </div>
  <div class="stat">
    <span class="stat-number">47%</span>
    <span class="stat-label">Downtime Reduced</span>
  </div>
  <div class="stat">
    <span class="stat-number">3</span>
    <span class="stat-label">Cloud Platforms</span>
  </div>
</div>

<div class="cta-group">
  <a href="/projects" class="cta-btn cta-primary">See My Work</a>
  <a href="/contact"  class="cta-btn cta-secondary">Let's Talk</a>
</div>

  </div>

  <div class="scroll-hint"><span></span></div>
</div>
