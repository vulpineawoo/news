---
layout: post
title: new tor usercloak
---

tor connections now have your sasl accountname appended to the end (ie `~xfnw@gateway/tor/xfnwtest`)

tor users not using sasl will now have `/account` at the end instead of `/unidentified`, however note
that sasl will soon be enforced on tor connections. making this irrelevant.
