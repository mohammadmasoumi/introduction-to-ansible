# Ansible Configuration

Configure our local Ansible environment with global specific properties associated with our setup.

 - create a **configuration file(ansible.cfg)** to control your local Ansible environmental settings.
    ```shell
    # ansible cfg

    [defaults]
    inventory = ./hosts-dev
    ```
   