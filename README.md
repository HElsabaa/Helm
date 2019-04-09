# kubernetes-and-ansible
This is Ansible Playbooks acting as IaaC to Install/Configure/Delete Helm on a Kubernetes cluster.

Prerequesits :
1. Up and runnning Kubernetes Cluster (i.e K8s)
2. Internet Access to donwload the Helm Binary 
3. Define the needed Service Account for Role Biniding in env_variables file 
4. Update Hosts file for the Kubernentes master node .

How to Use :
1. Use install_helm.yml to install Helm along with all needed tiller component .
2. Use clean_helm_setup.yml to completely remove Helm and Tiller component .

Copyright: Hassan ElSabaa - hassan.salah.elsabaa@gmail.com
