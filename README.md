**Архитектура ПО (семинары)**

***HomeWork 1. Введение в понятие архитектуры, проектирование ПО и жизненный цикл программного продукта. UML-диаграммы***

Задание 1. На основе Диаграмы классов ModelElements, разработать классы: Model Store, PoligonalModel (Texture, Poligon), Flash, Camera, Scene (Реализовать диограмму на любом языке программирования)
__

Задание 2. Ознакомиться с документацией в свободном формате, которая может пригодиться Вам для дальнейшей работы:

__
ГОСТ Р ИСО/МЭК 12207-2010 Информационная технология (ИТ). Системная и программная инженерия. Процессы жизненного цикла программных средств.
ISO/IEC/IEEE 29148:2018 Systems and software engineering — Life cycle processes — Requirements engineering
Стандарты ЕСКД — единая система конструкторской документации
ГОСТ 2.001-2013 ЕСКД. Общие положения
Стандарты АСУ ГОСТ 34 — автоматизированные системы управления
Стандарты ЕСПД ГОСТ 19 — единая система программной документации


***HomeWork 2. Объектно-ориентированные паттерны***

Задание:

Прислать простую реализацию 5-ти Патернов ,на любом языке (С комментариями ), из списка -

Строитель (Builder)

Цепочка обязанностей (Chain of Responsibility)

Команда (Command)

Итератор (Iterator)

Посредник (Mediator)

Памятка (Memento)

Состояние (State)

Стратегия (Strategy)

Шаблонный метод (Template Method)

Посетитель (Visitor)

Познакомиться с другими типами паттернов(по желанию)


***HomeWork 3. Принципы SOLID***

Продолжить работу с семинара.
Hассмотрим четвертый принцип SOLID - Принцип сегрегации интерфейса (Interface Segregation Principle, ISP). Он гласит: "Клиенты не должны зависеть от интерфейсов, которые они не используют".
Вам надо написать код который исправяет эту ошибку и реализует этот принцип
Пример кода, который нарушает ISP:


И аналогично 5-ый принцип

Принцип инверсии зависимостей (Dependency Inversion Principle, DIP) гласит: "Зависимости на абстракциях. Нет зависимостей на что-то конкретное". Это означает, что высокоуровневые модули, которые обеспечивают сложную логику, должны быть независимы от низкоуровневых модулей, которые обеспечивают утилитарные функции. Оба типа модулей должны зависеть от абстракций.

Пример кода, который нарушает DIP:


***HomeWork 3. Компоненты. Принципы связности и сочетаемости компонентов***
Вам необходимо доработать код, добавив контракты к методам, документацию и обеспечив высокую связанность и низкую сочетаемость:
Файл Задание.txt


***HomeWork 5. Горизонтальные уровни и вертикальные срезы архитектуры***

Джава - https://github.com/vyntyk/Srezy.git

Питон - https://github.com/JuliaRyzhova/Software_architecture/tree/main/Seminar_5

Реализовать любой паттерн с лекции . Выпустить диаграмму компонент UML по нему.

***HomeWork 6. Принципы построения приложений «чистая архитектура»***

Задание: 

Переделка программы под чистую архитектуру
__
Вам предоставляется программа, которая представляет интернет-магазин книг с использованием коллекций. Ваша задача - переработать эту программу, применяя принципы чистой архитектуры для лучшей организации кода и разделения компонентов. В результате переработки программа должна следовать принципам Boundary-Control-Entity (BCE).

***HomeWork 7. Типы архитектур WEB-приложений: MPA, SPA.***

Домашнее задание -
__
1. Подготовительный этап:
- Определение целей и задач приложения.
- Анализ аудитории и исследование рынка.
- Создание общего описания концепции и функциональности.

__
!!!ПРИМЕР ВЫПОЛНЕНИЯ!!!
https://github.com/CrazyQWERTYlunch/software_architecture/tree/main/Homework7
!!!


***HomeWork 8. Типы архитектур прикладных приложений (мобильные): MVC, MVP, MVVM.***

Задание: Создание UML диаграммы классов для веб-приложения(Любого, но лучше взять за основу прошлую работу)
__

Пример. Вы работаете над проектированием веб-приложения для онлайн-магазина книг. Вам нужно создать UML-диаграмму классов, отображающую связи между основными классами вашего приложения. 
Вам также необходимо создать YAML-диаграмму для этой диаграммы классов.
__

Инструкции:
__

Определите основные классы, которые будут присутствовать в вашем веб-приложении. Например, классы "Пользователь", "Книга", "Корзина", "Заказ" и другие.

Определите связи между этими классами. Например, класс "Пользователь" может иметь ассоциацию с классом "Корзина", а класс "Корзина" может иметь ассоциацию с классом "Книга".

Создайте UML-диаграмму классов, на которой отобразите классы и связи между ними. Не включайте методы и поля, только связи между классами.

