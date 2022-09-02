Containerize This: PHP/Apache/MySQL/MongoDB
Intro
Continuing with the Containerize, we're looking at common web application technologies and how they can be used within Docker containers effectively. PHP/Apache/MySQL/MongoDB have a very large market share on content management systems and web applications on the internet, and with so many developers using these technologies, there is a lot of interest to modernize the way that they use them from from local development all the way to production. 

/Docker-Compose-php-mysql-mongodb-apache2/
├── apache2
│   ├── Dockerfile
│   └── demo.apache.conf
├── docker-compose.yml
├── dockerfile
│   └── php.dockerfile
└── src
|    └── index.php
├── env

Once this structure is replicated or cloned with these files, and Docker installed locally, you can simply run "docker-compose up" from the root of the project to run this entire demo, and point your browser (or curl) to http://localhost:80 to see the demo.