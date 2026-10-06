# Reproduction record

Describe the smallest procedure that checks the named claim. A manual source comparison is a valid procedure. Say when essential evidence or code is unavailable.

## Claim and scope

- Claim, hypothesis, or result being checked:
- Original result and commit or release:
- Person performing this check and date:
- Check type: rerun / independent implementation / source comparison / other
- Shared inputs or assumptions and prior exposure to the expected result:

A rerun with the same transcription or key does not independently validate those inputs.

## Inputs and environment

- Source references and exact locations:
- Data, transcription, and key versions; checksums where practical:
- Code commit and dependency versions:
- Operating system and relevant hardware:
- Parameters, random seeds, resource limits, and approximate runtime:
- Input access, licence, or redistribution restrictions:

## Procedure

Write numbered steps or exact commands, starting from obtaining the permitted inputs and preparing the environment. Include manual decisions or transformations. Link the raw outputs and intermediate files needed to trace the result.

## Expected and observed output

Describe the expected output or acceptance criterion, then record the actual output. Include failures, warnings, deviations, and checks not run. If the original expectation was unavailable, say so rather than reconstructing it after the fact.

## Controls and sensitivity

When relevant, report a baseline or null control, plausible transcription alternatives, parameter sensitivity, and more than the best-performing run. Record tested search families and limits.

For heldout tests, state what was visible before the split, what was frozen and when, when the heldout material was first inspected, and any subsequent tuning or corrections. Reusing a consumed holdout is not a fresh test.

## Conclusion and remaining gaps

Does this reproduce the stated result? Which part failed or remains unchecked? Separate computational consistency, source fidelity, historical interpretation, and translation. State whether another reviewer can complete the same check with the publicly available material. Link a correction or next test where needed.
