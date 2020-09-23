# Chapter 7. Transactions

[Chapter 7. Partitioning in O'reilly](https://learning.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/ch07.html)

## Notes
- Isolation
  - Snapshot isolation has the mantra readers never block writers, and writers never block readers
  - "_Testing for concurrency issues is hard, because they are usually non deterministic—problems only occur if you get unlucky with the timing._" 

- _"The examples in this chapter used a relational data model. However, as discussed in “The need for multi-object transactions”, transactions are a valuable database feature, no matter which data model is used."_