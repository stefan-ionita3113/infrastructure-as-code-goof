FROM php:8.1-cli
COPY src/index.php /usr/src/myapp/index.php
COPY src/cards.json /db/cards.json
WORKDIR /usr/src/myapp
CMD [ "php", "-S", "0.0.0.0:8080" ]
