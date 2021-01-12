# ansible script for setting up a multi-node Kubernetes cluster

## Prerequisites
You will need:
- Ubuntu 20.04 virtual machines with SSH enabled with dns name resolution enabled. Host names must match the names in the hosts file in this directory
- Each nodes should be accessible by its simple name e.g. node1 (DNS server and suffix needs to work for this one)
- SSH keys needs to be copied over to each node with ssh-copy-id from the ansible host

## Installation
- ansible-playbook setup_master.yaml to setup the master node
- ansible-playbook setup_worker.yaml to setup the master node



