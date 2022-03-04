---
permalink: "/"
layout: "default"
title: "Scotten Sound"
---

# Scotten Sound is currenlty under maintenance.
Hello and welcome to my website! There is still a lot of information missing here so I will ask that, for now, you go check out my [LinkedIn here](https://www.linkedin.com/in/opscotten)! That is were you can find all of my work experience and past shows I have done up until now. Eventually I will be adding in work experience and past shows I have worked or designed here to give more detailed information.

### Site Backend
This site was written by me (mostly), if you were curious. It's currently hosted and managed through [GitHub Pages](https://pages.github.com/). If you want to see the source code, that I have written for this site, for any reason you can click [here](https://github.com/Scotten-Labs/Scotten-Sound-Site)!

---

#### TODO

 -- Stuff I need to complete before I graduate.

- [x] Figure out how to do inclusive markdown text (DONE)
- [ ] Footers < Look more into this
- [ ] Headers < ^^^ Same up there
- [x] About Page < Add stuff to ths
- [x] Finish About Page
- [ ] Portfolio
- [ ] Education / Background
- [ ] Past / Current Events

---

# Past Events

 -- To be updated with all past and current events before I graduate.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
