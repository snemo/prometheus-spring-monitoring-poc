# Spring BOOT Prometheus integration example

## Info about Prometheus and Grafana docker
https://github.com/stefanprodan/dockprom
    
## Build project
    ./gradlew clean build dockerBuild
    
## Build docker image
    cd build/docker
    docker build -t springapp .