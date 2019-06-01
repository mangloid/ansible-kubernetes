very basic install. The default IP pool is 192.168.144.0/20. I was testing a very small cluster.
If you need a larger IP pool update both master init_cluster and calico.yml.


Expectes three centos 7 machines and SSH keys setup. Update hosts file and ensure names are resolvable. 


# ansible-playbook -i hosts kubernetes_install.yml 
