---
case_id: DJI-MINI1-001
platform: DJI Mini 1
evidence_level: lead
status: open
created: 2026-08-07
---

# DJI-MINI1-001: reported failure after direct voltage application

## Case status

This is an **unverified public lead**. No diagnosis or component identity has been confirmed. Source images are intentionally not republished pending permission from their owner.

## Reported facts

| Field | Entry |
| --- | --- |
| Aircraft | DJI Mini 1 |
| Reported intervention | 1.8 V applied directly to a component |
| Reported result | Component failed or was visibly damaged |
| Reported top marking | `AVXK` / `236` (orientation and reading require confirmation) |
| Requested information | Schematic, component identity, compatible replacement |

## Observations from supplied screenshots

- The indicated device appears near an inductor and several passive components.
- The board overview contains a visible marking resembling `PP002206.02`; the remaining board text is not yet confirmed from original-resolution evidence.
- The close-up shows prior probing or rework around the indicated circuit.
- Package dimensions, pin count, nets, and rail direction cannot be established reliably from the screenshots alone.

## Hypotheses

- The component may be part of a switched power-conversion stage because of its proximity to an inductor and supporting passives.
- The applied 1.8 V may have been placed on an input, output, feedback, enable, or unrelated node. The report does not establish which.

These are working hypotheses, not identifications.

## Information requested from the owner

- [ ] Permission to quote the report and republish original images
- [ ] Original post URL and date
- [ ] Original-resolution, uncropped board photographs
- [ ] Exact aircraft model and serial number with the serial redacted for publication
- [ ] Board side, revision, and all readable board markings
- [ ] Exact component location and package dimensions
- [ ] Aircraft symptoms before and after the 1.8 V application
- [ ] Ground reference, injection point, current limit, and injection duration
- [ ] Resistance-to-ground measurements on each accessible pin
- [ ] Known-good comparison measurements, if available
- [ ] Repair steps and final outcome

## Validation plan

1. Establish board and component location from original evidence.
2. Map the component pins to ground, inductor, nearby passives, and adjacent ICs.
3. Compare resistance and diode-mode readings with a known-good DJI Mini 1 board.
4. Identify circuit function before attempting a part substitution.
5. Inspect upstream and downstream devices for collateral damage.
6. Record current-limited power-up and functional-test results.

## Outcome

Pending.
