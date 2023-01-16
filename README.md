##Risecommerce Advanced Sorting Extension
Advanced Sorting extension allows customers to sort products by Best Sellers, Top Rated, New Arrivals, Most Viewed, and Reviews Count options on catalog listing page.

##Support: 
version - 2.3.x, 2.4.x

##How to install Extension

Method I)

1. Download the archive file.
2. Unzip the files
3. Create a folder [Magento_Root]/app/code/Risecommerce/BuyNow
4. Drop/move the unzipped files to directory '[Magento_Root]/app/code/Risecommerce/BuyNow'

Method II)

Using Composer

composer require risecommerce/magento-2-buy-now-extension:1.0.1

#Enable Extension:
- php bin/magento module:enable Risecommerce_BuyNow
- php bin/magento setup:upgrade
- php bin/magento setup:di:compile
- php bin/magento setup:static-content:deploy
- php bin/magento cache:flush

#Disable Extension:
- php bin/magento module:disable Risecommerce_BuyNow
- php bin/magento setup:upgrade
- php bin/magento setup:di:compile
- php bin/magento setup:static-content:deploy
- php bin/magento cache:flush
