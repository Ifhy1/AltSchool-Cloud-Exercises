# Exercise 1 – Ubuntu 20.04 LTS Setup Using Vagrant

## Steps I Followed
1. Created a folder inside my altschool-cloud-exercises project.
2. Initialized Vagrant with Ubuntu 20.04 LTS using `vagrant init ubuntu/focal64`.
3. Edited the Vagrantfile to use a private network with DHCP.
4. Ran `vagrant up` to start the virtual machine.
5. Used `vagrant ssh` to connect and ran `ifconfig` to verify the network.

## Screenshot
![ifconfig output](ifconfig-output.png)

