# MosaicGuard MARTIAN Transition

## Product identity

**MosaicGuard** is a campus privacy-release guardian that detects identity reconstruction across documents, datasets, images, and prior releases.

Its defining threat is a **mosaic attack**: individually weak or apparently anonymized clues become identifying when combined across registrar, placement, hostel, club, research, support, and event records.

## Provenance

MosaicGuard is an authorized extension of the pre-existing VeilGraph privacy-engineering foundation. The project owner reports written organizer permission to reuse and extend that foundation for MARTIAN 1.0. The written approval should be retained with the submission records and disclosed to judges.

Existing VeilGraph history and evidence remain attributed as prior work. MARTIAN-period commits must identify newly built MosaicGuard capabilities and must not present earlier VeilGraph tests or implementation as work completed during MARTIAN.

## MARTIAN track

Security Track 4 - Open Innovation

## Problem statement

Campus departments routinely release files that appear safe in isolation. A placement list may omit names, a club report may omit email addresses, and a hostel notice may contain only a role or room block. An attacker can still combine department, age band, hometown, event date, club role, hostel block, related people, and repeated pseudonyms to reconstruct a student or staff identity.

Build an AI agent that monitors a simulated campus release pipeline, constructs a cross-document identity exposure graph, detects mosaic re-identification paths, recommends the least destructive safe treatment, quarantines unsafe releases with human oversight, attacks transformed outputs, and explains every decision.

## Required new work

The MARTIAN adaptation is not a dataset swap. It adds:

1. a simulated multi-department campus release environment;
2. a persistent cross-document and prior-release exposure graph;
3. a bounded re-identification attack agent;
4. campus roles, purposes, and release policies;
5. quarantine, approval, remediation, and release actions;
6. malicious-content and prompt-injection resistance tests;
7. a before-and-after threat demonstration;
8. campus-specific evaluation fixtures and metrics;
9. a complete audit trail separating prior foundation from new work.

## Demonstration contract

1. Ingest several fictional campus artifacts that appear safe individually.
2. Show the attack agent reconstructing a subject through cross-document clues.
3. Show MosaicGuard sensing the release set and explaining the reconstruction path.
4. Quarantine the unsafe artifact and propose a policy-aware transformation.
5. Require human approval for the consequential action.
6. Transform the artifact and run independent fail-closed attacks.
7. Release only after every mandatory check passes.
8. Produce an audit record and proof package for the final decision.

All people, identifiers, departments, records, and attacks used in the demonstration must be fictional and confined to the team's own simulated environment.
