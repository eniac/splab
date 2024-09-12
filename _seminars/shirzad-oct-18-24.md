---
layout: seminar
title: "Garuda and Pari: Faster and Smaller SNARKs via Equifficient Polynomial Commitments"
speaker: "Alireza Shirzad"
date: "2024-10-28"
speaker_website: "https://alireza-shirzad.github.io/"
paper: "https://eprint.iacr.org/2024/235"
abstract: "SNARK sare powerful cryptographic primitives that allow a prover to produce a succinct proof of a computation. Two key goals of SNARK research are to minimize the size of the proof and to minimize the time required to generate the proof. In this work, we present new SNARK constructions that push the frontier on both of these goals. Our first construction, PARI, is a SNARK that achieves the smallest proof size amongst all known SNARKs. Specifically, PARI achieves a proof size of just two group elements and two field elements, which, when instantiated with the BLS12-381 curve, totals just 160 bytes, smaller than that of Groth16 [Groth, EUROCRYPT ’16] and Polymath [Lipmaa, CRYPTO ’24]. Our second construction, GARUDA, is a SNARK that reduces proof generation time by supporting, for the first time, arbitrary “custom” gates and free linear gates. To demonstrate GARUDA’s performance, we implement and evaluate it, and show that it provides significant prover-time savings compared to both the state-of-the-art SNARKs (Groth16 and HyperPlonk [EUROCRYPT ’23]) Both constructions rely on a new cryptographic primitive: “equifficient” polynomial commitment schemes that enforce that committed polynomials have the same representation in particular bases. We provide both rigorous security definitions for this primitive as well as efficient constructions for univariate and multilinear polynomials."
---
