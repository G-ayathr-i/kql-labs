# Clout Defender: Phishing Investigation


- Date:27 June 2026
- Platform:KC7
- Category: Phishing Investigation | Security Investigation | Kusto Query Language (KQL)

## Objective

To investigate a targeted phishing attack against a social media influencer using Kusto Query Language (KQL), analyze attacker activity through multiple security logs, and understand how phishing, OSINT, and email compromise techniques are used in real-world attacks.

## What I Did

* Completed the **Clout Defender** investigation on KC7.
* Investigated a targeted spear-phishing attack against a social media influencer.
* Analyzed phishing emails and malicious URLs.
* Investigated malicious inbox forwarding rules and email filters.
* Used KQL to examine security logs and trace attacker activity.
* Used Passive DNS to identify domains associated with suspicious IP addresses.
* Learned how attackers use publicly available information (OSINT) to target victims.

## New Things I Learned

* Malicious URLs can reveal attacker infrastructure, tactics, and associated domains.
* MaxMind can be used to determine the geographical location of an IP address.
* BEC (Business Email Compromise): An email-based attack that tricks users into revealing information or transferring money.
* APT (Advanced Persistent Threat): A long-term, stealthy cyberattack aimed at stealing data or maintaining unauthorized access.

## KQL Concepts Practiced

* Searching logs using multiple keywords with `has_any`
* Passive DNS investigation
* Using `distinct` to retrieve unique domains
* Log filtering and event analysis
* Investigating email and network activity
* The `has_any` operator in KQL allows searching for multiple keywords simultaneously.
* Passive DNS helps identify domains linked to suspicious IP addresses.

## Reflection

This lab strengthened my understanding of how phishing investigations are conducted in a Security Operations Center (SOC). I learned how attackers exploit publicly available information to launch targeted phishing campaigns and how KQL can be used to investigate email activity, network logs etc. The exercise also highlighted the importance of OSINT awareness, MFA, and effective log analysis in detecting and responding to phishing incidents.
