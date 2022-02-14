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

![image](https://user-images.githubusercontent.com/97450080/153630959-23e4040b-fa5b-4602-9d6e-5a4b2ceb7f34.png)


еще какието трансфер зоны

еще нужно установить apt ll isc-dhcp-relay чтобы другой сегмент сети смог получить адреса.


![photo_2022-02-11_20-54-20](https://user-images.githubusercontent.com/97450080/153624203-b2950127-65d9-412a-af8e-17c11e69aff9.jpg)

как можно заметить это днсы


![photo_2022-02-11_20-55-04](https://user-images.githubusercontent.com/97450080/153624304-78470888-b0d6-4dc6-b9ba-981199eeb6f0.jpg)

![photo_2022-02-11_20-55-18](https://user-images.githubusercontent.com/97450080/153624349-67175c0a-af82-47c3-846b-51c4e38442d9.jpg)

/etc/bind/named.conf.default-zones


![photo_2022-02-11_20-55-38](https://user-images.githubusercontent.com/97450080/153624408-4a83045d-62bd-4cfc-b65d-e218e4750b22.jpg)

gre crontab


![photo_2022-02-11_20-56-28](https://user-images.githubusercontent.com/97450080/153624531-54dc1532-488c-467e-9cc7-955af717b93a.jpg)

fstab (filesystem)


![image](https://user-images.githubusercontent.com/97450080/153919735-4c016195-e191-47cd-8a2e-c11dcdafc35b.png)
подключить самбу

![image](https://user-images.githubusercontent.com/97450080/153919804-bef09ade-3f5b-47d0-9801-e39928a1fb5f.png)


![image](https://user-images.githubusercontent.com/97450080/153919869-8be142b4-6649-4fb5-97be-c60f9aae4653.png)


![image](https://user-images.githubusercontent.com/97450080/153919886-a2109462-7418-4d8f-a434-557ca4014e02.png)


![image](https://user-images.githubusercontent.com/97450080/153919903-94e6d613-18d3-499b-8749-a420cc2e6d30.png)


![image](https://user-images.githubusercontent.com/97450080/153919922-4a0c28ec-2da3-4aaa-9da3-1f03268ccbcc.png)


![image](https://user-images.githubusercontent.com/97450080/153919934-44a959b9-297e-471c-807f-1bd1d5276f81.png)


![image](https://user-images.githubusercontent.com/97450080/153919949-5b0e619d-6fce-4ecd-ba30-954370ac5450.png)


![image](https://user-images.githubusercontent.com/97450080/153919972-21b712c8-2f54-4f44-b9de-5d1252782656.png)


![image](https://user-images.githubusercontent.com/97450080/153919981-14c8a544-b7c2-42a9-ad18-bdf6e7c791b9.png)


![image](https://user-images.githubusercontent.com/97450080/153920004-9ac4bada-4a50-43c9-9f2e-0af75ac26b06.png)
CTRL+M

![image](https://user-images.githubusercontent.com/97450080/153920046-d456e2d1-1771-468d-b64f-98d220d9b105.png)


![image](https://user-images.githubusercontent.com/97450080/153920061-f7bf5b97-f146-4fc2-b96c-4ba08a83ccdd.png)


![image](https://user-images.githubusercontent.com/97450080/153920073-11ccf912-3835-4908-9550-b9afa9afb159.png)


![image](https://user-images.githubusercontent.com/97450080/153920089-657dd55c-c150-4d38-83ce-d70ce6b7ee80.png)


![image](https://user-images.githubusercontent.com/97450080/153920097-63430fe3-53bf-4328-b328-b06811e035a6.png)


![image](https://user-images.githubusercontent.com/97450080/153920114-8a42c8f9-2c75-429e-8ae4-dbe86d2ad879.png)


![image](https://user-images.githubusercontent.com/97450080/153920129-d0e537e3-1427-45a3-aeb6-393fefd48b20.png)


![image](https://user-images.githubusercontent.com/97450080/153920164-f4e2375d-f38f-4bfa-a92d-16dc45fcf0b8.png)


![image](https://user-images.githubusercontent.com/97450080/153920182-134c218c-773e-4b4b-a5c8-5671d2a2e962.png)
CA
