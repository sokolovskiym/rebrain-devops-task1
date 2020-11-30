*README.md*

**DEAR ALL!**

All actions bellow should be prepared **before** installations process will start:

```sh
$ sudo apt update
$ sudo apt upgrade
```

After system update you should clone this repo and edit some files:

1. Edit file hosts.txt with your own server's IP addresses

2. Edit file /group_vars/cloud with your own "ansible_user" and path to the "ansible_ssh_key_private_file"

3. Enjoy! :)

**Note!**

You need to logout and login to ansible host for using docker commands w/o "sudo"

**Additional information:**

Tested on UBUNTU 18.04 TLS


