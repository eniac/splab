---
layout: seminar
title: "Proofs for Deep Thought: Accumulation for large memories and deterministic computations"
speaker: "Jessica Chen"
date: "2024-04-22"
abstract: "An important part in proving machine computation is to prove the correctness of the read and write operations performed from the memory, which we term memory-proving. Previous methodologies required proving Merkle Tree openings or multi-set hashes, resulting in relatively large proof circuits. We construct an efficient memory-proving Incrementally Verifiable Computation (IVC) scheme from accumulation, which is particularly useful for machine computations with large memories and deterministic steps. In our scheme, the IVC prover PIVC has cost entirely independent of the memory size T and only needs to commit to approximately 15 field elements per read/write operation, marking a more than 100X improvement over prior work. We further reduce this cost by employing a modified, accumulation-friendly version of the GKR protocol. In the optimized version, PIVC only needs to commit to 6 small memory-table elements per read/write. If the table stores 32-bit values, then this is equivalent to committing to less than one single field element per read and write. Our modified GKR protocol is also valuable for proving other deterministic computations within the context of IVC. Our memory-proving protocol can be extended to support key-value stores."
paper: "https://eprint.iacr.org/2024/325.pdf"
---
