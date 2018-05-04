# mountebank-ok

A docker container containing a [mountebank](http://www.mbtest.org/) service that:

- exposes a HTTP server on port 8080 that always returns HTTP 200  
- exposes the mountebank serivce on port 2525

This allows for free-form contract/integration testing of a service where no 
useful mocking library is readily available (Mountebank offers the ability
to query the details of the requests made on port 8080).

