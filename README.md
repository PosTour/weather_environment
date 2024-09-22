Репозиторий содержит конфигурацию для создания и запуска Docker-контейнера для приложения отслеживания погодных явлений

Использование:

1. Клонируйте репозиторий: git clone https://github.com/PosTour/weather_environment.git
2. Постройте необходимые образы
3. Для сборки контейнера используйте команду: docker compose up (docker-compose up -d)
4. При необходимости остановить работу контейнера используйте команду: docker compose down

Подразумевается интеграция со следующими сервисами:<br />
https://github.com/PosTour/weather_bot<br />
https://github.com/PosTour/WeatherForecastAPI<br />
https://github.com/PosTour/weather