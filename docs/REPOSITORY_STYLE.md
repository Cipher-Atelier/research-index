# Research repository style

Use this standard for Cipher Atelier research entry points and the [topic README template](../templates/TOPIC_README.md) for new investigations. Keep the public presentation restrained and English-first, without badges or decorative graphics. Preserve original-language evidence and useful translations, with their status clearly identified.

## Opening and navigation

Use a descriptive title, then a short paragraph explaining the material, research question and present limits. Display the community name as **Cipher Atelier**; retain `Cipher-Atelier` in GitHub URLs and repository slugs.

After the introduction, use one navigation line linking Cipher Atelier, the research index, the repository's reading guide and its verification instructions. Link only files that exist. For a new project without those guides, use relevant existing source or proposal links and state what is missing.

## README structure

Keep the main entry point concise and link detailed records rather than copying them. For established research repositories, use this order:

1. **Current status — [evidence date]:** summarize established results, unresolved questions and evidence levels. Use the actual date of the reported evidence or check, not the date of a cosmetic edit.
2. **Start here:** give a short reading path from sources and recorded signs to literal output, interpretation and detailed records.
3. **Reproduce the checks:** give the minimal offline command, required environment, expected result and exact scope. Link a manual example when one exists.
4. **Research scope and limitations:** preserve source gaps, assumptions, uncertainty, negative results, alternative explanations and archived experiment qualifications.
5. **Contribute:** link bounded open questions, the onboarding guide and contribution policy. Public contributions do not require membership.
6. **Sources and rights:** link source records, prior work, attribution and publication provenance; retain item-specific restrictions.

New investigations may adapt or omit sections that have no meaningful content yet. Say explicitly when no literal, source transcription or runnable replay exists, and identify what is needed. Do not create placeholder commands or imply unavailable evidence exists. Preserve useful dated subsections and historical records under the appropriate section.

## Evidence and publication status

Separate source transcription, literal output, editorial interpretation and translation. Retain masks, awkward strings and alternatives. Coverage measures assigned positions, not verified accuracy. A passing replay checks the declared saved inputs and calculations; it does not establish historical truth, uniqueness or external human expert review.

Qualify independent-check claims with the exact claim, checker or report, date, scope and what information was available. Distinguish author-reported validation from blind independent reconstruction. AI agreement is not independent human review. Keep frozen first results and post-test corrections separately identifiable.

Check the current default branch and PR state before calling material published. An open draft is proposed work; a merge records integration, not scientific validation. Update the research index when published evidence or its limits change, preserving dated historical updates.

## Verification scope

For the nine existing investigations, the baseline offline entry point is `python3 verification/check_all.py`. Describe exactly which packages it covers and what remains outside its replay. The eight baseline Evidence checks workflows run that command with Python 3.10 and 3.13 and check whitespace. The workflows use the hosted `ubuntu-latest` runner and checkout/setup-python actions pinned to verified immutable commits. Anna's existing CI additionally runs fixtures and other checks with pinned NumPy/Pillow dependencies; describe these separately from its baseline command.

For future projects, add CI only when meaningful checks exist. State dependencies and limits accurately; do not imply every document or experiment is verified by a green workflow. When a tracked documentation file or workflow has a checksum entry, refresh only deliberately changed entries. Preserve scientific data and provenance records.

## Repository metadata and community defaults

Use a short factual English description naming the material and evidence level. Avoid unsupported solved, complete or priority claims. Use shared research topics alongside topics specific to the document, period, language or method. Only add topics supported by the repository. Point the homepage to the research index when no more useful project-specific site exists. Keep metadata and the published README consistent.

The public [community repository](https://github.com/Cipher-Atelier/.github) supplies supported contribution, conduct, issue/PR template and funding defaults when local overrides are absent. A local `.github/ISSUE_TEMPLATE` directory replaces the entire default chooser. Inspect the actual interface before relying on it. README files, workflows, CODEOWNERS and licences need repository-local configuration; they do not inherit.

## Sources and permissions

Preserve source links, catalogue identifiers, exact locations, prior editions, keys, researchers and AI disclosures. Identify which sources were inspected and which are unavailable. Public access does not grant redistribution rights. Link to authorized providers when scans or other items cannot be redistributed. Do not introduce a blanket licence or relicense third-party work.

Use the [maintainer checklist](MAINTAINER_CHECKLIST.md) for onboarding and review, the [contribution guide](https://github.com/Cipher-Atelier/.github/blob/main/CONTRIBUTING.md) for evidence requirements, and [Start here](../START_HERE.md) for participation.
