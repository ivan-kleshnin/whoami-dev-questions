# Вопросы для определения уровня разработчика

*Копипасту можно считать за реализацию, если вы разобрались как она работает*
*и считаете, что сможете реализовать такой же проект самостоятельно.*
*Описания даны для примера – выбирается уровень сложности а не наборы ДА и НЕТ*

### Браузерное приложение

#### Основное (выбрать 1 ближайший)
- [x] Нет опыта
- [ ] Одностраничное приложение на "чистом JavaScript"
- [ ] Одностраничное приложение на "старом" фреймворке (jQuery, Backbone)
- [ ] Одностраничное приложение на "современном" фреймворке (Angular, React, Svelte, Vue)
- [ ] Одностраничное приложение с API
- [ ] Многостраничное приложение
- [ ] Многостраничное приложение с SSR

#### Бонусы (выбрать все подходящие)
- [ ] Приложение документировано (полноценный гайд "Как инсталлировать" и т.д)
- [ ] Приложение типизировано (TypeScript) (типизировано 75+% кода)
- [ ] Приложение покрыто E2E тестами (тестируется 50+% функционала)
- [ ] Приложение содержит библиотечный код (проработанные хуки, поля форм, и т.д.)

### Мобильное приложение

#### Основное (выбрать 1 ближайший)
- [x] Нет опыта
- [ ] Простейшее одноэкранное приложение 
- [ ] Простейшее многоэкранное приложение
- [ ] Многоэкранное приложение с настройками и продуманным UI
- [ ] Приложение с режимами работы (активное, бэкграунд и т.д)

#### Бонусы (выбрать все подходящие)
- [ ] Приложение документировано (полноценный гайд "Как инсталлировать" и т.д)
- [ ] Приложение покрыто E2E тестами (тестируется 50+% функционала)
- [ ] Приложение содержит библиотечный код
- [ ] Приложение общается с сервером
- [ ] Приложение использует сенсоры устройства

### Утилита командной строки

#### Основное (выбрать 1 ближайший)
- [x] Нет опыта
- [ ] Простая команда с аргументами
- [ ] Команда с флагами
- [ ] Команда с флагами и меню помощи (--help)
- [ ] Команда с использование форков (sub-shells)
- [ ] Интерактивная утилита (поля ввода и т.д)

#### Бонусы (выбрать все подходящие)
- [ ] Приложение документировано (полноценный гайд "Как инсталлировать" и т.д)
- [ ] Приложение типизировано (TypeScript) (типизировано 75+% кода)
- [ ] Приложение покрыто E2E тестами (тестируется 50+% функционала)
- [ ] Приложение содержит библиотечный код (алгоритмы и т.д.)

### REST API

#### Основное (выбрать 1 ближайший)
- [x] Нет опыта
- [ ] Демка с 1-2 эндпойнтами
- [ ] CRUD 
- [ ] CRUD + Списки (кастомная фильтрация, сортировка, паджинация)
- [ ] Валидация, система прав доступа
- [ ] Отлаженный библиотечный код (автоконверсия REST Query -> SQL/Mongo Query)

#### Бонусы (выбрать все подходящие)
- [ ] API документировано (описано 90+% функционала, описания синхронизированы с кодом)
- [ ] API работает(-ло) в продакшене
- [ ] Выдерживает нагрузку в 100 одновременных клиентов
- [ ] Выдерживает нагрузку в 1000 одновременных клиентов
- [ ] Поддержка мультиязычности
- [ ] Риалтайм функционал (Сокеты)
- [ ] Приложение содержит библиотечный код (автоконверсия Query -> SQL, продуманная авторизация и т.д)

### GraphQL API

#### Основное (выбрать 1 ближайший)
- [x] Нет опыта
- [ ] Демка на 1-2 модели
- [ ] CRUD
- [ ] CRUD + списки (фильтрация, сортировка, паджинация)
- [ ] Валидация, система прав доступа
- [ ] Использование Dataloader
- [ ] Отлаженный библиотечный код (автоконверсия GraphQL Query -> SQL/Mongo Query)

#### Бонусы (выбрать все подходящие)
- [ ] API работает(-ло) в продакшене
- [ ] Выдерживает нагрузку в 100 одновременных клиентов
- [ ] Выдерживает нагрузку в 1000 одновременных клиентов
- [ ] Поддержка мультиязычности
- [ ] Риалтайм функционал (Subscriptions)
- [ ] Приложение содержит библиотечный код (автоконверсия GQL -> SQL, продуманная авторизация и т.д)

### Проектирование БД

#### Основное (выбрать 1 ближайший)
- [x] Нет опыта
- [ ] Практика с Excel или Google Sheets
- [ ] Реляционная БД на 2-5 таблиц без индексов
- [ ] Реляционная БД на 5+ таблиц с индексами, продуманная нормализация
- [ ] Реляционная БД со множеством таблиц и разнообразными связями (1-1, 1-N, M-N)
- [ ] Графовая БД на 2-5 типов
- [ ] Графовая БД на 10+ типов

