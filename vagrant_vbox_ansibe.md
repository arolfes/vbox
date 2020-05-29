# Show and Tell 28.05.2020

## vagrant

* wird benutzt um virtuelle maschinenen zu erstellen und verwalten
* zu verstehen als Wrapper zwischen der eigentlichen VM und der Provisionierungssoftware

* ist in ruby geschrieben
* stammt von HashiCorp

https://de.wikipedia.org/wiki/Vagrant_(Software)

https://www.vagrantup.com/

### Kommandos

* `vagrant up`
* `vagrant up --provision`
* `vagrant provision`
* `vagrant destroy -f`
* `vagrant halt`

### vagrant file

_zeigen und besprechen_

### vagrant plugins

* `vagrant plugin list`
* https://github.com/tmatilai/vagrant-proxyconf
* https://github.com/dotless-de/vagrant-vbguest
* https://github.com/kusnier/vagrant-persistent-storage
* https://github.com/fgrehm/vagrant-cachier


## virtual box

* Virtualisierungssoftware von Oracle
* wird benutzt um auf einen Betriebssystem ein anderes zu simulieren
  * Beispiel: Auf Windows läuft plötzlich ein echtes linux

https://de.wikipedia.org/wiki/VirtualBox
https://www.virtualbox.org/wiki/Downloads

## ansible

* automatische konfiguration und administration von Betriebssystemen
* es kümmert sich um 
  * Softwareverteilung
  * Kommandoausführung
  * Konfigurationsmanagement
* alternative zu puppet, chef, terraform etc...
* in python implementet

https://de.wikipedia.org/wiki/Ansible

https://www.ansible.com/

### playbook

yaml format

definiert wie das betriebssystem bestükt und konfiguriert werden soll

### ansible galaxy

* enthält vordefinierte artefakte die sich einfach einbinden lassen
* https://galaxy.ansible.com/
