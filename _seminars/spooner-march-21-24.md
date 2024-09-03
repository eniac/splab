---
layout: seminar
title: "Proof-carrying data from arithmetized random oracles"
speaker: "Nick Spooner"
date: "2024-03-21"
abstract: "Proof-carrying data (PCD) is a powerful cryptographic primitive that allows mutually distrustful parties to perform distributed computation in an efficiently verifiable manner. Known constructions of PCD are obtained by recursively-composing SNARKs or related primitives. SNARKs with desirable properties such as transparent setup are constructed in the random oracle model. However, using such SNARKs to construct PCD requires heuristically instantiating the oracle and using it in a non-black-box way. [CCS22] constructed SNARKs in the low-degree random oracle model, circumventing this issue, but instantiating their model in the real world appears difficult. In this paper, we introduce a new model: the arithmetized random oracle model (AROM). We provide a plausible standard-model (software-only) instantiation of the AROM, and we construct PCD in the AROM,given only a standard-model collision-resistant hash function. Furthermore, our PCD construction is for arbitrary-depth compliance predicates. We obtain our PCD construction by showing how to construct SNARKs in the AROMfor computations that query the oracle, given an accumulation scheme for oracle queries in the AROM. We then construct such an accumulation scheme for the AROM. We give an efficient “lazy sampling” algorithm (an emulator) for the ARO up to some error. Our emulator enables us to prove the security of cryptographic constructs in the AROM and that zkSNARKs in the ROM also satisfy zero-knowledge in the AROM. The algorithm is non-trivial, and relies on results in algebraic query complexity and the combinatorial nullstellensatz."
speaker_website: "https://spooner.cc/"
paper: "https://eprint.iacr.org/2023/587.pdf"
---