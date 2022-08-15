---
typora-root-url: ../

layout: post
title: "Job Interview Checklist"
author: "Vadym Bartko"
tags: job
hidden: true

excerpt_separator: <!--more-->
---

# Goals
* full remote
* USA/Europe
* interesting companies
* плюшки
* опыт прохождения собеседований - relocation

# Python

## General
* naming conventions
* PIP8  - code style
* type annotations

## Tools
* poetry
* pipenv
* Celery
* mypy - type checker <https://mypy.readthedocs.io/en/stable/>
* pylint
* flake8

## Libraries
* FastAPI
* Flask
* SQLAlchemy
* boto3
* Python Eve
* joblib
* pytest
* unittest
* DRF
* SQLAlchemy vs DjangoORM

## Core

### Collections
* iterator protocol - iter and next, iterator, iterable, generator
* reduce and map
* set/dict/list comprehension
* generator and iterator - method based and class based (generator is iterator)
  *  <https://stackoverflow.com/questions/2776829/difference-between-pythons-generators-and-iterators>
  * <https://stackoverflow.com/questions/231767/what-does-the-yield-keyword-do>
  * send method <https://stackoverflow.com/questions/19302530/whats-the-purpose-of-send-function-on-python-generators>



### Concurrency
* concurrency
* concurrent package
* async
* ThreadLocal
* pipe
* queue
* pool
* Value
* Array
* condition objects - wait/notify
* ContextVar
* [How to Choose the Right Python Concurrency API](https://superfastpython.com/python-concurrency-choose-api/), <https://news.ycombinator.com/item?id=32408577>
* producer-consumer pattern

### Core  types
* enums
* dataclasses
* list/dicts/sets
* iterators
* strings
* raw strings, byte strings, unicode strings
* tuples

### Core classes, functions, packages
* stdlib
* ABC and @abstractmethod
* ContextManager - contextlib annotation and class-based 
* decorators - function based, class based  (class with \_\_call\_\_ method), @wrap from functools
* @property decorator (setter, getter, deleter)
* NamedTuple
* Path
* OrderedDict

### Other
* slots
* yeld
* memory management - garbage collector and reference counter
* pattern matching
* inheritance
* \_\_init\_\_ and  \_\_new\_\_
* magic methods
* singletone - module based, classic, Borg - <https://www.geeksforgeeks.org/singleton-pattern-in-python-a-complete-guide/>, metaclass
* \_\_call\_\_ method (callable)
* metaclasses
  * <https://stackoverflow.com/questions/100003/what-are-metaclasses-in-python>

* descriptors
* type annotations
* \_\_hash\_\_  and  \_\_eq\_\_
* yield and generators
* @staticmethod and @classmethod (factory methods - cls as arg)
* @property (setter and getter)
* global and nonlocal
* signals
* \_\_init\_\_.py file - regular and namespace package <https://stackoverflow.com/questions/37139786/is-init-py-not-required-for-packages-in-python-3-3>

# AWS

* design patterns
* design examples
* request-response tracing
* logs
* deployment
* Security Groups
* best practices

## Articles
* <https://aws.amazon.com/blogs/mt/monitoring-aws-lambda-errors-using-amazon-cloudwatch/>

## Services

* SQS
* DirectConnect
* Batch
* EventBridge
* SNS
* CloudWatch
   * task scheduling
* Step Functions
* Lambda
   * deployment
   * layers
   * docker image
   * limitations
   * SAM
   * scheduling via EventBridge
   * X-Ray tracking & monitoring
* Kinesis
* DynamoDB
* Redshift
* RDS
* ElasticCache
* CloudFront
* KMS
* Textract
* EFS
* IAM
* Redis
* VPC
* Fargate
* Lambda Insights monitoring
* ECR
   * vulnerabilities scanner

* EC2
* ECS and Fargate
   * scheduled tasks

* Aurora
* Backup
* Transfer Family
* Elastic Load Balancing <https://aws.amazon.com/elasticloadbalancing/features/?nc1=h_ls>
   * Application Load Balancer
   * Gateway Load Balancer
   * Network Load Balancer
   * Classic Load Balancer
* S3
  * signed url
  * TTL
  * lifecircle
  * cross account access
  * storage classes
  * policies
  * access points
  * batch operations
  * object locks
  * storage lens
  * inventory
  * storage class analysis
  * data querying - S3 Select, Athena, Redshift Spectrum
  * replication
  * Object Lambda for GET requests
  * S3 Trigger for Lambda
  * S3 and notifications

### Small Notes

<pre>
• AWS Migration Hub: AWS Migration Hub is a central repository that can be used
to keep track of a migration project
• AWS Application Discovery Service: AWS Application Discovery Service
automates the discovery and inventory tracking of different infrastructure
resources, such as servers, and any dependencies among them.
• AWS Migration Pattern Library: This is a collection of migration templates
and design patterns that can assist in the comparison of migration options and
alternatives
• CloudEndure Migration: CloudEndure Migration is a product offered by AWS that
simplifies cloud migration by automating many of the steps necessary to migrate to
the cloud.
• AWS Data Migration Service: This service can facilitate the migration of data from
your on-premises databases to the cloud, for example, into Amazon RDS	
</pre>



# Tools

* Docker
* GitLab CI (pipeline)
* helm
* git
  * merge, merge fast-forward, rebase, interactive rebase
* Postgres
* mySQL
* Terraform
* Redis
* PostgREST
* Postman + Newman (cli to run tests)
* Snowflake
* Memcached vs Redis
* Kubernetes - objects and concepts



## Databases

* normal forms
* sql vs nosql
* vertical vs horizontal scaling
* sharding
* transactions
* indexes
* secondary indexes
* JOINs
* SQL
* SELECT FOR UPDATE
* db locks
* database migrations - alembic, django, liquibase



# Other

* REST
* deploy to production  - flow, approaches etc
* JWT - access token, refresh token, flow
* system design
* HTTP/2
* SQL
* SOLID in depth
* Agile/SCRUM/Kanban
* design patterns - порождающие, структурные, поведенческие
* Алгоритмы и структуры данных
* Architectural, Enterprise and Design Patterns
* system design
* OSI levels
* clean code
* LeetCode
* Postman
* Graphene
* horizontal and vertical scaling
* database normal forms
* PMBOK
* Graphql
  * SQL to GraphQL <https://hasura.io/>
  * SQL to GraphQL <https://graphjin.com/>
* RPC - gRPC, REST, HATEOS, JSON-RPC, XML-RPC, SOAP
  * https://stackoverflow.com/questions/46145417/rest-vs-rpc-actual-purpose-differences
  * <https://stackoverflow.com/questions/15056878/rest-vs-json-rpc>
  * [REST? Возьмите тупой JSON-RPC](https://habr.com/ru/post/441854/)
  * <https://ru.wikipedia.org/wiki/XML-RPC>


# Other-other

* write code without IDE

# Books
* Clean Code
* AWS WebServices in Action
* AWS for Solution Architects
* PMBOK
