# SpyGlass v2
Second generation of my SpyGlass Docker Stack for monitoring

## Table of Contents

- [SpyGlass v2](#spyglass-v2)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Getting Started](#getting-started)
  - [Usage](#usage)

## Introduction
SpyGlass was started to provide a learning platform for Docker Swarm and using open-source tools for monitoring of various systems in my home lab.  This served as a great platform, but the learnings coming from that is what drives SpyGlass v2. Not only will newer components be used, but newer, more dynamic techniques will be used to allow for public distribution without releasing any pivate information.

## Getting Started
Clone this repository to a machine that has Docker Compose installed and is running Docker 24+ in Swarm mode.

## Usage
Copy the example-compose.yml to docker-compose.yml and edit, setting the environmental variables as appropriate for the services defined.
Copy all files from the *conf-example* directory to *conf* (you will need to create this) and edit only as needed.  Most files will not need to be edited as we will pass in environmental variables via the docker-compose.yml file.