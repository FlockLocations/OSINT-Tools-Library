---
description: >-
  Tool Description: A free web-based utility for executing and testing
  individual PHP functions without installing PHP locally.
---

# Functions Online

| **Functions Online** | **Quick Overview**                                                                                                                                    |
| -------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| URL                  | [https://www.functions-online.com/](https://www.functions-online.com/)                                                                                |
| What it does         | Executes selected PHP functions for encoding/decoding, hashes, regular expressions, timestamps, URL/DNS processing, JSON and geographic calculations. |
| How to use it        | Select a function, enter the required parameters, execute it and inspect the returned output.                                                         |
| Cost                 | Free.                                                                                                                                                 |
| Account required     | No for basic use.                                                                                                                                     |
| Cookies              | A mix of Google advertising-security and cookie-consent management cookies                                                                            |
| Ownership            | Created and operated by Jan Bogutzki, an individual developer based in Hannover, Germany.                                                             |
| Use in Reporting     | Data decoding, timestamp conversion, regex extraction, domain/DNS research, hash calculation and geographic-distance calculations.                    |

### What does Functions Online do?

Functions Online allows you to test individual PHP functions directly in a browser. Its tools cover arrays, cryptography, date and time, general utilities, mathematics, regular expressions, strings and URLs. It also provides custom functions such as a random password generator and a geographic-distance calculator.&#x20;

It can also help you process information obtained from webpages, logs, browser artefacts, URLs and other technical sources. For example, a user can decode a Base64 string, convert a Unix timestamp, extract patterns using regular expressions, calculate a hash or look up DNS records.&#x20;

**Important Note:** The platform is not a full PHP development environment. It provides individual predefined functions with input fields, and submitted values are processed by the website's server.

**The lowdown:** It’s best treated as a data-processing and analysis utility.

### How to Use:

**1. Select a category relevant to your task, such as Cryptography, Date and Time, Regular Expression, String or URL.**

<img src="../.gitbook/assets/unknown (743).png" alt="" height="297" width="602">

**2. Select the specific function you need (e.g. convert\_uudecode), enter its required input values, and press ‘run’.**

<img src="../.gitbook/assets/unknown (744).png" alt="" height="187" width="602">

**3. Review the output and compare it with the original data. Record the function used and relevant inputs where reproducibility matters, and validate important findings with an independent tool or source.**

<img src="../.gitbook/assets/unknown (745).png" alt="" height="196" width="602">

### Cost

* [x] Free
* [ ] Partially Free
* [ ] Paid

## Data Processing

### Account Required:

* [ ] Yes
* [x] No

No for basic use.

### Cookies:&#x20;

Testing identified the Google \_\_eoi cookie, associated with security in Google advertising services, and three consent-management cookies: cookie\_consent\_level, cookie\_consent\_user\_accepted and cookie\_consent\_user\_consent\_token.

### Use in Reporting

Functions Online can be useful for:

* Decoding Base64, URL-encoded strings and other supported encodings found in publicly available technical artefacts.
* Calculating MD5, SHA-1 or other supported hashes for comparison and basic integrity checks.
* Converting Unix timestamps and interpreting date strings when reconstructing event timelines.
* Using regular expressions to identify or extract specific strings and patterns from collected data.
* Checking DNS records and processing domain names, URLs and internationalised domain names.
* Calculating straight-line distances between coordinates when analysing geographic information.
* Reproducing simple data transformations and documenting how a technical value was interpreted.

**Important Note:** It can transform or interpret information already obtained during an investigation, but it does not independently establish the origin, authenticity or meaning of that information.

| **Capabilities**                                                                                                                                                              | **Limitations**                                                                                                                                                                                                                                              |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <p>Supports multiple PHP functions for encoding, decoding and string manipulation.</p><p>Calculates supported hashes and performs basic cryptographic-related operations.</p> | <p>Only the functions provided by the service can be selected. It’s not a general-purpose programming environment. </p><p>MD5 and SHA-1 are unsuitable for modern collision-resistant integrity assurance; output alone does not establish authenticity.</p> |
| Converts timestamps and processes date strings for timeline work.                                                                                                             | Ambiguous date formats, timezones and incorrect source timestamps can produce misleading conclusions.                                                                                                                                                        |
| Provides regex, URL, IDNA and DNS functions useful for technical artefact analysis.                                                                                           | Results depend on the input, PHP function behaviour and current DNS responses where applicable.                                                                                                                                                              |
| Includes JSON utilities and a coordinate-distance calculator.                                                                                                                 | The geographic-distance function calculates straight-line distance, not road distance or travel time.                                                                                                                                                        |
| Free browser access without installing PHP or creating an account.                                                                                                            | Inputs are sent to an external server, and detailed retention information for submitted values is not clearly documented.                                                                                                                                    |

### Summary

Functions Online fits primarily into the processing and analysis stages of the OSINT workflow, with a supporting role in verification.Its main value is making common technical operations accessible without requiring a local PHP installation.&#x20;

However, it should be used to process investigative data, not as an authoritative source of evidence.&#x20;

### Ownership

Created and is operated by Jan Bogutzki, who identifies himself in the [site's imprint](https://www.functions-online.com/impressum.html). The imprint provides a contact address in Hannover, Germany, and links to his personal website and blog.

### Ethical Considerations

* Avoid submitting confidential records, passwords, API keys, session cookies or private cryptographic keys to the service.
* Remember that data entered into function forms is sent to a third-party server for processing.
* Do not treat a decoded string as proof of provenance or authenticity as encoding is not encryption, and decoding does not establish who created the content.
* Treat hash calculations as technical comparisons, not evidence of authorship or ownership.
* Avoid using legacy functions such as MD5 or SHA-1 as evidence of modern cryptographic security.

### Related Tools:

* CyberChef
* dCode
* Regex101
* DNSChecker

#### Sources

[https://www.functions-online.com/](https://www.functions-online.com/)&#x20;

[https://www.functions-online.com/impressum.html](https://www.functions-online.com/impressum.html)&#x20;

[https://jan.bogutzki.de/Kategorie/projekte/functions-online](https://jan.bogutzki.de/Kategorie/projekte/functions-online)&#x20;

[https://www.facebook.com/functionsonline/](https://www.facebook.com/functionsonline/)&#x20;

[http://twitter.com/functionsonline/](http://twitter.com/functionsonline/)
