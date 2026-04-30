---
title: Steph Norwood
layout: nav-profile
date: 2024-12-02
---


# Steph Norwood

Steph Norwood is a first-year Medieval Studies MA student in the English Department at the University of New Mexico. Their research focuses on gender, sexuality, and violence in medieval literature from the North Atlantic.

```yaml
homepage: TRUE
summary: Steph Norwood
thumbnail: assets/images/your-image.jpg
position: 1
```

{% assign essays = site.pages | where: "homepage", true %}
{% include nav/card-stack.html cards = essays %}