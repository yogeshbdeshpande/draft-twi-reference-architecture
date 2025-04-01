---
title: Trusted Workload Identity Reference Architecture
abbrev: TWI Reference Architecture
docname: draft-twi-reference-architecture-latest
category: info
ipr: trust200902
area: Security
workgroup: WIMSE

stand_alone: yes
pi:

  rfcedstyle: yes
  toc: yes
  tocindent: yes
  sortrefs: yes
  symrefs: yes
  strict: yes
  comments: yes
  text-list-symbols: -o*+
  docmapping: yes

author:

-
  name: Mark Novak
  org: JP Morgan
  email: mark.novak@outlook.com

-
  name: Yogesh Deshpande
  org: arm
  email: Yogesh.Deshpande@arm.com

informative:
  RFC9334: rats-arch


--- abstract
Technological advancement coupled with security concerns demands more and more use cases, that require data-in-use protections.
In addition regulatory bodies around the world increasingly require data-in-use protection and privacy enhancing technologies.
As these advanced technologies are been deployed, challenge remains how to identify the workloads and put trust behind them?
This draft will address the core issue of managing a trustworthy workload identity meeting Confidential Computing requirements.


--- middle

# Introduction

To be filled

# Conventions and Definitions

{::boilerplate bcp14}

This document uses terms and concepts defined by the WIMSE and RATS architecture. For a complete glossary, see {{Section 4 of -rats-arch}}.


## Glossary
{: #sec-glossary }

This document uses the following terms:

# TWI Use Cases
Following are some of the use cases demanding trustworthy workload identity.

1. A ML Model Owner (acting as Relying Party) wants to deploy its Workload with a unique identity in a privacy
preserving manner. It needs to ensure that the deployed workload is operating in an environment with certain
security guaranetees, such as isolated from cloud hosting environment and can be periodically attested.


2. A Worklaod operating as a deployed lambda running in an isolated environment.

# Core Requirements

## Workload composition

## Workload lifespan

##

# TWI Reference Architecture
{: #sec-ref-architecture }

This sections describes in detail, the Reference Architecture for Trusted Workload Identity system

## Assumptions

## Roles in the TWI Eco-System
The following sub-sections describe the various roles that exist in the TWI eco-system.

### Verifier

### Identity Provider

### Credential Issuer

## Reference Architecture




# Security Considerations

<cref>TODO</cref>

# IANA Considerations

## CBOR Tag Registrations


# Acknowledgements


<cref>TODO</cref>
