---
title: World War I
layout: base
date: 2026-01-01
summary: A starter site for collections built around things — artefacts, sites, specimens, places — where each object gets its own page and the directory assembles itself.

hero:
  image: /assets/images/backgrounds/wwi-ypres-header.jpg
  alt: Stereograph of trenches at Ypres, produced by the Keystone View Company
  kicker: A collection of artifacts and biographies
  title: World War I
  text: This website is as much a social and culture study of war as it is a military or political study.
  buttons:
    - label: Browse the Objects
      url: /objects
    - label: See the Gallery
      url: /gallery
    - label: See Them on a Map
      url: /map

featured:
  - slug: buddha-head
    label: Sculpture
  - slug: bowl-with-dragons
    label: Ceramics
  - slug: cosmetic-jar
    label: Glass

explore:
  - label: All Objects
    url: /objects
    text: The full grid, assembled from whatever folders exist under objects/.
  - label: Gallery
    url: /gallery
    text: The same objects as a wall of pictures, each at its own proportions.
  - label: Essays
    url: /essays
    text: Thematic threads that read across the objects rather than one at a time.
  - label: Map
    url: /map
    text: Every object that carries geo coordinates in its front matter.
  - label: Instructions
    url: /instructions
    text: How to add an object, and what each front matter field does.
  - label: Documentation
    url: /docs
    text: The whole Xanthan reference, including every component.
---

{% include layout/home-hero.html hero=page.hero %}

## What this template is for

{: .lede}
Use this starter when the object *is* the entry and the writing supports it — a
digital exhibit, a material-culture course, a site survey, a collection
catalogue. Choose the Essay Collection instead when the writing leads and images
illustrate it.

Each object lives in its own folder under `objects/`, with its page and its
images together. The catalogue facts — date, medium, place, coordinates, tags —
live in the front matter of that page, so they are written once and appear
wherever they are needed: on the grid, on the map, in search.

Nothing indexes objects by hand. Add a folder and it appears.

The [essays]({{ site.baseurl }}/essays) are the other half of the arrangement.
An object page describes one thing; an essay follows a motif, a material, or a
gap in the record through several of them. Objects stay independent of the
essays that cite them, so an argument can be added or withdrawn without
disturbing the collection underneath it.

{% include layout/picks.html
  items=page.featured
  collection="objects"
  variant="strip"
  columns=3
  kicker="Sample Objects"
  title="Three stand-ins, here to be replaced."
%}

{% include layout/link-index.html
  links=page.explore
  kicker="Where to go next"
  title="Start with the instructions, then delete these three."
%}

Header image credit: Stereograph of Trenches at Ypres, produced by the Keystone View Company, held by the [National WWI Museum](https://collections.theworldwar.org/argus/final/Portal/Default.aspx?component=AAAS&record=d1a50c22-42c2-4dcc-b05d-2e13e27d6ee8)