# Reliable, Scalable and Maintainable Applciations

### Summary

- Many applications are **data intensive** (as opposed to compute-intensive) which most of the problems lies in:
  - Amount of data
  - Complexity of data
  - Speed of data that is changing
- A typical data-intensive application standard building blocks consist of:
  - Storing data in another application such as **database** to retrieve it later
  - Storing data closer to requester such as **cache** to speed up read request and reduce expensive operations
  - Allow users to search or filter data by keywords which can be achieved by **search indexes**
  - Sending messages to another backend process, to be handled asynchronously using **stream processing** (event-loop)
  - Periodically prepare large volumn of data for analytics which includes stripping unwanted information and formatting it. **(batch-processing)**

#### Designing a data system?

Typically consist of 3 or more category; **databases,queues and caches**. As many tools for data storage and processing are optimized for a variety of different use case.
