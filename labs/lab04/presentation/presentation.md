---
## Front matter
lang: ru-RU
title: Лабораторная работа №4
subtitle: Презентация
author:
  - Коровкин Н.М
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 5 марта 2025


## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
 
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Коровкин Никита Михайлович
  * Студент
  * Российский университет дружбы народов
  * [1132246835@pfur.ru](mailto:1132246835@pfur.ru)

:::
::: {.column width="30%"}

:::
::::::::::::::

## Цель

Получение навыков правильной работы с репозиториями git


## Задание

Выполнить работу для тестового репозитория.
Преобразовать рабочий репозиторий в репозиторий с git-flow и conventional commits.

## Выполнение лабораторной работы

## Подключение репозитория

Для начала  мы подключим репозиторий, из которого можно скачать gitflow 

![Подключение репозитория](image/0.png)

## У становка
Нам нужно будет установить Git flow

![Установка Git flow](image/1.png)

## Установка

Теперь установим node.js

![Установка Git flow](image/2.png)

## Установка

Затем устанавливаем pnpm.

![Установка pnpm](image/3.png)

## Установка

далее настраиваем  pnpm.

![Настройка](image/4.png)

## Установка

И установим с помощью него Commitizen.

![Установка Commitizen](image/5.png)

## Создаем дрокументы

Создадим тестовый репозиторий git-extended.

![Создание тестового репозитория](image/6.png)

## Клонирование

И клонируем его себе на компьютер, а затем  сделаем соответствующий коммит.

![Клонирование репозитория](image/7.png)

Все изменения отправляем на GitHub.

## Редактура

Теперь проинициализируем pnpm.
После инициализации создастся файл package.json, который нужно изменить следующим образом.

![Редактирование файла package.json](image/8.png)

## Редактура

Затем делаем коммит и отправляем все на сервер.

![Отправка изменений на сервер](image/10.png)

## Редактура

Теперь проинициализируем gitflow.

![Инициализация gitflow](image/11.png)

## Редактура

Настроим ветки.

![Настройки веток](image/12.png)

## Редактура

Создаем changelog.

![создание changelog](image/13.png)

## Редактура

Проиндексируем changelog и сделаем коммит 

![Создание коммита с changelog](image/15.png)

## Редактура

Теперь сольём ветку release с веткой develop.

![Слияние веток](image/16.png)

Делаем обновленный релиз и добавляем туда чейнджлог.

## Редактура

![Обновляем релиз](image/18.png){#fig:016}

Добавляем комментарий в коммит.
![Добавляем комментарии](image/19.png)

## Редактура

Сольем ветку с журналом изменений с основной веткой.(

![Сливаем ветку](image/20.png){

## Редактура

Загрузим изменения в гитхаб и создадим релиз

![Загрузка изменений](image/21.png)

## Выводы

В ходе выполнения лабораторной работы мною были получены навыки работы с расширенными возможностями git, кроме того были созданы релизы к репозиторию и дополнительные ветки, которые автор научился сливать воедино
