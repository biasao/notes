# Chapter 5. Replication

[Chapter 5. Replication in O'reilly](https://learning.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/ch05.html)

## Notes

### Quorums for reading and writing
The quorum condition, w + r > n, allows the system to tolerate unavailable nodesas follows:
- If w < n, we can still process writes if a node is unavailable.
- If r < n, we can still process reads if a node is unavailable.
- With n = 3, w = 2, r = 2 we can tolerate one unavailable node.
- With n = 5, w = 3, r = 3 we can tolerate two unavailable nodes.
- Normally, reads and writes are always sent to all n replicas in parallel. The parameters w andr determine how many nodes we wait for