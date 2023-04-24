# three_sevices
Includes 3 services: mysql:8.0.32, phpmyadmin:5.2.1, node-red:2.2.2.

1. Install docker and docker compose on your machine.
2. Clone this Repositories:<br/>
	git clone https://github.com/huydinh39/three_sevices
3. Run following command same folder with docker-compose.yml:
```
	docker compose up -d
```
4. Access Node-red:
```
	http://localhost:18800
```
5. Access phpMyAdmin:
```
	http://localhost:33060
```
	user: root<br/>
	pass: root
6. Stop and remove services:<br/>
```
	docker compose down
```