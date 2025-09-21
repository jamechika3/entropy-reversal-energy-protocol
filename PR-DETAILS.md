Title: Launch entropy-reversal protocol contracts

Summary
- Introduces two Clarity smart contracts for the Entropy Reversal Energy Protocol:
  - thermodynamic-reversal-coordinator: coordinates facilities, global entropy balance, emergency controls, and energy distribution
  - post-scarcity-economics-manager: manages post-scarcity participation, value contributions, advancement projects, and abundance distribution

Changes
- Added contracts with comprehensive, self-contained logic (no cross-contract calls)
- Updated Clarinet.toml with new contracts
- Scaffolded tests (passing via vitest)
- README on main branch with system overview

Verification
- clarinet check: passes
- npm install && npm test: tests pass

Notes
- Warnings from clarinet are about unchecked user input in public functions; these are acceptable for this prototype and can be hardened later.

Risks
- Prototype economic parameters are illustrative; governance thresholds and limits may be tuned in future iterations.