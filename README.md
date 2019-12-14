# minicluster

This repo contains code to spin up a 3-node cluster of virtual ubuntu linux machines on MacOS.

### Requirements
* Virtualbox
* Vagrant

### Quick Start
```
cd node1 && vagrant up --provision && vagrant ssh
cd node2 && vagrant up --provision && vagrant ssh
cd node3 && vagrant up --provision && vagrant ssh
```

### Networking
Node | Static IP
--- | ---
`node1` | 192.168.0.10 
`node2` | 192.168.0.20 
`node3` | 192.168.0.30 

### Examples
* `examples/ansible` contains a simple ansible setup for the cluster.
