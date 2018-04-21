# cache

Simple Python HTTP Cache using sqlite3

* Stores cached data in sqlite3.Blobs
* Calculates lifetime, freshness as virtual columns
* Obeys cache control directives, immutable, no-store, etc
* Supports etag, last_modified, etc for validation 

Primarily designed for use with Kodi plugins but generic enough for most 
purposes.

Can be used as a generic key/blob data store that without directives.

https://docs.python.org/2/library/sqlite3.html
https://tools.ietf.org/html/rfc7234
