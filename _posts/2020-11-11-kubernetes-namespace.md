---
layout: post
title: "Kubernetes Namespace"
date: 2020-11-11 23:34:33 +0900
categories: [DevOps, Kubernetes]
---

### Definition
- A **namespace** is a virtual cluster inside a cluster.

### Use Cases of Namespaces
1. Grouping applications by task (ex. database, nginx, frontend).
2. Resource sharing and multiple development stages (ex. dev, staging). In this case, replicate frontend but use the same nginx is also possible.
3. Access resource and resource limit in namespaces (see `What isolates Linux Containers to one another? 7 namespaces.` notes).

### Characteristics of Namespaces
1. Cannot access most resources from another namespace. If want to do so, must use **ConfigMap**.
2. But you can access through service! Specify resources you want to share.
3. There are some components that cannot be in a namespace like volumes.

### References
[Kubernetes Namespaces Explained in 15 mins | Kubernetes Tutorial 21](https://www.youtube.com/watch?v=K3jNo4z5Jx8)
