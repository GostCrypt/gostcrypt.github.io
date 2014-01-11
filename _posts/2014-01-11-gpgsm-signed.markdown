---
layout: post
title: "GnuPG SM can verify signed S/MIME messages"
---

Got gpgsm to verify the signature on the 'signed' example in RFC4490. The code contains few dirty hacks
(thus I'm not posting it to GitHub yet), but it works and it actually verifies the signature. Next step
would be to add support for encrypted messages with key transport.
