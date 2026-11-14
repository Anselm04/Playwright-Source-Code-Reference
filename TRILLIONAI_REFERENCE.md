# Playwright — TrillionAI Engineering Reference

This public repository holds a pinned, Git-tracked upstream Playwright source snapshot for lawful source-code research and independently engineered TrillionAI Audit/AppForge browser verification. It is **not** a Playwright deployment or a completed TrillionAI Audit integration.

## Upstream identity and licence

- Original publisher: Microsoft
- Original GitHub project: https://github.com/microsoft/playwright
- Pinned upstream commit: `b4d016aadc5cbd2b898a284307975fe73e05483d`
- Pinned upstream Git tree: `6e0ff87e14ce08158f79ebe2070c95fc73abcbea`
- Git tree inventory: 3,492 entries containing 3,149 tracked blobs (~70.1 MB total tracked blob sizes).
- Original upstream root `LICENSE`: Apache License 2.0.
- Original upstream `NOTICE` and all applicable per-file/component attribution must be retained.
- Destination: tracked source files **directly on the default `main` branch**.
- Import status: **VERIFIED — imported source is visible on `main` and GitHub Actions succeeded.**

## Verified import result

- [Successful GitHub Actions source import](https://github.com/Anselm04/Playwright-Source-Code-Reference/actions/runs/43648413463)
- Original pinned upstream Git tree: `6e0ff87e14ce08158f79ebe2070c95fc73abcbea`
- Verified final destination Git tree: `a0b0a6d16731d52d613223283376908cf0864759`
- Original upstream tracked entries: **3,492**; blob entries: **3,149**
- Verified source-object mismatches: **zero**, ignoring removed upstream GitHub Actions workflows and the additional research document.
- Both original root `LICENSE` (Apache License 2.0) and `NOTICE` are preserved.
- Actual Playwright root source directories (`packages/`, `tests/`, `browser_patches/` and others) appear on `main`.

The destination root differs from upstream only in the documented excluded CI definitions and added TrillionAI research documentation. This result is source-integrity verification, **not** a claim that Playwright was executed or that all tests pass.

## Import and verification

The pinned import workflow at `.github/workflows/import-playwright-source.yml` fetches the exact commit and its tree, replaces the README-only starter layout with original upstream source, stores these notes as `TRILLIONAI_REFERENCE.md`, and removes imported upstream `.github/workflows/` definitions to avoid executing third-party workflows. The import workflow itself is also removed once finished.

Because of that intentional removal and the added research file, the final destination root tree hash is **not** identical to the original upstream root tree. All other imported files must preserve their original Git object identities. We do **not** run third-party code or activate cloud resources to create the source archive.

The snapshot does not import full upstream Git history, browser binary downloads, external services or generated runtime assets. A source archive is not proof that build, functional tests or security audits pass.

## Research topics

1. Actual browser automation, deterministic user journeys and E2E test orchestration.
2. Test isolation, bounded execution, timeouts and reproducible failure evidence.
3. Screenshot, trace and artifact capture with retention/privacy policies.
4. Chromium, Firefox and WebKit support boundaries.
5. AppForge preview verification and independent TrillionAI Audit pass/fail/not-assessed status.

## Commercial and licensing boundary

Copyright remains with Microsoft and contributors under applicable original licences. TrillionAI Audit remains proprietary: independently implement original Node.js/Flutter orchestration and interfaces and verify permission before copying any source. Do not enable deployments, paid services or upstream CI for archival research.
