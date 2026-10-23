# UK digital verification: cross-system control points — 2026-10-23 primary-source audit

## Why this is the highest-value lead
It provides a traceable public architecture for **trust decisions across different services** rather than merely showing similar technologies or overlapping conference attendees. Sources are UK official documents and legislation, not retrospective forecasts.

## VERIFIED regulatory state as at 2026-10-23
- **September 2, 2026:** Digital Verification Services trust framework v1.0 and right-to-work/right-to-rent supplementary codes 1.1 came into force, confirmed by OfDIA Sept 3 notice. Providers can seek certification; if employers/landlords **choose** digital verification routes, applicable regulations require use of a certified, registered provider for the statutory defense. This is not a general mandate for all citizens to hold a biometric ID. https://enablingdigitalidentity.blog.gov.uk/2026/09/03/updating-the-supplementary-codes-for-right-to-work-and-right-to-rent-to-version-1-1/
- Same government notice says **holder services can verify that an individual carrying out work already passed a right-to-work check**, potentially facilitating **continuous checks** and proof to entities other than their direct employer under extended-liability rules. A legal work-eligibility check is distinct from AI productivity monitoring or a behavioral score.
- **October 21, 2026:** Draft Code of Practice for an *information gateway* under section 45, Data (Use and Access) Act 2025, laid before Parliament. The planned power would permit qualifying public authorities to share information with registered private-sector Digital Verification Services, including government-issued credentials for private wallets and individual attribute/status responses subject to conditions. **The code is draft; both Houses' approval and commencement were prospective** at Oct 23, not yet an operational mandate. HMRC and certain devolved tax bodies explicitly excluded from expected commencement this year. https://enablingdigitalidentity.blog.gov.uk/2026/10/21/the-draft-code-of-practice-for-the-information-gateway-has-been-laid-in-parliament/
- Source statute/code: https://www.gov.uk/government/publications/draft-code-of-practice-for-public-authorities-sharing-information-with-digital-verification-services

## VERIFIED published technical architecture; TESTING/DEVELOPMENT not universal deployment
OfDIA September 29 technical testing announcement states it is **developing** a machine-readable register with two models:
1. **API/federation model:** Registered provider connects to an authority or relying party. mTLS, X.509 certificates, OpenID Federation, JWT-signed statements, and registration checks support trust. Other services may reject a provider if validation fails.
2. **Wallet/credential model:** Issuer and verifier trust is established via VICAL and RICAL signed lists; wallet or reader checks authorization before exchanging verified credentials.
3. **Revocation:** When a *provider* is removed from the register, its transport certificate is revoked and subordinate federation statements stop being published; relying systems stop trusting it when fresh evidence is checked or cached credentials expire.
4. **Offline:** Some certified service assertions may be cached to support offline transactions **within validity/refresh limits**. No claim that all independent/offline use becomes impossible.
5. **Important boundary:** The revocation described above concerns **service provider trust**, not a universal citizen behavioral score or automatic revocation of all of a person's credentials.

Official source: https://enablingdigitalidentity.blog.gov.uk/2026/09/29/help-us-test-the-dvs-registers-machine-readable-infrastructure/

## Interpretation
- **VERIFIED**: UK is standardizing cross-organization identity-verification trust and designing credential/attribute data links, some of which are now enabled in regulation.
- **INFERRED**: This could make a shared digital eligibility layer increasingly important to access in work, renting or government-facing services.
- **UNKNOWN**: actual percentage of employers requiring these checks, effects on excluded applicants, and whether offline or non-digital alternatives are materially disadvantaged.
- **NOT ESTABLISHED**: a cross-sector behavioral scoring database, linking worker output to public benefit eligibility, compulsory face biometric upload, WEF direction over these UK rules, or a Great Reset single implementation command.

## Primary-source research questions
- What alternatives are available in regulated right-to-work/right-to-rent workflows, and are they equally functional?
- Once Section 45 is commenced, which public authorities sign data-sharing agreements? What attributes are requested and how often?
- Can a revoked provider's customers transfer credentials to another provider without losing access?
- Which specific contractual or policy changes mention the WEF standards? Search legislative impact assessments, consultation responses and procurement ledgers before claiming influence.
