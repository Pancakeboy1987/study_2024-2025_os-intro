---
## Front matter
lang: ru-RU
title: Лабораторная работа №5
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


Научиться пользоваться pass и chezmoi

## Задание

Настроить ОС, синхронизируя её с данной. 
Научиться использовать программы для управления паролями 

## Выполнение лабораторной работы

Для начала установим  pass и pass-opt

![Скачивание pass и pass-opt](image/1.png)

## Установка

Уставновим gopass

![Уставновим gopass](image/2.png)

## Установка

Выведем список pgp ключей 

![Выведем список pgp ключей (](image/3.png)

## Установка

Проинициализируем pass, указав свой email и  Проинициализируем репозиторий в git для pass 

![Проинициализируем pass ](image/4.png)

## Установка

Создадим репозиторий


Делаем коммит

![коммитим](image/5.png)

## Настройка

НАстраиваем ветку на мейн

![Настройка](image/6.png)

## Настройка

Инициализируем и настраиваем chezmoi

![настраиваем chezmoi](image/7.png)

## Настройка

Открываем файл

![настраиваем chezmoi](image/8.png)

## Настройка

вписываем туда необходимые настройки[

![вписываем туда необходимые настройки](image/9.png)

## Выводы

В результате выполнения лабораторной работы были настроены программы для управления паролями, а также появился навык синхронизации настроек ОС



