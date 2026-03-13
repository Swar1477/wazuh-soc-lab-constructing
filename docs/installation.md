# Wazuh Manager Installation

This lab demonstrates the installation of Wazuh SIEM.

Environment

Operating System : CentOS
Virtualization : VirtualBox

Step 1 : Update system

sudo yum update -y

Step 2 : Download Wazuh install script

curl -sO https://packages.wazuh.com/4.x/wazuh-install.sh

Step 3 : Run installation

sudo bash wazuh-install.sh -a

Step 4 : Verify services

systemctl status wazuh-manager
systemctl status wazuh-dashboard
