# Kafka Stock market streaming project

## Overview
This project demonstrates how to use Apache Kafka to stream stock data from a CSV file using `pandas`. The producer reads the data from a CSV file and sends it to a Kafka topic named `stock-prices`, while the consumer reads the data from this topic.

## Prerequisites
Before you begin, ensure you have the following libraries installed:
- Apache Kafka
- Zookeeper (for Kafka)
- Python
- pandas
