# Fedora 40 playbook
**My fedora go to setup after fresh install**

How to install?
```sh
sudo dnf install git-core ansible -y
git clone https://github.com/SoloSaravanan/Ansible-fedora
cd Ansible-fedora
```

Replace password with your password
```sh
ansible-playbook fedora.yaml -e "ansible_sudo_pass= password"
```