<div align="center">

# [![Easy Libcurl](logo.svg)](https://github.com/nktnet1/easy-libcurl)

Please support [@JCMais](https://github.com/JCMais)'s original work on [node-libcurl](https://github.com/JCMais/node-libcurl#building-on-windows)

[![Try with Replit](https://replit.com/badge?caption=Try%20with%20Replit)](https://replit.com/@nktnet1/easy-libcurl-example#index.js)

</div>

---

- [1. Installation](#1-installation)
- [2. Usage](#2-usage)
- [3. License](#3-license)
- [4. Compatibility](#4-compatibility)
- [5. Caveats](#5-caveats)

## 1. Installation

```
npm install easy-libcurl
```

## 2. Usage

The Easy API is available in **node-libcurl**'s [documentation](https://node-libcurl-docs.netlify.app/classes/_lib_easy_.easy).

An example usage is provided in **node-libcurl**'s [examples/02-easy.js](https://github.com/JCMais/node-libcurl/blob/887949944dce38a19ee4ecbc5854aabe757e2a46/examples/02-easy.js).

## 3. License

<details closed>
<summary>node-libcurl (click to view)</summary>

```
MIT License

Copyright (C) 2014-present Jonathan Cardoso

Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the "Software"), to deal in the Software without
restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.
```

</details>

<details closed>
<summary>easy-libcurl (click to view)</summary>

```
Copyright (c) 2023 Khiet Tam Nguyen

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the “Software”),
to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL
THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
DEALINGS IN THE SOFTWARE.
```

</details>

## 4. Compatibility

See **node-libcurl**'s instructions for
- [build on Linux](https://github.com/JCMais/node-libcurl#building-on-linux)
- [build on MacOS](https://github.com/JCMais/node-libcurl#building-on-macos)
- [build on Windows](https://github.com/JCMais/node-libcurl#building-on-windows)

## 5. Caveats

About **easy-libcurl**:
- Made mainly to reduce size and complexity for use in [sync-request-curl](https://github.com/JCMais/node-libcurl#building-on-windows)
- Only the [Easy Interface](https://curl.se/libcurl/c/libcurl-easy.html) of [libcurl](https://curl.se/libcurl/c/) is exposed
- All development tests, setups and dependencies removed
- Cleaner distributable - see [pull request 398](https://github.com/JCMais/node-libcurl/pull/398) for further details

Prebuilt binaries of libcurl will still be installed from assets in **node-libcurl**'s [releases](https://github.com/JCMais/node-libcurl/releases).