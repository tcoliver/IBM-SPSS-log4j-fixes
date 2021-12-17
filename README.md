# Fix pack for SPSS log4j vulnerabilities

Applies the fixes recomended by IBM for log4j vulnerabilities (Security bulletin copied below).

There is a prebuilt signed pkg located in the build directory. You can deploy it using whatever means.

** created using [munkipkg](https://github.com/munki/munki-pkg)

---

Document Source: https://www.ibm.com/support/pages/node/6526182

> ## Security Bulletin: Log4Shell Vulnerability affects IBM SPSS Statistics (CVE-2021-44228)
>
> ### Summary
>
> There is a vulnerability in the version of Log4j that is part of IBM SPSS Statistics. IBM SPSS > Statistics has addressed this vulnerability.
>
> ### Vulnerability Details
> **CVEID**: CVE-2021-44228
> **DESCRIPTION**: Apache Log4j could allow a remote attacker to execute arbitrary code on the system, caused by the failure to protect against attacker controlled LDAP and other JNDI related endpoints by JNDI features. By sending a specially crafted code string, an attacker could exploit this vulnerability to load arbitrary Java code on the server and take complete > control of the system. Note: The vulnerability is also called Log4Shell or LogJam.
> CVSS Base score: 10
> CVSS Temporal Score: See: https://exchange.xforce.ibmcloud.com/vulnerabilities/214921 for the > current score.
> CVSS Vector: (CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:C/C:H/I:H/A:H)
>
> ### Affected Products and Versions
> | Affected Product(s) | Version(s) |
> | --------------------|------------|
> | SPSS Statistics     | 28.0.1     |
> | SPSS Statistics     | 27.0.1     |
> | SPSS Statistics     | 26.0       |
> | SPSS Statistics     | 25.0       |
>
> ### Remediation/Fixes
>
> | Affected Product(s)	| Version(s) | Fixes                        |
> | --------------------| ---------- | ---------------------------- |
> | SPSS Statistics	    | 28.0.1	 | Statistics 28.0.1-IF003      |
> | SPSS Statistics	    | 27.0.1	 | Statistics 27.0.1-IF019      |
> | SPSS Statistics	    | 26.0	     | Statistics 26.0.0.1-IF013    |
> | SPSS Statistics	    | 25.0	     | Statistics 25.0.0.2-IF013    |


