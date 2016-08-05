<p class="lede">This blog is a journal (of sorts). It focuses on an eclectic range of subjects clustered around two broad themes: technology and entrepreneurship, and private equity and venture capital.</p>

### Design Inspiration

> Good artists copy, great artists steal.
> <footer><span class="author">Pablo Ruiz Picasso</span></footer>

No design emerges, like Athena, fully-formed from the mind of its creator. I drew inspiration from a number of sources when designing this blog, and in the spirit of full disclosure, I want to acknowledge the influences that have shaped this design.

This blog draws some of its inspiration from Dan Cederholm’s [SimpleBits](http://simplebits.com/), which remains a timeless example of minimalist elegance. It is also shaped by [Mark Boulton](http://www.markboulton.co.uk/)’s excellent guide to typography, which first showed me the importance of vertical rhythms and proper use of ligatures, hanging punctuation (which, alas, is still difficult to do consistently on the web without using Javascript), and proper typographic hierarchy. I also borrowed Boulton’s single-column content layout. The circular profile picture was borrowed from an earlier version of Garrett Murray’s [Maniacal Rage](http://log.maniacalrage.net/).

### Typography

The headings on this blog are typeset in [Gotham](http://www.typography.com/fonts/gotham/overview/), a sans serif typeface from [Hoefler & Co.](http://www.typography.com/) that evokes the no-nonsense, brash spirit of America’s metropolises from the 1920s to the 1960s.  To me, Gotham represents a mixture of forthrightness and approachability, a typeface that asserts itself without being overbearing, and evokes the entrepreneurial spirit of North America.

[Mercury Text](http://www.typography.com/fonts/mercury-text/overview/), also from Hoefler &#38; Co., is used for the body copy. Mercury Text, a serif typeface  inspired by 18<sup>th</sup> century European punchcutters, is a compact typeface that works well at various body copy sizes. It evokes a sense of *history*, of thick books and old magazines, and contrasts well with the bold sans serif letters of Gotham.

Parenthetically, I _am_ aware that Gotham was the signature font of the Obama 2008 and 2012 presidential campaigns, while the Romney 2012 campaign used [Mercury Display](http://www.typography.com/fonts/mercury-display/overview/)—the inspiration for Mercury Text—for its headlines. What can I say? I like the contradiction.

The typographic scale was constructed using the excellent classical typographic scale, as recorded by Bringhurst in <cite>The Elements of Typographic Style</cite>, with some interpolations to fill in certain gaps in the classical scale, as suggested by [Spencer Mortensen](http://spencermortensen.com).

### Technical Details

**Warning:** Contains serious geekery. Read on at your peril.

This weblog is powered by [Ghost](https://ghost.org/), a dedicated blogging tool written in [node.js](http://nodejs.org). It is hosted on [Ghost(Pro)](https://ghost.org/pricing/). (Why a hosted solution rather than hosting it on a <abbr title="Virtual Private Server">VPS</abbr> that you manage? The short answer is so that I can focus on writing rather than on managing, securing, and optimizing a [Ubuntu 16.04 LTS](http://www.ubuntu.com/server) server stack with [Nginx](http://nginx.org) proxying to a local installation of Ghost.)

Static media files including images, <abbr>PDF</abbr>s, and spreadsheets are served through [Amazon Web Service S3](https://aws.amazon.com/s3/), as part of my exposure to public cloud computing. I used to use a [Linode](https://www.linode.com) <abbr title="Virtual Private Server">VPS</abbr> running Ubuntu 14.04 LTS and Nginx to serve these, but decided to swap it for something less cumbersome.

The fonts used on this site are served through [Cloud.typography](http://www.typography.com/cloud/welcome/), a web fonts service from Hoefler &#38; Co.

The theme used for this blog is a custom minimalist theme, called Aenea, that I created specifically for this blog. The source code for this theme is available (for reference and learning purposes only) on [GitHub](https://github.com/lucasktlee/aenea).

I use [Sass](http://sass-lang.com/) as my <abbr title="Cascading Style Sheets">CSS</abbr> preprocessor. (The previous theme used [stylus](https://learnboost.github.io/stylus/), but I found myself drawn to the more active community of Sass users because I did not want to have to re-invent the wheel on a regular basis.) Ghost uses the excellent (if slightly more verbose than I would like) [Handlebars](http://handlebarsjs.com) templating language for its templates. I use [Picturefill](http://scottjehl.github.io/picturefill/) for responsive images and [Prism](http://prismjs.com/) for code highlighting.

The code for this blog is written with [Atom](https://atom.io) on an [Apple Mac](http://www.apple.com/mac/). Posts are written with Atom on a Mac.
