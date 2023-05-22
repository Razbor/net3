# net3

   1. Подключитесь к публичному маршрутизатору в интернет. Найдите маршрут к вашему публичному IP.

telnet route-views.routeviews.org
Username: rviews
show ip route x.x.x.x/32
show bgp x.x.x.x/32

![изображение](https://github.com/Razbor/net3/assets/19568831/b82bc899-1a74-49fa-8112-0cca9835fc87)

![изображение](https://github.com/Razbor/net3/assets/19568831/dda6650c-9425-4c89-a579-7ac11c7f6643)


  2. Создайте dummy-интерфейс в Ubuntu. Добавьте несколько статических маршрутов. Проверьте таблицу маршрутизации.

![изображение](https://github.com/Razbor/net3/assets/19568831/dd09c317-5414-4a23-bf61-86e41e55646e)


![изображение](https://github.com/Razbor/net3/assets/19568831/19e1e125-302c-4124-abdb-21e03d1405fd)


  3. Проверьте открытые TCP-порты в Ubuntu. Какие протоколы и приложения используют эти порты? Приведите несколько примеров.
  
![изображение](https://github.com/Razbor/net3/assets/19568831/62b5c255-bdc1-4cfe-b94f-119a443891c9)
22 SSH
9100  Node_exporter
19999 netdata

![изображение](https://github.com/Razbor/net3/assets/19568831/fa1d7f1e-335b-407a-abdb-1ee5ff259fd7)

  4. Проверьте используемые UDP-сокеты в Ubuntu. Какие протоколы и приложения используют эти порты?
  
![изображение](https://github.com/Razbor/net3/assets/19568831/c373f945-d869-44ad-aa1f-5be156cdaa23)

53 DNS
68 bootpc

   5. Используя diagrams.net, создайте L3-диаграмму вашей домашней сети или любой другой сети, с которой вы работали.
   6. 
![Диаграмма без названия drawio](https://github.com/Razbor/net3/assets/19568831/c8c5312b-dfdc-411c-a888-a60cae435419)

