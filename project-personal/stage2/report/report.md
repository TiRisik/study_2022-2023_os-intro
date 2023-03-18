---
## Front matter
title: "Второй этап индивидуального проекта"
subtitle: "Простейший вариант"
author: "Тарутина Кристина"

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

Научиться настраивать и редактировать собственный сайт на шаблоне HUGO


# Выполнение лабораторной работы

Добавляю собственный аватар вместо шаблонного(рис. @fig:001).

![Аватар в папке](image/image1.png){#fig:001 width=70%}

Настраиваю на сайте своё имя и фамилию, а также место обучения (рис. @fig:002).

![Изменённая информация](image/image2.png){#fig:002 width=70%}

Пишу краткую биографию и указываю интересы (рис. @fig:003).

![Краткая биография](image/image3.png){#fig:003 width=70%}

Указываю пройденные мной курсы (рис. @fig:004).

![Курсы](image/image4.png){#fig:004 width=70%}

Создаю шапку поста по прошедшей неделе(рис. @fig:005).

![Шапка поста](image/image5.png){#fig:005 width=70%}

Пишу основной текст поста про прошедшую неделю (рис. @fig:006).

![Текст поста](image/image6.png){#fig:006 width=70%}


# Выводы

МЫ успешно научились настраивать и редактировать часть элементов сайта

# Список литературы{.unnumbered}

::: {#refs}
:::
