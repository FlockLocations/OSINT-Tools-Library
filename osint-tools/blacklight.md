---
description: >-
  Tool Description: A free website privacy-inspection tool that scans websites
  for tracking technologies.
---

# Blacklight

| **Blacklight**   | **Quick Overview**                                                                                                                     |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| URL              | [https://themarkup.org/blacklight](https://themarkup.org/blacklight)                                                                   |
| What it does     | Scans websites for tracking technologies and identifies third-party companies that may receive visitor data.                           |
| How to use it    | Enter a website address, select the inspection options, run the scan and review the detected trackers and privacy-related behaviours.  |
| Cost             | Free.                                                                                                                                  |
| Account required | No account required for website scans.                                                                                                 |
| Cookies          | None for ordinary browsing. Third-party donation services may use cookies.                                                             |
| Ownership        | Developed and operated by The Markup, a nonprofit newsroom that became part of CalMatters in 2024.                                     |
| Use in Reporting | Website privacy investigations, tracking analysis, identifying third-party data recipients and documenting potential privacy risks.    |

### What does Blacklight do?

Blacklight is a website privacy inspector that simulates a visitor browsing a website to identify tracking technologies and potential privacy-invasive behaviour. It helps reveal which companies may receive visitor information through advertising, analytics and other embedded scripts.&#x20;

The platform currently checks nine categories of tracking behaviour, including third-party cookies, advertising trackers, keylogging, session recording, canvas fingerprinting, Facebook tracking, Google Analytics remarketing audiences, and X and TikTok tracking pixels.

**The lowdown:** It’s ideal for auditing websites for advertising trackers, analytics scripts, browser fingerprinting and other technologies that may collect/share visitor’s data.

### How to Use:

**1. Enter the website address you want to inspect. Choose the available location and device options, such as desktop or mobile, where relevant.**

<img src="../.gitbook/assets/unknown (739).png" alt="" height="469" width="602">

**2. Run the scan and review the detected trackers, cookies, tracking pixels and other behaviours. Where available, inspect the associated third-party companies and network-request information.**

<img src="../.gitbook/assets/unknown (740).png" alt="" height="465" width="602">

**3. Record the results, scan date, website address and inspection settings. If accuracy or currency matters, use the option to force a fresh scan rather than relying on cached results, then corroborate significant findings with browser developer tools or other technical evidence.**        &#x20;

### Cost

* [x] Free
* [ ] Partially Free
* [ ] Paid

## Data Processing

### Account Required:

* [ ] Yes
* [x] No

No account required for website scans.&#x20;

### Cookies:&#x20;

None for ordinary browsing. Third-party donation services may use cookies.&#x20;

No cookies noted during our site session on 13 October 2026.

### Use in Reporting

Blacklight can be useful for:

* Identifying advertising and analytics trackers embedded in a website.
* Establishing which third-party companies may receive information about visitors.
* Detecting scripts associated with session recording, keylogging behaviour or browser fingerprinting.
* Checking for Facebook, Google, X and TikTok tracking technologies.
* Comparing privacy-related behaviour across websites, organisations or sectors.
* Supporting investigations into data collection practices on government, healthcare, education, nonprofit and commercial websites.
* Documenting potential privacy risks, generating leads and supporting further technical investigation.

As a real world example, investigators scanned more than 80,000 popular websites using Blacklight as documented in [The Markup’s reporting](https://themarkup.org/blacklight/2020/09/22/blacklight-tracking-advertisers-digital-privacy-sensitive-websites). They found widespread third-party tracking, including browser fingerprinting, session recording and scripts capturing text entered into forms. The investigation also examined tracking on sensitive websites, including healthcare and support services.

| **Capabilities**                                                                    | **Limitations**                                                                              |
| ----------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| Detects multiple categories of tracking technologies in one scan.                   | Only detects behaviours covered by its tests and current detection methods.                  |
| Identifies third-party domains and associated tracking companies.                   | A third-party request does not by itself prove that personal data was collected or misused.  |
| Tests for session recording, keylogging behaviour and browser fingerprinting.       | Cannot always determine the intent behind a script or whether every visit is recorded.       |
| Supports different device/location settings and fresh scans.                        | Results can differ by device, location, time, consent state and website configuration.       |
| Provides an open-source engine and batch-scanning option through Blacklight Query.  | Automated browsing differs from human activity and may trigger different website behaviour.  |

### Summary

Blacklight fits primarily into the verification and analysis stages of the OSINT workflow, with a secondary role in discovery. Its main value is helping investigators understand the tracking technologies embedded in a website and identify potential recipients of visitor data.&#x20;

**Note:** Blacklight's own documentation warns that results are an initial automated inspection and should not be treated as the final determination of a privacy violation.&#x20;

### Ownership

Blacklight was developed by [The Markup](https://themarkup.org/about), an American nonprofit investigative newsroom focused on the effects of technology on society. The organisation became part of [CalMatters](https://calmatters.org/) in 2024. Its work includes data-driven investigations, public-interest reporting and open-source tools.&#x20;

### Ethical Considerations

* Treat detected trackers as technical indicators, not proof of unlawful surveillance or deliberate misuse of data.
* Distinguish between a script being present and evidence that personal information was actually collected, transmitted or used.
* Record the scan date, device, location and caching settings because website behaviour can vary.
* Avoid repeatedly scanning websites in ways that create unnecessary load; Blacklight's caching is designed partly to limit this risk.
* Be careful when investigating sensitive websites, particularly healthcare, education or support services, where findings may reveal privacy risks affecting vulnerable users.
* Clearly separate observed technical behaviour from interpretations about intent, compliance or liability.

### Related Tools:

* BrowserLeaks
* [Cover Your Tracks](cover-your-tracks.md)
* [urlscan.io](urlscan.md)
* Wappalyzer
* BuiltWith

#### Sources

[https://themarkup.org/blacklight](https://themarkup.org/blacklight)&#x20;

[https://themarkup.org/about](https://themarkup.org/about)&#x20;

[https://calmatters.org/](https://calmatters.org/)&#x20;

[https://themarkup.org/blacklight/2020/09/22/blacklight-tracking-advertisers-digital-privacy-sensitive-websites](https://themarkup.org/blacklight/2020/09/22/blacklight-tracking-advertisers-digital-privacy-sensitive-websites)&#x20;

[https://x.com/themarkup](https://x.com/themarkup)
