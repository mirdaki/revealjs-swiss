# reveal.js Swiss Theme

[Swiss design](https://en.wikipedia.org/wiki/International_Typographic_Style) is one of my favorite design styles, so it naturally made sense to make a Swiss inspired design for [reveal.js](https://github.com/hakimel/reveal.js) (a really cool web based presentation framework). You can checkout an example of it [here](https://mirdaki.github.io/revealjs-swiss).

Both the [Jekyll Swiss theme](https://broccolini.net/swiss/) and the [reveal.js theme built by Myplanet](https://medium.com/myplanet-musings/building-a-responsive-reveal-js-theme-399179632cc6) were used as reference for this theme.

## Usage

To use, copy the `swiss.scss` file and the `swiss-colors` folder from `css/theme/source` into your own reveal.js presentation.

To change the color style, update the `@import "swiss-colors/COLOR";` on line 19 of the `swiss.scss` with respective color you would like and regenerate the CSS (you will probably have to switch to the gh-pages branch to generate the file).

Finally, update your `index.html` to use `css/theme/swiss.css` as your theme.

Optionally, grab a code syntax highlighter theme from [highlight.js](https://highlightjs.org/) and include it as a stylesheet in your `index.html`. 

## Future Work

This is a first release, so expect it to be rough around the edges. 

Contributions are welcome! Check out the [1.0.0 milestone](https://github.com/mirdaki/revealjs-swiss/milestone/1) to see what should be done first.

## License

This project's code is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