Создайте YAML-диаграмму для этой UML-диаграммы классов. В YAML-диаграмме укажите только имена классов и связи между ними.
Примечание:
__

Ваша UML-диаграмма должна визуализировать связи между классами, такие как ассоциации, агрегации и композиции.

Ваша YAML-диаграмма должна быть валидным YAML-файлом и отражать связи между классами.

Вы можете использовать любой инструмент для создания диаграмм, такой как draw.io, Lucidchart или даже бумагу и карандаш.


***HomeWork 9. Способы организации передачи данных между компонентами приложения, протоколы и API. REST, gRPC, очереди..***

Материaл с Семинара https://github.com/vyntyk/untitledAPI.git

Итоги и ключевые моменты:
HTTP и REST:

HTTP - протокол передачи данных в сети, используется для взаимодействия между клиентом и сервером.

REST (Representational State Transfer) - архитектурный стиль, который определяет принципы для построения веб-сервисов.

REST API - интерфейс для взаимодействия между клиентами и серверами по принципам REST.

JSON (JavaScript Object Notation):

JSON - легкий формат обмена данными, основанный на синтаксисе JavaScript.

JSON представляет данные в виде пар "ключ-значение" и поддерживает массивы и вложенные структуры.

Часто используется для передачи данных между клиентом и сервером в RESTful API.

Apache Maven:

Maven - инструмент для автоматизации сборки проектов, управления зависимостями и генерации документации.
Основные понятия Maven: проект, артефакт, зависимость, цель, плагин.
Файл "pom.xml" содержит настройки проекта, зависимости и инструкции для сборки.

Пример использования:

Мы создали простое RESTful API с использованием Java HTTP Server API.

Пример демонстрирует обработку GET, POST и DELETE запросов к ресурсу "/users".

Для работы с JSON мы использовали библиотеку Jackson для сериализации и десериализации данных.

Задание Java (Коротко , потому как разбирали на семинаре)

Задачи*:

1. Разработать простой RESTful API для сущности "Книга".

2. Провести тестирование созданного API с помощью инструментов вроде Postman или брузера , как делали на семмнаре


Подробная инструкция:

1. Разработка RESTful API для сущности "Книга"

a. Определение модели "Книга":

- Определите атрибуты для книги: например, ID, название, автор, год издания и т.д.

b. Создание API:
- Используя ваше предпочтительное программное обеспечение или фреймворк (например, Express для Node.js, Flask для Python и т.д.), создайте базовые CRUD операции:
- POST /books - добавить новую книгу.
- GET /books - получить список всех книг.
- GET /books/{id} - получить информацию о конкретной книге по ID.
- PUT /books/{id} - обновить информацию о книге.
- DELETE /books/{id} - удалить книгу.


***HomeWork 10. Структура приложения с пользовательским интерфейсом и базой данных (паттерн Repository)***

Вы можете реализовать эти патерны, в рамках своего проекта, к которому Вы делали диограммы и таблицы. Или реализовать отдельно от них.

Домашнее задание: Реализация паттернов Агрегатор, Репозиторий и Кеширования

Цель: Освоить принципы работы и применение трёх ключевых паттернов проектирования: Агрегатор, Репозиторий и Кеширование.

Часть 1: Паттерн Агрегатор
Реализуйте классы Order, OrderItem и Product.

Order должен содержать список OrderItem, каждый из которых содержит Product и количество этого продукта.

У каждого заказа должен быть метод для расчета общей стоимости.

Часть 2: Паттерн Репозиторий
Создайте интерфейс OrderRepository, который определяет методы для работы с заказами (сохранение, загрузка по ID, загрузка всех заказов и т. д.).

Реализуйте класс OrderRepositoryImpl, который реализует данный интерфейс, используя любую базу данных на ваш выбор (может быть встроенной, например, SQLite).

В репозитории обеспечьте сохранение и загрузку заказов, а также всех связанных с ними объектов (OrderItem, Product).

Часть 3: Паттерн Кеширования
Исследуйте и выберите одну из библиотек для кеширования в Java (например, EhCache, Caffeine или Guava Cache).

Реализуйте кеширование в вашем репозитории таким образом, чтобы часто запрашиваемые заказы загружались из кэша, а не из базы данных.

Обеспечьте инвалидацию кэша (обновление данных в кэше), если информация в базе данных была изменена.

Дополнительное задание:

Реализуйте пользовательский интерфейс (может быть консольным или графическим), чтобы демонстрировать создание, редактирование, загрузку и удаление заказов.

Добавьте возможность фильтрации и сортировки заказов при их загрузке из базы данных.

Советы:

Соблюдайте принципы SOLID при проектировании и реализации вашего приложения.

Обрабатывайте все возможные исключения, особенно при работе с базой данных.

Подумайте над оптимальной стратегией кеширования в зависимости от предполагаемого объема данных и частоты запросов.

