---
layout: page
footer: true
---

Welcome to home Scotch Collies at Halcyon Lane Farm.


<span>
<img src="/images/jack-lassie.jpg" width="300" alt="Jack and Lassie" title="Jack and Lassie" />
By and by, things change.
<img src="/images/dogs-lounging.jpg" align="right" width="400" alt="lazy dogs" title="Lazy Dogs" />
</span>




Some of the latest news can be found here:

<ul>
  {% for post in site.posts reverse %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
