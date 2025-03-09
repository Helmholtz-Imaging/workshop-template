---
title: "My awesome workshop"
date: 2025-03-09
draft: false
layout: workshop
author: My awesome group
description: "This is the description of the workshop"
cover: img/workshop-cover.webp
---

## Introduction

What this presentation provides:

- Demo page for Helmholtz Imaging workshops based on markdown format
- Examples of special elements which can be used in a presentation

---

## Presentation metadata

The frontmatter of a workshop markdown file provides metadata used to print the title slide.

---

## Slide separation

Slides in markdown are separated by `---` lines.

---

## Headers
### Subheaders 

Use markdown headers to define slide headers. A table of content will automatically be rendered from the first header on each slide. 

---

## Notes

Use `notes` shortcode for presentation notes.

{{< notes >}}
Text provided in a `{{notes}}` section will be readable on the scrolling document, and provided as speaker notes in 
slides view, but not printed on the slides.
{{</ notes >}}

---

## Unlist slides

Use `unlist` shortcode at the beginning of a slide so that it is not listed in the table of content.

---

## Citations

Use the `citations` shortcode to render a list of links which will all be shown using the same style in the bottom left corner.

The tools linked below are used for creating these pages, so it's worth checking them out.

{{< citations >}}
- [Hugo static pages](https://gohugo.io/)
- [reveal.js web presentations](https://github.com/hakimel/reveal.js/)
{{< /citations >}}

---

## Code embedding

Show a block of code using the `highlight` shortcode:

{{<highlight python >}}
this is code
{{</highlight>}}

---

## Subtutorials

{{< notes >}}
Use the `tutorial-link` shortcode to render boxes linking to subtutorials. Subtutorials are a great way to group complex content into separate topics which can be studied and shared separately.
{{</ notes >}}


{{< tutorial-link link="tutorial-layout" >}}

---

## Thank you..

{{<unlisted>}}

.. and feel free to post issues [here](https://github.com/Helmholtz-Imaging/workshop-template/issues)!