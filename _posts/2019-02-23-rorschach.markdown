---
layout: post
title:  "I made dis #1, Rorschach's ink blot"
date:   2019-02-23 20:00:00 +0700
categories: css codepen
excerpt: do you see anything?
banner: https://picsum.photos/g/1280/640?image=329
---

## This page might take a heavy load on the browser

Recently I took a liking on experimenting stuff on codepen. And here's what I made.

## Randomly generated Rorschach's ink blot

Below is a pen I made for this week's codepen challenge. The theme for February is shapes, and this week's are blobs.

<p class="codepen" data-height="640" data-theme-id="dark" data-default-tab="result" data-user="anthesema" data-slug-hash="GzzGpQ" style="height: 420px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid black; margin: 1em 0; padding: 1em;" data-pen-title="transforming rorschach&amp;apos;s mask">
  <span>See the Pen <a href="https://codepen.io/anthesema/pen/GzzGpQ/">
  transforming rorschach&apos;s mask</a> by anthesema (<a href="https://codepen.io/anthesema">@anthesema</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

## How it works

I used several dozens of `div` elements, shaped them into circles, put an svg `filter` on the container and randomly generate position for each of them in JS.

The CSS `transition` property took care of the animation.

My laptop fan was _whooshing_ a bit as I wrote this post.

But hey, it's kind of satisfying to look at.