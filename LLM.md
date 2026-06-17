# insights-rs

Rust client SDK for Hanzo Insights (product analytics) — crate `insights-rs`. Event capture, feature flags (local + remote eval), multivariate/A-B flags, and group/B2B analytics. Async (`tokio`) by default; sync via the blocking client. Forked from the PostHog Rust SDK.

Uses the `tracing` crate for logs (`RUST_LOG=insights_rs=debug`). Releases managed with Sampo (changesets + crates.io).

- Build: `cargo build`
- Test: `cargo test`

Full docs: README.md
