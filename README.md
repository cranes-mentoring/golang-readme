# golang-readme

Ниже приведён список рекомендуемых материалов и библиотек для самоподготовки.

---

## 1. Go

**Официальная документация:**
- [Go Official Docs](https://go.dev/doc/) – общий обзор языка, туториалы и руководства.  
- [Effective Go (ENG)](https://go.dev/doc/effective_go) – полезное руководство по стилю и идиоматическим приёмам.

**Учебники/руководства:**
- [Tour of Go](https://go.dev/tour/) – интерактивный курс, покрывающий основы Go (есть русская версия: [Tour of Go (RU)](https://go-tour-ru-ru.appspot.com/)).
- [Go By Example (ENG)](https://gobyexample.com/) – короткие примеры кода по ключевым механизмам (горутины, каналы, и т.д.).
- Книга «[Go. Разработка приложений](https://www.ozon.ru/context/detail/id/153277623/)» (Алекс Щукин) – хорошая книга на русском о практической разработке на Go.

**Статьи и видео по внутреннему устройству Go (шедулер, горутины):**
- [Inside the Go Scheduler (ENG)](https://morsmachine.dk/go-scheduler) – детальный разбор работы шедулера.
- [Goroutines and concurrency in Go (ENG)](https://blog.golang.org/concurrency-timeouts) – статьи в официальном блоге Go о работе с конкуренцией.

**Популярные библиотеки и пакеты:**
- [sync](https://pkg.go.dev/sync) (стандартная библиотека) – для мьютексов, условных переменных, waitgroup и т.д.
- [atomic](https://pkg.go.dev/sync/atomic) (стандартная библиотека) – атомарные операции.
- [context](https://pkg.go.dev/context) – важнейший пакет для управления временем жизни горутин.
- [map, slice](https://go.dev/blog/maps) – статья в блоге Go о правильной работе с коллекциями.

**Популярные книги:**
- «100 ошибок Go и как их избежать»

**Рекомендуемая статья:**
- [Какие грабли есть в Go и как их избежать (Habr)](https://habr.com/ru/companies/ru_mts/articles/761752/)

---

## 2. PostgreSQL

**Документация и руководства:**
- [PostgreSQL Official Docs (ENG)](https://www.postgresql.org/docs/) – официальная документация по СУБД.
- [Русскоязычная документация PostgreSQL](https://postgrespro.ru/docs/postgresql/) – перевод и адаптация Postgres Pro.

**Клиентские библиотеки для Go:**
- [pq](https://github.com/lib/pq) – «чистый» драйвер для работы с PostgreSQL.
- [pgx](https://github.com/jackc/pgx) – рекомендуемый драйвер, поддерживает пул соединений, доп. возможности и высокую производительность.

**Дополнительные материалы/статьи:**
- [Go и PostgreSQL: подробное руководство (ENG)](https://www.calhoun.io/using-postgresql-with-go/) – пример кода и объяснения.
- [Инструмент для миграций схемы БД](https://github.com/golang-migrate/migrate)
- [VACUUM (русская документация)](https://postgrespro.ru/docs/postgrespro/9.5/sql-vacuum)
- [Статья на Habr с видеоразбором](https://habr.com/ru/articles/501516/)

**Топ книги (бесплатные):**
- [Сборник книг на postgrespro.ru](https://postgrespro.ru/education/books)

---

## 3. Redis

**Документация:**
- [Redis Official Docs (ENG)](https://redis.io/documentation)

**Go-библиотеки:**
- [go-redis](https://github.com/redis/go-redis) – основная библиотека для работы с Redis.
- [redigo](https://github.com/gomodule/redigo) – более старый клиент, всё ещё актуальный в некоторых проектах.

**Ресурсы и статьи:**
- [Using Redis with Go (ENG)](https://www.digitalocean.com/community/tutorials/how-to-use-redis-with-go) – базовый пример.
- [go-redis Guide (ENG)](https://redis.uptrace.dev/) – документация и гайды по go-redis.

---

## 4. Memcached

**Документация:**
- [Memcached Official Docs (ENG)](https://memcached.org/)

**Go-клиенты:**
- [gomemcache](https://github.com/bradfitz/gomemcache) – основной клиент, автор – Brad Fitzpatrick (известный контрибьютор Go).

**Статьи:**
- [Using Memcached in Go (ENG)](https://www.calhoun.io/using-memcached-with-go/)
- [Caching in Golang using Memcached (ENG)](https://dev.to/franciscomendes10866/caching-in-golang-using-memcached-42pc)

---

## 5. MongoDB

**Документация:**
- [MongoDB Official Docs (ENG)](https://docs.mongodb.com/)

**Go-клиент:**
- [MongoDB Go Driver](https://github.com/mongodb/mongo-go-driver) – официальный драйвер.

**Обучение и статьи:**
- [Quick Start with Go & MongoDB (ENG)](https://www.mongodb.com/docs/drivers/go/current/quick-start/)
- [MongoDB University (ENG)](https://university.mongodb.com/) – бесплатные курсы по теории и практике.

---

## 6. Kafka

**Документация:**
- [Apache Kafka Official Docs (ENG)](https://kafka.apache.org/documentation/)

**Go-клиенты:**
- [IBM Sarama](https://github.com/IBM/sarama) - лучшая библиотека для работы с Kafka.
- [Confluent Kafka Golang](https://github.com/confluentinc/confluent-kafka-go) – от Confluent, основан на `librdkafka`.
- [Segmentio/kafka-go](https://github.com/segmentio/kafka-go) – популярный и простой в использовании.

**Статьи, гайды:**
- [Kafka Integration in Go (ENG)](https://medium.com/segmentio/kafka-in-go-36c0eaf3e07b)
- [Confluent Tutorials (ENG)](https://docs.confluent.io/platform/current/tutorials.html)
- [Подборка статей на Habr (RU)](https://habr.com/ru/companies/kuper/articles/738634/), [2](https://habr.com/ru/companies/slurm/articles/550934/), [3](https://habr.com/ru/companies/selectel/articles/757440/)
- [Видео 1 (YouTube)](https://www.youtube.com/watch?v=A_yUaPARv8U)
- [Видео 2 (YouTube)](https://www.youtube.com/watch?v=SqVfCyfCJqw)

**Книги:**
- *Kafka: The Definitive Guide: Real-Time Data and Stream Processing at Scale*
- *Apache Kafka. Потоковая обработка и анализ данных, 2-е издание* (Г. Шапира, Т. Палино)

---

## 7. OpenTelemetry (Otel)

**Документация:**
- [OpenTelemetry Docs (ENG)](https://opentelemetry.io/docs/)

**Go-библиотеки:**
- [opentelemetry-go](https://github.com/open-telemetry/opentelemetry-go) – основной SDK.
- [opentelemetry-go-contrib](https://github.com/open-telemetry/opentelemetry-go-contrib) – интеграции с HTTP, gRPC и т.д.

**Обучение и статьи:**
- [OpenTelemetry Getting Started (ENG)](https://opentelemetry.io/docs/instrumentation/go/)
- [Введение в OpenTelemetry (RU, Habr)](https://habr.com/ru/articles/555228/)

---

## 8. Логи

**Популярные библиотеки логирования в Go:**
- [logrus](https://github.com/sirupsen/logrus) – одна из первых популярных библиотек.
- [zap](https://github.com/uber-go/zap) – высокопроизводительная библиотека от Uber.
- [zerolog](https://github.com/rs/zerolog) – минималистичный и быстрый JSON-логгер.

**Статьи по логированию:**
- [Comparing Logrus and Zap (ENG)](https://medium.com/@sagarvaidyanathan/comparing-uber-go-zap-and-logrus-8a7122f6ad31)

**ELK/EFK Stack (Elastic, Fluentd, Kibana):**
- [Setting up ELK Stack (ENG)](https://www.elastic.co/guide/en/elastic-stack-get-started/current/get-started-elastic-stack.html)

---

## 9. Основные паттерны (в том числе Outbox)

**Книги и сайты**
- [Design Patterns](https://refactoring.guru/design-patterns)
- [A pattern language for microservices](https://microservices.io/patterns)

**Обзор паттернов проектирования:**
- [Go Patterns (ENG)](https://github.com/tmrts/go-patterns) – большой репозиторий-шпаргалка по паттернам в Go.
- [Go Design Patterns (ENG)](https://www.amazon.com/Go-Design-Patterns-Second-Mario-Castro-Contreras/dp/1788629810)

**Outbox-паттерн:**
- [Статья Мартина Фаулера (ENG)](https://martinfowler.com/articles/patterns-of-distributed-systems/outbox.html)
- [Implementing Outbox (RU, Habr)](https://habr.com/ru/articles/486590/)

---

## 10. gRPC

**Документация:**
- [Official gRPC Docs (ENG)](https://grpc.io/docs/)

**Go-гайды:**
- [gRPC Go Quickstart (ENG)](https://grpc.io/docs/languages/go/quickstart/)
- [Примеры кода (ENG)](https://github.com/grpc/grpc-go/tree/master/examples)

**Протобуф (Protocol Buffers):**
- [Protocol Buffers (ENG)](https://developers.google.com/protocol-buffers/docs/gotutorial)

---

## 11. NATS

**Документация:**
- [NATS Official Docs (ENG)](https://docs.nats.io/)

**Go-клиент:**
- [nats.go](https://github.com/nats-io/nats.go)

**Статьи/руководства:**
- [Introducing NATS for Go Developers (ENG)](https://dev.to/mchmarny/introducing-nats-for-go-developers-a8n)
- [NATS Patterns (ENG)](https://docs.nats.io/developing/patterns)

---

## 12. AI (TensorFlow)

**TensorFlow для Go:**
- [TensorFlow Go Docs (ENG)](https://www.tensorflow.org/install/lang_go)

**Альтернативы/библиотеки для ML на Go:**
- [Gorgonia](https://github.com/gorgonia/gorgonia)
- [gonum](https://github.com/gonum/gonum)

**Общие материалы:**
- [Go AI resources (ENG)](https://github.com/owainlewis/awesome-artificial-intelligence#go)
- [Модели TensorFlow для Go (RU, Хабр)](https://habr.com/ru/articles/312110/)

---

## 13. Тестирование

**Стандартный пакет `testing`:**
- [testing (Go Doc)](https://pkg.go.dev/testing)
- [Покрытие тестами (coverage)](https://go.dev/blog/cover)

**Фреймворки и библиотеки:**
- [Testify](https://github.com/stretchr/testify)
- [GoConvey](https://github.com/smartystreets/goconvey)
- [Ginkgo/Gomega](https://github.com/onsi/ginkgo)
- [uber-go/mock](https://github.com/uber-go/mock)

**Статьи:**
- [Writing Testable Go Code (ENG)](https://go.dev/doc/articles/testability)
- [A Tour of Go Testing (ENG)](https://blog.alexellis.io/golang-writing-unit-tests/)

---

## 14. Testcontainers

**Документация и репозитории:**
- [Testcontainers Go (ENG)](https://github.com/testcontainers/testcontainers-go) – позволяет поднимать контейнеры (Postgres, Redis, Kafka и т.д.) в тестах.

**Статьи/примеры:**
- [Testcontainers – документация (ENG)](https://www.testcontainers.org/) – общее описание и гайды (в основном для Java, но концепция та же).
- [Пример использования testcontainers-go (ENG)](https://dev.to/douglasmakey/integration-testing-with-testcontainers-go-4ljg)
- [Testcontainers (RU, Habr)](https://habr.com/ru/articles/558488/) – пример на Java, но полезен и для Go.
  

--- 

## 15. Web

**Пакет net/http:**
- HTTP сервер и клиент (Go Doc)(https://pkg.go.dev/net/http) – базовый пакет для создания HTTP серверов и клиентов.
Примеры:
- Простой HTTP сервер (GoDoc Example)(https://pkg.go.dev/net/http#example-Server) – пример создания простого HTTP сервера.

**Библиотека Fiber:**
-Fiber (GitHub)(https://github.com/gofiber/fiber) – высокопроизводительная веб-платформа для создания веб-приложений и API.
Примеры: Пример создания REST API с Fiber (GitHub)(https://github.com/gofiber/fiber/tree/master/examples/rest)

**Библиотека Gin:**
- Gin (GitHub)(https://github.com/gin-gonic/gin) – высокопроизводительный веб-фреймворк для Go.
Пример создания REST API с Gin (GitHub)(https://github.com/gin-gonic/gin/tree/master/examples)

**Библиотека Echo:**
- Echo (GitHub)(https://github.com/labstack/echo) – минималистичный и мощный веб-фреймворк.
Пример создания REST API с Echo (GitHub)(https://github.com/labstack/echo/tree/master/examples)

**Библиотека Gorilla Mux:**
- Gorilla Mux (GitHub)(https://github.com/gorilla/mux) – гибкая и мощная маршрутизация для веб-приложений.
Пример использования Gorilla Mux (GitHub)(https://github.com/gorilla/mux/tree/master/examples)

**Статьи:**
- Building a RESTful API with Go and Gin (ENG)(https://www.digitalocean.com/community/tutorials/how-to-build-a-restful-api-with-go-and-gin)
- Creating a REST API with Go and Gin (ENG)(https://medium.com/@saurabh47gupta/creating-a-rest-api-with-go-and-gin-gonic-499991991998)
