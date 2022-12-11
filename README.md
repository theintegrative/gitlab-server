# Gitlab server

Links to documentation: https://docs.gitlab.com/ee/install/docker.html

## How to use

### To the remote machine
``` /bin/bash
ansible-playbook -i home-lab0, -bK playbook.yml
```

### Locally at the remote machine
Optional when new updates are pushed to github:
``` /bin/bash
ansible-playbook --connection=local -i localhost, -bK playbook.yml
```

For using dockerswarm
``` /bin/bash
docker stack deploy --compose-file docker-compose.yml mygitlab
```
