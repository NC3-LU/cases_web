---
layout: articlesmall
title:  "SSL/TLS – encryption technologies on the web"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
---

## In brief
All the technologies that make up SSL (Secure Socket Layer) were initially developed by Netscape for its browser software. Version 3 was taken over and extended by the IETF (Internet Engineering Task Force) for the development and standardisation of TLS (Transport Layer Security). To be precise, we should be talking about TLS rather than SSL, but SSL stuck in the vocabulary as the most widely used term to designate encryption methods mainly used for web technologies.

More specifically, these techniques add a layer of encryption to the “http” protocol and change it into “https”, in which the letter “s” stands for “secure”. This means that communications are encrypted from the browser to the web server.

## Certificates
Sites seeking to offer the possibility of encrypting communications must hold a certificate. A certificate is a set of cryptographic data and identity information. The “https” therefore not only guarantees encrypted communications, but also the site identity.

Certificates used by “https” respect standard X509. Amongst other things, such a certificate contains the following information:

* the name of the server for which the certificate was created. (e.g. www.cases.lu);
* the name of the certificate issuer. (e.g. LuxTrust SA);
* the date from which the certificate is valid and the date from which it will be considered to have expired;
* the public key of the server, as well as the name of the algorithm with which the key is used;
* the signature of the certificate issuer, as well as the method used to generate it.

As with an identity card, which is issued and certified by different States, an SSL certificate must be digitally signed by a certification authority acting as the certificate issuer. The signature of the certificate is verified by the browser using the certificate from the certification authority, which is called the root certificate. All browsers hold a large number of root certificates.

A browser will notify the user in the event of:

* the expiry of the certificate;
* inconsistency between the website domain name and the name used in the certificate (a certificate for www.cases.lu cannot be used for www.etat.lu);
* signature by an unknown authority (risk of domain name theft);

## Trust and security
Contrary to popular belief and although the term “secured site” is used, SSL does not guarantee the security of a website, which may contain vulnerabilities, but rather the site identity and the security of the communications.

For example, if you use your usual banking website, SSL can guarantee that nobody on the network will be able to read your password or see your transactions. As well as this, the certificate acts as a guarantee that you are on the correct site. It cannot, however, guarantee that the website being visited is law-abiding or that it does not present security flaws.
