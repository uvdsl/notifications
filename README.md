# Solid Notifications

This repository hosts the technical reports for Solid Notifications.

These reports are incubated by the [Solid Notifications Panel](https://github.com/solid/notifications-panel) for inclusion in the [Solid Technical Reports](https://solidproject.org/TR/) as part of the [W3C Solid Community Group](https://www.w3.org/community/solid/) (CG). The reports are within the scope of the [Notifications Panel Charter](https://github.com/solid/process/blob/main/notifications-panel-charter.md).

## Technical Reports

### Protocol
* Latest Published Version:
  * [Solid Notifications Protocol](https://solidproject.org/TR/notifications-protocol)
* Editors Draft:
  * [Solid Notifications Protocol](https://solid.github.io/notifications/protocol)

### Subscription Types

The Solid Notification Protocol makes it possible to define [subscription types](https://solid.github.io/notifications/protocol#subscription-types). An index of subscription types published by the CG is available at [Notification Subscription Types](https://solidproject.org/TR/notification-subscription-types).

The subscription types listed below are intended to be useful to application developers looking for existing
subscription types as well as to authors of new subscription types.

* Editors Drafts:
  * [EventSourceChannel2023](https://solid.github.io/notifications/eventsource-channel-2023)
  * [WebSocketChannel2023](https://solid.github.io/notifications/websocket-channel-2023)
  * [StreamingHTTPChannel2023](https://solid.github.io/notifications/streaming-http-channel-2023)
  * [LDNChannel2023](https://solid.github.io/notifications/ldn-channel-2023)

* Deprecated Editors Drafts:
  * [WebSocketSubscription2021](https://solid.github.io/notifications/websocket-subscription-2021)
  * [StreamingHTTPSubscription2021](https://solid.github.io/notifications/streaming-http-subscription-2021)
  * [EventSourceSubscription2021](https://solid.github.io/notifications/eventsource-subscription-2021)
  * [LinkedDataNotificationsSubscription2021](https://solid.github.io/notifications/linkeddatanotifications-subscription-2021)
  * [WebHookSubscription2021](https://github.com/solid/notifications/blob/main/webhook-subscription-2021.md)
  * [WebPushSubscription2022](https://solid.github.io/notifications/webpush-subscription-2022)

To add a new subscription type to the list, please create a PR including the name and the URL of the document describing the subscription type.





## Diagrams

### Mermaid

Sequence diagrams use [Mermaid](https://mermaid-js.github.io/mermaid/) as source syntax.
Github workflow generates them automatically before deplying github pages.
Any file ending with `.mmd` will be rendered into file ending with `.mmd.svg`.
For exmple `source-flow.mmd` results in `source-flow.mmd.svg` which can be referenced from the spec.

To preview diagrams locally following tools are available:

* [Mermaid Live Editor](https://mermaid-js.github.io/mermaid-live-editor/)
* [Docker image](https://hub.docker.com/r/matthewfeickert/mermaid-cli)
* [mermaid-cli](https://www.npmjs.com/package/@mermaid-js/mermaid-cli)
* [code editor extensions](https://github.com/mermaid-js/mermaid/blob/develop/docs/integrations.md#editor-plugins)

All `*.mmd.svg` files are ignored by git so they won't be commited to the repository.
