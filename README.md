
# Setting the vars.yml

The vars.yml file should look like this:

    IREDMAIL_DIR: /opt/iRedMail
    HOSTNAME: mail.example.com
    FIRST_MAIL_DOMAIN: example.com
    FIRST_MAIL_DOMAIN_ADMIN_PASSWORD: testpassword



After the playbook has executed head to:

    http://<ip-address>/iredadmin

You can login with the credentials you set in the vars file
    
    username: postmaster@example.com
    password: FIRST_MAIL_DOMAIN_ADMIN_PASSWORD

Here you can view the admin panel of the mail server
