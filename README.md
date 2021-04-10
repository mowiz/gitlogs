Test av git log
(Dessutom mixade authors ... delvis i detta repo, delvis var gitbash lägger global gitconfig?
- $ git config --global user.namne Per
- $ git config user.email me@perit.se

=== Global config

$ git config --show-scope --show-origin --get-all user.namne
global  file:C:/Users/Per Hall/.gitconfig       Per

```
$ git config --show-scope --show-origin --get-regexp user.*
global  file:C:/Users/Per Hall/.gitconfig       user.namne Per
local   file:.git/config        user.email me@perit.se
```

Hela listan, multipla platser

$ git config --show-scope --show-origin --list
system  file:C:/Program Files/Git/etc/gitconfig diff.astextplain.textconv=astextplain
system  file:C:/Program Files/Git/etc/gitconfig filter.lfs.clean=git-lfs clean -- %f
system  file:C:/Program Files/Git/etc/gitconfig filter.lfs.smudge=git-lfs smudge -- %f
system  file:C:/Program Files/Git/etc/gitconfig filter.lfs.process=git-lfs filter-process
system  file:C:/Program Files/Git/etc/gitconfig filter.lfs.required=true
system  file:C:/Program Files/Git/etc/gitconfig http.sslbackend=openssl
system  file:C:/Program Files/Git/etc/gitconfig http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
system  file:C:/Program Files/Git/etc/gitconfig core.autocrlf=true
system  file:C:/Program Files/Git/etc/gitconfig core.fscache=true
system  file:C:/Program Files/Git/etc/gitconfig core.symlinks=false
system  file:C:/Program Files/Git/etc/gitconfig pull.rebase=false
system  file:C:/Program Files/Git/etc/gitconfig credential.helper=manager-core
system  file:C:/Program Files/Git/etc/gitconfig credential.https://dev.azure.com.usehttppath=true
global  file:C:/Users/Per Hall/.gitconfig       user.namne=Per
local   file:.git/config        core.repositoryformatversion=0
local   file:.git/config        core.filemode=false
local   file:.git/config        core.bare=false
local   file:.git/config        core.logallrefupdates=true
local   file:.git/config        core.symlinks=false
local   file:.git/config        core.ignorecase=true
local   file:.git/config        user.email=me@perit.se

