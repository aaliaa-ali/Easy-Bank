# Easy-Bank

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

- challenge is to build out this landing page and get it looking as close to the design as possible.
  <img src="./design/desktop-design.jpg" width='30%' alt="" />

### Screenshot

<!-- <image s>./screen-shots/mopile%20screen.png) -->
<img src="./screenShots/mopile.png" width='30%' alt="" />
<img src="./screenShots/desktop.png" width='30%' alt="" />
<img src="./screenShots/hidden-menu.png" width='30%' alt="" />

## My process

-first i build my html
-build main scss files (variable,normalize)
-build project styling
-deploy project on git pages

### Built with

- HTML& scss custom properties
- bootstrap

### What I learned

### proud OfThis script

use it to change svg color

 <script>
      const objs = document.querySelectorAll("object");

      for (let obj of objs) {
        obj.addEventListener(
          "mouseover",
          changesSvgColor.bind("", obj, " hsl(136, 65%, 51%)")
        );
        obj.addEventListener(
          "mouseleave",
          changesSvgColor.bind("", obj, " hsl(0, 0%, 100%)")
        );
        function changesSvgColor(element, color) {
          const svg = element.getSVGDocument();
          // make changes
          Array.from(svg.getElementsByTagName("path")).forEach((p) => {
            p.setAttribute("fill", color);
            p.setAttribute("cursor", "pointer");
          });
        }
      }
    </script>

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

## Acknowledgments

-use object tag to display svg and appy css changes on it.
