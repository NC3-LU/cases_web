---
layout: publication-list
title:  "Cloud computing"
menutitle: "Cloud computing"
logo:
date:  2017-11-06 00:00:00 +0100
short: "This file addresses the key points of cloud computing, thanks to him you will master this subject"
categories: securing
toc: true
---
<h3 class="titre-page" id="in-brief">In brief</h3>
Cloud computing covers different ways for companies to outsource their IT resources and access them through a network.
Generally these services, especially if they are managed by a third party, are hosted in data centres over which the user has little control.

Originally cloud computing described a cluster of servers sharing their tasks. It therefore involves pooling resources that are generally under-utilised. Each user typically uses only a fraction of total capacity but may at times benefit from the full capacity of a shared resource. This technology makes it possible to adapt, without major investment, the IT needs of a company flexibly.

The infrastructure of e-commerce sites is a good example of cloud computing. They often experience a spike in use around Christmas. But for the rest of the year, far fewer resources are needed. To cope with the 'Christmas peak', e-commerce sites have a major incentive to lease their additional capacity for that period only, so that they do not have to finance oversized machines all year round. If they opt for the latter solution, they can also become cloud service **providers**.

It is no coincidence that one of the biggest players cloud in computing is Amazon, which decided to lease and extend its infrastructure to third parties.

<h3 class="titre-page" id="types-of-cloud">Types of cloud</h3>
Cloud computing generally involves the provision of several types of service:

**IaaS**: Infrastructure as a Service: The cloud provider provides an infrastructure, i.e. a means of communication, a predefined number of processors, RAM and storage space. The customer must install and manage its own operating systems and applications. If required, the application can request more speed, processors, RAM or storage space. The customer therefore has the advantage of an infrastructure that can react dynamically to peak needs without funding the infrastructure year-round. Generally the customer only pays for what is needed – the famous "pay as you go".

**PaaS**: Platform as a Service: As in the IaaS model, the cloud provider makes the infrastructure available to the customer and adds the operating system layer and a production environment such as web servers, database server and so on. In this case, the customer only needs to set up its application on the infrastructure because everything else is managed by the cloud provider.

**SaaS**: Software as a service: The cloud provider supplies the customer with the application to be used. The customer therefore does not need to manage anything and can focus on just using the application provided.

<h3 class="titre-page" id="distinctive-features-of-the-cloud">Distinctive features of the cloud</h3>
 
Legislation
There is no specific legislative framework for cloud computing in Europe or Luxembourg. As noted in the introduction, Cloud Computing is a convergence of several online services existing elsewhere. These services themselves are for the most part covered by specific legislative aspects (e-commerce, personal data protection, archiving, etc.), so Cloud Computing is at the confluence of a host of regulations and laws.

Obviously, any obligations existing in Luxembourg for certain industries, such as the financial sector, remain relevant to Cloud Computing. More generally, all legislation applicable to personal data protection remains valid for companies seeking to rely on a cloud computing solution. When outsourcing part or all of its data storage or data processing infrastructure, a company remains responsible for the integrity and use of the same data. Companies wishing to migrate to the cloud are therefore recommended to read the contracts (including SLAs) for the cloud service they have chosen with the utmost care. In particular, the geographical location of the data storage sites is a key element, as these storage sites may be set up in countries that do not comply with European and/or Luxembourg obligations.

Finally, intellectual property should be mentioned. Whether it is to comply with confidentiality commitments to third parties or the secrecy of methods developed within the company, subcontracting IT activity potentially means exposing the company to risks in terms of confidentiality compliance and monitoring. There are technical solutions such as encryption, which are discussed later in this document. They should not be underestimated.

<h3 class="titre-page" id="data-security">Data security</h3>

### Data transmission:
It should be confirmed that data sent to the cloud is protected against any loss of confidentiality. An encrypted connection (SSL) must therefore be used or data must be encrypted before being transferred to the cloud.

The transmission protocols used for backups generally manage data availability and integrity very well. The data is not changed or lost during transmission. Conversely, if the cloud is used as a collaborative platform and if documents are edited using web applications, loss of connectivity can lead to data losses.

