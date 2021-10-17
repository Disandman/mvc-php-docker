# mvc-v2.0
 MVC V.2

Первый запуск приложения:
1) docker-compose -f "docker-compose.yml" up -d --build
2) docker-compose exec app composer install
3) docker-compose exec app php vendor/robmorgan/phinx/bin/phinx migrate
