# **Домашнее задание к занятию «Резервное копирование» SYS-32 - Кумышев Аслан**

# * Задание 1 *
Что нужно сделать:

* Составьте команду rsync, которая позволяет создавать зеркальную копию домашней директории пользователя в директорию /tmp/backup
* Необходимо исключить из синхронизации все директории, начинающиеся с точки (скрытые)
* Необходимо сделать так, чтобы rsync подсчитывал хэш-суммы для всех файлов, даже если их время модификации и размер идентичны в источнике и приемнике.
* На проверку направить скриншот с командой и результатом ее выполнения

1. ![alt text](https://github.com/sAslank/Rezervcopy/blob/main/img/аа2.jpg)
2. ![alt text](https://github.com/sAslank/Rezervcopy/blob/main/img/аа1.jpg)

 **************************************************************************

# * Задание 2 *
Что нужно сделать:
* Написать скрипт и настроить задачу на регулярное резервное копирование домашней директории пользователя с помощью rsync и cron.
* Резервная копия должна быть полностью зеркальной
* Резервная копия должна создаваться раз в день, в системном логе должна появляться запись об успешном или неуспешном выполнении операции
* Резервная копия размещается локально, в директории /tmp/backup
* На проверку направить файл crontab и скриншот с результатом работы утилиты.

1. ![alt text](https://github.com/sAslank/Rezervcopy/blob/main/img/вв4.jpg)

2. ![alt text](https://github.com/sAslank/Rezervcopy/blob/main/img/вв3.jpg)

3. ![alt text](https://github.com/sAslank/Rezervcopy/blob/main/img/вв2.jpg)
