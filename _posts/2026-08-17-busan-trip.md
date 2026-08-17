---
layout: post
title: "sample: a weekend in Busan"
date: 2026-08-17 11:00:00 +0900
description: what a travel post with photos looks like
tags: travel
categories: daily-life
thumbnail: assets/img/posts/2026-08-busan/beach.jpg
---

This is a sample travel post. The photos live in one folder (`assets/img/posts/2026-08-busan/`), and every image below is click-to-zoom.

A single full-width photo:

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/posts/2026-08-busan/beach.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Haeundae beach, first morning.
</div>

Two photos side by side (they stack vertically on a phone):

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/posts/2026-08-busan/market.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/posts/2026-08-busan/sunset.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Jagalchi market, then sunset from Gwangan bridge.
</div>

And ordinary Markdown text in between, of course. Last one before heading home:

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/posts/2026-08-busan/night.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
