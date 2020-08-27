# Chapter 4. Encoding and Evolution

[Chapter 4. Encoding and Evolution in O'reilly](https://learning.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/ch04.html)

## Notes
- "_The difficulty of getting different organizations to agree on anything outweighs most other concerns._"

### Binary encoding
- "_For a small dataset, the gains are negligible, but once you get into the terabytes, the choice of data format can have a big impact._"
- Compression and fast to process -- no parsing. 
- Field tags are immutable

### Schema evolution
- Backward compatibility 
    - Newer code can read data that was written by older code.

- Forward compatibility
    - Older code can read data that was written by newer code.