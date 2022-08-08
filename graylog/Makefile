up:
	docker-compose up -d --build
down: 
	docker-compose stop
load: 
	docker exec g_mysql /bin/sh -c 'mysql -u root -pQwerty123 graylog </data/load.sql'