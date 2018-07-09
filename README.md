# Slickmap CSS

**A Visual Sitemapping Tool for Web Developers**

Created by Matt Everson of Astuteo  
[https://www.astuteo.com/slickmap](https://www.astuteo.com/slickmap)

### Improvements in Version 2

- Four levels deep! Upgraded from a previous maximum of three.
- Flexbox! Floats and hardcoded column widths have been eliminated.
- No images! All visual elements are now CSS-driven.
- Responsive! Maybe a pointless endeavor, but woo hoo.
- New color scheme! Updated version of original skin also available.

### How To Use

1. Create an HTML file with an unordered list of links. Slickmap was
   designed to style actual linked navigation, not simply lists, so make
   sure to include anchor tags. See index.html for the correct formatting.

2. Apply slickmap.css as you would any other stylesheet, using it for both
   "screen" and "print" media as seen here:

   `<link rel="stylesheet" type="text/css" media="screen,print" href="slickmap.css" />`

3. Within your HTML file, the link to your home page should be at the top
   of the unordered list and have the id of `#home`. This is required to pull
   the home page link out above the rest of the site tree.

4. Responsive media queries are provided at the end of slickmap.css to optimize
   the layout for the exact number of columns you require. To do it, remove or
   comment out the queries that go beyond the number of columns you need. For
   example if your sitemap is 4 columns, remove queries for columns 5 and over.

### Donations

Slickmap is entirely free for you to download and use, modify for your own applications, or otherwise make millions from. That said, if you happen to find yourself so overwhelmed with gratitude that you want to buy me a beer with Bitcoin, there’s no doubt the gesture will be appreciated. Either way, enjoy. To donate, shoot those digital dólares to any address below:

- **BTC:** 3PC7sseUcTFRDG5SuP713rHMp51Yp79Ynt
- **LTC:** MDoZaCqB57PPWZgrSkfvoRUiQkn14Mkqah
- **ETH:** 0x6f62d4F65Ed04E0357fFC49663B7fc18829fAffC
