# Event Source

An `EventSource` defines the configurations required to consume events from external sources like AWS SNS, SQS, GCP PubSub, Webhooks, etc. It further
transforms the events into the [cloudevents](https://github.com/cloudevents/spec) and dispatches them over to the eventbus.

Available event-sources:

1. AMQP
1. AWS SNS
1. AWS SQS
1. Azure Events Hub
1. BitBucket
1. BitBucet Server
1. Calendar
1. Emitter
1. File Based Events
1. GCP PubSub
1. Generic EventSource
1. GitHub
1. GitLab
1. HDFS
1. K8s Resources
1. Kafka
1. Minio
1. NATS
1. NetApp StorageGrid
1. MQTT
1. NSQ
1. Pulsar
1. Redis
1. Slack
1. Stripe
1. Webhooks

## Specification

The complete specification is available [here](https://github.com/argoproj/argo-events/blob/master/api/event-source.md).

## Examples

Examples are located under [examples/event-sources](https://github.com/argoproj/argo-events/tree/master/examples/event-sources).
