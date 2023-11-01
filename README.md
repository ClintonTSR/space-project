# space-project

### Prerequisite: Docker
https://docs.docker.com/engine/install/

### Installation Guide
Download the docker-compose.yaml from this repo

Clone the repositories from \
https://github.com/ClintonTSR/space-project-app \
https://github.com/ClintonTSR/space-project-api \
https://github.com/ClintonTSR/space-project-cron 

Put the cloned repositories into the same folder as docker-compose.yaml, \
the folder structure should look like this:
```
app (root folder)
 | - docker-compose.yaml
 | - space-project-app
 | - space-project-api
 | - space-project-cron
```

Open Terminal from that folder \
Execute the following two commands: 

`docker-compose build` 

`docker-compose up`

### How to use
Once installation completed, visit http://localhost:3000 to access the web page.
