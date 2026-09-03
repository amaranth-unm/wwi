---
title: Food and Nutrition During WWI
layout: base
author: Your Name
date: 2026-01-01
position: 2
header-image: /essays/food-and-nutrition/images/maconochie-tin-resized.jpg
header-title: Food and Nutrition
header-tier: banner
header-position: center
thumbnail: /objects/hardtack-bread/images/hardtack-bread.jpg
summary: Battle conditions and the larger economic context greatly affected food and nutrition during WWI.
tags:
  - food
  - daily-life

objects:
  - slug: pow-rations
    label: POW rations
  - slug: hardtack-bread
    label: Hardtack bread
---

# Food and Nutrition During WWI

{: .lede}
This is sample content. Replace it with your own argument and images from your research. Every object in this collection is incomplete, and the incompleteness is not
damage — it is the ordinary condition of surviving. The colour has gone off one,
the contents out of another, and the practice that made sense of the third has
left no record at all. An essay can say what an object page cannot: that the
absence is itself evidence, and of what.

This is sample content. Replace it with your own argument and images from your research.

{% include layout/picks.html
  items=page.objects
  collection="objects"
  variant="strip"
  columns=2
  kicker="Objects in this essay"
  title="These two objects reveal much about nutrition in WWI."
%}

## Attitudes Toward Food Consumption

The war also affected attitudes toward food consumption on the home front.

{%
include scrollybox/bg.html
above-box-space="100vh"
below-box-space="100vh"
height="250vh"
image-path="/essays/food-and-nutrition/images/us-food-admin.jpg"
box-align="center"
box-content="
### The U.S. Food Administration agency
On the home front, a government agency called the U.S. Food Administration produced posters and other documents to help conserve needed food supplies for the troops in Europe."
%}




## Hardtack Bread

The [hardtack bread]({{ site.baseurl }}/objects/hardtack-bread) that soldiers ate was not very tasty.

{% include typography/pullquote.html
  text="Soldiers in WWI received rations. This quote is in larger type and calls attention to something that also appears in the main text of the webpage."
%}

Here is more text that you will replace.

## POWs

The [rations for POWs]({{ site.baseurl }}/objects/pow-rations) varied in quantity and quality.


{% include images/figure-wrap.html
  image-path="/objects/pow-rations/images/pow-rations.jpg"
  caption="A photograph of POW rations. [National WWI Museum](https://collections.theworldwar.org/argus/final/Portal/Default.aspx?component=AAAS&record=34e5ed84-43c5-4ff4-9a38-bd627e803e82), open access."
  alt-text="A photograph of POW rations."
  image-position="right"
  image-width="45%"
  text="The text you put here sits beside the image, not below it. Good for introductory paragraphs, a key argument tied to a specific image, or whenever the visual and the words need to be read together. Content that follows the include starts at full width below both columns."
%}



Here is more sample text that you would replace.

## Writing your own

This essay is in a folder under `essays/` with an `index.md` in it. The two habits worth keeping:

**Name the objects you are arguing from.** Link them in the prose, and list them
in the `objects:` block in this page's front matter so the strip above builds
itself. If you rename an object's folder, the strip prints a visible warning
rather than failing silently.

**Do not repeat the catalogue.** The object page already says what the thing is,
where it was made, and what it is made of. The essay should say what it is
evidence *for*.

---

## Bibliography

- Author. *Title*. Publisher, Year.
