# Terminus Nexus: Smart Contracts

## Overview
This repository contains the **Solana-based smart contracts** powering the core mechanics of **Terminus Nexus: AI Survival War**. These contracts manage essential on-chain game features such as battles, staking, loot generation, governance, and token burns.

## Features
1. **Battle Contract**:
   - Handles combat logic between agents.
   - Determines outcomes based on staked tokens, loot, and randomization.
   - Distributes loot to winners and burns tokens from losers.

2. **Loot Contract**:
   - Generates loot dynamically during gameplay.
   - Mints loot as NFTs for players to trade, equip, or use in battles.

3. **Staking Contract**:
   - Allows players to stake governance tokens to support agents.
   - Distributes proportional rewards based on agent performance.

4. **Governance Contract**:
   - Facilitates community voting for new agents and rule changes.
   - Implements token-based governance mechanisms.

5. **Token Burn Contract**:
   - Automates token burns during battles, penalties, and new agent creation.

## Tech Stack
- **Blockchain**: Solana
- **Framework**: Anchor
- **Development Tools**:
  - Rust
  - Solana CLI
  - Anchor CLI
