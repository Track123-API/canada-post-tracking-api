# Canada Post Tracking Statuses with Track123

Track123 normalizes Canada Post shipment events into standard delivery statuses so your application can use one status model across carriers.

> Status names are Track123 normalized values. They are not a reproduction of Canada Post's own event taxonomy.

## Use standardized shipment statuses

Map carrier events to the Track123 delivery status and sub-status returned by the API. Typical progress includes information received, in transit, delivered, and exception states.

## Build customer-facing tracking

Use normalized statuses for order timelines, notification triggers, support workflows, and delivery-exception handling. Refer to the current status documentation rather than hard-coding carrier event text.

## Resources

- [Track123 delivery status reference](https://docs.track123.com/reference/package-status)
- [Track123 delivery sub-status reference](https://docs.track123.com/reference/package-status-copy)
- [Track Canada Post packages on Track123](https://www.track123.com/carriers/canada-post)
- [Back to Canada Post tracking API](README.md)
