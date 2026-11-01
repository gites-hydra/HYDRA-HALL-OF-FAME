# HGS-SILVER — AI contribution and provenance

**Task:** HYDRA-HOF-SILVER-FULL-MANUSCRIPT-001
**Record:** HGS-SILVER full manuscript (prepared as a Project Diderot candidate before submission)
**Date:** 2026-11-01 (Europe/Warsaw)
**Current publication status (2026-11-01):** GitHub `RELEASED`; Project Diderot `PUBLISHED`; aiXiv `PUBLISHED` with `OFFICIAL_REVIEW_COMPLETED`. See the linked records in `PUBLICATION-STATUS.md`.

**Historical preparation state (archived):** `PUBLICATION=HOLD` · `EXTERNAL_CONTACT=NOT_AUTHORIZED`. This described the pre-submission preparation stage and is superseded by the current records above.

## 1. Disclosure statement (as printed in the manuscript)

The proofs and the principal results were developed with AI systems, in a staged research project directed by a human project owner whose authorship role has not been decided. Model audits (P8, P13) are not human peer review. No human mathematician has reviewed the proofs. No priority is claimed. The present manuscript was edited by Claude; the editing is not a new independent certification of the proofs.

## 2. Stage-by-stage attribution

Identities are copied from controlled stage records. Where a record does not establish an executor, the entry says NOT_ESTABLISHED. Session identifiers, transcript paths and hashes, and local user names that appear in the internal records are deliberately not reproduced in this package.

