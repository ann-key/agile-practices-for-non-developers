# Командный тренинг «Культура, процесс и инженерные практики Agile в продуктовой разработке для не-разработчиков»
_Как помочь команде втаскивать успешные продукты._ 24 hrs.

![](vision.png)

# Objectives
## После тренинга участники смогут применять:
### Коммуникации с инженерами
- [ ] Понимание *языка разработчиков*
- [ ] Их *способы решения задач*
- [ ] Их *когнитивные ловушки*
### Продуктовая бизнес-модель
- [ ] *Ценности* продуктовой разработки для обоснования процессных решений
- [ ] *Видение продукта* для упрощения принятия инженерных решений
### Культура и процесс
- [ ] *Производственная культура* для осознания личной и командной культур инженерами
- [ ] Принцип *Just in Time поставок* и практика *Time Boxing*
- [ ] Как померить качество через *rework*
- [ ] PBI *DoD* как механизм контроля внутреннего качества
- [ ] *Информационные радиаторы* как инструмент коммуникаций с инженерами
- [ ] *Парная разработка* в формате Driver + Navigator и когда ее применять
- [ ] *Trunk based development*, *Feature Toggling*
### Работа с требованиями
- [ ] Понимание ценности в формате *User Story*
- [ ] *Декомпозиция* пользовательских историй
- [ ] Ключевые внешние *NFRs*
### Инженерные практики обеспечения внешнего качества
- [ ] *ATDD*, *Front-end tests*, *BDD*
- [ ] *Автоматизированное тестирование* и базовые техники *тест-дизайна*, *изоляции* и *анализа покрытия*
### Инженерные практики обеспечения внутреннего качества
- [ ] *Внутренняя модель качества* из обоснованных внутренних NFRs и *технический долг*
- [ ] *TDD*
- [ ] *Simple Design*
- [ ] *Рефакторинг* 
- [ ] *Code Review*
- [ ] *Статический анализ кода*
### Инженерные практики ускорения поставок
- [ ] *Автоматическая сборки* релиза
- [ ] *CI*
- [ ] *Версионирование схемы БД*
- [ ] *CD*
- [ ] *Культура DevOps* и *Continouos Feedback*
- [ ] Мониторинг *системных- и продуктовых метрик*

# Программа
## 1. Зачем мы собрались? (0.5 часа всего / _из них_ 0.25 часа практики и обсуждений)
- [ ] Знакомство с тренером
- [ ] Договоренности
- [ ] Разбивка по командам по "бразильской системе" в соотвествии с принципами Scrum
- [ ] Самостоятельный обзор тренинга в группах
- [ ] Парковка кейсов и проблем участников: проблемные ситуации на производстве
- [ ] Ветка потока в github
### Уровни решений в производстве ПО
- [ ] Общая картина дисциплин "снизу-вверх"

## Что такое продуктовый бизнес и что он ждет от производства? (1/1)
### Продуктовая бизнес-модель
- [ ] Как вы определяете бизнес по разработке цифровых продуктов?
- [ ] Важнейшие особенности продуктовой разработки
- Тиражируемость
- Инновационность
- Неопределенность
- Снижение лояльности к брендам: нерерывное развитие
- В запутанных системах бизнес-рынок-клиенты нельзя ничего предсказать
### Общая картина бизнес-моделей: паттерны
- [ ] Продукт и Заказ
- [ ] In-house и Outsource
- [ ] Сервис и Проект
- [ ] Стартап и Зрелый
- [ ] T&M и Fixed*
### Что _продуктовый_ бизнес ждет от производства
- [ ] Подходы к неопределенности по модели Cynefin
### Декларируем наши команды на разделение бизнес-ценностей
- [ ] Каковы ключевые метрики продуктового бизнеса?
- [ ] Как вы поймете, что сделали бизнесу хорошо? Манифест команды.
- [ ] На какие trade-offs придется пойти?

## Sound-check (0/0)
- [ ] Участники могут на своих машинах клонировать, собрать проект и запушить изменения

