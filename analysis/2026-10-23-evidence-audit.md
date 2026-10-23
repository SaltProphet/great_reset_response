# Research Cycle 4 — Audit of evidence, 2026-10-23

## Ranked observations
| Claim | Grade | Basis | Significant limitation |
|---|---|---|---|
| PHP2Shell critical flaws publicly patched Oct 21 | VERIFIED | AWS original vulnerability and response advisory | Vulnerability ≠ proof of breach at specific institution |
| Oct 17 pre-disclosure exploit attempt | VERIFIED as **AWS attribution** | Amazon MadPot threat report | Honeypot observation, not target-specific compromise |
| SoftBank emergency alerts suspended Oct 23 at 06:47 JST | VERIFIED | Original SoftBank statement, municipal warnings | Oct 26 restoration date was an estimate |
| Y!mobile/LINEMO homepage maintenance resolved Oct 22 17:30 JST | VERIFIED | Original SoftBank corporate statement | Separate service, not emergency warning |
| My SoftBank portal offline Oct 17–21 | VERIFIED | Original SoftBank operator notice | Operator attributed it to attempts at unauthorized access; PHP connection UNKNOWN |
| Nomura and MUFG online services restricted in PHP response | REPORTED | Reuters Oct 21–23 | Need original bank notifications; banking panic/compromise not established |
| WEF published 2020 digital currency governance consortium | VERIFIED | Original WEF Jan 24 2020 announcement | Framework advocacy, not an enforcement authority |
| WEF DCGC published CBDC interoperability principles | VERIFIED | WEF June 29 2023 report | Not evidence BIS Project Agora copied or implemented them |
| BIS Agorá July 2026 real-value test ~CHF 800K across 17 scenarios | VERIFIED | BIS Project Agorá project page | Wholesale controlled test, not consumer digital money |
| UK digitally verified right-to-work infrastructure | VERIFIED | Official 2026 certification code and government blog | Employer opt-in digital checks, not proof all work requires biometric credentials |

## Substantive corrected distinctions
**Three SoftBank events** differ in dates, services, and publicly stated reasons. Do not fold them into one incident.
**WAF vs patching:** Provider-managed firewall controls are partial; there is no proof this incident forces universal central authentication.
**Claims about bank panic:** Press reports of temporary website restrictions do not establish loss of customer deposits or inability to conduct core banking.
**Institutional relationship:** WEF consortium co-design ≠ law; BIS implementation ≠ WEF direction without an explicit cited connection.
**UK warning:** In prior conversation a blanket claim that the UK had canceled all digital identity work appeared. It is too broad; the September 2026 RtW Digital Verification Services supplementary code is publicly active. Investigate separately whether a proposed mandatory national ID program was canceled; do not conflate with voluntary employer-verification standards.

## Evidence sources (original where possible)
- AWS PHP disclosure: https://aws.amazon.com/blogs/security/using-aws-waf-to-apply-mitigations-for-php2shell-rce-vulnerabilities-cve-2026-109618-and-cve-2026-109619/
- AWS honeypot report: https://aws.amazon.com/blogs/security/amazon-threat-intelligence-identifies-php2shell-exploitation-prior-to-public-disclosure-in-madpot/
- SoftBank alert original: https://www.softbank.jp/corp/news/info/2026/20261023_01/
- SoftBank homepage update: https://www.softbank.jp/corp/news/info/2026/20261022_01/
- SoftBank My portal notice: https://www.softbank.jp/mobile/info/personal/news/support/20261017a/
- Local Japan government: https://www.city.hatsukaichi.hiroshima.jp/soshiki/3/146181.html
- WEF 2020: https://www.weforum.org/media/governing-the-coin-world-economic-forum-announces-global-consortium-for-digital-currency-governance
- WEF 2023: https://www.weforum.org/publications/central-bank-digital-currency-global-interoperability-principles/
- BIS real-value testing: https://www.bis.org/project/agora
- UK government Sept 2026 RtW code: https://www.gov.uk/government/publications/supplementary-code-for-digital-right-to-work-checks-1-1
- UK blog status of code in effect Sept 2: https://enablingdigitalidentity.blog.gov.uk/2026/09/03/updating-the-supplementary-codes-for-right-to-work-and-right-to-rent-to-version-1-1/

## Next research decision
Trace published primary source WEF DCGC recommendations to any **explicit** adoption/citation in BIS, government legislation, or procurement. In parallel obtain independent original bank notices, not further retellings of wire reports.
