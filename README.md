# TOIB-lab3
## Задание 1. Начальная настройка

Устанавливаем Kali и DVL. Определим IP на DVL

![image](https://github.com/Vladislav789k/TOIB-lab3/assets/71137501/f58097e6-86ee-41c4-ad37-0fcf3fb41e65)


## Задание 2. Сканирование Сети и Уязвимостей

1. Nmap

![image](https://github.com/Vladislav789k/TOIB-lab3/assets/71137501/4895eb63-e9d4-4440-a453-f2e466decb7a)


2. OpenVAS

![image](https://github.com/Vladislav789k/TOIB-lab3/assets/71137501/b91cb162-aa9d-4c66-8eac-5606051d9884)

![image](https://github.com/Vladislav789k/TOIB-lab3/assets/71137501/00bcec5d-91b8-4c47-9324-fed8e285bd8e)


## Задание 3. Пентестинг Веб-Приложений
1. XSS<br>
Тестируем приложение

![image](https://github.com/Vladislav789k/TOIB-lab3/assets/71137501/4e8a23cc-bdc9-40c0-81bd-2327e06963a0)


Перехватываем и меняем запрос

![image](https://github.com/Vladislav789k/TOIB-lab3/assets/71137501/64657488-9842-4e15-a464-947697f5e264)


Успешное выполнение

![image](https://github.com/Vladislav789k/TOIB-lab3/assets/71137501/a445ae24-fd4f-4c29-8381-6fb88ab51445)


3. CSRF<br>
Тестируем приложение

![image](https://github.com/Vladislav789k/TOIB-lab3/assets/71137501/f7ac0ee9-07e8-4984-8111-359c24307e83)


Перехватываем и меняем запрос

![image](https://github.com/Vladislav789k/TOIB-lab3/assets/71137501/c2a726f5-b72c-4796-8bb3-b5775ad24472)


Успешное выполнение

![image](https://github.com/Vladislav789k/TOIB-lab3/assets/71137501/cf45a7bd-5e88-41ed-ac9e-2d110ea13213)


## Задание 4. Анализ Безопасности Системы

1. Metasploit<br>
Задаем нужные параметры
 
![image](https://github.com/Vladislav789k/TOIB-lab3/assets/71137501/29bf2edc-b8f8-479b-8b0c-e745db8b51d6)


Получаем пароль root пользователя

![image](https://github.com/Vladislav789k/TOIB-lab3/assets/71137501/44a8cb8c-1ab0-476e-8d1d-c45f25063af3)


2. JohnTheRipper<br>
С помощью найденного пароля заходим в SSH и подключаемся к MySQL - находим учетку
 
![image](https://github.com/Vladislav789k/TOIB-lab3/assets/71137501/a4462d56-b474-42ba-8b84-a3df6730e5ce)


Ломаем пароль учетки "admin"

![image](https://github.com/Vladislav789k/TOIB-lab3/assets/71137501/19829e5b-052c-49cf-9b89-ae5f8b1d214e)


## Задание 5. Сетевая Защита и Защита От Вторжений

1. Wireshark<br>
Детект аномальных запросов

![image](https://github.com/Vladislav789k/TOIB-lab3/assets/71137501/abb48bef-1d2b-400f-999f-3123fa447330)


2. Snort<br>
Правила защиты

![image](https://github.com/Vladislav789k/TOIB-lab3/assets/71137501/3abd5340-d0ef-4aaf-98f4-67ccddd8eede)

