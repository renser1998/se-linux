# Task 1
## 1. Способ. Установили флаг setsebool -P nis_enabled 1 
![alt text](pic1/1_2.png)
Проверили статус сервиса
![alt text](pic1/1_3.png)
Открытый порт 4881
![alt text](pic1/1_4.png)

## 2. Способ. Разрешение порта для http трафика с помощью semanage
![alt text](pic1/2_1.png)
Проверили статус сервиса
![alt text](pic1/2_2.png)

## 3. Способ. Разрешим в SELinux работу nginx на порту с помощью формирования и установки модуля SELinux:
![alt text](pic1/3_1.png)
Установленный модуль nginx
![alt text](pic1/3_2.png)
