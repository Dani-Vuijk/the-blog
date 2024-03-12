---
title: The Blog
---
Hi! I'm setting this up.  

Stuff left to do:  
- [ ] bother cloning this locally so I don't need to use GitHub's shitty built-in edditor.
- [ ] actually write content
- [ ] write a generic about me page.
- [ ] summon
- [ ] setup mailing list
- [ ] tell people I'm doing this
- [ ] banish
- [x] invent time travel

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
