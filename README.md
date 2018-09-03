# Playground for RedHat OpenShift / OKD
A playground to provision openshift cluster with `oc cluster up` command

## Prerequisites
- Linux
- Virtualbox
- Vagrant
- Ansible

## Instructions

1. Install ansible roles: `ansible-galaxy install -r roles.yml -p roles`
1. Start VM: `vagrant up`
1. ssh into the vm: `vagrant ssh`
1. Start openshift cluster: `oc cluster up`
