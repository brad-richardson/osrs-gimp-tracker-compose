
`git clone https://github.com/Rachnus/osrs-gimp-tracker-frontend`

`git clone https://github.com/Rachnus/osrs-gimp-tracker-backend`

Update values in .env to match where the server is hosted and secure password

`docker-compose --build up -d`

To update - git pull in both cloned repo folders, run `docker-compose down && docker-compose --build up -d`

