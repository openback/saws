# chainsaws
Power tools for Amazon Web Services

## Purpose

Provides abstraction layer for core AWS application services such as DynamoDB, SNS, and SQS so that your microservices
don't end up tightly coupled to the platform. Helps immensely with testability and other concerns related to maintaining
a so-called hexagonal architecture. <http://alistair.cockburn.us/Hexagonal+architecture>