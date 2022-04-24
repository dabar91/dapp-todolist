# dapp-todolist

Docker container setup

- docker pull ubuntu
- docker run --name dapp_todolist -itd -p 8081:8080 -p 7546:8545 -v {$HOST_FOLDER_PATH}:{$CONTAINER_FOLDER_PATH} {DOCKER_IMAGE_ID}
- docker exec -it {CONTAINER_ID} /bin/bash


Install Container dependencies:

- apt-get update
- apt-get install -y nodejs npm 
- npm install -g ganache truffle


#START GANACHE
ganache -h 0.0.0.0
