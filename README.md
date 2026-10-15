<div align="center">

# Aman Kumar
### Principal Security Engineer • Systems Infrastructure Architect • Open Source Core Contributor
**Founder, [The LeetSec](https://github.com/theleetsec) & [BSides Dehradun](https://github.com/bsidesdehradun)**

<br/>

[![GitHub followers](https://img.shields.io/github/followers/sudo-a-man?style=for-the-badge&color=0f172a&labelColor=020617&logo=github)](https://github.com/sudo-a-man)
[![Open Source Merged PRs](https://img.shields.io/badge/Verified_OSS_PRs-18+_Merged_•_18_Open-10b981?style=for-the-badge&color=10b981&labelColor=020617&logo=git)](https://github.com/sudo-a-man)
[![Zero-Trust Architecture](https://img.shields.io/badge/Security_Domain-Zero_Trust_&_CI_Governance-38bdf8?style=for-the-badge&color=38bdf8&labelColor=020617&logo=securityscorecard)](https://github.com/sudo-a-man)
[![Conference Lead](https://img.shields.io/badge/BSides_Dehradun-Lead_Organizer-818cf8?style=for-the-badge&color=818cf8&labelColor=020617&logo=radar)](https://bsidesdehradun.com)
[![X (Twitter)](https://img.shields.io/badge/X-@sudoaman-0f172a?style=for-the-badge&color=0f172a&labelColor=020617&logo=x)](https://x.com/sudoaman)
[![Direct Contact](https://img.shields.io/badge/Verified_Email-sudoamansec@gmail.com-ea4335?style=for-the-badge&color=ea4335&labelColor=020617&logo=gmail&logoColor=white)](mailto:sudoamansec@gmail.com)

<br/>

```
  ┌─────────────────────────────────────────────────────────────────────────────┐
  │  SYSTEM STATUS: ALL RELEASE GATES VERIFIED [PASS]  •  ZERO UNHANDLED TRAPS  │
  │  CORE FOCUS: RESILIENT RUNTIMES  •  DEFENSIVE BOUNDARIES  •  SUPPLY CHAIN   │
  └─────────────────────────────────────────────────────────────────────────────┘
```

</div>

---

### 🏛️ Executive Engineering Profile

With over a decade of deep immersion in offensive security research, systems architecture, and distributed platform engineering, I design and build **high-assurance, fail-closed software systems and automated release governance pipelines**.

My work sits at the critical intersection of **cryptographic integrity, runtime sandboxing, and deterministic CI/CD release gating**. Rather than treating security as an afterthought or post-hoc auditing pass, I embed formal invariance verification, strict input validation, and boundary-condition assertions directly into compile and deployment pipelines.

* **Fail-Closed by Construction:** Eradicating unhandled fallback states, unvalidated edge boundaries, and untyped parameters at ingress.
* **Deterministic Release Governance:** Building automated CI gates that reject deployments unless verified by independent SAST, security test suites, and cryptographic audit trails.
* **Production Open-Source Impact:** 18+ pull requests merged into canonical production repositories powering cryptographic infrastructure, commerce engines, and decentralized networks.

---

### 🚀 Verified Open Source Track Record & Production Contributions

#### 🔹 [Sottara (`Sottara-Labs/sottara`)](https://github.com/Sottara-Labs/sottara) — High-Assurance Cryptographic Platform
*Core Contributor responsible for automated CI release governance, security test execution, and identity resolution architecture. **18 Pull Requests Merged directly into `main`**.*

| Engineering Domain | Impact Analysis & Mitigated Surface | Verified Commits / PRs | Status |
| :--- | :--- | :--- | :---: |
| **CI Release Governance & Evidence** | Engineered automated governance verifications into the deployment pipeline; built immutable evidence generation to guarantee auditability before release artifacts are promoted. | [#257](https://github.com/Sottara-Labs/sottara/pull/257) | **Merged** ✅ |
| **Continuous Security Evaluation** | Hardened deployment safety by integrating the automated `test:security` test suite as a blocking gate; aligned security advisories with canonical upstream vulnerability tracking. | [#262](https://github.com/Sottara-Labs/sottara/pull/262)<br/>[#253](https://github.com/Sottara-Labs/sottara/pull/253) | **Merged** ✅ |
| **Cryptographic Identity Defense** | Refactored `IdentityResolverService` to eradicate unsafe global fallback handlers; isolated cryptographic performance benchmarking harnesses into standalone, reproducible tooling. | [#258](https://github.com/Sottara-Labs/sottara/pull/258)<br/>[#217](https://github.com/Sottara-Labs/sottara/pull/217) | **Merged** ✅ |
| **Pipeline Reliability & Deploy Bounding** | Hardened staging and production deployment automation by enforcing strict step execution timeouts to prevent hanging runners and pipeline resource exhaustion. | [#249](https://github.com/Sottara-Labs/sottara/pull/249)<br/>[#214](https://github.com/Sottara-Labs/sottara/pull/214) | **Merged** ✅ |
| **Environment & Secret Isolation** | Comprehensive mapping, documentation, and isolation of multi-tier environment variables and cryptographic secret access across staging and production clusters. | [#250](https://github.com/Sottara-Labs/sottara/pull/250), [#251](https://github.com/Sottara-Labs/sottara/pull/251)<br/>[#254](https://github.com/Sottara-Labs/sottara/pull/254), [#255](https://github.com/Sottara-Labs/sottara/pull/255) | **Merged** ✅ |
| **Boundary Defensive Testing** | Resolved subtle edge-case boundary errors in API rate-limit quotas; engineered comprehensive unit test coverage for reactive state hooks; restored WCAG-compliant accessible focus states. | [#215](https://github.com/Sottara-Labs/sottara/pull/215)<br/>[#216](https://github.com/Sottara-Labs/sottara/pull/216)<br/>[#261](https://github.com/Sottara-Labs/sottara/pull/261) | **Merged** ✅ |
| **Preview Deployment Gating** | Enforced strict conditional gating on transient preview deployments, isolating review environments from production credentials. | [#259](https://github.com/Sottara-Labs/sottara/pull/259)<br/>[#263](https://github.com/Sottara-Labs/sottara/pull/263) | **Merged** ✅ |

<br/>

#### 🔹 [MedusaJS (`medusajs/medusa`)](https://github.com/medusajs/medusa) — Enterprise Open Source Commerce Platform (25,000+ ⭐)
*Active contributor enhancing core UI reliability, telemetry, and administrative query parameters.*
* **Notification State Resilience:** Resolved client-side toast notification state drift, introducing explicit dismiss handlers to prevent memory leaks and zombie DOM nodes ([#17241](https://github.com/medusajs/medusa/pull/17241)) — **`initial-approval`** ✅ *(automated audit passed with zero security/performance flaws)*.
* **Chronological Sort Inversion:** Corrected inverted sort-order label telemetry in the core admin dashboard interface ([#17242](https://github.com/medusajs/medusa/pull/17242)) — **`initial-approval`** ✅ *(verified changeset)*.
* **Input Boundary Sanitization:** Added telephone filter query parameter parsing and defensive handling to customer administration endpoints ([#17243](https://github.com/medusajs/medusa/pull/17243)).

<br/>

#### 🔹 [SUSU-LABS](https://github.com/SUSU-LABS) — Decentralized Web & Data Infrastructure
*Author of 10 targeted reliability and boundary-hardening pull requests across full-stack repositories.*
* **Web Client Architecture (`susu-web`):** Runtime response validation with Zod schemas ([#96](https://github.com/SUSU-LABS/susu-web/pull/96)); async auth session recovery ([#94](https://github.com/SUSU-LABS/susu-web/pull/94)); configurable API network timeouts ([#93](https://github.com/SUSU-LABS/susu-web/pull/93)); wallet race-condition concurrency guards ([#89](https://github.com/SUSU-LABS/susu-web/pull/89)).
* **Backend API Resilience (`susu-api`):** Graceful PostgreSQL connection pool termination on SIGTERM/SIGINT ([#100](https://github.com/SUSU-LABS/susu-api/pull/100)); nonce-reaping lifecycle synchronization ([#101](https://github.com/SUSU-LABS/susu-api/pull/101)); group boundary invite leak protection ([#102](https://github.com/SUSU-LABS/susu-api/pull/102)).
* **Blockchain Indexer (`susu-indexer`):** Resilient in-flight `pg_cron` alert scheduling ([#79](https://github.com/SUSU-LABS/susu-indexer/pull/79)).

<br/>

#### 🔹 Community Leadership & Security Ecosystem Building
* **Founder & Technical Director, [The LeetSec](https://github.com/theleetsec):** Spearheading offensive security research, open-source auditing tools, vulnerability triage, and developer threat modeling training.
* **Lead Organizer, [BSides Dehradun](https://github.com/bsidesdehradun) ([bsidesdehradun.com](https://bsidesdehradun.com)):** Founded the Dehradun chapter of Security BSides, fostering a collaborative security community, hosting workshops, and mentoring hundreds of engineers across threat hunting, reverse engineering, and cloud security.

---

### 📊 Real-Time Activity & Telemetry

<div align="center">
  <table border="0">
    <tr>
      <td align="center" width="50%">
        <img src="https://github-readme-stats.vercel.app/api?username=sudo-a-man&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0b0f19&title_color=38bdf8&icon_color=10b981&text_color=94a3b8" width="100%" alt="Aman Kumar's GitHub Stats" />
      </td>
      <td align="center" width="50%">
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=sudo-a-man&theme=tokyonight&hide_border=true&background=0b0f19&ring=38bdf8&fire=10b981&currStreakLabel=38bdf8&sideLabels=94a3b8" width="100%" alt="Aman Kumar's GitHub Streak" />
      </td>
    </tr>
  </table>
</div>

---

### 🛠️ Architecture & Technical Competencies

```
┌─────────────────────────────────┬────────────────────────────────────────────────────────────────────────┐
│ Domain                          │ Core Competencies, Tools & Frameworks                                  │
├─────────────────────────────────┼────────────────────────────────────────────────────────────────────────┤
│ Security Architecture & SAST    │ Threat Modeling (STRIDE / PASTA), Zero-Trust Architecture,             │
│                                 │ Secret Scanning, Semgrep, Dependency Risk Mitigation, Cryptographic    │
│                                 │ Identity Resolution, Memory Safety & Boundary Defense                 │
├─────────────────────────────────┼────────────────────────────────────────────────────────────────────────┤
│ Systems, Languages & Core       │ TypeScript (Strict), Node.js (ESNext / Worker Threads), Python, Rust,  │
│                                 │ Go, POSIX Shell / Bash, React, Next.js Runtimes                       │
├─────────────────────────────────┼────────────────────────────────────────────────────────────────────────┤
│ Infrastructure & Deployment     │ Deterministic CI/CD (GitHub Actions), Docker, Linux Kernel / POSIX,   │
│                                 │ Cloudflare Workers, Edge Computing, PostgreSQL, Redis                  │
├─────────────────────────────────┼────────────────────────────────────────────────────────────────────────┤
│ Verification & Test Harnesses   │ Vitest, Jest, Playwright, Benchmark Automation, Mock Service Workers,  │
│                                 │ Deterministic Boundary Fixtures, Automated Mutation & Invariance Tests │
└─────────────────────────────────┴────────────────────────────────────────────────────────────────────────┘
```

---

### 📐 Engineering Principles

1. **Safety by Construction:** Any system state that cannot be mathematically or logically validated must fail closed. Never allow an unhandled fallback or ambiguous authorization state to proceed silently.
2. **Automated Evidence Over Assumption:** A pull request is not production-ready until CI independently proves that all security, governance, and functional invariants hold true under adversarial inputs.
3. **Deterministic & Reproducible Builds:** Every deployment artifact and security test suite must be idempotent, reproducible, and verifiable across environments.
4. **Ruthless Boundary Isolation:** Third-party dependencies, user inputs, and untrusted execution contexts must be sandboxed behind rigorous validation envelopes.

---

### 📬 Connect & Collaborate

```
  ┌──────────────────────────────────────────────────────────────────────────────┐
  │  GPG SIGNATURE: ALL PRODUCTION COMMITS CRYPTOGRAPHICALLY VERIFIED           │
  │  LOCATION: DEHRADUN, INDIA  •  ACTIVE COLLABORATIONS: OPEN                  │
  └──────────────────────────────────────────────────────────────────────────────┘
```

<div align="center">

**[Direct Contact (Email)](mailto:sudoamansec@gmail.com)** &nbsp;•&nbsp;
**[GitHub Profile](https://github.com/sudo-a-man)** &nbsp;•&nbsp;
**[The LeetSec Org](https://github.com/theleetsec)** &nbsp;•&nbsp;
**[BSides Dehradun](https://bsidesdehradun.com)** &nbsp;•&nbsp;
**[X (@sudoaman)](https://x.com/sudoaman)**

<br/>

<sub>Architected with uncompromising rigor, deterministic standards, and verifiable excellence.</sub>

</div>
