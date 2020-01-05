Setting up Weblogic Instance using ANSIBLE
--------------------------------------------


Download Below two files and store it into roles/setup-weblogic/files

https://www.oracle.com/middleware/technologies/weblogic-server-downloads.html

https://www.oracle.com/technetwork/java/javase/downloads/server-jre8-downloads-2133154.html

Install JAVA in all nodes


Install Ansible and password less authentication to both nodes

#ansible-playbook playbook.yaml -i ansible_hosts



refernce:  https://github.com/AKSarav/VagrantWeblogicInfra-AnsibleRole
