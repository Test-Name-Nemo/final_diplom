# Этап 1. Создание и настройка проекта.

## Критерии достижения

1. Имею актуальный код данного репозитория на рабочем компьютере;
2. Cоздан django-проект и он запускается без ошибок;

## Необходимые инструменты

1. Система контроля версий Git;
2. Аккаунт на Github;
3. Установленный локально  Python = 3.12.7;

## Порядок выполнения

1. Создан проект, final_diplom
2. Клонируйте репозиторий командой в вашем терминале 
```git clone git@github.com:Test-Name-Nemo/final_diplom.git```
3. Создайте виртуальное окружение для своего проекта
```virtualenv --python=python3 env```
4. Установите все необходимые пакеты проекта командой 
```pip install -r requirements.txt```
5. Создайте проект django, в случае если создаете проект с нуля без использования примера
```django-admin startproject orders .```, ```django-admin startapp backend```