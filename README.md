# laravel-docker
my docker container to host multiple laravel sites

Add app1.laradock.com & app2.laradock.com to etc/host

Run docker-compose build

Run docker-compose up -d

Now both apps will be available under http://app1.laradock.com:8080/ & http://app1.laradock.com:8080/

phpMyAdmin will be available at http://localhost:8088/

to add more sites, please add extra server blocks to docker/conf/nginx.conf
