# Maintainer triage and repository checklist

Use the parts needed for the proposal or contribution. Keep decisions in the issue so the next person can follow the work.

## Triage a new issue

- Check the actual question and link related projects, issues, PRs, or earlier research. If it duplicates work, connect the discussion and explain where it continues.
- Confirm that the requested scope and first step are understandable. Ask one focused question when essential information is missing.
- Check public-data suitability, source access, attribution, and redistribution limits. Link restricted material rather than copying it.
- Verify that Maxim, [@cayde-6](https://github.com/cayde-6), is assigned for initial triage. Form assignment identifies the triage contact; it does not mean he will personally perform every research task.
- For existing research, help the contributor coordinate a bounded task. Preserve room for independent replication and alternative explanations.
- Record the outcome: needs information, connected to existing work, approved for a new repository, or declined with a reason. These can be ordinary comments; a label system is optional.

An issue, donation, or proposed result does not create membership, grant funding, or establish a review deadline.

## Provision an approved topic

Only the organization owner creates the new public repository after manually approving the proposal. Do not create repositories, invitations, or permissions automatically from issue content.

- Record the approval, repository name, scope, and initial coordinating issue.
- Create the public repository and add a short README using the [topic template](../templates/TOPIC_README.md). Record evidence gaps plainly; do not fill them with inferred facts.
- Include source references, prior work, credit, and item-specific rights. Confirm intended terms for original material before adding a licence; do not relicense third-party work.
- Confirm that issues and the intended contribution templates are available, and that the default branch uses the agreed review protections. Grant no extra access merely because someone proposed a topic.
- Link the repository from the proposal and add it to the index with an evidence-calibrated description. Avoid “solved” or novelty claims without the corresponding record.
- Identify a small first task. Contributors can fork the repository and propose changes through PRs. Add other record templates only when useful.
- Close the hosting request when provisioning is complete, with the repository link and remaining research questions. The investigation can remain open in its own issues.

## Review a contribution

Use the [review template](../templates/CONTRIBUTION_REVIEW.md) for substantial changes. Check the specific sources, tests, attribution, and claim limits that apply. Give concrete revision requests and preserve useful negative results. Record what was independently checked and what still relies on the original inputs.

Merge only through the repository's configured review process. Update the README or index when the contribution materially changes a published summary. A merge is not a certificate that a claim is true.

## Check issue routing

The issue forms use `assignees: [cayde-6]`. GitHub supports this metadata for issues created through those forms. The chooser uses `blank_issues_enabled: false`; maintainers with write access or higher may still create blank issues. Issues created by API or other routes are not covered by form defaults. Check assignment during triage rather than promising universal auto-assignment.

Forms and PR templates become active on the default branch. A repository's local templates can override organization defaults, so inspect the actual chooser when provisioning or changing templates. Do not add a privileged workflow or token to compensate for an unverified configuration.

Official references: [issue form syntax](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/syntax-for-issue-forms), [template chooser configuration](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/configuring-issue-templates-for-your-repository), and [issue assignment](https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/assigning-issues-and-pull-requests-to-other-github-users).
