# Chapter 3. Is Kafka What You Think It Is?

[Chapter 3. Is Kafka What You Think It Is? at O'reilly](https://learning.oreilly.com/library/view/designing-event-driven-systems/9781492038252/ch03.html)

## Notes
- _"A broker is a separate piece of infrastructure that broadcasts messages to any programs that are interested in them, as well as storing them for as long as is needed. So it’s perfect for streaming or fire-and-forget messaging."_
- _"So Kafka is a mechanism for programs to exchange information, but its home ground is event-based communication, where events are business facts that have value to more than one service and are worth keeping around."_
- [Kafka is a streaming platform](https://www.confluent.io/blog/stream-data-platform-1/)
- "Kafka Streams and KSQL ... These APIs can be stateful, which means they can hold data tables much like a regular database"
- _"The difference is that ESBs focus on the integration of legacy and off-the-shelf systems, using an ephemeral and comparably low-throughput messaging layer, which encourages request-response protocols_
_... Kafka, however, is a streaming platform, and as such puts emphasis on high-throughput events and stream processing. A Kafka cluster is a distributed system at heart, providing high availability, storage, and linear scale-out_"
- _[event streaming as a source of truth](https://www.thoughtworks.com/radar/techniques/event-streaming-as-the-source-of-truth)_
- _"This is emphasized by the core mantra of event-driven services: Centralize an immutable stream of facts. Decentralize the freedom to act, adapt, and change."_
