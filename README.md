# DevOps – Kubernetes y Minikube

Esta práctica tiene como objetivo familiarizarse con el uso, instalación y administración de Kubernetes utilizando Minikube como entorno de ejecución local.
Durante el desarrollo se aprenden los conceptos básicos de pods, deployments y services, así como los comandos esenciales para gestionar estos recursos.

## La práctica se divide en dos partes principales:

1. Instalación y exploración de Minikube: se realiza la configuración inicial, el uso del dashboard y la creación de un deployment de prueba.
2. Creación y despliegue de una aplicación PHP personalizada:
- Se construye una imagen Docker con un archivo Dockerfile.
- Se genera su deployment YAML.
- Se expone mediante un service tipo NodePort, accediendo finalmente a través del comando minikube service.
