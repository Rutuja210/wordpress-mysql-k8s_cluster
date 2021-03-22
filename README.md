# wordpress-mysql-k8s_cluster
## Task Description:
```
🔅 Launch ec2-instances on AWS Cloud eg. for master and slave.
🔅 Create roles that will configure master node and slave node seperately.
🔅 Launch a wordpress and mysql database connected to it in the respectine slaves. 
🔅 Expose the wordpress pod and client able hit the wordpress ip with its respective port."
```

### Part I: Create the roles that will configure the master and slave node respectively
[Refer this repo for complete configuration of kubernetes cluster on AWS](https://github.com/Rutuja210/k8s-multinode-cluster.git)

### Part II: Create the role for launching wordpress and mysql database
Download [this role](./wordpress_mysql) in your roles directory.

### Part III: Create Ansible playbook (yaml) file 
Copy [this yaml](./main_setup.yml) file in your working directory and run it by the command 
**_ansible-playbook main_setup.yml_**
