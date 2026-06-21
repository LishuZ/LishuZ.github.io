---
permalink: /
title: "Lishu Zhang / 张郦姝"
layout: splash
author_profile: false
header:
  overlay_color: "#65312B"
  avatar: "newpic.jpg"
  cta_url: "/research/"
  cta_label: "Explore my research"
excerpt: "PhD candidate in Economics, Tilburg University<br>Researcher in Finance, CREST (Paris)"
feature_row:
  - title: "Job Market Paper 1"
    excerpt: "**Critical Raw Material Dependency and Asset Pricing**<br>A firm-level measure of exposure to critical raw materials, built on a production-network framework, with asset-pricing implications."
    url: "#"
    btn_label: "Coming soon"
    btn_class: "btn--disabled"
  - title: "Job Market Paper 2"
    excerpt: "**Resistance and Arbitrage: International Trade in Brown Loans**<br>A measure of carbon sensitivity in lending and the international transfer of climate risk.<br>*Yihong Xia Best Paper Award, CICF 2025.*"
    url: "https://www.dropbox.com/scl/fi/hcqlp7ls6i2v8ughdodbc/JMP_2026.pdf?rlkey=z7iw0zsemz8hrkdfkr0eo2ima&st=xu14dxor&dl=0"
    btn_label: "Read draft"
    btn_class: "btn--primary"
---

<style>
/* ---- Homepage hero, split into two halves ---- */
.page__hero--overlay {
  background: linear-gradient(
    90deg,
    rgba(101, 49, 43, 0.82) 0%,
    #65312B 12%,
    #65312B 88%,
    rgba(101, 49, 43, 0.82) 100%
  ) !important;
  padding: 2.25em 1em;
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
  position: relative;
  left: -1.8em;
}
.page__hero--overlay .page__hero-text { flex: 0 1 auto; position: relative; top: 0.7em; }
.page__hero--overlay .page__title {
  font-size: 2em;
  font-weight: 700;
  letter-spacing: 0;
  color: #fff !important;
  text-shadow: 0 2px 10px rgba(47, 37, 35, 0.22) !important;
}
.page__hero--overlay .page__lead {
  font-size: 1.05em;
  font-weight: 400;
  opacity: 1;
  color: #fff !important;
  text-shadow: 0 1px 8px rgba(47, 37, 35, 0.18) !important;
}
/* Stack vertically on small screens */
@media (max-width: 600px) {
  .page__hero--overlay {
    background: #65312B !important;
    padding: 1.65em 1em 1.9em;
  }
  .page__hero--overlay .page__hero-split {
    flex-direction: column;
    text-align: center;
    gap: 1.2em;
  }
  .page__hero--overlay .page__hero-avatar {
    width: 60%;
    max-width: 220px;
    margin: 0 auto;
    left: 0;
  }
  .page__hero--overlay .page__hero-split { padding-left: 0; }
  .page__hero--overlay .page__hero-text { top: 0; }
  .page__hero--overlay .page__lead { white-space: normal; }
}
.page__hero--overlay .btn--light-outline {
  font-weight: 600;
  border-width: 2px;
  background: rgba(255, 255, 255, 0.08);
  color: #fff !important;
  border-color: #fff !important;
  box-shadow: 0 6px 18px rgba(47, 37, 35, 0.13);
  text-shadow: 0 1px 6px rgba(47, 37, 35, 0.14) !important;
}
.page__hero--overlay .btn--light-outline:hover {
  background-color: #fff;
  border-color: #fff !important;
  color: #65312B !important;
}

/* ---- Two JMP cards below the panel ---- */
.feature__wrapper {
  border-bottom: none !important;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 1.22em;
  margin: 1.25em auto 0;
}
.feature__wrapper .feature__item {
  float: none;
  width: 47%;
  max-width: 470px;
  margin: 0;
  font-size: 1rem;
}
.feature__item .archive__item-body {
  background: #fff;
  border-radius: 14px;
  padding: 0.5em 1.25em 0.55em;
  box-shadow: 0 12px 30px rgba(47, 37, 35, 0.10);
  border: 1px solid #F4D34D;
  border-top: 5px solid #F5C518;
  height: 100%;
  display: flex;
  flex-direction: column;
  transition: transform 0.15s ease, box-shadow 0.15s ease;
}
.feature__item .archive__item-body:hover {
  transform: translateY(-4px);
  box-shadow: 0 14px 34px rgba(20, 20, 60, 0.16);
}
.feature__item .archive__item-title { margin-top: 0.05em; margin-bottom: 0.22em; font-weight: 700; font-size: 1.1em; text-align: center; }
.feature__item .archive__item-excerpt { font-size: 0.93em; margin-bottom: 0.45em; }
.feature__item .archive__item-body .btn {
  display: block;
  width: 100%;
  text-align: center;
  font-size: 1em;
  padding: 0.5em 0.8em;
  margin: 0.55em 0 0.05em;
  margin-top: auto;
  border-width: 2px;
  border-radius: 8px;
}
.btn--primary {
  background-color: #fff !important;
  border-color: #F5C518 !important;
  color: #9A7A0E !important;
}
.btn--primary:hover {
  background-color: #F5C518 !important;
  border-color: #F5C518 !important;
  color: #65312B !important;
}
/* Muted "Coming soon" card (JMP1) */
.feature__item:nth-child(1) .archive__item-body {
  border-color: #F7E08A;
  border-top-color: #F2D24A;
  opacity: 0.65;
}
.feature__item:nth-child(1) .archive__item-body:hover {
  transform: none;
  box-shadow: 0 8px 24px rgba(20, 20, 60, 0.10);
}
.btn--disabled {
  background-color: #F7F4F5 !important;
  border-color: #E7DCB6 !important;
  color: #7A7074 !important;
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
