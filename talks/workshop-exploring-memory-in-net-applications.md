---
tags: talks
layout: layouts/talk.html
title: 'Workshop: Exploring memory in .NET applications'
link: https://ndcmelbourne.com/talk/workshop-exploring-memory-in-net-applications/
speakers: [adam-furmanek]
day: 30 July
time: 13:30 - 17:00
venue: Room 1
---
.NET provides a safe type system which saves us from most memory problems we had in native applications. However, it still exposes API to manipulate the memory directly which we can use to increase performance in some scenarios where speed is critical. In this workshop we will understand memory structure and what can be done beyond reference and value types. We will see how to allocate reference type on the stack, how to implement list faster than the provided List of T, how to serialize objects by reading their bytes directly, or how to hide them from GC.