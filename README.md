# grl
Generic Rate Limiting (GRL) service

Generic rate limiting service based on vertx and bucket4j
The aim is to initial support http incoming requests and then focus on other interfaces (eg udp/tcp/grpc)
GRL will require backend REDIS server present to be used for the rate limiting actions by bucket4j token-bucket algorithm
