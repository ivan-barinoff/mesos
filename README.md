## Ubuntu 14.04 cluster via vagrant
The repository provides a vagrant template with a provision file.

It will create cluster with the following machines:
1. ubuntu-01 = 172.17.10.101
2. ubuntu-02 = 172.17.10.102
3. ubuntu-03 = 172.17.10.103

The provision file contains the following:
install java, mesos, marathon, chronos

## How to run
vagrant up