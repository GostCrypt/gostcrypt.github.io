---
layout: simple
title: Implementation status
permalink: standards
special: true
---
### GOST Standards

1. GOST 28147-89
    * block cipher - merged, test params only
    * ECB - existing code
    * CFB - existing code
    * CNT - WIP
    * IMIT - not implemented
1. GOST R 34.10-94 - not implemented
1. GOST R 34.10-2001 - submitted
1. GOST R 34.10-2012 - submitted
1. GOST R 34.11-94 - merged, test params only
1. GOST R 34.11-2012 - merged

### RFC4357

1. symmetric ciphers

    * S-Boxes - not implemented
1. cipher modes

    * CBC - existing code
1. padding modes

    * Not necessary - higher level code(?)
1. key meshing

    * CryptoPro - not implemented
1. HMAC_GOSTR3411

    * Not verified, should be handled by existing code

1. PRF_GOSTR3411

    * TLS specific thing
1. key derivation
    * VKO GOST R 34.10-94 - not implemented
    * VKO GOST R 34.10-2001 - not implemented
1. key wrap
    * GOST 28147-89 - not implemented
    * CryptoPro - not implemented
1. key diversification
    * CryptoPro KEK - not implemented
    * Secret key - not implemented
