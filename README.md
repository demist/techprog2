![year][0] ![status][1] ![progress][2]

## Summary

**2 модуль, 2021/2022 учебный год, ВШЭ ВШБ ДБИ**

## Канал курса в telegram

## Таблица с результатами по курсу

# Аннотация

*Курс про все, что связано с созданием ПО, кроме непосредственно написания программного кода*

Курс состоит из лекций и семинарских занятий.

Лекционный материал включает краткий обзор важных с точки зрения процесса разработки понятий: методы отладки и этапы исправления дефектов ПО, критерии хорошей и неудачной архитектуры, этапы проектирования и разработки, методологии разработки.
Семинарский материал состоит из рассказа о важных инструментах программиста: системы контроля версий, системы сборки, gdb, valgrind, развертывание и настройка систем непрерывной интеграции.

Цель курса — дать слушателям, которые параллельно изучают языки программирования, алгоритмы и т. п., информацию и дополнительные знания, какими инструментами можно пользоваться и на что обращать внимание при создании рыночного программного продукта.

# План лекций

## Лекция №0 *(неделя 1)*

- План курса
- Правила оценки
- Информация о заданиях
- Контрольные мероприятия

## Лекция №1 *(неделя 1)*

**Принципы проектирования ПО, часть 1**

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

## Лекция №2 *(неделя 1)*

**Принципы проектирования ПО, часть 2**

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

## Лекция №3 *(неделя 2)*

**Основные диаграммы UML**

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

## Лекция №4 *(неделя 2)*

**Этапы развития проекта**

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

## Лекция №5 *(неделя 3)*

**Методологии разработки ПО**

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

## Лекция №6 *(неделя 3)*

**Отладка ПО, ч.1: работа с ошибками ПО**

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


## Лекция №7 *(неделя 4)*

**Отладка ПО, ч.2: техники отладки**

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


## Лекция №8 *(неделя 4)*

*Часть времени этой лекции съест лекционная контрольная работа*

**Управление качеством ПО, ч.1**

- Понятие о качестве ПО
- Характеристики и атрибуты качества ПО
- Основые аспекты качества ПО
- Парадокс тестировщика
- Соответствие ожиданиям stakeholder'ов
- Качество и деньги
	- Десятичное правило качества
	- Важные аспекты

## Лекция №9 *(неделя 5)*

**Управление качеством ПО, ч.2**

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

**CI/CD/CD**

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

**Архитектурные паттерны**

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

**Базовые понятия о языках программирования**

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

[0]:https://img.shields.io/badge/year-2021%2F2022-blue
[1]:https://img.shields.io/badge/status-pending-yellow
[2]:https://progress-bar.dev/0/