# goTCHA

In a world of [pets vs cattle](http://blog.factual.com/docker-mesos-marathon-and-the-end-of-pets) one price we pay for the dynamic allocation of applications to nodes and ports is service discovery. To help folks to get up to speed with service discovery, I decided to write goTCHA (Transparent CHoreography Automation written in Go), an opinionated service discovery tool that:

- Assumes you have [Mesos-DNS](http://mesosphere.github.io/mesos-dns/), for the global mapping between apps to node `IP:PORT`
- Uses [HAproxy](http://www.haproxy.org/) per node for load balancing and routing
- Provides [Marathon](https://mesosphere.github.io/marathon/) app specs for deployment
- Is written in [Go](https://golang.org/) for minimal dependencies
- Enables dynamic allocation in a transparent way, that is, no need to re-write your existing apps (be it containerized or not)

## Usage

## Example

