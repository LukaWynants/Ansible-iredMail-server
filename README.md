
# Setting the vars.yml

The vars.yml file should look like this:

    IREDMAIL_DIR: /opt/iRedMail
    HOSTNAME: mail.example.com
    FIRST_MAIL_DOMAIN: example.com
    FIRST_MAIL_DOMAIN_ADMIN_PASSWORD: testpassword



After the playbook has executed head to:

    http://<ip-address>/iredadmin

This is the admin panel of the iRedMail server 
You can login with the credentials you set in the vars file
    
    username: postmaster@example.com
    password: FIRST_MAIL_DOMAIN_ADMIN_PASSWORD



To head to the mail panel to send an recieve mails head to:

    http://<ip-address>







