# scdf-cp-monitoring
Docker-compose example on Spring Cloud Data Flow and Confluent Platform (with Prometheus and Grafana monitoring)

Derived from the following resources:

1. [Getting Started with Spring Cloud Data Flow and Confluent Cloud](https://www.confluent.io/blog/apache-kafka-spring-cloud-data-flow-tutorial/)
2. [`cp-all-in-one` repository](https://github.com/confluentinc/cp-all-in-one)
3. [`spring-cloud-dataflow` repository](https://github.com/spring-cloud/spring-cloud-dataflow)
4. [Spring Cloud Data Flow - Installating by Using Docker Compose](https://dataflow.spring.io/docs/installation/local/docker/)
5. [Spring Cloud Data Flow - Prometheus & Grafana](https://dataflow.spring.io/docs/installation/local/docker-customize/#prometheus--grafana)

To run:

```
export DATAFLOW_VERSION=2.9.2
export SKIPPER_VERSION=2.8.2
docker-compose -f docker-compose.yml -f docker-compose-prometheus.yml up -d`
```

To tear-down:

```
docker-compose -f docker-compose.yml -f docker-compose-prometheus.yml down -v
```