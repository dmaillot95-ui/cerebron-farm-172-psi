# F172 PSI — HANDOFF FOR RECURSIVE IMPROVEMENT AI

Date: 2026-09-25
Baseline HEAD at preparation: `71c48b69e0806c9a04abb36ea19de5a51dca2228`

## Mission
PSI searches for hidden variables, omitted states, latent assumptions and unknown-unknown candidates that could overturn a conclusion.

## Current proven state
- repository scaffold exists;
- architecture guard and training-source gate exist;
- status: `SCAFFOLDED_NOT_TRAINED`;
- runtime_changed: false;
- weights_changed: false;
- benchmark file is a frozen template with **no executed baseline yet**;
- training readiness gates G0→G8 are still PENDING.

## First obligation
Do **not** start neural training merely because this handoff exists.
First execute and record a real PSI role baseline, pin the model revision, freeze/hash M6, prove train/validation/M6 separation and satisfy the readiness gates.

## Recursive improvement loop
Use `config/recursive-improvement-contract.json`.
One cycle = one measurable hypothesis. Keep a change only if benchmark evidence improves and no critical regression appears.

## Forbidden claims
- scaffold != trained model
- runtime config != neural learning
- memory write != training
- shared-base agreement != independent evidence
- workflow success != scientific success

## Coordination
Another session may be working elsewhere in CÉRÉBRON. Stay inside F172 unless a cross-repo change is strictly required. Fetch the real HEAD again before every write. Never force-push.
