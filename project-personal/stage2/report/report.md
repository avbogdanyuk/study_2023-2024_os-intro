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

Выполнение 2 этапа индивидуального проекта. Добавить к сайту данные о себе.

# Задание

1. Разместить свою фотографию на сайте
2. Разместить краткое описание владельца
3. Добавить информацию об интересах
4. Добавить информацию об образовании
5. Добавить 2 поста

# Выполнение лабораторной работы

Для начала перехожу в каталог personal_project/content/authors/admin. Затем добавляю свою фотографию avatar.jpg (рис. 1).

![Добавляю свою фотографию](image/1.png){#fig:001 width=70%}

Проверяю, подгрузилась ли она. Все работает (рис. 2).

![Мой сайт на данный момент](image/2.png){#fig:002 width=70%}

Теперь добавляю информацию об учреждении, в котором я обучаюсь (рис. 3).

![Информация о себе](image/3.png){#fig:003 width=70%}

Затем пишу о своих интересах (рис. 4).

![Мои интересы](image/4.png){#fig:004 width=70%}

Далее заполняю информацию о моем образовании (рис. 5).

![Моё образование](image/5.png){#fig:005 width=70%}

Вот как на данный момент выглядит мой сайт (рис. 6).

![Сайт](image/6.png){#fig:006 width=70%}

Добавляю краткую биографию (рис. 7).

![Краткая биография](image/7.png){#fig:007 width=70%}

Перехоже к этапу написания постов. Подгружаю картинки. Я выбрала написать пост об управлении версиями (рис. 8).

![Загружаю картинки для постов](image/8.png){#fig:008 width=70%}

Теперь пишу текст для постов (рис. 9).

![Текст поста о git](image/9.png){#fig:009 width=70%}

В итоге на моем сайте есть два поста: прошлая неделя и управление версиями (рис. 10).

![Посты на сайте](image/10.png){#fig:010 width=70%}

# Выводы

В ходе выполнения 2 этапа индивидуального проекта была добавлена информация на сайт об его владельце.
