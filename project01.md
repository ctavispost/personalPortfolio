---
title: jot &
layout: default
---
<article class="projContainer">

  <section class="projLimitWidth lgBreak">
  {% include_relative project01/summary.md %}
  </section>

  <section class="projLimitWidth medBreak">
  {% include_relative project01/introduction.md %}
  </section>

  <button class="accordion accordBottomBorder lgBreak">
    <h1>Discovery</h1>
  </button>

  <section class="projLimitWidth panel">
  {% include_relative project01/discovery.md %}
  </section>

  <button class="accordion accordBottomBorder">
    <h1>Information architecture</h1>
  </button>
  <section class="projLimitWidth panel">
  {% include_relative project01/information_architecture.md %}
  </section>

  <button class="accordion accordBottomBorder">
    <h1>Visual Design</h1>
  </button>

  <section class="projLimitWidth panel">
  {% include_relative project01/visual_design.md %}
  </section>

  <button class="accordion"><h1>Conclusions</h1></button>
  <section class="projLimitWidth panel"> <!-- conclusions -->
  {% include_relative project01/conclusions.md %}
  </section> <!-- conclusions -->
</article>

<script src="scripts/accordion.js"></script>
