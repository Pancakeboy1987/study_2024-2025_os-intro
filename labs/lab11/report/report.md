---
## Front matter
title: "Лабораторная работа №11"
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

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs [@tuis]

# Задание

Ознакомиться с теоретическим материалом. Ознакомиться с редактором emacs. Выполнить упражнения. Ответить на контрольные вопросы.

# Выполнение лабораторной работы

Откроем Emacs и создадим при помощии него новый файл(рис. [-@fig:001]).

![Создание файла](image/1.png){#fig:001}

Вставим туда код из предложенного файла(рис. [-@fig:002]).

![Вписываем код](image/2.png){#fig:002}

При помощи комбинации клавиш C-space выделяем всю область.(рис. [-@fig:003]).

![Выделяем](image/3.png){#fig:003}

Перемещаем курсор с помощью других комбинаций.
затем скопируем, вырежем и вставим часть текста.(рис. [-@fig:004]).


![коипруем,вырезаем](image/4.png){#fig:004}

Уберем изменения(рис. [-@fig:005]).

![убираем все ](image/5.png){#fig:005}

Откроем список буферов(рис. [-@fig:006]).

![откроем список буферов ](image/6.png){#fig:006}

Воспользуемся поиском(рис. [-@fig:007]).

![используем поиск ](image/7.png){#fig:007}

# Выводы

В результате выполнения лабораторной работы нами были получены навыки работы с текстовым редактором emacs

# Список литературы{.unnumbered}

::: {#refs}
:::
