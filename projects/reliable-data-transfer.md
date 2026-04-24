---
layout: project
type: project
image: images/software-code.jpg
title: Reliable Data Transfer Protocol over UDP
permalink: projects/reliable-data-transfer
date: 2025-12-01
labels:
  - C
  - Networking
  - UDP
  - Wireshark
summary: Designed and implemented a custom reliable transmission protocol on top of UDP in C, with sequence numbers, ACKs, retransmissions, and FIN handling.
---

For this project, I designed and implemented a custom reliable data transfer protocol built on top of UDP using C. Since UDP is an unreliable transport protocol by nature, the goal was to replicate the reliability features of TCP from scratch.

The implementation included sequence numbers, acknowledgments (ACKs), retransmissions, timers, and FIN handling to guarantee reliable delivery even when packets are dropped or delayed. I used Wireshark to analyze packet behavior in real time, inspecting packet loss, retransmissions, and overall protocol correctness. Finally, I evaluated performance trade-offs by testing across different window sizes and simulated network delay conditions.
