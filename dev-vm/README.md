﻿# Dev VBox

Die eigenliche VBox

## box bauen

1. copy localsettings.rb.example to localsettings.rb
cp localsettings.rb.example localsettings.rb

2. edit localsettings.rb

```
settings[:username] = 'arolfes'
settings[:diskPath] = 'C:\\Users\\arolfes\\VirtualBoxVMs\\workspace.vdi'

settings[:ssh_private_key_file_name] = 'DER_NAME_DEINER_SSH_PRIVATE_KEY_DATEI'
settings[:ssh_public_key_file_name] = 'DER_NAME_DEINER_SSH_PUBLIC_KEY_DATEI'
settings[:ssh_username] = 'DEFAULT_SSH_LOGIN_NAME'

settings[:git_user_name] = 'Dein Benutzer Namen Alias zB: arolfes'
settings[:git_user_email] = 'Deine Email Adresse zB: arolfes@users.noreply.github.com'
```

3. remove old box
`vagrant destroy`

4. start new box
`vagrant up`

# Predefined bash alias
* `alias gs="git status" `
* `alias gc="git clone" `
* `alias gf="git fetch" `
* `alias gp="git pull" `
* `alias gfp="git fetch && git pull" `
* `alias gl="git log --oneline" `
* `alias n="nautilus ." `
* `alias n^="nautilus ./.." `

