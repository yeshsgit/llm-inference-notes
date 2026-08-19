# LLM Inference Notes


43 pages of handwritten notes on [Reiner Pope's lecture](https://youtu.be/xmkSf5IS-zw?si=Pkn0BpqW8NqSMerK)

[Read the notes (PDF)](./llm-inference-notes-reiner-pope.pdf)


## Why these notes exist..
The content in the lecture is delivered superbly and it felt like an injustice not to try and understand it all. So, I worked through the lecture as if I were revising for an exam. I tried my best to cover all key concepts, derivations, intuition, and where I needed to do some extra reading, some background too. I hope sharing this might help others trying to understand this content.


## Contents

| Section | Pages | Episode timestamp |
|---|---|---|
| The impact of batch size on token cost and speed | 1–13 | 00:00:00 |
| Sparsity and model quality (Unified Scaling Laws) | 13–15 | 00:27:54 |
| How MoE models are laid out across GPU racks | 15–20 | 00:32:09 |
| Pipeline parallelism and micro-batching | 21–28 | 00:47:12 |
| Memory capacity vs bandwidth; why scale-up size matters | 27–29 | 01:03:37 |
| RL and overtraining (~100× beyond Chinchilla) | 30–34 | 01:18:59 |
| Deductions from API prices (context tiers, input vs output, caching) | 34–40 | 01:33:02 |
| Neural nets and cryptography (Feistel ciphers → RevNets) | 41–43 | 02:04:02 |


## Credit
These notes are based on Dwarkesh Patel's video [How GPT, Claude, and Gemini are actually trained and served – Reiner Pope](https://youtu.be/xmkSf5IS-zw?si=Pkn0BpqW8NqSMerK)

Dwarkesh makes loads of awesome videos like this. I definitely recommend checking out his channel!

Related resources:
- [Official transcript](https://www.dwarkesh.com/p/reiner-pope)
- [Dwarkesh's flashcards & practice problems](https://flashcards.dwarkesh.com/reiner-pope/)
- [The scaling book](https://jax-ml.github.io/scaling-book/) recommended in the episode for further study

If there are any mistakes, please let me know.
