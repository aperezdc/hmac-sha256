hmac-sha256
===========

HMAC-SHA256 implemented in C.

Installation
------------

Install with [clib](https://github.com/clibs/clib):

```sh
clib install aperezdc/hmac-sha256 --save
```

API
---

```c
#define HMAC_SHA256_DIGEST_SIZE 32

void hmac_sha256 (uint8_t out[HMAC_SHA256_DIGEST_SIZE],
                  const uint8_t *data, size_t data_len,
                  const uint8_t *key, size_t key_len);
```


License
-------

Distributed under the terms of the [MIT/X11
license](https://opensource.org/licenses/MIT)