#### Бонусы (выбрать все подходящие)
- [ ] БД работает(-ло) в продакшене
- [ ] Поддержка мультиязычности
- [ ] Структура БД пережила 10 и более миграций (и не была отброшена)

### Игровое приложение

#### Основное (выбрать 1 ближайший)
- [x] Нет опыта
- [ ] Пошаговая 2D игра (текстовые квесты, поле в клеточку, псевдографика)
- [ ] Пошаговая 2D на фреймворке (графика на спрайтах)
- [ ] Песочница риалтайм 2D игры (скроллер-аркада или другое)
- [ ] Песочница риалтайм 3D игры
- [ ] Продуманный геймплей, уровни и сюжет (2D или 3D)

#### Бонусы (выбрать все подходящие)
- [ ] Графика с просчётом освещения
- [ ] Графика с анимациями
- [ ] Звуковое сопровождение
- [ ] Игра была опубликована и имеет(-ла) реальных игроков
- [ ] Многопользовательская игра
- [ ] Автогенерация мира/уровней
- [ ] Алгоритм соперника на базе MINIMAX
- [ ] Алгоритм соперника на базе нейронной сети

*Тут сложно уместить в один опрос, подразумевается геймдев как хобби, а не профессия* 

### Разработка библиотек и фреймворков

#### Основное (выбрать 1 ближайший)
- [x] Нет опыта
- [ ] Проект-стартер (пример настроек/использования чужого инструмента)
- [ ] Набор универсальных хелперов (а-ля Lodash)
- [ ] Таргетирует узкую проблему (MultiSelect с тегами, проверка прав доступа и т.д)
- [ ] Таргетирует слой приложения (реализация Virtual DOM)
- [ ] Таргетирует платформу (Express, Vue, React)
- [ ] Демка языка программирования
- [ ] "Реальный" язык программирования

#### Бонусы (выбрать все подходящие)
- [ ] Инструмент документирован (гайды "Как инсталлировать", "Как использовать" и т.д)
- [ ] Инструмент типизирован (типизировано 75+% кода)
- [ ] Инструмент покрыт интеграционными тестами (тестируется 50+% функционала)
- [ ] Инструмент используется(-валcя) в реальной практике
- [ ] Инструмент включает сложные алгоритмы (ресайз изображения и т.д) 
- [ ] Инструмент включает сложные эвристики (экспертная система)
- [ ] Инструмент использует алгоритмы машинного обучения
- [ ] Инструмент собрал 1000+ звёзд GitHub или 50000 недельных скачиваний NPM

### Самообразование

#### Основное (выбрать 1 ближайший)
- [x] Нет опыта
- [ ] Просматриваю новости по специальности
- [ ] Регулярно читаю блоги, книги, слушаю подкасты
- [ ] Веду блог по специальности
- [ ] Имею план по развитию на ближайшие годы

#### Бонусы (выбрать все подходящие)
- [ ] Есть опыт составления туториалов или задачек (а-ля CodeWars, не менее 10 задач)
- [ ] Занимался с ментором (есть фидбек по качеству кода/решений от специалиста)
- [ ] Имею высшее образование по специальности
- [ ] Написал книгу или составил курс по специальности

### Компьютерная наука (как хобби)

#### Основное (выбрать 1 ближайший)
- [x] Нет опыта
- [ ] Забыл весь матан, вспоминаю по необходимости
- [ ] Помню основы дискретки, что-то из теории вероятностей, азы информатики
- [ ] Знаю 1-2 спец. направления (формальная логика, линейная алгебра, тригонометрия и т.д)
- [ ] Знаю несколько смежных направлений (статистика, например)
- [ ] Продвинулся дальше 

#### Бонусы (выбрать все подходящие)
- [ ] Знаю как устроены сети, опыт реализации сетевых протоколов
- [ ] Опыт работы с блокчейнами
- [ ] Опыт использования математических методов
- [ ] Опыт использования машинного обучения
- [ ] Опыт проектирования алгоритмов
- [ ] Опыт проектирования алгоритмических систем

### Опыт работы в годах (по одной специальности)

#### Основное (выбрать 1 ближайший)
- [x] Нет опыта
- [ ] До 1 года
- [ ] 1–3 года
- [ ] 3–5 лет
- [ ] 5–10 лет
- [ ] 10–15 лет
- [ ] 15 и более лет

### Командная работа

#### Основное (выбрать 1 ближайший)
- [x] Нет опыта
- [ ] Опыт фриланса
- [ ] Опыт работы в небольшой команде (до 5 человек)
- [ ] Опыт работы в средней команде (до 20 человек)
- [ ] Опыт работы в крупной команде (40 человек и более)
- [ ] Опыт кураторства/менторства младшего специалиста
- [ ] Опыт лида небольшой команды
- [ ] Опыт лида средней команды
- [ ] Опыт лида крупной команды

#### Бонусы (выбрать все подходящие)
- [ ] Команда включала людей из разных культур
