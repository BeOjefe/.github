# BeOjefe Studio
### African Digital Infrastructure & High-Performance Engineering

> *"On construit des choses qui marchent vraiment, pour de vrais utilisateurs."*

BeOjefe is an independent technology studio and engineering lab dedicated to building robust digital platforms, financial data infrastructure, and bespoke software tailored specifically for the African continent.

---

## 🌍 Our Mission

African markets operate under distinct technological and environmental constraints: volatile network connectivity, high mobile-money adoption, and diverse hardware profiles. 

We reject off-the-shelf software retrofitting. Every system engineered at BeOjefe is designed from the very first line of code with local realities as primary architecture constraints:
- **Offline-First & Degraded State Resilience**: Applications remain functional even when underlying APIs encounter latency spikes.
- **Low-Bandwidth Optimization**: Hyper-optimized asset delivery, compact binary data protocols, and predictive caching.
- **Zero-Trust Hardened Security**: Centralized secret lifecycle management via OpenBao and encrypted mesh networking.

---

## 🏛️ Ecosystem & Open Architectures

```text
┌────────────────────────────────────────────────────────────────────────┐
│                          BEOJEFE ECOSYSTEM                             │
└────────────────────────────────────────────────────────────────────────┘
          │                                            │
          ▼                                            ▼
   [ MEOCE PLATFORM ]                         [ INFRASTRUCTURE CORE ]
   BRVM Market Intelligence                   High-Availability Lab
   ├── meoce-api (FastAPI Core)               ├── Proxmox VE LXC Nodes
   ├── meoce-frontend (Next.js 16)            ├── OpenBao Secrets (OIDC)
   ├── meoce-intraday-worker (Streaming)      ├── Garage S3 & DB Cluster
   └── meoce-airflow (BRVM Pipelines)         └── Dokploy & Vercel CI/CD
```

### 📈 [MEOCE](https://github.com/BeOjefe/meoce-api) — Market Intelligence Engine
The flagship financial intelligence platform covering the West African Regional Stock Exchange (BRVM):
- Sub-second market orderbook streaming.
- Vectorized technical analysis and automated indicator pipelines.
- WhatsApp multi-channel market reporting.

### 🛡️ Enterprise-Grade Governance
All BeOjefe repositories adhere to strict industrial development standards:
- **Governed Branch Protections**: 100% of pull requests must pass strict automated test and lint pipelines prior to merging.
- **Zero Permanent CI Secrets**: Automated GitHub OIDC token exchange with OpenBao (15 min ephemeral TTL, isolated non-production scopes).
- **Continuous Delivery**: Fully automated, zero-downtime deployment triggering on verified merges to `main`.

---

## 🤝 Collaborate & Connect

- 🌐 **Official Studio**: [beojefe.com](https://beojefe.com)
- 📊 **MEOCE Portal**: [meocehub.com](https://meocehub.com)
- ✉️ **Inquiries & Partnerships**: [contact@beojefe.com](mailto:contact@beojefe.com)
- 📍 **Offices**: Casablanca · Libreville
