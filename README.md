#### dcos-slave-vagrant | Deploy Mesosphere DCOS Slave Instance with Vagrant

##### 1. You will need vagrant installed beforehand

  - **NOTE:** You will need to run the **dcos-vagrant** master instance first.
  - https://github.com/brycekottke/dcos-master-vagrant
  - Spinning up DCOS Slave

```bash
$ vagrant up

http://<dcos-master-ip>  # Your Slave instance should show under "Nodes". Can take 10 - 15 mins
```
