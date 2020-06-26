# Basis VBox

Baut aus einem Ubuntu Basis Image eine VBox
Creates a Fedora Workstation with additional development tools from basic image [generic/fedora32](https://app.vagrantup.com/generic/boxes/fedora32) 

## box bauen

1) remove old box if there exists already one (does not harm if no box exists)
`vagrant destroy`

2) build the box
`vagrant up`

3) export the box
`vagrant package --output nt-base-box-<VERSION>.<YYYYMMDD>.box`
example:
`vagrant package --output nt-base-box-fedora-32.20200626.box`

4) add box to VirtualBox to create the "real" environment
`vagrant box add --force --name dev-vm-<VERSION> nt-dev-vm-<VERSION>.<YYYYMMDD>.box`
Beispiel:
`vagrant box add --force --name nt-base-box-fedora-32 nt-base-box-fedora-32.20200626.box`
