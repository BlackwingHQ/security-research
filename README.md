# Security Research

This project hosts security advisories and their accompanying proof-of-concepts related to security research conducted at Blackwing.


## Advisories

The disclosure of vulnerabilities are in the form of security advisories, which can be browsed in the [Security
Advisories](https://github.com/BlackwingHQ/security-research/security/advisories?state=published)
page.

When Blackwing finds a new vulnerability as part of our public vulnerability research, we send a detailed technical description of the issue to the relevant vendor or open source project (responsible party). This initial vulnerability report includes the following statement:

_"This bug is subject to a 90 day disclosure deadline. If a fix for this issue is made available to users before the end of the 90-day deadline, this bug report will become public 30 days after the fix was made available. Otherwise, this bug report will become public at the deadline."_

Our expectation is that the responsible party will fix the security vulnerability and make a patch available to users within 90 days. If so, Blackwing will release details about the vulnerability 30 days after the fix is made available to users. In some cases the responsible party may agree to publish details at an earlier date (for example, if they want to align disclosure to an official security bulletin release, or if the technical details are already public due to normal development practices).

## Advisory Database
Our vulnerability discoveries are tracked in the Blackwing Security Research advisory database: [Security Advisories](https://github.com/BlackwingHQ/security-research/security/advisories). Initially, all of our advisories are restricted so that only Blackwing team members can see the technical content. When coordinating with a responsible party, we may invite individuals delegated by the responsible party to join the advisory as guests to facilitate collaboration. When it's time to disclose, we "publish" the advisory which means the technical description of the vulnerability will become publicly accessible in our advisory database.

## Proof of Concepts

Accompanying proof-of-concept code will be used to demonstrate the
security vulnerabilities.

| Year | Title | Advisories | Links |
| ---- | ----- | ---------- | ----- |
| 2024 | | | 
| 2024 | | | 


## Coordinated Disclosure Policy

The Blackwing Intelligence research team is dedicated to protecting users. We view vulnerability disclosure as a collaborative process to protect users. This is why Blackwing adheres to a 90-day disclosure deadline.

When we identify a vulnerability in a project or product as part of our public vulnerability research, we will report it by attempting to contact the publicly-listed security contact for the responsible party if one exists; otherwise we will attempt to contact the responsible party directly.

If the responsible party responds and agrees the issue poses a security risk, we will work with their security team or individuals delegated by the responsible party to communicate the vulnerability in detail, and coordinate the process for public disclosure. Responsibility for developing and releasing a patch lies firmly with the responsible party, though we aim to facilitate this by providing detailed information about the vulnerability.

After notifying responsible parties of vulnerabilities, details will be shared in public with the defensive community after 90 days, or sooner if the responsible party releases a fix. That deadline can vary in the following ways:

- If a deadline is due to expire on a weekend or US public holiday, the deadline will be moved to the next normal work day.
- Before the 90-day deadline has expired, if the responsible party lets us know that a patch is scheduled for release on a specific day that will fall within 14 days following the deadline, we will delay the public disclosure until the availability of the patch.
- If we observe a 0day (see below for definition) vulnerability being actively exploited, we believe more urgent action is appropriate and we may apply a shorter disclosure deadline. We believe it is important that responsible parties disclose that there is evidence to suggest that the vulnerability is under active exploitation.

As always, we reserve the right to bring deadlines forwards or backwards based on extreme circumstances. We remain committed to treating all responsible parties equally.

This policy is strongly in line with our desire to improve industry response times to security bugs, but also results in softer landings for bugs marginally over deadline.

**Note:** This policy is primarily based on [Google's vulnerability disclosure policy](https://about.google/appsecurity/). We join Google in calling on all researchers to adopt disclosure deadlines in some form. Creating pressure towards more reasonably-timed fixes will result in better security outcomes for users. 

### Terms
    - Responsible party - Vendors, open source maintainers, and other third parties that are responsible for addressing security vulnerabilities in their products or projects.
    - 0day - A 0day (zero-day) vulnerability refers to a security flaw in software or hardware that is not widely known.

### Frequently Asked Questions
- **Why don't you use the term responsible disclosure?**
    - The term "responsible disclosure", while possibly well intentioned, carries the implication that researchers who prioritize the protection of users over the interests of vendors by disclosing vulnerability details are acting irresponsibly. We use the term "coordinated disclosure" to emphasize the collaborative nature of the process. We believe that vulnerability disclosure is a two-way street, and that it is important for researchers and vendors to work together to protect users.
