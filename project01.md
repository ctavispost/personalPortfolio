---
title: jot &
layout: default
---
<nav id="collapsibleNav">
  <a href="#collapsibleNav" id="plus">&#43;</a>
  <a href="#plus" id="collapse">&#45;</a>
  <ul class="contents">
    <li class="contSect">Introduction</li>
    <li class="contSect">Discovery</li>
    <li class="contSect">Information architecture</li>
    <li class="contSect">Visual design</li>
    <li class="contSect">Conclusion</li>
  </ul>
</nav>

<article class="projContainer">
  <section class="projLimitWidth lgBreak">
  {% include_relative project01/summary.md %}
  </section>

  <section class="projLimitWidth medBreak">
  {% include_relative project01/introduction.md %}
  </section>

  <section class="projLimitWidth lgBreak">
  {% include_relative project01/discovery.md %}
  </section>

  <section class="projLimitWidth lgBreak">
  {% include_relative project01/information_architecture.md %}
  </section>

  <section class="projLimitWidth lgBreak">
  {% include_relative project01/visual_design.md %}
  </section>

  <section class="projLimitWidth lgBreak"> <!-- conclusions -->
  {% include_relative project01/conclusions.md %}
  </section> <!-- conclusions -->
</article>
