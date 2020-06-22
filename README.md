## Docker-compose Wordpres Boilerplate

this docker-compose is a boilerplate for wordpress service. Wordpres, mysql and phpmyadmin already bundled and updated to fix some deployment issue in wordpress when using docker-compose (take a look at known issues)


### Known issues

- Docker sometimes fail when contact db, it really recommended to using root user for mysql instead of mysql ordinary user. 
- For wordpress some restriction in php need to be changed, like max upload files etc.

### what fixed
- Added custom config at ```web-config/uploads.ini``` folder that will be automaticly loaded in volume. Take a look at this folder for further information. (fixed 2nd issues)
 
###### copyrigt &copy; 2020 <a href="https://panjibaskoro.web.id">panjibaskoro.web.id</a>