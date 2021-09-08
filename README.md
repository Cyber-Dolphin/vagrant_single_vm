# Vagrant single VM

Get start:

vagrant up

---

Connect ssh:

vagrant ssh 

---

Stop VM:

vagrant halt

---

Destroy VM:

vagrant destroy

---

Add box:

vagrant box add --name=<BOX_NAME> <PATH_BOX>

Example:

vagrant box add --name=cyberdolphin_debian F:\packer_debian\cyberdolphin_debian.box

P.S. For windows 10, specify the full path

---

Install new vbox guest plugin:

vagrant plugin install vagrant-vbguest

---

Reload VM:

vagrant reload --provision

---

Init new Vagrantfile

vagrant init <BOX_NAME> 

Example:

vagrant init cyberdolphin_debian
