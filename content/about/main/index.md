---
## Configure page content in wide column
title: "A little about me..." # leave blank to exclude
number_featured: 1 # pulling from mainSections in config.toml
use_featured: false # if false, use most recent by date
number_categories: 3 # set to zero to exclude
show_intro: true
intro: |
  Something something something...
  
  Some more stuff about me...
  
  Here is an example of an embedded YouTube video. Hugo apparently already has a built-in YouTube shortcode.
  
  {{< youtube bzv2gSGJPCY >}}
  
  <br>
  <br>
  
  Here is an example of an embedded ArcGIS Story Map. For the Story Map, I had to create a storymap.html file in layouts/shortcodes.
  
  {{< storymap src="https://storymaps.arcgis.com/stories/e9a008c4129341d7b4f49ddd731def37" >}}

show_outro: true
outro: |
  Insert some outro text here?


---

** index doesn't contain a body, just front matter above.
See about/list.html in the layouts folder **