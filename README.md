# Barbarian big data system

Barbarian is the world's best cloud-first, cloud-agnostic in-memory big data system founded on Apache Hadoop for enterprise-ready parallel distributed data processing at scale.

Read more at:
[https://barbarians.io/](https://barbarians.io)

Docs at:
[http://docs.barbarians.io/](http://docs.barbarians.io)

### About Barbarian

The Barbarian Data System is an in-memory, parallel, distributed (MPP) data warehousing engine designed to be deployed to Kubernetes clusters, offering Apache Hive for powerful and flexible SQL based analytics. Barbarian includes an integrated in-memory filesystem and can run in three modes of operation.
* As an in-memory, standalone data warehousing system
* As a data warehousing system backed by an external storage system like Amazon S3
* In a hybrid mode, where primary storage is the external storage system, with common paths mounted to the in-memory filesystem

Barbarian includes compelling features including Apache Hive LLAP and Tez, with transactional tables enabled by default. 

Barbarian's integrated Ignite in-memory distributed parallel filesystem is resilient to node failure with replication enabled by default.

Barbarian has no single points of failure.

Barbarian is offered with the [Apache v2.0](https://www.apache.org/licenses/LICENSE-2.0) software license.

### Installing Barbarian

Barbarian can be deployed to your Kubernetes cluster with just two commands:

```helm repo add barbarians http://charts.barbarians.io/barbarian```
```helm install barbarians/barbarian```

## Apache Hadoop

This repo contains the Barbarian Data System fork of the **Apache Hadoop** project.

## Releases

| Release | Notes |
| -- | -- |
| 0.1 | Prelease 1 |
| 0.2 | Barbarian Data System r2 |


