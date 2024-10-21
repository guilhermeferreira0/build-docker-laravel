DOCKER COMMANDS

- Starting: docker-compose up -d server
- Database: docker-compose run --rm artisan migrate
- Npm: docker-compose run --rm npm install
- Remove All: docker-compose down --rmi all -v