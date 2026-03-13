# General

![Customize General](_images/customize-general.png#alignright)

This panel contains sections which have general options for:

- **Site Identity**
- **Homepage Settings**
- **Preloader**
- **Popup**
- **Maintenance**


## Site Identity

![Cusomize General Site Identity](_images/customize-general--site_identity.png#alignright)

This section contains genral options for your website like: site title, site description, favicon.

- **Site Title** - Text box for site title
- **Tagline** - Text box for tag line/aka site description
- **Site Icon** - The Site Icon is used as a browser and app icon for your site. Icons must be square, and at least 512 pixels wide and tall. Click Select Image to open the Media Library. Select an image from it or upload the new image from Upload Files Tab screen and click Select button at the bottom right.


## Homepage Settings

![Cusomize General Statuc Front Page](_images/customize-general--static_front_page.png#alignright)

You site's home page can either contain your latest posts or display a static page or post. You can set it here or in **Settings > Reading**.

- **Your latest posts** - select this to show your latest posts in your home page
- **A static page** - select either a Front page or Posts page. Refer Creating a Static Front Page for more detail information and available combination.

	- **Front Page** - select a page for your front page.
	- **Posts Page** - select a page for your blog.


## Preloader

![Cusomize General Preloader](_images/customize-general--preloader.png#alignright)

From the version 1.2.0, Sober supports preloader. Preloader is a layer display over the site when it is loading. In this section, you will see following options.

- **Enable Preloader** - enable or disable the preloader. It is disabled by default.
- **Background Color** - select the background color for the preloader.


## Popup

![Cusomize General Popup](_images/customize-general--popup.png#alignright)

This section contains options for the newsletter popup.

- **Enable Popup** - enable or disable the popup. It is disable by deafult.
- **Popup Layout** - select the layout of the popup. Sober supports 2 layouts. The first layout doesn't support image. The second layout supports image.
- **Overlay Color** - select the background color of the overlay. It is the dark layer behind the newsletter form.
- **Banner Image** - upload the banner image. This option only appear if you select the second popup layout.
- **Popup Content** - then content of popup. It allows HTML and shortcodes.
- **Frequency** - enter a number of the day that the popup will not show up to the same visitor until this much day has passed.
- **Popup Visible** - select whenever the popup show up. You can select to show the popup right after page has loaded. Or wait for seconds after page has loaded completely.
- **Delay Time** - enter a number of seconds that popup will wait before showing up.


## Maintenance

![Cusomize General Maintenance](_images/customize-general--maintenance.png#alignright)

This section containts options to turn your site into the maintenance mode. Its allows you to display a user-friendly notice to yor users instead of a broken site during website maintenance. When you are logged as an administrator, you can visit your website normally.

- **Enable Maintenance Mode** - turn on/off the maintenance mode on your site.
- **Mode** - select the suitable mode for your site. There are 2 options for you chose from, _Maintenance_ or _Coming Soon_.
	- **Maintenance** - select this mode if you need to work on building/fixing your site for a long perior of time. It return the HTTP 503 to browsers and bots.
	- **Coming soon** - select this mode if you just need to close your website to vistor in a short perior of time. It return the HTTP 200 to browsers and bots.

	This option help your site always be friendly to search bots and don't affect to your site SEO ranking. You can learn more about these status codes in [this link](https://yoast.com/http-503-site-maintenance-seo/).

- **Mainenance Page** - select the page you designed to display as your maintenance page.
- **Maintenance Page Layout** - select the layout for the maintenance page. This option only works if the maintenance page use the default tempalte.