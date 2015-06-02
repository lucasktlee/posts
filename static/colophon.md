<p class="lede">This blog is a journal (of sorts). It focuses on an eclectic range of subjects clustered around two broad themes: technology and entrepreneurship, and private equity and venture capital.</p>

### Design Inspiration

> Good artists copy, great artists steal.
> <footer><span class="author">Pablo Ruiz Picasso</span></footer>

No design emerges, like Athena, fully-formed from the mind of its creator. I drew inspiration from a number of sources when designing this blog, and in the spirit of full disclosure, I want to acknowledge the influences that have shaped this design.

This blog is inspired, in part, by [Mark Boulton](http://www.markboulton.co.uk/), whose writings on typographic scales and grids influenced how I approached the typesetting and typographic layout. It also draws inspiration from the long-form article layout at [Medium](http://medium.com/), which I find to be one of the better approaches to displaying long-form content on the web. I first spotted the circular, centered profile photo on Garrett Murray's [blog](http://log.maniacalrage.net/) quite some time ago, and loved it so much that I decided to incorporate it into this design. The [Clonium](https://github.com/cparaiso/clonium/) theme from [Chris Paraiso](http://blog.chrisparaiso.com/) also provided a starting point for me when trying to craft a minimalist custom theme for Ghost. 

### Typography 

The headings on this blog are typeset in [Gotham](http://www.typography.com/fonts/gotham/overview/), a sans serif typeface from [Hoefler & Co.](http://www.typography.com/) that evokes the no-nonsense, brash spirit of America’s metropolises from the 1920s to the 1960s.  To me, Gotham represents a mixture of forthrightness and approachability, a typeface that asserts itself without being overbearing, and evokes the entrepreneurial spirit of North America.

[Mercury Text](http://www.typography.com/fonts/mercury-text/overview/), also from Hoefler & Co., is used for the body copy. Mercury Text, a serif typeface  inspired by 18<sup>th</sup> century European punchcutters, is a compact typeface that works well at various body copy sizes. It evokes a sense of *history*, of thick books and old magazines, and contrasts well with the bold sans serif letters of Gotham. 

Parenthetically, I _am_ aware that Gotham was the signature font of the Obama 2008 and 2012 presidential campaigns, while the Romney 2012 campaign used [Mercury Display](http://www.typography.com/fonts/mercury-display/overview/)—the inspiration for Mercury Text—for its headlines. What can I say? I like the contradiction. 

### Technical Details 

**Warning:** Contains serious geekery. Read on at your peril.

This weblog is powered by [Ghost](https://ghost.org/), a dedicated blogging tool written in [node.js](http://nodejs.org). It is hosted on [Ghost(Pro)](https://ghost.org/pricing/). (Why a hosted solution rather than hosting it on a <abbr title="Virtual Private Server">VPS</abbr> that you manage? The short answer is so that I can focus on writing rather than on managing, securing, and optimizing a [Ubuntu 14.04 LTS](http://www.ubuntu.com/server) server stack with [Nginx](http://nginx.org) proxying to a local installation of Ghost.)  

The fonts used on this site are served through [Cloud.typography](http://www.typography.com/cloud/welcome/), a web fonts service from Hoefler & Co.

The theme used for this blog is a custom minimalist theme, called Sisirinah, that I created specifically for this blog. The source code for this theme is available (for reference and learning purposes only) on [GitHub](https://github.com/lucasktlee/sisirinah).

In keeping with the whole node.js theme, I use [stylus](http://learnboost.github.io/stylus/) as my <abbr title="Cascading Style Sheets">CSS</abbr> preprocessor. Ghost uses the excellent (if slightly more verbose than I would like) [Handlebars](http://handlebarsjs.com) templating language for its templates. I use [Picturefill](http://scottjehl.github.io/picturefill/) for responsive images.

The code for this blog is written in [Sublime Text](http://www.sublimetext.com/) on an [Apple Mac](http://www.apple.com/mac/). Posts are written with [Sublime Text](http://www.sublimetext.com/) on a Mac. 