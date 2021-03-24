# Chapter 4. Beyond Messaging: An Overview of the Kafka Broker

[Chapter 4. Beyond Messaging: An Overview of the Kafka Broker at O'reilly](https://learning.oreilly.com/library/view/designing-event-driven-systems/9781492038252/ch03.html)

## Notes
- _"Accordingly, its architecture inherits more from storage systems like HDFS, HBase, or Cassandra than it does from traditional messaging systems that implement JMS (Java Message Service) or AMQP (Advanced Message Queuing Protocol)."_
- _"The underlying abstraction is a [partitioned log](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying) — essentially a set of append-only files spread over a number of machines—which encourages sequential access patterns that naturally flow with the grain of the underlying hardware."_
- _"A Kafka cluster is a distributed system, spreading data over many machines both for fault tolerance and for linear scale-out"_
- - _" The first is that messages that require relative ordering need to be sent to the same partition. (Kafka provides ordering guarantees only within a partition.) This is managed for you: you supply the same key for all messages that require a relative order"_
- _"Kafka provides durability through replication."_
- _"This process actually works by assigning whole partitions to different consumers. A strength of this approach is that a single partition can only ever be assigned to a single service instance (consumer). This is an invariant, implying that ordering is guaranteed, even as services fail and restart."_
