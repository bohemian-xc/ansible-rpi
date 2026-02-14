# ansible-rpi
Raspberry Pi (2) installation automation with ansible

Pre-requisites:
Your Raspberry Pi 2 is running Raspberry Pi OS (Lite) or Debian-based OS

You can SSH into it

You want no Ansible installed on your laptop

You are comfortable with basic CLI usage


Create a dedicated Ansible user (recommended)

sudo adduser ansible
sudo usermod -aG sudo ansible

Allow passwordless sudo:
sudo visudo


Add:
ansible ALL=(ALL) NOPASSWD:ALL