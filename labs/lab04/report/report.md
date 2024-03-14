---
## Front matter
title: "Отчет по лабораторной работе 4"
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

Получение навыков правильной работы с репозиториями git.

# Выполнение лабораторной работы

Установила git-flow.

Установила Node.js.

Настроила Node.js.

Ввела программу pnpm add -g commitizen для помощи в форматировании коммитов. 

Ввела программу pnpm add -g standard-changelog для помощи в создании логов.

Создала новый репозиторий на git и сделала первый коммит.

Сделала конфигурацию для пакетов Node.js с помощью программы pnpm init.

Сделала конфигурацию git-flow.

Создала ветку для новой функциональности.

Создала релиз git-flow. Обновила номер версии в файле package.json. Установила ее в 1.2.3.

Создала журнал изменений. Добавила журнал изменений в индекс.

Залила релизную ветку в основную ветку.

Отправила данные на github. 

Создала релиз на github с комментарием из журнала изменений.

# Выводы

Я получила новые навыки работы с репозиторием git.

# Список литературы{.unnumbered}

::: {#refs}
:::
