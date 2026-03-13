# Config Image Sizes

After finish installing required plugins, there some options of product image sizes you must config before importing the demo content.

### With WooCommerce 3.3.0 or newer

From the version 3.3.0, WooCommerce moved settings for image sizes to **Appearance > Customize > WooCommerce > Product Images**. There are new settings for them:

![woocommerce image size settings](_images/woocommerce-settings-image-sizes-330.png)

- **Main image width**: 897
- **Thumbnail width**: 433
- **Thumbnail cropping**: Custom (73x87)

### With WooCommerce older than 3.3.0

In the WordPress Dashboard, navigate to **Woocommerce > Settings > Products > Display**, under the Product Images section, you will found options for image sizes of Catalog Images, Single Product Images, and Product Thumbnails.

- Catalog Images are the product thumbnails on the shop page. It is also used in shortcodes which are used to show products.
- Single Product Images are product images on the single product page.
- Product Thumbnails are small images of products. They are the product gallery thumbnails on single product page or product thumbnails on widgets.

![woocommerce image size settings](_images/woocommerce-settings-image-sizes.png)

There are settings you should use for them:

- **Catalog Images**: 433 x 516
- **Single Product Images**: 897 x 908
- **Product Thumbnails**: 80 x 100

