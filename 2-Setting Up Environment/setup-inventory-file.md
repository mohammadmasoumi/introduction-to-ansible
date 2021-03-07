# Setup Inventory File

### Inventory File

 - hosts-dev 
   ```shell
   # hosts-dev
   [webservers]
   app.server.1:3435 # define specific port
   app.server.2
   
   [loadbalancers]
   lb load.balancer.server.1=12.34.54.23 # define aliases
   ```
 - default Ansible inventory is located in the
   ```etc/ansible/hosts```
 - reference a different inventory by using the `-i <path>` option in the commandline. 

