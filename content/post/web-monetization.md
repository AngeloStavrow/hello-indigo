---
title: "Web Monetization support"
date: 2020-07-13T11:15:00-04:00
draft: false
categories: ["features"]
tags: ["monetization"]
---

With the [release of v1.4.0], Indigo now supports [Web Monetization]!

<!--more-->

Web Monetization is a privacy-focused draft Web API that aims to change how creators can generate revenue from their work. To enable it in Indigo, add your [payment pointer] to the new `paymentPointer` site parameter in the **config.toml** file for your site.

Subscribers to a web monetization service like [Coil] will then stream micropayments to your account when they visit your blog.

[release of v1.4.0]: /release/indigo-v1-4-0-released/
[Web Monetization]: https://webmonetization.org/
[payment pointer]: https://webmonetization.org/docs/getting-started#2-get-your-payment-pointer
[Coil]: https://coil.com