---
title: Home
description: Portfolio
model: data_file
source: ../graphics/example.html
openGraph:
  image: /assets/images/placeholder.png
styles:
  - /styles/main.css
  - //vjs.zencdn.net/5.9.2/video-js.min.css
scripts:
  - //ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js
---

{{#each collections}}
  <h2><a href="/{{@key}}">{{@key}}</a></h2>
{{/each}}
