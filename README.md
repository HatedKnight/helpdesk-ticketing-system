# helpdesk-ticketing-system
This repository contains the necessary configuration files to deploy an osTicket helpdesk ticketing system using Docker and Docker Compose. osTicket is a widely-used open-source support ticket system that provides an efficient way to manage, organize, and streamline customer support requests.

## Features
    -Easy deployment using Docker and Docker Compose
    -MariaDB as the database backend
    -Scalable and easy to update
    
## Deployment
1. Clone this repository to your local machine:
    git clone https://github.com/yourusername/osticket-docker.git
    cd osticket-docker

2. Start the osTicket helpdesk system:
    docker-compose up -d

3. Access the osTicket web interface by navigating to http://localhost:8080 in your browser. 
4. After the installation, sign in to the osTicket admin panel to configure your helpdesk settings, email integration, and user accounts.

## Updating osTicket

1. docker-compose down
2. docker pull campbellsoftwaresolutions/osticket
3. docker-compose up -d
