# IOTA reference implementation overview

**The IRI (IOTA reference implementation) is open-source Java software for the IOTA protocol. This software currently runs on nodes in the [public IOTA networks](root://getting-started/0.1/network/iota-networks.md), where clients can transfer the IOTA token among each other.**

IRI nodes are the core of an IOTA network, and are responsible for the following functions:

- Validate transactions
- Store valid transactions in a ledger
- Allow clients to interact with the IRI and have their transactions appended to the ledger

By running your own IRI node you have the following benefits:

- You have direct access to an IOTA network instead of having to connect to someone else's IRI node
- You help the IOTA network to become more distributed by adding to the number of ledgers and validating the transactions in your [neighbor's](root://getting-started/0.1/network/nodes.md#neighbors) ledgers

## Limitations

IRI receives transactions and records them in a ledger, it doesn't create or sign transactions. To create or sign transactions, you must use client software such as [Trinity](root://wallets/0.1/trinity/introduction/overview.md) or a [client library](root://client-libraries/0.1/introduction/overview.md) and send the transactions to an IRI node.

## Blog posts

Read the following blog posts about IRI:

- [Introducing Local Snapshots](https://blog.iota.org/coming-up-local-snapshots-7018ff0ed5db)
- [Networking Rewrite](https://blog.iota.org/iri-1-8-0-with-networking-rewrite-9d1e2be001e7)

## Repository

Go to the IRI source code on [Github](https://github.com/iotaledger/iri).

## Discord channels

[Join our Discord channel](https://discord.iota.org) where you can:

- Take part in discussions with IOTA developers and the community
- Ask for help
- Share your knowledge to help others

We have the following channels for IRI:

- **#iri-dev:** A read-only channel where developers discuss topics and where any GitHub updates are displayed

- **#iri-discussion:** An open channel where anyone is free to discuss IRI

- **#fullnodes:** An open channel where anyone is free to discuss node software

- **#nodesharing:** An open channel where anyone is free to find neighbors

## Next steps

[Run IRI](../how-to-guides/install-iri.md) to get started.

