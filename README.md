# My home driven by ansible

## Ansible hosts
In order to access all nodes via ansible simply copy `hosts` file to `/etc/ansible/hosts` on your ansible machine.

Currently configured:
- NAS
- Raspberry Pi 4

Check availability of all elements by runnin `ansible home -m ping`

## Raspberry Pi Kubernetes cluster

- raspbian installation
- add `ssh` file without extension directly to your boot drive (USB flash disk / sd card / others.)
- init raspberry instance to enable paswordless access - `ssh-copy-id pi@<raspberry_ip>` - initial password is `raspberry`


## Sources
- kubernetes pi cluster: https://github.com/rak8s/rak8s