# [easy-libcurl](https://github.com/nktnet1/easy-libcurl)

Please support @JCMais's original work on **node-libcurl**:
- https://github.com/JCMais/node-libcurl
- https://www.npmjs.com/package/node-libcurl

About this fork of **node-libcurl**:
- Made mainly to reduce build size and complexity for use in **sync-request-curl**:
    - https://github.com/nktnet1/sync-request-curl
    - https://www.npmjs.com/package/sync-request-curl
- Only the Easy interface of [libcurl](https://curl.se/libcurl/c/) is exposed
- Minimal production dependencies
- All development tests, setups and dependencies removed

Binary versions of libcurl will still be installed from **node-libcurl**'s released assets:
- https://github.com/JCMais/node-libcurl/releases