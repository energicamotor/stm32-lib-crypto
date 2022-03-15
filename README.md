# CRYPTO LIBRARY

STM32 optimized Cryptographic Library

# Supported Hardware
- NUCLEO-L552ZE-Q
- NUCLEO-H745ZI-Q

# How to use
- Add `lib-crypto` to your project.
- Modify the `lib_crypto_config.h.example` as needed and rename it `lib_crypto_config.h`

# Available algorithms by category
## Cyclic Redundancy Check
### CHECK-8
- [header](https://github.com/energicamotor/stm32-lib-crypto/blob/main/crc/lib_check8.h)
- [source](https://github.com/energicamotor/stm32-lib-crypto/blob/main/crc/lib_check8.c)
### CRC-16-CCITT
- [header](https://github.com/energicamotor/stm32-lib-crypto/blob/main/crc/lib_crc16_ccitt.h)
- [source](https://github.com/energicamotor/stm32-lib-crypto/blob/main/crc/lib_crc16_ccitt.c)
### CRC-16-IBM
- [header](https://github.com/energicamotor/stm32-lib-crypto/blob/main/crc/lib_crc16_ibm.h)
- [source](https://github.com/energicamotor/stm32-lib-crypto/blob/main/crc/lib_crc16_ibm.c)
## Elliptic Curve Cryptography
### Elliptic Curve Digital Signature 
  - [header](https://github.com/energicamotor/stm32-lib-crypto/blob/main/ecc/ecdsa.h)
  - [source](https://github.com/energicamotor/stm32-lib-crypto/blob/main/ecc/ecdsa.c)
## Encoding
### BASE58
  - [header](https://github.com/energicamotor/stm32-lib-crypto/blob/main/enc/base58.h)
  - [source](https://github.com/energicamotor/stm32-lib-crypto/blob/main/enc/base58.c)
### BASE64
  - [header](https://github.com/energicamotor/stm32-lib-crypto/blob/main/enc/base64.h)
  - [source](https://github.com/energicamotor/stm32-lib-crypto/blob/main/enc/base64.c)
## Hash functions
### BLAKE-256
 - [header](https://github.com/energicamotor/stm32-lib-crypto/blob/main/hash/blake256.h)
 - [source](https://github.com/energicamotor/stm32-lib-crypto/blob/main/hash/blake256.c)
### BLAKE2
 - [header](https://github.com/energicamotor/stm32-lib-crypto/blob/main/hash/blake2b.h)
 - [source](https://github.com/energicamotor/stm32-lib-crypto/blob/main/hash/blake2b.c)
### Grøstl
 - [header](https://github.com/energicamotor/stm32-lib-crypto/blob/main/hash/groestl.h)
 - [source](https://github.com/energicamotor/stm32-lib-crypto/blob/main/hash/groestl.c)
### RIPEMD-160
 - [header](https://github.com/energicamotor/stm32-lib-crypto/blob/main/hash/ripemd160.h)
 - [source](https://github.com/energicamotor/stm32-lib-crypto/blob/main/hash/ripemd160.c)
### SHA-2
 - [header](https://github.com/energicamotor/stm32-lib-crypto/blob/main/hash/sha2.h)
 - [source](https://github.com/energicamotor/stm32-lib-crypto/blob/main/hash/sha2.c)
### SHA-3
 - [header](https://github.com/energicamotor/stm32-lib-crypto/blob/main/hash/sha3.h)
 - [source](https://github.com/energicamotor/stm32-lib-crypto/blob/main/hash/sha3.c)

# Available algorithms by name
### BASE58
  - [header](https://github.com/energicamotor/stm32-lib-crypto/blob/main/enc/base58.h)
  - [source](https://github.com/energicamotor/stm32-lib-crypto/blob/main/enc/base58.c)
### BASE64
  - [header](https://github.com/energicamotor/stm32-lib-crypto/blob/main/enc/base64.h)
  - [source](https://github.com/energicamotor/stm32-lib-crypto/blob/main/enc/base64.c)
### BLAKE2
 - [header](https://github.com/energicamotor/stm32-lib-crypto/blob/main/hash/blake2b.h)
 - [source](https://github.com/energicamotor/stm32-lib-crypto/blob/main/hash/blake2b.c)
### BLAKE-256
 - [header](https://github.com/energicamotor/stm32-lib-crypto/blob/main/hash/blake256.h)
 - [source](https://github.com/energicamotor/stm32-lib-crypto/blob/main/hash/blake256.c)
### CHECK-8
- [header](https://github.com/energicamotor/stm32-lib-crypto/blob/main/crc/lib_check8.h)
- [source](https://github.com/energicamotor/stm32-lib-crypto/blob/main/crc/lib_check8.c)
### CRC-16-CCITT
- [header](https://github.com/energicamotor/stm32-lib-crypto/blob/main/crc/lib_crc16_ccitt.h)
- [source](https://github.com/energicamotor/stm32-lib-crypto/blob/main/crc/lib_crc16_ccitt.c)
### CRC-16-IBM
- [header](https://github.com/energicamotor/stm32-lib-crypto/blob/main/crc/lib_crc16_ibm.h)
- [source](https://github.com/energicamotor/stm32-lib-crypto/blob/main/crc/lib_crc16_ibm.c)
### Elliptic Curve Digital Signature 
  - [header](https://github.com/energicamotor/stm32-lib-crypto/blob/main/ecc/ecdsa.h)
  - [source](https://github.com/energicamotor/stm32-lib-crypto/blob/main/ecc/ecdsa.c)
### Grøstl
 - [header](https://github.com/energicamotor/stm32-lib-crypto/blob/main/hash/groestl.h)
 - [source](https://github.com/energicamotor/stm32-lib-crypto/blob/main/hash/groestl.c)
### RIPEMD-160
 - [header](https://github.com/energicamotor/stm32-lib-crypto/blob/main/hash/ripemd160.h)
 - [source](https://github.com/energicamotor/stm32-lib-crypto/blob/main/hash/ripemd160.c)
 ### SHA-2
 - [header](https://github.com/energicamotor/stm32-lib-crypto/blob/main/hash/sha2.h)
 - [source](https://github.com/energicamotor/stm32-lib-crypto/blob/main/hash/sha2.c)
### SHA-3
 - [header](https://github.com/energicamotor/stm32-lib-crypto/blob/main/hash/sha3.h)
 - [source](https://github.com/energicamotor/stm32-lib-crypto/blob/main/hash/sha3.c)
