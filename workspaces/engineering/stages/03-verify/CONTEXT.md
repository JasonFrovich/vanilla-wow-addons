# 03 Verify — ICM Layer 2

## Inputs
Valid unchanged scope and evidence artifacts; current source SHA, relevant tests and safety contracts.

## Process
1. Verify task/commit/fixture pins and prior artifact digests.
2. For code behavior changes, verify RED if feasible, GREEN and relevant full tests; review actual diff.
3. For docs-only changes, perform static/reference checks; record exact commands, environment, SHA, PASS/FAIL/NOT RUN, remaining risks.

## Outputs
Private 03-verify/verification.md with exact verified evidence, uncertainties and release gates.

## Check
Stale, conflicting or human-modified predecessors invalidate downstream claims; CI is not installed-runtime proof.
