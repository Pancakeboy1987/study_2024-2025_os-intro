---
## Front matter
title: "Отчёт по индивидуальному проекту"
subtitle: "Часть 3"
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

Создать индивидуальный сайт, постепенно его заполняя


# Задание



Добавить информацию об достижениях .
Добавить информацию о хобби .
Добавить информацию об опыте
Сделать пост по прошедшей неделе.
Добавить пост на тему по выбору


# Выполнение лабораторной работы



Добавим информацию о себе, о навыках рис. [-@fig:001])

![заполнение базовой информации о себе](image/1.png){#fig:001}

Добавим так же информацию о себе, о хобби рис. [-@fig:002])

![заполнение базовой информации о себе](image/2.png){#fig:002}

Добавим информацию о себе, о опыте рис. [-@fig:003])

![заполнение базовой информации о себе](image/3.png){#fig:003}

Напишем пост о прошедшей неделе в папке posts (рис. [-@fig:004])

![Пост о прошедшей неделе](image/4.png){#fig:004}

А после пост о LaTEX (рис. [-@fig:005])

![Пост о LaTEX](image/5.png){#fig:005}


# Выводы

В результате выполнения лабораторной работы был создан сайт, который находится на хостинге Github

# Список литературы{.unnumbered}

::: {#refs}
:::
