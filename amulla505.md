# vApp Submission: ZkPassport

## Verification
```yaml
github_username: amulla505
discord_id: 272414287820226560
timestamp: "2025-08-25"
```

Developer

Name: A. Mulla

GitHub: @amulla505

Discord: amulla505#3930

Experience: 2 years in smart contract development, contributor to DeFi and identity-based zk projects.

Project
Name & Category

Project: ZkPassport

Category: identity

Description

ZkPassport is a decentralized identity vApp that allows users to prove attributes (age, residency, membership) without revealing their full identity or wallet details. It solves the problem of privacy-preserving verification for Web3 communities, DAOs, and DeFi platforms.

SL Integration

Uses Soundness Layer’s zk-proof verification to generate and validate selective identity proofs.

Leverages SL rollups for scaling credential checks at low cost.

Integrates with SL’s developer framework for building zero-knowledge circuits.

Technical
Architecture

Issuer Module: Trusted issuers (universities, DAOs, KYC providers) issue zk-based credentials.

User Wallet: Stores credentials locally, generates zk-proofs on request.

Verifier Contract: Smart contract on Soundness Layer validates proofs.

App Layer: dApp for users to share verifications (e.g., “I’m over 18” without sharing DOB).

Stack

Frontend: React + Tailwind

Backend: Node.js + GraphQL API

Blockchain: Soundness Layer + Ethereum (for bridging)

Storage: WALRUS for credential metadata, IPFS for encrypted proofs

Features

Selective Disclosure – Prove one attribute without exposing full ID.

DAO & DeFi Integration – Access gated services with zk-verifications.

Cross-App Identity – Credentials reusable across vApps in the ecosystem.

Timeline
PoC (3 weeks)

 Build issuer + verifier contracts

 Basic zk-circuit for age proof

 Simple dApp for demo

MVP (6 weeks)

 Full credential issuance system

 DAO/DeFi integration demo

 User dashboard with reusable credentials

Innovation

Most identity systems in Web3 either leak excessive data or rely on centralized attestations. ZkPassport is unique because it combines selective zk-disclosure with cross-app reusability, making identity both private and portable.

Contact

Preferred: TG (https://t.me/amulla505)

Updates will be shared via GitHub project board and Soundness Discord.
