# Ansible Exercises
## Description
This repository will show how ansible is ran with the help of some screenshots. 
More can be found in the word document "Ansible Screenshots" found in this repo. However the main ansible ones
can be found here. See the "Ansible Screenshots" document for a full view of the screenshots taken during this 
exercise.

# Contents
## Please go to the below link to find a full list of screenshots.
![Ansible Screenshots](https://github.com/L00187850/Ansible/blob/main/Ansible%20Screenshots.docx)
## Proving connectivity between servers
This screenshot confirms that communication between all three servers is possible.

![Connectivity](https://github.com/L00187850/Ansible/blob/main/screenshots/Connectivity%20between%20ansiblemanager%20and%20other%20servers.jpg)

## Editing Hosts File at etc/hosts
This screenshot shows how the hosts file is configured to include other servers.
![Editing main Hosts file to include other servers](https://github.com/L00187850/Ansible/blob/main/screenshots/changing%20hosts%20file%20to%20include%20other%20servers.jpg)

## Installing Ansible
This part shows the installation of ansible on a linux device.

![Installing Ansible](https://github.com/L00187850/Ansible/blob/main/screenshots/installingAnsible.jpg)

## Changing Ansible Hosts file
Here we see the Ansible hosts file being edited to include the other two servers

![Changing Ansible Hosts file](https://github.com/L00187850/Ansible/blob/main/screenshots/Changing%20hosts%20file%20on%20manager.jpg)

## Gathering Ansible Inventory
Here we see a command "ansible-inventory --list -y" being ran to get a view of our Ansible Inventory.
![Ansible Inventory](https://github.com/L00187850/Ansible/blob/main/screenshots/AnsibleInventory.jpg)

## Showing Commands changing multiple deivces
This screenshot displays a single command being 
ran on multiple devices.
In this example we have got disk space being
ran on every server in ansible.

![Showing that commands can affect multiple devices](https://github.com/L00187850/Ansible/blob/main/screenshots/Showing%20that%20commands%20affect%20multiple%20devices.jpg)

## SSH acces on all devices
This part shows the status of SSH access on all devices running in ansible.

![Using Ansible to show ssh access on all devices](https://github.com/L00187850/Ansible/blob/main/screenshots/Showing%20SSH%20access%20to%20a%20user%20on%20multiple%20devices.jpg)

## Playbook introduction
This screenshot introduces the concept of playbooks. A playbook is a script used to 
define a set of tasks to be executed. It allows for the automated configuration of 
systems and devices on a range of topics, from updates, to software installations.
It is normally ran in the YAML format.
In this case a playbook is being used to update devices using "dist upgrade"
and then reboot the device afterwards if it is required.

![running a playbook to run a task](https://github.com/L00187850/Ansible/blob/main/screenshots/running%20updates.yaml%20file.jpg)

## Apache installation
The screenshot below demonstrates the installation of Apache on all devices in a 
specific group. In this example it is the webservers group.

![Installing apache](https://github.com/L00187850/Ansible/blob/main/screenshots/running%20install_apache.yaml%20file.jpg)

Below is proof afterward thats apache installed on AnsibleServer1. Note that the IP 
Address is the same as Ansible Server 1.

![Apache installed](https://github.com/L00187850/Ansible/blob/main/screenshots/proof%20of%20apache%20server%20running.jpg)


