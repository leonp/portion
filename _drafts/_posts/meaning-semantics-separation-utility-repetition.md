---
title: Meaning, semantics, separation, utility, repetition
date: 2017-08-10 17:42:31 +0000
layout: post
---


Well worth reading [CSS Utility Classes and "Separation of Concerns"](https://adamwathan.me/css-utility-classes-and-separation-of-concerns/); it's excellent (and thorough) on why utility CSS (e.g. [Tachyons](http://tachyons.io)) is the sanest, most "semantic" approach to CSS, and why it's not the same as inline styles. Only bit I'd question is its approach to repeatable blocks of code. Wathan suggests adding classes like `btn-purple`​; instead, use includes and variables to generate HTML with utility classes. In Jekyll you'd use something like `include button.html bg=purple text=white` or similar.