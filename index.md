---
layout: home
---
Увижу я эту тему сегодня или опять нет?!
# Archives

## Sep 2022

* 2020-10-10 my first post: [first post](_posts/2020-10-10-first-post.md)
   
## Aug 2022
                    
* 2020-10-20 my second post: [second post](_posts/2020-10-20-seconf-post.md) 

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
