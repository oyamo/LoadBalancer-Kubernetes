# Load Balancer Kubernetes

Kubernetes is a container orchestration system that is used to manage containers. It is a system that is used to manage a cluster of containers. It is used to manage the deployment, scaling, and management of containerized applications. It is a system that is used to manage a cluster of containers. It is used to manage the deployment, scaling, and management of containerized applications.

## What is Load Balancer?
A load balancer is a device that distributes network or application traffic across a cluster of servers. Load balancers are used to increase capacity (concurrent users) and reliability of applications. They do this by spreading the workload across multiple servers. Load balancers are often used to improve the availability and performance of applications. They do this by distributing the workload across multiple servers. Load balancers are often used to improve the availability and performance of applications. They do this by distributing the workload across multiple servers.

## Setup

### Prerequisites
*Download and install [Docker](https://www.docker.com/products/docker-desktop) and [Kubernetes](https://kubernetes.io/docs/tasks/tools/install-kubectl/)*

## Creating containers
To create a container, run the following command:
```bash
docker build -t <container-name> .
```

## Running containers in docker
To run a container in docker, run the following command:
```bash
docker run -p <port>:<port> <container-name>
```

Note: The port number should be the same as the port number in the Dockerfile.

## Running containers in Kubernetes
To run a container in Kubernetes, run the following command:
```bash
kubectl apply -f <deployment-name>.yaml
```

## References
* [Kubernetes](https://kubernetes.io/docs/concepts/overview/what-is-kubernetes/)
