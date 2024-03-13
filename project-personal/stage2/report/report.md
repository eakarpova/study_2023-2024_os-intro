---
## Front matter
title: "Индивидуальный проект"
subtitle: "Этап 1"
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

Научиться добавлять к сайту данные о себе

# Задание

1. Разместить фотографию владельца сайта, краткое описание владельца сайта (Biography),добавить информацию об интересах (Interests). и об образовании (Education).

2. Сделать пост по прошедшей неделе.
   Добавить пост на тему по выбору:
    1) Управление версиями. Git.
    2) Непрерывная интеграция и непрерывное развертывание (CI/CD).


# Выполнение лабораторной работы

1. Размещение фотографии владельца сайта

Добавляю свою фотографию в директорию admin (рис. [-@fig:001]).

![Размещение фотографии владельца сайта](image/1.png){#fig:001 width=100%}

Меняю в файле _index.md данные о себе (рис. [-@fig:002]).

![Добавление информации о себе](image/2.png){#fig:002 width=100%}

Проверяю нахождении фотографии и информации на сайте (рис. [-@fig:003]).

![Проверяю сайт](image/3.png){#fig:003 width=100%}

2. Размещение поста на тему по выбору

Я выбрала тему "Управление версиями. Git.". Пишу пост в нужной директории (рис. [-@fig:004]).

![Написание поста](image/4.png){#fig:004 width=100%}

Пишу второй пост о том, как прошла моя неделя. Все посты расположены в соответствующих диреткориях (рис. [-@fig:005]).

![Расположение постов](image/5.png){#fig:005 width=100%}

Проверяю наличие постов на сайте (рис. [-@fig:006]).

![Наличие постов](image/6.png){#fig:006 width=100%}

Посты открываются, виден текст и картинка (рис. [-@fig:007]).

![Пост](image/7.png){#fig:007 width=100%}


# Выводы

В ходе выполнения лабороторной работы я научилась добавлять к сайту данные о себе.


