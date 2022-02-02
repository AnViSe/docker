#Создание образа
docker build -t fastapi .

#Запуск образа
docker run --name first -d --rm fastapi
docker run --rm --name first -p 8000:8000 fastapi

#Список контейнеров
docker ps -a

#Остановка контейнера по имени
docker stop first

#Список образов
docker images