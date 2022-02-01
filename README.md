# Fix pack for SPSS log4j vulnerabilities

Applies the log4j 2.17.1 fixes recomended by IBM for log4j vulnerabilities (Security bulletin copied below).

There is a prebuilt signed pkg located in the build directory. You can deploy it using whatever means.

** created using [munkipkg](https://github.com/munki/munki-pkg)

---

Document Source: https://www.ibm.com/support/pages/apache-log4j-cve-2021-44228-vulnerability-ibm-spss-statistics
Sourced on: 1/3/22

> # Apache Log4j CVE-2021-44228 vulnerability in IBM SPSS Statistics
>
> ## News
>
> ### Abstract
>
> IBM is actively responding to the reported remote code execution vulnerability in the Apache Log4j 2 Java library dubbed Log4Shell (or LogJam).
>
> The IBM SPSS Statistics Development team produced interim fixes for our currently supported versions, updating the Log4j .jar files to version 2.17.1. This version resolves CVE-2021-44228, CVE-2021-45046, CVE-2021-45105, and CVE-2021-44832 vulnerabilities.
>
> NOTE: These fixes are updated to include Log4j version 2.17.1. If you have downloaded fixes from this note before 18 January 2022, download and apply these new, updated fixes.
>
> ### Content
> **IBM SPSS Amos, IBM SPSS Data Access Pack, and the IBM SPSS Concurrent License Manager and Tools products are not affected by this issue.**
>
> An interim fix now exists for each of the currently supported releases of IBM SPSS Statistics. Supported versions are release 25.0 and later.  If you have deployed IBM SPSS Statistics 24.0 or earlier, these versions are end of service and are no longer supported.  Upgrade to a supported release.
>
> Update your version of IBM SPSS Statistics to the latest Fixpack (or Modified Release).
>
>   * For example, if you have SPSS Statistics 27.0 deployed, update it to Statistics 27.0.1 before applying the associated interim fix.
>   * IBM SPSS Statistics Subscription updates via the "Help -> Check for updates" menu item.  The interim fix found here applies to IBM SPSS Statistics Subscription release 28.0.1.0 (142) . If you are not at that release, please update to it before applying this interim fix.
>
> If you do not know your current release and Fixpack level,
> See: [how-do-i-identify-my-spss-product-releasebuild](https://www.ibm.com/support/pages/how-do-i-identify-my-spss-product-releasebuild)
>
> #### Fixpacks and Modified Releases:
> IBM SPSS Statistics 28.0 Modified Release 1: [https://www.ibm.com/support/pages/node/6507707](https://www.ibm.com/support/pages/node/6507707)
> IBM SPSS Statistics 27.0 Modified Release 1: [https://www.ibm.com/support/pages/node/6351067](https://www.ibm.com/support/pages/node/6351067)
> IBM SPSS Statistics 26.0 Fixpack 1: [https://www.ibm.com/support/pages/node/961766](https://www.ibm.com/support/pages/node/961766)
> IBM SPSS Statistics 25.0 Fixpack 2: [https://www.ibm.com/support/pages/spss-statistics-250-fix-pack-2](https://www.ibm.com/support/pages/spss-statistics-250-fix-pack-2)
>
> #### Interim Fixes
> Download the interim fix, extract it and find the "Readme" file for installation instructions.
>
> IBM SPSS Statistics 28.0.1.0, IF 009:  [IF 28.0.1.0-9](https://www.ibm.com/support/fixcentral/quickorder?product=ibm%2FInformation+Management%2FSPSS+Statistics&fixids=28.0.1-IM-S28STATC-ALL-IF009&source=SAR)
> IBM SPSS Statistics Subscription:  [IF for Subscription](https://www.ibm.com/support/fixcentral/quickorder?product=ibm%2FInformation+Management%2FSPSS+Statistics&fixids=27.0.1-IM-S27STATC-ALL-IF023&source=SAR)
> IBM SPSS Statistics 27.0.1.0, IF 023:  [IF 27.0.1.0-23](https://www.ibm.com/support/fixcentral/quickorder?product=ibm%2FInformation+Management%2FSPSS+Statistics&fixids=27.0.1-IM-S27STATC-ALL-IF022&source=SAR)
> IBM SPSS Statistics 26.0.0.1 (Windows) or 26.0.0.2 (macOS), IF 017:  [IF 26.0.1-017](https://www.ibm.com/support/fixcentral/quickorder?product=ibm%2FInformation+Management%2FSPSS+Statistics&fixids=26.0-IM-S26STAT-ALL-FP001-IF017&source=SAR)
> IBM SPSS Statistics 25.0.0.2, IF 017:  [IF 25.0.0.2-17](https://www.ibm.com/support/fixcentral/quickorder?product=ibm%2FInformation+Management%2FSPSS+Statistics&fixids=25.0-IM-S25STAT-ALL-FP002-IF017&source=SAR)
