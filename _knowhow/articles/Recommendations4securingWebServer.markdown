---
layout: articlesmall
title:  "Recommendations for securing a web server"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
---
## Basic considerations
A web server is a server that is constantly connected to the Internet. It is therefore advisable to follow the recommendations to secure servers connected to the Internet.

## Security measures

1. Web servers have the specific function of serving web applications on the Internet. The security level for these applications is often little known or not known at all. It is therefore important to prevent, or to limit the scope of, damage if they are compromised:
  1. ensure your applications have the maximum possible security by carrying out penetration tests beforehand;
  2. install an application firewall such as Microsoft Forefront, Modsecurity or Naxsi for IIS, Apache and Nginx respectively;
  3. limit the web server application rights – if possible hold it in a restricted execution area;
  4. remember to apply your developers’ best practice.
2. Some web applications enable downloads of any kind of file onto the server. It is important to test files downloaded in this way using anti-virus software.
3. If you are using databases on the server itself, consider restricting access to local users.
4. Think about installing modules protecting against denial of service.
5. Check your log files regularly for anomalies.
