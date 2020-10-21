# api-platform-admin-exemple

steps for using project:
- run command "composer install"
- run command "yarn install"
- create database " php bin/console doctrine:database:create "
- migrate db " php bin/console doctrine:migrations:migrate "
- run encore " yarn encore dev --watch "
- start server " php bin/console server:run "
and that's it, go to " http://127.0.0.1:8000/admin "

PS : using " php -S 127.0.0.1:3000 -t public " command will occur an error. 
