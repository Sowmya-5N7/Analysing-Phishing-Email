# Analysing-Phishing-Email : Amazon Phishing Revealed
## Overview of the project

To analyze and identify phishing characteristics in a suspicious email impersonating Amazon, and raise awareness about how attackers trick users into revealing sensitive information.These include :
-  Email header analysis
-  Red flags indentification
-  Suspicious Attachment Analysis
-  Other Hidden Threats

## Findings
| Finding                 | Details                                                                      | 
|-------------------------|------------------------------------------------------------------------------|
| Fake Sender Domain      | no-reply@amaz0n-security.com — uses "0" instead of "o" to mimic Amazon.      |
| Urgent Language         | Phrases like “Action Required”, “Time Sensitive”, “restricted access”        |           
|Suspicious Link          | "Secure Your Account” leads to a fake site, not Amazon’s official domain.    |
| Generic Greeting        | Starts with “Dear Customer” instead of the recipient’s real name.            | 
|Fake Login Location Info |Mentions login from Mumbai (IP: 185.143.223.67) to make the alert seem real.  | 

## Protection Guidelines
-   Don’t Click Suspicious Links
-   Verify the Sender
-   Use Two-Factor Authentication (2FA)
-   Never Share Sensitive Info via Email
-   Report Phishing Emails

## Tools used
-   MXToolBox Header Analyzer
-   Blacklist verification via AbuseIPDB
