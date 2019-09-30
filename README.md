# **zookeeper**
___

### Description
___

This image runs the official [*Apache ZooKeeper*](https://zookeeper.apache.org/) on a Centos Linux distribution.

The *latest* tag of this image is build with the [latest stable](https://zookeeper.apache.org/releases.html) release of Apache ZooKeeper on Centos 7.

You can pull it with:

    docker pull comchangs/zookeeper


You can also find other images based on different Apache Hadoop releases, using a different tag in the following form:

    docker pull comchangs/zookeeper:[zookeeper-release]


For example, if you want Apache ZooKeeper release 3.4.8 you can pull the image with:

    docker pull comchangs/zookeeper:3.4.8

Run with Docker Compose:

    docker-compose -p comchangs up
