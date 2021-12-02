---
permalink: "/"
layout: "default"
---

# Scotten Sound is currenlty being built.

### This site is built using jekyll and hosted on GitHub Pages.
Most everything visible is for testing purposes **ONLY**, nothing is permanent nor finalized.

---

#### TODO
- [x] Figure out how to do inclusive markdown text (DONE)
- [ ] Footers < Look more into this
- [ ] Headers < ^^^ Same up there
- [x] About Page < Add stuff to ths
- [ ] Finish About Page
- [ ] Portfolio
- [ ] Education / Background

---

# Past Events

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>