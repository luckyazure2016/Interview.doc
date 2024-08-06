# project

**Task 1: Simple Node Js Application Deployment on Docker container**
**Description:**

- Create a Dockerfile for a simple Node.js application that listens on port 3000. The
Dockerfile should use a lightweight base image, install dependencies, copy the
application code, and specify the command to run the application.

**Deliverable: Dockerfile**


**Task 2: K8s App restrictions over network
Description:**

- my-app-deployment and cache-deployment deployed, and my-app-deployment
deployment exposed through a service named my-app-service . Create a
NetworkPolicy named my-app-network-policy to restrict incoming and outgoing traffic
to my-app-deployment pods with the following specifications:
- Allow incoming traffic only from pods within the same namespace.
- Allow incoming traffic from a specific pod with the label app=trusted
- Allow outgoing traffic to pods within the same namespace.
- Deny all other incoming and outgoing traffic.
- 
**Deliverable: All manifest files.**
