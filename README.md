# MosaicGuard

**Agentic privacy protection against cross-document identity reconstruction on campus.**

> Removing a name is not enough when department, hostel, club, event, placement, and research records can be linked back to the same person.

MosaicGuard is the MARTIAN 1.0 campus evolution of the VeilGraph privacy-engineering foundation. It is designed for **Security Track 4 - Open Innovation** and protects a simulated campus release pipeline from mosaic re-identification attacks.

## Status

`MARTIAN ADAPTATION IN PROGRESS`

The repository currently contains the inherited, working VeilGraph privacy compiler and the first MosaicGuard rebrand. Cross-document campus monitoring, the attacker simulation, campus release policies, new fixtures, and MARTIAN evaluation remain active development work.

## The problem

Campus data is rarely released from one place. Registrar exports, placement lists, hostel notices, club reports, research datasets, support records, and event media may each look harmless after basic redaction. Together, their remaining clues can identify a student or staff member.

This is a **mosaic attack**: individually weak facts become identifying when combined.

MosaicGuard will monitor fictional campus releases, build a persistent exposure graph across them, identify reconstruction paths, quarantine unsafe artifacts, recommend the least destructive treatment, require human approval for consequential actions, and verify the transformed output before release.

## Agent loop

```text
SENSE
  Observe a simulated campus release queue and extract direct, contextual,
  relational, visual, and historical identity clues.

THINK
  Link clues across files and prior releases, run a bounded attacker,
  evaluate audience/purpose policy, and explain the reconstruction path.

ACT
  Quarantine, redact, generalize, pseudonymize, synthesize, or recommend
  a human-approved response.

EXPLAIN
  Show the exposure graph, evidence, policy decision, verification gates,
  audit events, and signed release proof.
```

## Winning demonstration

1. Several fictional campus departments submit apparently anonymized artifacts.
2. A bounded attack agent combines clues across those artifacts and reconstructs a subject.
3. MosaicGuard visualizes the cross-document path and quarantines the risky release.
4. A human reviews the evidence and approves the proposed treatment.
5. MosaicGuard transforms the artifact and attacks it through format-specific fail-closed checks.
6. The artifact is released only after every mandatory verification passes.
7. The system produces a tamper-evident audit record and signed proof package.

## Foundation already present

The inherited engine provides:

- deterministic direct-identifier detection;
- a lightweight offline semantic NER model;
- an Identity Exposure Graph;
- L1-L5 privacy compilation;
- native transformation for documents, images, structured data, and video;
- a format-specific fail-closed Privacy Red Team;
- encrypted per-job workspaces;
- human review for uncertain sensitive candidates;
- SHA-256 audit commitments and Ed25519 proof certificates;
- explicit retention expiry and signed destruction tombstones.

The inherited public snapshot recorded 268 passing backend tests plus a successful TypeScript typecheck and production build. These results are **prior-foundation evidence**, not MARTIAN-period implementation claims.

## New MARTIAN work

The adaptation is deliberately more than a dataset change:

- [ ] simulated registrar, placement, hostel, club, research, and support release sources;
- [ ] persistent graph across files and prior releases;
- [ ] cross-document mosaic attack agent;
- [ ] campus audience, purpose, and disclosure policies;
- [ ] quarantine and human-approval workflow;
- [ ] malicious embedded-instruction and prompt-injection resistance;
- [ ] fictional campus attack and benign-control fixtures;
- [ ] before/after attack measurements;
- [ ] MARTIAN-specific evaluation and judge script;
- [ ] clean submission packaging and provenance manifest.

The authoritative transition scope is documented in [MARTIAN_TRANSITION.md](MARTIAN_TRANSITION.md).

## Privacy gradation

| Level | Name | Core behavior |
|---:|---|---|
| L1 | Direct masking | Masks direct identifiers while retaining lower-risk context. |
| L2 | Sensitive-entity protection | Replaces high-impact identity and credential fields with opaque tokens. |
| L3 | Context generalization | Masks direct identity and broadens quasi-identifying context. |
| L4 | Relationship-safe pseudonymization | Preserves useful relationships using stable pseudonyms while generalizing exact clues. |
| L5 | Synthetic Twin | Generates a new local population for structured data and verifies source independence and utility. |

MosaicGuard does not claim guaranteed anonymity, universal PII recall, differential privacy, or legal certification. Its exposure score is a calibrated product indicator, and uncertainty blocks release.

## Supported foundation formats

PDF, scanned PDF, PNG, JPG, TXT, Markdown, safe RTF, DOCX, CSV, JSON, XLSX, MP4, and MOV.

## Quick start

Requirements:

- macOS or Linux;
- Python 3.11+;
- Node.js 18+;
- Tesseract OCR;
- Poppler.

```bash
chmod +x scripts/*.sh
./scripts/setup_once.sh
./scripts/run_checks.sh
./scripts/start_local.sh
```

Open `http://127.0.0.1:5173`.

Operational privacy processing is local and has no mandatory external model API. Dependency installation requires network access; the judged offline runtime does not.

## Repository map

```text
backend/                 FastAPI privacy and proof engine
frontend/                React and TypeScript judge interface
competition/             inherited VeilGraph evidence and fixtures
docs/engineering/        inherited engineering history and provenance
scripts/                 setup, regression, benchmark, and evidence runners
MARTIAN_TRANSITION.md    MosaicGuard scope, provenance, and demo contract
```

## Provenance and permission

MosaicGuard is an authorized extension of [VeilGraph](https://github.com/amogh-hub/VeilGraph). The project owner reports written organizer permission to reuse and extend the foundation for MARTIAN 1.0. Keep that written permission with the submission records and disclose the reuse to judges.

The original VeilGraph commit history and frozen evidence remain prior work. New commits in this repository must distinguish MARTIAN-period capabilities from inherited functionality. Renaming the product does not erase or replace its provenance.

## Safety

- Use fictional people and fake data only.
- Run attacks only against the team's simulated environment.
- Do not connect to real campus systems.
- Do not create or release malware.
- Keep a human in control of consequential actions.
- Treat uploaded content as untrusted and never execute embedded instructions.
- Never commit credentials, private keys, runtime workspaces, or real personal data.