Это задание предполагает разработку приложения с использованием трёх ключевых паттернов




***HomeWork 11. Сервис-ориентированные архитектуры***

Расширяем наш проект

Была одна главная страница- делаем наброски для друг страниц(Заказ, доставка, и т д в зависимости от темы.

 Пример - https://stealth-force-e00.notion.site/f38d6a54d65542fd97f8fc39aba36758?pvs=4). Вы это делаете для дизайнера, можно сделать и в пейнт, не надо тратить на это много время . https://www.figma.com/

Расширяем диограммы.

Пример на основе приложения для робота-пылесоса - https://geekbrainspro.notion.site/2-11-1b0361e053584d5db3f09064ef90cf2d

__
UML-диаграмма пакетов:
__

Пакеты и подсистемы: Показывает структуру пакетов и их взаимосвязи. Пакеты могут содержать классы, интерфейсы, диаграммы и другие элементы.

Отношения между пакетами: Диаграмма может показать, как пакеты связаны друг с другом, например, зависимости или ассоциации.

__


UML-диаграмма системы обновления приложения:
__

Компоненты и связи: Показывает компоненты, связанные с обновлением приложения, такие как "Клиентское приложение", "Сервер обновлений", "База данных версий".

Поток данных: Может включать поток данных от клиентского приложения к серверу обновлений и обратно.
__

UML-диаграмма домена (Domain Diagram):

__

Сущности и связи: Диаграмма домена обычно представляет ключевые сущности в системе и связи между ними. Это может быть базовая структура данных, которая влияет на всю систему.

Атрибуты: Диаграмма может также включать атрибуты, которые описывают каждую сущность.

Системы и компоненты: Если система состоит из различных подсистем или компонентов, они также могут быть показаны

__

UML-диаграмма системы обновления приложения:

Компоненты и связи: Показывает компоненты, связанные с обновлением приложения, такие как "Клиентское приложение", "Сервер обновлений", "База данных версий".

Поток данных: Может включать поток данных от клиентского приложения к серверу обновлений и обратно.

__
__
__
__

По желанию, но крайне рекомендуется добавить к своему проекту.

Спроектировать слой  API Gateway (mobile, web), сформировать REST запросы: GET, POST, PUT, DELETE (https://swagger.io).

Предположим, у вас есть простой API для управления списком пользователей. Вам нужно описать запрос типа GET, который вернет список всех пользователей.

__

Откройте Swagger: Перейдите на сайт https://swagger.io и, возможно, создайте новую спецификацию или проект, чтобы начать описание вашего API.

____

Описание запроса GET:
Определите функциональность API Gateway:

__

Определите, какие функции будет выполнять ваш API Gateway. Например, это может быть маршрутизация запросов от мобильных устройств и веб-клиентов к соответствующим микросервисам.

Выберите инструмент Swagger:

__

Откройте инструмент Swagger (https://swagger.io) или его альтернативы, которые позволяют создавать и документировать API.

Создайте новую спецификацию:

__

Если используете Swagger, создайте новую спецификацию (или проект) для вашего API Gateway.
Определите эндпоинты:

__

Определите список эндпоинтов (URL-путей), которые будут доступны через ваш API Gateway. Например, /mobile и /web.
Сформируйте запросы:

__

Для каждого эндпоинта, определите HTTP-методы, которые он поддерживает (GET, POST, PUT, DELETE).
Опишите запросы:

__

Для каждого метода опишите, какие параметры (если есть) должны быть переданы в запросе, а также форматы данных запроса и ответа.
Пример запроса:

__

Предоставьте пример запроса для каждого метода, чтобы пользователи могли понять, как правильно формировать запросы.
Форматы данных:

__

Укажите, какой формат данных (обычно JSON) используется для передачи данных между клиентами и API Gateway.
Генерируйте документацию:

__

Используйте возможности инструмента Swagger для автоматической генерации документации на основе вашей спецификации. Документация должна быть понятной и информативной.
Тестирование:

__

Используйте инструмент Swagger или другие инструменты для тестирования запросов на вашем API Gateway. Убедитесь, что запросы выполняются корректно.
Документация и доступность:

__

Предоставьте ссылку на документацию вашего API Gateway. Удостоверьтесь, что другие разработчики и клиенты смогут получить доступ к этой документации.

__

Помните, что проектирование API Gateway - это описание, как клиенты (мобильные приложения, веб-приложения и т.д.) будут взаимодействовать с вашей системой через единый входной точки. Swagger поможет вам создать четкую документацию, которая упростит интеграцию с вашим API Gateway.

Пример выполнения - https://stealth-force-e00.notion.site/289383d7b8b3424f911c04b25d722c80?pvs=4

__

Задача Swagger - упростить процесс описания и документирования вашего API, а также предоставить средства для тестирования API непосредственно из документации.