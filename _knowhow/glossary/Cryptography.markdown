---
layout: article
title:  "Cryptography"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossarycryptography
lang: en
---

> Check to verify the completeness of this article.

## History
Humans have always tried to keep certain information or data secret or, failing this, to restrict access to certain people. One of the oldest examples of cryptographic use comes from Julius Caesar.

The Roman emperor used a specific method to communicate with his general staff. As messages in those days were carried by messengers, Julius Caesar wanted to protect their confidentiality. His transcription method was to replace one letter by an offset of three. For example, 'A' was replaced with 'D', 'B' with 'E', and so on. In this way, only those who knew the ruse were able to decode the information.

Until the twentieth century, the use of cryptography was relatively minor and methods used were often rudimentary.

It was only during the Second World War, with the advent of advanced communication technologies such as radio, that it became indispensable to develop encryption mechanisms preventing the interception of signals by the enemy. In fact, it became necessary to start encrypting radio transmissions (Enigma)! Cryptography had a major impact on this global conflict.

Since then, but especially with the advent of the DES algorithm and the advent of asymmetric cryptography, the use of cryptography has exploded. The needs of military applications have mingled with the needs of civilian applications and encryption techniques have become an engine of progress. (banking applications, telecommunications, IT, online banking, etc.)

## Definitions

### Cryptography
This is the science of the mathematical principles and methods applied for purposes such as data confidentiality or integrity. It therefore tends to develop techniques for the storage of sensitive information and its transmission via insecure networks (such as the Internet) so that the data can only be read or altered by authorised individuals.

### Cryptanalysis
Cryptanalysis is the study of the security of cryptographic mechanisms. It involves testing existing cryptographic functions in order to assess their strengths and weaknesses. Cryptanalysis is therefore a combination of analytical reasoning, the application of mathematical tools, the discovery of redundancies, patience, determination – and also luck.

### Cryptology
Cryptology is the science that covers both cryptography and cryptanalysis.

> IMAGE OR SMTH

### Encryption and decryption
"Plain text" refers to data that is readable and understandable without specific intervention. Encryption is the method of hiding plain text by masking its content. This involves turning a normal text into unintelligible gibberish called encrypted text. This operation ensures that only the people for whom the information is intended will be able to access it. The reverse process – converting encrypted text back to the original text – is called decryption.

### Key
The key is the value used in a cryptographic algorithm to encrypt a text. This is often a very large number, whose size is measured in bits. The larger the key, the greater the security of the solution. However, it is the combination of algorithms and keys that guarantees the security of the solution. Keys must be stored securely so that only the owner can access and use them.

### Cryptosystem
A cryptosystem is an overall cryptographic solution. Such a system therefore includes the encryption algorithm plus all the keys used and the protocols necessary for its operation.

## Symmetric cryptography
Private key encryption systems, also known as symmetric encryption systems, have been used for centuries.

### Basic principle
A sender and a recipient wishing to communicate securely using symmetric encryption must agree on a key and not disclose it. In symmetric encryption systems, the encryption key and the decryption key are identical.

### Advantages

> WHAT?

Symmetric encryption has a major advantage: speed. It is particularly suitable for sending large amounts of data.

### Weaknesses
This system requires that the sender and the recipient both know the key. However, the transmission of this key between those involved is the inherent weakness of the system. If they are in different geographical locations, they will have to trust a third party or use a secure means of communication.

Anyone intercepting the key during a transfer can then read, modify and falsify all encrypted information with this key.

From Julius Caesar's secret code to the AES data encryption standard, the distribution of keys remains the major symmetric encryption problem. (In other words, how can the key be sent to the recipient without being intercepted?) The resources required to ensure the secure distribution of keys between correspondents are very expensive, which is an additional inconvenience.

In general it is important to use secure channels, for example the post office or the telephone, to transmit the key. It is also possible to use asymmetric cryptography to exchange keys.

### Examples
In English the terms are: Single-key, one-key, private-key, symmetric-key encryption.

The main private key algorithms are:

* Blowfish
* DES/3DES
* IDEA
* RC2, RC5, RC6
* Rijndael/AES

## Asymmetric cryptography
Public key cryptography is a response to the problem of key transmission in private key encryption. The concept was devised by Whitfield Diffie and Martin Hellman in 1975, although it is commonly accepted that the British secret service had already made the same discovery several years earlier, but that it was protected as a military secret.

### Basic principle
Public key cryptography is an asymmetric method that uses a key pair for encryption, i.e. a public key to encrypt the data and a corresponding private or secret key for the decryption.

The principle is, therefore, to distribute the public key while keeping the private key secret. Any user holding a copy of the public key can then encrypt information that only the owner of the private key can decrypt.

Note also that it is impossible to guess the private key from the public key.

All of the above is what causes this system to be called "asymmetric".

Note that the private key can also be used for encryption; it is then the public key that is used for the decryption. This property is used not for confidentiality but for electronic signature (integrity).

### Advantages
Public key cryptography has a major advantage: it allows messages to be exchanged securely without any additional security features.

The sender and recipient no longer need to share secret keys via a secure transmission channel. Communications involve only the use of public keys and no private key is transmitted or shared.

Public key encryption is a technological revolution offering every citizen the opportunity to use robust cryptography. Indeed, symmetric cryptography was previously the only method for the transmission of secret information. The costs of the transmission and secure distribution of keys had limited its use to institutions with sufficient means, such as governments and banks.

## Examples of public key cryptography
Elgamal (from the name of its inventor, Taher Elgamal), RSA (from the names of its inventors, Ron Rivest, Adi Shamir and Leonard Adleman), Diffie-Hellman (also named after its inventors) and DSA, the digital signature algorithm (developed by David Kravitz), are examples of public key cryptography systems.

A practical example of public key cryptography is OpenPGP for email encryption or TLS (https) for web communications encryption; TLS uses public-key cryptography for key exchange and then symmetric cryptography for encryption of communication.

## Security policy
Draft and enforce a sectoral policy on:

* [Classification and monitoring of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %})
  * [Classification of and responsibility for resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %}#classification-and-responsibility-for-resources)
* [Human factors]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %})
  * [Training and information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#training-and-information)
* [Physical and environmental security]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %})
  * [Off-site equipment security]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#off-site-equipment-security)
* [Operational and communications aspects]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %})
  * [Documented procedures]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#documentation-of-procedures)
  * [Data backups]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#data-backups)
  * [Device security during transport]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#device-security-during-transport)
  * [Email]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#email)
* [Access control]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %})
  * [Access control policy]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-control-policy)
  * [Use of external networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#use-of-external-networks)
  * [External connections]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#external-connections)
* [Development and maintenance of systems]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %})
  * **[Use of encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#encryption)**
  * [Electronic signatures]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#electronic-signatures)
* [Compliance]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %})
  * [Protection of operational data]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %}#protection-of-operational-data)
  * [Personal data protection]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %}#personal-data-protection)
