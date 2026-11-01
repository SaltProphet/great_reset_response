# PHP2Shell & AI Access Watch

**Monitoring specification established:** 2026-10-29  
**Latest synchronized baseline:** 2026-11-01  
**Scope boundary:** security, access, and governance monitoring—not attribution of coordinated intent.

This watch extends the existing [PHP2Shell incident register](php2shell-2026-10.md). It tracks how a critical web-runtime vulnerability can affect the credentials, data, tools, and service access surrounding independently hosted models and AI agents. It does **not** treat a vulnerability, a model capability evaluation, or a provider-access dispute as evidence of a common cause.

## Monitoring questions

1. **PHP2Shell remediation and exploitation:** What is officially fixed, exploited, or only reported? Which service interruptions are preventive isolation rather than confirmed compromise?
2. **Local inference and open weights:** Are there material changes to the availability, deployment, or evaluation of downloadable models that affect independent operation?
3. **Agent identity and delegated access:** What controls exist for agent identity, short-lived credentials, revocation, least privilege, audit, and execution isolation? Are they announced, preview-only, or operating in production?
4. **Service-provider enforcement:** How do platforms distinguish authorized integrations from unidentified automation, credential reuse, scraping, or other non-permitted access?
5. **Policy and law:** What enacted rules, proposed rules, or official consultations materially affect model access, cybersecurity research, or technology transfer?

## Latest synchronized assessment

The dated [November 1 assessment](../analysis/2026-11-01-php2shell-ai-access-assessment.md) synchronizes this watch with the Google Drive source ledger as read on 2026-11-01.

The latest selective checks record **no consequential new evidence**: PHP2Shell remains an active-exploitation and patching issue; no additional successful production compromise, universal agent-identity mandate, general private local-inference prohibition, or PHP2Shell-to-AI-policy causal link was established. The ledger does record IBM's October 27 enterprise identity/control announcement as a previously missed, non-consequential provider-specific development. The ledger remains the controlling source for the full chronology, source URLs, evidence grades, corrections, and monitoring notes.

## Evidence standard

Every entry must record:

| Field | Requirement |
|---|---|
| Primary evidence | Official advisory, vendor release, statute/regulator, incident notice, or original technical research where available |
| Dates | Keep event date, publication date, and monitor-observation date separate |
| Status | Label as **VERIFIED**, **REPORTED**, **INFERRED**, or **UNKNOWN** |
| Operational state | Distinguish proposal, preview, pilot, deployed control, and observed enforcement |
| Scope | Identify affected systems/people, jurisdiction, and exclusions |
| Counterevidence | Preserve limits, alternative explanations, and facts that weaken a claim |
| Baseline comparison | Classify as new, previously missed, unchanged, or timing unknown; do not infer timing from discovery alone |

## Current baseline

### PHP2Shell

- CVE-2026-109618/109619 remain critical PHP RCE vulnerabilities affecting exposed management interfaces.
- Palo Alto's October 29 advisory records active exploitation and fixed builds; this is attack evidence, not proof of a newly confirmed named production victim.
- AWS records pre-disclosure honeypot exploitation activity; the evidence does not identify a compromised production target.
- UK Hansard records 32 government services unavailable and four partially unavailable during precautionary response; it also records no known confirmed central-government compromise at that time.
- SoftBank's PHP-related service interruptions and its separate Oct 17–21 account-site incident remain distinct.

### Agent access and identity

- NIST identity/standards work, Microsoft governance, RSA Agent ID, Proof x401, IBM enterprise Vault controls, and transaction-specific services demonstrate different scopes.
- Provider announcements establish stated capability, policy, or planned availability only; arbitrary self-hosted-agent effectiveness remains **UNKNOWN**.
- Local-model support and open-weight releases remain counterevidence to a blanket-closure theory.

## Required reporting format

Each monitoring result should state:

1. Check timestamp and previous verified baseline.
2. Whether the previous run's completion was independently verifiable.
3. Qualified findings first, with direct source links.
4. A clear distinction among observed facts, reported claims, and analysis.
5. A practical action limited to the evidence.
6. A source-ledger status, including any inaccessible source or unperformed persistence step.

## Handling source gaps

- Do not treat an unavailable ledger, inaccessible document, missing vendor notice, or absent execution log as proof that nothing happened.
- Do not claim a persistent update unless the target storage was written and read back successfully.
- When only secondary reporting is available, preserve the primary-confirmation gap and avoid extending the claim beyond that report.
- Record no-change results only for the sources and areas actually checked.

## Out of scope

This watch does not establish:

- that PHP2Shell was used in every reported outage or intrusion;
- that locally hosted models caused or participated in a PHP2Shell incident;
- that shared terminology, timing, or institutions prove coordination;
- that a product announcement equals operational deployment;
- that a proposed policy is legally binding.

## Next evidence priorities

1. Maintain the PHP2Shell register with original vendor remediation and restoration records.
2. Capture documented production deployments of agent identity, delegated authorization, credential expiration/revocation, and containment controls.
3. Preserve original platform policies or enforcement statements when an agent is denied or permitted access.
4. Track enacted law separately from consultations, draft controls, and policy discussion.
5. Evaluate the exact model and configuration when cyber-capability claims affect a local-agent risk assessment.
