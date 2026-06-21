---
permalink: /
title: "Lishu Zhang / 张郦姝"
layout: splash
author_profile: false
redirect_from:
  - /about/
  - /about.html
header:
  overlay_color: "#2c3e50"
  avatar: "newpic.jpg"
  cta_url: "/research/"
  cta_label: "Explore my research"
excerpt: "PhD candidate in Economics, Tilburg University<br>Researcher in Finance, CREST (Paris)"
feature_row:
  - title: "Job Market Paper 1"
    excerpt: "**Critical Raw Material Dependency and Asset Pricing** — a firm-level measure of exposure to critical raw materials, built on a production-network framework, with asset-pricing implications."
    url: "#"
    btn_label: "Coming soon"
    btn_class: "btn--disabled"
  - title: "Job Market Paper 2"
    excerpt: "**Resistance and Arbitrage: International Trade in Brown Loans** — a measure of carbon sensitivity in lending and the international transfer of climate risk.<br>*Yihong Xia Best Paper Award, CICF 2025.*"
    url: "https://www.dropbox.com/scl/fi/hcqlp7ls6i2v8ughdodbc/JMP_2026.pdf?rlkey=z7iw0zsemz8hrkdfkr0eo2ima&st=xu14dxor&dl=0"
    btn_label: "Read draft"
    btn_class: "btn--primary"
---

<style>
/* ---- Minimal teal splash hero, split into two halves ---- */
.page__hero--overlay {
  background-color: #2c3e50 !important;
  padding: 2.25em 0;
}
.page__hero--overlay .page__hero-split {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 2em;
  max-width: 880px;
  margin: 0 auto;
  padding-left: 3em;
}
.page__hero--overlay .page__lead { white-space: nowrap; }
.page__hero--overlay .page__hero-avatar {
  flex: 0 0 30%;
  max-width: 220px;
  width: 30%;
  height: auto;
  aspect-ratio: 1 / 1;
  object-fit: cover;
  border-radius: 14px;
  border: 4px solid rgba(255, 255, 255, 0.9);
  box-shadow: 0 10px 28px rgba(0, 0, 0, 0.25);
  margin: 0 0 0 -1em;
}
.page__hero--overlay .page__hero-text { flex: 0 1 auto; position: relative; top: 0.7em; }
.page__hero--overlay .page__title {
  font-size: 2em;
  font-weight: 700;
  letter-spacing: -0.3px;
}
.page__hero--overlay .page__lead {
  font-size: 1.05em;
  font-weight: 400;
  opacity: 0.95;
}
/* Stack vertically on small screens */
@media (max-width: 600px) {
  .page__hero--overlay .page__hero-split {
    flex-direction: column;
    text-align: center;
    gap: 1.2em;
  }
  .page__hero--overlay .page__hero-avatar { width: 60%; }
  .page__hero--overlay .page__hero-split { padding-left: 0; }
  .page__hero--overlay .page__lead { white-space: normal; }
}
.page__hero--overlay .btn--light-outline {
  font-weight: 600;
  border-width: 2px;
}

/* ---- Two JMP cards below the panel ---- */
.feature__wrapper {
  border-bottom: none !important;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 1em;
  margin: 1.25em auto 0;
}
.feature__wrapper .feature__item {
  float: none;
  width: 48%;
  max-width: 510px;
  margin: 0;
  font-size: 1rem;
}
.feature__item .archive__item-body {
  background: #fff;
  border-radius: 14px;
  padding: 0.7em 1.4em 0.9em;
  box-shadow: 0 8px 24px rgba(20, 20, 60, 0.10);
  border-top: 5px solid #2c3e50;
  height: 100%;
  transition: transform 0.15s ease, box-shadow 0.15s ease;
}
.feature__item .archive__item-body:hover {
  transform: translateY(-4px);
  box-shadow: 0 14px 34px rgba(20, 20, 60, 0.16);
}
.feature__item .archive__item-title { margin-top: 0.2em; margin-bottom: 0.3em; font-weight: 700; font-size: 1.1em; }
.feature__item .archive__item-excerpt { font-size: 0.95em; margin-bottom: 0.6em; }
.feature__item .archive__item-body .btn { margin-bottom: 0.2em; }
.btn--primary {
  background-color: #2c3e50 !important;
  border-color: #2c3e50 !important;
}
/* Muted "Coming soon" card (JMP1) */
.feature__item:nth-child(1) .archive__item-body {
  border-top-color: #b5b5b5;
  opacity: 0.65;
}
.feature__item:nth-child(1) .archive__item-body:hover {
  transform: none;
  box-shadow: 0 8px 24px rgba(20, 20, 60, 0.10);
}
.btn--disabled {
  background-color: #9e9e9e !important;
  border-color: #9e9e9e !important;
  pointer-events: none;
  cursor: default;
}
@media (max-width: 600px) {
  .feature__wrapper .feature__item { width: 100%; max-width: none; }
}

/* ---- Welcome line + intro text ---- */
.page__content .welcome-line {
  text-align: center;
  font-size: 1.45em;
  font-weight: 700;
  margin: 1.5em auto 0;
}
.page__content .intro { max-width: 46em; margin: 2.5em auto 0; }
</style>

<p class="welcome-line">Welcome to my personal website!</p>

{% include feature_row %}

<div class="intro" markdown="1">

I am a fifth-year PhD candidate in Economics at Tilburg University. My research interests lie broadly within Trade, Environmental Economics, and Finance. My current research is in Climate Finance, where I draw on trade and macroeconomic theory to motivate and structure empirical tests. I am supervised by Prof. Harry Huizinga, Prof. Harald Benink, and Dr. Louis Raes. I joined CREST (Finance group) from 1 Nov 2025 as a researcher in Paris.

My research agenda studies how global financial markets respond to climate change and how these responses redistribute climate-related risks across countries, firms, and investors. My dissertation examines this question through cross-border equity investment, M&A, and bank lending, focusing on the financing and control of brown assets. At CREST, I extend this agenda to critical raw material (CRM) risk, shifting attention from the risks of carbon-intensive assets to the material bottlenecks created by the green transition. This new line of work combines trade, climate finance, and AI-assisted measurement to study how supply-chain dependencies shape firm vulnerability and asset prices.

</div>
