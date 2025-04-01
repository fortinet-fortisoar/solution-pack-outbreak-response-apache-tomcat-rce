# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 

# Overview 

FortiGuard Labs has identified ongoing attack attempts aimed at exploiting the recently discovered Apache Tomcat remote code execution vulnerability, CVE-2025-24813. If successful, attackers could gain access to sensitive security files, allowing them to view or inject arbitrary content and potentially execute code remotely on target systems. 

 The **Outbreak Response - Apache Tomcat RCE** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/2.0.0/docs/background-information.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*.

 The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/apache-tomcat-rce) contains information about the outbreak alert **Outbreak Response - Apache Tomcat RCE**. 

## Background: 

Exploit code for this vulnerability is publicly available, and no authentication is required to launch an attack, making prompt mitigation essential. According to Apache, successful exploitation requires specific conditions, and some of them may be enabled by default, allowing attackers to manipulate and view sensitive files or execute remote code. 

## Announced: 

Impacted users should implement the recommended mitigations provided by Apache and follow the instructions outlined in the vendor's advisory:

- Upgrade to Apache Tomcat 11.0.3 or later
- Upgrade to Apache Tomcat 10.1.35 or later
- Upgrade to Apache Tomcat 9.0.99 or later 

## Latest Developments: 

March 27, 2025: FortiGuard Labs released a Threat Signal
https://www.fortiguard.com/threat-signal-report/6053/apache-tomcat-rce

March 10, 2025: On March 10, 2025, Apache issued a security advisory regarding a critical vulnerability (CVE-2025-24813) affecting the Apache Tomcat web server.
https://lists.apache.org/thread/j5fkjv2k477os90nczf2v9l61fb0kkgq 

# Next Steps
 | [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) | 
 |--------------------------------------------|----------------------------------------------|------------------------|------------------------------|