---
date: 2018-10-06
title: "Coding SuperCollider with sc-hacks"
linkTitle: "Announcing sc-hacks documentation"
description: "Sc-hacks provides shortcuts and other facilities for coding performances in SuperCollider."
author: Iannis Zannos ([@iani](https://iani.github.io))
resources:
- src: "**.{png,jpg}"
  title: "Image #:counter"
  params:
    byline: "Photo: Riona MacNamara / CC-BY-CA"
---

**This is a test blog item as we begin the documentation**

Here we are just testing how to use the docsy theme for making the website with Hugo and deploying it on Netlify.

## One more edit

Here we test how edits update automatically on the local browser via the hugo server.

Here's an image (`featured-sunset-get.png`) that includes a byline and a caption.

{{< imgproc sunset Fill "600x300" >}}
Fetch and scale an image in the upcoming Hugo 0.43.
{{< /imgproc >}}

The front matter of this post specifies properties to be assigned to all image resources:

```
resources:
- src: "**.{png,jpg}"
  title: "Image #:counter"
  params:
    byline: "Photo: Riona MacNamara / CC-BY-CA"
```

To include the image in a page, specify its details like this:

```
{{< imgproc sunset Fill "600x300" >}}
Fetch and scale an image in the upcoming Hugo 0.43.
{{< /imgproc >}}
```

The image will be rendered at the size and byline specified in the front matter.


