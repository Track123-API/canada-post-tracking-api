# Canada Post Tracking API & Webhooks

Use Track123 to track Canada Post shipments through one unified shipment tracking API.

Track123 lets your application register Canada Post tracking numbers, retrieve tracking updates, and receive delivery events through webhooks.

- Canada Post carrier code: `canada-post`

- [Track Canada Post packages on Track123](https://www.track123.com/carriers/canada-post)

- [Canada Post API integration page](https://www.track123.com/carriers/canada-post/api)

- [Track123 API documentation](https://docs.track123.com)

> This repository explains how to track Canada Post shipments with Track123. It is not official Canada Post API documentation.

## Canada Post tracking API integration

When your application already knows that a shipment is handled by Canada Post, set `courierCode` to `canada-post` when registering the tracking number.

Use [Carrier Detection](https://docs.track123.com/reference/detection-courier) when your application does not have an approved carrier code.

Use your own tracking number in the registration request. Track123 does not provide public test tracking numbers in this repository.

## Integration guides

- [Canada Post tracking webhook](webhook.md)
- [Canada Post tracking statuses](tracking-status.md)
- [Canada Post API errors and rate limits](errors-and-rate-limits.md)

## Canada Post tracking API resources

- [Register package trackings](https://docs.track123.com/reference/register-package-trackings)
- [Get package trackings](https://docs.track123.com/reference/get-package-trackings)
- [Carrier detection](https://docs.track123.com/reference/detection-courier)

## Track Canada Post packages and view FAQs

For shipment lookup, carrier contact information, and customer-facing FAQs, visit [Canada Post tracking on Track123](https://www.track123.com/carriers/canada-post).

## More Track123 resources

- [All supported carriers](https://www.track123.com/carriers)
- [Track123 developer documentation](https://docs.track123.com)

Carrier names and websites are used only to identify compatible carriers. Track123 is not affiliated with or endorsed by Canada Post unless explicitly stated.
