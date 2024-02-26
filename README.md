# Web_HW_2
docker ps -a  #вивисти всі контейнера
docker build . -t anzhelikakodlubovska/web_hw_2:0.0.1 #створення образа
docker images вивести список образів
docker push anzhelikakodlubovska/web_hw_2:0.0.1 #завантажити і образ на Docker hub
docker pull #вивантаження(скачування) образа з Docker hub
docker run --name HW4_cont -it anzhelikakodlubovska/web_hw_2:0.0.1 #запуск контейнера з іменем в інтерактивному режимі
docker start (ім'я_контейнера)  #Docker запускає контейнер зі стану, в якому він був зупинений
docker stop  (ім'я_контейнера)  #Контейнер переходить у стан "зупинено"
docker restart  #Docker зупиняє контейнер, а потім запускає його знову
docker rm  #видалити контейнер
docker attach (назва контейнера)  #увійти в контейнер
docker logs  #перегляд журналу виведення контейнера Docker
docker rmi (ідентифікатор_або_назва_образу)  #видалення образів Docker з системи
