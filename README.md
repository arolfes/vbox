
# Vagrant Box

build up an fedora linux with vagrant and virtual box.

## Details


## Vorraussetzungen

- Windows Management Framework 4.0 und DotNet Framework >4.5 - lokale Adminrechte reichen aus um das WMF upzudaten.  
  Sie dieser Link http://mikefrobbins.com/2015/01/08/how-to-check-the-powershell-version-and-install-a-new-version
  
- [VirtualBox 6.1.2](https://www.virtualbox.org/)  
  **Achtung:** Wenn man VirtualBox 5.2.6 verwendet, muss man ein anderes GuestAdditionsIso runter laden.  
  *The Guest Additions which come with VirtualBox 5.2.6 and 5.1.32 do not work properly on Linux guests with 3D enabled.*  
  https://www.virtualbox.org/wiki/Downloads
  
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


