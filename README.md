# grl
Generic Rate Limiting (GRL) service

Generic rate limiting service based on vertx[^1] and bucket4j[^2].

The aim is to initial support http incoming requests and then focus on other interfaces (eg udp[^6]/tcp[^5]/grpc[^4]). GRL will require backend REDIS[^3] server present to be used for the rate limiting actions by bucket4j[^2] token-bucket algorithm

[^1]: [Eclipse Vert.x™ Reactive applications on the JVM](https://vertx.io/)
[^2]: [Bucket4j - Java rate-limiting library based on token-bucket algorithm](https://github.com/bucket4j/bucket4j)
[^3]: [Bitnami package for Redis(R)](https://artifacthub.io/packages/helm/bitnami/redis)
[^4]: [Vert.x gRPC](https://vertx.io/docs/vertx-grpc/java/)
[^5]: [Vertx TCP servers & clients]([vertx.io/docs/vertx-core/java/#_writing_tcp_servers_and_clients](https://vertx.io/docs/vertx-core/java/#_writing_tcp_servers_and_clients))
[^6]: [Vertx Datagram socket UDP](https://vertx.io/docs/vertx-core/java/#_datagram_sockets_udp)
