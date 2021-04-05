# Odoo-install From version 8.0 to 14.0
Bash script to install odoo 8.0, 10.0, 11.0, 12.0, 13.0 and 14.0 .

- After executing this script, Try to use Terminal and:

  - Connect to postgres user: $ sudo su postgres
  
  - Using psql: $ psql 
  
  - Listing the psq roles: $ \du
  
  - Update Password for odoo13 role: $ alter role odoo13 with password 'odoo13'
  
  - exit postgres: $ \q
