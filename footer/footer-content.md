# Footer Content

The Sober default footer contains footer content area and copyright area. Both of these areas can be configured in **Customize > Footer** section. All settings for the footer is described in [Theme Options > Footer](theme-options/footer.md).

Footer content area is the section where you see the subscribe form on the footer.


## Remove Footer Content

You can remove the footer content area by un-selecting the option **Enable Footer Content** in **Customize > Footer > Footer Content**.


## Add Subscribe Form

The option **Footer Extra Content** is the main option of this area. You can enter _HTML_ and _Shortcodes_ here. For example, we used a subscribe form which is provided by plugin [MailChimp for WordPress](https://wordpress.org/plugins/mailchimp-for-wp/) plugin. This is the code we used:

```
<h3>Newsletter</h3>
<p>Get timely updates from your favorite products</p>
[mc4wp_form id="306"]
```

Please note that the form ID here (306) is on our site only. It could be different on your site. If you want to get the right shortcode for this, please go to **MailChimp for WP > Forms** and press the **Get Shortcode** button. Besides, the default form will look a little bit different with the form on our demo. Please replace all code of that form by following code:

```
<input type="email" name="EMAIL" placeholder="Your email address" required="">
<input type="submit" value="Subscribe">
```
