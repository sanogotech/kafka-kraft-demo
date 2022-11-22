# kafka-kraft-demo
Sample kafka server configs for setting up a kafka cluster without zookeeper

##  Docs

- https://adityasridhar.com/posts/how-to-easily-install-kafka-without-zookeeper
- https://www.instaclustr.com/blog/apache-kafka-kraft-abandons-the-zookeeper-part-1-partitions-and-data-performance/
- https://cwiki.apache.org/confluence/display/KAFKA/KIP-833%3A+Mark+KRaft+as+Production+Ready


## KRAFT

```
For several years, we have been developing a new way to run Kafka with self-managed metadata. This new mode, called KRaft mode, addresses many urgent scalability and performance issues in Kafka. It also eliminates the need to run an Apache ZooKeeper cluster alongside every Kafka cluster. See KIP-500 for more details.

In Kafka 2.8, KRaft mode was released in early access. By Kafka 3.0, it was in preview.

This KIP proposes to:

Mark KRaft as production-ready for new clusters in the upcoming Kafka 3.3 release.
Deprecate ZooKeeper mode in the upcoming Kafka 3.4 release
Plan to remove ZooKeeper mode entirely in Kafka 4.0.

```