### Data storage:
In the cloud, you are not necessarily the only person who can access your data. If you hire the services of a provider, the provider also has access to your data because it has to manage the infrastructure. In the event of problems, mishandling or the exploitation of vulnerabilities by malicious individuals, others may also have access to your data. Such cases have already occurred at online storage providers.

Some providers offer encryption, but at times it is difficult to determine if you're the only person who can decrypt your data. Do not be dazzled by over-complicated terms – just make sure you are the only one holding the encryption keys.

Otherwise, it is preferable not to trust anybody else and encrypt your data on your local workstations before sending it to the cloud. But this all depends on how you use the data: if you store non-confidential data and you want to take advantage of search capabilities in the text, you will need unencrypted data.

When several people need to work on documents stored on the cloud, sharing passwords between people or machines may be useful. This can be done using a database of passwords. The passwords database must be properly protected using encryption to avoid the passwords appearing on search engine results pages.

### Data access:
Based on the classification level of data stored in the cloud, it must be confirmed that no authorised person is able to access, delete, edit or divulge the data. The suitability of authentication mechanisms must, therefore, be confirmed:

* Username and password: strong passwords must be chosen and properly protected. It is advisable to change them regularly. For non-critical data.
* Strong authentication:
  * username, password and one-time password sent by SMS or generated on a smartphone,
  * username, password and one-time password generated by a dedicated device (token),
  * username, password and password and certificate (smart card, customer certificate) or software key.

### Data destruction
At the end of the contract when you want to delete old backups, it is important to ensure that your data is destroyed and no longer accessible to unauthorised persons. The best way to guarantee this is to encrypt the data again.

<h3 class="titre-page" id="availability">Availability</h3>
Some providers guarantee a specific level of availability, while others do not make any specific commitment, except "best effort".

So, a provider offering availability of 98.5% can have 5.5 days' downtime a year (including 5.5 consecutive days) without violating the contracts. It is essential to perform this calculation to assess whether or not you can survive such a failure. Of course, higher availability costs more than average or low availability.  The best data centres guarantee up to 99.99% availability (less than one hour of downtime a year).

The availability of cloud solutions is also conditioned by connectivity. A loss of connectivity at your company, ISP or cloud provider renders these services unavailable. Distributed denial of service (DDOS) attacks can also jeopardise an entire cloud infrastructure and affect you if one of your provider's customers becomes the target.

The availability of an asset within an entity is defined by the assurance that it is usable in terms of time and expected performance. Also think about the time needed to retrieve backups from an online service. This time-scale can become very long, even prohibitive, because of the lower speed allocated to you.
<h3 class="titre-page" id="connectivity">Connectivity</h3>
### Speed
Most cloud services guarantee a data speed to their customers. It is imperative that companies check that these speeds are sufficient for the use that will be made of them.

For a backup service, it is therefore vital to check the upstream speed and calculate how long the backup will take. On one side we have the bitrate offered by your ISP, on the other the bitrate offered by your cloud provider: the bottleneck will necessarily be defined by the smaller of these values:

| Backup volume | Upstream speed (ISP) | Bandwidth (cloud provider) | Duration |
--------------------------------------------------------------------------------
| 5 GB | 2.5 Mb/s | 2 Mb/s | 5000*8/2 = 20,000 seconds (5.5 hours) |
| 5 GB | 2.5 Mb/s | 2.5 Mb/s | 5000*8/2.5 = 16,000 seconds (4.4 hours) |
| 5 GB | 5 Mb/s | 10 Mb/s | 5000*8/5 = 8000 seconds (2.2 hours) |

### The amount of data transferred
Some cloud providers charge by the amount of data transferred. Check if this model is suitable for your needs.

<h3 class="titre-page" id="the-most-used-services">The most used services</h3>
> TO complete

<h3 class="titre-page" id="backups">Backups</h3>
Backups should not be confused with storage. Indeed, Luxembourg recently enacted a law on PSDCs, Digitisation and Archiving Service Providers, service providers in the field of electronic archiving.

