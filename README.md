### Описание:
-------------------------------------------------------------------

В связи с популярности веб-сервера nginx Я давно начал использовать
этот веб сервер и за годы практики Я узнал много best practices, 
который Я бы хотел с вами делиться, поэтому настроил этот конфиг
nginx.conf, создал эту репозиторию и сделал общедоступным, можете
использовать этот конфиг где хотите ...

#### В nginx-e были изменены и включены такие параметры:

> multi_accept **on**

> use epoll

> gzip **on**

> gzip_comp_level **4**

#### а также были отключены следующие параметры:

> server_tokens **off**

> reset_timedout_connection **on**

> timeout **30s**

#### Мой репозиторий доступен на самых популярных хостингах таких как:

![](https://www.vectorlogo.zone/logos/gitlab/gitlab-icon.svg)

![](https://cdn.iconscout.com/icon/free/png-64/github-170-1175028.png)

![](https://cdn.iconscout.com/icon/free/png-64/bitbucket-3628654-3029879.png)


#### И доступен по следующим ссылкам:

*если хотите скачать с GitLab:*

[https url GitLab](https://gitlab.rebrainme.com/devops_users_repos/2422/rebrain-devops-task1.git)

[ssh url GitLab](git@gitlab.rebrainme.com:devops_users_repos/2422/rebrain-devops-task1.git)




*если хотите скачать с GitHub:*

[https url GitHub](https://github.com/komronu/rebrain-devops-task1.git)

[ssh url GitHub](git@github.com:komronu/rebrain-devops-task1.git)




*если хотите скачать с Bitbucket:*

git clone git@bitbucket.org:komronu/rebrain-devops-task1.git

git clone https://komronu@bitbucket.org/komronu/rebrain-devops-task1.git

