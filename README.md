# Installing wordpress via container... follow the commands

## Description

This repository contains a Docker Compose configuration for quickly setting up a WordPress environment with MySQL using Docker containers.

## Prerequisites
Make sure you have the following installed on your system:

- [killerkoda](https://killercoda.com/)
- [Docker Compose]

## Create a two directory for wordpress files and SQL files
```bash
  mkdir wordpress db

## Make the system UP

  docker-compose up -d

## Check the system is running propely or not?

  docker images
  docker ps
