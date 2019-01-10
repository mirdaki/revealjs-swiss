# reveal.js Swiss Theme

[Swiss design](https://en.wikipedia.org/wiki/International_Typographic_Style) is one of my favorite design styles, so it naturally made sense to make a Swiss inspired design for [reveal.js](https://github.com/hakimel/reveal.js) (a really cool web based presentation framework). You can checkout an example of it [here](https://mirdaki.github.io/revealjs-swiss).

Both the [Jekyll Swiss theme](https://broccolini.net/swiss/) and the [reveal.js theme built by Myplanet](https://medium.com/myplanet-musings/building-a-responsive-reveal-js-theme-399179632cc6) were used as reference for this theme.

## Usage

To use, copy the `swiss.scss` file and the `swiss-colors` folder from `css/theme/source` into your own reveal.js presentation.

To change the color style, update the `@import "swiss-colors/COLOR";` on line 19 of the `swiss.scss` with respective color you would like.

Finally, update your `index.html` to use `css/theme/swiss.css` as your theme.

Optionally, grab a code syntax highlighter theme from [highlight.js](https://highlightjs.org/) and include it as a stylesheet in your `index.html`. 

## Future Work

This is a first release, so expect it to be rough around the edges. 

Contributions are welcome!

Things to work on:
- Better scalability across device form factors
- Implement different types of slide formats
	- Two columns slide
	- Title slide
	- Section slide
	- Interactive code slide
- Improve the UX with adding the so someone would only need to download one CSS file
	- While also not having to repeat code too much 
- More/better color options 
- Provide slide examples in the README

## License

This project's code is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.