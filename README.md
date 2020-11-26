# ansible script for setting up a 5 node Kubernetes cluster

## Introduction
You will need:
- 5 ubuntu 20.04 virtual machines with SSH enabled named node1,node2,node3,node4,node5.
- Each nodes should be accessible by its simple name e.g. node1 (DNS server and suffix needs to work for this one)
- SSH keys needs to be copied over to each node with ssh-copy-id


