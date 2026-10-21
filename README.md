# Straum

A clustered MQTT broker in Rust that acknowledges a publish only after a
majority of its nodes has committed it to one replicated log.

**Website and docs: [straum-io.github.io](https://straum-io.github.io/)**

> Experimental, not production-ready: no TLS or credentials yet. See the
> [limitations](https://straum-io.github.io/project/limitations/).

| Repository | What it is | Status |
|---|---|---|
| [straum](https://github.com/straum-io/straum) | The broker: MQTT 3.1.1 and 5, majority commit, failover, Prometheus metrics | Experimental |
| [straum-cli](https://github.com/straum-io/straum-cli) | Terminal client: publish, subscribe, every node's state | Experimental |
| [straum-console](https://github.com/straum-io/straum-console) | Web console for a cluster | Not started |
| [straum-io.github.io](https://github.com/straum-io/straum-io.github.io) | This website | |

Start with the [quick start](https://straum-io.github.io/start/quick-start/):
three nodes on one machine.
