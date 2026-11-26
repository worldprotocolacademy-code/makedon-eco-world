# Makedon Eco World v11.0 RC2 — Full platform integration

Date: 2026-11-26. Status: draft release candidate; not production deployed.

## Scope and provenance
- Baseline v10 main commit: 049a6483d44dab029edd50c4bc4c2603133bfd27; root index blob e4da35313bcae3d34eb61574c26f210e0d076191; unchanged.
- v11 RC1 citizen ledger: `pilot-v11/index.html`, unchanged blob 1606552ac9d9f4add1139b27c14ad2ce879ba480.
- RC2 portal: `platform-v11/index.html`, blob b05fad0a82f69414d25c6de41d73b10bca2a47e2, SHA-256 baae6e553e1abf9a58f61224c40ecd9646ec2233053f16dd3394524631e1d58f.
- V10 architecture library: `platform-v11/architecture.html`, blob 2495b90b253dc6d7a3f813157a30d560df3b672d. All 29 original sections retained, historical concepts labelled, previous controls and external links disabled. No legacy scripts or forms. Original text includes unverified illustrative claims, not current endorsements or services.

## Acceptance results
- 29/29 original module IDs match the RC2 navigation and archive: PASS (GitHub readback).
- 15 prospective organisations from v10, not confirmed partnerships: PASS.
- New dashboard MK/HR/EN language, filters, financial scenario arithmetic and validation, GTIN checksum, unsupported-camera fallback, layout at 360/390/768/1024/1440 px: 34 controlled Chromium checks passed, with exact local CSS and JS inlined and CSP omitted in the test harness. Hero contrast corrected and checked. Prior ledger suite: 42 controlled checks, not repeated as part of RC2 except loading the ledger.
- Local browser URL navigation restricted by environment. Actual HTTPS, physical camera, native storage on deployed origin, archive full browser render, real devices, independent security review: NOT TESTED. Barcode check is not proof of item or handover. Camera only where native BarcodeDetector and permissions are available; manual fallback always available.
- External AI, payments, operator integrations, certificates, government APIs, blockchain, IoT and all other undeployed features remain planned; no verified operational services or partners are claimed. The original 11-language dictionary remains in v10; RC2 dashboard and ledger support 3 languages, other languages not migrated. No actual payment, financial commitment, or external communication.

## Release and rollback
Keep main unchanged; review draft PR #1. Deploy and verify portal route, archive anchors, ledger storage/export, physical camera and responsive devices before presenting externally. A future decision may promote RC2 to the root; do not silently replace v10. Original source recoverable from baseline commit. Human Gate required before production promotion and external outreach.
