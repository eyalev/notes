
# App Engine

## Incoming requests default timeout

- [2018-10-07]
  - 60 seconds


- https://cloud.google.com/appengine/docs/standard/python/how-requests-are-handled#quotas_and_limits

## Maximum services per project

- [2018-10-07]
  - Free: 5
  - Paid: 105

  
- https://cloud.google.com/appengine/docs/standard/python/an-overview-of-app-engine#limits

## Logs

### Viewing web console logs

#### Excluding log messages

- Move to "Advanced Log Filters" mode
- Add `NOT textPayload:(text-to-exclude)`

