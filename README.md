# scdf-cp-monitoring
Docker-compose example on Spring Cloud Data Flow and Confluent Platform (with Prometheus and Grafana monitoring)

Derived from the following resources:

1. [`cp-all-in-one` repository](https://github.com/confluentinc/cp-all-in-one)
2. [`spring-cloud-dataflow` repository](https://github.com/spring-cloud/spring-cloud-dataflow)
3. [Spring Cloud Data Flow - Installating by Using Docker Compose](https://dataflow.spring.io/docs/installation/local/docker/)
4. [Spring Cloud Data Flow - Prometheus & Grafana](https://dataflow.spring.io/docs/installation/local/docker-customize/#prometheus--grafana)

To run:

`docker-compose -f docker-compose.yml -f docker-compose-prometheus.yml up -d`

To tear-down:

`docker-compose -f docker-compose.yml -f docker-compose-prometheus.yml down -v`