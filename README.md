## How to install this (don't)

- **(!DOCKER REQUIRED!)** </br>
1 - Get out of this directory (cd ..) </br>
2 - git clone https://github.com/NcH9/diploma-hotel.git </br>
3 - </br>
cd dh-dev-env </br>
docker compose build </br>
docker compose up -d </br>
docker run --rm -v $(pwd):/app composer install </br>
4 - cd ../diploma-hotel/frontend </br>
5 - npm install </br>
