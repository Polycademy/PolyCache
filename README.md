PolyCache
=========

Polyglot Caching Service

Integration of tedivm/Stash and Flysystem and Gaufrette. So the cache can accept a filesystem adapter. Should abide by PSR-6.

This will be a daemon that can expose a REST interface or an RPC interface.

Look into Thrift RPC and other messaging protocols.

Might build it with Node.js or PHP Amp, since async IO would be very suitable.

Should be stateless and functional so it can be parrallelised.

Can be used by any language and use any adapter.

Inpiration: https://github.com/tedivm/Stash/issues/23 Look at all the cool strategies!

Needs to be clusterable, and can support distributed cache. The distributed aspect of cache would be handled by the drivers.

Also use these strategies: http://en.wikipedia.org/wiki/Cache_algorithms
