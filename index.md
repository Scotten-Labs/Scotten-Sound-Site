<body>
    {% capture homeRow %}{% include homeRow.md %}{% endcapture %}
    {{ homeRow | markdownify }}
</body>

# Scotten Sound is currently down for maintenance.
Everything visible is for testing purposes **ONLY** nothing is permanent or finalized.

#### TODO
- [x] Figure out how to do inclusive markdown text (DONE)
- [ ] Footers < Look more into this
- [x] About Page
- [ ] Finish About Page
- [ ] Portfolio
- [ ] Education / Background

<body>
    {% capture testing %}{% include test.md %}{% endcapture %}
    {{ testing | markdownify }}
</body>
