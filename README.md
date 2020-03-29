<div align="center">

# YAMB CSS
<small>Yet Another Minimal Barebone CSS Framework</small>

[![license](https://img.shields.io/badge/license-BOML-green?style=flat-square)](LICENSE.md)
[![version](https://img.shields.io/github/v/tag/runxel/yamb-css)](https://github.com/runxel/yamb-css/releases)
</div>

> YAMB is a «no bullshit» CSS boilerplate ready to use in your projects.

This project evolved from my own small CSS micro-framework: reoccuring basic snippets I didn't wanted to copy&paste everytime I start a new project or MVP/demo.

YAMB is ready to use, but can also act as a solid starting point for your own design adventure. It has everything you need!

## Features
- 🏝 easy to use, since it is mostly<sup id="a1">[1](#f1)</sup> classless
- 💻 easy to hack on: it's plain simple CSS, no preproccesors involved!<sup id="a2">[2](#f2)</sup> 
- 🎨 easy to customize, since there are a lot of CSS variables defined
- ⚡ lightweight at just 10kb minified<sup id="a3">[3](#f3)</sup>
- 🌚 **dark mode's** built in!
- 📰 comes with a **print** stylesheet<sup id="a4">[4](#f4)</sup> (yes, really!)


<b id="f1">[1]</b> Why "_mostly_" classless?  
There are some classes, because there are some conventions many people are following. E.g. the whole content is wrapped in a `div` with a class called `page`. I aim to finde the happy medium. [↩](#a1)

<b id="f2">[2]</b> The CSS is still a bit too verbose for my taste, but since this is just plain CSS without any preprocessors it's as good as it can be. It is easy to imagine how compact the CSS could become if a preprocessor with mixins would be used. This is left to be discovered by the reader. [↩](#a2)

<b id="f3">[3]</b> Minimized with [crass](https://github.com/mattbasta/crass), v0.12.3:
`crass yamb.css --optimize --O1 > yamb.min.css` [↩](#a3)

<b id="f4">[4]</b> Support for paged media is somewhat patchy, so I tend to include CSS2 specs as well as their new counterparts from CSS3. [↩](#a4)

---

There are actually some efforts for easy barebone CSS frameworks out there. They are called _classless_, since you don't need to learn any proprietary conventions used by full fledged frameworks like Tailwind.
A user called _dohliam_ made a fine [website](https://dohliam.github.io/dropin-minimal-css/) where you can directly test a lot of those barebone CSS boilerplates.
_Chef's recommendations: Sakura CSS & and Water CSS._


![Imgur](https://i.imgur.com/NX391J6.gifv)

