---
layout: default
title: Home
---

<section id="about-me">
  <h2><i class="fa-solid fa-user"></i> About Me</h2>
  {{ site.data.about-me.about | markdownify }}
</section>

<section id="experience">
  <h2><i class="fa-solid fa-briefcase"></i> Experience</h2>
  {% for exp in site.data.experience %}
  <div class="experience-item">
    <h3>{{ exp.role }} at {{ exp.organization }}</h3>
    <p><em>{{ exp.period }}</em></p>
    {{ exp.details | markdownify }}
  </div>
  {% endfor %}
</section>

<section id="skills">
  <h2><i class="fa-solid fa-cogs"></i> Skills</h2>
  <ul>
    {% for skill in site.data.skills %}
      <li>{{ skill }}</li>
    {% endfor %}
  </ul>
</section>

<section id="publications">
  <h2><i class="fa-solid fa-book"></i> Publications</h2>
  {{ site.data.publication.detail | markdownify }}
</section>


