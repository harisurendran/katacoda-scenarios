# Ace your CKAD examination.

This Question bank presents a sereies of scenarios that you can use to build your skills in Kubernetes.

This course assume you have understood the basics of Kubernetes and ready to work on exercises. 

Run > launch.sh


Deployment
* Scaling
* management
  


  What happens when one or more containers go down?

  How to manage containers in production
  How about networking
  How to avoid sinblepoint of failures
  update containers without bringing down the applications
  Robust networking and persistent storage options.
  Everything after we package an app.

  Conductor of your production orchestra.



  * Service discovery/load balancing
  * Storage orchestration
  * Automate rollouts/rollbacks
  * Self-healing
  * secret and confiugration management
  * Horizontal scale


Container and cluster management


## Declarative way of managing

Current state --> desired state

## Building blocks

## Cluster, Nodes and pods

Node is a machine,a virtual machine. 

Pod is similar to a box of a product. A very apt comparison is with a space suit. Communication, health status etc.

# Master and worker nodes

## Architecture

* API server
* controller manager
* scheduler
* store
* kubectl - command line tool


# Benefits and use cases

## Why do we need containers?

* Accelerate developer onboarding
* Eliminate app conflicts
* Environement consistency
* ship software fast


## Key kubernetes benefits

* orchestrate containers
*  zero runtime deployments
*  self healing
*  scale containers

## Why developers needs to learn

* emulate production locally
* move from docker compose to kubernetes
* Create end-to-end testing
* Ensure application scales properly
* Ensure secrets/configs are working properly
* Workload scenarios cicd is good
* leverage deployment options such as blue/green
*  Help devops to troubleshoot


## Running locally

* minikube
* docker desktop