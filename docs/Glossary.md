---
title: CA/Browser Forum Glossary and Definitions Guidelines

subtitle: Version 1.0.0
author:
  - CA/Browser Forum

date: XX-XXX-2025  

copyright: |
  Copyright 2025 CA/Browser Forum

  This work is licensed under the Creative Commons Attribution 4.0 International license.
---

# Introduction

This Glossary is intended as a glossary document encapsulating a set of definitions for terms used within the CA/Browser Forum and its Guidelines.

## Overview

**Recommendations for CA/Browser Forum Working Groups**

The Definitions and Glossary Working Group recommends that each CA/Browser Forum Working Group incorporate this Glossary within the documents produced by the Working Groups by reference. 

Additionally it is recommended, but not required, to reference the latest version of this Glossary as stated on https://www.cabforum.org/, thereby aligning potential requirements stated in multiple CA/Browser Forum documents at the same time.

**Defined Term Priority**:

In the case of a conflict between a capitalized term specified within this Glossary and a capitalized term specified within a document produced by a CA/Browser Forum Working Group, the capitalized term specified within the applicable CA/Browser Forum Working Group document SHALL take precedence.

## Document name and identification

### Revisions

| **Ver.** | **Ballot** | **Description** | **Adopted** | **Effective** |
|-|-|-----|--|--|
| 1.0 | DG-001 | Original Version Adopted | XX-XXX-25 | XX-XXX-25 |


### Definitions

**Accounting Practitioner**: A certified public accountant, chartered accountant, or a person with an equivalent license within the country of the Applicant's Jurisdiction of Incorporation or Registration or any jurisdiction where the Applicant maintains an office or physical facility; provided that an accounting standards body in the jurisdiction maintains full (not "suspended" or "associate") membership status with the International Federation of Accountants.

**Applicant**: The natural person or Legal Entity that applies for (or seeks renewal of) a Certificate. Once the Certificate is issued, the Applicant is referred to as the Subscriber. For Certificates issued to devices, the Applicant is the entity that controls or operates the device named in the Certificate, even if the device is sending the actual certificate request.

**Audit Period**: In a period-of-time audit, the period between the first day (start) and the last day of operations (end) covered by the auditors in their engagement. (This is not the same as the period of time when the auditors are on-site at the CA.).

**Audit Report**: A report from a Qualified Auditor stating the Qualified Auditor’s opinion on whether an entity’s processes and controls comply with the mandatory provisions of these Requirements.

**Certificate**: An electronic document that uses a digital signature to bind a public key and an identity.

**Certificate Management System**: A system used by a CA or Delegated Third Party to process, approve issuance of, or store certificates or certificate status information, including the database, database server, and storage.

**Certificate Policy**: A set of rules that indicates the applicability of a named Certificate to a particular community and/or PKI implementation with common security 
requirements.

**Certificate Revocation List**: A regularly updated time-stamped list of revoked Certificates that is created and digitally signed by the CA that issued the Certificates.

**Certificate System**: A system used by a CA or Delegated Third Party to access, process, or manage data or provide services related to performing:

   1. identity validation;
   2. identity authentication;
   3. account registration;
   4. certificate application;
   5. certificate approval;
   6. certificate issuance;
   7. certificate revocation;
   8. generation and signing of authoritative certificate status; or
   9. key escrow.

**Delegated Third Party**: A natural person or Legal Entity that is not the CA but is authorized by the CA, and whose activities are not within the scope of the appropriate CA audits, to assist in the Certificate Management Process by performing or fulfilling one or more of the CA requirements found herein.

**Delegated Third Party System**: Any part of a Certificate System used by a Delegated Third Party while performing the functions delegated to it by the CA.

**Glossary**: The CA/Browser Forum Glossary and Definitions as outlined in this document.

**Key Pair**: The Private Key and its associated Public Key.

**Multi-Factor Authentication**: An authentication mechanism consisting of two or more of the following independent categories of credentials (i.e. factors) to verify the user’s identity for a login or other transaction:

   1. something the user knows (knowledge factor);
   2. something the user has (possession factor); and
   3. something the user is (inherence factor).

Each factor is independent of the other(s).

**Online Certificate Status Protocol**: An online Certificate-checking protocol that enables relying-party application software to determine the status of an identified 
Certificate. 

**Private Key**: The cryptographic key of an asymmetric Key Pair that is kept secret by the holder of the Key Pair. It may be used to create digital signatures and/or to decrypt data that were encrypted by the corresponding Public Key.

**Public Key**: The cryptographic key of an asymmetric Key Pair that can be made public without compromising the security of the Key Pair. It may be used to verify digital signatures and/or to encrypt data that can be decrypted by the corresponding Private Key.

**Risk Assessment**: A formal process that:

   1. Identifies and documents foreseeable internal and external threats to the CA Infrastucture that could result in:
      * unauthorized access to the CA Infrastructure;
      * disclosure of data stored in the CA Infrastructure;
      * misuse of the CA Infrastructure; or
      * unapproved alteration or destruction of any part of the CA Infrastructure;
   2. Assesses and documents the likelihood and potential damage of each identified threat, taking into consideration minimally the sensitivity and criticality of the CA Infrastructure; and
   3. Assesses and documents the sufficiency of the policies, procedures, controls, information systems, technology, and other arrangements that the CA has in place to counter each identified threat.

**Root CA Certificate**:  A self-signed and self-issued certificate where:

   1. the issuer and subject of the certificate are the same; and
   2. the digital signature of the certificate is:
      * generated using the Private Key of a Key Pair whose corresponding Public Key is bound to the certificate; and
      * verified using the Public Key contained in the certificate.

**Root CA Private Key**: The Private Key associated with a Root CA Certificate.

**Root CA System**: A system used to:

   1. generate a Key Pair whose Private Key is or will be a Root CA Private Key;
   2. store a Root CA Private Key; or
   3. create digital signatures using a Root CA Private Key.
