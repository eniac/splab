---
layout: seminar
title: "NOPE: Strengthening Domain Authentication with Succinct Proofs"
speaker: "Zachary DeStefano"
date: "2024-11-11"
abstract: "Server authentication assures users that they are communicating with a server that genuinely represents a claimed domain. Today, server authentication relies on certification authorities (CAs), third parties who sign statements binding public keys to domains. CAs remain a weak spot in Internet security, as any faulty CA can issue a certificate for any domain.
I will describe NOPE [SOSP ’24], a new mechanism for server authentication that uses succinct proofs (for example, zero-knowledge proofs) to prove that a DNSSEC chain exists that links a public key to a specified domain. The use of DNSSEC dramatically reduces reliance on CAs, and the small size of the proofs enables compatibility with legacy infrastructure, including TLS servers, certificate formats, and certificate transparency. NOPE proofs add little performance overhead to clients, increasing the size of a typical certificate chain by about 10% and requiring just over 1 ms to verify.
NOPE's core technical contributions (which generalize beyond NOPE) include efficient techniques for representing parsing and cryptographic operations within succinct proofs, which reduce proof generation time and memory requirements by nearly an order of magnitude.
Joint work with Jeff J. Ma, Joseph Bonneau, and Michael Walfish"
paper: "https://nope-tools.org/nope.pdf"
speaker_website: "https://jbonneau.com/"
---
