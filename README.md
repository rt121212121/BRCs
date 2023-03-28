# BRCs: Bitcoin Request for Comments

BRCs (Bitcoin Request for Comments) is a repository of standards, templates, and protocols related to the Bitcoin network. The goal of BRCs is to provide a platform for proposing and discussing potential standards without overhead and friction. The goal for this repository is to be able to host everything in one place so that things are easy to find, reference, and implement.

Read more about areas of interest on [OpenStandards.cash](https://openstandards.cash)

## Background

BRCs aim to provide a less formal and less strict process for proposing and discussing potential standards, templates, and protocols related to the Bitcoin network. BRCs will serve as an open platform for discussing and refining proposals, with the ultimate goal of promoting interoperability and standardization within the Bitcoin ecosystem.

## Structure

The BRCs repository is organized into directories, each representing a different category of proposal. Categories may include, but are not limited to:

- Transaction Templates
- Bitcoin Script Templates
- Protocol Standards

Each proposal should be written as a markdown file and should loosely adhere to the following:

- **Title:** A descriptive title for the standard being defined.
- **Author(s):** Who wrote the standard and where did it come from? How can they be reached?
- **Abstract:** A brief description of the proposed standard or template.
- **Motivation:** The reasoning behind the proposal and why it is needed.
- **Specification:** A detailed technical specification of the proposal.
- **Implementations:** Information on how the proposal has been or can be implemented.
- **References:** Any relevant literature or external resources related to the proposal.

**Note** that additional relevant content, identifiers or other information may be added to the document. Documents that already existed before the repository may not follow these requirements.

Things that help depict and understand the document, such as media, may also be added in a media subdirectory where appropriate.

Refer to the [Banana-Powered Bitcoin Wallet Control Protocol](./EXAMPLE.md) for a fun example template you can copy when proposing your own standards.

## Standards

BRC | Standard
-----|------------------
0    | [Banana-Powered Bitcoin Wallet Control Protocol](./EXAMPLE.md)
1    | [Transaction Creation](./wallet/0001.md)
2    | Data Encryption and Decryption
3    | Digital Signature Creation
4    | Input Redemption
5    | HTTP Wallet Communications Substrate
6    | XDM Wallet Communications Substrate
7    | Window Wallet Communication Substrate
8    | Transaction Envelopes
9    | Simplified Payment Verification
10   | TSC Merkle Proof Standard Format
11   | TSC Proof Format with Heights (Tone)
12   | Raw Transaction Format
13   | TXO Transaction Object Format
14   | [Bitcoin Script Binary, Hex and ASM Formats](./scripts/0014.md)
15   | [Bitcoin Script Assembly Language](./scripts/0015.md)
16   | [Pay to Public Key Hash](./scripts/0016.md)
17   | [Pay to R Puzzle Hash](./scripts/0017.md)
18   | [Pay to False Return](./scripts/0018.md)
19   | [Pay to True Return](./scripts/0019.md)
20   | [Pay to Push Drop](./scripts/0020.md)
21   | [Push TX](./0021.md)
22   | Confederacy Data Synchronization
23   | Confederacy Host Interconnect Protocol
24   | Confederacy Lookup Services
25   | User Management Protocol
26   | Universal Hash Resolution Protocol
27   | Direct Payment Protocol (DPP)
28   | Paymail Payment Destinations
29   | Simple Authenticated BSV P2PKH Payment Protocol
30   | Extended Format (Siggi and Simon)
31   | Authrite Mutual Authentication
32   | [BIP32 Key Derivation Scheme](./key-derivation/0032.md)
33   | PeerServ Message Relay Interface
34   | PeerServ Host Interconnect Protocol
35   | PeerServ Host Message Synchronization Protocol
36   | Format for Bitcoin Outpoints (Confederacy Lookup Format)
37   | Format for Bitcoin Outputs with Spending Instructions
38   | User Wallet Data Format
39   | User Wallet Data Format Encryption Extension
40   | User Wallet Data Synchronization
41   | PacketPay HTTP Payment Mechanism
42   | [Sendover Key Derivation Scheme](./key-derivation/0042.md)
43   | [Security Levels, Protocol IDs, Key IDs and Counterparties](./key-derivation/0043.md)
44   | [Admin-reserved and Prohibited Key Derivation Protocols](./key-derivation/0044.md)
45   | Definition of UTXOs as Bitcoin Tokens
46   | Wallet Transaction Output Tracking (Output Baskets)
47   | [Bare Multi-Signature](./scripts/0047.md)

## Contributing

Contributions to BRCs are welcome and encouraged. To propose a new standard or template, simply create a new markdown file in the appropriate directory of the BRCs repository, following the structure outlined above. Once your proposal is complete, submit a pull request for review and discussion.

To participate in discussions about existing proposals, simply open an issue and make reference to the proposal.

## Iterative improvement

We believe in encouraging discussion and iterative improvement of proposals, resulting in incremental improvement within the bounds of the Bitcoin protocol. We welcome suggestions for improvement and are committed to working with contributors to improve proposals and ensure that they align with our guidelines.

**Note** that substantial revisions to standards (beyond fixing typos, adding context or wording) should go into a new standard that extends or revises the old one, so as not to disrupt existing implementations.

We look forward to your contributions and helping to create a world where transactions are seamlessly formed, and applications interact with each other with ease.

## License

Everything in this repository is subject to the [Open BSV License](https://github.com/bitcoin-sv/bitcoin-sv/blob/master/LICENSE).
