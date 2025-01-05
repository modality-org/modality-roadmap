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

## What is formal verification?
