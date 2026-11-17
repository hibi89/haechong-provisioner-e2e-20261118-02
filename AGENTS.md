# AGENTS — haechong-provisioner-e2e-20261118-02

Project: Haechong PUBLIC Provisioner Synthetic E2E. Independent work area for parallel implementation.
Policy authority: hibi89/hackathon-command-center-2026 at exact SHA 09bd637e1bce4441b56263f51a19b05c8de20548.
Central execution: https://github.com/hibi89/hackathon-command-center-2026/blob/09bd637e1bce4441b56263f51a19b05c8de20548/docs/strategy/OWNER_DEV_EXECUTION_CANONICAL_20261116.md (§0J)
SWU standard: https://github.com/hibi89/hackathon-command-center-2026/blob/09bd637e1bce4441b56263f51a19b05c8de20548/docs/strategy/GPT6_HIGH_STANDARD_WORK_UNIT_20261117.md (§0E)

## Mission and precedence
Latest user instructions and approved final blueprint/safety rules outrank project task notes. Refresh canonical remote HEAD before work. Initial bootstrapping does NOT authorize implementation scope or claim that a product is built.

## P1 development
Use SWU-CPAA for critical-path and dependency-aware READY selection and SWU-WE for 1..6 actual independent functional SWUs per chat turn when safe. Implement real caller-to-callee BE/FE/API/DB/CLI and core failure paths; preserve REQ/SWU IDs, allowed paths and interface contracts. Multiple independent GPT chats require distinct areas, one integration owner, shared base SHA and no conflicting writes.

On actual no-progress failure: two attempts -> ISOLATED_REDESIGN_PENDING, redesigned two further attempts -> SOLMAX_BATCH_PENDING. Essential high-risk blockage may request expertise earlier. Documentation/CI polling do not count as implementation. P1 syntax/type/smoke and urgent safety gates remain; P2 full CI, integration, security, browser, recovery and independent audit are NOT automatically done.

## Safety
All new repos are PUBLIC. Never publish secrets, non-public designs, customer files or personal data.
No paid calls, customer data export, privilege expansion, secrets, destructive database writes, force push, main merge, Production, domain, commercial release or deletion without explicit owner approval. Protect original code, backup and history. Unrun checks must be NOT_RUN; unknown implementation or verification rate must be UNASSESSED. Exact branch/SHA and paths are required for progress reporting.
