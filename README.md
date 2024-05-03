
#Setting the vars.yml

The vars.yml file should look like this:

IREDMAIL_DIR: /opt/iRedMail
HOSTNAME: mail.example.com
FIRST_MAIL_DOMAIN: example.com
FIRST_MAIL_DOMAIN_ADMIN_PASSWORD: testpassword



After the playbook has executed head to:

    http://DNSorIP/iredadmin

You can login with the credentials you set in the vars file
    
    username: postmaster@example.com
    password: FIRST_MAIL_DOMAIN_ADMIN_PASSWORD