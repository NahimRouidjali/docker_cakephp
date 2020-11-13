# Docker CakePHP PHP 7.4 MySQL
## Requirements
**Composer** (2.0+)  
**Docker** (Unix or Windows)  
**Docker Compose**
## Settings .env
You need to change the environment variable for mysql in .env file
```sh
MYSQL_ROOT_PASSWORD=root
MYSQL_DATABASE=myapp
MYSQL_USER=myapp
MYSQL_PASSWORD=myapp
```

## Deployment

```sh
git clone https://github.com/NahimRouidjali/docker_cakephp.git; // Clone repo
cd docker_cakephp
composer create-project --prefer-dist cakephp/app cakephp // Generate cakephp project
cd docker
docker-compose up -d // Deploy and run containers
```
Go to http://localhost:8180
