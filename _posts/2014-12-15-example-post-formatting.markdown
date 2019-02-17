---
layout: post
title:  "Abstract"
date:   2019-01-05
description: Database outsourcing is becoming increasingly popular introducing a new paradigm, called
             database-as-a-service (DAS), where an organization’s database is stored at an external service
             provider.
---

Database outsourcing is becoming increasingly popular introducing a new paradigm, called
                                                            database-as-a-service (DAS), where an organization’s database is stored at an external service
                                                            provider. In such a scenario, security represented by data encryption, crypto key, and access
                                                            control are very important issues, especially if the data owner wishes to publish his data for
                                                            external use.

In this, first I present some approaches for the implementation of encrypting/decrypting data with less time and resources consuming also an implementation of access control through selective encryption on the client side in a cloud environment. The focus of this paper is that the presentation
of the project results, which demonstrate the applicability of my proposal. Companies need new mechanisms to control access to the outsourced data and allow users to query the encrypted data without revealing sensitive information to the cloud provider. I will introduce methodologies used on the data stored in the cloud server (Backend), where any administrative actions (such as updating access rights or adding/deleting users) do not require re-distributing keys or re-encryption of data.

In another word, cryptographic solutions refer to protection, storage, back up and administration of cryptographic keys is the key management. Encryption techniques ensure the confidentiality of data, if and only if, encryption/decryption keys are accessible only to authorized entities. Therefore, the cryptographic keys used for encryption of data should be protected from malicious administrators or software hackers in an untrusted third-party service environment like public cloud databases. The problem is that a single enterprise may end up using several different and possibly incompatible encryption algorithms to protect sensitive data. Subsequently, huge numbers of cryptographic keys are generated which those in turn needed to be protected and used efficiently also the size of the encrypted data increasing depending on the key size which consuming big storage in the cloud database.
