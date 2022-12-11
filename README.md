# Gitlab server

Links to documentation: https://docs.gitlab.com/ee/install/docker.html

## How to use

``` /bin/bash
ansible-playbook -i home-lab0, -bK playbook.yml

docker stack deploy --compose-file docker-compose.yml mygitlab
```
