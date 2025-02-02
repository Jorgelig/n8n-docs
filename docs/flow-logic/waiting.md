---
title: Waiting
description: How to make your workflow execution wait.
contentType: howto
---

# Waiting

Waiting allows you to pause a workflow mid-execution, then resume where the workflow left off, with the same data. This is useful if you need to rate limit your calls to a service, or wait for an external event to complete. You can wait for a specified time period, or until a webhook is called.

Making a workflow wait uses the [Wait](/integrations/builtin/core-nodes/n8n-nodes-base.wait/) node. Refer to the node documentation for usage details.

n8n provides a workflow template with a basice example of [Rate limiting and waiting for external events](https://n8n.io/workflows/1749-rate-limiting-and-waiting-for-external-events/){:target=_blank .external-link}.
