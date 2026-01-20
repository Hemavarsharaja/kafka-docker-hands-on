# kafka-docker-hands-on
# Kafka Producer–Consumer CLI Demo using Docker

## 📌 Overview
This repository contains a hands-on demonstration of Apache Kafka where
two separate command prompts communicate with each other through a
producer–consumer pipeline.

Kafka is deployed using Docker, and messages are exchanged via Kafka topics
using command-line tools.

## 🛠 Technologies Used
- Apache Kafka
- Docker & Docker Compose
- Kafka CLI tools

## 🧪 What This Demo Shows
- Setting up Kafka using Docker
- Creating Kafka topics
- Running producer and consumer in separate terminals
- Real-time message exchange between terminals

## ⚙️ How It Works
1. Kafka broker runs inside Docker
2. One terminal acts as a producer
3. Another terminal acts as a consumer
4. Messages typed in producer appear instantly in consumer

## 🚀 How to Run
```bash
docker-compose up -d

**Start Consumer**
 kafka-console-consumer --topic test-topic --from-beginning --bootstrap-server localhost:9092

**Start Producer**
kafka-console-producer --topic test-topic --bootstrap-server localhost:9092

![Kafka Producer Terminal Output](https://github.com/user-attachments/assets/bfb2eb48-17bb-4331-9039-a2d1944ad86a)




