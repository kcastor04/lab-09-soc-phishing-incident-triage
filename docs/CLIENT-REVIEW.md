# Client Review: Lab 09 SOC Phishing Incident Triage and Classification

This package was written from a two-point summary supplied by the portfolio owner. No lab guide, screenshots, alert exports or logs were provided, so every result in the README is marked **client-reported**. Please answer the questions below before publication.

## Decisions needed

| # | Decision | Options | Current default in the README |
|---|---|---|---|
| 1 | Approve the documentation style (same structure as the other labs) | Approve / request changes | Same structure as Labs 02, 03, 06 and 07 |
| 2 | Name the training platform and lab title | Platform name and exercise title, or keep unnamed | "Separate training platform; name not provided" |
| 3 | Confirm that "Alantra Financial Services" is a fictional scenario organization | Fictional / real / rename | Treated as the lab's scenario organization; a real financial firm uses the name "Alantra", so confirmation matters |
| 4 | Outcome of the third SIEM alert | Part of the FIN_FLOOR cluster / separate true positive / other | "Outcome not stated in the client summary" |
| 5 | VirusTotal detection ratio and lookup date | Provide values, or keep omitted | "Ratio not provided" |
| 6 | Supply your own screenshots or exports (see the README's evidence table) | Provide / none | No screenshots included |
| 7 | Confirm the lab was completed personally and the results are accurate | Confirm / correct | Presented as client-reported, not independently verified |
| 8 | GitHub owner, repository name and visibility | Owner, name, public or private | Suggested name: `lab-09-soc-phishing-incident-triage` |
| 9 | Permission to describe the platform's scenario publicly | Yes / no / restricted | Scenario described at summary level only |

## How the answers change the README

- **Platform and lab title:** added to the Evidence scope note, the Lab Context table and the Disclaimer.
- **Scenario organization:** if it is not fictional, or if you prefer, the name can be replaced with a neutral name such as "a financial services organization".
- **Third alert and VirusTotal ratio:** the "not provided" notes in Steps 4 and 6, the Key Findings table and the workflow diagram are replaced with your values.
- **Screenshots:** each image is checked for user names, email addresses, internal IP addresses, hostnames, token values and session data, then irreversibly redacted where needed and placed in the step it supports. The manifest records each file, its checksum and any redaction.
- **Confirmation of completion:** the "client-reported" wording can be softened to "completed by the portfolio owner on <platform>", while still not implying independent verification.

## Safety decisions already applied

- The phishing domain is defanged as `harvest-alantra[.]com` and is not a clickable link.
- The URL ends at `token=` as supplied; no token value is included or invented.
- No screenshots, log lines, alert IDs, timestamps, user names, host names or IP addresses have been created or simulated.
- The FCA and GDPR wording is limited to the lab scenario; no real regulatory filing or compliance claim is made.
- Method notes in the README describe the standard way each step is performed and are labeled as such, separate from the reported results.

## Unresolved gaps

- Platform, SIEM product and lab title
- Outcome of the third alert
- Exact VirusTotal detection ratio
- Affected user and host counts in the FIN_FLOOR cluster
- Content of the classification record and of the escalation
- Any evidence of completion
