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
  height: 210px;
  overflow: hidden;
  border-radius: 14px;
  margin: 0.4em 0 1.6em 0;
  background: #fafafa;
  border: 1px solid #eee;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.04);
  animation: hero-fade-in 0.9s ease both;
}
.hero-banner__bg {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: center 38%;
  opacity: 0.22;
  pointer-events: none;
  user-select: none;
}
.hero-banner__overlay {
  position: absolute;
  inset: 0;
  background: linear-gradient(180deg, rgba(255,255,255,0.55) 0%, rgba(255,255,255,0.15) 45%, rgba(255,255,255,0.55) 100%);
  pointer-events: none;
}
.hero-banner__marquee {
  position: absolute;
  inset: 0;
  display: flex;
  align-items: center;
  overflow: hidden;
}
.hero-banner__track {
  display: inline-flex;
  white-space: nowrap;
  will-change: transform;
  animation: hero-marquee 42s linear infinite;
}
.hero-banner__marquee:hover .hero-banner__track {
  animation-play-state: paused;
}
.hero-banner__track span {
  padding-right: 6rem;
  font-size: 1.05em;
  font-style: italic;
  letter-spacing: 0.02em;
  color: #333;
}
@keyframes hero-marquee {
  from { transform: translateX(0); }
  to   { transform: translateX(-50%); }
}
@keyframes hero-fade-in {
  from { opacity: 0; transform: translateY(10px); }
  to   { opacity: 1; transform: translateY(0); }
}
@media (max-width: 600px) {
  .hero-banner { height: 150px; }
  .hero-banner__track span { font-size: 0.85em; padding-right: 3rem; }
}
@media (prefers-reduced-motion: reduce) {
  .hero-banner { animation: none; }
  .hero-banner__track { animation: none; transform: none; white-space: normal; }
}
[data-theme="dark"] .hero-banner {
  background: #1a1a1a;
  border-color: #333;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.4);
}
[data-theme="dark"] .hero-banner__bg { opacity: 0.14; }
[data-theme="dark"] .hero-banner__overlay {
  background: linear-gradient(180deg, rgba(20,20,20,0.6) 0%, rgba(20,20,20,0.25) 45%, rgba(20,20,20,0.6) 100%);
}
[data-theme="dark"] .hero-banner__track span { color: #e5e5e5; }
</style>

<div class="hero-banner">
  <img class="hero-banner__bg" src="{{ '/images/banner-cat.jpg' | relative_url }}" alt="" aria-hidden="true" loading="eager">
  <div class="hero-banner__overlay"></div>
  <div class="hero-banner__marquee" role="marquee" aria-label="Welcome to my homepage! I'm a 28fall undergraduate majoring in Automation. Early in college, I focused on dynamic planning and statistical machine learning, and was exposed to 3D vision in Jun. 2025 and multi-modal methods in Nov. 2025.">
    <div class="hero-banner__track">
      <span>Welcome to my homepage! I'm a 28fall undergraduate majoring in Automation. Early in college, I focused on dynamic planning and statistical machine learning, and was exposed to 3D vision in Jun. 2025 and multi-modal methods in Nov. 2025.</span>
      <span aria-hidden="true">Welcome to my homepage! I'm a 28fall undergraduate majoring in Automation. Early in college, I focused on dynamic planning and statistical machine learning, and was exposed to 3D vision in Jun. 2025 and multi-modal methods in Nov. 2025.</span>
    </div>
  </div>
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
