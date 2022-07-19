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

## Tools
* poetry
* pipenv
* Celery

## Libraries
* FastAPI
* Flask
* SQLAlchemy
* boto3

## Core

### Collections
* iterator protocol - iter and next
* reduce and map
* set/dict/list comprehension
* generator and iterator - method based and class based


### Concurrency
* concurrency
* async
* ThreadLocal
* ContextVar

### Core  types
* enums
* dataclasses
* list/dicts
* iterators
* strings
* raw strings, byte strings, unicode strings

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
* garbage collector
* pattern matching
* inheritance
* \_\_init\_\_ and  \_\_new\_\_
* magic methods
* singletone
* \_\_call\_\_ method
* metaclasses
* descriptors
* type annotations
* \_\_hash\_\_  and  \_\_eq\_\_
* yield and generators
* @staticmethod and @classmethod (factory methods - cls as arg)
* @property (setter and getter)
* locals and globals
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
* KMS
* Textract
* EFS
* IAM
* VPC
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
* GitLab CI
* git
  * merge, merge fast-forward, rebase, interactive rebase
* Postgres
* mySQL
* Terraform



# Other

* REST
* JWT - access token, refresh token, flow
* system design
* HTTP/2
* SQL
* SOLID
* Agile/SCRUM/Kanban
* design patterns
* Алгоритмы и структуры данных
* OSI levels
* clean code
* LeetCode



# Other-other

* write code without IDE

# Books
* Clean Code

