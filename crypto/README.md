# This Notes is for Crypto stuff (how to handle bytes)

### convert a hex string to sequence of bytes (for byte operations)
use the byteutils package an download it with nimble
```sh
nimble install byteutils
```
convert example:
```nim
var encryptedMessage1 = hexToSeqByte("fd034c32294bfa6ab44a28892e75c4f24d8e71b41cfb9a81a634b90e6238443a813a3d34")
```
[click here for Code example Crypto CTF Challenge](sol.nims)


