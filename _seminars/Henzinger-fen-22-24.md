---
layout: seminar
title: " Private Web Search with Tiptoe"
speaker: "Alexandra Henzinge"
date: "2024-02-22"
abstract: "Tiptoe is a private web search engine that allows clients to search over hundreds of millions of documents, while revealing no information about their search query to the search engine’s servers. Tiptoe’s privacy guarantee is based on cryptography alone; it does not require hardware enclaves or non-colluding servers. Tiptoe uses semantic embeddings to reduce the problem of private full-text search to private nearest-neighbor search. Then, Tiptoe implements private nearest-neighbor search with a new, high-throughput protocol based on linearly homomorphic encryption. Running on a 45-server cluster, Tiptoe can privately search over 360 million webpageswith145core-secondsofservercompute,56.9MiB of client-server communication (74% of which occurs before the client enters its search query), and 2.7 seconds of end-toend latency. Tiptoe’s search works best on conceptual queries (“knee pain”) and less well on exact string matches (“123 Main Street, New York”). On the MS MARCO search-quality benchmark, Tiptoe ranks the best-matching result in position 7.7 on average. This is worse than a state-of-the-art, nonprivate neural search algorithm (average rank: 2.3), but is close to the classical tf-idf algorithm (average rank: 6.7). Finally, Tiptoe is extensible: it also supports private text-toimage search and, with minor modifications, it can search over audio, code, and more."
speaker_website: "https://people.csail.mit.edu/ahenz/"
paper: "https://eprint.iacr.org/2023/1438.pdf"
---
