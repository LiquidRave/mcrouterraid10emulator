# mcrouterraid10emulator
This is a raid 10 emulator for 4 instances of memcached, data is being sharded to two instances and replicated on two instances.
If one memcached instance fails, his replica set will pick up the load and re-seed the keys back.
