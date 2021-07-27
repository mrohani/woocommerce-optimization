# woocommerce-optimization

WooCommerce is a resource intensive plugin which may take your server resources for loading all relevant stylesheets and scripts. If you have few products with hundreds of thousands of blog posts then it make sense to dequeue or disable all WooCommerce relevant stuffs on the blog posts. In other words you can only allow WooCommerce scripts on shop relevant pages so that all other pages will load faster.

The code will first check whether WooCommerce plugin exist on your site and then disable the styles and scripts on all pages except product, cart and checkout pages. This will help to remove “wc-ajax=get_refreshed_fragments” calls from all posts/pages except WooCommerce related pages.
