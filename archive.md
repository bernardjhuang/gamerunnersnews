---
layout: default
---

<div class="home">

  <h1 class="page-heading">GameRunners LoL News Archive</h1>

  <ul class="post-list">
    {% for post in site.categories.lol %}
      <li>
        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
        <p>
          <span class="post-meta">
            {{ post.date | date: "%b %-d, %Y" }}
            {% if post.author_coach %} 
              by <a href="{{ post.author_coach }}">{{ post.author }}</a>
            {% else %}
              by {{ post.author }}
            {% endif %}
          </span>
        </p>
        {% if post.thumbnail %}
          <a href="{{ post.url | prepend: site.baseurl }}">
            <img class="thumbnail" src="{{ post.thumbnail }}" alt="{{ post.title thumbnail }}">
          </a>
        {% endif %}
        <p>{{ post.excerpt }}</p>
        <a href="{{ post.url | prepend: site.baseurl }}">Continue reading</a>
      </li>
    {% endfor %}
  </ul>

</div>