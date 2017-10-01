# CSEL website files

This was the source code for my personal site, which was hosted at https://csel.cs.colorado.edu/~gore/ while I was a student at the [University of Colorado Boulder](http://www.colorado.edu). Upon my graduation, I stopped paying tuition, and the site no longer exists.

## Files

* index.html: The landing page. This site, like the rest, is pure HTML and CSS. The title, including a "Hello, world" message, was written in the typewriter-like Fira Mono, evoking both coding and my undergraduate studies in journalism. The rest of the text was in Lato.

* mike.html: This was my "About me" page, which I updated a few times over the years.

* readingpicks.html: I wanted to have something unique on my site, so I kept a list of great things I'd read online recently, such as news articles and speeches. I kept a link to the most recent one on my index page, and the archives were here. I kept these in sync manually, which was kind of silly, but worked.

* second.html: I had a page I made for my wife and I's second anniversary. There was no link on the homepage; you had to know the URL, which you can probably guess from the name of the file.

* template.html: This was a template file I used whenever I wanted to make a new page. I didn't end up doing that as often as I thought. The line about viewport device-width is, I think, what made the text reflow nicely on mobile.

* mystyle.css: My site-wide CSS. I must have followed a demo that named its CSS file "mystyle.css" because that's an underwhelming name. No real tricks there, except I used large body text, following the sensible recommendations at [Butterick's Practical Typography](http://practicaltypography.com). Oh, and going "max-width: 640px" kept it from looking too bad at full-screen on a desktop.

* README.md: This very file!

* Hidden files:
 * sync.sh: I .gitignored this file, which was simply an scp command to sync files to my server. It took me a while to figure out exactly how to write an scp command and I didn't want to have to do it again. Turns it out it's easy once you understand Unix filesystem conventions, which of course I didn't at the time I was looking up a tutorial. This is depressingly common for learning to code.
 * hidden.txt: I had a hidden page on my site! It was mostly a Neal Stephenson quote and the date I put the page up. Don't know if anyone ever found it. (The same goes for index.html. 😉)
