# Ansible Configuration

Configure our local Ansible environment with global specific properties associated with our setup.

- create a **configuration file(ansible.cfg)** to control your local Ansible environmental settings.
   ```shell
   # ansible cfg

   [defaults]
   inventory = ./hosts-dev
   ```
- configuration file will be search in the following order:
   - `ANSIBLE_CONFIG` (environment variable if set)
   - `ansible.cfg` (in the current directory)
   - `~/.ansible.cfg` (in the home directory)
   - `/etc/ansible/ansible.cfg`