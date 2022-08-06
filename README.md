# Install

Extract the repo files to the public_html

Open console (ssh terminal)

In the console (terminal) navigate to your magento root folder:

Install the new module using the command below:

```sh
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
php bin/magento cache:flush
```

# Description
Module that corrects the application of discount by the configuration of the payment method.

Functional in versions: 2.2.x and 2.3.x (not tested in the others);

This module was developed based on the modules below, which by themselves did not solve the problem when applied to the versions mentioned above:

https://github.com/MagestyApps/magento2-fix-discount-rules

https://github.com/MeetanshiInc/Solution-Discount-Based-on-Payment-Method-Not-Showing-in-Magento-2-Cart-Total
