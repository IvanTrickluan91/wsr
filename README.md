![photo_2022-02-11_20-49-32](https://user-images.githubusercontent.com/97450080/153623300-d00c6a25-13e8-4ae5-95fe-c3cc2a1bea1c.jpg)

![photo_2022-02-11_20-49-52](https://user-images.githubusercontent.com/97450080/153623348-9f6c90dd-d8c8-4e1a-b213-59798c46a014.jpg)

![photo_2022-02-11_20-50-01](https://user-images.githubusercontent.com/97450080/153623377-9fa5678d-ccf8-4b5b-8c53-5c4b95462389.jpg)

![photo_2022-02-11_20-50-09](https://user-images.githubusercontent.com/97450080/153623402-fb44254e-7a3b-4611-b973-280ceadc5ac8.jpg)

Также все эти конфиги лежат в репе ансибл.
![photo_2022-02-11_20-50-26](https://user-images.githubusercontent.com/97450080/153623448-4ff1343f-03cd-4ba6-b827-f35ce796cee3.jpg)

это для reverse proxy ключик


![photo_2022-02-11_20-50-58](https://user-images.githubusercontent.com/97450080/153623555-29153876-9524-49d2-99b7-f77a40f38091.jpg)

(iptables -t nat -A POSTROUTING -s 172.20.0.0/16 -o ens192 -j MASQUERADE)

![photo_2022-02-11_20-53-09](https://user-images.githubusercontent.com/97450080/153623960-bfc80bb7-e37d-425a-9dac-98f355eed49c.jpg)

добавили сенд хостнейм чтобы отправлять хотснейм такой вот не знаю зачем)))


![photo_2022-02-11_20-53-25](https://user-images.githubusercontent.com/97450080/153624019-7337d18e-708e-4462-8037-1e5ff01ea96a.jpg)

а для того, чтобы создавать авто домашнюю папку нужно вот


![photo_2022-02-11_20-53-58](https://user-images.githubusercontent.com/97450080/153624127-4c21051c-b880-4912-9b36-d693b4d94884.jpg)

еще какието трансфер зоны


![photo_2022-02-11_20-54-20](https://user-images.githubusercontent.com/97450080/153624203-b2950127-65d9-412a-af8e-17c11e69aff9.jpg)

как можно заметить это днсы


![photo_2022-02-11_20-55-04](https://user-images.githubusercontent.com/97450080/153624304-78470888-b0d6-4dc6-b9ba-981199eeb6f0.jpg)

![photo_2022-02-11_20-55-18](https://user-images.githubusercontent.com/97450080/153624349-67175c0a-af82-47c3-846b-51c4e38442d9.jpg)

/etc/bind/named.conf.default-zones


![photo_2022-02-11_20-55-38](https://user-images.githubusercontent.com/97450080/153624408-4a83045d-62bd-4cfc-b65d-e218e4750b22.jpg)

gre crontab


![photo_2022-02-11_20-56-28](https://user-images.githubusercontent.com/97450080/153624531-54dc1532-488c-467e-9cc7-955af717b93a.jpg)

fstab (filesystem)
