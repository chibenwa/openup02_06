# Docker and Apache

In this practical work, we will see docker basis. You will know how to deploy a server in a docker container.

Hint :

Sometime to debug, it is usefull to enter a container. To do so : docker run -ti --entrypoint=/bin/bash image

## Exercice 1

Docker Hello world :

Create a docker container with an entry point that says Hello world.

## Exercice 2

Docker Hello world 2 :

Create a docker container that read the content of a file in a container and prints its content, setted to "Hello world".

## Exercice 3

Docker Hello world 3 :

Create a docker container that read the content of a file outside the container and prints its content.

## Exercice 4

Install Apache in a docker container. You should be able to render the default page in your browser.

Hint : You can start apache normally and then listen on a log file (/var/log/apache2/error.log) for instance

## Exercice 5

Replace this default page by yours ! (Hello world "your name"!) for instance.

Hint : you need to replace /var/www/html/index.html by yours !

## Exercice 6

Add a virtual host to Apache and a second site. You should be able to access both sites using your browser.

You should have the two site's domain names in your */etc/hosts* file, pointing to 127.0.0.1.

Hint : you need to secify a server name for /etc/apache2/sites-enabled/000-default.conf
