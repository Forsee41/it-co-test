# IT-CO Test Project

## Deploy

1. Install docker and docker-compose
1. Run `git clone https://github.com/Forsee41/it-co-test.git --recurse-submodules`
1. Copy docker-compose.yml in a new prod file `cp docker-compose.yml prod.yml`
1. Change frontend `VUE_APP_BASEURL` build arg to `your_hostname/api`
1. Run `sudo docker-compose -f prod.yml up -d`
