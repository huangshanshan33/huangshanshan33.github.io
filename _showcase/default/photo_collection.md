---
show: true
width: 4
date: 2021-09-12 00:01:00 +0800
height: 295px
images:
- src: assets/scene/sea.jpg
- - src: assets/scene/desert.jpg
- src: assets/scene/animal.jpg
- src: assets/scene/free.jpg
  title: Photo 2
  desc: Description 2
- src: assets/scene/hill.jpg
- src: assets/scene/tree.jpg
---

{% include widgets/carousel.html id=page.id images=page.images height=page.height %}
