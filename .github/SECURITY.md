# Security Policy

## Supported Versions

The **VALTOR — V9 Aquila Digital Flagship** team actively maintains and provides security updates for the latest release branch:

| Version | Branch | Supported |
| :--- | :--- | :---: |
| **1.0.x** | `main` | ✅ Yes |
| **< 1.0.0** | Legacy pre-release | ❌ No |

---

## Security Architecture Overview

This project is a purely client-side static frontend showcase built with **Vanilla ES Modules**, **GSAP**, **Lenis**, and **Vite**:

- **Zero Server-Side Execution:** The production build (`dist/`) consists exclusively of static HTML, CSS, JavaScript, and curated photographic assets.
- **No Sensitive Credential Storage:** No API keys, private tokens, or database credentials are bundled or evaluated at runtime.
- **DOM Sanitization & Integrity:** All editorial copy and media paths are sourced from immutable static data manifests (`src/data/brandData.js`), preventing untrusted user-supplied HTML injection (`XSS`).
- **Official Treasury Verification:** The sole official Solana (SOL / SPL USDC) payment and sponsorship wallet address associated with this project is:
  ```text
  3HvUMCUSSHEdtA35UuD4J7mbgpTxJ7LgT2X7GfdzvBdm
  ```
  Always verify this exact address in [`PAYMENT.md`](../PAYMENT.md), [`SPONSORS.md`](../SPONSORS.md), and [`.github/FUNDING.yml`](./FUNDING.yml) before executing any on-chain transaction.

---

## Reporting a Vulnerability

We take security vulnerabilities, supply-chain dependency risks, and DOM injection vectors seriously.

> [!IMPORTANT]
> **Please do NOT report security vulnerabilities through public GitHub issues, discussions, or pull requests.**

### Responsible Disclosure Procedure

1. **Private Notification:** Send a detailed report to **`concierge@valtorautomobiles.com`** with the subject line `[SECURITY DISCLOSURE] VALTOR Digital Flagship` or use GitHub's **Private Vulnerability Reporting** tab under the repository's **Security** section.
2. **Required Information:**
   - A clear description of the vulnerability and affected component (`src/...` or dependency in `package.json`).
   - Step-by-step reproduction instructions or a minimal Proof-of-Concept (PoC).
   - Potential impact assessment (e.g., DOM XSS, dependency prototype pollution, supply-chain compromise).
3. **Response Timeline:**
   - **Acknowledgement:** Within **24 hours** of submission.
   - **Triage & Technical Assessment:** Within **72 hours**.
   - **Patch Release & Advisory:** Critical fixes are patched and pushed to `main` within **5 business days**.

---

## Bug Bounty & Responsible Disclosure Recognition

Security researchers who responsibly disclose valid critical or high-severity vulnerabilities are eligible for public recognition in our security advisories and discretionary bounty rewards settled via **Solana (SOL / USDC-SPL)**.
