![year][0] ![status][1] ![progress][2]

## Summary

**2 модуль, 2021/2022 учебный год, ВШЭ ВШБ ДБИ**

## Ссылки

### [Канал с объявлениями по курсу в telegram](https://t.me/tphsetechprog2021_2)
### [Чат по курсу в telegram](https://t.me/joinchat/9Wrx-cie3EM0NWNi)
### Таблица с результатами по курсу (*ссылка будет опубликована после первого отчетного мероприятия*)

# Аннотация

*Курс про все, что связано с созданием ПО, кроме непосредственно написания программного кода*

Курс состоит из лекций и семинарских занятий.

Лекционный материал включает краткий обзор важных с точки зрения процесса разработки понятий: методы отладки и этапы исправления дефектов ПО, критерии хорошей и неудачной архитектуры, этапы проектирования и разработки, методологии разработки.
Семинарский материал состоит из рассказа о важных инструментах программиста: системы контроля версий, системы сборки, gdb, valgrind, развертывание и настройка систем непрерывной интеграции.

Цель курса — дать слушателям, которые параллельно изучают языки программирования, алгоритмы и т. п., информацию и дополнительные знания, какими инструментами можно пользоваться и на что обращать внимание при создании рыночного программного продукта.

# План лекций

## :white_check_mark: [Лекция №0](https://github.com/demist/techprog2/blob/main/%D1%81%D0%BB%D0%B0%D0%B9%D0%B4%D1%8B%20%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D0%B9/%D0%A2%D0%9F%20%D0%92%D0%A8%D0%91%202021%20-%202%2C%20%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D1%8F%200.pdf) *(неделя 1)*

- План курса
- Правила оценки
- Информация о заданиях
- Контрольные мероприятия

## :white_check_mark: [Лекция №1](https://github.com/demist/techprog2/blob/main/%D1%81%D0%BB%D0%B0%D0%B9%D0%B4%D1%8B%20%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D0%B9/%D0%A2%D0%9F%20%D0%92%D0%A8%D0%91%202021%20-%202%2C%20%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D1%8F%201.pdf) *(неделя 1)*

### Принципы проектирования ПО, часть 1

- Что такое архитектура ПО
- Что такое "Проектирование ПО"?
- По каким критериям можно оценить архитектуру? 
	- Критерии хорошей архитектуры
		- Эффективность
		- Гибкость
		- Расширяемость
		- Масштабируемость, тестируемость, возможность повторного использования, сопровождаемость
	- Критерии неудачной архитектуры
		- Жесткость
		- Хрупкость
		- Неподвижность
- Принцип *High Cohesion / Low Coupling*

