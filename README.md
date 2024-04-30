<p align="center">
  <img src="https://github.com/SecurityBagel/SecurityBagel/blob/main/SecurityBagel.png"/>
</p>

# VulnBagel - In Progress
A collection of dashboards, templates, API's and Power BI code for vulnerability management and analysis. 

# Goals
Retrieve open source vulnerability data provided by NIST, CISA, FIRST.org, and Exploit-DB.
Allow adjustment of the date range and EPSS/CVSS variables.
View and prioritize by exploitation information.
Prioritization metrics for risk-based vulnerability decisions. 
CVSS Environmental Scoring with asset context.
     
## Coming Soon
- Vulnerability scanner API queries.
- Vulnerability prioritization methodologies.
- Patch metrics.
- SSVC guidance.

# Directions
1. Download the free Microsoft Power BI Desktop. (https://powerbi.microsoft.com/en-us/desktop/) 
2. Download the .pbit template file and run locally or publish to your Power BI Service.
3. Enter NIST NVD API Key. You can request an API Key from https://nvd.nist.gov/developers/request-an-api-key.
4. Enter your desired CVE Start Year (Example: 2022). The API's pull all CVEs at once, an earlier start year will take longer to load.

# Usage
- API queries to sync with NIST NVD and EPSS.
- Vulnerability exploit intelligence feeds from CISA KEV and Exploit-DB.
- Product and vulnerability lookup and metrics.
- App like navigation with exploit drillthrough details and web links.
- Filters for multi-criteria vulnerability prioritization. (Base CVSS + Environmental, Exploit Probability(EPSS), and exploit metadata)
- CVSS environmental metric scoring with NVD base score correlation for asset context.
- Priorization metrics for Effort and Exploit Coverage.

# Contact
Damian Mehsling: https://www.linkedin.com/in/damianmehsling/, secbagel@gmail.com

## Data Sources
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
- If you have suggestions, feedback, or find errors, please fork the repo and create a pull request or open an issue. Thanks!
- Sponsor or donate: https://github.com/sponsors/SecurityBagel
  
# Acknowledgements
- NIST
- CISA
- First.org
- Exploit-DB
  
Security Bagel is not affiliated or endorsed with associated organization. Please submit an issue if you find errors or bugs. 
