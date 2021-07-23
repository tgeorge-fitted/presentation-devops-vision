# Presentation - DevOps and Infrastructure Vision

## Run

    docker build . -t pres-devops-vision:latest
    docker run --rm -p 8080:8000 pres-devops-vision:latest

## Develop

    docker run -d --rm -p 8080:8000 -v $HOME/Development/tgeorge-fitted/presentation-devops-vision/presentation:/presentation pres-devops-vision:latest

