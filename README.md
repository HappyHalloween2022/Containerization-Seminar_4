﻿# Контейнеризация (семинары)


![picture for containerization](containerization.jpg)

## Урок 4. Dockerfile и слои

### **Информация о проекте**

Задание: Сбилдить свой имейдж на основе имейджа mariaDB используя Dockerfile. Можете еще в Dockerfile добавить функционал по уменьшению веса образа к примеру.
Сделать свой конфиг для mariaDB и заменить конфиг базового имейджа используя Dockerfile. Допустим поменять порт, максимальное использованеи памяти и т.д. - Оцена Отлично
Слинковать папку с базой данных с контейнера с mariaDB в папку на хосте (как на семинаре). Заполнить БД данными или добавить запись и проверить, что файлы базы данных появились на хостовой машине. - Если выполняете этот пункт то оценка Отлично.
Запустить phpmyadmin (в контейнере) и через веб проверить, что все введенные данные доступны.
*5 (не обязательно). Сбилдить образ любой базы данных на основе alpine. Запустить контейнер и проверить, что БД запустилась (допустим зайти через командную строку и вывести список баз данных).




**Выполнение**

![Dockerfile](Dockerfile)
![python-file](task4.py)

![command for linux containerization](source/02-08-35.png?raw=true)
![command for linux containerization](source/02-09-34.png?raw=true)
![command for linux containerization](source/02-10-00.png?raw=true)
![command for linux containerization](source/02-10-58.png?raw=true)
![command for linux containerization](source/02-12-45.png?raw=true)
![command for linux containerization](source/02-12-54.png?raw=true)

