---
layout: default
title: Rubyrush
---

这是我的博客，我会在这里记录生活和想法。


<p><br /><b>My Blog:</b></p>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>


<p><br /><b>RubyRush:</b></p>

<blockquote>
永远爱我的老婆Ruby
</blockquote>

[oss]:http://en.wikipedia.org/wiki/Open_source
