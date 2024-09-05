# ubuntu-server-test

Basic Project Description

This repository contains a basic ubuntu server setup hosted with VirtualBox. It a single application which can be assessed on 'http://192.168.100.59'. 

login-name: olawale-host
password: olawale-host

Features

A CI/CD pipeline is activated for this server on gitea "https://zone01normandie.org/git/"


Basic Project S

gitea, docker and a drone server is download in the '/srv/' path server root. thus: a docker-compose.yml file is configured to enable connection between gitea and the drone server. this requires the OAuth credentials from the gitea account so our network can easily connect to the repositories we need. 

Note:

- CI/CD Pipeline is configured such that when a push occured in the master branch.
- The webhook secret is similar to the 'DRONE_RPC_SECRET' used in the docker-composer.yml file.
- Apache2 used for App hosting


Conclusion:

This project aided in learning ubuntu server configuration and application hosting, CI/CD pipeline, Docker, Drone Servers and the uses of Webhooks.

Sulaiman