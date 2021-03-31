# Chapter 5. Events: A Basis for Collaboration

[Chapter 5. Events: A Basis for Collaboration at O'reilly](https://learning.oreilly.com/library/view/designing-event-driven-systems/9781492038252/ch05.html)

## Notes
- _"In practice we tend to embrace this automatically. We’ve all found ourselves polling database tables for changes, or implementing some kind of scheduled cron job to churn through updates. These are simple ways to break the ties of synchronicity, but they always feel like a bit of a hack. There is a good reason for this: they probably are."_
- "streaming platforms(https://www.confluent.io/blog/event-streaming-platform-1)"
- _"The beauty of events is they wear two hats: a notification hat that triggers services into action, but also a replication hat that copies data from one service to another"_
- _"Loose coupling reduces the number of assumptions two parties make about one another when they exchange information."_
- _"Loose coupling lets components change independently of one another. Tight coupling lets components extract more value from one another."_
- _"Functional couplings are optional. Core data couplings are essential."_
- _"Communication between microservices needs to be based on asynchronous message passing (while logic inside each microservice is performed in a synchronous fashion)."_
- _"This might not sound too different from any other workflow, but what is special about Event Collaboration is that no single service owns the whole process; instead, each service owns a small part—some subset of state transitions—and these plug together through a chain of events"_