---
title: Add html map widget to webpage
author: Hansen Johnson
date: '2018-03-04'
categories:
  - Code
tags:
  - data-visualization
  - html
slug: add-html-map-to-webpage
header:
  caption: ''
  image: ''
summary: Quick example of how to embed an html widget, in this case a map, into a
  webpage
---

Here's a quick example for how to embed an html widget, in this case an interactive map of right whale survey results, into any webpage. Simply copy and paste the following `html` line into the webpage (html or md) where you would like the map to show up. This makes use of two different `html` tags, an `iframe`, which allows you to embed content, and a `div` which basically lets you define certain aspects of the things inside it (in this case, it's used to center the iframe). For more information on these and other tags, and much more, check out the great resources at [w3schools.com](https://www.w3schools.com/)

```
<div align="center">
  <iframe src="https://leviathan.ocean.dal.ca/server_index/whale_map.html" width="80%" height="540"></iframe>
</div>
```

<div align="center">
  <iframe src="https://leviathan.ocean.dal.ca/server_index/whale_map.html" width="80%" height="540"></iframe>
</div>

That's it! Now you can easily add that map, or any other html widgets with a known url, to any webpage! For more information about this map in particular, check out our lab's [data visualization webpage](http://leviathan.ocean.dal.ca/).
