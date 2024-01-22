#Real-Time YouTube Analytics Streamed to Telegram
* This Python-based project aims to fetch real-time YouTube metrics like likes, views, comments, and favorites, and then streams this data via Kafka. Also, KSqlDB was used for stream processing and the processed data is then sent to a Telegram bot for real-time notifications.

System Architecture




Requirements
* Python 3.10 (minimum)
* Kafka
* Telegram API
* Docker
* Confluent Containers (Zookeeper, Kafka, Schema Registry, Connect, ksqlDB, Control Center)
