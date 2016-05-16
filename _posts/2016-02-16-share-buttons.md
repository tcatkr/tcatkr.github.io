---
layout: post
title: Share buttons implemented!
subtitle: Another little tweak to this blog
tags: Github Jekyll
---
Share buttons are another feature that I missed from dinamically generated blogs.
On <a href="https://wordpress.com/" target="_blank">Wordpress</a>, for example, plugins are available that do this automatically, while on <a href="https://www.tumblr.com/" target="_blank">Tumblr</a> or other platforms you can easily find add-ons that let you share your pages and posts easily.

Since I am using <a href="https://jekyllrb.com/" target="_blank">Jekyll</a>, a static web site generator, and I am letting <a href="https://pages.github.com/" target="_blank">GitHub pages</a> generate my blog, a tiny little bit of tweaking was required to add this feature.

1. Go to the <a href="https://simplesharingbuttons.com/" target="_blank">Simple Sharing Buttons Generator</a> and follow the easy steps to generate your html code and CSS code.
2. Add the CSS code to the blog's stylesheet.
3. Download the icons, upload them to a folder of the blog on github (or on your website if self-hosted).
4. Grab the html code, paste it on a .txt file and change the src attribute of each icon so it points to the correct folder.
5. Now, this code will share the main site to any of the selected social media. The href attribute needs to be changed so the share button works for each blog post. I have done so by tweaking the urls based on <a href="https://superdevresources.com/share-buttons-jekyll/" target="_blank">this tutorial</a>.
6. Make a "share.html" page and place it into the "_include" folder of the blog. Paste the fixed code into the page and save. Here is how mine looks:
<script src="https://gist.github.com/Melyanna/f58aea50ad8dc533d8f1.js"></script>
7. Add the "share.html" page to the post and page layout. 
<script src="https://gist.github.com/Melyanna/633b1e3dbc06f466c027.js"></script>

And done!
