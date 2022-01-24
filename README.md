# Nextcloud in Docker Compose
## Introduction
This repository contains a Docker compose file for running Nextcloud with MariaDB. It contains a sample file with some variables that can be changed to your liking.

## Preparation
The `docker-compose.yml` file can be downloaded and saved somewhere on your drive or server. Make sure to have a separate folder for the configuration and data files. Change the volumes and environment to fit your situation. 

## Starting It Up
You can launch the file with `docker-compose up`. After it has finished starting, which should not take very long, you can go to your browser and check if it is running properly.
You can check by going to `127.0.0.1:4433` if you're on the same machine. Replace `127.0.0.1` with the ip address in question if you have it hosted on another machine.

After you are sure that it all works, you can keep Nextcloud running in the background, just run `docker-compose up -d`.

## More Information
For a more in depth guide on how this works, you can go to [selfhostedheaven.com](https://selfhostedheaven.com/posts/20220116-moving-google-contacts-and-calendar-to-nextcloud/).
