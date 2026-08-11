# [Immich]

Date: [07/2026]
Status: [completed]

---

## Overview

this project involved installing Immich, an open-source, self-hosted photo and video storage solution through Docker.

## Environment

Device: [Dell OptiPlex 3060]
OS: [Ubuntu Server 26.04 LTS (64-bit)]
Storage: [2x WD Red Plus 4TB HDDs in external dual-bay enclosure (independent/JBOD mode)]
IP Address: [private]

Steps

1. [create a directory to store immich components (named: ./immich-app) by entering: mkdir ./immich-app]
2. [move to the immich directory by entering: cd ./immich-app]
3. [download docker compose by entering: sudo wget -0 docker-compose.yml https://github.com/immichapp/immich/releases/latest/download/docker-compose.yml]
4. [get .env file by entering: sudo wget -0 .env https://github.com/immich-app/immich/releases/latest/download/example.env]
5. [populate .env with custom values by entering: nano | paste .env template from immich website (https://docs.immich.app/install/docker-compose) and modify time zone and default password for security]
6. [make a directory for ./library by entering: mkdir ./library]
7. [save nano file and execute the container in docker by entering: docker compose up -d]
8. [enter local host ip address in browser and create immich account]

## Issues Encountered
-none

## Result
-fully functional self-hosted photo and video storage solution

## Notes
-install tailscale and cloudeflare to access immich from outside the network
