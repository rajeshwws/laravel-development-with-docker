Install Laravel on Mac for beginners using Docker. (see shortcuts below to key points)  how to create a new Laravel project, and set up a development environment with Docker.

Key Topics:
- Install Laravel Via Composer Create-Project
- Using Artisan to perform tasks in Laravel
- Create docker-compose.yaml
- Create Dockerfile
- Use Laravel with Docker container

Installation
Development environment requirements :

Docker >= 17.06 CE
Docker Compose
Setting up your development environment on your local machine :

$ git clone https://github.com/rajeshwws/laravel-development-with-docker.git

$ cd laravel-development-with-docker

$ cp .env.example .env

$ docker-compose run --rm --no-deps webapp composer install

$ docker-compose up -d

Now you can access the application via http://localhost:8000.
