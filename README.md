# Font Awesome SVGs

Doing a lot of prototyping in the past, having [Font Awesome](http://fontawesome.io/) as part of my front end starter files was always really handy for quickly adding icons when I was building a UI.

Nowadays we are more aware that using a font to represent icons isn’t necessarily the most accessible thing to do for everyone, [as Serend explains here](https://www.youtube.com/watch?v=9xXBYcWgCHA).

So as I’m whipping up a website right at this moment I thought it a good opportunity to take the first steps to swap out the font for svgs. So…

### [Here’s a repo with font awesome icons as svgs](https://github.com/Rumyra/Font-Awesome-SVGs)

I forked the Font Awesome repo so I can keep it as up to date with the original as I can.

I added an SVG folder to add all the generated glyphs to.

I used [font blast](https://www.npmjs.com/package/font-blast) to generate SVGs from a font, a la [Sara Soueidan mentions in her blog post here](https://sarasoueidan.com/blog/icon-fonts-to-svg/).

To include the SVG’s I used the CSS Inline SVG Sprites method, [again described by Sara here](https://24ways.org/2014/an-overview-of-svg-sprite-creation-techniques/). It seemed the easiest to integrate with the set up I already had, as I was using classes to add icons to elements.

The most long winded part was making sure I had all the correct icons - I think a good addition to this repo would be a generated spite sheet with stylesheet companion and easy reference classes. I’ve opened an issue 😎

———————————————

All Font Awesome licensing etc… still applies. Info etc… is in the origin [readme here](https://github.com/FortAwesome/Font-Awesome)