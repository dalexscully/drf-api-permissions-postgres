# Permissions & Postgresql

## Author: Domaine Scully

## Features Tasks and Requirements

General

- You have been supplied with two demos, each presenting a key new feature.
  - blogapi-permissions demonstrates how to restrict access to portions of your APIs data.
  - blogapi-postgres demonstrates switching over to using postgres vs sqlite
- Your job is to merge the functionality of both demos.
- Customize your project to use different application features/models than Blog and Post

Django REST Framework

- Make your site a DRF powered API as you did in previous lab.
- Adjust project's permissions so that only authenticated user's have access to API.
- Add a custom permission so that only author of blog post can update or delete it.
- Add ability to switch user's directly from browsable API.

Docker

- NOTE Refer to demo for built out Dockerfile and docker-compose.yml examples.
- create Dockerfile based off python:3.11-slim
- create docker-compose.yml to run Django app as a web service.
- enter docker-compose up --build to start your site.
- add postgres 11 as a service

  - Note: It is not required to include a volume so that data can persist when container is shut down.

- Go to browsable api and confirm site properly restricts users based on their permissions.
