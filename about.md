---
layout: page
title: Blog
permalink: /blog/
---

<div class="home">

  <h1 class="page-heading">Posts</h1>

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

  <!-- <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p> -->

</div>

<!-- This is the base Jekyll theme. You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](http://jekyllrb.com/)

You can find the source code for the Jekyll new theme at:
{% include icon-github.html username="jglovier" %} /
[jekyll-new](https://github.com/jglovier/jekyll-new)

You can find the source code for Jekyll at
{% include icon-github.html username="jekyll" %} /
[jekyll](https://github.com/jekyll/jekyll) -->
