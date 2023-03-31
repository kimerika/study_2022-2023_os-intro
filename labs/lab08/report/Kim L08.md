---
## Front matter
title: "Лабораторная рбота №8"
subtitle: "Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах."
author: "Ким Эрика Алексеевна"

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


Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах.



# Выполнение лабораторной работы



1. Создайте каталог с именем ~/work/os/lab08.Перейдите во вновь созданный каталог.Вызовите vi и создайте файл hello.sh

![...](image/1.png){#fig:001 width=90%}

2. ажмите клавишу i и вводите следующий текст.
 
![...](image/2.png){#fig:002 width=90%}

3. Нажмите клавишу Esc для перехода в командный режим после завершения ввода
текста.Нажмите : для перехода в режим последней строки и внизу вашего экрана появится приглашение в виде двоеточия.Нажмите w (записать) и q (выйти), а затем нажмите клавишу Enter для сохранения вашего текста и завершения работы.
 
![...](image/3.png){#fig:003 width=90%}

4. Сделайте файл исполняемым
  
![...](image/4.png){#fig:004 width=90%} 

5. Перейдите в режим вставки и замените на HELLO. Нажмите Esc для возврата в командный режим.

![...](image/5.png){#fig:005 width=90%}

6.  Установите курсор на последней строке файла. Вставьте после неё строку, содержащую
следующий текст: echo $HELLO
  
![...](image/6.png){#fig:006 width=90%}

7. Нажмите Esc для перехода в командный режим.Удалите последнюю строку.

![...](image/7.png){#fig:07 width=90%}

8. Введите команду отмены изменений u для отмены последней команды. Введите символ : для перехода в режим последней строки. Запишите произведённые изменения и выйдите из vi

![...](image/8.png){#fig:08 width=90%}


  
  
  
# Выводы

Освоили основные возможности командной оболочки MC.

# Список литературы{.unnumbered}

::: {#refs}
:::
