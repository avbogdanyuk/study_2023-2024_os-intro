---
## Front matter
title: "Лабораторная работа 9"
subtitle: "Командная оболочка Midnight Commander"
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

Освоение основных возможностей командной оболочки Midnight Commander. Приобретение навыков практической работы по просмотру каталогов и файлов; манипуляций с ними.

# Задание

1. Задание по mc

# Выполнение лабораторной работы

Изучаю информацию о  mc, для этого захожу в справочник по команде man mc (рис. 1).

![Справочник mc](image/1.png){#fig:001 width=70%}

Затем запускаю midnight commander. Создаю текстовый файл и добавляю туда текст о змеях. Использую все предложеные операции (операции с панелями; выделение/отмена выделения файлов, копирование/перемещение файлов, получение информации о размере и правах доступа на файлы и/или каталоги и т.п.)(рис. 2).

![Выполнение операций](image/2.png){#fig:002 width=70%}

Использую возможности подменю File (рис. 3).

![Возможности подменю](image/3.png){#fig:003 width=70%}

Затем использую возможности подменю Command (рис. 4).

![Возможности подменю](image/4.png){#fig:004 width=70%}

Затем использую возможности подменю Option (рис. 5).

![Возможности подменю](image/5.png){#fig:005 width=70%}

Создаю файл с именем text.txt (рис. 6).

![touch text.txt](image/6.png){#fig:006 width=70%}

Вставляю в файл текст о змеях и удаляю строку, и виделяю фрагемент текста, и копирую его на новую строку и так далее (рис. 7).

![Выполнение операций](image/7.png){#fig:007 width=70%}

Создаю файл с именем amigo.cpp, т.е. файл с программой на языке C++. Изменяю его (рис. 8).

![amigo.cpp](image/8.png){#fig:008 width=70%}


# Выводы

В ходе выполнения лабораторной работы были освоены основные возможности командной оболочки Midnight Commander. Приобретены навыки практической работы по просмотру каталогов и файлов; манипуляций с ними.
