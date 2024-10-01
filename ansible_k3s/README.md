#Before installation you'll need to 
#download K3s Binary:
#-------
#  curl -L -o k3s https://github.com/k3s-io/k3s/releases/download/v1.29.1-rc2%2Bk3s1/k3s
#  chmod +x k3s
#-------

#-------
#Download Airgap Image:
#-------
#  curl -L -o k3s-airgap-images-amd64.tar https://github.com/k3s-io/k3s/releases/download/v1.29.1-rc2%2Bk3s1/k3s-airgap-images-amd64.tar
#-------

#-------
# Download k3s install script:
#-------
#  curl -L -o install.sh https://get.k3s.io
#  chmod +x install.sh
#-------
#and copy them to folders:
# ./roles/k3s_agent/files/ 
# ./roles/k3s_install/files/



#sudo mkdir -p /var/lib/rancher/k3s/agent/images/
#sudo cp ./k3s-airgap-images-amd64.tar /var/lib/rancher/k3s/agent/images/
#sudo cp ./k3s-selinux-0.4-1.el8.noarch.rpm /var/lib/rancher/k3s/agent/images/
#sudo cp ./k3s /usr/local/bin
#sudo cp ./install.sh /usr/local/bin



