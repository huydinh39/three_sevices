# three_sevices
Includes 3 services: mysql:8.0.32, phpmyadmin:5.2.1, node-red:2.2.2.

1. Install docker and docker compose on your machine.
2. Run following command same folder with docker-compose.yml:
docker compose up -d 
3. Access Node-red:
	http://localhost:18800
4. Access phpMyAdmin:
	http://localhost:33060, user: root, pass: root
5. Stop and remove services: 
docker compose down