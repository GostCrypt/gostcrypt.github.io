---
layout: simple
title: Existing implementations
---

Of course there several implementations of GOST algorithms, both open and closed source

### Open source

#### [OpenSSL](http://www.openssl.org)

CryptoCom contributed GOST algorithms implementation to OpenSSL at version 1.0.0. It supports
both TLS and S/MIME protocols. Supported algorithms are GOST 28147-89, GOST R 34.10-94, GOST R 34.10-2001,
GOST R 34.11-94. No support for Stribog hash algorithm and updated digital signature algorithm is provided.

#### [Bouncy Castle](http://www.bouncycastle.org)
BouncyCastle provides support for GOST 28147-89, GOST R 34.10-94, GOST R 34.10-2001,
GOST R 34.11-94. No support for Stribog hash algorithm and updated digital signature algorithm is provided.

### Closed source

#### [CryptoPro](http://www.cryptopro.ru)
CryptoPro is one of the major players in Russian Cryptography. CryptoPro CSP since version 4.0 gained
support for GOST R 34.10-2012/GOST R 34.11-2012 algorithms, but lost support for GOST R 34.10-94
digital signature algorithm. CryptoPro CSP natively integrates into Microsoft Windows CryptoAPI and provides
native support for GOST algorithms. There exist versions of CryptoPRO CSP for several UNIX-like operation systems
however they provide no native integration of cryptographic functions. Instead it provides
several command line tools and cryptographic library.

#### [CryptoCom](http://www.cryptocom.ru)
CryptoCom extended OpenSSL to provide GOST cryptography support in their products. CryptoPro
contributed open source implementation of gost engine to the OpenSSL cryptographic library and
actievely worked with several upstream products to integrate support for GOST algorithms.
However it looks like (for now) they provide no support for Stribog hash algorithm and updated digital signature algorithm.

#### [Lissi-crypto](http://www.lissi-crypto.ru)
Lissi-crypto provide Microsoft Windows CSP libraries (to provide native support for
GOST cryptography on Microsoft platofrms). Quite unique products Lissi provides are
GOST-enabled versions of popular Web browsers (Mozilla Firefox, Google Chrome).
Support is provided through GOST-enabled PKCS#11 libraries (for both hardware
and software tokens).

#### [Infotecs](http://infotecs.ru)
Infotecs participated in development of GOST R 34.11-2012/GOST R 34.10-2012 standards. Since version 4.0
ViPNet CSP provides support for these algorithms.
