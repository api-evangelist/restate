---
title: "Agent checkpointing is far from production-grade resiliency"
url: "https://restate.dev/blog/why-checkpointing-is-not-production-grade-durable-execution"
date: "2026-06-15"
author: "Giselle van Dongen"
feed_url: "https://restate.dev/blog/"
---
Many agent frameworks advertise durable execution through checkpointing, but checkpointing only helps with recovery, and agents are distributed applications that need more than that to be truly durable. The post argues that production-grade resilience requires a comprehensive durable execution runtime handling failure detection, retry policies, session management, and safe upgrades, far beyond what checkpoint-based solutions provide.
