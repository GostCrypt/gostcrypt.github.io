---
layout: post
title: "LibreSSL 2.1.2 featuring GOST cryptography was released"
categories: [posts]
---

LibreSSL library version supporting GOST cryptography was released.

The new release of LibreSSL library (2.1.2) was posted today. Several months
ago ccgost engine was dropped from the library. It was a dynamic engine, wasn't
really maintained upstream, didn't implement the latest versions of GOST
algorithms. So the removal was logical. Now GOST support was added back,
including all major algorighms (except GOST R 34.11-94 signatures/public keys,
they are obsolete now). Kudos goes to the CryptoPro company for providing a
public-accessible tls testing servers.
