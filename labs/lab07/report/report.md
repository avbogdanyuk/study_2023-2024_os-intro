---
## Front matter
title: "Индивидуальный проект"
subtitle: "Этап 2"
author: "Богданюк Анна Васильевна"

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
mainfont: PT Mono
romanfont: PT Mono
sansfont: PT Mono
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

Получение навыков правильной работы с репозиториями git.

# Задание

1. 

# Теоретическое введение



# Выполнение лабораторной работы

Для (рис. 1).

![](image/1.png){#fig:001 width=70%}

Затем (рис. 2).

![](image/2.png){#fig:002 width=70%}

Тепери (рис. 3).

![](image/3.png){#fig:003 width=70%}

Затем (рис. 4).

![](image/4.png){#fig:004 width=70%}

Для (рис. 5).

![](image/5.png){#fig:005 width=70%}

Выполняю (рис. 6).

![](image/6.png){#fig:006 width=70%}

Данная (рис. 7).

![](image/7.png){#fig:007 width=70%}

Данная (рис. 8).

![](image/8.png){#fig:008 width=70%}

Теперь (рис. 9).

![](image/9.png){#fig:009 width=70%}

Делаем (рис. 10).

![](image/10.png){#fig:010 width=70%}

# Выводы

В ходе выполнения лабораторной работы были получены навыки правильной работы с репозиториями git.
