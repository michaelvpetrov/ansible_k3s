### Pre-requirements:

Download K3s Binary:
> curl -L -o k3s https://github.com/k3s-io/k3s/releases/download/v1.29.1-rc2%2Bk3s1/k3s
> chmod +x k3s

Download Airgap Image:
> curl -L -o k3s-airgap-images-amd64.tar https://github.com/k3s-io/k3s/releases/download/v1.29.1-rc2%2Bk3s1/k3s-airgap-images-amd64.tar

Download k3s install script:
> curl -L -o install.sh https://get.k3s.io
> chmod +x install.sh

copy files to folders:
```
> ./roles/k3s_agent/files/ 
> ./roles/k3s_install/files/
```
### Install the project: 
**run ansible_autotun.sh**

