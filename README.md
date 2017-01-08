# Media Expressions Specification [<img src="https://rawgit.com/jonathantneal/media-expressions-spec/gh-pages/css-logo.svg" alt="CSS Logo" width="90" height="90" align="right">][Media Expressions Specification]

[![Build Status][cli-img]][cli-url]
[![Licensing][lic-img]][lic-url]
[![Changelog][log-img]][log-url]

The [Media Expressions Specification] lets you use media queries within values in CSS.

```css
body {
	font-size: media(
		16px,
		(min-width:  600px) 18px,
		(min-width: 1000px) 20px
	);
}
```

### Prollyfill

You can try the `media()` function right now with [CodePen], or use it in your own projects using the [Media()] plugin.

[cli-url]: https://travis-ci.org/jonathantneal/media-expressions-spec
[cli-img]: https://img.shields.io/travis/jonathantneal/media-expressions-spec.svg
[lic-url]: LICENSE.md
[lic-img]: https://img.shields.io/npm/l/media-expressions-spec.svg
[log-url]: CHANGELOG.md
[log-img]: https://img.shields.io/badge/changelog-md-blue.svg

[Media Expressions Specification]: https://jonathantneal.github.io/media-expressions-spec/
[Media()]: https://github.com/jonathantneal/postcss-media-fn
[CodePen]: http://codepen.io/pen?template=dNyWaX
