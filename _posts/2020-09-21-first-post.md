---
layout: post
title:  "First Post"
---

# ...is this thing on? Testing, testing, aw-deeeeee-ohhhhhhhhhhh, aw-deeeeeeeee-oh...

(could be worse - I could just be dropping carriers)

**Hello world**, this is my first Jekyll blog post.

I don't really care if you like it or not, it is what it is.

-- Mark/VK3EET, MERC webmonkey



<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