Cloud backups are nothing more than the relocation of backed up data to another data centre. It is therefore necessary to check the security of the data during transmission, storage and, finally, destruction in the event of contract termination, deletion by users or bankruptcy of the cloud provider.

A backup can take all night, without disrupting production. Data must be restored as quickly as possible. So, make sure you have sufficient bitrate to download the data in a reasonable amount of time. To keep this time short, be sure to choose a good backup strategy involving local data storage and keeping data in the cloud for disasters like fire.

<h3 class="titre-page" id="synchronisation">Synchronisation</h3>
The synchronisation of different work tools is a recurring need. Instead of sending documents by unsecured email or using removable media, it is best to synchronise the data using a central service accessible to all.

There are many services offering these forms of collaboration for synchronisation. The required bitrate and the amount of data exchanged are generally lower than for backup services.

Documents are thus always available on the various synchronised work tools, because a complete copy is found on all platforms. Loss of availability of the cloud service does not result in all the data being lost, but in loss of the synchronisation option. Manual synchronisation via secure email or removable media is always possible.

Confidentiality needs are, however, very real since this generally involves current data, which could attract the interest of competitors or other malicious individuals. Encryption during transmission and storage on the cloud server is required. It is preferable for customers only to hold encryption keys to prevent unauthorised access through the cloud.

<h3 class="titre-page" id="collaborative-platform">Collaborative platform</h3>
When several people collaborate on the same documents, it is usually via a file server or a similar server within a company.

If the company does not want to maintain a file server or if several people from different companies, without access to the same file server, need to collaborate, online collaboration platforms can be used.

Everybody working on the same project has access to the same project space and can work on shared documents. There are two ways to do this:

* by downloading the document from the cloud server to the work tool and returning once the work is finished. In this case it is possible to use encryption controlled by the customers and unknown to the cloud operator.
* by using online tools provided for document processing. In this case the use of encryption resources by customers is not possible. This way of working, therefore, does not guarantee a high level of confidentiality.

Collaboration on a cloud platform can also pose a risk of availability. If the cloud is not accessible, the work documents are no longer available. If there is disaster in the cloud or during a downtime, there is a risk that all data will be lost. It is therefore vital to provide timely backup solutions outside the cloud, at the premises of one of the partners.

Managing access rights between rights holders can often be a problem. Check the granularity of the rights granted when choosing the supplier.

These collaboration platforms also offer other benefits such as calendars, mailboxes or other useful applications.

Often it is not possible to check data access logs.

<h3 class="titre-page" id="other-services">Other services</h3>
These include online services such as hosting of web sites or mailboxes, but it is also possible to go as far as virtualising the entire work environment. Some providers of virtual desktops can be accessed through a common browser.

The cloud offers tremendous opportunities and transforms IT into a service that can be rented according to need, thus making it possible for even small businesses to access technologies hitherto restricted to large businesses.

All these options obviously have a price and it is essential to evaluate the value of your data properly to ensure that the appropriate security measures are put in place.

<h3 class="titre-page" id="summary">Summary</h3>

| Technical specifications | | | | |
| Features | Authentication | Encryption | Availability | Bitrate |
-------------------------------------------------------------------
| Non-critical data backups | Strong password | SSL connection | Medium to strong | According to data volume and backup frequency |
| Critical data backups | 2-factor authentication / strong authentication | SSL connection | AND data encryption | Strong, especially if the data is urgent | High, if rapid data recovery is required |
| Synchronisation | According to the criticality of the data (see Backups) | According to the criticality of the data (see Backups) | Low or Medium | According to the volume of data to be  synchronised |
| File sharing | According to the criticality of the data (see Backups) | SSL connection | Shared key encryption if the data is critical | Medium to strong | According to the number of users and the volume of files to be shared |
| Collaborative work | According to the criticality of the data (see Backups) | SSL connection | Strong, to avoid data loss. Provide for local backups? | High, to allow simultaneous access to multiple users |
