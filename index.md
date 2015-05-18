---
layout: page
tagline: open data science initiative
---

Open data science is a philosophy designed to address emerging challenges for society in data. The Open Data Science Initiative is a cross faculty project built around the ideas in [this white paper](http://inverseprobability.com/2014/07/01/open-data-science/). 


Many talented people would like to see their ideas and work being applied for the widest benefit possible. The modern internet provides tools such as github, jupyter notebook and reddit for easily distribution and comment on this material. In Sheffield we make our ideas available through these mechanisms. The idea of open data science is to:

1.  Make new analysis methodologies available as widely and rapidly as possible with as few conditions on their use as possible (see [http://sheffieldml.github.io/software.html] and the local [software page](./software.html)).
2.  Educate our commercial, scientific and medical partners in the use of these latest methodologies (see [http://gpss.cc])
3.  Act to achieve a balance between data sharing for societal benefit and the right of an individual to own their data. (see our summary of our efforts in [public understanding and debate](./public_understanding.html))


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


