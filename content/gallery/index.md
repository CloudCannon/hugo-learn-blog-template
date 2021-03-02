---
title: "Gallery"
date: 2021-03-03T12:42:53+13:00
draft: true
resources:
- alt: Kea on a snowy mountain
  src: images/kea.jpg
- alt: Kaka in profile
  src: images/kaka.jpg
- alt: Kereru in a tree
  src: images/kereru.jpg
- alt: Hoiho with eyes closed
  src: images/hoiho.jpg
- alt: Pukeko on a wooden deck
  src: images/pukeko.jpg
- alt: Tui in a harakeke/NZ flax bush
  src: images/tui.jpg
---

# Gallery - with shortcodes

## Built-in shortcodes

### YouTube
{{< youtube 7W7hEUGtv4U >}}  
{{< youtube E3a88_SjJR0 >}}

### Figure
{{< figure src="./images/kea.jpg" title="Kea on a mountain" >}}

### Highlighting
HTML:
{{< highlight html >}}
<div>
  <p>Lorem ipsum.</p>
</div>
{{< /highlight >}}  

JavaScript:
{{< highlight js >}}
// All highlighting options:
// https://gohugo.io/content-management/syntax-highlighting/#list-of-chroma-highlighting-languages
const add = (a, b) => (a + b);
console.log(add(1, 2));
{{< /highlight >}}

## Custom shortcode
### With figures
{{< gallery figures=true >}}
### Without figures
<!-- Leaving out "figures" will also be considered "false" -->
{{< gallery figures=false >}}