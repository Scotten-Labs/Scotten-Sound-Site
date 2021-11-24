---
permalink: /test.html
layout: "posts"
---

<body>
    {% capture homeRow %}{% include homeRow.md %}{% endcapture %}
    {{ homeRow | markdownify }}
</body>


# Hello World!

### Blog Posts
<!-- BLOG-POST-LIST:START -->
<!-- BLOG-POST-LIST:END -->