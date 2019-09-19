# fleeman-position-tracker
Consumes vehicle position reports from a queue. Stores them in-memory for testing.

Note: the implementation of a data store for this microservice is probably not threadsafe. 
"In Real Life" we'd be using a proper datastore so all of this should be a moot point.
