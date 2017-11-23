# CloudStax FireCamp on the AWS Cloud

This Quick Start deploys CloudStax FireCamp into an AWS Cloud configuration of your choice.

[FireCamp](https://github.com/cloudstax/firecamp/) is an open source platform to easily setup, manage and scale the stateful services. FireCamp Dockerizes the stateful services on AWS ECS (Elastic Container Service) and Docker Swarm. Kubernetes and Mesos will be supported in the future. FireCamp deeply integrates with the popular open source stateful services, such as Redis, Cassandra, MongoDB, Kafka, PostgreSQL, ElasticSearch, etc.

The customer could easily run any service with no management overhead on cloud. The node failure is handled automatically. When one node goes down, AWS Auto Scaling Group will start a new node. AWS ECS will automatically start the service container. FireCamp will attach the volume and update AWS Route53. There is no data copy involved during the failover.

The AWS CloudFormation templates included with the Quick Start automate the following:

- Deploying CloudStax FireCamp into a new VPC
- Deploying CloudStax FireCamp into an existing VPC
