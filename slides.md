---
theme: seriph
addons:
  - "@twitwi/slidev-addon-ultracharger"
addonsConfig:
  ultracharger:
    inlineSvg:
      markersWorkaround: false
    disable:
      - metaFooter
      - tocFooter
NObackground: >-
  https://images.unsplash.com/photo-1511149755252-35875b273fd6?ixlib=rb-4.0.3&dl=leon-contreras-qpdfU6vehgs-unsplash.jpg&w=1920&q=80&fm=jpg&crop=entropy&cs=tinysrgb
background: /midjourney_eye.jpg
highlighter: shiki
routerMode: hash
lineNumbers: false

css: unocss
title: Научная визуализация данных
subtitle: Лекция 3. Зрительное восприятие
date: 13/11/2024
venue: HSE
author: Алексей Болдырев
---

<br>
<br>

# <span style="font-size:28.0pt" v-html="$slidev.configs.title?.replaceAll(' ', '<br/>')"></span>
# <span style="font-size:24.0pt" v-html="$slidev.configs.subtitle?.replaceAll(' ', '<br/>')"></span>
# <span style="font-size:18.0pt" v-html="$slidev.configs.author?.replaceAll(' ', '<br/>')"></span>

<span style="font-size:18.0pt" v-html="$slidev.configs.date?.replaceAll(' ', '<br/>')"></span>

<div>
<br>
<br>
<span style="color:#b3b3b3ff; font-size: 11px; float: right;">Изображение: Midjourney 6.0. Запрос "Visual perception and data visualization"
</span>
</div>


<style>
  :deep(footer) { padding-bottom: 3em !important; }
</style>

<!--
NB: This demo uses a custom syntax (using preparser extensions), with all the @@@@.
-->

---
src: ./slides/0_outline.md
---

---
src: ./slides/0_intro.md
---

---
src: ./slides/1_piecharts.md
---

---
src: ./slides/2_barcharts.md
---

---
src: ./slides/3_mapping_data.md
---

---
src: ./slides/0_end.md
---