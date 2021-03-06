# NDN Essential Tools

[![Build Status](https://travis-ci.org/named-data/ndn-tools.svg?branch=master)](https://travis-ci.org/named-data/ndn-tools)

**ndn-tools** is a collection of essential tools for
[Named Data Networking](http://named-data.net/).
These tools are recommended to be installed on all NDN nodes.  
Tools in this collection include:

* [peek](tools/peek): transmit a single packet between a consumer and a producer
* [chunks](tools/chunks): segmented file transfer between a consumer and producer
* [ping](tools/ping): test reachability between two nodes
* [dump](tools/dump): analyze traffic on wire
* [dissect](tools/dissect): inspect TLV structure of NDN packet format
* [dissect-wireshark](tools/dissect-wireshark): Wireshark extension to inspect TLV structure of NDN
  packets
* [pib](tools/pib): a service to manage the public information of keys and publish certificates

See [INSTALL.md](INSTALL.md) for build instructions.

If you are new to the NDN software community, please read the
[Contributor's Guide](https://github.com/named-data/NFD/blob/master/CONTRIBUTING.md).  
Please file bug reports and feature requests on
[ndn-tools Redmine site](https://redmine.named-data.net/projects/ndn-tools).  
You may contribute code on [NDN Gerrit](https://gerrit.named-data.net).
GitHub pull requests are not accepted.
