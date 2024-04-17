<p align="center">
  <img src="https://github.com/SecurityBagel/SecurityBagel/blob/main/SecurityBagel.png"/>
</p>

# VulnBagel
A collection of dashboards, templates, API's and Power BI code for vulnerability management and analysis. 

## Vulnerability Templates
- Custom API to NIST NVD and automated feeds to public vulnerability and threat intelligence repositories.
- Product and vendor vulnerability lookup.
- Vulnerability statistics.
- CVSS calculator using advanced DAX measures.

## Coming Soon
- Vulnerability scanner API queries.
- Vulnerability prioritization methodologies.
- Patch metrics.

# Directions
1. Download the free Microsoft Power BI Desktop. (https://powerbi.microsoft.com/en-us/desktop/) 
2. Download the .pbit template file and run locally or publish to your Power BI Service.
3. Enter NIST NVD API Key. You can request an API Key from https://nvd.nist.gov/developers/request-an-api-key.
4. Enter your desired CVE Start Year (Example: 2022). The API's pull all CVEs at once, an earlier start year will take longer to load.

# Usage
- Learning and research.
- Use API and DAX code samples for your own projects.
- Integrate with your internal vulnerability scan results to enhance your organizations vulnerability management programs.
- Embedded in your vulnerability application with Power BI Embedded. (https://azure.microsoft.com/en-us/products/power-bi-embedded/)

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
- First.org
- Exploit-DB
  
Security Bagel is not affiliated or endorsed with associated organization. Please submit an issue if you find errors or bugs. 
