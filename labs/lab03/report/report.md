---
## Front matter
title: "Лабораторная работа №3"
subtitle: "Отчёт"
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

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown. [@tuis]

# Задание

Сделать отчёт по предыдущей лабораторной работе в формате Markdown.  В качестве отчёта предоставить отчёты в 3 форматах: pdf, docx и md (в архиве,
поскольку он должен содержать скриншоты, Makefile и т.д.)

# Выполнение лабораторной работы

Для начала необходимо открыть файл отчёта "report.md" для заполнения. Я буду использовать редактор gedit (рис. [-@fig:001])

![Открытие файла report.md](image/1.png){#fig:001}

Перед нами открыт шаблон, который нужно заполнить по образцу.(рис. [-@fig:002])

![Шаблон заполнения отчета](image/2.png){#fig:002}

Заполним наш отчет согласно образцу(рис. [-@fig:003])

![Заполнение отчета](image/3.png){#fig:003}

После этого заполним файл cite.bib. В нем ссылка на литературу.(рис. [-@fig:004])

![Заполняем используемую лит-ру](image/4.png){#fig:004}

Теперь создадим отчет с помощью терминала и команды make(рис. [-@fig:005])

![Создание файлов](image/5.png){#fig:005}

Проверм: создались ли нужные файлы.(рис. [-@fig:006])

![Проверка](image/6.png){#fig:006}

Все верно, работа выполнена успешно.

# Выводы

В ходе выполнения лабораторной работы были получены навыки создания отчётов в формате .md и работы с языком markdown.

# Список литературы{.unnumbered}

::: {#refs}
:::
