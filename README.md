#Instalación

Clonar repo git remote add origin https://github.com/NIXON315/parcialdocker.git
Ejecutar en la raiz 

$ docker-compose build app
$ docker-compose up -d
$ docker-compose exec app ls -l
$ docker-compose exec app composer install
$ docker-compose exec app php artisan key:generate

http://server_domain_or_IP:8000

Datos de acceso admin Itp12345678

