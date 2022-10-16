# ***Ansible***

### Install Ansible 

> ansible install on readhat family
```bash
yum update -y
yum install epel-release -y
yum install ansible -y
```

> ansible install on debain 
```bash
sudo apt update -y
sudo apt install software-properties-common -y
sudo apt-add-repository --yes --update ppa:ansible/ansible
sudo apt install ansible -y
ansible --version
```
> ansible install using binary
```bash
sudo yum install python3 -y
curl -O https://bootstrap.pypa.io/pip/3.6/get-pip.py
python3 get-pip.py --user
python3 -m pip install --user ansible
python3 -m pip install --upgrade --user ansible
```
---
