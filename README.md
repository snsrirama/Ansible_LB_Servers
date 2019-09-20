# Ansible_LB_Servers
Ansible for having a loadbalancer and two application servers

Followed YAML syntax from https://docs.ansible.com/ansible/latest/reference_appendices/YAMLSyntax.html

Ansible Tutorial for Beginners https://linuxhint.com/ansible-tutorial-beginners/

For starting the instances on OpenStack follow https://courses.cs.ut.ee/2018/DDPC/fall/Main/Lab12018 

To login to the instances from the controller without password

cat .ssh/id_rsa.pub|ssh -i satish/OpenStackKeys/Srirama2019.pem ubuntu@172.17.67.54 'cat >> .ssh/authorized_keys'
