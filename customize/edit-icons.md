# Change theme's icons


### Manage header icons

![Manage header icons](https://gcdnb.pbrd.co/images/wKLgaJSlP7qg.png?o=1#alignright)

The Sober theme has options to manage the header icons. You can enable/disable icons, or re-arrange them. This option can be found in **Appearance > Customize > Header > Header Icons**.

In order to disable/enable an icon, you can click on the "eye" icon.

If you want to change the order of icons, just drag them in the order you want.

Some icons require your website has plugins installed to be visbile and work. They are wishist, currency switcher, and language switcher. Therefore you can also disable these icons by deactivating the plugin.



### Change the cart icon


![Change shopping cart icon](https://gcdnb.pbrd.co/images/DjzvpZvLxKhX.png?o=1#alignright)

This theme provides options to change some header icons like the cart icon. You can find these options in **Appearance > Customize > Header > Header Icons**.

You can use a predefined icon of the theme, or upload your icon image.



### Change other icons


The theme cannot provide options to change all icons of the theme. However it is still possible to change them with custom code. This is the PHP to change a SVG icon of this theme.

```
add_filter( 'sober_svg_icon', function( $svg, $args ) {
	if ( 'icon-name' == $args['icon'] ) {
		$svg = 'your svg icon code';
	}

	return $svg;
}, 10, 2 );
```

For example, to change the account icon, the `icon-name` is `user-account-people`. You can easily find the `icon-name` is the file name of svg files in folder **images/svg**.