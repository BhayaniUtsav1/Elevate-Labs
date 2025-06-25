Phishing Email Analysis – Task 2

  Objective:

The goal of this task is to identify and analyze potential phishing characteristics in a suspicious email. This report enhances awareness of social engineering attacks and helps build essential email threat analysis skills.

---

  Tools Used:

* Email Client / Sample Email (Text format)
* Online Header Analyzer: [MXToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)

---

  Steps Followed:

1. Obtained a sample phishing email from an online repository.
2. Analyzed the sender's address for spoofing signs.
3. Examined the email header for SPF/DKIM/return-path issues.
4. Checked links and attachments for suspicious URLs.
5. Identified urgent or threatening language in the body content.
6. Hovered over URLs to check for mismatched domains.
7. Verified for spelling or grammar mistakes.
8. Summarized all indicators in a structured format.

---

  Summary of Phishing Indicators:

| Indicator Type            | Finding Example                                 |
| ------------------------- | ----------------------------------------------- |
| Spoofed Email Address     | `service@paypa1.com` instead of `@paypal.com`   |
| Fake Domain in Link       | `paypal.com-security-alerts.co`                 |
| SPF/DKIM Failures         | Found in header analysis                        |
| Threatening Language      | “Account will be suspended in 24 hours”         |
| Mismatched URLs           | Hover text ≠ actual link                        |
| Grammar/Formatting Issues | Template-style message, generic greeting        |
| IP/Region Mismatch        | Header shows sender IP from suspicious location |

---

  Conclusion:

This analysis confirms that the email is a phishing attempt. Users should always verify sender details, check URLs before clicking, and analyze email headers when in doubt. Awareness is the best defense.


