# base64

This rust library provides functions for base64:
*  Encoding of `Vec<u8>` outputting to `Vec<char>`
*  Decoding of `Vec<char>` outputting to `Vec<u8>`

This was developed for fun and learning by Geno.

## Usage

Add the following to your Cargo.toml under `[dependencies]`:
```
base64 = { git = "https://github.com/genonullfree/base64.git" }
```

Add the following to your .rs file:
```
use ::base64::*;
```
