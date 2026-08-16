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
  object-position: 45% 55%;
  opacity: 0.18;
  pointer-events: none;
  user-select: none;
}
.hero-banner__overlay {
  position: absolute;
  inset: 0;
  background: linear-gradient(180deg, rgba(255,255,255,0.72) 0%, rgba(255,255,255,0.55) 45%, rgba(255,255,255,0.72) 100%);
  pointer-events: none;
}
.hero-banner__text {
  position: relative;
  max-width: 72ch;
  margin: 0 auto;
  padding: 2.4em 2em;
  font-family: Georgia, 'Times New Roman', serif;
  font-size: 0.88em;
  line-height: 1.8;
  color: #2b2b2b;
}
.hero-banner__text .hero-banner__title {
  text-align: center;
  font-size: 1.15em;
  font-variant: small-caps;
  letter-spacing: 0.12em;
  margin: 0 0 1.2em 0;
  color: #222;
}
.hero-banner__text p {
  margin: 0 0 1em 0;
}
.hero-banner__text p:last-child {
  margin-bottom: 0;
}
@keyframes hero-fade-in {
  from { opacity: 0; transform: translateY(10px); }
  to   { opacity: 1; transform: translateY(0); }
}
@media (max-width: 768px) {
  .hero-banner__text { padding: 1.6em 1.2em; font-size: 0.8em; line-height: 1.7; }
}
@media (prefers-reduced-motion: reduce) {
  .hero-banner { animation: none; }
}
[data-theme="dark"] .hero-banner {
  background: #1a1a1a;
  border-color: #333;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.4);
}
[data-theme="dark"] .hero-banner__bg { opacity: 0.12; }
[data-theme="dark"] .hero-banner__overlay {
  background: linear-gradient(180deg, rgba(20,20,20,0.78) 0%, rgba(20,20,20,0.6) 45%, rgba(20,20,20,0.78) 100%);
}
[data-theme="dark"] .hero-banner__text { color: #dcdcdc; }
[data-theme="dark"] .hero-banner__text .hero-banner__title { color: #eaeaea; }
</style>

<div class="hero-banner">
  <img class="hero-banner__bg" src="{{ '/images/banner-cat.jpg' | relative_url }}" alt="" aria-hidden="true" loading="eager">
  <div class="hero-banner__overlay"></div>
  <div class="hero-banner__text">
    <p class="hero-banner__title">The Harness Is Not a Leash</p>
    <p>Watch the hand move the bishop. Diagonal, three squares. Nothing forced it; nothing prevented it either — that is the strange thing, the thing one keeps almost seeing and then losing — the rules of chess forbid nothing at all. Knock the board over, pocket the piece, no law stops you. And yet without the rules there is no bishop, no diagonal, no game; only wood on wood, only a hand in the air. Rawls saw it first, or named it first, in 1955; Searle built a whole theory of social reality along the seam. Some rules regulate — the traffic light, the queue — they govern what already happens. Others constitute. They do not say <em>do this, not that.</em> They say: <em>this is what counts as a move at all.</em></p>
    <p>How odd, then — the thought comes unbidden, watching the little agent run its errands across the screen — how odd that we speak of harnesses only in the language of restraint. Guardrails, leashes, sandboxes; as if the model were a reservoir and all our craft were dams. Safety has its reasons, yes. But the vocabulary is subtraction, and the thing itself is not subtraction. The thing itself is chess rules.</p>
    <p>For before the schema — before the little litany of name, of arguments, of types — <em>calling a tool</em> was not something the model was forbidden to do. It was not anything. There was no move to suppress; the square did not exist on the board. And the schema does not say <em>you may.</em> It says what a call <em>is</em> — which was Austin's old discovery, that some utterances do not describe but do; <em>I do</em>, said at the altar, and the world rearranges itself around the words — and Searle's refinement, that such acts carry felicity conditions, that the tokens must come forth <em>just so</em> or they are noise dressed as intent. The schema is the ceremony. The ceremony is what makes the vow a vow.</p>
    <p>Then MCP, and the view widens the way a street widens into a square. Read the specification: there are almost no prohibitions in it. It is a book of definitions. <em>This is what a tool is. This is what a resource is. This is what a prompt is.</em> Everyone speaks of the engineering, N times M collapsing into N plus M, but that is arithmetic; the deeper event is ontological. Interoperability was not permitted by the protocol. It was constituted by it. Before, "a tool" was not a stable object in the agent's world; afterward it exists the way money exists, the way a promise exists — because we agree on what counts. A social fact, conjured out of agreement, holding the whole bazaar together.</p>
    <p>Outside, the evening. The cursor blinks. A behavior that did not exist this morning exists now; nothing was forbidden, nothing was taken away — and somewhere a hand moves a bishop, diagonally, three squares, and it means something.</p>
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
