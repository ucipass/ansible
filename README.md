# Ansible script for setting up a multi-node Kubernetes (k8s or k3s) cluster

## Prerequisites
You will need:
- Ubuntu 20.04 virtual machines with SSH and DNS name resolution enabled.
- Each nodes should be accessible by its simple name e.g. node1 (DNS server and suffix needs to work)
- SSH keys needs to be copied over to each node with ssh-copy-id from the ansible host
- Ansible needs to be run from the project directory in order to find the customer ansible.cfg and hosts files.

## k8s Installation
- ansible-playbook setupk8s.yaml

## k3s Installation
- ansible-playbook setupk3s.yaml

## OpenEBS Installation
....under development



