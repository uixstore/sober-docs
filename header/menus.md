# Menus

Menus are the default part of any WordPress site. If you are new with WordPress, we recommend you take a look at this guide firstly - [WordPress Menu User Guide](https://codex.wordpress.org/WordPress_Menu_User_Guide).


## Menu Locations

In Sober theme, there are 6 menu locations:

- **Primary Menu** - this is the main menu of your website.
- **Secondary Menu** - in case you choose header layout __Header V4__, your header will display 2 menus with logo at the center of primary menu and secondary menu.
- **Topbar Menu** - this menu will be display in the right side of your topbar. As we wrote in the __Topbar__ section, you need enable topbar first, then select __Topbar Layout__ as "2 Columns" first.
- **Footer Menu** - this is left menu in the footer.
- **Footer Socials** - it is displayed in the right side of site footer. This menu only displays social icons base on URLs you enter.
- **Mobile Menu** - this is the menu for display on mobile devices. If this menu is not set, it will use __Primary Menu__ for mobile menu. Why you need this? Because of the primary menu support mega menu on large screens, therefore you should create another menu for mobile. Of course, theme will remove all mega menu style if you still using the primary menu for mobile.


## Setup Mega Menu

Sober theme come with a built-in Mega menu. It means you don't need to purchase or install extra plugin for this feature. To setup mega menu, please go **Appearance > Menus** and select menu you want to edit. Please note that mega menu doesn't support config in Customizer.

A mega menu can ben enabled on every first level menu item. This image can show you what is menu item level:

![Menu levels](_images/menu-levels.png)

We will guide you how to setup a mega menu:

**Step 1**: Select top level (Level 1) menu item that you want to setup mega menu for it. You will see a new _Settings_ link added to every menu item. Click to that _Settings_ link, a new popup will show up. Please note with different menu item levels, different popups will appear.

![Menu settings](_images/mega-menu-settings.png)

**Step 2**: In the popup, there are options helping you setup this mega menu item.

![Mega menu popup](_images/mega-menu-popup.png)

- Enable mega menu: select enable or disable mega menu for this menu item. By default, it is disabled.
- Mega panel width: enter the width of the mega menu panel in pixel. This option **can not be empty**.

Besides, you will see all direct children menu items of this menu item display there. They are all menu items level 2 which are children of current menu item. Each of them will be a column in mega menu panel. You can change the width of each column right there by clicking to the arrow icons.

**Step 3**: If you don't want to setup the background for this mega menu, you can ignore this step. Just click to _Background_ menu in the left side of popup, new options will appear and allow you to upload background image as well as select background properties.

![Mega menu background](_images/mega-menu-bg.png)

**Step 4**: This step is optional too. With menu item level 2, you will be abble to hide it. For example, you can see in the shop mega menu, our last column is empty. It is used to create a space for displaying background image.

And from menu item level 2, you can add custom content to your menu item.
