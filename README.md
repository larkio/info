# Информация для HR

Здравствуйте!

Связаться со мной можно следующими способами:
 - *Telegram*: https://t.me/larkio — предпочтительный вариант, отвечаю оперативно практически 24/7;
 - *Gmail*: larkiowork@gmail.com — проверяю раз в сутки;
 - *Телефон*: +7-999-220-2081 — прошу предварительно согласовывать время звонка через мессенджеры, но можно использовать для оперативной связи.

Другими мессенджерами (WhatsApp и т.д.) не пользуюсь, просьба там не писать.


# Информация для PM / TL / собеседующего

Всю представленную информацию с радостью расскажу/дополню при необходимости. Текст ниже необязателен, но дает четкое представление об имеющихся опыте и навыках.

## Последний проект

Последние N лет разрабатывал и сопровождал программный компонент голосового взаимодействия с диалоговыми ассистентами и IVR-системами, обеспечивающий синтез и распознавание речи, управление исходящими оповещениями и обработку входящих вызовов. По своей сути решение представляло собой комплексный распределенный монолит с возможностью гибкого планирования звонков, предоставляющее подмножество побочных функций (синтез речи, распознавание речи, хранение медиа-данных, управление ролями/доступами и т.п. функции). ПО on-premise, не cloud. ПО довольно сложное, технический "онбоардинг" проходит около 8-10 месяцев. В разработке часто приходилось сталкиваться с низкоуровневым взаимодействием (анализ дампов wireshark'а), разработкой и починкой сложных и нагруженных многопоточных модулей (миллионы строк логов на трейсе, тред-хип дампы, гонки, изоляции транзакций — проще сказать, чего не было), созданием собственных библиотек, модулей для тестирования (функциональное, нагрузочное), кэшей (самописных и существующих). Из-за специфической философии команды, работавшей над проектом до нынешней (и до моего устройства на работу), в продукте было принято очень много спорных проприетарных-велосипедных решений, из-за чего параллельно разработке тратились огромные ресурсы на рефакторинг. Свои плоды дало и закалило. Наверное, это всё ещё не кровавый, но явно серьёзный энтерпрайз.

## Технологический стек

**Жирным выделил то, с чем работал много**, *курсивом то, с чем поменьше или редко*:

 - Языки: **Java 8**, **Java 21**, *Kotlin*, *Groovy*. Большую часть времени провел на 8, переводил проект на 21-ую, в последнее время работал с ней. Котлин/груви используются в функциональных тестах (Write in Java, press "Kotlinize" in IDEA), но искренне не люблю их. 
 - DI: **Google Guice** + **Spring**. Изначально был только гусь, но совместными усилиями добавили спринг. "Задушить гуся" полностью не получилось, к сожалению.
 - ORM: **Hibernate**, **Spring Data Jpa**. Работ с БД было много. Было море любви и ненависти, был рефакторинг (n+1)^x запросов на вывод DTO для FE, было жонглирование уровнями изоляции в запросах, был даже динамический маппинг таблиц на интерфейсы. Писал и нативные запросы (в том числе и сложные для отчетов), и HQL, но большую часть времени была Criteria API.
 - RDB: **Postgres**, **Oracle**, **H2**, *MySQL*.
 - NoSQL DB: *Redis*, *Mongo*.
 - Build: **Maven**, *Gradle*.
 - Messaging: **REST**, **Websocket**, **gRPC**, *rabbitMQ*. С кроликом работы велась не с AMQP, но через самописный модуль.
 - Tests: **JUnit 4/5**, **Mockito**, **JMeter**, *TestNG*.
 - DevOops: **Linux** (Centos/Alma/RedOS) + **TeamCity** + **GitLab** + **Docker**. Скорее пользователь, чем создатель, но в рамках компетенций разработчика справляюсь успешно.
 - Infrastructure: **Jira**, **Confluence**, **Git** + **Git LFS**, **Kibana**, **Swagger**, **Prometheus** + **Grafana**.
 - Интересное: **Spring Reactor**, **Apache NiFi**, **Asterisk**, **ChatGPT** + **Cursor IDE**.

## Чего нет

Быстро учусь, многие технологии пробовал в "Hello-world"-проектах, но коммерческого опыта со следующими технологиями нет:

 - Kafka, AMQP, GraphQL, Spark.
 - Spring JDBC, Jooq, Jinq, QueryDSL.
 - Spring Security.
 - ElasticSearch, Cassandra.
 - Jenkins, Kubernetes.
 - GraalVM, Quarkus.

С каждой из вышеперечисленных технологий очень хотел бы поработать.

## О себе

Знаю все анекдоты категории Б. Хожу в качалку, хожу в книжный клуб. Иногда играю в CS и покер (не лудоман). Являюсь отцом прекрасного суккулента по имени Марк. Не потерял огня в глазах даже спустя 5 лет коммерческого опыта разработки. Буду рад влиться в коллектив целеустремленных и активных людей.
