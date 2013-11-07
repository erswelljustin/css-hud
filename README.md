CSS HUD
=======

A Simple CSS Heads Up Display

Simply include the hud.css into your project above and then place the following code above all of the elements on your page but directly after the `<body>` tag in your HTML document. There is an inline style to hide the div until needed and called using JQuery for instance

	<div id="hud-overlay" style="display: none">
		<div class="hud">
			<img src="YOUR_LOADER_IMAGE">
			<p>SOME TEXT</p>
		</div>
	</div>
	
I would suggest using the always brilliant Public domain: [http://ajaxload.info](http://ajaxload.info) site to generate the loading image in the color style you prefer. I have included a basic loader for you in this repo.

======

If you want to use jquery for showing this as part of an AJAX event for example, just add the following code to your script

	`$('#hud-overlay').show();`

======

## License ##

Public domain: [http://unlicense.org](http://unlicense.org)

## Acknowledgements ##

Kindly Facilitated by [Create Digital Media](http://createdm.com)

Inspired by [MBProgressHUD](https://github.com/jdg/MBProgressHUD)'s brilliant library for iOS.
