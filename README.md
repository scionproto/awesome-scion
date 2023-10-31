# Awesome SCION

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Slack chat](https://img.shields.io/badge/chat%20on-slack-blue?logo=slack)](https://scionproto.slack.com)
[![Matrix chat](https://img.shields.io/badge/chat%20on-matrix-blue?logo=matrix)](https://matrix.to/#/#dev:matrix.scion.org)
[![SCION Association](https://img.shields.io/badge/SCION-Association-white)](https://www.scion.org)

<a href="https://www.scion.org"><img src="awesome-scion-logo.png" height="160" align="right" alt="awesome SCION"></a>

A curated list of awesome SCION tools, applications, libraries and resources.

> Symbol legend
> - :wrench:: Experimental
> - :construction:: Under construction
> - :broom:: Outdated/discontinued/unclear

## Infrastructure
- [scionproto/scion](https://github.com/scionproto/scion) - The open-source implementation of SCION.
- [Anapaya](https://www.anapaya.net) - Vendor of SCION infrastructure, both based on the open-source implementation and proprietary.
- [scion-ca](https://github.com/netsys-lab/scion-ca) - SCION Control Plane PKI implementation based on [smallstep/step-ca](https://github.com/smallstep/certificates).
- [bootstrapper](https://github.com/netsec-ethz/bootstrapper) - SCION endhost autoconfiguration tool.
- [tofino-scion-br](https://github.com/netsys-lab/scion-p4/tree/main/tofino-scion-br) - SCION border router in P4 with support for AES accelerators. :wrench:
- [eXpress SCION Router (XSR)](https://github.com/netsys-lab/express-scion-router) - A SCION border router making use of XDP and P4. :wrench: :construction:

## Applications
- [scion-apps](https://github.com/netsec-ethz/scion-apps) - Miscellaneous SCION demo applications.
- [scion-browser-extension](https://github.com/netsys-lab/scion-browser-extensions) - SCION support for Chrome/Firefox ([docs](https://docs.scionlab.org/content/apps/scion-browser.html)). :wrench:
- [bittorrent-over-scion](https://github.com/netsys-lab/bittorrent-over-scion) - Path-aware BitTorrent client running on SCION.
- [spate](https://github.com/netsys-lab/scion-apps/tree/tool/spate-bpf/spate) - Multipath traffic generator and bandwidth tester. :wrench:
- [hercules](https://github.com/netsec-ethz/hercules) - High speed bulk data transfer application. :wrench:
- [ioq3-scion](https://github.com/lschulz/ioq3-scion) - Quake III with SCION networking. :boom:

## Libraries

##### Go
- [scion-apps/pkg/pan](https://pkg.go.dev/github.com/netsec-ethz/scion-apps/pkg/pan) - Policy-based, path aware network library for building applications supporting SCION natively.
- [scion-apps/pkg/shttp](https://pkg.go.dev/github.com/netsec-ethz/scion-apps/pkg/shttp) - Glue to use the standard net/http libraries for HTTP with SCION, using pan.
- [scion-apps/pkg/shttp3](https://pkg.go.dev/github.com/netsec-ethz/scion-apps/pkg/shttp3) - Glue to use quic-go/http3 libraries for HTTP/3 with SCION, using pan.
- [parts](https://github.com/netsys-lab/parts) - Path-aware Reliable Transport over SCION. :wrench:
- [scion-path-discovery](https://github.com/netsys-lab/scion-path-discovery) - Multipath library for SCION.
- [snet](https://pkg.go.dev/github.com/scionproto/scion/pkg/snet) - Primary, but low-ish-level level library for native SCION applications.

##### Java
- [scion-java-client](https://github.com/netsec-ethz/scion-java-client) - Java SCION application library. :construction:

##### Rust
- :lobster: - Rust SCION application library. Work in progress, not yet public. :construction:

##### Bindings
- [pan-bindings](https://github.com/lschulz/pan-bindings) - C, C++, and Python bindings for pan.
- [pan-lua](https://github.com/netsys-lab/pan-lua) - Lua-scriptable path selector interface to pan.

## Deployments
- [SSFN](https://www.six-group.com/de/products-services/banking-services/ssfn.html) - Swiss Secure Finance Network, a closed network using SCION.
- [Scion Education Network](https://sciera.readthedocs.io/en/latest/index.html) - SCION network connecting universities and national research and education networks (NRENs).
- [SCIONLab](https://www.scionlab.org) - Global SCION network testbed.
- [SCI-ED](https://scied.scion-architecture.net/) - SCION at various institutions of the ETH Domain. :broom:
- [swissix SCION peering](https://www.swissix.ch/services/scion-peering-mesh/scion-peering-participants/) - SCION peering mesh at the swissix internet exchange.

## Tools
- [SEED Emulator](https://github.com/seed-labs/seed-emulator/tree/master/examples/scion) - SEED Security Labs network emulator supports SCION.
- [scapy-scion-int](https://github.com/lschulz/scapy-scion-int) - [Scapy](https://scapy.net/) layers for SCION.
- [tofino-pktgen](https://github.com/netsys-lab/scion-p4/tree/main/tofino-pktgen) - SCION packet generator for Intel Tofino 2 switches.

## IETF
- [draft-dekater-panrg-scion-overview](https://datatracker.ietf.org/doc/draft-dekater-panrg-scion-overview/)
- [draft-rustignoli-panrg-scion-components](https://datatracker.ietf.org/doc/draft-rustignoli-panrg-scion-components/)
- [draft-dekater-scion-pki](https://datatracker.ietf.org/doc/draft-dekater-scion-pki/)
- [draft-dekater-scion-controlplane](https://datatracker.ietf.org/doc/draft-dekater-scion-controlplane/)
- [draft-dekater-scion-dataplane](https://datatracker.ietf.org/doc/draft-dekater-scion-dataplane/)

## Research
- [Publications list](https://scion-architecture.net/pages/publications/)
- [LightningFilter](https://github.com/netsec-ethz/lightning-filter) - High-speed traffic filtering mechanism that performs authentication, rate limiting, and duplicate detection.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
