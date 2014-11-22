---
layout: post
title: "LibreSSL got GOST support"
categories: [posts]
---

LibreSSL library received GOST cryptorgraphy support.

LibreSSL is a fork of OpenSSL library made by OpenBSD project. One of the goals of the fork
is to have a clean, working and secure TLS/cryptography implementation. One of the first
things they did after the fork was dropping of most of so-called "engines". Including
ccgost engine, which implemented GOST algorithms support. Time has passed and today LibreSSL
CVS got a set of patches fully implementing GOST support as a part of the core library.
The LibreSSL now supports all necessary GOST algorithms, including GOST R 34.11-2012 and
GOST R 34.10-2012.
