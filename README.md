# Bash
### Решение:
#### [Задание 1-Задание2](bash_sol)
---
### Задание 1:
От разработчиков поступила задача: нужно выяснить, какие запросы шли с IP-адреса. IP-адрес состоит из четырёх чисел, они разделены точками. Тебе нужны адреса, которые начинаются с «233.201.».

Логи лежат на удалённом сервере по адресу logs/2019/12. День, когда случилась ошибка, неизвестен. 

Твоя задача — узнать, какие запросы были отправлены. 

В ответе приложи:
1. команду, которой тебе удалось получить нужные логи;
2. подходящие строки, например: ```184.79.247.161 - - [30/12/2019:21:38:13 +0000] "PUT /alerts HTTP/1.1" 400 3557```

### Задание 2:
В системе обнаружен баг. Он проявлялся 30.12.2019 и 31.12.2019 с 21:30:00 до 21:39:59. При этом появлялись ошибки с номерами 400 и 500. Твоя задача — сохранить в отдельный файл логи, которые были записаны в этот период.  

Затем эти логи надо разложить по отдельным файлам: логи с одинаковой ошибкой положи в один файл.

В ответе приложи:
1. команды, которые создают директории bug1 и events;
2. команду, которой ты выбираешь запросы за указанный период. Это те запросы, которыми ты отбираешь логи в файл main.txt;
3. команды, которыми ты кладёшь логи в файлы 400.txt и 500.txt из main.txt;
