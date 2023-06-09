# Elasticsearch
[Elasticsearch](https://www.elastic.co/elasticsearch/) — это распределенная поисковая и аналитическая система, которая лежит в основе Elastic Stack.

Elasticsearch обеспечивает поиск и аналитику практически в реальном времени для всех типов данных. Независимо от того, структурированный или неструктурированный текст, числовые данные или геопространственные данные, Elasticsearch может эффективно хранить и индексировать их таким образом, чтобы поддерживать быстрый поиск. Позволяет выйти далеко за рамки простого поиска данных и агрегировать информацию, чтобы обнаружить тенденции и закономерности в данных.

Elasticsearch используется для хранения, поиска и управления данными в области:
- Журналирования
- Метриках
- Серверной части поиска
- Мониторинга приложений
- Безопасности
- Прочее

Основные плюсы Elasticsearch
- **Скорость**. В Elasticsearch внедрены инвертированные индексы с преобразователями конечного состояния для полнотекстовых запросов, BKD-деревья для хранения числовых и географических данных и хранилище столбцов для аналитики. Так как всё проиндексировано, то и скорость доступа к данным высокая.
- **Масштабируемость**. Elasticsearch масштабируется по горизонтали, чтобы обрабатывать миллионы событий в секунду, при этом автоматически управляя тем, как индексы и запросы распределяются по кластеру для бесперебойной работы.
- **Релевантность**. В Elasticsearch реализована возможность ранжирования результатов поиска на основе множества факторов — от частоты или новизны термина до популярности и других факторов. Elasticsearch способен обрабатывать человеческие ошибки, включая достасточно сложные, такие, как опечатки.
- **Надежность**. Elasticsearch обнаруживает сбои, чтобы обеспечить безопасность и доступность кластера (и данных). При межкластерной репликации вторичный кластер может работать в режиме горячего резервного копирования. Elasticsearch работает в распределенной среде, разработанной с нуля.
- **Гибкость**. Elasticsearch позволяет сбалансировать производительность и стоимость. Можно хранить данные локально — для быстрых запросов или удаленно на недорогих решениях — остальные данные.

Elasticsearch использует стандартные API RESTful и JSON. Реализованы и поддерживаются клиенты для работы с Elasticsearch на языках: Java, Python, .NET, SQL и PHP.

Подключение Elasticsearch может осуществляться несколькими способами:
1. С использованием Elastic Cloud.
2. Установить в ОС.
3. Развернуть в Docker-контейнере.

Elasticsearch создан с использованием Java и включает версию OpenJDK в составе каждого дистрибутива. Связанная JVM является рекомендуемой JVM, но есть возможность её изменить.

Последняя версия Elasticsearch, на момент написания: 8.8.0 от 25 мая 2023.

Аналоги:
- [RediSearch](https://redis.io/docs/stack/search/)
- [Postgres FTS](https://www.postgresql.org/docs/15/textsearch.html)
- [TypeSense](https://typesense.org/)
- [MeiliSearch](https://www.meilisearch.com/)
- [Sphinx](http://sphinxsearch.com/)
- [Splunk](https://www.splunk.com/)
- [Solr](https://solr.apache.org/)
- [OpenSearch](https://opensearch.org/)


## Источники
1. [Elasticsearch Guide](https://www.elastic.co/guide/en/elasticsearch/reference/current/index.html)
2. [Сравнение эффективности поиска: Elasticsearch и конкуренты](https://habr.com/ru/articles/581394/)
3. [DB-Engines Ranking of Search Engines](https://db-engines.com/en/ranking/search+engine)
