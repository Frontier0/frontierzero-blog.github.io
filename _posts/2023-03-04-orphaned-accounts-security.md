---
layout: post
title:  "Unseen Threats: The Hidden Dangers of Orphaned Accounts"
author: morsy
categories: [access, risk ]
tags: [security, account]
image: assets/images/employee-credentials.jpg
description: "Active, yet not-in-use accounts can be inconspicuously dangerous"
featured: true
hidden: false
canonical_url: https://www.frontierzero.io/blog/security-remote-access
---

## What are Orphaned Accounts?

Orphaned Accounts, also known as "Zombie Accounts" or "Orphan Accounts", are user accounts that have been created but are no longer in use or actively managed by their owners.

Orphaned accounts pose a significant risk to companies, as they can provide unauthorized access to sensitive data and systems. In this article, we will explore the dangers of orphaned accounts and how they pose a threat to companies.


## How can They Occur?

Orphaned accounts can occur for a variety of reasons. They may be the result of an employee leaving the company or changing positions, without proper account management procedures being followed. Alternatively, they may be created as a temporary account to perform a specific task or project, and then forgotten or left untouched. Whatever the reason, orphaned accounts represent a security threat that companies must address.


## Dangers of Orphaned Accounts

One of the primary dangers of orphaned accounts is the potential for unauthorized access to sensitive data and systems. When a user account is left unchecked, it can be exploited by cybercriminals who can use the account to gain access to company networks and data. Once they have access, they can steal or modify data, install malware or ransomware, and cause significant harm to the company.

Another risk posed by orphaned accounts is the potential for insider threats. Disgruntled former employees may use their old accounts to sabotage the company or steal valuable information. Even if the former employee did not have malicious intent, the account may still be compromised and used by someone else for nefarious purposes.

Furthermore, orphaned accounts can lead to compliance issues, which can result in legal and financial consequences for companies. Many industries, such as healthcare and finance, have strict regulations governing data access and storage. If an orphaned account is used to access sensitive data, the company may be found in violation of these regulations and face costly fines and legal action.


## Case Study: Colonial Pipeline Breach in 2021

In May 2021, the Colonial Pipeline, which supplies nearly half of the fuel consumed on the East Coast of the United States, was hit by a devastating cybersecurity attack. The attack, which was carried out by a criminal gang known as DarkSide, caused the pipeline to shut down for several days, resulting in widespread fuel shortages and panic buying.

The attackers gained access to Colonial Pipeline's computer systems through a compromised virtual private network (VPN) account. The account was reportedly no longer in use but was still active and had not been disabled. It is unclear how the attackers obtained the credentials for the account, but it is likely that they were obtained through social engineering or phishing.

Once the attackers gained access to the Colonial Pipeline's systems, they deployed ransomware, which encrypted the company's data and made it inaccessible. In exchange for the decryption key, the attackers demanded a ransom payment of $4.4 million, which Colonial Pipeline ultimately paid.


## How to Mitigate the risk of Orphaned Accounts?

To prevent orphaned accounts from posing a threat to companies, it is essential to implement proper account management procedures. This includes regularly reviewing and removing unused accounts, assigning clear ownership and responsibility for each account, and limiting access to only those who require it.
It is also crucial to have a process in place for disabling accounts when an employee leaves the company or changes positions.


## How can FrontierZero Help Address This Problem?

At FrontierZero, we recognize the importance of tracking orphaned accounts and taking preemptive measures against potential credential leaks and possible abuse. As a tenant administrator, you’ll get periodic access audit reports informing you of inactive accounts.

<p align="center"><img src="/assets/images/access-audit-email.png" alt="Access audit email sample" width="500"></p>

In order to correctly receive those emails, you'll need to set these values under your [Tenant Settings](https://app.frontierzero.io/tenant-settings/configuration):
<p align="center"><img src="/assets/images/tenant-access-audit-config.png" alt="Access audit tenant configuration" width="500"></p>
<br>
- **Missed Activation Email Threshold**: The number of days after which an email notification will be sent informing that a user hasn't activate their account yet.
- **User Inactivity Email Threshold**: The number of days of inactivity after which an email notification will sent to administrators.
- **User Inactivity Suspension Threshold**: The number of days of inactivity after which the user account will be automatically suspended. Suspended accounts restrict their users from performing all actions on the platform, including viewing, administrating and connecting to applications.

<br>
To know more and see this feature in action, [book a free demo today!](https://www.frontierzero.io/contact-us.html)