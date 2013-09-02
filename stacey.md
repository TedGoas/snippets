#Snippets for [Stacey CMS](https://github.com/kolber/stacey)

A few code snippets and mixins to suppliment the [Stacey App documentation](http://www.staceyapp.com/documentation/).

***

	foreach $css do
		<link rel="stylesheet" href="@url" type="text/css">
	endforeach

Creates CSS references for extra CSS files found in the current page's directory. Useful for art-directed pages or a collection of one-off CSS styles.

***