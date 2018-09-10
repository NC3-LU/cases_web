---
layout: article
title:  "LuxTrust"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossaryluxtrust
lang: en
---
## In brief
LuxTrust offers [authentication]({% link _knowhow/glossary/Authentication.markdown %}) and [electronic signature]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#electronic-signatures) products. The most frequently used products in the professional domain are the chip card and the signing stick. From a technological point of view, these two products are very similar: a chip integrated into the card or the USB stick contains an authentication certificate and a signature certificate. The chip card requires the use of a card reader, which is not the case for the USB stick.

Depending on the type of card, the signature may be a personal signature, in other words in the cardholder’s name, or it may be a professional signature, which means it’s in the name of one of the organisation’s managers and makes it liable.

## Advantages
The following security advantages are offered by either the chip card or the signing stick:

* The authentication and signature devices cannot be copied;
* The activation of certificates requires a PIN code to be entered. As the card is automatically blocked after 3 incorrect PIN code attempts, a brute force PIN code attack is impossible, even though the code is composed solely of numbers. To unlock the card, you need the PUK code, which is much more complex than the PIN code;
* It’s very easy and quick to change the PIN code. It is therefore recommended that you change it immediately if you suspect a third party might have discovered it.
* You will soon notice if the card or stick has been stolen, especially in a professional environment where the authentication and signature device is used regularly. If necessary, the tool in question can quickly be cancelled or temporarily suspended. Such a cancellation or suspension becomes effective within four hours at most.

## Security measures

### Behavioural security measures
Make sure you adopt some security measures:

* The LuxTrust authentication device is strictly personal. Guard against any illicit use, notably theft.
* Do not lend your authentication and signature device to others. Anybody who is in possession of your LuxTrust authentication device and who knows your PIN code can sign authorised documents or access your online services, both professional or private.
* Never write your PIN code on your LuxTrust card.
* In the event of theft, cancel your LuxTrust card immediately. In case of doubt, you can suspend your LuxTrust authentication signature device for 30 days. A suspended certificate can be reactivated, whereas the cancellation of a card is permanent. As the suspension or cancellation of your card takes affect within 4 hours of the request, once this deadline has passed your card with no longer work for authentication or signatures.

### Organisational security measures
* Draft and enforce a security policy relating to the development and maintenance of the systems – [electronic signature]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#electronic-signatures);
* Draft and enforce a security policy relating to access control – [access rights management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-rights-management);
* Train your staff in the correct use of LuxTrust’s signature and authentication devices.
