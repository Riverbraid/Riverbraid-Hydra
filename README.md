# Riverbraid-Hydra

**Status:** Experimental / Research
**Normative Source:** Riverbraid-Core
**Claim Boundary:** Declared Conditions Only

## Role in Riverbraid

Riverbraid-Hydra is a runtime fork surface for Hydra based Riverbraid video synthesis and modular signal experiments.

Riverbraid-Core remains the normative source for protocol semantics. This repository does not define or replace canonical Riverbraid protocol rules.

## Authority Boundary

This repository is a Ring 2 runtime fork. Local runtime, synthesis, or modular signal language is not protocol authority.

## API Boundary

Riverbraid-Core does not currently expose internal files such as `run-vectors.cjs` or `gate.mjs` as public package scoped APIs. Package scoped imports such as `require("riverbraid-core/gate.mjs")` are not part of the current supported surface.

## Verification Boundary

The local verification surface is limited to repository evidence and declared local verifier output. `verify-output.json` records repository specific verifier output. It does not verify the full constellation.

## Local Verification

```powershell
node .\verify.mjs
```

Expected local status: `VERIFIED`.

## Non Claims

This repository does not claim certification, production readiness, external audit, legal approval, complete AI safety, absolute security, or absence of defects.

## License

MIT.
