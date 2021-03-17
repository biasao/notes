# Chapter 1. Setting the Stage

[Chapter 1. Setting the Stage in O'reilly](https://learning.oreilly.com/library/view/designing-event-driven-systems/9781492038252/ch01.html)

## Notes
-  _"So applications became platforms, and building platforms is hard._
    _LinkedIn felt this pain as it evolved away from its original, monolithic Java application into 800–1,100 services. Complex dependencies led to instability, versioning issues caused painful lockstep releases, and early on, it wasn’t clear that the new architecture was actually an improvement."_
- _"One difference in the way LinkedIn evolved its approach was its use of a messaging system built in-house: Kafka. Kafka added an asynchronous publish-subscribe model to the architecture that enabled trillions of messages a day to be transported around the organization. This was important for a company in hypergrowth, as it allowed new applications to be plugged in without disturbing the fragile web of synchronous interactions that drove the frontend."_
- _"But a replayable log provides a far more suitable place to hold this kind of data because (somewhat counterintuitively) you can’t query it!"_