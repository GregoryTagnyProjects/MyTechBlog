---
weight: 4
title: "Building your Github page with Hugo"
date: 2020-03-03T16:29:41+08:00
lastmod: 2020-03-03T16:29:41+08:00
draft: false
author: "Gregory"
authorLink: "https://www.linkedin.com/in/gregorytagny/"
description: "Hugo + Github"
images: ["/images/theme-documentation-extended-shortcodes/featured-image-preview.jpg"]

tags: ["Web Design","Front-End"]
categories: ["web"]
featuredImage: "/images/theme-documentation-extended-shortcodes/featured-image.jpg"
featuredImagePreview: "/images/theme-documentation-extended-shortcodes/featured-image-preview.jpg"

lightgallery: true
---

A quick and simple step-by-step guide on how to host your Hugo website on Github.  

<!--more-->
{{< admonition warning >}}
Sorry, this page is still under construction. Subscribe to the newsletter to stay updated. :innocent:

## 1 figure {#figure}

Example `figure` input:

```markdown
{{</* figure src="/images/theme-documentation-built-in-shortcodes/lighthouse.jpg" title="Lighthouse (figure)" */>}}
```

The rendered output looks like this:

{{< figure src="/images/theme-documentation-built-in-shortcodes/lighthouse.jpg" title="Lighthouse (figure)" >}}

The corresponding HTML code looks like this:

```html
<figure>
    <img src="/images/theme-documentation-built-in-shortcodes/lighthouse.jpg"/>
    <figcaption>
        <h4>Lighthouse (figure)</h4>
    </figcaption>
</figure>
```
