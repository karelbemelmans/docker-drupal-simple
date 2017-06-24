# Drupal PHP Simple container

This is an example Dockerfile that shows how to run a Docker container with the PHP built-in webserver.

Details about the web server: http://php.net/manual/en/features.commandline.webserver.php

## Run the container

docker run -p 8080:8080 -it karelbemelmans/drupal-simple

And then browse to http://localhost:8080/ to test it.

## Disclaimer

Do not use this for production. It's not a valid replacement for Apache or nginx.
