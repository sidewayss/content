---
title: "WorkerNavigator: connection property"
short-title: connection
slug: Web/API/WorkerNavigator/connection
page-type: web-api-instance-property
browser-compat: api.WorkerNavigator.connection
---

{{APIRef("Network Information API")}}{{AvailableInWorkers("worker")}}

The **`connection`** read-only property of the {{domxref("WorkerNavigator")}} interface returns a {{domxref("NetworkInformation")}} object containing information about the system's connection, such as the current bandwidth of the user's device or whether the connection is metered.
This could be used to select high definition content or low definition content based on the user's connection.

## Value

A {{domxref("NetworkInformation")}} object.

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- [Online and offline events](/en-US/docs/Web/API/Navigator/onLine)
- [Network Information API](/en-US/docs/Web/API/Network_Information_API)
