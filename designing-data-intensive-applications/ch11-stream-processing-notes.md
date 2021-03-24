# Chapter 11. Stream Processing

[Chapter 11. Stream Processing at O'reilly](https://learning.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/ch11.html)

## Notes
- key take away :) ->
_"Truly deleting data is surprisingly hard... Deletion is more a matter of “making it harder to retrieve the data” than actually “making it impossible to retrieve the data.” "_

- Processing stream
_"The one crucial difference to batch jobs is that a stream never ends"_

- Analytics streaming
  - Azure Stream Analytics?

- Reasonig about time:
  _"On the other hand, many stream processing frameworks use the local system clock on the processing machine (the processing time) to determine windowing [79]. This approach has the advantage of being simple, and it is reasonable if the delay between event creation and event processing is negligibly short. However, it breaks down if there is any significant processing lag—i.e., if the processing may happen noticeably later than the time at which the event actually occurred."_