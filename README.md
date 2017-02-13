## devops training
In listed directories you can find Vagrantfile  

**chef related:**  
- main:  
workstation + server(for chef-server)* + node 
- for CI:  
gitlab* + jenkins*

**additional directories:**  
- bento, related to [this one](https://github.com/chef/bento)
- virt_py, virtualenv
- multi_machine, related to [this one](https://www.vagrantup.com/docs/multi-machine/ )

**docker with jenkins:**  
```bash
$ docker run -d --name jenkins -p 8080:8080 jenkins:2.7.2
```

* - requires manual config
