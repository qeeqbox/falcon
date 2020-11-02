<p align="center"> <img src="https://raw.githubusercontent.com/qeeqbox/falcon/main/readme/falconlogo.png"></p>

#
[![Generic badge](https://img.shields.io/badge/dynamic/json.svg?url=https://raw.githubusercontent.com/qeeqbox/falcon/main/info&label=version&query=$.version&colorB=blue&style=flat-square)](https://github.com/qeeqbox/falcon/blob/main/changes.md) [![Generic badge](https://img.shields.io/badge/dynamic/json.svg?url=https://raw.githubusercontent.com/qeeqbox/falcon/main/info&label=number%20of%20exploits&query=$.count&colorB=green&style=flat-square)](https://github.com/qeeqbox/falcon/blob/main/changes.md) [![Generic badge](https://img.shields.io/static/v1?label=%F0%9F%91%8D&message=!&color=yellow&style=flat-square)](https://github.com/qeeqbox/falcon/stargazers)

Falcon is an automated CVE hunter system that monitors different honeypots and feeds for new CVEs (This repo contains the results ONLY)

## Current Exploits
<table>
  <tr>
  <td>Critical</td>
  <td>CVE-2020-14882</td>
  <td>Oracle WebLogic Server Under Active Exploitation (RCE)</td>
  </tr>
   <tr>
  <td>Medium</td>
  <td>CVE-2020-13935</td>
  <td>Apache Tomcat Denial of Service</td>
  </tr>
</table>

## Install and run
```bash
git clone https://github.com/qeeqbox/falcon.git
cd falcon
CVE-2020-14882.py
```

## Severity Table
![](https://raw.githubusercontent.com/qeeqbox/falcon/main/readme/cve_table_qeeqbox_falcon.png)

## Disclaimer\Notes
- Please patch your systems ASAP
- All exploits are posted here as python script for educational purposes
