
# Distributed Microservice Cache Manager

The Distributed Microservice Cache Manager is a microservice that provides a centralized cache management system that can be used by other microservices to store and retrieve frequently used data. It uses caching technologies like Redis, Memcached, or Hazelcast to cache data, and is built using a REST API that allows other microservices to access it.

## Features

* REST API for storing and retrieving data from the cache
* Support for caching technologies like Redis, Memcached, or Hazelcast
* Cache eviction policies like Least Recently Used (LRU) or Least Frequently Used (LFU)
* Support for cache synchronization across multiple instances of the service
* Containerized using Docker and deployable on Kubernetes

## Getting Started
### Prerequisites
* Docker
* Kubernetes (optional)
* Installation
* Clone the repository:
```bash
git clone https://github.com/Addax101/Distributed-microservice-cache-manager.git```
