netty-kafka-fail
================

Toy repo to show the dependency graph of `com.linkedin.kafka:kafka_2.12:2.4.1.3`

Steps to reproduce: `$ ./gradlew build -is --scan`

...then follow steps to explore build-scan on public scans.gradle.com.

Note that `zookeeper:3.5.8` depends on `netty-handler:4.1.48.Final`, which has a known security vulnerability. 

One example: https://scans.gradle.com/s/3wmsraql6s6ds/dependencies?configurationFilter=WyJjb21waWxlQ2xhc3NwYXRoIl0&dependencies=netty&expandAll&focusedDependency=WzAsMSw0NSxbMCwwLFswXV1d&focusedDependencyView=versions