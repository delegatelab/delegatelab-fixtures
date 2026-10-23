# DelegateLab — Boundary regression scenarios

Open-source adversarial testing for Stellar delegated-account authorization. This repository owns the fixtures component.

Run `npm test` and `npm run demo`. policies.json includes cap=1, a value beyond JavaScript safe-integer range, and an i128 boundary. Every fixture is synthetic and model-only. Real delegated authorization diagnostics are in the backend testnet evidence.

Read [INTEGRATION.md](INTEGRATION.md) to run the connected workspace and [ROADMAP.md](ROADMAP.md) for the exact remaining scope. All five repositories: [engine](https://github.com/delegatelab/delegatelab-engine), [contracts](https://github.com/delegatelab/delegatelab-contracts), [backend](https://github.com/delegatelab/delegatelab-backend), [frontend](https://github.com/delegatelab/delegatelab-frontend), [fixtures](https://github.com/delegatelab/delegatelab-fixtures).

MIT licensed. Early fixture-focused testnet MVP, not a production wallet or security certification.
