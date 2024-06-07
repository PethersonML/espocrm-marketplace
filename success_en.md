 ![EspoCRM](https://raw.githubusercontent.com/PethersonML/espocrm-marketplace/main/images/espocrm-logo.png)
  
  ### Below are access details for Managing your Environment ${env.displayName}
  
  
  ##### Information to set up EspoCRM:
  
  **Database Host:** ${nodes.mariadb113.intIP}

  **Database Name:** espocrm
  
  ---

  **Important:** After creating the Environment, it is necessary to access EspoCRM for the first time to complete the installation.

  1- In the first step, choose the desired Language and the Theme that will be used.
  
  2- Then accept the terms of the license agreement.
  
  3- In the third one, you will need to enter the information from the Database. Leave the MySQL/MariaDB option selected and enter the host information, Database name, username and password as provided in this email.
  
  4- On this screen, confirm that all dependencies are correct and continue with Installation.
  
  5- From here, the EspoCRM Admin user will be created and will need to define some personalized options such as Timezone, Date format, Currency, Email Server, etc. Just make all the adjustments according to your needs and you will reach the installation completion screen.
  
  6- At this point, a configuration will appear that must be done in the Linux CRON Scheduler service where EspoCRM was installed. If you need help with this, please contact our [24/7 Support](https://api.whatsapp.com/message/2HGCCPU36CDMA1?autoload=1&app_absent=0)

  ---

  ##### phpMyAdmin access data:
  
  **Host:** [${nodes.mariadb113.adminUrl}](${nodes.mariadb113.adminUrl})

  **User:** espocrm

  **Password:** ${globals.PASSWD}

&nbsp;