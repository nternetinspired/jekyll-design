---
layout: page
title: About
---

This is a work-in-progress attempt to create a rapid prototyping
and comping tool with <a href="//jekyllrb.com">Jekyll</a>. Made by
<a href="//twitter.com/nternetinspired">Seth Warburton</a> to enable (his own)
rapid in-browser design, from wireframes and hi-fidelity mockups right through to
production html and css. Nice.
{: class="intro" }

Crucially, it allows me to present the design direction of <em>specific</em> site
elements without the surrounding context, and distraction, of ‘a web design’.
Hopefully this will…


<blockquote cite="http://styletil.es/">
    …help form a common visual language between the designers and the stakeholders
    and provide a catalyst for discussions around the preferences and goals of
    the client.
    <cite><a href="//twitter.com/samanthatoy">
    Samantha Warren</a></cite>
</blockquote>

## Mmmmm Sassy
It includes some neat things like my <a href="//sass-lang.com/">Sass</a>
interpretation of <a href="//twitter.com/samanthatoy">
Samantha Warren</a>'s <a href="//styletil.es/">Style Tiles</a>, Element Collages
inspired by an article from Dan Mall <a href="http://danielmall.com/articles/rif-element-collages/">
http://danielmall.com/articles/rif-element-collages/</a>, which I was turned
on to by <a href="https://twitter.com/_cdja">Chris Allwood</a> ,
and some other patterns that allow you to quickly get past the fundamentals of
a site design. It also includes a customised version of my own Sass framework,
<a href="//github.com/nternetinspired/oneweb-sass/tree/master">oneweb-sass</a>
though it's super-simple to rip out my Sass and replace it with your own.
Whatever floats your boat.

Items of note:

* Fully awesomised Jekyll.
* Github pages friendly. Clone > tweak > push > view.
* A re-usable modular code-base.
* YAML content; set once, use everywhere.
* Style tiles.
* Sassy colour manipulation tools.
* A typography test page.
* oneweb sass.
* Minified html output (optional).

You can find the source code for it at: <a href="//github.com/nternetinspired/jekyll-design">Github</a>.
To run locally you just need to fire up terminal and enter:

    jekyll serve --watch --baseurl
