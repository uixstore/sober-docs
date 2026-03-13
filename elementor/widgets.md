# Elementor Widgets

From the version 3.0, we are happy to introduce one of the most anticipated updates for our theme with Elementor compatibility! We have implemented 100% compatibility with this builder and now our theme works flawlessly with both WPBakery and Elementor and you can decide which one is better for you.

![Elementor Widgets](_images/elementor--widgets.png)


Sober has 20+ widgets that you can find in the **Sober** section.


### How to transform WPBakery content into Elementor widgets. <!-- {docsify-ignore} -->

Unfortunately, there is no transfer mechanism for pages built with WPBakery Page Builder to transform their content into Elementor. So if you want to use Elementor then you will need to create all pages from scratch manually. All our elements that you used with WPBakery are working in the same way on Elementor.

However, in the theme, you can find all predefined templates to recreate your pages. Please read more about Elementor templates in this link: [Elementor Templates](elementor/templates.md)


### Editting the Shop page

While trying to edit the archive pages with Elementor, you may encounter an error message that indicates that the content area has not been found on the page. This error message usually appears in the following scenarios:

- When Trying to edit an archive page without creating an archive template / not editing through the archive template.

- When the website URL and home page URL are not the same


For example, you will receive an error message **"The content area has not been found on your page"** while trying to edit the shop page. The error occurs because when a page is set as the Shop page, WooCommerce plugin takes over and assigns the WooCommerce template to that page. This means that the page is no longer editable in Elementor, as the WooCommerce template takes priority over any other templates or page builders.

The reason for this is that the WooCommerce plugin has its own template hierarchy that determines how the WooCommerce shop page is displayed. The WooCommerce template takes priority over any other templates or page builders, including Elementor.

In summary, WooCommerce shop pages cannot currently be directly edited by Elementor. With Elementor Pro, however, you can create a new shop archive page to use in place of the default shop page. If you have the Elementor Pro on your website, you can refer to the documentation of [How to create a WooCommerce archive template](https://elementor.com/help/creating-a-woocommerce-archive-template/).

You can also refer to the documentation of [How to fix the error: “The content area has not been found on your page”?](https://elementor.com/help/the-content-area-was-not-found-error/) to learn more about the error and how to fix it.
