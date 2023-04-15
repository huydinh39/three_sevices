# three_sevices
Includes 3 services: mysql:8.0.32, phpmyadmin:5.2.1, node-red:2.2.2.

1. Install docker and docker compose on your machine.
2. Run following command same folder with docker-compose.yml:<br/>
	**docker compose up -d**
3. Access Node-red:<br/>
	http://localhost:18800
4. Access phpMyAdmin:<br/>
	http://localhost:33060<br/>
	user: root<br/>
	pass: root
5. Stop and remove services:<br/>
	**docker compose down**