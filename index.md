---
layout: default
title: Home
---

# Welcome

![coiling snake image]({{ site.url }}/_images/coiling snake.jpg)

Ithaca Nei Gong is a school of Daoist internal development, offering ongoing classes in Qi Gong. We are affiliated with [Lotus Nei Gong](http://lotusneigong.com){:target="_blank"}, the school of Damo Mitchell, and we attempt to teach as close to that lineage as possible.

{%comment%}
The word <i>neigong</i> (內功) is comprised of <i>nei</i>, meaning 'internal', and <i>gong</i> meaning 'skill acquired through long training'. Thus, neigong could be described as development of skill of your inner landscape. 

The body work is designed to remove imbalances caused by... 

Goals:
- To build a body capable of having the mind stably sit in it.

I don't care about money. I'm simply looking for people of adventurous spirit to engage in practice.

This needs work…
<b>Lotus Nei Gong</b> is a northern sect Daoist school
and as such teaches: 
* ”Ming before Xing" - 
restoration and refinement of the body 
before beginning 
cultivation of a person's nature. 

* “Xing before Ming" - 
cultivation of a person's nature
before beginning 
restoration and refinement of the body. 

![obligatory low flying dragon image]({{ site.url }}/_images/low flying dragon.jpg)

{%endcomment%}

The starting point for our practice is working to clear our own body of imbalances and habitual tensions. The practical implication of this is that new students should be prepared to do quite a bit of physical work - stretching, core training, movement, standing, and breathing.

<br/>

---

# Most recent blog post...
  <h2 class="post-title">
    <a href="{{ site.posts.first.url }}">{{ site.posts.first.title }}</a>
  </h2>
  <span class="post-date">{{ site.posts.first.date | date_to_string }}</span>
  {{ site.posts.first.content | strip_html | truncatewords:30 }}

{% comment %}
<div class="posts">
  {% for post in paginator.posts %}
  <div class="post">
    <h1 class="post-title">
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h1>

    <span class="post-date">{{ post.date | date_to_string }}</span>

    {{ post.content }}
  </div>
  {% endfor %}
</div>

<div class="pagination">
  {% if paginator.next_page %}
    <a class="pagination-item older" href="{{ site.baseurl }}/page{{paginator.next_page}}">Older</a>
  {% else %}
    <span class="pagination-item older">Older</span>
  {% endif %}
  {% if paginator.previous_page %}
    {% if paginator.page == 2 %}
      <a class="pagination-item newer" href="{{ site.baseurl }}/">Newer</a>
    {% else %}
      <a class="pagination-item newer" href="{{ site.baseurl }}/page{{paginator.previous_page}}">Newer</a>
    {% endif %}
  {% else %}
    <span class="pagination-item newer">Newer</span>
  {% endif %}
</div>

{% endcomment %}
