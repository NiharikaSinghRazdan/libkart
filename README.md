Follow below process to bring up server on your local system:

1. git clone repository

2. enter the directory and run > docker-compose up 

3. open another session and run > 

docker-compose exec web python manage.py migrate

docker-compose exec web python3 manage.py collectstatic

docker-compose exec web python3 manage.py populatedb --createsuperuser

