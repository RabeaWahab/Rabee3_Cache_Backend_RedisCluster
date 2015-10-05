# Rabee3_Cache_Backend_RedisCluster
Redis Cache Backend for Magento with Cluster Support

The extension of Zend_Cache is built depending on [Predis](https://github.com/nrk/predis) as a client library, at the same time it has been created from a working copy of the standard `Credis` supported by Magento.

Please make sure that :
- you have Predis installed and added to composer.
- Redis 3.0 to support cluster.

Note:
- A set of functionalities is still not supported by the cluster such as *Intersection* and *Union*.
