---
permalink: /template.html
---

<body>
    {% capture homeRow %}{% include homeRow.md %}{% endcapture %}
    {{ homeRow | markdownify }}
</body>
