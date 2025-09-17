---
layout: default
title: AI Data Production Landscape
description: A comprehensive analysis of artificial intelligence data production systems and methodologies
---

<style>
.hero-banner {
  background: linear-gradient(135deg, #FFECD2 0%, #FCB69F 50%, #FFD700 100%);
  padding: 4rem 2rem;
  text-align: center;
  margin-bottom: 3rem;
  border-radius: 8px;
}

.hero-banner h1 {
  color: #333;
  font-size: 2.5rem;
  margin-bottom: 1rem;
  font-weight: 300;
}

.hero-banner p {
  color: #666;
  font-size: 1.2rem;
  max-width: 600px;
  margin: 0 auto;
}

.cards-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 2rem;
  margin: 3rem 0;
}

.card {
  background: #fff;
  border: 1px solid #e1e1e1;
  border-radius: 8px;
  padding: 2rem;
  box-shadow: 0 2px 8px rgba(0,0,0,0.05);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.card:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 16px rgba(0,0,0,0.1);
}

.card h3 {
  color: #333;
  margin-bottom: 1rem;
  font-size: 1.3rem;
}

.card p {
  color: #666;
  margin-bottom: 1.5rem;
  line-height: 1.6;
}

.card-link {
  color: #FCB69F;
  text-decoration: none;
  font-weight: 500;
  border-bottom: 1px solid transparent;
  transition: border-color 0.2s ease;
}

.card-link:hover {
  border-bottom-color: #FCB69F;
}

.footer {
  margin-top: 4rem;
  padding: 2rem 0;
  border-top: 1px solid #e1e1e1;
  color: #666;
  text-align: center;
}

@media (max-width: 768px) {
  .hero-banner h1 {
    font-size: 2rem;
  }
  
  .hero-banner p {
    font-size: 1rem;
  }
  
  .cards-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="hero-banner">
  <h1>AI Data Production Landscape</h1>
  <p>A comprehensive analysis of artificial intelligence data production systems, methodologies, and empirical findings</p>
</div>

<div class="cards-grid">
  <div class="card">
    <h3>Dataset</h3>
    <p>Curated collection of AI data production metrics, system performance indicators, and production pipeline characteristics across diverse organizational contexts.</p>
    <a href="../data/processed/dataset.csv" class="card-link">View Dataset →</a>
  </div>

  <div class="card">
    <h3>Collections</h3>
    <p>Structured repositories of supplementary materials, code implementations, and methodological artifacts supporting the research findings.</p>
    <a href="../collections/" class="card-link">Browse Collections →</a>
  </div>

  <div class="card">
    <h3>Paper</h3>
    <p>Research manuscript examining patterns, challenges, and emerging practices in contemporary AI data production workflows and organizational implementations.</p>
    <a href="../paper/draft/" class="card-link">Read Paper →</a>
  </div>

  <div class="card">
    <h3>About</h3>
    <p>Project overview, methodology documentation, and contextual information regarding data collection procedures and analytical frameworks employed.</p>
    <a href="../README.md" class="card-link">Learn More →</a>
  </div>
</div>

<div class="footer">
  <p>This research contributes to understanding AI data production systems in academic and industry contexts.</p>
</div>