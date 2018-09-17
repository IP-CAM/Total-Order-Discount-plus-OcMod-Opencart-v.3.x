# Total Order Discount+

Total Order Discount+ extension is for CMS Opencart 3. It allows to add a discount system to the store, based on sub-total price or products amount in the cart.
Have been tested with 3.0.2.0 only, but should work with other OC 3.x versions.

## Features
* Allows to make unlimited number of discounts, that based on sub-total price or products amount in the cart.
* Two types of discount - percentage or fixed.
* "Discount" appears in the order only when applied.
* Negative discount- Surcharge for low order.
* Auto sort discount table in extension panel.
* Multilangual - EN/UA/RU.
* Does not change original files - OCMOD modification.

## History
* v1.0 (2018.08.01):
    * First release

## How to install
* To begin, make backup, really!
* Open OpenCart Admin Panel
* Extensions > Installer > [Upload]: open the file total-order-discount-plus.ocmod.zip
* See the "Success: You have modified extensions!" message
* Extensions > Modifications > [Refresh]
* Extensions > Extensions > Order Totals > Total Order Discount+ > [Install]
* Extensions > Modifications > [Refresh]
* Go to Dashboard > [Developer Settings] > Theme [Refresh]
* Go to Dashboard > [Developer Settings] > SASS [Refresh]

## How to configure
* Admin > Extensions > Order Totals > [underr] Total Order Discount+ - Install
* Admin > Extensions > Order Totals > [underr] Total Order Discount+ - Edit
    * Set the desired parameters
* Admin > Extensions > Order Totals
    * Set the correct sort order values for the modules:
        1. All modules that are subject to a discount must be located before the Sub-Total module.
        2. The Sub-Total module.
        3. The Total Order Discount+ module.
        4. The Total module.

## How to uninstall
* Make backup
* OpenCart Admin -> Extensions menu > Installer
* Extensions > Install History: find the total-order-discount-plus.ocmod.zip file and click [Uninstall]
* Extensions > Modifications > [Refresh]
* Go to Dashboard > [Developer Settings] > Theme [Refresh]
* Go to Dashboard > [Developer Settings] > SASS [Refresh]

## Links
* [Opencart Marketplace](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=)
* [underr.space](https://underr.space/notes/projects/project-011.html)

