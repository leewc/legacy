---
title: META
subtitle: This blog (literally) would not exist without these awesome projects.
meta: off
layout: no-sidebar
permalink: /site-meta/
---

If there's one thing I learnt about creating a static-site with all the bells and whistles, and yet remains clean and elegant, is that out here on the wild wild web, there are so many awesome projects infinite resources to help with setting up a site.

Here's how I set up this little blog of mine, and hopefully this page here not only helps you in making your own website (if you're here wondering how certain things were done you're in the right place.), it also serves as a small thank you of sorts, to all the virtual pats on the back I've graciously received throughout the development of this website. 

Without further ado, curtain calls for all the technologies that made this site possible. 


### Jekyll, the static-site generator

Jekyll is a (very) powerful site generator written in Ruby. It's perfect for creating blogs but works for sites too. Unlike Wordpress or some other content management system (CMS), sites generated with Jekyll have no backend database or other moving parts, only a bunch of files. This makes it really fast and efficient. I only found out about Jekyll after my friend KokHouser mentioned it when his blog launched. After a lot of research and reading the documentation I felt it would be fun to build a blog in Jekyll, a step-up from my blogger.com days where I used to have a blog named LifehackingWithComputergeek. Plus it's designed to work well with a version control system like Git and using Markdown (I use Kramdown) and combined with YAML and Liquid suited pretty much every software developer out there.

You can find the source code for the Jekyll new theme at: [github.com/jglovier/jekyll-new](https://github.com/jglovier/jekyll-new)
You can find the source code for Jekyll at [github.com/jekyll/jekyll](https://github.com/jekyll/jekyll)
And the documentation. I constantly learnt new things from referring to it. Even if it was confusing at times, taking the time to read and understand it really helped. 


### The Helios Theme by HTML5UP

Much as I'm a big fan of customization, it will take me forever to conceive a theme that is as beautiful as this, the Helios Theme by [HTML5UP](http://HTML5UP.net). It is a free HTML5 theme by [n33](n33.co), made responsive using the skel framework which is also by n33 himself. For the unfamiliar, responsive means that the website displays optimally and differently across all devices and different screen sizes. You can find the original theme here (TO LINK)

I've ported the theme to work on Jekyll, which you can find the original source for version 1 here and version 2 here (TO LINK). The first version was a minimal port to Jekyll with syntax highlighting support and implementing the article read time feature and responsive image layout, while the second version has even more features like a scroll to top button, font-awesome renaming to prevent social media blocks which ruins the site layout. These are all tagged so you get downloadable zips and can go ahead and start customizing them.  

I should probably note that the license for the theme is [Creative Commons Attribution 3.0 Unported](http://creativecommons.org/licenses/by/3.0/) which is different from the rest of the website. On that note, all my code changes are released under the MIT license. 


### Font Awesome

Although originally bundled with the Helios Theme, I feel that this deserves it's own mention. Initially when beginning to port the theme over I thought this was an ordinary font, turns out it's actually a ton of icons that are packaged as a font! The non-rasterized property they have (aka they're all vectors), make them scalable and infinitely customizable without worry that the icons come out blur. Not only are they pretty (who doesn't like pretty things?), they're free and open source. Can't beat that.


### Also worth mentioning ...

Armed with only those tools this website would still not be possible without a lot of self discovery, Google-fu and other helpful bloggers, so here's a few more note-worthy mentions that you might be interested in using. (apologies if I missed you out, contact me!)

- The Source Sans Pro font
- [List of Posts by Category](http://christianspecht.de/2014/10/25/separate-pages-per-tag-category-with-jekyll-without-plugins/) by Christian Specht
- [Getting Post thumbnails](https://truongtx.me/2013/01/05/thumbnail-post-list-for-jekyll-bootstrap/) by Trong
- [Liquid Syntax for Designers, by Shopify](https://github.com/Shopify/liquid/wiki/Liquid-for-Designers)
- [Yes We Jekyll](http://yeswejekyll.com/) -- A ton of reading was done from this blog
- [Reading time without plugins](http://carlosbecker.com/posts/jekyll-reading-time-without-plugins/) by Carlos Becker
- [Back to top Button](http://www.jqueryscript.net/other/Minimal-Back-To-Top-Functionality-with-jQuery-CSS3.html) which I adapted by not using the JQuery supplied and instead the Scrolly script included with the theme
- [Responsive Images and Responsive Design](http://webdesignerwall.com/tutorials/5-useful-css-tricks-for-responsive-design) allowed for centered images that scale according to screen size! :)