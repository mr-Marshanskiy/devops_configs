# DRF + Websockets + PSQL + Redis

* Define .env
* `docker-compose up -d`
* `docker-compose exec web python manage.py makemigrations`
* `docker-compose exec web python manage.py migrate`
* ````
  docker-compose exec -it web /bin/sh
  #/ python manage.py createsuperuser
  ````