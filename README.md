# HTTP 301/302 Redirect and Hop Chain Auditor

[![Redirect 301 Tracker](https://img.shields.io/badge/TAVARDT-Redirect%20301-5b3cf5.svg)](https://tools.tavardt.com/ca/redirect-checker/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Audits bilingual redirect routing, infinite loop detection, link equity preservation, and latency.

***

## HTTP Redirect and Hop Chain Audit Capabilities

* **Bilingual Routing and Hop Chain Tracing**: Full hop-by-hop auditing across bilingual English and French routes and international targets.
* **Infinite Redirect Loop Detection**: Immediate identification of cyclic paths causing critical browser and crawler failures.
* **Link Equity and PageRank Conservation**: Alerts against long redirect chains (> 3 hops) that dilute equity and waste crawl budget.
* **Mixed Protocol Verification**: Identification of insecure intermediary downgrades from HTTPS to HTTP.
* **Redirect Efficiency Health Score**: Quantitative 0 to 100 score with prioritized technical remediation steps.

***

## Installation and Execution

Requires Python 3.8 or higher.

```bash
git clone https://github.com/TAVARDT-Canada/redirect-301-tracker-ca.git
cd redirect-301-tracker-ca
python redirect_tracker.py https://company.ca
```

To output results in structured JSON format:

```bash
python redirect_tracker.py https://company.ca -json
```

***

## Technical SEO and Site Migration Advisory

For Canadian federal and enterprise platforms aligning with W3C Standards and Canadian Digital Guidelines, contact the specialists at **TAVARDT**.

***

## Useful Links

* **Corporate Portal:** https://ag.tavardt.com/ca/
* **Diagnostic Suite:** https://tools.tavardt.com/ca/
* **Technical Contact:** https://ag.tavardt.com/ca/contact/

***

### License
Released under the MIT License.

***

© 2026 TAVARDT. All rights reserved.
