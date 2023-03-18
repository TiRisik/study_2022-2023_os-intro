---
## Front matter
title: "Лабораторная работа №6"
subtitle: "Поиск файлов. Перенаправление ввода-вывода. Просмотр запущенных процессов"
author: "Тарутина Кристина Олеговна"

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

Ознакомление с инструментами поиска файлов и фильтрации текстовых данных.
Приобретение практических навыков: по управлению процессами (и заданиями), по
проверке использования диска и обслуживанию файловых систем.

# Выполнение лабораторной работы

Записываю в файл file.txt названия файлов, содержащихся в каталоге /etc. Дописываю в этот же файл названия файлов, содержащихся в  домашнем каталоге.(рис. @fig:001 - @fig:002).

![рис 1](image/image1.png){#fig:001 width=70%}

![рис 2](image/image2.png){#fig:002 width=70%}

Определяю, какие файлы в домашнем каталоге имеют имена, начинавшиеся
с символа c. (рис. @fig:003).

![рис 3](image/image3.png){#fig:003 width=70%}

Вывожу на экран имена файлов из каталога /etc, начинающиеся
с символа h.(рис. @fig:004).

![рис 4](image/image4.png){#fig:004 width=70%}

Запускаю в фоновом режиме процесс, который будет записывать в файл ~/logfile
файлы, имена которых начинаются с log. (рис. @fig:005 - @fig:006).

![рис 5](image/image5.png){#fig:005 width=70%}

![рис 6](image/image6.png){#fig:006 width=70%}

Удаляю файл ~/logfile(рис. @fig:007).

![рис 7](image/image7.png){#fig:007 width=70%}

Запускаю из консоли в фоновом режиме редактор gedit.
Определяю идентификатор процесса gedit, используя команду ps(рис. @fig:008).

![рис 8](image/image8.png){#fig:008 width=70%}

Читаю справку (man) команды kill, после чего использую её для завершения
процесса gedit(рис. @fig:009 - @fig:010).

![рис 9](image/image9.png){#fig:009 width=70%}

![рис 10](image/image10.png){#fig:010 width=70%}

Выполняю команды df и du, предварительно получив более подробную информацию
об этих командах, с помощью команды man.(рис. @fig:011 - @fig:013)

![рис 11](image/image11.png){#fig:011 width=70%}


![рис 12](image/image12.png){#fig:012 width=70%}


![рис 13](image/image13.png){#fig:013 width=70%}


# Выводы

Ознакомление с инструментами поиска файлов и фильтрации текстовых данных, приобретение практических навыков: по управлению процессами (и заданиями), по
проверке использования диска и обслуживанию файловых систем прошло успешно.


# Список литературы{.unnumbered}

::: {#refs}
:::
