---
tags: talks
layout: layouts/talk.html
title: 'Workshop: Observing and understanding distributed systems with OpenTelemetry'
link: https://ndcmelbourne.com/talk/observing-and-understanding-distributed-systems-with-opentelemetry/
speakers: [liz-fong-jones]
day: 29 July
time: 09:00 - 12:30
venue: Room 6
---
Modern systems architecture often splits functionality into microservices for adaptability and velocity. The challenge of managing infrastructure for microservices has led to the cloud native ecosystem, including Kubernetes, Envoy, gRPC, and other projects. Observability, including application performance management (APM), is an essential component of a cloud native stack. Without observability, application developers and operators cannot understand the behavior of their applications and ensure the reliability of those applications.


OpenTelemetry (the successor to OpenCensus and OpenTracing) is a standardized library and specification that collects distributed traces and metrics from instrumented services. By instrumenting once with OpenTelemetry, you can understand how data and events flow through your applications through a variety of different visualization backends.


Liz Fong-Jones walks you through how to instrument a distributed set of microservices for traceability using OpenTelemetry and how to analyze your service’s traces using open source software backends like Jaeger and Zipkin. You’ll be able to leverage the OpenTelemetry vendor-neutral flexibility to try out other tracing backends, including the hosted SaaS products Stackdriver and Honeycomb without recompiling. You’ll leave comfortable with implementing OpenTelemetry in your own applications and prepared to choose how to store and visualize traces.
