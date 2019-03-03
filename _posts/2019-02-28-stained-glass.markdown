---
layout: post
title:  "I made dis #2, stained glass effect with CSS"
date:   2019-02-28 20:00:00 +0700
categories: css codepen
excerpt: it looked better than I expected... I think
banner: https://picsum.photos/1280/640?image=206
---

## Unlike the previous one, this page won't take a heavy load on the browser

I still took a liking on experimenting stuff on codepen. And here's another one that I made. 

## CSS stained glass effect

Below is another pen I made for this week's codepen challenge. The theme for February was shapes, last week's was blots, this week is polygons

<p class="codepen" data-height="480" data-theme-id="dark" data-default-tab="result" data-user="anthesema" data-slug-hash="LaYBPa" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid black; margin: 1em 0; padding: 1em;" data-pen-title="CSS stained glass">
  <span>See the Pen <a href="https://codepen.io/anthesema/pen/LaYBPa/">
  CSS stained glass</a> by anthesema (<a href="https://codepen.io/anthesema">@anthesema</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

## How does it work?

Basically
- Create a bunch of layers with background images (set the `background-attachment` to `fixed` so it aligns perfectly on each layer)
- Style each layer to spread to the full height & width of the container
- `blur` each layers with `filter`
- Mpdify each layer's `hue-saturation` to give it a dynamic color effect based on it's background

It took a bunch of CSS `clip-path`s and a bit of time to shape complex polygons one by one on each layer. But what took longer is deciding what kind of image that goes with it. An idea passed my mind. Put an image of a wall/window in the front, then put a landscape on the back. I thought "That would be cool", sadly it doesn't.

I was already halfway done with the shapes at the time, and I can't seem to find a way of putting it on top of an image without it looking off. So I flipped through a bunch of images and found this one to be the one that felt the most satisfying.

Initially I was thinking of making a more complex symmetrical patterns.