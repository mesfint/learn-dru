# Drupal Docker App

## Project Overview

This repository contains a Dockerized Drupal application. It includes both Drupal and MySQL services, which are managed using Docker Compose. This setup allows you to quickly deploy a Drupal site with a pre-configured database.

## Getting Started

To run this Drupal application on your local machine, follow these steps:

### Prerequisites

- **Docker**: Make sure Docker is installed on your system. You can download and install Docker from [Docker's official site](https://docs.docker.com/get-docker/).

- **Docker Compose**: This project uses Docker Compose to manage multi-container Docker applications. Follow the [installation instructions](https://docs.docker.com/compose/install/) if Docker Compose is not already installed.

### Pull the Docker Image

First, you need to pull the Docker image from Docker Hub:

```bash
docker pull mesfinm/drupal-app:initial-setup
