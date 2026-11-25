# Kubernetes Nginx Lab

## Project Description

This project demonstrates how to deploy and manage Nginx in a local Kubernetes cluster using kind.

## Technologies

- Linux (Ubuntu Server)

- Docker

- Kubernetes

- kubectl

- kind

- Nginx

- YAML

## Features

- Deployment with 3 Nginx replicas

- CPU and memory requests and limits

- Rolling updates

- Pod monitoring with Metrics Server

- Application logs and troubleshooting

## Resource Configuration

- CPU Request: 50m

- CPU Limit: 200m

- Memory Request: 32Mi

- Memory Limit: 128Mi

## Deployment

Apply the Kubernetes manifest:

    kubectl apply -f deployment.yaml

Check the deployment:

    kubectl get deployments
    kubectl get pods

## Monitoring

Check resource usage:

    kubectl top nodes
    kubectl top pods

View application logs:

    kubectl logs deployment/nginx-demo

## Troubleshooting

During this lab, I practiced:

- Checking Pod status and restart counts

- Reading Kubernetes events

- Investigating container termination reasons

- Testing HTTP responses with curl

- Finding HTTP 200 and 404 responses in Nginx logs

## Project Goal

- Practice Kubernetes deployment, monitoring, resource management, and troubleshooting as part of my Junior DevOps training.
