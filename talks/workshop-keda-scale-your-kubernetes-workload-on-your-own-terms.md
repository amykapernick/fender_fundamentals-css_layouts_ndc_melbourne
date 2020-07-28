---
tags: talks
layout: layouts/talk.html
title: 'Workshop: KEDA, Scale Your Kubernetes Workload on Your Own Terms'
link: https://ndcmelbourne.com/talk/workshop-keda-scale-your-kubernetes-workload-on-your-own-terms/
speakers: [emad-alashi]
day: 29 July
time: 13:30 - 17:00
venue: Room 1
---
Kubernetes is a powerful platform to host various kind of workloads, and these workloads vary in their need of scale. For that, Kubernetes has a built-in functionality to scale these workloads based on their resources consumption like CPU and memory.

However, there is no built-in way to scale workloads based on events that happen outside of the cluster; e.g. the length of a storage queue in the cloud.
KEDA came in to fill this gap with various built-in scalers that come with the package. You can also write your own scaler that responds to your own events and needs.

In this session we will understand what KEDA is, how it works, and how we can build our own scaler that scales our workloads to our own events and needs.