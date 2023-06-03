W zadaniu plik 'docker-compose.yml' umożliwia uruchomienie usługi za pomocą docker compose.

Polecenie: 
docker compose up -d

Po zakończeniu procesu budowania i uruchamiania, usługi będą dostępne pod adresami:
nginx: localhost:6666
phpMyAdmin: localhost:6001

Polecenie do zatrzymania usługi:
docker compose down

Struktura katalogów:
-nginx - zawiera Dockerfile, konfigurację nginx i plik index.php
-php - zawiera Dockerfile dla php
-mysql - zawiera Dockerfile dla mysql
-phpmyadmin - zawiera Dockerfile dla phpmyadmin

Serwer wyświetla stronę startową index.php.