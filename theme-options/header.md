# Header

![Customize Header](_images/customize-header.png#alignright)

This panel contains sections which have options that helping you control your site header, like top bar, logo, header icons, header layout... We will have a separated tutorial for controling your site header bellow. At this writing, we only introduce to you the general purposes of sections in this panel.


## Topbar

![Customize Header Topbar](_images/customize-header--topbar.png#alignright)

This section contains options for controling the topbar, like turn it on/off, select topbar layout, set the content for it.

- **Show topbar** - enable or disable the topbar
- **Topbar Color** - select the background color for topbar. There are 2 options for you choose - Dark or Light
- **Topbar Layout** - select layout of topbar. There are 2 options - 1 column (full width) or 2 columns (split topbar into 2 columns).
- **Left Content** - if you select 2 columns layout, you will be able to select which content will be displayed in the left side of topbar. You can choose either "Currency & Language switcher" or "Custom Content". For having currency & language switchers, you need to install [WooCommerce Currency Switcher](https://wordpress.org/plugins/woocommerce-currency-switcher/) and [WPML](https://wpml.org/) plugins. Note that the right content is the **Topbar Menu** which is set in the Menus section.
- **Custom Content** - enter the custom content for the topbar. It will be displayed on the left side if you select **2 Columns** layout and the left content value is **Custom content**. If you select topbar layout is **1 Column**, this content will be displayed centered.


## Header

![Customize Header Header](_images/customize-header--header.png#alignright)

This section contains options for controling how your header display. You can select the header layout, background color, text color, enable sticky header, select menu animation...

In order to help you setup your header easier, we group many options into one option for header layout and more other options for header style:

- **Header Layout** - select the right layout for your site header. There are 6 layouts with diffent elements, structure for each layout.
- **Header Wrapper** - select the width of header container. It can be wrapped or full width.
- **Header Background** - select header background from options: Dark, White, Transparent or Custom.
- **Header Text Color** - select header text color from two options - Dark or Light.
- **Header Hover** - turn on/off the hover effect of the trasnsparent header.
- **Sticky Header** - select the sticky header type or disable sticky header.
- **Menu Hover Animation** - select sub-menu animation when the cursor hover.

> [!NOTE]
> On each individual page, you can override some setting about background color and text color with the help of [Display Settings](page/display-settings.md) meta box.


## Logo

![Customize Header Logo](_images/customize-header--logo.png#alignright)

This section contains options for controling how your site logo. You can select either logo image or logo text and config them.

- **Logo Type** - select logo type either "Image" or "Text".
- **Logo Margin** - this option is used to adjust the logo to the right position you want.

If you select Logo Type as "Image", you will see these options:

- **Logo** - upload your logo image there.
- **Logo Light** - upload your logo which is in light color. When you need this? If you select header background as transparent, you should prepare the main logo in dark color and upload this light version to make sure your logo display well in all situations.
- **Logo Width & Logo Height** - specify the width and height of your logo image. By default, you don't need to enter values for them. The logo will be display in nature dimension. But if you want the logo displays well on retina screens, you should prepare it in double dimension then enter these values as regular dimension. For example, your logo is 140x70, you should design it in 280x140. Then enter the value of width is 140px and height is 70px.

If you select Logo Type as "Text", you will see these options:

- **Logo Text** - enter your branding here. It is usually your site name.
- **Logo Font** - select font's properties for you logo, like Font family, font size, font weight, text transform, letter spacing...


## Header Icons

![Customize Header ](_images/customize-header--icons.png)

Sober theme has options for controlling header icon for each header layout. You can also select the cart icon or upload your own.

- **Header Icons** - this option will show up when you select header layout v1, v2, v3, v6. It allows you to arrange and toggle icons.
- **Header Icons Left & Header Icons Right** - this option will show up when you select header layout v5. It allow you to arrange and toggle header icons on the left and right side of header layout v5.
- **Header Icons Left V4 & Header Icons Right V4** - this option will show up when you select header layout v4. It allow you to arrange and toggle header icons on the left and right side of header layout v4.
- **Shopping Cart Icon Source** - you can select to use a built-in icon from the Sober theme or upload your own icon image.
- **Shopping Cart Icon Behaviour** - select the action when you click on the cart icon. It can open the cart modal or link to the cart page.
- **Whislist Icon Behaviour** - select the action when you click on the wishlist icon. It can open the wishlist modal or link to the wishlist page.
- **Account Icon Behaviour** - select the action when you click on the account (man) icon. It can open the login/register modal or link to the My Account page.


## Search

![Customize Header Search](_images/customize-header--search.png)

This section contains options of the search modal on header. The search modal is the popup for searching products. It will when you click on the search icon on the header. From Sober version 2.0.4, we have added new options for that modal.

- **Search for** - you can select what type of content you want to search for when using this modal. By default, it will search for products. You can select searching for products or posts.
- **Cateogories** - Enter category names, separate by commas. You can leave it empty to get all categories. Enter "0" to disable the category selector. Enter a number to get limited number of top categories.
- **Top Categories** - Enable it if you want to display first level categories only. Please note this option does not work if you enter category names in above option.