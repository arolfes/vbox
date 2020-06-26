
# Vagrant Box

build up an fedora linux with vagrant and virtual box.

# how to build and run

1) change dir into base-box
`vbox> cd base-box`

2) execute all 4 steps from [base-box/README.md](base-box/README.md)

## Details


## Vorraussetzungen

- Windows Management Framework 4.0 und DotNet Framework >4.5 - lokale Adminrechte reichen aus um das WMF upzudaten.  
  Sie dieser Link http://mikefrobbins.com/2015/01/08/how-to-check-the-powershell-version-and-install-a-new-version
  
- [VirtualBox 6.1.2](https://www.virtualbox.org/)  
  
- [Vagrant 2.2.7](https://www.vagrantup.com/)
- Vagrant Plugins
    - vagrant-cachier (1.2.1)
    - vagrant-persistent-storage (0.0.48)
    - vagrant-vbguest (0.23.0)

*Die oben genannten Versionsnummern sind getestet.  
Es müsste auch mit etwas älteren Versionsnummern gehen. (Zum Beispiel VirtualBox 5.x und Vagrant 1.9.x)  
Bei den Vagrant Plugin Versionen muss man dann aufpassen. Da gibt es Abhängigkeiten*  



### links
http://mikefrobbins.com/2015/01/08/how-to-check-the-powershell-version-and-install-a-new-version/

- http://kvz.io/blog/2013/01/16/vagrant-tip-keep-virtualbox-guest-additions-in-sync/
- https://techblog.covermymeds.com/infrastructure/versioned-vagrant-boxes-privately/
- https://www.vagrantup.com/docs/vagrantfile/machine_settings.html


- https://app.vagrantup.com/boxes/search


