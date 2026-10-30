<h1 align="center">Kassebridge – Checkout Migration & Health for WooCommerce</h1>

<p align="center"><b>Safely migrate WooCommerce from classic checkout to the Checkout block with readiness scans and controlled rollout.</b></p>

<p align="center">
  <a href="https://wordpress.org/plugins/kassebridge-checkout-migration-health-for-woocommerce/"><img src="assets/download-wporg.svg" alt="Download on WordPress.org" height="36"></a>
</p>

<p align="center">Free WordPress plugin · Version 1.0.4 · GPLv2 or later</p>

> [!NOTE]
> Kassebridge – Checkout Migration & Health for WooCommerce is officially distributed through **WordPress.org**. Please download, install and get updates from its [WordPress.org page](https://wordpress.org/plugins/kassebridge-checkout-migration-health-for-woocommerce/) so you always have the latest reviewed version.

## About

Kassebridge is a WooCommerce add-on for stores moving from the classic checkout to the Checkout block. WooCommerce must be installed and active.

It helps store managers check compatibility, preview a block checkout, send a controlled share of shoppers to it, compare aggregate results, and stop the rollout when the configured safety checks detect a problem.

#### Main features

- Scan active plugins, must-use plugins, the active theme, and payment gateways for common classic-checkout patterns.
- Show a readiness score with the findings behind it.
- Create or select a second checkout page that contains the WooCommerce Checkout block.
- Preview the block checkout for store managers before sending shopper traffic to it.
- Gradually roll out the block checkout at 10%, 25%, 50%, or 100%.
- Compare aggregate checkout views, orders created, completed orders, and failures.
- Automatically pause a rollout when configured safety thresholds are crossed.
- Run health checks for WooCommerce, checkout configuration, HTTPS, PHP, order storage, Store API rate limiting, and failed orders.
- Alert store managers when failed orders rise sharply.
- Promote the block checkout to the main WooCommerce checkout page, with an undo action.

#### Data and privacy

Kassebridge does not use third-party analytics or telemetry and does not create its own tracking cookie.

Its custom analytics table stores aggregate counters only. During a rollout, private Kassebridge metadata may be added to participating orders to remember the checkout bucket and avoid double-counting. It does not store names, email addresses, IP addresses, card details, or other payment details in its analytics table.

The rollout choice uses the WooCommerce session that already exists for the cart and checkout.

Kassebridge supports High-Performance Order Storage and declares compatibility with WooCommerce Cart and Checkout blocks.

#### Important limits

The compatibility scan checks code patterns and cannot prove that another plugin works with Checkout blocks. Always test the block checkout and place a real test order before increasing rollout traffic.

The checkout comparison is a practical safety signal, not a scientific experiment. Kassebridge waits for enough checkout views before showing a comparison verdict.

### External services

Kassebridge does not connect to a Kassebridge server, analytics provider, advertising network, or other third-party service.

The optional “Load checkout page” health check sends an HTTP GET request only to the published WooCommerce checkout URL on the same WordPress site. It runs only when an authorized store manager starts the health test. The request is used to confirm that the site’s own checkout responds successfully. No store, customer, order, payment, rollout, or analytics data is sent to an external service by this check.

Emails are sent by the site itself through the standard WordPress mail function.

### Third-party resources

- Manrope font, Copyright 2018 The Manrope Project Authors, licensed under the SIL Open Font License 1.1. The font and its license are bundled in `assets/fonts/` and are loaded locally.

## Requirements

- WordPress 6.5 or higher
- Tested up to WordPress 7.1.4
- PHP 7.4 or higher
- WooCommerce (installed and active)

## How to install

1. In your WordPress dashboard go to **Plugins → Add New Plugin**.
2. Search for **Kassebridge**.
3. Click **Install Now**, then **Activate**.

Or download it directly from **[WordPress.org](https://wordpress.org/plugins/kassebridge-checkout-migration-health-for-woocommerce/)**.

## Support

Questions or problems? Please use the **[support forum on WordPress.org](https://wordpress.org/support/plugin/kassebridge-checkout-migration-health-for-woocommerce/)**.

## Author

Developed by **[Muhammad Mujahid Sarfraz](https://profiles.wordpress.org/mujahidwp/)** · [All my WordPress products](https://profiles.wordpress.org/mujahidwp/) · [LinkedIn](https://www.linkedin.com/in/muhammad-mujahid-sarfraz-2631a43b6)
