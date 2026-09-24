готов
1) Учебный сервис предварительной оценки заявки на заём под ПТС: принимает VIN, год выпуска, пробег, оценочную стоимость, сумму и срок, считает LTV и возвращает approve / review / reject.
2) Makefile: make help, make up, make down, make ps, make logs, make install, make test, make lint, make seed; docker-compose.yml: backend запускает PHP-сервер на ${APP_PORT:-8080}:8080, db запускает MySQL 8 на ${DB_PORT:-3307}:3306.
3) Решение approve / review / reject считается в папке backend/src/Domain, в DecisionEngine.php.
модель: training-2026-09-gpt-5.6-terra
