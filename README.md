
# Setting the vars.yml

In the vars.yml file you have to configure:
1. The location of the docker container
2. The hostname of your mail server
3. The mail domain
4. The admin password of the the admin console

The vars.yml file should look like this:

    IREDMAIL_DIR: /opt/iRedMail
    HOSTNAME: mail.example.com
    FIRST_MAIL_DOMAIN: example.com
    FIRST_MAIL_DOMAIN_ADMIN_PASSWORD: testpassword

After the playbook has executed head to:

    http://<ip-address>/iredadmin

This is the admin panel of the iRedMail server, here you can configure settings, add users ect.
You can login with the credentials you set in the vars file
    
    username: postmaster@example.com
    password: FIRST_MAIL_DOMAIN_ADMIN_PASSWORD


To head to the mail panel to send an recieve mails head to:

    http://<ip-address>







