# Awesome SCION
A curated list of awesome SCION libraries, frameworks, tools and code snippets.

## Collections of Resources
Repositories that contain a bunch of different resources, like demos, tools, libraries, etc.

- [scion-apps](https://github.com/netsec-ethz/scion-apps)  Demo applications using the SCION protocol.

## Libraries

### Path-Aware Networking
- [pan](https://github.com/netsec-ethz/scion-apps/pull/187) Path-aware Networking library to replace appnet
- [SCION pathdiscovery](https://github.com/netsys-lab/scion-path-discovery) Design and implementation of a multipath library for SCION.

## Protocols

### Transport over SCION
Custom Transport protocols running on SCION.
- [appquic](https://github.com/netsec-ethz/scion-apps/tree/master/pkg/appnet/appquic) Quic-go wrapper for SCION
- [parts](https://github.com/netsys-lab/parts) Path-aware Reliable Transport over SCION

## Applications and Extensions

### Filetransfer
Applications to transfer files over SCION.
- [BitTorrent over SCION](https://github.com/netsys-lab/bittorrent-over-scion) Path-aware BitTorrent client running on SCION
- [BitTorrent DHT](https://github.com/netsys-lab/dht) Dht-based peer discovery for BitTorrent over SCION

## Research Tools

### Bandwidth Tester
Tools that create traffic, measure bandwidth, etc.
- [bandwidthtester](https://github.com/netsec-ethz/scion-apps/tree/master/bwtester) SCION bandwidth tester
- [spate](https://github.com/netsys-lab/scion-apps/tree/tool/spate-bpf/spate) Multipath traffic generator and bandwidth
