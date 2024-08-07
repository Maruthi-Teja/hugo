+++
title = 'Apache Kafka Use Cases: When To Use It? When Not To?'
date = 2024-06-20T08:36:55+05:30
draft = false

+++


What is Apache Kafka?
Apache Kafka is an open-source streaming data platform originally developed by LinkedIn.

Kafka operates like a traditional pub-sub message queue, such as RabbitMQ, in that it enables you to publish and subscribe to streams of messages.  But it differs from traditional message queues in 3 key ways:

Kafka operates as a modern distributed system that runs as a cluster and can scale to handle any number of applications. 
Kafka is designed to serve as a storage system and can store data as long as necessary; most message queues remove messages immediately after the consumer confirms receipt.
Kafka handles stream processing, computing derived streams and datasets dynamically, rather than just passing batches of messages.

What is Kafka used for?
Kafka can be used in asynchronous processing.It is used in the usecases like update profile where we submit the request for update and in the backend it will process the updates and we don't wait for the request response.
