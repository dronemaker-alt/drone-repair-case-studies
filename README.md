# Drone Repair Case Studies

An evidence-led collection of board-level drone failures, diagnostic work, repairs, and outcomes. The project exists to validate repeatable methods and tools for diagnosing undocumented electronics—not to turn guesses into folklore with nicer formatting.

## Evidence levels

| Level | Meaning |
| --- | --- |
| Lead | Public or owner-supplied report that has not been independently verified |
| Documented | Device identity, history, original evidence, and measurements are recorded with permission |
| Validated | Diagnosis or repair was tested and the outcome recorded |

## Workflow

1. Submit a case using the case-intake issue form.
2. Remove personal information and confirm permission for anything to be published.
3. Create a case folder from `templates/case-study-template.md`.
4. Preserve reported facts separately from observations and hypotheses.
5. Record measurements, reasoning, repair steps, and the final outcome.
6. Update `cases/index.md` and the project metrics.

## What makes a useful case

- Exact aircraft, module, and board identity
- Clear fault history and symptoms
- Original, uncropped overview and macro photographs
- Board markings and component top codes
- Known-good comparison data when available
- Instrument, setup, test point, units, and conditions for every measurement
- Repair outcome, including unsuccessful repairs

## Repository layout

```text
.github/ISSUE_TEMPLATE/  Public case intake
cases/                   Case records and index
templates/               Reusable case-study template
docs/                    Evidence, privacy, and measurement rules
```

## Project metrics

Each validated case may contribute:

- time to isolate the failed circuit;
- components positively identified;
- measurements required;
- known-good donor dependency;
- repair and functional-test result;
- diagnostic cost compared with board replacement; and
- whether another technician reproduced the procedure.

## Contributions and permissions

Do not upload screenshots, names, profile photographs, private messages, serial numbers, location data, or third-party photographs without permission. A public post may be indexed as a lead, but its claims remain attributed and unverified until evidence is supplied.

See `docs/evidence-and-privacy.md` before submitting material.

## License

Repository text and original data are intended for release under CC BY 4.0 once the repository owner confirms licensing. Third-party evidence remains the property of its owner and must carry its own permission and attribution record.
