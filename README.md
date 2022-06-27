# role-freeradius-jumpcloud-proxy

This role installs and configures freeradius to proxy its connections to Jumpcloud's radius service.


To get started, you need to add a Radius service to your Jumpcloud console. Login to the Jumpcloud admin section, and on the left click RADIUS and then the big green +. The servername is just for your reference and not used. The IP is the source IP of where Radius requests will come from, so you need to have 1 radius server per Source IP. The Shared secret needs to be saved and vaulted for use in this playbook.


You will also need to setup clients to point to this machine and use the secret you made up for the clients config.


