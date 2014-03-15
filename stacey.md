#Snippets for [Stacey CMS](https://github.com/kolber/stacey)

A few code snippets and mixins to suppliment the [Stacey App documentation](http://www.staceyapp.com/documentation/).

***

	foreach $css do
		<link rel="stylesheet" href="@url" type="text/css">
	endforeach

Creates CSS references for extra CSS files found in the current page's directory. Useful for art-directed pages or a collection of one-off CSS styles.

***

***

	<link rel="canonical" href="http://www.your-website.com/@permalink">
	
Creates a good canonical reference tag for each page.

***

***

	$this->data['@absolute_url'] = 'http://'.$_SERVER['HTTP_HOST'].str_replace('/index.php', '', $_SERVER['PHP_SELF']).'/'.str_replace('./','', $file_path);
	
Creates an absolute image path.
Place inside `app / asset-types / asset.inc.php` file at the end of the `set_default_data` function
[c/o Catherine](https://getsatisfaction.com/stacey/topics/how_can_i_get_absolute_image_path)

***