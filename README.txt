Ansible playbook to create kubernetes cluster in Ubuntu OS
Run command: ansible-playbook  -i hosts kubeinstall.yml
*****Modify the hosts file with required ip addresses*****

Preparatory tasks
•Install Ansible, pip in local Machine.
Ansible Installation :
sudo apt-get update
sudo apt-get install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt-get update
sudo apt-get install ansible
ansible –version
pip installation:
sudo apt-get install python-pip python-dev build-essential 
sudo pip install --upgrade pip 
sudo pip install --upgrade virtualenv
sudo pip install packaging
sudo pip install msrestazure
sudo pip install ansible[azure]
