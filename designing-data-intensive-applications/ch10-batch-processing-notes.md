# Chapter 9. Consistency

[Chapter 9. Consistency at O'reilly](https://learning.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/ch09.html)

## Notes
- Linearizability
  - “behave as though there is only a single copy of the data,and all operations on it are atomic,”
  - "Linearizability is slow—and this is true all the time, not only during a network fault."
  - "It seems the answer isno: Attiya and Welch [47]prove that if you want linearizability, the response time of read and write requests is at leastproportional to the uncertainty of delays in the network."
- CAP
  - "At the time, many distributed databases focused on providing linearizable semantics on a cluster of machines with shared storage, and CAP encouraged database engineers to explore a wider design space of distributed shared-nothing systems, which were more suitable for implementing large-scale web services."