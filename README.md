# The Things Network Redis

Redis is an open-source, networked, in-memory, key-value data store with optional durability. It is written in ANSI C. The development of Redis has been sponsored by Pivotal since May 2013; before that, it was sponsored by VMware. According to the monthly ranking by DB-Engines.com, Redis is the most popular key-value store. The name Redis means REmote DIctionary Server.

## About this image

- Based on [`redis:alpine`](https://hub.docker.com/_/redis/) (BSD License)
- Uses `appendonly.aof` AOF persistence
- Uses `dump.rdb` RDB persistence
- Publishes keyspace events for generic, list, set and hash commands
