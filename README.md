<p align="center"> <img src="https://raw.githubusercontent.com/qeeqbox/falcon/main/readme/falconlogo.png"></p>

#
[![Generic badge](https://img.shields.io/badge/dynamic/json.svg?url=https://raw.githubusercontent.com/qeeqbox/falcon/main/info&label=version&query=$.version&colorB=blue&style=flat-square)](https://github.com/qeeqbox/falcon/blob/main/changes.md) [![Generic badge](https://img.shields.io/badge/dynamic/json.svg?url=https://raw.githubusercontent.com/qeeqbox/falcon/main/info&label=number%20of%20exploits&query=$.count&colorB=green&style=flat-square)](https://github.com/qeeqbox/falcon/blob/main/changes.md) [![Generic badge](https://img.shields.io/static/v1?label=%F0%9F%91%8D&message=!&color=yellow&style=flat-square)](https://github.com/qeeqbox/falcon/stargazers)

Collection of exploits that were verified by an automated system (It monitors different honeypots and feeds for new\potential exploits). The results are optimized python modules that can be integrated into your Vulnerability Intelligence Scanner. 

## Current Exploits
<table>
  <tr><td>Critical</td><td>CVE-2020-14882</td><td>Oracle WebLogic Server Under Active Exploitation (RCE)</td></tr>
  <tr><td>High</td><td>CVE-2020-13935</td><td>Apache Tomcat Denial of Service</td></tr>
  <tr><td>High</td><td>CVE-2020-3452</td><td>Cisco Adaptive Security Appliance Directory Traversal</td></tr>
</table>

## Install and run
```bash
git clone https://github.com/qeeqbox/falcon.git
cd falcon
```

## Severity Table
![](https://raw.githubusercontent.com/qeeqbox/falcon/main/readme/cve_table_qeeqbox_falcon.png)

## Resources
- https://cve.mitre.org
- https://nvd.nist.gov
- https://www.rapid7.com/db/?type=nexpose

## Disclaimer\Notes
- Please patch your systems ASAP
- All exploits will be posted here as python scripts
- Please contact me if I missed a reference or resource so I add them
- Some exploits might have external write-ups (please check Resources or search about them)
