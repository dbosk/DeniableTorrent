# DeniableTorrent: Private information retrieval and sharing for Torrent like protocols

In the current BitTorrent protocol it is obvious what files someone is after. It would be interesting to add private information-retrieval to the protocol, thus giving better privacy properties.

[OneSwarm](http://www.oneswarm.org/about.html) was a good initiative. It's downside (I guess) is the requiement of a social network. Also it required an additional client. The protocol must be transparently implementable in [libtorrent](http://www.libtorrent.org/) so that all clients can support it.
