# Lumina Network Backend & Contracts

This repository contains the Lumina Network ecosystem, including the Node.js backend API and the Soroban Rust smart contracts.

- `/backend`: Node.js Express API for managing vesting schedules, claims, and providing off-chain analytics.
- `/contracts`: Soroban (Rust) smart contracts for on-chain vesting enforcement.
- `/docs`: Detailed implementation summaries, architecture guides, and API documentation.
- `/kubernetes`: K8s deployment manifests for scalable infrastructure.
- `/scripts`: Utility scripts for deployment, backups, and maintenance.

See [DOCUMENTATION.md](./DOCUMENTATION.md) for the complete documentation, including API reference, architecture guides, implementation summaries, and deployment guides.

## Getting Started

### Smart Contracts (Rust)
```bash
cd contracts && cargo test
```

### Backend (Node.js)
```bash
cd backend && npm install && npm start
```

## License
MIT