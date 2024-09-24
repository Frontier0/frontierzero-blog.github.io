---
layout: post
title: "The Future of SaaS Security: Why Shared Responsibility Matters Now"
author: oskars
categories: [shadow, saas, security]
tags: [saas, security]
image: assets/images/shared-responsibility-matters-now-main.png
description: ""
hidden: false
featured: true
canonical_url: https://www.frontierzero.io/blog/shared-responsibility-matters-now
toc: true
---

The recent exposure of sensitive corporate data from thousands of ServiceNow Knowledge Base (KB) instances highlights a common issue in today’s SaaS ecosystem: everyone points the finger at the SaaS provider when things go wrong. In this case, nearly 45% of ServiceNow KB instances were found to be leaking data, even after security updates were implemented last year. The exposure was attributed to misconfigured access controls, which allowed unauthorized access to personally identifiable information (PII), internal system details, and even active credentials.

## How the Current System Works

In today’s system, when a data breach occurs in a SaaS platform, the blame often falls on the provider. But is that fair? SaaS providers like ServiceNow are responsible for securing the infrastructure: the networks, servers, and underlying software that power the platform. However, it’s the customer—businesses using the platform—who are responsible for configuring access controls, managing user permissions, and safeguarding sensitive data.

Unfortunately, many businesses assume that their SaaS provider will handle everything. This misunderstanding can leave critical gaps in security. For example, in the ServiceNow incident, many of the data leaks were due to outdated or misconfigured access controls—something that falls squarely on the customer to manage.

## Moving to the Shared Responsibility Model

![Shared Responsibility Model](/assets/images/frontierzero-shared-responsibility-model.png)

To prevent these kinds of issues, we need to move to a SaaS Shared Responsibility Model, where both the provider and the customer understand and take responsibility for their respective roles in securing data.

- SaaS Providers’ Responsibility: Providers like ServiceNow are responsible for securing the infrastructure, ensuring proper encryption, and protecting the platform from external threats. They provide the tools (like ACLs, encryption, and security patches) that customers can use to secure their environments.
- Customers’ Responsibility: The customer’s role is just as critical. Businesses need to ensure that they configure these security tools properly, manage access controls, and monitor user activity. This includes regular audits of access permissions, updating security configurations, and applying proper user authentication protocols (like 2FA) to limit unauthorized access.

## Why the Shared Responsibility Model Works

The reality is that no single entity can fully protect an organization’s data in a hyper-connected SaaS world. Both the provider and the customer need to work together to close security gaps. The ServiceNow incident is a perfect example: ServiceNow provided security updates, but many businesses failed to configure their systems properly, allowing unauthorized access. This could have been prevented if there was a clearer understanding of who is responsible for what.

## How the Shared Responsibility Model Would Have Helped

In the ServiceNow case, had businesses understood that it was their responsibility to configure and manage access to their KB instances, they could have performed regular security audits, ensured proper access controls, and reduced the risk of data exposure. Meanwhile, ServiceNow played its part by providing the necessary tools to prevent unauthorized access, but it was up to the customer to use them effectively.

## Conclusion

Blaming the SaaS provider when things go wrong is easy, but it doesn’t solve the underlying issue. The Shared Responsibility Model ensures that both providers and customers understand their roles in securing data. By embracing this model, organizations can avoid the pitfalls of misconfigurations, like the one seen in the ServiceNow incident, and protect their sensitive data more effectively.

Moving forward, every organization should ask themselves: <b>Are we doing our part in the Shared Responsibility Model to protect our data?</b> The tools are there—now it’s about using them wisely.