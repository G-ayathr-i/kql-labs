# The Valdorian Times: Political Influence Investigation

[View Badge]KC7/Valdorian_Times.pdf

* Date: 28 June 2026
* Platform: KC7
* Category: Incident Response | Threat Hunting | Kusto Query Language (KQL)

## Objective

To investigate a phishing-based security incident involving an unauthorized newspaper article by analyzing email, endpoint, and network logs using Kusto Query Language (KQL), and reconstruct the complete attack timeline.

## What I Did

* Analyzed employee roles, email communications, endpoint activity, and computer process events.
* Used KQL to reconstruct the attack timeline across multiple log sources.
* Investigated attacker commands, command-and-control (C2) activity, and evidence of data exfiltration.
* Correlated multiple log sources to determine the sequence of attacker actions.

## New Things I Learned

* Timeline reconstruction is essential for understanding the full attack lifecycle.
* `count` is used to determine the number of matching records.
* `distinct` returns unique values from a column.
* `let` is used to save query results or variables for reuse within a KQL query.
* Learned the difference between `has` and `contains` operators for text searches.
* File creation events often contain hash values, which help identify and verify suspicious files.
* Plink (PuTTY Link) can be abused by attackers to establish SSH tunnels, enabling remote access and hands-on-keyboard activity on a compromised system.
* The `mv` (move) command is used to rename or move files.
* `curl` is used to transfer data to or from remote servers and can be abused to download malware or exfiltrate data.
  
## KQL Concepts Practiced

* Time-based filtering
* Correlating multiple log sources
* Timeline reconstruction

## Reflection

This lab strengthened my incident response and threat hunting skills by demonstrating how to reconstruct a complete attack timeline using Kusto Query Language (KQL). I gained practical experience investigating phishing emails, endpoint activity, attacker commands, and network communications while learning how to correlate evidence from multiple log sources. The exercise also improved my understanding of key KQL operators, attacker techniques such as Command-and-Control (C2) and data exfiltration, and the importance of following evidence to accurately determine the root cause of a security incident.
