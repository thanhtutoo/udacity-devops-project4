[![thanhtutoo](https://circleci.com/gh/thanhtutoo/udacity-devops-project4.svg?style=svg)](https://circleci.com/gh/thanhtutoo/udacity-devops-project4)
## Project Overview

This project is about Machine Learning Microservice API which is written in python and wraped with docker and kubernete.
### Steps to run
1. git clone git@github.com:thanhtutoo/udacity-devops-project4.git
2. cd udacity-devops-project4
3. make setup
4. make install
5. make lint
6. ./run_docker.sh
7. ./make_prediction.sh
8. ./upload_docker.sh
9. ./run_kubernetes.sh
10. ./make_prediction.sh

### Make files
* app.py (the application file)
* Makefile (the file that set up and install dependencies for the project)
* run_docker.sh (build docker image and run)
* make_prediction.sh (the file that curl request to the app)
* upload_docker.sh (the file that upload to the docker hub)
* run_kubernetes.sh (the file that set up kubernetes cluster)

