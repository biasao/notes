# Chapter 7. Event Sourcing, CQRS, and Other Stateful Patterns

[Chapter 7. Event Sourcing, CQRS, and Other Stateful Patterns](https://learning.oreilly.com/library/view/designing-event-driven-systems/9781492038252/ch07.html)

## Notes
- _"In contrast to an update-in-place persistence model like CRUD (create, read, update, delete), the validated order is represented as an entirely new event, being appended to the log rather than overwriting the existing order."_
- _"Event Sourcing ensures every state change in a system is recorded, much like a version control system. As the saying goes, “Accountants don’t use erasers.”"_
- _"One side effect of the previous example is that the application of Event Sourcing means the event, not the database record, is the source of truth."_
- _"There is a close link between the query side of CQRS and a materialized view in a relational database"_
- _"So, in summary, the rule of thumb is record exactly what you receive, immutably."_
- _"Event Sourcing is about saving state using the exact same medium we use to communicate it, in a way that ensures that every change is recorded immutably"_
- _"Event Sourcing and CQRS make events first-class citizens"_