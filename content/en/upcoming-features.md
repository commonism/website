---
title: Upcoming Features
slug: upcoming-features
top_graphic: 1
lastmod: 2021-04-29
---

{{< lastmod >}}

## IP Addresses in Certificates

We are planning to add support for validating and including IP addresses in certificates.

## ECDSA Root and Intermediates

We are issuing certificates from our production ECDSA intermediate to [allow-listed accounts](https://community.letsencrypt.org/t/ecdsa-availability-in-production-environment/150679). There is no planned date for removing the allow-list.

# Completed Features

## Multi-Perspective Validation

* Enabled: February 19, 2020

We now validate domain control from [multiple network perspectives](https://letsencrypt.org/2020/02/19/multi-perspective-validation.html).

## Certificate Transparency Log

* Enabled: May 15, 2019

We now operate a [Certificate Transparency log](/docs/ct-logs).

## TLS ALPN Challenge Support

* Enabled: July 12, 2018

We've specified and implemented a [replacement](https://tools.ietf.org/html/rfc8737) for the TLS-SNI validation method, which was [discontinued for security reasons](https://community.letsencrypt.org/t/important-what-you-need-to-know-about-tls-sni-validation-issues/50811). Introducing a replacement was important for subscribers who only want to use port 443 for validation.

## Embed SCT receipts in certificates

* Enabled: March 29, 2018

## Wildcard Certificates

* Enabled: March 13, 2018

## ACME v2 API

* Enabled: March 13, 2018

## IDN Support

* Enabled: October 20, 2016

Let's Encrypt now supports issuance for Internationalized Domain Names (IDNs).

## Full IPv6 Support

* Enabled: July 26, 2016

Initially, only parts of the Let's Encrypt API infrastructure could communicate via IPv6. This prevented IPv6-only systems from being able to fully interact with Let's Encrypt. This has been resolved - IPv6 support has been enabled for all functionality.

## Windows XP Certificate Compatibility

* Enabled: March 25, 2016

Resolved an issue with our certificate chain that prevented Let's Encrypt certificates from being accepted by browsers on Windows XP.

## ECDSA Signing Support

* Enabled: February 10, 2016

Added the ability for Let's Encrypt to sign ECDSA keys with Let's Encrypt's RSA intermediates. Support for signing ECDSA keys with a full ECDSA cert chain will be added later.

## ACME DNS Challenge Support

* Enabled: January 20, 2016

Let's Encrypt allows validation via DNS records as defined in the ACME specification.
