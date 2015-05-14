---
layout: page
tagline: open data science initiative
---

Open data science is a philosophy designed to address emerging challenges for society in data. The Open Data Science Initiative is a cross faculty project built around the ideas in this white paper. 

# News

<ul class="post-list">
    {% for post in site.posts %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>


