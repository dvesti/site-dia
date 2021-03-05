---
title: "Search Results"
sitemap:
  priority : 0.1
---

Results from static site search implemented using _Fusejs_, _jquery_
and _mark.js_. -- [Source](https://gist.github.com/eddiewebb/735feb48f50f0ddd65ae5606a1cb41ae)

[//]: # "Exported with love from a post written in Org mode"
[//]: # "- https://github.com/kaushalmodi/ox-hugo"


<div id="search-results"></div>
<script id="search-result-template" type="text/x-js-template">
    <div id="summary-${key}">
        <h3><a href="${link}">${title}</a></h3>
        <p>${snippet}</p>
    </div>
</script>  
