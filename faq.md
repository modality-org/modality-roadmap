# 🤔 Modality Q&A

## What is Modality?

Modality is an open source standard for verifiable contracts.

## What are verifiable contracts?

Verifiable contracts are a mechanism for ensuring the compliance of evolving constraints over data.

## How are verifiable contracts different from smart contracts?

Both smart contracts and verifiable contracts keep an append-only log of interactions. Both serve to restrict the nature of those interactions.

But only verifiable contracts provide native formal verification, ensuring that they work exactly as specified.

In contrast, smart contracts are implemented as computer programs and are not able to be formally verified. Any attempt at formal verification of smart contracts is critical limited because of this. Even the most expensive audits of smart contracts are known to miss critical bugs.

|                                       | Smart Contracts     | Verifiable Contracts       |
| :------------------------------------ | :-----------------: | :------------------------: |
| Does it need a blockchain?            | ✅                   | ❌                         |
| Does it keep an append-only log?      | ✅                   | ✅                         |
| Does it restrict interactions?        | ✅                   | ✅                         |
| Does it ensure correctness?           | ❌                    | ✅                         |
| Is it formally specified?             | ❌                    | ✅                         |

## Who started this project?

Modality was initially conceptualized by [Bud Mishra](https://scholar.google.com/citations?user=kXVBr20AAAAJ&hl=en) and [Foy Savas](https://foysavas.com).

Notably, [Bud was the first person to use formal verification to identity a hardware bug](https://discuss.modality.org/t/the-birth-of-model-checking/14/2). When formal verification for hardware was being initially developed, almost everyone considered it impossible or impractical. Today, formal verification is a standard part of the hardware development process.

## What is formal verification?

