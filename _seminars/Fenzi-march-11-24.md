---
layout: seminar
title: "UC-Security of practical zkSNARKs"
speaker: "Giacomo Fenzi"
date: "2024-03-11"
abstract: "The universal composability (UC) framework is a “gold standard” for security in cryptography. UCsecure protocols achieve strong security guarantees against powerful adaptive adversaries, and retain these guarantees when used as part of larger protocols. Zero knowledge succinct non-interactive arguments of knowledge (zkSNARKs) are a popular cryptographic primitive that are often used within larger protocols deployed in dynamic environments, and so UC-security is a highly desirable, if not necessary, goal. In this paper we prove that there exist zkSNARKs in the random oracle model (ROM) that unconditionally achieve UC-security. Here, “unconditionally” means that security holds against adversaries that make a bounded number of queries to the random oracle, but are otherwise computationally unbounded. Prior work studying UC-security for zkSNARKs obtains transformations that rely on computational assumptions and, in many cases, lose most of the succinctness property of the zkSNARK. Moreover, these transformations make the resulting zkSNARK more expensive and complicated. In contrast, we prove that widely used zkSNARKs in the ROM are UC-secure without modifications. Weprove that the Micali construction, which is the canonical construction of a zkSNARK, is UC-secure. Moreover, we prove that the BCS construction, which many zkSNARKs deployed in practice are based on, is UC-secure. Our results confirm the intuition that these natural zkSNARKs do not need to be augmented to achieve UC-security, and give confidence that their use in larger real-world systems is secure."
speaker_website: "https://gfenzi.io/"
paper: "https://eprint.iacr.org/2024/724.pdf"
---
