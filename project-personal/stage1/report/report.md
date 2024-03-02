---
## Front matter
title: "Индивидуальный проект"
subtitle: "Этап 1"
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

Научиться размещать сайт на GitHub pages.

# Задание

Установить необходимое программное обеспечение.
Скачать шаблон темы сайта.
Разместить его на хостинге git.
Установить параметр для URLs сайта.
Разместить заготовку сайта на Github pages.

# Выполнение лабораторной работы

Скачиваю последнюю версию hugo с GitHub для Linux (рис. [-@fig:001]).

![Hugo](image/1.png){#fig:001 width=70%}

Распаковываю архив с Hugo (рис. [-@fig:002]).

![Распаковка архива](image/2.png){#fig:002 width=70%}

Создаю свой репозиторий на основе шаблона темы сайта, затем клонирую его (рис. [-@fig:003]).

![Шаблон темы сайта](image/3.png){#fig:003 width=70%}

Устанавливаю Go (рис. [-@fig:004]).

![Установка Go](image/4.png){#fig:004 width=70%}

Перехожу в репозиторий для индивидульного проекта и запускаю hugo (рис. [-@fig:005]).

![Запуск hugo](image/5.png){#fig:005 width=70%}

Удаляю папку public, так как на данный момент она нам не требуется (рис. [-@fig:006]).

![Удаление папки public](image/6.png){#fig:006 width=70%}

Запускаю исполнительный файл с server, получаю страницу сайта на локальном сервере (рис. [-@fig:007]).

![Страница сайта](image/7.png){#fig:007 width=70%}

Создаю новый репозиторий с именем, совпадающим с названием сайта (рис. [-@fig:008]).

![Новый репозиторий](image/8.png){#fig:008 width=70%}

Клонирую этот репозиторий, чтобы создать локальный репозиторий у себя на компьютере (рис. [-@fig:009]).

![Клонирование репозитория](image/9.png){#fig:009 width=70%}

Создаю главную ветку (main) (рис. [-@fig:010]).

![Main branch](image/10.png){#fig:010 width=70%}

Отправляю изменения на сервер (рис. [-@fig:011]).

![Отправляю изменения](image/11.png){#fig:011 width=70%}

Подключаю репозиторий к папке public (рис. [-@fig:012]).

![Папка public](image/12.png){#fig:012 width=70%}

Снова запускаю hugo, чтобы заполнить public (рис. [-@fig:013]).

![Повторный запуск hugo](image/13.png){#fig:013 width=70%}

Проверяю, чтобы было подключение между public и avbogdanyuk.github.io, затем отправляю изменения на сервер (рис. [-@fig:014]).

![Отправка изменений на сервер](image/14.png){#fig:014 width=70%}

# Выводы

В ходе выполнения первого этапа индивидуального проекта я научилась размещать персональный сайт на GitHub pages.
