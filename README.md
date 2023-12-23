# Odoo-install From version 8.0 to 17.0

## For Dockers : take a look at [Odoo dockers based on git repositories](https://github.com/elhamdaoui/odoo_docker/tree/arm64_v8)

Bash script to install odoo 8.0, 10.0, 11.0, 12.0, 13.0, 14.0, 15.0, 16.0 and 17.0

- After executing this script, Try to use Terminal and:
- sudo su - postgres -c "createuser -s odoo" 2> /dev/null || true

  - Connect to postgres user: $ sudo su postgres
  
  - Using psql: $ psql 
  
  - Listing the psq roles: $ \du
  
  - Update Password for OE_USER (ex: "odoo13") role: $ alter role odoo13 with password 'odoo13'
  
  - exit postgres: $ \q
  - The new password must be copied on 'db_password=' in 'odooXX-server.conf' (XX in 8,10,11,12,13,14...)



For Centos/Redhat, see the link below (odoo 13)
https://www.tecmint.com/install-odoo-in-centos-8/
