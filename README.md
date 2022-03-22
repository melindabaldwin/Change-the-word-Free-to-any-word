# Change-the-word-Free-to-any-word
Change the word "Free" to any word
/**
 * WooCommerce Extra Feature
 * --------------------------
 *
 * Replace "Free!" by a custom string
 *
 */
function woo_my_custom_free_message() {
        return "Liên hệ để lấy giá";
}
 
add_filter('woocommerce_free_price_html', 'woo_my_custom_free_message');
