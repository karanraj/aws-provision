AWS-Provision
=========

This role will launch 3 AWS Amazon linux. and update your invenstory file with IP under master and slave host-group..

Requirements
------------

You must have login on your AWS CLI console using aws-configure option so that aaws-access-key and aws-secret-key would fetch from that..

Example Playbook
----------------


    - hosts: localhost
      roles:
         - { role: karanraj.aws-provison }
* See Also
  [k8s-slave-node-setup](https://galaxy.ansible.com/karanraj/k8s_slave)
  [k8s-master-node-setup](https://galaxy.ansible.com/karanraj/k8s_master)
