# Installing Ansible

 - Preferably **Linux/unix** based.
 - You will need python **2.x** or **3.x** installed.
    ```shell
   # update the packages list and install the prerequisites
   sudo apt update
   sudo apt install software-properties-common
   
   # add the deadsnakes PPA to your system’s sources list
   sudo add-apt-repository ppa:deadsnakes/ppa

   # once the repository is enabled, you can install Python 3.9 by executing
   sudo apt install python3.9

   # verify that the installation was successful by typing
   python3.9 --version
   
   # python alternatives
   sudo update-alternatives --install /usr/bin/python python /usr/bin/python3.8 1
   sudo update-alternatives --install /usr/bin/python python /usr/bin/python3.9 2
  
   # verify python alternatives
   python -V
   ```
 - Installing **pip** and **ansible**.
   ```shell
   sudo apt install python3-pip
   sudo pip install ansible
   ```

