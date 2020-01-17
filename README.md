# First App in Docker

This is very simple NGINX website.

It's mostly used as a sample application.

To use it:

Build it:
`docker build -t first_app_in_docker .`

Run it:
`docker container run -d -p 80:80 first_app_in_docker`
