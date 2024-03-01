---
## Front matter
title: "Отчет по лабораторной работе 1"
subtitle: "Операционные системы"
author: "Быкова Алина Александровна"

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

Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

# Выполнение лабораторной работы

Установила Virtual Box и образ дистрибутива Fedora.

Создала ВМ, настроила для нее виртуальный диск, память, тип ос.

Запустила ВМ и настроила ее для себя.

# Выводы

Я научилась устанавливать ВМ и настраивать ее.

# Ответы на контрольные вопросы

1. Учётная запись пользователя хранит информацию об имени пользователя и пароль.

2. Для справки по команде после нее нужно добавить ключ -h, для перемещения по файловой системе сd для просмотра содержимого каталога ls для получения информации о размере католога du для создания и удаления файлов соответсвенно cat, rm и для катологов mkdir, rm -r права задаются командой chmod (такая команда разрешит выполнение для всех пользователей) для просмотра истории комманд history.

3. Файловая система - способ организации файлов и папок для работы с ними. ZFS – файловая система, разработанная для систем хранения данных. Главная ее черта – отказоустойчивость. Данные с которыми ведется работа копируются в служебный сектор. Его объем должен быть равен области хранения.

4. С помощью поманды findmnt.

5. Зависший процесс можно прервать с момощьюкомбинации клавиш ctrl + С.

# Список литературы{.unnumbered}

::: {#refs}
:::
