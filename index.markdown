---
layout: default
title: Home
---

<section class="intro">
  <h2>Mystic Hearth is our circle.</h2>
  <p>A place where old roots and new growth share the same soil.<br>
  Come as you are, bring what you love, and let’s build something beautiful together.</p>
</section>

<section class="cards">
  <a href="./apothecary/" class="card">
	<img src="{{ '/assets/images/market.jpg' | relative_url }}" alt="The Market">
    <h2>Apothecary</h2>
    <p>Explore our market - A collection of handcrafted goods inspired by nature and the turning seasons.</p>
  </a>

  <a href="./enrichment/" class="card">
	<img src="{{ '/assets/images/enrichment.jpg' | relative_url }}" alt="Enrichment">
    <h2>Enrichment</h2>
    <p>Homeschool Courses - Where learning follows the rhythm of the seasons and nature leads the way.</p>
  </a>

  <a href="./journal/" class="card">
	<img src="{{ '/assets/images/journal.jpg' | relative_url }}" alt="Journal">
    <h2>Journal</h2>
    <p>A seasonal journal of homegrown learning. Stories, crafts, and recipes from our little hearth.</p>
  </a>
</section>

<style>
.intro {
  text-align: center;
  margin: 2rem 0;
  font-size: 1.1rem;
}

.cards {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 1.5rem;
  max-width: 960px;   /* Fits 3 cards neatly */
  margin: 0 auto;
  padding-bottom: 2rem;
}

.card {
  background: #fffaf3;
  border-radius: 12px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.15);
  text-align: center;
  text-decoration: none;
  color: #2c1c11;
  width: 280px;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  display: flex;
  flex-direction: column;
}

.card img {
  width: 100%;
  height: 360px;
  object-fit: cover;
  border-top-left-radius: 12px;
  border-top-right-radius: 12px;
}

.card h2 {
  margin: 0.75rem 0 0;
}

.card p {
  padding: 0 1rem 1.5rem;
  flex-grow: 1;
}

.card:hover {
  transform: scale(1.03);
  box-shadow: 0 6px 16px rgba(0,0,0,0.25);
}

/* Only stack on smaller screens */
@media (max-width: 900px) {
  .cards {
    flex-direction: column;
    align-items: center;
  }
}
</style>
