# Web_HW_2
docker ps -a  вивисти всі контейнера
docker build . -t anzhelikakodlubovska/web_hw_2:0.0.1 #створення образа
docker images #вивести список образів
docker push anzhelikakodlubovska/web_hw_2:0.0.1 #завантажити і образ на Docker hub
docker pull #вивантаження(скачування) образа з Docker hub
docker run --name HW4_cont -it anzhelikakodlubovska/web_hw_2:0.0.1 #запуск контейнера з іменем в інтерактивному режимі