---
title: Projects

type: landing

sections:
  - block: markdown
    content:
      title: <strong><font size="7">Projects</font></strong>
  - block: markdown
    content:
      title: <u>Analyzing Anomalous Traffic Using Large-Scale Honeypot Deployment and Designing Effective Countermeasures</u>
      text: |
        <img src="/images/sweetspot.png" style="width: 100%; max-width: 800px; height: auto; display: block; margin: 0 auto 20px auto;">
        It has been nearly 20 years since the launch of the Leurré.com project, which deployed honeypots in over 30 countries to collect anomalous traffic data. Honeypots are a cybersecurity technology designed to attract attackers by intentionally exposing systems that appear vulnerable, enabling the observation and analysis of various malicious activities, such as unauthorized access or malware execution. Although the project is no longer active, the landscape of Internet usage has drastically changed since that time, with the emergence of a wide variety of applications. As a result, there remains a pressing need to continuously monitor and investigate security threats through large-scale honeypot deployments. In this research, in close collaboration with international research institutions such as Inria and DFKI, we aim to realize more secure network operations by addressing two key research questions: what the characteristics of newly observed anomalous traffic captured by large-scale honeypot deployments are, and what kinds of countermeasures can be developed to address these new forms of anomalous traffic. To achieve this goal, we observe the evolving security threats posed by the growing diversity of applications and build effective countermeasures using advanced machine learning and deep learning models that were not available at the time of the earlier project.
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: markdown
    content:
      title: <u>Establishing a Secure Email Environment through Attack Analysis</u>
      text: |
        Email was invented approximately 50 years ago as a fundamental means of communication. In recent years, messaging applications such as WhatsApp, which allow direct communication via centralized servers, have become widespread. However, email remains essential for commercial communication, and it is unlikely to be completely replaced by these applications. Its widespread use and importance provide attackers with a strong incentive to send malicious emails. Email attacks have become increasingly sophisticated. While some use tailored messages targeting individuals, recent developments in Large Language Models enable the easy generation of highly realistic malicious emails in a wide variety of formats. As a result, conventional security measures alone are often insufficient for users to distinguish between legitimate and malicious emails. This study aims to provide a secure email environment by conducting header analysis, including evaluation of sending domains, as well as content analysis focusing on linguistic patterns, event themes, and structural characteristics typical of malicious emails. Through this approach, we aim to deepen the understanding of email authentication practices and attack methods, thereby contributing to the dissemination of effective security measures.
  - block: markdown
    content:
      title: <u>Comprehensive Study on the Implementation Status and Effectiveness of Countermeasures Against Domain Name System Cache Poisoning</u>
      text: |
        The Domain Name System (DNS) is a critical infrastructure that underpins the Internet; however, various attacks targeting DNS have been reported for many years. Among these, DNS cache poisoning, where an attacker injects forged DNS records into a DNS cache server to cause users to receive incorrect name resolution results, is a well-known threat. As a primary countermeasure, DNS Security Extensions (DNSSEC) have been standardized, but due to the complexity of deployment and operation, their adoption remains limited. Meanwhile, alternative measures such as DNS cookies and case randomization are also widely used in practice. This study aims to clarify the current implementation status of countermeasures against DNS cache poisoning that can be applied to authoritative DNS servers and DNS cache servers, and to evaluate how effectively these measures function in real-world environments.
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"
---
