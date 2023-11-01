# Magento2 Coupon Link
- Use <a href="https://mirasvit.com/magento-2-extended-shopping-cart-rules.html">Mirasvit extended shopping cart rule (Special Promotion)</a> instead of this extension. it is better solution.
- The extension allows you to create URL links that will automatically add a coupon code for your customer to the shopping cart. Used in newsletter campaigns, marketing banners or posts, social media posting or in any promotional tools.
Format of the link is...
```
https://{your_domain}/checkout/cart/coupon/?code={code}
```
```
https://localhost/checkout/cart/coupon/?code=PROMOX34Y
```

## Compatibility
Magento 2.4.6 + PHP 8.2.9

## Install

#### Install via Composer (recommend)

1. Go to Magento2 root folder

2. Enter following commands to install module:

    ```bash
    composer require hgati/magento2-coupon-link:dev-master
    ```

   Wait while dependencies are updated.

#### Completion of installation

1. Go to Magento2 root folder

2. Enter following commands:

    ```bash
    php bin/magento setup:upgrade
    php bin/magento setup:di:compile
    php bin/magento setup:static-content:deploy (optional)
    ```
## Usage

### Configuration

Format of the link is https://{domain}/checkout/cart/coupon/?code={code}

## Uninstall

You can uninstall a module only if you’re certain you won’t use it. Instead of uninstalling a module, you can disable it. Pleace, create backup so you can recover the data at a later time.

#### Uninstall via Composer

1. Go to Magento2 root folder

2. Enter following commands to remove:

    ```bash
    composer remove hgati/magento2-coupon-link
    ```
#### Completion of uninstall

1. Go to Magento2 root folder

2. Enter following commands:

    ```bash
    php bin/magento setup:upgrade
    php bin/magento setup:di:compile
    php bin/magento setup:static-content:deploy (optional)
    ```