| Stage | Contribution to the manuscript | Executor as recorded | Record basis | Limitation |
|---|---|---|---|---|
| P0–P6 | silver-ratio model; first derivation of the transfer (STT-1 lineage) | NOT_ESTABLISHED (P5, P6 headers: "WYKONAWCA: niewskazany w HO"; P1–P4 headers carry no executor) | P5-00, P6-00 | do not infer |
| P7 | PET-1; PET-2 for odd ℓ≥3; silver maximum and uniqueness argument (STT-2 lineage) | OpenAI `gpt-6-luna` / Codex | P8-00/01 (session record), P13-01 §5 | model-originated proof |
| P8 | model certification of P7; extension of PET-2 to ℓ=1; proof of the transfer used in the manuscript (d'Ocagne route); derivation of STT-3 (Corollary E) | Anthropic `claude-opus-5-5` / Claude Code | P8-00 header; P8-05 | model audit, non-blind, not human review |
| P9 | prior-art audit; manuscript revision; referee package | DeepSeek `deepseek-flash` / DeepSeek Harness | P9-00 header | same executor identity as P13 (priority axis not independent) |
| P10 | bibliographic follow-up; full-text reading of six works | NOT_ESTABLISHED | P14-10 | do not infer |
| P11 | even-length set recursion; count E_k (PET-3) | OpenAI `gpt-6-luna` / Codex | P13-01 §5 (turn-level `turn_context` reading); P14-10 | turn-level attribution in a multi-model session |
| P12 | audit of P11; proof P12-B (PET-4, "B-LEVEL-3") | Anthropic `claude-opus-5-5` / Claude Code | P12-00 header; P13-01 §5 (transcript metadata) | — |
| P13 | independent model certification of P12-B; P11 errata proposal; standalone proof text | DeepSeek `deepseek-flash` / DeepSeek Harness | P13-00 header; P13-01 §6 (self-identification) | executor-level independence only; non-blind; not human review |
| P14 | canonical reconciliation (PET/STT namespace); documentary errata adoption (MD-1, D-2, D-3, P12-N1–N4, S1–S7) within its own package; working manuscript R2 | OpenAI `gpt-6.1-terra` / Codex, as recorded in P14's own register | P14-10 (self-reported, "bieżący wykonawca") | not a new mathematical audit; identity not cross-confirmed by an independent log reading |
| This task | editing of R2 into the full manuscript; LaTeX/PDF/Markdown; editorial corrections E-1…E-10 (see SOURCE-AND-CLAIM-CROSSWALK.md, part D); bibliographic metadata check; editorial consistency computations | Claude (Anthropic), session configured for model identifier `claude-opus-5-5` | this package | same model identifier as P8 and P12; not independent of them; not a certification |

## 3. Confrontation with the attribution stated in the task

| Task statement | Original record | Result |
|---|---|---|
| P11 developed by `gpt-6-luna` in Codex | P13-01 §5: Codex session, turn `turn_context` records model `gpt-6-luna`; P14-10 repeats it | CONFIRMED (turn-level) |
| P12-B developed by `claude-opus-5-5` in Claude Code | P12-00 header; P13-01 §5: Claude Code transcript, the only model string is `claude-opus-5-5` | CONFIRMED |
| P13 audited by `deepseek-flash` in DSH | P13-00 header and P13-01 §6: DeepSeek Harness / `deepseek-flash` / DeepSeek (HO field empty, identity established by P13 itself) | CONFIRMED (self-identification) |
| P14 consolidated results and adopted documentary corrections in the described scope | P14-00, P14-07, P14-10: adoption append-only for MD-1, D-2, D-3, P12-N1–N4, S1–S7; executor recorded as OpenAI `gpt-6.1-terra` / Codex | CONFIRMED; executor identity added from P14-10 |
| present manuscript edited by Claude | this session | CONFIRMED |
| (not in task) P7, P8, P9, P10, P0–P6 | see §2 | added because PET-1, PET-2, STT-1–STT-3 originate there; P0–P6 and P10 left NOT_ESTABLISHED |

No missing identifier was guessed.

## 4. Status of the reviews

- **P8** certified P7 at the level of the executing model (different provider, model and harness from P7). Model audit, non-blind.
- **P13** certified P12-B as `INDEPENDENTLY_CERTIFIED` with qualifications Q1–Q8 at the level of the executing model (different provider, model and harness from the author of P12-B). It read the proof before reconstructing it (non-blind, Q2), it is not a human review (Q3), and it shares its executor identity with P9 (Q5).
- **P14** was a reconciliation and editing stage, not a mathematical audit.
- **This task** re-read every proof step while editing and ran exact consistency computations (SUPPORT/EDITORIAL-CONSISTENCY-CHECKS.py, 70 381 assertions, PASS). This is editorial quality control by a model that shares its identifier with the authors of P8 and P12; it is **not** a new independent certification.
- **Human review:** none. HUMAN_REVIEW_NOT_REQUESTED (P14-11).
- **aiXiv platform review:** the public record currently displays `Official Review Completed` (2026-11-01). This is a platform review status, not human proof verification, endorsement, or a claim of acceptance.

## 5. Historical preparation draft for the Project Diderot "AI Tool Disclosure" certificate (not issued)

This section preserves a pre-submission draft and platform note. A preparation-time note stated: “Diderot allows only the submitting author to issue this certificate; AI systems cannot self-certify.” That note is retained as historical context, not asserted here as current platform policy. This section is not a current submission-status statement and is not a certificate. The draft below was prepared for possible use by the Owner before submission was authorized; no certificate is claimed here.

- **Tools and models used (as recorded):** OpenAI `gpt-6-luna` (Codex); Anthropic `claude-opus-5-5` (Claude Code); DeepSeek `deepseek-flash` (DeepSeek Harness); OpenAI `gpt-6.1-terra` (Codex, consolidation, as self-recorded); executors of the earliest stages and of P10 not established.
- **Model IDs in Diderot format (`provider/model-version`):** NOT_ESTABLISHED. They must be looked up by the submitter at openrouter.ai/models; if a model is not listed, the "custom agent" option requires a public description link, which is not authorized at present.
- **Roles:** derivation of proofs (P7, P11, P12); model certification (P8, P13); literature audit (P9, P10); consolidation (P14); editing of this text (Claude).
- **AI-generated sections:** all sections of the manuscript, as far as the records show.
- **Human-written sections:** none recorded. The human project owner set the tasks and took the adoption decisions recorded in P14-07.

## 6. What this package does not do

It does not identify a human person as a mathematical author, does not attribute human review or a proof-verification certificate to anyone, does not claim priority, and does not publish internal transcripts, private registers or personal data.
