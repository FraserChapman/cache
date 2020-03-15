# cache

Simple Python HTTP Cache using sqlite3

* Stores cached data in sqlite3.Blobs
* Calculates lifetime, freshness as virtual columns
* Obeys cache control directives, immutable, no-store, etc
* Supports etag, last_modified, etc for validation 
* Can be used as a generic key/blob data store when used without directives

Originally designed for use with Kodi plugins but generic enough for most 
purposes.

For use in Kodi you are probably better served using the [script.module.cache](https://github.com/FraserChapman/script.module.cache) 


https://docs.python.org/2/library/sqlite3.html

https://tools.ietf.org/html/rfc7234
