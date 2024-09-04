# RabbitMQ Solution

This repository contains a .NET 8 solution with two console applications demonstrating how to work with RabbitMQ. 

## Projects

### ProducerApp

The `ProducerApp` project demonstrates how to send messages to a RabbitMQ queue. It connects to a local RabbitMQ server, declares a queue named "hello", and sends a "Hello RabbitMQ!" message to that queue.

### ConsumerApp

The `ConsumerApp` project demonstrates how to consume messages from a RabbitMQ queue. It connects to the same RabbitMQ server, listens to the "hello" queue, and prints any received messages to the console.

## Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- [RabbitMQ Server](https://www.rabbitmq.com/download.html)

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/mahmut-bilir/RabbitMQSolution.git
