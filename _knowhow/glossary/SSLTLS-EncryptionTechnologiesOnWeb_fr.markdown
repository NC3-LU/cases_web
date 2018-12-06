---
layout: article
title:  "SSL/TLS - les technologies de chiffrement sur la toile"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
ref: glossaryssltlsontheweb
lang: fr
---

## En quelques mots
L'ensemble de technologies qui forment le SSL (Secure Socket Layer) a initialement été développé par la société Netscape pour son navigateur. La version 3 fût reprise et étendue par l'IETF (Internet Engineering Task Force) pour le développement et la standardisation de TLS (Transport Layer Security). Pour être exact il faudrait d'ailleurs parler de TLS au lieu de SSL, mais ce dernier est resté dans le vocabulaire usuel comme le terme le plus utilisé pour désigner les méthodes de chiffrement utilisées principalement pour les technologies web.
Concrètement ces techniques ajoutent une couche de chiffrement au protocole «http» et le transforment en «https», où la lettre «s» ajoutée signifie «secure». Cela signifie que la communication est chiffrée depuis le navigateur jusqu'au serveur web.

## Certificats
Les sites voulant offrir la possibilité de chiffrer la communication doivent impérativement se doter d'un certificat. Un certificat est un ensemble de données cryptographiques et d'informations d'identité. Le «https» garantit donc non seulement le chiffrement de la communication mais aussi l'identité du site.

Les certificats utilisés par «https» respectent la norme X509. Un tel certificat contient entres autres les informations suivantes :

* le nom du serveur pour lequel ce certificat à été créé. (p.ex : www.cases.lu) ;
* le nom de l'émetteur du certificat. (p. ex. LuxTrust SA) ;
* la date à partir de laquelle le certificat est valide et la date à partir de laquelle il sera considéré comme étant expiré ;
* la clé publique du serveur, ainsi que le nom de l'algorithme avec lequel s'utilise cette clé ;
* la signature de l'émetteur du certificat, ainsi que le nom de la méthode utilisée pour la générer.

Comme pour une carte d'identité, qui est émise et certifiée par les différents États, le certificat SSL doit être signé de manière digitale par une autorité de certification qui fera office d'émetteur du certificat. La signature d'un certificat est vérifiée par le navigateur à l'aide du certificat de l'autorité de certification, qui est appelé certificat racine. Tous les navigateurs contiennent un grand nombre de certificats racines.

Un navigateur mettra en garde les internautes en cas de :

* expiration du certificat ;
* non concordance entre le nom de domaine du site est le nom utilisé dans le certificat (un certificat pour www.cases.lu ne peut pas être utilisé pour www.etat.lu) ;
* signature par une autorité inconnue (risque d'usurpation de nom de domaine) ;

## Confiance et sécurité
Contrairement à la croyance populaire et bien que souvent le terme «site sécurisé» soit utilisé, le SSL ne garantit pas la sécurité d'un site web, qui pourrait contenir des [vulnérabilités]({% link _knowhow/glossary/Vulnerabilities_fr.markdown %}),  mais bien l'identité du site et la sécurité de la communication.

Par exemple, si vous utilisez votre site de web banking usuel, le SSL vous garantit que personne sur le réseau ne pourra lire votre mot de passe, ni voir vos transactions. De plus, le certificat vous garantira que vous êtes bien sur le bon site. En revanche il ne garantira pas que le site visité est honnête ni qu'il ne présente pas de failles de sécurité.
