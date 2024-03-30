---
## Front matter
title: "Индивидуальный проект"
subtitle: "Этап 3"
author: "Карпова Есения Алексеевна"

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

Научиться добавлять к сайту достижения.

# Задание

1) Добавить список достижений:

    - информацию о навыках (Skills).
    - информацию об опыте (Experience).
    - информацию о достижениях (Accomplishments).

2)Сделать пост по прошедшей неделе и добавить пост на тему по выбору

# Выполнение лабораторной работы

## Добавление достижений

Для того, чтобы внести данные об опыте работы (Experience) я захожу в директорию content в файл index.md. Нахожу блок связанный с опытом и меняю его под себя. С помощью команды ~/bin/hugo server загружаю данные на сайт и проверяю результат (рис. [-@fig:001]).

![Experience](image/1.png){#fig:001 width=100%}

Аналогичным образом добавляю информацию о достижениях (рис. [-@fig:002]).

![Accomplishments](image/2.png){#fig:002 width=100%}


Для того, чтобы поменять иконки - загружаю изображения в каталог website/assets/meadi/icons/brands в формате svg(рис. [-@fig:003]).

![Загрузка иконок](image/3.png){#fig:003 width=100%}

## Написание постов

Пишу посты о том, как прошла моя неделя и на тему по выбору (Язык разметки Markdown)(рис. [-@fig:004]).

![Посты](image/4.png){#fig:004 width=100%}


Проверяю корректность загрузки постов на сайт (рис. [-@fig:005]).

![Открытие постов на сайте](image/5.png){#fig:005 width=100%}

# Выводы

В ходе лабораторной работы я научилась добавлять к сайту достижения.

