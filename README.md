![Github Actions](https://github.com/oskardudycz/EventSourcing.NetCore/actions/workflows/build.dotnet.yml/badge.svg?branch=main) [![Github Sponsors](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&link=https://github.com/sponsors/oskardudycz/)](https://github.com/sponsors/oskardudycz/) [![blog](https://img.shields.io/badge/blog-event--driven.io-brightgreen)](https://event-driven.io/?utm_source=event_sourcing_net) [![blog](https://img.shields.io/badge/%F0%9F%9A%80-Architecture%20Weekly-important)](https://www.architecture-weekly.com/?utm_source=event_sourcing_net)  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/oskardudycz/) 

# Messaging and EDA

## General

* [Jay Kreps - The Log: What every software engineer should know about real-time data's unifying abstraction](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying)
* [Delivering Billions of Messages Exactly Once by Segment](https://segment.com/blog/exactly-once-delivery/)
* [Gregor Hohpe - Starbucks Does Not Use Two-Phase Commit](http://www.enterpriseintegrationpatterns.com/ramblings/18_starbucks.html) - explanation of events compensation
* [Marc de Graauw - Nobody Needs Reliable Messaging](https://www.infoq.com/articles/no-reliable-messaging)
* [David Boike - Putting your events on a diet](https://particular.net/blog/putting-your-events-on-a-diet)
* [Martin Fowler - The Many Meanings of Event-Driven Architecture](https://www.youtube.com/watch?v=STKCRSUsyP0&t=822s)

## Architectures
* [Lambda Architecture](http://lambda-architecture.net/)
* [Questioning the Lambda Architecture](https://www.oreilly.com/ideas/questioning-the-lambda-architecture)
* [Pat Helland - Life beyond Distributed Transactions: an Apostate’s Opinion](http://adrianmarriott.net/logosroot/papers/LifeBeyondTxns.pdf)
* [Jimmy Bogard - Life Beyond Distributed Transactions: An Apostate's Implementation](https://www.youtube.com/watch?v=AUrKofVRHV4)
* [Derek Comartin - Event-Driven Architecture: I do not think it means what you think it means](https://www.youtube.com/watch?v=iAA7PTqs4xY)

## Stream Processing, Event Driven architecture
* [Martin Klepmann - Event sourcing and stream processing at scale](https://martin.kleppmann.com/2016/01/29/event-sourcing-stream-processing-at-ddd-europe.html)
* [Jonas Bonér - Designing Events-First Microservices](https://www.youtube.com/watch?v=1hwuWmMNT4c)
* [Jay Kreps - Why local state is a fundamental primitive in stream processing](https://www.oreilly.com/ideas/why-local-state-is-a-fundamental-primitive-in-stream-processing)
* [Simon Green - Microservices, Containers & Event-Driven Architecture: Key Integration Factors](https://www.redhat.com/en/about/videos/microservices-containers-event-driven-architecture)
* [Jakub Pilimon - Event-Driven Architecture Traps](https://www.youtube.com/watch?v=5_fFmVwqaVY)
* [Martin Kleppmann, Alastair R. Beresford, and Boerge Svingen - Online Event Processing. Achieving consistency where distributed transactions have failed](https://queue.acm.org/detail.cfm?id=3321612)
* [Thomas Pierrain - As Time Goes By… (a Bi-temporal Event Sourcing story)](https://m.youtube.com/watch?v=xzekp1RuZbM)
* [Martin Fowler - What do you mean by “Event-Driven”?](https://martinfowler.com/articles/201701-event-driven.html)
* [Bernd Ruecker - Complex Event Flows in Distributed Systems](https://www.youtube.com/watch?v=g1z520X-dgU)
* [James Hood - Building Event-Driven Serverless Apps with AWS Event Fork Pipelines](https://pages.awscloud.com/Building-Event-Driven-Serverless-Apps-with-AWS-Event-Fork-Pipelines_2019_0509-SRV_OD.html?utm_source=newsletter&utm_medium=email&utm_content=offbynone&utm_campaign=Off-by-none%3A%20Issue%20%2339)
* [Michiel Overeem - Event Sourcing after launch](https://www.youtube.com/watch?v=JzWJI8kW2kc)
* [Kevin Webber - Full Stack Reactive In Practice](https://www.youtube.com/watch?v=ygVuPuxrRIo) with [samples](https://github.com/RedElastic/reactive-stock-trader)

## Serverless
- [Julian Wood, Chris Greenwood - AWS re:Invent 2022 - A closer look at AWS Lambda](https://www.youtube.com/watch?v=0_jfH6qijVY)
- [Yan Cui - Choreography vs Orchestration in the land of serverless](https://theburningmonk.com/2020/08/choreography-vs-orchestration-in-the-land-of-serverless/)
- [Yan Cui - Are Lambda-to-Lambda calls really so bad?](https://theburningmonk.com/2020/07/are-lambda-to-lambda-calls-really-so-bad/)

## AWS
- [Eric Johnson - AWS re:Invent 2022 - Building next-gen applications with event-driven architectures](https://www.youtube.com/watch?v=SbL3a9YOW7s&list=PL2yQDdvlhXf_lYR5Ntvr9V5iVYv5rcbNc)
- [Be A Better Dev - Event Driven Architectures vs Workflows (with AWS Services!)](https://www.youtube.com/watch?v=Q_QCu6OP2mQ)
- [Be A Better Dev - AWS SQS vs SNS vs EventBridge - When to Use What?](https://www.youtube.com/watch?v=RoKAEzdcr7k)
- [Serverlessland - Introduction to Event Driven Architecture](https://serverlessland.com/event-driven-architecture)
- [Durgadas Kamath - Event-Driven Messaging Made Easy with Amazon SQS, SNS, and EventBridge](https://towardsaws.com/event-driven-messaging-made-easy-with-amazon-sqs-sns-and-eventbridge-122ab47ef91b)
- [James Beswick - AWS re:Invent 2022 - Building Serverlesspresso: Creating event-driven architectures](https://www.youtube.com/watch?v=qs0U0LdNkV0)

### SQS
* [Miia Niemelä - Lessons learned from combining SQS and Lambda in a data project](https://data.solita.fi/lessons-learned-from-combining-sqs-and-lambda-in-a-data-project/)

#### SQS FIFO
* [Kevin Sookocheff - Dissecting SQS FIFO Queues — Does Ordered and Exactly Once Messaging Really Exist?](https://sookocheff.com/post/messaging/dissecting-sqs-fifo-queues/)
* [Tom Gregory - 3 surprising facts about AWS SQS FIFO queues](https://tomgregory.com/3-surprising-facts-about-aws-sqs-fifo-queues/)

### SNS
- [AWS - Building event-driven architectures with Amazon SNS FIFO](https://aws.amazon.com/blogs/compute/building-event-driven-architectures-with-amazon-sns-fifo/)

### SQS + SNS
* [Sandro Volpicella - AWS SNS vs. SQS - What Are the Main Differences?](https://blog.serverlessq.com/aws-sns-vs-sqs-what-are-the-main-differences)
* [Tara Van Unen - Building Loosely Coupled, Scalable, C# Applications with Amazon SQS and Amazon SNS](https://aws.amazon.com/blogs/compute/building-loosely-coupled-scalable-c-applications-with-amazon-sqs-and-amazon-sns/)
- [Jeremy Daly - How To: Use SNS and SQS to Distribute and Throttle Events](https://www.jeremydaly.com/how-to-use-sns-and-sqs-to-distribute-and-throttle-events/)

### Dead Letter Queues
- [AWS - Amazon SNS dead-letter queues (DLQs)](https://docs.aws.amazon.com/sns/latest/dg/sns-dead-letter-queues.html)
- [PicnicError - SQS vs SNS for Lambda Dead Letter Queues](https://picnicerror.net/development/sqs-vs-sns-for-lambda-dead-letter-queues-2018-03-02/)

### AWS Fargate
- [Fargate vs Lambda: The Battle of the Future](https://www.clickittech.com/devops/fargate-vs-lambda/)

### Event Bridge
- [AWS - Deep Dive on Amazon EventBridge](https://www.youtube.com/watch?v=28B4L1fnnGM)

## Kafka
* [Jay Kreps - Putting Apache Kafka to Use for Event Streams](https://www.youtube.com/watch?v=el-SqcZLZlI)
* [Matthias J. Sax - Introducing Exactly Once Semantics in Apache Kafka](https://www.youtube.com/watch?v=Wo9jlaz8h0k)
* [Kafka Clients (At-Most-Once, At-Least-Once, Exactly-Once, and Avro Client)](https://medium.com/@ajmalbabu/kafka-0-9-0-clients-db1f43257d30)
* [Enabling Exactly-Once in Kafka Streams](https://www.confluent.io/blog/enabling-exactly-kafka-streams/)
* [ASP.Net Core Streaming Application Using Kafka – Part 1](https://dotnetcorecentral.com/blog/asp-net-core-streaming-application-using-kafka-part-1/)
* [Streaming data from PostgreSQL to Kafka using Debezium](https://medium.com/@tilakpatidar/streaming-data-from-postgresql-to-kafka-using-debezium-a14a2644906d)
* [Event Sourcing Using Apache Kafka](https://www.confluent.io/blog/event-sourcing-using-apache-kafka/)
* [Kafka Docker for development. Kafka, Zookeeper, Schema Registry, Kafka-Connect, Landoop Tools, 20+ connectors ](https://github.com/Landoop/fast-data-dev)
* [Understanding When to use RabbitMQ or Apache Kafka](https://content.pivotal.io/blog/understanding-when-to-use-rabbitmq-or-apache-kafka)
* [Kafka, GDPR and Event Sourcing](https://danlebrero.com/2018/04/11/kafka-gdpr-event-sourcing/)
* [Apache Kafka is not for Event Sourcing](https://medium.com/serialized-io/apache-kafka-is-not-for-event-sourcing-81735c3cf5c)
* [Gunnar Morling - Reliable Microservices Data Exchange With the Outbox Pattern](https://debezium.io/blog/2019/02/19/reliable-microservices-data-exchange-with-the-outbox-pattern/)
* [Vlad Mihalcea - How to extract change data events from MySQL to Kafka using Debezium](https://vladmihalcea.com/how-to-extract-change-data-events-from-mysql-to-kafka-using-debezium/)
* [Robin Moffatt - No More Silos: Integrating Databases and Apache Kafka](https://talks.rmoff.net/eGacLb/no-more-silos-integrating-databases-and-apache-kafka)
* [Emily Chang - Lessons learned from running Kafka at Datadog](https://www.datadoghq.com/blog/kafka-at-datadog/)
* [Anna Povzner, Scott Hendricks - 99th Percentile Latency at Scale with Apache Kafka](https://www.confluent.io/blog/configure-kafka-to-minimize-latency/)

## RabbitMQ
- [Erez Rabih - RabbitMQ Retries — The Full Story](https://engineering.nanit.com/rabbitmq-retries-the-full-story-ca4cc6c5b493)

## Kafka vs RabbitMQ
- [Eran Stiller - RabbitMQ vs. Kafka](https://medium.com/better-programming/rabbitmq-vs-kafka-1ef22a041793)
- [Eran Stiller - RabbitMQ vs. Kafka: Head-To-Head](https://medium.com/better-programming/rabbitmq-vs-kafka-1779b5b70c41)
* [RabbitMQ vs Kafka Part 1 - Two Different Takes on Messaging](https://jack-vanlightly.com/blog/2017/12/4/rabbitmq-vs-kafka-part-1-messaging-topologies)
- [Lovisa Johansson - When to use RabbitMQ or Apache Kafka](https://www.cloudamqp.com/blog/2019-12-12-when-to-use-rabbitmq-or-apache-kafka.html)

## NATS vs Kafka
- [Emil Koutanov - Contrasting NATS with Apache Kafka](https://itnext.io/contrasting-nats-with-apache-kafka-1d3bdb9aa767)
