# suitcase.mongo

This is a suitcase subpackage for inserting bluesky documents into MongoDB. It
contains two packages:

* `suitcase.mongo_normalized` --- This creates a Mongo Collection for each
  bluesky document type and has 1:1 correspondence between bluesky documents and
  Mongo documents. This is the layout that has been used in production at
  NSLS-II for several years.
* `suitcase.mongo_embedded` -- This is an experimental new layout under active
  development and benchmarking. It is not recommended for use in production yet.

## Installation

```
pip install suitcase-mongo
```
