 ![EspoCRM](https://raw.githubusercontent.com/PethersonML/espocrm-marketplace/main/images/espocrm-logo.png)
  
  ### Seguem dados de acesso para Gerenciamento do seu Ambiente ${env.displayName}
  

  ##### Dados de acesso do phpMyAdmin:
  
  **Host:** [${nodes.mariadb113.adminUrl}](${nodes.mariadb113.adminUrl})

  **Usu&aacute;rio:** espocrm

  **Senha:** ${globals.PASSWD}
  
  ---
  
  ##### Informações para configurar o EspoCRM:
  
  **Host do Banco de Dados:** ${nodes.mariadb113.intIP}

  **Nome do Banco de Dados:** espocrm
  
  ---

  **Importante:** Após a criação do Ambiente é necessário realizar um primeiro acesso ao EspoCRM para finalizar a instalação.

  1- No primeiro passo, escolha o Idioma desejado e o Tema que será utilizado.
  2- Depois aceite os termos do contrato de licença.
  3- No terceiro será necessário colocar as informações do Banco de Dados. Deixar selecionado a opção MySQL/MariaDB e colocar as informações de host, nome do Banco de Dados, usuário e senha conforme passadas nesse email.
  4- Nessa tela, confirme que todas as dependencias estão corretas e siga para Instalação.
  5- A partir daqui será criado o usuário Administrados do EspoCRM e precisa definir algumas opçòes personalizadas como Timezone, formato de Data, Moeda, Servidor de Email, etc. Basta realizar todos os ajustes conforme sua necessidade e chegará na tela de finalização da instalação.
  6- Nesse momento irá aparecer uma configuração que deve ser feita no serviço CRON Scheduler do Linux em que o EspoCRM foi instalado, caso precise de auxilio para isso entre em contato com nosso [Suporte 24/7](https://api.whatsapp.com/message/2HGCCPU36CDMA1?autoload=1&app_absent=0)

&nbsp;