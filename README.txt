Opencart module for eValor
============================

This module integrates the eValor sidebar module in your online store. This module is
easy to install. For that you can use the instructions.

This module has been optimized for OpenCart version 2.0.1.0 and higher.


Installation instructions
----------------------------

     1. Upload the files from the upload folder to the web server.

     2. The module can now be activated in your OpenCart control panel.

     3. Enter the ID number of your online store and the API code and configure
     the module.

     4. If you want to send invitations you must configure a cronjob. The cronjob is
     must be done every afternoon with the url:

       http://www.su-tienda-online.es/index.php?route=module/webwinkelkeur/cron

     To carry out this process put the following rule in your crontab.

       30 23 * * * wget --quiet -O- 'http://www.your-store-online.es/index.php?route=module/webwinkelkeur/cron' 

