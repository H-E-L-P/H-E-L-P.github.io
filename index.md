---
layout: page
---

Our aim is to provide new techniques, tools and data to enable astronomers in
Europe to capitalise on the surveys of the distant Universe made by the ESA
mission Herschel.

![EU flag]({{site-url}}/assets/images/flag_yellow_low.jpg?w=300&h=200)

This project has received funding from the European Union’s Seventh Framework
Programme for research, technological development and demonstration under grant
agreement no 607254.

<div class="home">

  <h1 class="page-heading">Events</h1>

  <ul class="post-list">
    {% for post in site.posts %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

        <h2>
          <a class="post-link" href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>


</div>
