---
layout: subpage-list
title: Test Level
h1: True
nav:
 hide: True
stylus: |
 body
  background: url("64-checkerboard.png") #ece repeat center -64px;
 main
  background: transparent;
 iframe
  display: block;
  margin: 0 auto;
 @media (min-width: 640px)
  main
   background-position: left 64px;
   > article
    background: transparent url("../penguin-bg.png") no-repeat left bottom;
    > :first-child
     float: right;
     position: relative; top: 0.25em;
     margin-left: 0.5em; margin-bottom: 0.5em;
    > nav.subpage
     position: relative; top: -0.5em;
---

<iframe src="https://www.youtube.com/embed/FVPG2B3pdrU"
        style="width: 360px; height: 570px;" frameborder="0" allowfullscreen></iframe>
