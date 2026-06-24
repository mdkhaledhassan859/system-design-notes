# CAP Theorem

A distributed system can only guarantee 2 of 3:

- Consistency: all nodes see same data
- Availability: system responds to requests
- Partition Tolerance: system works despite network failures

## Trade-off
In real systems, partition tolerance is required, so you choose between consistency and availability.
