---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

<style>
.hero-banner {
  position: relative;
  height: 300px;
  overflow: hidden;
  border-radius: 14px;
  margin: 0.4em 0 1.6em 0;
  background: #fafafa;
  border: 1px solid #eee;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.04);
  container-type: inline-size;
  animation: hero-fade-in 0.9s ease both;
}
.hero-banner__bg {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: center 55%;
  opacity: 0.22;
  pointer-events: none;
  user-select: none;
}
.hero-banner__overlay {
  position: absolute;
  inset: 0;
  background: linear-gradient(180deg, rgba(255,255,255,0.5) 0%, rgba(255,255,255,0.12) 45%, rgba(255,255,255,0.5) 100%);
  pointer-events: none;
}
.hero-banner__line {
  position: absolute;
  inset: 0;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  white-space: nowrap;
  margin: 0;
  padding: 0 1.5%;
  font-family: Georgia, 'Times New Roman', serif;
  font-style: italic;
  letter-spacing: 0.01em;
  color: #333;
  opacity: 0;
  animation: hero-switch 16s ease-in-out infinite;
}
.hero-banner__line--1 { font-size: 21px; }
.hero-banner__line--2 { font-size: 12px; animation-delay: -8s; }
@supports (container-type: inline-size) {
  .hero-banner__line--1 { font-size: 2.3cqw; }
  .hero-banner__line--2 { font-size: 1.1cqw; }
}
.hero-banner:hover .hero-banner__line {
  animation-play-state: paused;
}
@keyframes hero-switch {
  0%   { opacity: 0; transform: translateY(12px); }
  4%   { opacity: 1; transform: translateY(0); }
  46%  { opacity: 1; transform: translateY(0); }
  50%  { opacity: 0; transform: translateY(-12px); }
  100% { opacity: 0; transform: translateY(-12px); }
}
@keyframes hero-fade-in {
  from { opacity: 0; transform: translateY(10px); }
  to   { opacity: 1; transform: translateY(0); }
}
@media (max-width: 768px) {
  .hero-banner { height: 200px; }
  .hero-banner__line { white-space: normal; padding: 0 14px; }
  .hero-banner__line--1 { font-size: 15px; }
  .hero-banner__line--2 { font-size: 11.5px; }
}
@media (prefers-reduced-motion: reduce) {
  .hero-banner { animation: none; }
  .hero-banner__line { animation: none; position: static; transform: none; white-space: normal; padding: 6px 14px; }
  .hero-banner__line--1 { opacity: 1; }
  .hero-banner__line--2 { opacity: 1; }
}
[data-theme="dark"] .hero-banner {
  background: #1a1a1a;
  border-color: #333;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.4);
}
[data-theme="dark"] .hero-banner__bg { opacity: 0.14; }
[data-theme="dark"] .hero-banner__overlay {
  background: linear-gradient(180deg, rgba(20,20,20,0.55) 0%, rgba(20,20,20,0.2) 45%, rgba(20,20,20,0.55) 100%);
}
[data-theme="dark"] .hero-banner__line { color: #e5e5e5; }
</style>

<div class="hero-banner" role="note" aria-label="Welcome to my homepage! I'm a 28fall undergraduate majoring in Automation. Early in college, I focused on dynamic planning and statistical machine learning, and was exposed to 3D vision in Jun. 2025 and multi-modal methods in Nov. 2025.">
  <img class="hero-banner__bg" src="{{ '/images/banner-cat.jpg' | relative_url }}" alt="" aria-hidden="true" loading="eager">
  <div class="hero-banner__overlay"></div>
  <p class="hero-banner__line hero-banner__line--1" aria-hidden="true">Welcome to my homepage! I'm a 28fall undergraduate majoring in Automation.</p>
  <p class="hero-banner__line hero-banner__line--2" aria-hidden="true">Early in college, I focused on dynamic planning and statistical machine learning, and was exposed to 3D vision in Jun. 2025 and multi-modal methods in Nov. 2025.</p>
</div>

{% include_relative section/intro.md %}

{% include_relative section/interests.md %}

{% include_relative section/vision.md %}

{% include_relative section/news.md %}

{% include_relative section/publications.md %}

{% include_relative section/awards.md %}

{% include_relative section/_skills.md %}

# Contact
- **Email**: [huanhuanli104@gmail.com](mailto:huanhuanli104@gmail.com)

---

<div style="text-align: center; color: #666; font-size: 0.9em; margin-top: 2em; border-top: 1px solid #eee; padding-top: 1em;">
<em>Last updated: Aug. 2026</em>
</div>
