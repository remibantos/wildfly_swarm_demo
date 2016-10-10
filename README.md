# wildfly_swarm_demo
Sample service built as an uberjar with [Wildfly Swarm](http://wildfly-swarm.io/).

Uses JAX-RS with CDI and management-console Wildfly fractions.

Run mvn wildfly-swarm:run to get access to:
* http://localhost:8080/hello, the hello resource
* http://localhost:9990, the Wildfly management UI
