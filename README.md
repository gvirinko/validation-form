# gvirinko.github.io
## Форма с валидацией регулярными выражениями

**Версия:** ________________

**Цель проекта:** учебная (тренировка написания регулярных выражений и знакомство с git).

**Используемые технологии:** HTML, CSS, GIT.

**Описание:** форма регистрации с валидацией полей разного типа регулярными выражениями.  
Ниже представлены валидируемые условия для каждого из полей.

#### 1. Имя
* только кириллица;
* первая буква заглавная;
* можно ввести от 2 до 20 символов — это можно задать в атрибутах minlength и maxlength;
* возможна запись двойных имён — например Анна-Мария.

#### 2. Email
* только латиница;
* «собака» @ — обязательный символ;
* Точка . — тоже обязательный символ.
* Цифры, подчерк, тире — разрешённые символы

#### 3. Телефон
Шаблон для телефона должен находить номера в таких форматах:
+7(925)900-90-90
+7(925) 900-90-90
+7 925-900-90-90
+79259009090
89259009090

#### 4. Сайт
Адрес сайта должен
* начинаться с http:// или https://;
* затем www. — это необязательная группа;
* IP-адрес — 255.255.255.255 или доменное имя — stasbasov.ru
* порт — тоже необязательная группа. Порт начинается с двоеточия, за которым идут от 2 до 5 цифр. Например: :8080;
* путь — последовательность из цифр, слешей и латинских букв, на конце которого может стоять решётка #.
