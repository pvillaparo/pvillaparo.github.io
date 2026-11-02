---
layout: single
title: "Cusco-stats"
permalink: /cusco-stats/
excerpt: "The 116 districts of Cusco, Peru, in data: canon, municipal budgets, schools, households and poverty, harmonized from official statistics."
author_profile: true
cusco_theme: true
share_title: "Cusco-stats · The 116 districts of Cusco, in data"
share_description: "Interactive charts and maps of canon transfers, municipal budgets, schools, households and poverty for the districts of Cusco, Peru, built from official INEI statistics. In English and Spanish."
share_image: "/images/cusco-stats-share-v2.png"
share_image_alt: "Cusco-stats: a map of the 116 districts of Cusco shaded in blue by canon per person, next to the title The 116 districts of Cusco, Peru, in data."
---

{% include base_path %}

<div id="cusco-stats" class="cs-landing">
  <section class="cs-hero" aria-labelledby="cs-hero-title">
    <div class="cs-hero-text">
      <div class="cs-brand">
        <svg class="cs-logo" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32 32" aria-hidden="true" focusable="false"><rect x="3" y="18" width="5" height="11" rx="1.5"/><rect x="10.5" y="11" width="5" height="18" rx="1.5"/><rect x="18" y="14" width="5" height="15" rx="1.5"/><rect class="cs-logo-accent" x="25.5" y="5" width="5" height="24" rx="1.5"/></svg>
        <span class="cs-wordmark">Cusco-stats</span>
        <span class="cs-badge">FIRST RELEASE</span>
      </div>
      <h2 id="cs-hero-title">The 116 districts of Cusco, in data.</h2>
      <p class="cs-hero-copy">Canon transfers, municipal budgets, schools, households, poverty and public services, harmonized from official statistics into one consistent district-by-year dataset.</p>
      <div class="cs-actions">
        <a class="cs-cta" href="https://pvillaparo.github.io/cusco-data/">Open Cusco-stats <span aria-hidden="true">↗</span></a>
        <a class="cs-secondary" href="https://pvillaparo.github.io/cusco-data/?lang=es" lang="es" hreflang="es">Ver en español <span aria-hidden="true">↗</span></a>
      </div>
      <p class="cs-hero-note">English and Spanish · Charts and maps for every district · Downloadable data</p>
    </div>
    <figure class="cs-hero-map">
      <img src="{{ base_path }}/images/cusco-stats-map.svg" width="400" height="480" alt="Map of the districts of Cusco shaded by canon per person: the districts of La Convención, in the north, receive by far the most.">
      <figcaption>Canon per person by district, 2020–2024 average. Darker means more.</figcaption>
    </figure>
  </section>

  <p class="cs-intro">Cusco is my hometown. Official statistics about its districts exist, but they are scattered across many tables, change definitions over time and rarely line up from one year to the next. I built Cusco-stats to bring them together in one place, harmonized so that districts can be compared with each other and over time, and to share them with anyone curious about the region.</p>

  <section class="cs-features" aria-label="What you can do with Cusco-stats">
    <article class="cs-feature">
      <span class="cs-feature-number">01</span>
      <h3>Start with the story</h3>
      <p>Six short charts on how canon windfalls, municipal budgets, schools and households in Cusco have changed since the 2000s, each with links that open the data behind it.</p>
    </article>
    <article class="cs-feature">
      <span class="cs-feature-number">02</span>
      <h3>Explore any district</h3>
      <p>Indicators for the department, its 13 provinces and 116 districts. Compare up to six places, switch between totals, values per person and constant 2024 soles, and map the districts year by year.</p>
    </article>
    <article class="cs-feature">
      <span class="cs-feature-number">03</span>
      <h3>Take the data with you</h3>
      <p>Every view can be shared as a link and downloaded as a CSV file. The code and the harmonized dataset are open on GitHub.</p>
    </article>
  </section>

  <section class="cs-sources" aria-labelledby="cs-sources-title">
    <h3 id="cs-sources-title">Data and sources</h3>
    <p>The figures come from the <strong>Regional Information System for Decision Making (SIRTOD)</strong> of INEI, Peru's national statistics institute, which compiles official series from INEI itself, the Ministry of Economy and Finance, the Ministry of Education and other public agencies.</p>
    <p>Harmonizing them involved a few choices that matter for interpretation: population projections from the 2007 and 2017 censuses are spliced into one series, provincial and departmental figures are shown only when enough districts report, and money in constant soles is deflated with the Cusco city consumer price index. All of this is documented, step by step, in <a href="https://pvillaparo.github.io/cusco-data/methods.html">Methods &amp; data</a>.</p>
    <p class="cs-source-line">Data: INEI, SIRTOD (download of September 2026). District boundaries: INEI, IDE 2024 edition. Harmonized data and text: <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a>; code: <a href="https://github.com/pvillaparo/cusco-data/blob/main/LICENSE">MIT</a>.</p>
  </section>

  <aside class="cs-notes" aria-labelledby="cs-notes-title">
    <h3 id="cs-notes-title">About this project</h3>
    <p>A project by Paola Villa Paro, built with assistance from Claude (Anthropic). It is a first release: corrections and suggestions are very welcome through the <a href="https://github.com/pvillaparo/cusco-data/issues">project's GitHub page</a>.</p>
  </aside>
</div>
