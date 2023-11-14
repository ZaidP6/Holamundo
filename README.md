# Un repositorio de Java

Hola Luismi, este es un repositorio que contiene código java.

git log --oneline
  4e1c6b2 (HEAD -> main, tag: v1.0) translate println
  7dcbf71 Merge branch 'main' of https://github.com/ZaidP6/Holamundo
  1d6bfc0 guaaaaauuu
  4498961 Update README.md
  f6bc3ca Create README.md
  103400a holamundo
  
git tag -a 4498961  //??? buscra como hacer un tag de un commit anterior

git push origin --tags      //para subir todos los tags al repo

git config --list   // comprobar en casa las cosas

diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/etc/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
core.editor=notepad
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=ZaidP6
user.email=aguilar.dimar23@triana.salesianos.edu
user.name=Pilar
user.name=Pilar
core.editor=code --wait
merge.tool==
mergetool.vscode.cmd=code --wait
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true
remote.origin.url=https://github.com/ZaidP6/Holamundo.git
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*
branch.main.remote=origin
branch.main.merge=refs/heads/main
