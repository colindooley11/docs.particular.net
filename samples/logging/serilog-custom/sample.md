---
title: Custom Serilog configuration
summary: Customizing Serilog usage by configuring Serilog targets and rules.
reviewed: 2018-09-14
component: Serilog
tags:
 - Logging
related:
 - nservicebus/logging
 - nservicebus/logging/serilog-tracing
---


This sample illustrates how to customize logging by configuring Serilog targets and rules.


### Configure Serilog

snippet: ConfigureSerilog


### Pass the configuration to NServiceBus

snippet: UseConfig


### Ensure logging is flushed on shutdown

snippet: Cleanup

