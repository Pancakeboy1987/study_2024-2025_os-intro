---
## Front matter
title: "Лабораторная работа №5"
subtitle: "Отчет"
author: "Коровкин Никита Михайлович"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Научиться пользоваться pass и chezmoi.

# Задание

Настроить ОС, синхронизируя её с данной. 
Научиться использовать программы для управления паролями.

# Выполнение лабораторной работы

Для начала установим  pass и pass-opt(рис. [-@fig:001])

![Скачивание pass и pass-opt](image/1.png){#fig:001}

Уставновим gopass(рис. [-@fig:002])

![Уставновим gopass](image/2.png){#fig:002}

Выведем список pgp ключей ((рис. [-@fig:003])

![Выведем список pgp ключей (](image/3.png){#fig:003}

Проинициализируем pass, указав свой email и  Проинициализируем репозиторий в git для pass ((рис. [-@fig:004])

![Проинициализируем pass ](image/4.png){#fig:004}


Создадим репозиторий


Делаем коммит(рис. [-@fig:005])

![коммитим](image/5.png){#fig:005}

НАстраиваем ветку на мейн(рис. [-@fig:006])

![Настройка](image/6.png){#fig:006}

Инициализируем и настраиваем chezmoi(рис. [-@fig:007])

![настраиваем chezmoi](image/7.png){#fig:007}

Открываем файл(рис. [-@fig:008])

![настраиваем chezmoi](image/8.png){#fig:008}

вписываем туда необходимые настройки[#fig:009]

![вписываем туда необходимые настройки](image/9.png){#fig:009}

# Выводы

В результате выполнения лабораторной работы были настроены программы для управления паролями, а также появился навык синхронизации настроек ОС


# Список литературы{.unnumbered}

::: {#refs}
:::
