---
layout: post
title: "First patches got merged into libgcrypt"
---

Today a first set of patches implementing GOST cryptography got merged into libgcrypt.

Now libgcrypt provides support for algorithms defined in GOST 28147-89,
GOST R 34.11-94 and GOST R 34.11-2012. Not all modes are implemented, s-boxes are limited to ones
defined as "for testing only". However this is the first step in the long path of GOST crypto implementation.
