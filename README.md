# challenge-laa
Solution for a Log Access Analytics technical challenge

# Configuring the development server with Ansible

The server-config folder contains the Ansible playbooks used to configure the Jenkins server.

To use it on the managed machine, you must install Python 2, as Ansible depends on it:

apt-get install python

Then to configure the server:

ansible-playbook -i hosts --user root development-server.yml