## Что продуктовый бизнес ждет от _производственной культуры_ (1/1)
- [ ] Понятие культуры компании
- [ ] Роль производственной культуры компании
- [ ] Групповая практика на определение производственной культуры по Шнайдеру
- [ ] [Типовые когнитивные ловушки инженеров](https://www.dropbox.com/s/o1bgzqldh25fpti/%D0%90%D0%BD%D1%82%D0%B8%D0%BF%D0%B0%D1%82%D1%82%D0%B5%D1%80%D0%BD%D1%8B%20%D0%BF%D0%BE%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D1%8F%20%D1%80%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%87%D0%B8%D0%BA%D0%BE%D0%B2%20%D0%B2%20%D0%BF%D1%80%D0%BE%D0%B4%D1%83%D0%BA%D1%82%D0%BE%D0%B2%D1%8B%D1%85%20%D0%BA%D0%BE%D0%BC%D0%BF%D0%B0%D0%BD%D0%B8%D1%8F%D1%85.pdf?dl=0) - выбираем кейсы из своей практики для дальнейшего решения
### Декларируем наши команды на соответствие ожиданиям
- [ ] Как вы "продадите" свою команду бизнесу, что бы выбрали именно вас? Обновляем Манифест команды.
```
Мы поможем двигать продукт вперёд по бизнес-метрикам к успеху 
за счёт быстрых эффективных проверок новых гипотез и анализа текущего использования. 
Мы обеспечим качество продукта в условиях непрерывного потока изменений 
за счёт осмысленного применения современных инженерных практик. 
Наше преимущество - быстрая реакция на любые изменения, 
это удаётся нам за счёт сознательного развития высокоадаптивной внутренней культуры. 
```
- [ ] На какие trade-offs придется пойти?

## Что продуктовый бизнес ждет от _производственной системы_ (1/0.5)
### Команды выбирают процессные паттерны и обосновывают через бизнес-метрики
- [ ] Подход SLA к балансу бизнес-метрик: scope, time, quality, price, ?. Time-boxing.
- [ ] Подход к частоте поставок: сервис/проекты
- [ ] Подход к запасам. JIT. Запасы в IT-разработке.
- [ ] Подход к структуре команд: feature teams/matrix. Свойства feature team.
- [ ] Подход к формализации/самоуправлению
- [ ] Подход к описанию процесса: процедурный/декларативный. Практика PBI DoD
- [ ] Подход к ответственности: персональная/коллективная
- [ ] Подход к коммуникациям: формальная/неформальная. Распределение знаний по артефактам.
- [ ] Подход к экспертизе: фокусировка/T-shaping. Практика Star Map.
- [ ] Подход к инженерным решениям: все запроектировать заранее/откладывай@делегируй
- [ ] Подход к гибкости в архитектуре: делать гибко/делать просто
- [ ] Подход к внутреннему качеству (техдолгу): фигак-фигак-и-впродакшн/техналог 
### Трансформация
- [ ] Работающие инженерные практики как результат трансформации
- [ ] Reference: [Как безопасно трансформировать культуру и процесс](https://www.dropbox.com/s/h9ghvkktirbxgdw/%D0%98%D0%BD%D0%BA%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B9%20%D0%BF%D0%BE%D0%B4%D1%85%D0%BE%D0%B4%20%D0%BA%20%D0%B8%D0%B7%D0%BC%D0%B5%D0%BD%D0%B5%D0%BD%D0%B8%D1%8E%20%D0%BA%D1%83%D0%BB%D1%8C%D1%82%D1%83%D1%80%D1%8B%20%D0%B8%20%D0%B2%D0%BD%D0%B5%D0%B4%D1%80%D0%B5%D0%BD%D0%B8%D1%8E%20%D0%BF%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D0%BA%20Agile.pdf?dl=0) 
- [ ] Культура DevOps и Continouos Feedback

## Sprint PRODDEV-01: продуктовая модель (0/0.5)
- [ ] Что такое product development/discovery?
- [ ] Как сформулировать гипотезу продуктовой бизнес-модели? Формальные/неформальные подходы
- [ ] На какие ключевые вопросы должна отвечать продуктовая гипотеза?
- [ ] Зачем нужна metaphor/vision?
```
Наш продукт Фито-няша для толстячков,
в отличие от боди-позитива содержит кокаин.
```
### Формулируем гипотезы продуктовой бизнес-модели
#### Даны
- [ ] Структура Lean Canvas
#### Когда команды проведут
- [ ] Дизайн продуктовой гипотезы в формате Lean Canvas
- [ ] Фокусировка с помощью Vision
- [ ] Меппинг на архитектурные риски
- [ ] Scope решения в терминах epics
#### Тогда на дебрифе
- [ ] Кросс-ревью метафор
- [ ] Кросс-ревью продуктовых моделей
#### Ретро

---

## Ретроспектива по вчерашнему дню (0.5/0.5)
- [ ] Закрытые цели тренинга, burndown
- [ ] Персональные инсайты
- [ ] 𝚫+
- [ ] Take-away actions

## Sprint PRODDEV-02: беклог как выражение продуктовой стратегии (0.5/0)
### Backlog
- [ ] Что такое беклог? Какие ключевые свойства?
- [ ] Элементы беклога – единица планирования и результ процесса коммуникации
- [ ] Как происходит управление элементами беклога? Порядок внесения новых элементов, уточнение и жизненный цикл.
- [ ] Элементы беклога: Themes, Epics, User Stories
### BPI
- [ ] Name
- [ ] Story
- [ ] Acceptance Criteria (*GWT*)
- [ ] NFRs
- [ ] DoD
### *Декомпозиция историй*
- [ ] Почему важно декомпозировать истории? 
- [ ] Как обеспечить "тонкую нарезку" инкрементов?
### Первичный дизайн беклога
#### Дано
- [ ] Практика User Story Mapping
- [ ] Практики декомпозиции историй
#### Когда
- [ ] Команды проведут USM
- [ ] Получат беклоги c подробными PBI на первый спринт
#### Тогда на дебрифе
- [ ] Кросс-ревью командных беклогов
#### Ретро

## Введение в разработку ПО (1.5/0.5)
### Разработчики не такие умные
- [ ] Модель уровней понимания и зоны черного ящика
- [ ] Закон расширения черного ящика: цикл Коулба
### Live Coding Demo: ключевые технологические решения в разработке и история
- [ ] Кейс: онлайн-система персонального финучета
- [ ] OS и Hardware
- [ ] Исходники и синтаксис
- [ ] Компиляция
- [ ] Запуск приложения
- [ ] Процедурный стиль
- [ ] Библиотеки кода
- [ ] Объектный стиль
- [ ] Конфигурация vs hardcode
- [ ] Фреймворки
- [ ] Автотесты
### Итого
![](flipcharts/Screenshot%202019-12-03%20at%2017.55.59.png)
### Начинаем песональный глоссарий технологий и практик
- [ ] В отдельном документе Markdown для каждой команды
- [ ] *Свой* глоссарий важных для *вас* концепций

## Командная работа с кодом (1/0.5)
### DVCS local workflow
- [ ] Local repo
- [ ] Workspace
- [ ] Commit
- [ ] Branch and merge
- [ ] Log
### DVCS remote workflow
- [ ] Remote repo
- [ ] Clone
- [ ] Push
- [ ] Pull
### Configuration Management patterns
- [ ] Repo patterns: centralized/decentralized
- [ ] Branch patterns: GitFlow/TBD+FT
- [ ] Pull Requests
### Hands-on
- [ ] Github account
- [ ] Central Glossary github repo
- [ ] Teams make overall cross-team glossary

---

## Ретроспектива по вчерашнему дню (0.5/0.5)
- [ ] Закрытые цели тренинга, burndown
- [ ] Персональные инсайты
- [ ] 𝚫+
- [ ] Take-away actions

## Введение в типовую архитектуру современных систем и автосборку (1.5/0.5)
### Кейс: онлайн-система персонального финучета
- [ ] Points Of View
- [ ] Архитектура клиент-сервер
- [ ] Удаленные вызовы и типы клиентов
- [ ] Типовые паттерны в рамках системы
- [ ] Помощь фреймворка Spring
- [ ] Хранилища данных
### Автоматическая сборка проекта
- [ ] Maven build tooling
- [ ] Maven dependency tooling
### Hand-on
- [ ] Cloning project from [corporate repo](http://84.201.134.115:7990/scm/dbo/dbo-app.git) / admin:Ag1lePracticeS
- [ ] Building and running app

## Переход к процессу разработки и поставки: дизайн процесса через выбор практик (1.5/0.5)
- [ ] Современное отношение к дизайну процессов: от императивности и формальности к декларативности и гибкости
- [ ] Выбор практик как process design core
- [ ] [Как DevOps помогает продуктовой разработке](https://paper.dropbox.com/doc/Delivery-Pipeline-ci-cd-devops--AbaLMZphhnvfm0spHme2SHkYAg-OBLCVRSkMek24U7IXIHbq)
### Проектируем модель зрелости процесса через практики
#### Даны уровни зрелости процесса с т.з. продуктового бизнеса
1. Уровень: хоть как-то получаем хоть какой-то результат на prod
2. Уровень: управляем внешним качеством
3. Уровень: управляем внутренним качеством
4. Уровень: управляем TTM
5. Уровень: управляем успехом продукта
#### Когда
- [ ] Команды расставят практики из целей тренинга по уровням (+неуказанные)
- [ ] BPI DoD
#### Тогда на дебрифе
- [ ] Мерж в единый процессный беклог: долг по внедрению практик для дальнейшей проработки в рамках тренинга
- [ ] Кросс-ревью командных моделей зрелости
### CI/CD Pipeline Live Demo: пронос изменений по всему конвейеру с описанием задействованных практик
- [ ] ATTD + Cucumber + Selenium
- [ ] TBD + Feature Toggling
- [ ] TDD
- [ ] Simple Design
- [ ] Code Review
- [ ] Automated Build
- [ ] Test Coverage Metrics
- [ ] DB Versioning
- [ ] CI
- [ ] Automated Code Review and Metrics
- [ ] CD
- [ ] System and Business Metrics
### Hands-on
- [ ] Дополняем глоссарий

## Sprint DEV-01 (1/1)
### Даны
- [ ] Обзор системы автосборки, CI и анализа кода
- [ ] Беклог
- [ ] Legacy codebase и инфраструктура
### Когда
- [ ] Команды проводят декомпозицию User Stories
- [ ] Команды фиксируют NFRs
- [ ] Команды проводят Sprint Planning
- [ ] Команды проводят спринт
- [ ] Парная работа в формате Driver + Navigator
- [ ] Помощь тренера по решению блокеров
### Тогда
- [ ] Sprint Review
- [ ] Добавление технического долга в беклог
- [ ] Retro

## Sprint DEV-02 (1/1)
### Даны
- [ ] Обзор системы автосборки, CI и анализа кода
- [ ] Беклог
- [ ] Legacy codebase и инфраструктура
### Когда
- [ ] Команды проводят декомпозицию User Stories
- [ ] Команды фиксируют NFRs
- [ ] Команды проводят Sprint Planning
- [ ] Команды проводят спринт
- [ ] Парная работа в формате Driver + Navigator
- [ ] Помощь тренера по решению блокеров
### Тогда
- [ ] Sprint Review
- [ ] Добавление технического долга в беклог
- [ ] Retro

## Финальная ретроспектива (0.5/0.5)
### Даны
- [ ] Полученные на тренинге знания
- [ ] Полученные на тренинге практический опыт
- [ ] Полученные на тренинге артефакты
### Когда
- [ ] Кросс-командная ретроспектива тренинга
### Тогда
- [ ] Закрытые цели тренинга, burndown
- [ ] Инсайты
- [ ] 𝚫+
- [ ] *Обоснованные* next actions на производстве
