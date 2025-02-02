<p align="center">
  <img src="https://github.com/SecurityBagel/SecurityBagel/blob/main/SecurityBagel.png"/>
</p>

# VulnBagel
A collection of Power BI templates, reports, and dashboards for vulnerability and patch management 

# Directions
1. Download the free Microsoft Power BI Desktop. (https://powerbi.microsoft.com/en-us/desktop/) 
2. Download the .pbit or .pbix template file and run locally or publish to your Power BI Service.

# Features
- API queries to sync with NIST NVD and EPSS.
- Vulnerability exploit intelligence feeds from CISA KEV and Exploit-DB.
- Product and vulnerability lookup and metrics.
- App like navigation with exploit drillthrough details and web links.
- Filters for multi-criteria vulnerability prioritization. (Base CVSS + Environmental, Exploit Probability(EPSS), and exploit metadata)
- CVSS environmental metric scoring with NVD base score correlation for asset context.
- Priorization metrics for Effort and Exploit Coverage.
- Patch metrics with advanced analytics.

# Contact
Damian Mehsling: https://www.linkedin.com/in/damianmehsling/, secbagel@securitybagel.io

# Data Sources
- NIST CVEs and CPEs:
  - Note: You will need need an API key
  - API Custom Query: https://services.nvd.nist.gov/rest/json/cves/2.0
- Exploit-DB:
  - Web: https://gitlab.com/exploit-database/exploitdb
- CISA KEV:
  - Web: https://www.cisa.gov/sites/default/files/feeds/known_exploited_vulnerabilities.json
- EPSS:
  - API Custom Query: https://api.first.org/data/v1/epss

# Contributing
- If you find errors, please fork the repo and create a pull request or open an issue. Thanks!
- Sponsor or donate: https://github.com/sponsors/SecurityBagel
- Want to help? Have Ideas? template and additional features, example datasets, test environment (Tenable, Nessus, OpenVAS, Nexpose)
- If you have a Power BI vulnerability scanner query or connector please consider sharing for the community!
  
# Acknowledgements
- NIST
- CISA
- First.org
- Exploit-DB
  
Security Bagel is not affiliated or endorsed with associated organizations. Please submit an issue if you find errors or bugs. 
