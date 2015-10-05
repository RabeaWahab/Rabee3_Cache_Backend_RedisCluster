# Rabee3_Cache_Backend_RedisCluster
Redis Cache Backend for Magento with Cluster Support

The extension of Zend_Cache is built depending on [Predis](https://github.com/nrk/predis) as a client library, at the same time it has been created from a working copy of the standard `Credis` supported by Magento.

##Usage:
- add a new tag to your `app/etc/local.xml` file under the cache sections:
1. `<backend>Rabee3_Cache_Backend_RedisCluster</backend>`
2. `<cluster>true</cluster>`

As per the documentation of Predis, ony support one IP for Redis and all the nodes will discover each other. so there is no changes other than the above.

###Please make sure that :
- You have Predis installed and added to composer.
- Redis 3.0 to support cluster.

###Note:
- A set of functionalities is still not supported by the cluster such as *Intersection* and *Union*.
