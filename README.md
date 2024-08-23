# CustomOrderNumber-Magento-2-Extension-Module
CustomOrderNumber Magento 2 Extension Module
**  First upload this extenstion on following path app/code/Vendor/
** after upload folder extract that folder
** then enable module run following command 
php -dmemory_limit=5G bin/magento module:enable Vendor_CustomInvoiceNumber
** when module enabled then run below command
php -dmemory_limit=5G bin/magento setup:upgrade
** when upgrade commend success then run below command
php -dmemory_limit=5G bin/magento setup:di:compile
** when this command success then run below command to clear cache
php -dmemory_limit=5G bin/magento cache:flush
