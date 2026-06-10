<p align="center">
  <img src="https://raw.githubusercontent.com/bartekus/bartekus/main/assets/banner-dark.svg" alt="Bartek Kus - Systems Architect & Principal Engineer" />
</p>

## 👋 Howdy, I'm Bartek

<a href="https://www.buymeacoffee.com/bartekus" target="_blank" rel="noreferrer">
  <img align="right" src="https://cdn.buymeacoffee.com/buttons/default-red.png" height="32" width="170" alt="Buy Me A Coffee">
</a>
<a href="https://www.linkedin.com/in/bartekus/" target="_blank" rel="noreferrer">
  <img align="right" src="https://raw.githubusercontent.com/bartekus/bartekus/main/assets/svgs/linkedin.svg" height="32px" alt="LinkedIn">
</a>
<a href="https://twitter.com/bartekus/" target="_blank" rel="noreferrer">
  <img align="right" src="https://raw.githubusercontent.com/bartekus/bartekus/main/assets/svgs/twitter.svg" height="32px" alt="Twitter">
</a>

<br />

I'm **Bartek Kus**, a systems architect from Edmonton, Canada. I work on the trust problem in AI-native software delivery:

> **AI can write the code. The unsolved problem is trusting what it wrote.**

My answer is **architecting intent**: the human authors the contract, agents do the work, and machinery (not optimism) refuses anything that drifts from the contract. Stop reviewing output; start constraining intent.

---

### 🔭 What I'm building

**[spec-spine](https://github.com/bartekus/spec-spine)**: a typed, hash-verifiable authority ledger over a markdown spec corpus. Every spec declares the files, sections, and symbols it owns; a PR-time coupling gate refuses code that drifts from its owning spec. Deterministic to the byte across five platforms; Rust; Apache-2.0. Install from [crates.io](https://crates.io/crates/spec-spine-cli) or [npm](https://www.npmjs.com/package/spec-spine). It governs itself: its own coupling gate runs against its own spec corpus in CI.

**[open-agentic-platform](https://github.com/stagecraft-ing/open-agentic-platform)**: the same ideas at platform scale; a governed control plane for AI-native software delivery. 200 frozen, hash-verifiable specs compile to a deterministic registry; every agent action reconciles to the spec that authorised it; every pipeline run emits a self-authenticating governance certificate an auditor can verify independently; the OWASP ASI 2026 control-to-spec mapping is one CLI invocation. AGPL-3.0. Built by one person directing a fleet of governed agents, which is rather the point.

---

### 🧭 What I think

- **Architecting intent over vibe coding.** No human reviews every line an agent produces; pretending otherwise just moves the bottleneck back to the human. Make intent the requirement, the requirement a spec, and the spec law.
- **Agentic output is hostile by default.** Agents earn passage by surviving gates, not by appealing to trust.
- **Humans gate contracts, not diffs.** Specs, approvals, and irreversible boundaries are human territory; everything between them is enforced by machinery.
- **Typed contracts beat convention.** It's why my backends are [Encore.ts](https://encore.dev), not Express: declarative, type-safe APIs that generate their own infrastructure, instead of middleware chains held together by discipline.

How I got here is one problem at three scales: a decade of digital identity (OIDC, SSI, DID) asking "can this person be trusted", platform engineering asking "can this system be trusted", and now governed agent delivery asking "can machine-generated change be trusted".

---

### 🛠 Tech I reach for often

`Rust` • `TypeScript` • `Encore.ts` • `React` • `Tauri` • `PostgreSQL` •
`Kubernetes` • `Helm` • `Terraform` • `OpenTelemetry` • `Claude Code` • `MCP`

---

### 📊 GitHub at a glance

<p align="left">
  <img
    src="https://github-readme-stats.vercel.app/api?username=bartekus&show_icons=true&hide_title=true&hide_border=true&include_all_commits=true&count_private=true&theme=tokyonight"
    alt="GitHub stats for bartekus"
    height="150"
  />
  <img
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=bartekus&layout=compact&hide_border=true&theme=tokyonight&langs_count=6"
    alt="Top languages for bartekus"
    height="150"
  />
</p>

---

### 📫 Reach me

➡️ **https://bartekus.com**
➡️ **LinkedIn:** /in/bartekus
➡️ **Twitter:** @bartekus
➡️ **Email:** bartekus@gmail.com

---

> _"The human authors the law; the agents comply with it; the spine makes non-compliance impossible to merge."_
