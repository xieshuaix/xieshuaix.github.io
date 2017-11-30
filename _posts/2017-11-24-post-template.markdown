---
layout:       post
title:        "Post Template"
subtitle:     "Subtitle"
date:         2017-11-24  # Do not enter time accurate to second, that causes issue with time settings of Jekyll
author:       "Shuai"
header-img:   "img/in-post/post-eleme-pwa/eleme-at-io.jpg"
header-mask:  0.3
catalog:      true
multilingual: false
tags:
    - Label 1
    - Label 2
    - Label 3
---

<!-- Example on comment within this file -->
<!-- Ctrl+L to comment/decomment a line-->
<!-- Ctrl+Shift+L to comment/decomment a block -->

## Example on text formatting
<!-- Normal -->
BlaBlaBla
<!-- Italitc -->
*BlaBlaBla*
<!-- Bold -->
**BlaBlaBla**
<!-- Indented block -->
>BlaBlaBla
><br/>
>BlaBlaBla
<br/>

<!-- Bullet points -->
* BlaBlaBla
* BlaBlaBla

<!-- Enumerate -->
1. BlaBlaBla
2. BlaBlaBla

## Example on including an image
![](/img/in-post/post-nextgen-web-pwa/flipkart-3.jpeg)
*Credit to: Hux & [@adityapunjani][i4]*

## Example on including code snippet:
```html
<!-- Example code -->
<meta name="example-code" content="yes">
```

```json
{
  "icons": [{
      "src": "launcher-icon-2x.png",
      "sizes": "96x96",
      "type": "image/png"
   }]
}
```

## Example on citation
This sentence has a [link][1][^1] attached.

---

## Reference
<!-- attach links for [link], will not be displayed -->
[1]: baidu.com "Baidu"

<!-- Below will be displayed under reference  -->
[^1]: baidu.com "Baidu"



<!-- Chinese Version -->
<!-- <div class="zh post-container">
    {% capture about_zh %}{% include posts/2017-07-12-upgrading-eleme-to-pwa/zh.md %}{% endcapture %}
    {{ about_zh | markdownify }}
</div> -->

<!-- English Version -->
<!-- <div class="en post-container">
    {% capture about_en %}{% include posts/2017-07-12-upgrading-eleme-to-pwa/en.md %}{% endcapture %}
    {{ about_en | markdownify }}
</div> -->
