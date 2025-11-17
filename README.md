# ZK-Neura dApp (Beta)

ZK-Neura is a privacy-preserving health intelligence application built on Solana.  
It enables users to manage health records locally, perform private AI-assisted health analysis, and generate Zero-Knowledge Proofs for secure, verifiable interactions without exposing sensitive data.

This repository contains the official ZK-Neura frontend application.

---

## Overview

- Local-first health records tied to the user's Solana wallet  
- AI Health Check for private symptom analysis  
- Zero-Knowledge proof generation (commitment + nullifier)  
- Privacy-preserving verification workflows  
- Fast, responsive UI using modern Next.js  
- No centralized data storage

---

## Features

- Wallet authentication (Phantom, Solflare, Backpack)
- Local encrypted record storage
- AI-based health assessment with no data retention
- Proof Vault for commitment & nullifier management
- Client-side cryptography (SHA-256, AES-GCM)
- Works on web and mobile browsers

---

## Technology Stack

- Next.js 16  
- React 19  
- TailwindCSS v4  
- shadcn/ui  
- Zustand  
- Zod  
- WebCrypto API  
- Solana Web3.js  
- Vercel AI Gateway → GPT-4o-mini  

---

## Getting Started

### 1. Clone


git clone https://github.com/zk-neura/zkneura-dapp
cd zkneura-dapp

### 2. Install Dependencies
npm install

### 3. Environment Setup
cp .env.example .env.local


NEXT_PUBLIC_SOLANA_CLUSTER=devnet
VERCEL_AI_GATEWAY_URL=
OPENAI_API_KEY=

### 4. Start Development Server
npm run dev


The application runs at:
http://localhost:3000

Production Build
npm run build


Deployment via Vercel is recommended.

Project Structure
src/
  app/            # Routes (Next.js App Router)
  components/     # UI components
  lib/            # Helpers & libraries
  store/          # Zustand state management
  hooks/          # Custom hooks
  utils/          # Utilities & crypto helpers
  styles/         # Global styles
public/           # Static assets
docs/             # Internal documentation

Security Notes

ZK-Neura stores no medical data on servers.
All data remains local to the user's device, encrypted and wallet-scoped.
Always keep your wallet secure and back up your recovery phrase.
For vulnerability reports, contact:
security@zkneura.xyz
Contributing
Please read CONTRIBUTING.md for the development workflow, coding standards, and pull request guidelines.
License

Tis project is licensed under the MIT License.
