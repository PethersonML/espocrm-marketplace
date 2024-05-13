 ![EspoCRM](https://raw.githubusercontent.com/PethersonML/espocrm-marketplace/main/images/espocrm-logo.png)
  
  ### A continuación se muestran los detalles de acceso para Gestionar su entorno ${env.displayName}
  

  ##### Datos de acceso de phpMyAdmin:
  
  **Host:** [${nodes.mariadb113.adminUrl}](${nodes.mariadb113.adminUrl})

  **Usuario:** espocrm

  **Contraseña:** ${globals.PASSWD}
  
  ---
  
  ##### Informações para configurar o EspoCRM:
  
  **Host de base de datos:** ${nodes.mariadb113.intIP}

  **Nombre de la base de datos:** espocrm
  
  ---

  **Importante:** Luego de crear el Entorno, primero debe acceder a EspoCRM para completar la instalación.

  1- En el primer paso, elija el idioma deseado y el tema que se utilizará.
  
  2- Luego acepte los términos del acuerdo de licencia.
  
  3- En el tercero será necesario ingresar la información de la Base de Datos. Deje seleccionada la opción MySQL/MariaDB e ingrese la información del host, el nombre de la base de datos, el nombre de usuario y la contraseña como se proporciona en este correo electrónico.
  
  4- En esta pantalla, confirme que todas las dependencias sean correctas y continúe con la Instalación.
  
  5- Desde aquí, se creará el usuario Administrador de EspoCRM y deberá definir algunas opciones personalizadas como zona horaria, formato de fecha, moneda, servidor de correo electrónico, etc. Simplemente haga todos los ajustes necesarios y llegará a la pantalla de finalización de la instalación.
  
  6- En este punto, aparecerá una configuración que se debe realizar en el servicio Programador CRON de Linux donde se instaló EspoCRM. Si necesita ayuda con esto, comuníquese con nuestro [Soporte 24/7](https://api.whatsapp.com/message/2HGCCPU36CDMA1?autoload=1&app_absent=0)

&nbsp;