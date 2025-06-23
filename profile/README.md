# d-verse

**d-verse** is a local-first, peer-to-peer framework for building **trust-aware applications** that work without cloud platforms, centralized servers, or blockchain dependencies.

It enables developers to build systems where logic is portable, identities are cryptographically verifiable, and data can be shared, executed, and stored locally or across trusted peers. Apps built with Kriyo can function offline, sync via distributed protocols, and enforce rules defined in signed capsules — not external platforms.

## Key Features

- **Capsule-based architecture**: Code and data are bundled into cryptographically signed, self-contained units.
- **Offline-first runtime**: Execute WebAssembly (WASM) logic locally with no dependency on cloud compute.
- **Cryptographic identities (DIDs)**: Every peer and capsule is verifiable through local trust graphs.
- **Trust-aware DAGs**: Each device builds a local graph of trusted capsules, peers, and endorsements.
- **Modular networking**: Combines direct QUIC transport with decentralized routing (Kademlia DHT) and optional relays for availability and message forwarding.
- **Encrypted, content-addressable storage**: Uses BLAKE3 hashes to store data locally or across peers with optional pinning and redundancy.

> ⚠️ This project is in **active research and early development**. We're sharing the vision, architecture, and initial scaffolding publicly to invite early feedback and contributors.
