Weaver
======

A cloud-based PGP Web of Trust manager written in Node.js that implements an authoritative key server (AKS - https://npmjs.org/package/aks) and makes use of OpenPGP.js (http://openpgpjs.org/) to provide robust key managment tools.  

Weaver will also expose a services layer that will allow the integration of third-party tools such as browser plugins and eliminate the need to copy sets of keys between multiple computers that may be used for signing and encrypting/decrypting emails, documents or other objects using PGP with the overall goal of helping make PGP ubiquitous in terms of a secure way to communicate with others.

Additionally, Weaver will interact with a browser extension (Chrome/Firefox) in order to facilitate the secure retrieval of keys for import into local key stores.

A number of privacy concerns will also be addressed, as detailed in the following list:

1. Secondary encryption of stored key-pair information to a secret only known to the owner of that information in order to prevent a host from being compelled to turn a users data over

2. A user will be able to remove all of their data quickly with a single click  


