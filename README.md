# Lab 3 Part 1 - Deploying using Google Kubernetes Engine

**Atharva Rajadhyaksha - 101041016**

## Contents
- `BinaryCalculatorWebapp/` — Maven Spring Boot Binary Calculator app (Add, OR, AND, Multiply) with Dockerfile and unit tests
- `BinaryCalculatorWebapp/k8s/` - Custom Kubernetes YAML files for deploying the Binary Calculator (Design task)
- `MySQL/` - Deployment and service YAML files for MySQL

## Deployment Summary
- GKE cluster `sofe3980u`, 3 nodes, zone `us-central1-a`
- MySQL deployed both imperatively (kubectl commands) and via YAML files
- Binary Calculator image built and pushed to Artifact Registry, deployed to GKE, exposed via LoadBalancer
- Design task: added OR, AND, Multiply operations; replaced imperative deployment with custom YAML files (`binarycalculator-deploy.yaml`, `binarycalculator-service.yaml`)
