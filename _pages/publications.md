---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: false
---

<!-- {% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %} -->

<p>
  <b style="font-size: 20px;">Efficient Fault Tolerance for Stateful Serverless Computing with Asymmetric Logging</b><br>
  Sheng Qi, <b>Haoyu Feng</b>, Xuanzhe Liu, Xin Jin<br>
  ACM Transactions on Computer Systems (<a href="https://dl.acm.org/journal/tocs">TOCS</a>), 2025.<br>
  [<a href="https://dl.acm.org/doi/pdf/10.1145/3725985">PDF</a>][<a href="https://doi.org/10.1145/3725985">DOI</a>]
</p>

<!-- New style rendering if publication categories are defined -->
<!-- {% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %} -->



