---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Gallery Demo"
subtitle: ""
summary: ""
date: 2020-10-06T17:12:01.815Z
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []

gallery_item:
- album: gallery1
  image: theme-ocean.png
  caption: Write your image caption here
---
## Gallery
{{< gallery album="gallery1" >}}

## Grouped images
{{< figure src="theme-ocean.png" title="A caption" lightbox-group="group1">}}
{{< figure src="theme-dark.png" title="Another caption" lightbox-group="group1">}}
{{< figure src="theme-apogee.png" title="another2 caption" lightbox-group="group1">}}

## Single image
{{< figure src="theme-apogee.png" title="Single image">}}

## SVG
{{< figure src="SVG_logo_h.svg">}}

## External SVG
{{< figure src="https://upload.wikimedia.org/wikipedia/commons/6/67/Firefox_Logo%2C_2017.svg">}}