> [Отличный ресурс про паттерны проектирования](https://refactoring.guru/ru/design-patterns/catalog)

## :white_check_mark: [Лекция №2](https://github.com/demist/techprog2/blob/main/%D1%81%D0%BB%D0%B0%D0%B9%D0%B4%D1%8B%20%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D0%B9/%D0%A2%D0%9F%20%D0%92%D0%A8%D0%91%202021%20-%202%2C%20%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D1%8F%202.pdf) *(неделя 1)*

### Принципы проектирования ПО, часть 2

- Принципы SOLID
	- **S**ingle responsibility principle
	- **O**pen-closed principle
	- **L**iskov substitutional principle
	- **I**nterface segregation principle
	- **D**ependency inversion principle
- Закон Деметры
- *YAGNI*
- *DRY / DIE*
- *KISS*

> [Лекция Роберта *Uncle Bob* Мартина  про SOLID](https://www.youtube.com/watch?v=zHiWqnTWsn4)

## :white_check_mark: [Лекция №3](https://github.com/demist/techprog2/blob/main/%D1%81%D0%BB%D0%B0%D0%B9%D0%B4%D1%8B%20%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D0%B9/%D0%A2%D0%9F%20%D0%92%D0%A8%D0%91%202021%20-%202%2C%20%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D1%8F%203.pdf) *(неделя 2)*

### Основные диаграммы UML

- Что такое UML? 
	- Базовое понятие о нотации UML
- Диаграмма вариантов использования
	- Понятие о вариантах использования
	- Понятие об акторах
	- Нотация диаграммы вариантов использования
- Диаграмма классов
	- Понятие о классах
	- Нотация диаграммы классов
	- Выделение сущностей
		- Карточки CRC
		- Метод Аббота
- Диаграмма последовательности
	- Нотация диаграммы последовательности
- Диаграмма состояний
	- Нотация диаграммы состояний
- Диаграмма деятельности
	- Нотация диаграммы деятельности

> [UML Cheat Sheet](https://www.guru99.com/uml-cheatsheet-reference-guide.html)

## :white_check_mark: [Лекция №4](https://github.com/demist/techprog2/blob/main/%D1%81%D0%BB%D0%B0%D0%B9%D0%B4%D1%8B%20%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D0%B9/%D0%A2%D0%9F%20%D0%92%D0%A8%D0%91%202021%20-%202%2C%20%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D1%8F%204.pdf) *(неделя 2)*

### Этапы развития проекта

- Основные этапы жизненного цикла проектирования, реализации и внедрения ПО
- Формирование требований
- Разработка концепции
- Техническое задание
- Эскизный проект
    - Понятие о MVP и примеры MVP
- Технический проект
- Рабочая документация
- Поставка / ввод в действие
- Сопровождение 
- Вывод из эксплуатации

## :white_check_mark: [Лекция №5](https://github.com/demist/techprog2/blob/main/слайды%20лекций/ТП%20ВШБ%202021%20-%202%2C%20лекция%205.pdf) *(неделя 3)*

### Методологии разработки ПО

- Основные понятия
- Факторы, оказывающие влияние на процесс разработки
	- Внешние факторы
	- Внутренние факторы
- Каскадная модель
- V-модель
- Инкрементная модель
- Итерационная модель
- Спиральная модель
- RAD-модель 
- Семейство гибких методологий
	- Agile-манифест
	- Scrum
	- Kanban

> [Статья про методологии разработки](https://acodez.in/12-best-software-development-methodologies-pros-cons/)

## :white_check_mark: [Лекция №6](https://github.com/demist/techprog2/blob/main/слайды%20лекций/ТП%20ВШБ%202021%20-%202%2C%20лекция%206.pdf) *(неделя 3)*

### Отладка ПО, ч.1: работа с ошибками ПО

- Основные этапы отладки ПО
- Воспроизведение дефекта
	- Необходимая информация для воспроизведения
- Анализ дефекта
	- Понятие root-cause
	- Условия возникновения
	- Область повреждения
	- Необходимые выводы
- Дизайн исправления 
	- Технический
	- Архитектурный
	- Технологический
- Исправление дефекта
- Валидация исправления
- Интеграция исправления в код или целевую систему
- Дополнительные валидации после интеграции


## :fire: Лекция №7 *(неделя 4)*

### Отладка ПО, ч.2: техники отладки

- Запуск программ в отладчике (трассировка)
	- Софтверный дебаггер
	- "Железный" дебаггер
	- Удаленный дебаггер
- Логирование
	- Работы системы
	- Программного кода
- Анализ программного кода без исполнения программы
	- "Метод пристального взгляда"
	- Статические анализаторы
- Анализ поведения системы
	- Упрощение сценария
	- Ограничение объема данных
	- Упрощение данных / запроса
- UNIT-тестирование
- Прототипирование
- Отладка с помощью дампов
- Отладка с помощью перехватов
- Профилирование кода
- Выполнение кода в другой среде
- Отладка методом RPC (*Remote procedure call*)
- Отладка путем анализа документации
- Отладка трансляцией кода 
	- Трансляция "вниз"
	- Трансляция "вверх"
- Отладка разработкой интерпретатора
- Метод индукции
- Метод дедукции
- Обратное движение по алгоритму


## :fire: Лекция №8 *(неделя 4)*

*Часть времени этой лекции съест лекционная контрольная работа*

### Управление качеством ПО, ч.1

- Понятие о качестве ПО
- Характеристики и атрибуты качества ПО
- Основые аспекты качества ПО
- Парадокс тестировщика
- Соответствие ожиданиям stakeholder'ов
- Качество и деньги
	- Десятичное правило качества
	- Важные аспекты

## Лекция №9 *(неделя 5)*

### Управление качеством ПО, ч.2

- Ручное тестирования
	- Класс эквивалентности
	- Граничные значения
- 7 ключевых инструментов качества
	- Причинно-следственная диаграмма Исикавы
	- Блок-схема
	- Контрольный листок
	- Контрольная карта (карта Шухарта)
		- Примеры
	- Гистограмма
	- Диаграмма Парето
	- Диаграмма разбрасывания
- Ручное тестирование. Практические советы
- Автоматизированное тестирование 
	- Основные аспекты
	- Жизненный цикл автотеста
	- Практические советы
	- Как на практике?

## Лекция №10 *(неделя 5)*

### CI/CD/CD

- CI/CD/CD
- Понятие о Continuous Integration
- Понятие о Continuous Delivery
- Понятие о Continuous Deployment
- Пример организации процесса разработка из индустрии
	- Этап проектирования
	- Этап реализации
	- Этап сдачи задачи
	- Подготовка к выпуску версии

> [TravisCI](https://www.travis-ci.com/)

> [TeamCity](https://www.jetbrains.com/teamcity/)

> [GitHub Actions](https://github.com/features/actions)

> [Jenkins](https://www.jenkins.io/)

## Лекция №11 *(неделя 6)*

### Архитектурные паттерны

- Классификация архитектуры ПО
	- Локальные
	- Распределенные
		- Файл-серверные
		- Клиент-серверные
			- Двухзвенные
			- Трехзвенные
			- Многозвенные
- Локальные приложения 
	- MVC (*Model-View-Controller*)
- Клиент-серверная архитектура 
	- Тонкий и толстый клиент
	- Трехзвенная архитектура
- Оценка нагрузки на систему
- Тип проекта и влияние на нагрузку
- Ресурсы для обеспечения производительности 
- Масштабирование
	- Горизонтальное
	- Вертикальное
	- Функциональное разбиение
	- Шардинг
- Типичная архитектура веб-сервиса
- Типичная архитектура нагруженной информационной системы

## Лекция №12 *(неделя 6)*

### Базовые понятия о языках программирования

- Парадигмы программирования
	- Императивное программирование
		- Описание
		- Примеры
		- "Вложенные парадигмы"
			- Процедурное программирование
			- Структурное программирование
			- Аспектно-ориентированное программирование
			- Объектно-ориентированное программирование
			- Обобщенное программирование
	- Декларативное программирование
		- Пример-объяснение
		- "Вложенные парадигмы"
			- Логическое программирование 
			- Функциональное программирование
	- Общая схема парадигм
	- Метапрограммирование
	- Реализация парадигм в языках программирования
- Компилируемые и интерпретируемые языка
	- Определения
	- Примеры
- Типизация
	- Сильная / слабая типизация
	- Статическая / динамическая типизация
	- Явная / неявная типизация

# План семинаров 

## :white_check_mark: Семинар 1 *(неделя 1)*

### Базовые инструменты разработки ПО

Системы контроля версий, git, git-flow (*опционально*). 

Bash и основные команды.

**План семинара:** 

- показываем bash (*на лекции предупрежу, что надо иметь Linux / macOS или WSL*)
- базовые команды bash: touch, rm, cd, mkdir, rmdir, ls, cp, mv, cat, echo, ...
- пишем простой скрипт на bash (*Например, считаем количество файлов в директории*)
- рассказываем про системы контроля версий в целом (зачем нужно, какие есть)
- рассказываем основы git: что такое репозиторий, что такое ветки, что такое коммиты, pull-request'ы
- показываем: создание репозитория на github, клонирование локально, создание файла, коммит, push origin

> [bash commands cheatsheet](https://www.educative.io/blog/bash-shell-command-cheat-sheet)

> [bash script cheatsheet](https://devhints.io/bash)

## :white_check_mark: Семинар 2 *(неделя 2)*

### Диаграммы UML

*Отработка на семинаре навыков построения диаграмм, решение небольших задач. Диаграммы классов пока не рассматриваем.*

**План семинара:**
- решаем задачку на диаграмму вариантов использования (например, "варианты использования сайта аэропорта")
- решаем задачку на диаграмму последовательности (например, "снимаем деньги в банкомате")
- решаем задачку на диаграмму деятельности (например, "поступаем в университет")
- решаем задачку на диаграмму состояний ("рассматриваем сдачу курса: изучается-сдан-пересдача-не сдан")

## :white_check_mark: Семинар 3 *(неделя 3)*

### Основы Python

- понятие о python и интерпретаторе
- запускаем интерпретатор и считаем парочку арифметических выражений
- показываем переменные
- пишем скрипт на сложение чисел
- пишем скрипт "Hello world"
- показываем условные переходы и циклы
- пишем простую функцию расчета факториала

## Семинар 4 *(неделя 4)*

### Инструменты отладки

*Показываем дебаггер в IDE, точки останова, как с этим работать*.
*(опционально) показываем gdb & valgrind*

**План семинара:**
- запускаем любимую IDE 
- пишем простую программу (лучше на питоне), запускаем дебагер
- показываем точки останова, шаг вперед / шаг с заходом / шаг с обходом
- показываем значения переменных
- *опционально* показываем профилировщик
- *опционально* показываем gdb - как работать из консоли (опять же, на простом примере)
- *опционально* показываем valgrind в простейших сценариях (память не освобождена, переменная не инициализирована, используется неинициализированная переменная в условном переходе)

## Семинар 5 *(неделя 5)*

### Тестирование ПО

*Отработка на семинаре простейших примеров написания тестов на python, демонстрация разных видов тестов*

**План семинара:**
- пишем на питоне пару простых функций (например, сложение и умножение чисел)
- показываем юнит-тесты (каждую функцию)
- показываем нагрузочное тестирование (запускаем много итераций теста, смотрим производительность)
- показываем сценарное тестирование (на уровне "посчитаем значения выражения")

## Семинар 6 *(неделя 6)*

### Практика проектирования

*Отрабатываем практические навыки проектирования (без погружения в программный код) понятных предметных задач: заказ такси через приложение, покупка в интернет-магазине...Рисуем диаграммы классов UML*

**План семинара:**
- решаем простую задачу на проектирование локального приложения (мобильного или десктопного), без взаимодействия с сервером. *Например, проектируем простейшее приложение для создания и хранения заметок. Жетально проектировать на уровне классов. Если идет сложно - сначала пытаемся выделить варианты использования и придумать, как их реализовать. Даже если получится по итогу криво, главное, чтобы получилось хоть что-то.*.
- решаем задачу посложнее на проектирование клиент-серверного приложения. *Например, приложение для заказа такси. Обязательно надо подстветить проблему, что запрос от клиента до сервера может не дойти (или от сервера до клиента), как это можно решать (спойлер - таймлимитом)*

# Контрольные мероприятия

## Контрольная работа (КР)

*TBA*

## Техническое задание №1 (ТЗ1)

:fire: **Дедлайн**: 21 ноября, 23:59

#### **Задание**: 

Вам необходимо написать bash-скрипт, который работает с файлами.

- (**1 балл**) скрипт умеет принимать 3 аргумента: имя `директории для обработки`, имя `директории для сохранения результатов работы`, `имя архива`
- (**2 балла**) скрипт может рекурсивно обойти `директорию для обработки` и вывести на экран статистику: общее количество вложенных директорий, общее количество файлов, размер директории (сколько памяти занимает)
- (**2 балла**) скрипт может скопировать все файлы `директории для обработки` (любого уровня вложенности) в корень `директории для сохранения результатов` (обратите внимание, повторение иерархии вложенных папок `директории для обработки` в `директории для сохранения результатов` не только не требуется, но и противоречит заданию)
- (**1 балл**) скрипт может создать архив с именем `имя архива`, в который добавлены все файлы из `директории для обработки` 
- (**2 балла**) скрипт при копировании файлов из `директории для обработки` в `директорию для сохранения результатов` умеет корректно (без потери информации) обрабатывать ситуации, когда в `директории для обработки` имеются файлы с одинаковым именем
- (**1 балл**) скрипт при передаче параметра `-h` (*help*) выводит краткую справку о том, что он делает, и какие параметры принимает
- (**1 балл**) скрипт при передаче параметра `-s` (*silence*) продолжает выполнять все те же действия, но ничего не выводит в консоль

#### **Пример работы**: 

**input_dir**:

- *A*
  - *test.txt*
  - *readme.md*

- *B*
  - *test.txt*

`my_script input_dir output_dir archive_name`

`2 dirs, 3 files, 1,5Kb`

**output_dir**

- *test.txt*
- *test_2.txt*
- *readme.md*

#### **Правила сдачи**

Отправьте выполненное задание в формате скрипта (в формате *.sh*) на электронную почту вашего семинариста. 

**Обязательно** укажите тему письма в формате *ТП2\_ТЗ1\_ГРУППА\_ФАМИЛИЯ* (например, ТП2\_ТЗ1\_292\_ПЕТРОВ)

## Техническое задание №2 (ТЗ2)

> Составлять диаграммы можно в любом удобном для вас ПО или с помощью любого веб-сервиса. Мы предлагаем варианты: [draw.io](https://app.diagrams.net/), [Miro](https://miro.com/), [plantuml](https://plantuml.com/ru/)

:fire: **Дедлайн**: 28 ноября, 23:59

#### **Задание**: 
Вам необходимо составить несколько UML-диаграмм для описания процесса снятия денег в банкомате. 
Обратите внимание на описание пунктов задания. Ничего "сверх" описанного делать не нужно, баллы за это, конечно, не снимаются, но и дополнительные баллы не начисляются. Также обратим внимание, что от вас не требуется знание того, как этот процесс устроен в действительности в реальных банкоматах (и проверять это мы не будем). Ваша задача описать процесс таким, каким вы его себе представляете (но тем не менее, он должен был логичным, последовательным и не противоречить здравому смыслу). Все диаграммы, выполненные в рамках задания, должна быть согласованы между собой (не должны противоречить друг другу).

- (**2 балла**) Составьте `диаграмму вариантов использования` (предполагаем, что банкомат умеет только выдавать деньги, больше ничего - ни платежей, ни внесения наличных). Не забудьте, что банкомат действует не сам по себе, а взаимодействует с серверами банка. При этом мы говорим именно о вариантах использования банкомата. Правильно расставьте границы системы. 
- (**3 балла**) Составьте `диаграмму последовательности` для процесса снятия денег. Не забудьте, что любые операции, производимые на банкомате, требуют согласованности с серверами банка. Также не забудьте о том, что связь между банкоматом и серверами банка может работать нестабильно, либо вообще не работать - в таком случае можно и отказать в выполнении операции. 
- (**2 балла**) Составьте `диаграмму состояний` банкомата в процессе работы, с учетом выполнения операции выдачи денег. Обязательно укажите внутренние состоятия процесса выдачи денег (например, `проверка пин-кода`, `ожидание ответа сервера`). Решения с одним состоянием `выдает деньги` приниматься не будут.
- (**2 балла**) Составьте `диаграмму деятельности` для процесса получения денег в банкомате.
- (**1 балл**) Подумайте, как обеспечить возможность работы банкомата в случае отсутствия связи с серверами банка (например, для выдачи небольших сумм денег). Отразите предлагаемое решение на `диаграмме деятельности`. **Обратите внимание**, не нужно вносить изменения в уже сделанную диаграмму - сделайте копию, и внесите необходимые корректировки. Т.е. вы будете присылать семинаристу на проверку две диаграммы деятельности: 1) обычный режим работы 2) работа в случае отсутствия связи с серверами банка.


#### **Правила сдачи**

Отправьте выполненное задание в формате изображений (*jpg, png*) или pdf-файла на электронную почту вашего семинариста. 

**Обязательно** укажите тему письма в формате *ТП2\_ТЗ2\_ГРУППА\_ФАМИЛИЯ* (например, ТП2\_ТЗ2\_293\_ИВАНОВ)

## Техническое задание №3 (ТЗ3)

*TBA*

## Письменный экзамен (ЭКЗ)

*TBA*

# Правила оценивания

*Оценка* = Округление (0,25\*(*ТЗ1* + *ТЗ2* + *ТЗ3*)/3 + 0,25\**КР* + 0,5\**ЭКЗ*)

[0]:https://img.shields.io/badge/year-2021%2F2022-blue
[1]:https://img.shields.io/badge/status-running-green
[2]:https://progress-bar.dev/50/