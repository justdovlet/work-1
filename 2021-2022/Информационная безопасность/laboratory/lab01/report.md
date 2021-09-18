---
# Front matter
lang: ru-RU
title: "Отчет по лабораторной работе №1"
subtitle: Информационная безопасность
author: "Кроз Елена Константиновна НФИбд-02-18"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the υalue makes tex try to haυe fewer lines in the paragraph.
  - \interlinepenalty=0 # υalue of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \usepackage{amsmath}
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для
дальнейшей работы сервисов.

# Задание

Установить на виртуальную машину VirtualBox операционной системы
Linux, дистрибутив Centos.


# Выполнение лабораторной работы

## Процесс выполнения лабораторной работы

![Создаем новую машину](image/1.png){ #fig:001 width=70% height=70% }



![Указываем объем памяти](image/2.png){ #fig:002 width=70% height=70% }



![Создать новый виртуальный жесткий диск](image/3.png){ #fig:003 width=70% height=70% }


![Указываем размер диска](image/4.png){ #fig:004 width=70% height=70% }



![Добавляем носитель](image/5.png){ #fig:005 width=70% height=70% }



![Ожидаем установку ОС](image/6.png){ #fig:006 width=70% height=70% }


![Выбираем язык](image/7.png){ #fig:007 width=70% height=70% }


![Устанавливаем пароль root](image/8.png){ #fig:008 width=70% height=70% }



![Добавляем пользователя](image/9.png){ #fig:009 width=70% height=70% }



![Устанавливаем время и часовой пояс](image/10.png){ #fig:010 width=70% height=70% }



![Ждем окончания установки](image/11.png){ #fig:011 width=70% height=70% }



![После перезагрузки принимаем лицензионное соглашение](image/12.png){ #fig:012 width=70% height=70% }



![Вводим имя пользователя и пароль](image/13.png){ #fig:013 width=70% height=70% }



![В терминале прописываем команду su](image/14.png){ #fig:014 width=70% height=70% }



![В терминале прописываем yum update](image/15.png){ #fig:015 width=70% height=70% }



![В терминале прописываем yum install mc](image/16.png){ #fig:016 width=70% height=70% }



![Освобождаем диск](image/17.png){ #fig:017 width=70% height=70% }



![Меняем тип подключения диска](image/18.png){ #fig:018 width=70% height=70% }



![Создаем виртуальную машину с имеющимся диском](image/19.png){ #fig:019 width=70% height=70% }

# Выводы

В ходе выполнения лабораторной работы я приобрела практические навыки установки операционной системы на виртуальную машину, настройки минимально необходимых для
дальнейшей работы сервисов.