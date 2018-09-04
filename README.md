# Magento2 Ecomfit Module
This is an example ecomfit module In Magento2
## Manually Installation

Ecomfit module installation is very easy, please follow the steps for installation-

=> Download and unzip the respective extension zip and create Ecomfit(vendor) and Tracking(module) name folder inside your magento/app/code/ directory and then move all module's files into magento root directory Magento2/app/code/Ecomfit/Tracking/ folder.

## Install with Composer as you go
Specify the version of the module you need, and go.
    
    composer require locpx/magento2_tracking_module
    

## Run following command via terminal from magento root directory 
  
     $ php bin/magento setup:upgrade
     $ php bin/magento setup:di:compile
     $ php bin/magento setup:static-content:deploy

=> Flush the cache and reindex all.

now module is properly installed

