---
layout: simple
title: Enabling GnuTLS 
---

### GnuTLS with LibGCrypt

A long time ago it was possible to build GnuTLS with either Nettle crypto backend or with libgcrypt one. At some point this functionality was removed. The first step is to bring things back.

#### Internal Crypto backend API

In my current tree all API is supported.

#### libgcrypt additions

##### Required
* PKCS1 simple verification (hash AID checked on the caller's side) (submitted).
* Hash truncation for DSA/ECDSA modes.

##### Optional
* UMAC

##### Done
* Salsa20 and Salsa20/12.
* GCM

### GOST support in GnuTLS

* Add support for GOST public and private keys loading
* Add support for actually handling GOST keys
* Add support for GOST ciphersuites
* (optional) S/MIME to PKCS 7 conversion as handled by certtool ????
* (optional) - dnssec/dane/etc
* TC26 defined addenums to PKCS #5, #8, #12 and #15. Analyze if there is anything to implement in GnuTLS.
