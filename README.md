## Escrow-STX
A trustless escrow smart contract built with Clarity on the Stacks blockchain.
It ensures secure fund transfers between two or more parties without requiring a trusted intermediary.

## Features:
Create escrow agreements with STX
Fund escrow securely
Release funds only when conditions are met
Cancel escrow with refund option
Optional time-lock for dispute resolution
Technical Overview
Language: Clarity

## Core Functions:
create-escrow – initialize escrow with participants
fund-escrow – deposit STX into escrow
release – release funds to beneficiary
cancel – refund to sender if conditions unmet

## Installation & Usage
Clone repository:
git clone https://github.com/your-repo/escrow-stx.git
cd escrow-stx

## Deploy with Clarinet:
clarinet contract deploy escrow-stx

## Run tests:
clarinet test

## Roadmap
Add multi-sig support for escrow approvals
Integrate arbitration system
Expand asset support (NFTs, SIP-010 tokens)
Full security audit
