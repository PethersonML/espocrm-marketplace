 ![EspoCRM](https://raw.githubusercontent.com/PethersonML/espocrm-marketplace/main/images/espocrm-logo.png)
  
  ### Seguem dados de acesso para Gerenciamento do seu Ambiente ${env.displayName}
  
  ##### Dados de acesso do LiteSpeed Web Admin:
  
  **Host:** [${globals.adminUrl}](${globals.adminUrl})
  **Usu&aacute;rio:** admin
  **Senha:** ${globals.LS_ADMIN_PASS}
  
  ---
  
  ##### Dados de acesso do phpMyAdmin:
  
  **Host:** [${nodes.db.adminUrl}](${nodes.db.adminUrl})
  **Usu&aacute;rio:** espocrm
  **Senha:** ${globals.PASSWD}
  
  ---
  
  ##### Informações para configurar o EspoCRM:
  
  **Host do Banco de Dados:** ${nodes.db.intIP}
  **Nome do Banco de Dados:** espocrm
  
  ---

  **Importante:** N&Atilde;O utilize a op&ccedil;&atilde;o &quot;Reimplantar&quot; da ferramenta de Altera&ccedil;&atilde;o de Topologia, pois isso causar&aacute; problemas em seu servidor Litespeed, para atualizar a vers&atilde;o do Litespeed &eacute; recomendado criar um novo ambiente.

&nbsp;