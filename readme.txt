=== Category Listing for WooCommerce ===
Contributors: alexanderjuulj
Donate link: https://alexanderjuulj.com/donate/
Tags: woocommerce, category, categories, listing, separate
Requires at least: 5.0
Tested up to: 6.2
Stable tag: 1.0.6
Requires PHP: 7.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
 
Increase user-experience by listing both products and categories on your shop pages in separate lists. Easy setup. Install and activate only. Requires WooCommerce.

== Description ==

WooCommerce displays categories and products in the same list by default, which doesn’t look very good and it’s hard for the user to understand, what is products and what is categories.

This little plugins splits categories and products into two separate lists. 

It’s important that you DON’T ask WooCommerce to “Show categories and products” in the Customizing Tab. Set it to the default option “Show products”, and the separate listing for categories will automatically be added before the list of products.

The frontend is by default in English, but is also available in German, Spanish, Danish and Russian. POT included for easy translation with [Poedit](https://poedit.net/), WPML or Polylang.

Plugin is tested and tried with [Storefront](https://wordpress.org/themes/storefront/) by [Automattic](https://wordpress.org/themes/author/automattic/).

== Installation ==

1. Upload the Category Listing for WooCommerce plugin to the /wp-content/plugins/ directory or through the Plugins and Add New section in the WordPress Dashboard.
2. Activate the plugin through the Plugins menu in WordPress
3. That's all!

== Frequently Asked Questions ==

= Will the plugin create a separate listing for categories? =

Yes, all your categories will be shown above the product list on archive pages.

= Will I be able to determine what pages will show the category listing? =

No, at the moment the plugin is always showing the categories above the products. If the current category doesn’t have any subcategories, no categories will be shown.

== Screenshots ==

1. This is a screenshot of the main Shop page in WooCommerce, when the plugin is active. Storefront theme used for example.
2. This is a screenshot of a category page showing the subcategories in WooCommerce. Storefront theme used for example.
 
== Changelog ==
= 1.0.6 =
* Version - WC tested up to 7.7.0

= 1.0.5 =
* Enhancement - Implementing BEM naming structure
* Enhancement - CSS cleanup
* Version - WC tested up to 7.6.1

= 1.0.4 =
* Enhancement - Remove unnecessary
* Enhancement - Changed the conditional logic to only show on WooCommerce pages with a shop loop. 
* Dev - Add a unique id with the category slug to each single list tag
* Version - WC tested up to 5.1.0

= 1.0.3 =
* Removed categories from search results page.
* Removed headlines from search results page.
* Tested with newer version of WooCommerce.

= 1.0.2 =
* List is now using flex grid.
* Improved mobile experience.
* Tested with newer version of WordPress and WooCommerce. 

= 1.0.1 =
* Removed the Categories headline when there's no categories.
* Updated the Danish translation.

= 1.0.0 =
* Initial release.