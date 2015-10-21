# wooly-parade-junction-box
Magento 2 Sample Module - Demonstrating Plugins

## Installation Steps

    composer config repositories.mttjohnson/wooly-parade-junction-box git git@github.com:mttjohnson/wooly-parade-junction-box.git
    composer require mttjohnson/wooly-parade-junction-box:dev-master
    bin/magento module:enable Mttjohnson_JunctionBox --clear-static-content
    bin/magento setup:upgrade
