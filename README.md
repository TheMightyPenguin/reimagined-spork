# reimagined-spork
Swag Editado desde UC

En git para poder hacer push con http, o sobre un proxy
cambiar el contenido del archivo .git/config de

[remote "origin"]
fetch = +refs/heads/*:refs/remotes/origin/*
url = http://git.repository.url/repo.git

por

[remote "origin"]
fetch = +refs/heads/*:refs/remotes/origin/*
url = http://username:password@git.repository.url/repo.git

O usar lo siguiente 

$ git config credential.helper store
$ git push http://example.com/repo.git
Username: <type your username>
Password: <type your password>

[several days later]
$ git push http://example.com/repo.git
[your credentials are used automatically]
