---
layout: default
title: Home
---

# Welcome

Ithaca Nei Gong is a school of Daoist internal arts, offering ongoing classes in Qi Gong. We are affiliated with [Lotus Nei Gong](http://lotusneigong.com), the school of Damo Mitchell, and we attempt to teach as close to that lineage as possible.

{%comment%}
The word <i>neigong</i> (內功) is comprised of <i>nei</i>, meaning 'internal', and <i>gong</i> meaning 'skill acquired through long training'. Thus, neigong could be described as development of skill of your inner landscape. 

The body work is designed to remove imbalances caused by... 

Goals:
- To build a body capable of having the mind stably sit in it.

I don't care about money. I'm simply looking for people of adventurous spirit to engage in practice.
{%endcomment%}

Lotus Nei Gong is a northern sect Daoist school and as such teaches "Ming before Xing" - restoration and refinement of the body before beginning cultivation of a person's nature. The practical implication of this is that we do quite a bit of body work - stretching, core training, movement, standing, breathing, etc. 


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
