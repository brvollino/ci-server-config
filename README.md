# ci-server-config

Contains the Ansible playbooks that configure the continuous integration server (a.k.a. "Jenkins machine").

You must install Python 2 in the managed machine, in order to be able to configure it with Ansible:

apt-get install python

Then configure the server:

ansible-playbook -i hosts --user root ci-server.yml