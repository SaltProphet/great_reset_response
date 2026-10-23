# PHP2Shell incident register — reviewed 2026-10-23

## Severity and technical remediation — VERIFIED
On 2026-10-21, PHP published fixes for CVE-2026-109618 and CVE-2026-109619, rated critical (CVSS v4.0 9.2). AWS documents the affected server-side request paths and fixed PHP 8.5.12, 8.4.27, 8.3.36 and 8.2.35. Patching is the *only complete fix*; WAF is partial mitigation. 
- AWS primary advisory: https://aws.amazon.com/blogs/security/using-aws-waf-to-apply-mitigations-for-php2shell-rce-vulnerabilities-cve-2026-109618-and-cve-2026-109619/
- AWS threat intelligence observed an apparent Oct 17 exploit attempt in a honeypot. This is *not evidence that a particular bank or carrier was breached*: https://aws.amazon.com/blogs/security/amazon-threat-intelligence-identifies-php2shell-exploitation-prior-to-public-disclosure-in-madpot/

## SoftBank — VERIFIED from operator and municipalities
**Emergency alerts:** SoftBank's original notice (dated 2026-10-23) confirms emergency suspension of its mobile emergency alert messages while maintaining its PHP-dependent service, beginning **06:47 JST on Oct 23**, with Oct 26 only a *projected* end. Scope: SoftBank, Y!mobile and LINEMO customers; earthquake/tsunami/evacuation alerts via the affected carrier service. SoftBank directs customers to alternate warning services.
- Operator primary statement: https://www.softbank.jp/corp/news/info/2026/20261023_01/
- Local government confirmation: https://www.city.hatsukaichi.hiroshima.jp/soshiki/3/146181.html
- No restoration confirmation yet verified as of Oct 23.

**Other separate events that must not be conflated:**
- SoftBank temporarily shut *My SoftBank* website from **Oct 17, 08:00 JST** through **Oct 21, approx. 21:00 JST** after noticing unauthorized third-party access attempts against part of its system; the mobile app remained available. The operator does *not* attribute this outage to the Oct 21 PHP vulnerability disclosure. PHP-related linkage remains UNKNOWN. https://www.softbank.jp/mobile/info/personal/news/support/20261017a/
- SoftBank confirms that PHP maintenance temporarily suspended Y!mobile and LINEMO *official website homepages* and that they reopened Oct 22 at **17:30 JST**. This is distinct from emergency-alert delivery and My SoftBank account website. https://www.softbank.jp/corp/news/info/2026/20261022_01/

## Banking — REPORTED; primary confirmation gap
Reuters reports temporary online-service restrictions across Japanese organizations including Nomura and Mitsubishi UFJ Financial Group following PHP security response, but bank-authored notices establishing exact product scope, duration, restoration, or data loss were **not retrieved** in this cycle.
- Reuters original Oct 21: https://www.reuters.com/technology/websites-taken-offline-over-php-risks-2026-10-21/
- Reuters Oct 22: https://www.reuters.com/world/asia-pacific/cloudflare-sees-millions-exploit-attempts-after-php-disclosure-2026-10-22/
- Reuters Oct 23: https://www.reuters.com/business/media-telecom/japan-simulate-cyberattacks-php-flaws-roil-global-internet-2026-10-23/

**UNKNOWN:** No evidence reviewed demonstrates stolen bank deposits, collapse of settlement infrastructure, confirmed bank breach from PHP2Shell, or a bank-wide crisis. Corporate caution is consistent with defensive isolation.

## Institutional response — VERIFIED vs INFERRED
- **VERIFIED:** CISA/other national agencies and major platform providers issued urgent remediation guidance; SoftBank and municipalities published access alternatives.
- **REPORTED:** Japan announced work on AI-enabled simulation of cyberattacks following the wider event (Reuters Oct 23); seek dated government order/budget before claiming implementation.
- **INFERRED:** The incident could accelerate central hosting and compliance dependencies, but **no sourced order, contract or implementation** establishes this as an effect yet.
- **NOT ESTABLISHED:** a Great Reset/WEF operational direction behind either outage or remediation.

## Next evidence requests
1. Original operator statements from Nomura / MUFG and dated service restoration logs.
2. Japanese ministry's announcement and precise legal/funding status of proposed AI cyber team.
3. SoftBank's actual emergency-alert restoration report after Oct 26; do not assume restoration before verification.
4. Identify confirmed compromise vs attempted attacks vs precautionary shutdowns per organization.
5. Record any *actual* new credential, payment-access or identity mandates adopted in response to PHP2Shell, with date and authority.
