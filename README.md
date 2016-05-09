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

Editado
