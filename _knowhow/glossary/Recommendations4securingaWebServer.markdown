---
layout: article
title:  "Recommendations to secure a Web server"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
ref: glossaryrecomm4securingwebserver
lang: en
---
Basic Considerations
--------------------
A web server is a server permanently connected to the Internet. It is, therefore, advisable to follow the [recommendations for securing servers connected to the Internet]({% link _publications/recommendationsecuring/Recommendations4securingServerConnectedInternet.markdown %}).

Security Measures
-----------------

1.	Web servers have the distinction of serving web applications on the Internet. The level of security of these applications is often little or not known. It is, therefore, important to prevent or even limit the extent of the damage in the event of compromise:
	1.	ensure that your applications have a maximum degree of security by carrying out penetration tests beforehand;
	2.	install an application firewall like Microsoft Forefront, Modsecurity or Naxsi for IIS, Apache, and Nginx respectively;
	3.	limit the rights of the web server application, if possible, contain it in a restricted execution space;
	4.	consider applying [good practice rules]({% link _publications/recommendationsecuring/SecurityChecklistForPHPWebApplications.markdown %}) to your developers.
2.	Some web applications allow files of any type to be uploaded to the server. It is important to test the downloaded files with an antivirus.
3.	When using databases on the server itself, consider restricting its access to local users.
4.	Consider installing modules protecting denials of service.
5.	Check your log files regularly to find any anomalies.
