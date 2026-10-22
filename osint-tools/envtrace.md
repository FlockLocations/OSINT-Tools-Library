---
description: >-
  Tool Description: A browser-based toolkit for checking browser fingerprints,
  IP addresses, and network signals.
---

# EnvTrace

| **EnvTrace**     | **Quick Overview**                                                                                                                                                        |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| URL              | [https://envtrace.net/](https://envtrace.net/)                                                                                                                            |
| What it does     | Shows fingerprint signals, exit IP/proxy traits, WebRTC/DNS leaks, timezone/language mismatches and automation traces.                                                    |
| How to use it    | Open the site in the profile you will use, read the health score, and fix flagged mismatches.                                                                             |
| Cost             | Free.                                                                                                                                                                     |
| Account required | No.                                                                                                                                                                       |
| Cookies          | Google Analytics 4 cookies.                                                                                                                                               |
| Ownership        | Independent project by TX Wu. Not affiliated with any antidetect browser vendor.                                                                                          |
| Use in Reporting | Investigator operational security, browser-fingerprint assessment, IP/network verification, leak testing and documenting the technical environment used during research.  |

### What does EnvTrace do?

EnvTrace is a browser and connection self-audit for investigators running sock-puppet or research profiles. It shows the fingerprint signals, exit IP/proxy traits, WebRTC/DNS leaks and timezone/language mismatches a target site can see, and checks for automation traces.

**The lowdown:** It’s an OPSEC and pre-investigation diagnostic tool rather than a tool for discovering information about a target.

### How to Use:

**1. Simply open the site in the browser profile you plan to use (behind your VPN/proxy) and allow it to run the scan.**

<img src="../.gitbook/assets/unknown (734).png" alt="" height="469" width="602">

**2. Read the health score and fix flagged mismatches before logging in to the target platform.**&#x20;

<img src="../.gitbook/assets/unknown (735).png" alt="" height="524" width="602">

### Cost

* [x] Free
* [ ] Partially Free
* [ ] Paid

## Data Processing

### Account Required:

* [ ] Yes
* [x] No

### Cookies:&#x20;

Testing identified Google Analytics 4 cookies on .envtrace.net: \_ga, which distinguishes browsers for visitor measurement, and \_ga\_RXC848HY0P, which persists Analytics session state. These cookies support website usage measurement rather than the browser-fingerprint or network-test results themselves.

### Use in Reporting

EnvTrace can be useful for:

* Assessing an investigator's browser fingerprint and how distinctive the browser may appear to websites.
* Checking whether a VPN or proxy connection exposes unexpected IP or network information through WebRTC or DNS.
* Verifying the apparent IP address, network provider, connection type and approximate location of the research environment.
* Checking whether browser timezone, language and regional settings are consistent with the current environment.
* Identifying technical privacy issues that could compromise the confidentiality of an investigation.
* Recording the browser and network conditions under which online research was conducted.
* Supporting operational security checks before accessing sensitive sources or using investigative accounts.

Note from the Developer: Investigators can open EnvTrace in a sock-puppet or research profile before logging in to a target platform, then read the health score and fix flagged mismatches. Scores are heuristics, not a guarantee against platform detection. No published third-party case study is claimed.

| **Capabilities**                                                         | **Limitations**                                                                        |
| ------------------------------------------------------------------------ | -------------------------------------------------------------------------------------- |
| Browser fingerprint signals, alongside exit IP and proxy quality traits. | Checks your own browser and connection only, not third parties.                        |
| WebRTC and DNS leak check.                                               | IP lookup runs server-side; results are not stored.                                    |
| Timezone and language match.                                             | Scores are heuristics, not a guarantee against platform detection.                     |
| Automation traces.                                                       | Results reflect the current browser and network configuration at the time of testing.  |
| One health score.                                                        | <p><br></p>                                                                            |

### Summary

EnvTrace fits primarily into the preparation and OPSEC stages of the OSINT workflow, with a secondary role in verification and technical Troubleshooting. Its main value is helping investigators understand the technical signals exposed by their own browser and network before conducting research.&#x20;

### Ownership

Independent project by TX Wu. Not affiliated with any antidetect browser vendor.

Contact: contact@envtrace.net

### Ethical Considerations

* Use EnvTrace primarily to assess your own browser, device and network environment, not third parties.
* Do not use it to collect or share someone else’s personal data.
* IP lookup runs server-side; results are not stored.
* Scores are heuristics and not a guarantee against platform detection.

### Related Tools:

* BrowserLeaks
* CreepJS
* IPleak

#### Sources

[https://envtrace.net/](https://envtrace.net/)&#x20;



_With thanks to TX Wu for submitting this tool to the OSINT Tool Library._

\
<br>
