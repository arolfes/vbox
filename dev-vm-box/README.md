# Basis VBox für Entwickler

Baut aus einem Ubuntu Basis Image eine VBox

## box bauen

1) alte box entfernen
`vagrant destroy`

2) box bauen
`vagrant up`

3) box exportieren
`vagrant package --output nt-dev-vm-<VERSION>.<YYYYMMDD>.box`
Beispiel:
`vagrant package --output nt-dev-vm-18.04-bionicbeaver64.20200402.box`

4) Box zu vagrant hinzufügen um das erstellen der lokalen Box auszuprobieren
`vagrant box add --force --name dev-vm-<VERSION> nt-dev-vm-<VERSION>.<YYYYMMDD>.box`
Beispiel:
`vagrant box add --force --name dev-vm-18.04-bionicbeaver64 nt-dev-vm-18.04-bionicbeaver64.20200402.box`
