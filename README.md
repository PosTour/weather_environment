Репозиторий содержит конфигурацию для создания и запуска Docker-контейнера для приложения отслеживания погодных явлений

Использование:

1. Клонируйте репозиторий: git clone https://github.com/PosTour/weather_environment.git
2. Постройте необходимые образы
3. Для сборки контейнера используйте команду: docker compose up (docker-compose up -d)
4. При необходимости остановить работу контейнера используйте команду: docker compose down

Для реализации полного функционала приложения необходима интеграция с сервисами https://github.com/PosTour/weather и https://github.com/PosTour/weather_bot