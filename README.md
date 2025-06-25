# 🧠 AI for Security & Security for AI

Welcome to the **AI-for-Security-and-Security-for-AI** resources!

This repository curates and organizes cutting-edge research at the intersection of **artificial intelligence (AI) and cybersecurity**, with a clear separation of two core themes:
### - 🛡️ AI4Sec (AI for Security): 

AI4Sec focuses on how AI can strengthen cybersecurity operations across the full defensive and offensive spectrum. This includes the use of machine learning and large language models (LLMs) for:

  - 🔍 Threat detection and alert triage  
  - 📈 Anomaly detection and behavioral analysis  
  - 🤖 Agent-based response and automation  
  - 🕵️ AI-assisted offensive techniques (e.g., reconnaissance, phishing, evasion)

To provide structure and industry alignment, this section follows:

  - The **[NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)** for defensive categories such as Govern, Identify, Protect, Detect, Respond, and Recover.  
  - The **[MITRE ATT&CK Matrix](https://attack.mitre.org/)** to map offensive AI use cases to real-world adversary tactics such as Reconnaissance and Resource Development.

### - 🔓 Sec4AI (Security for AI): 

Sec4AI focuses on protecting AI systems themselves from evolving cybersecurity threats. This includes understanding and mitigating risks targeting machine learning models, large language models (LLMs), and agentic systems.

Key areas of concern include:

- 🎯 Adversarial attacks (evasion, poisoning)
- 🧠 Model stealing, inversion, and privacy leakage
- 🔓 Jailbreaking and prompt injection in LLMs
- 📦 Secure training pipelines and deployment practices

This section is organized using the **[MITRE ATLAS Framework](https://atlas.mitre.org/matrices/ATLAS)**, which systematically categorizes tactics and techniques used by real-world adversaries against AI systems.

---

## 📚 Table of Contents

### 1. AI4Sec — AI for Security

#### 1.1 Defensive Security ([NIST Cybersecurity Framework](https://www.nist.gov/cyberframework))
- [1.1.1 Govern](#)
- [1.1.2 Identify](#)
- [1.1.3 Protect](#)
- [1.1.4 Detect](#)
- [1.1.5 Respond](#)
- [1.1.6 Recover](#)

#### 1.2 Offensive Security ([MITRE ATT&CK Matrix](https://attack.mitre.org/))
- [1.2.1 Reconnaissance](#)
- [1.2.2 Resource Development](#)
- [1.2.3 Initial Access](#)
- [1.2.4 Execution](#)
- [1.2.5 Persistence](#)
- [1.2.6 Privilege Escalation](#)
- [1.2.7 Defense Evasion](#)
- [1.2.8 Credential Access](#)
- [1.2.9 Discovery](#)
- [1.2.10 Lateral Movement](#)
- [1.2.11 Collection](#)
- [1.2.12 Command and Control](#)
- [1.2.13 Exfiltration](#)
- [1.2.14 Impact](#)

#### 1.3 Misc
- [1.3.1 Dataset](#)
- [1.3.2 Open-source tools](#)

---
### 2. Sec4AI — Security for AI
#### 2.1 Defensive Security for AI Models (no standard framework)
- [2.1.1 Detection](#)
- [2.2.1 Mitigation](#)
#### 2.2 Offensive Security ([MITRE ATLAS framework](https://atlas.mitre.org/matrices/ATLAS))
- [2.2.1 Reconnaissance](#)
- [2.2.2 Resource Development](#)
- [2.2.3 Initial Access](#)
- [2.2.4 AI Model Access](#)
- [2.2.5 Execution](#)
- [2.2.6 Persistence](#)
- [2.2.7 Privilege Escalation](#)
- [2.2.8 Defense Evasion](#)
- [2.2.9 Credential Access](#)
- [2.2.10 Discovery](#)
- [2.2.11 Collection](#)
- [2.2.12 AI Attack Staging](#)
- [2.2.13 Command and Control](#)
- [2.2.14 Exfiltration](#)
- [2.2.15 Impact](#)

#### 2.3 Misc
- [2.3.1 Dataset](#)
- [2.3.2 Open-source tools](#)

---
## 1. AI4Sec — AI for Security

### 1.1 Defensive Security ([NIST Cybersecurity Framework](https://www.nist.gov/cyberframework))

#### 1.1.1 Govern
<!-- Content for Govern -->

#### 1.1.2 Identify
<!-- Content for Identify -->

#### 1.1.3 Protect
<!-- Content for Protect -->

#### 1.1.4 Detect
📅 2025
- [Agentic-AI][Transforming cybersecurity with agentic AI to combat emerging cyber threats](https://www.sciencedirect.com/science/article/pii/S0308596125000734): This paper investigates the transformative potential of agentic AI in cybersecurity, specifically addressing how it can enhance practices in response to emerging threats. It aims to explore how agentic AI can transform cybersecurity practices, particularly in addressing new and evolving threats, while also examining the cybersecurity risks associated with its integration. The research explores the possibilities for agentic AI to automate critical tasks within Security Operations Centers (SOCs), such as decision-making, incident response, and threat detection. It also emphasizes the risks associated with AI integration, including the introduction of new vulnerabilities and challenges in managing automated systems, which call for a reassessment of existing cybersecurity frameworks to effectively address these risks.
- [Agentic-AI][TAGAPT: Toward Automatic Generation of APT Samples With Provenance-Level Granularity](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10948500): Detecting advanced persistent threats (APTs) at a host via data provenance has emerged as a valuable yet challenging task. Compared with attack rule matching, machine learning approaches offer new perspectives for efficiently detecting attacks by leveraging their inherent ability to autonomously learn from data and adapt to dynamic environments. However, the scarcity of APT samples poses a significant limitation, rendering supervised learning methods that have demonstrated remarkable capabilities in other domains (e.g., malware detection) impractical. Therefore, we propose a system called TAGAPT, which is able to automatically generate numerous APT samples with provenance-level granularity. First, we introduce a deep graph generation model to generalize various graph structures that represent new attack patterns. Second, we propose an attack stage division algorithm to divide each generated graph structure into stage subgraphs. Finally, we design a genetic algorithm to find the optimal attack technique explanation for each subgraph and obtain fully instantiated APT samples. Experimental results demonstrate that TAGAPT can learn from existing attack patterns and generalize to novel attack patterns. Furthermore, the generated APT samples 1) exhibit the ability to help with efficient threat hunting and 2) provide additional assistance to the state-of-theart (SOTA) attack detection system (Kairos) by filtering out 73% of the observed false positives. We have open-sourced the code and the generated samples to support the development of the security community
📅 2024
- [Agentic-AI][Using LLMs as AI Agents to Identify False Positive Alerts in Security Operation Center](https://www.researchsquare.com/article/rs-5420741/v1): This paper addresses the challenges and solutions related to identifying false positive (FP) alerts in Security Information and Event Management (SIEM) systems, which often overwhelm security operators. To tackle this issue, we propose a novel approach that employs a Large Language Model (LLM), specifically Llama, as an AI agent through a contextual-based approach to identify FPs in security alerts generated by multiple network sensors and collected in Security Operations Centers (SOCs). Our method follows three key steps: data extraction, enrichment, and playbook execution. First, Llama normalizes security alerts using a common schema, extracting key contextual elements such as IP addresses, host names, filenames, services, and vulnerabilities. Second, these extracted elements are enriched by integrating external resources such as threat intelligence databases and Configuration Management Databases (CMDB) to generate dynamic metadata. Finally, this enriched data is analyzed through predefined false positive investigation playbooks, designed by security professionals, to systematically evaluate and identify FPs.By automating the false positive identification process, this approach reduces the operational burden on human security operators, enhancing the overall efficiency and accuracy of SOCs, and improving the organization's security posture.
#### 1.1.5 Respond
<!-- Content for Respond -->

#### 1.1.6 Recover
<!-- Content for Recover -->

### 1.2 Offensive Security ([MITRE ATT&CK Matrix](https://attack.mitre.org/))

#### 1.2.1 Reconnaissance
<!-- Content for Reconnaissance -->

#### 1.2.2 Resource Development
<!-- Content for Resource Development -->

#### 1.2.3 Initial Access
<!-- Content for Initial Access -->

#### 1.2.4 Execution
<!-- Content for Execution -->

#### 1.2.5 Persistence
<!-- Content for Persistence -->

#### 1.2.6 Privilege Escalation
<!-- Content for Privilege Escalation -->

#### 1.2.7 Defense Evasion
<!-- Content for Defense Evasion -->

#### 1.2.8 Credential Access
<!-- Content for Credential Access -->

#### 1.2.9 Discovery
<!-- Content for Discovery -->

#### 1.2.10 Lateral Movement
<!-- Content for Lateral Movement -->

#### 1.2.11 Collection
<!-- Content for Collection -->

#### 1.2.12 Command and Control
<!-- Content for Command and Control -->

#### 1.2.13 Exfiltration
<!-- Content for Exfiltration -->

#### 1.2.14 Impact
<!-- Content for Impact -->

### 1.3 Misc

#### 1.3.1 Dataset
<!-- Content for Dataset -->

#### 1.3.2 Open-source tools
<!-- Content for Open-source tools -->

---

## 2. Sec4AI — Security for AI

### 2.1 Defensive Security for AI Models (no standard framework)

#### 2.1.1 Detection
📅 2023
- [Survey][Defense strategies for Adversarial Machine Learning: A survey](https://www.sciencedirect.com/science/article/pii/S1574013723000400)

#### 2.1.2 Mitigation
<!-- Content for Mitigation -->

### 2.2 Offensive Security ([MITRE ATLAS framework](https://atlas.mitre.org/matrices/ATLAS))

#### 2.2.1 Reconnaissance
<!-- Content for Reconnaissance -->

#### 2.2.2 Resource Development
<!-- Content for Resource Development -->

#### 2.2.3 Initial Access
<!-- Content for Initial Access -->

#### 2.2.4 AI Model Access
<!-- Content for AI Model Access -->

#### 2.2.5 Execution
<!-- Content for Execution -->

#### 2.2.6 Persistence
<!-- Content for Persistence -->

#### 2.2.7 Privilege Escalation
<!-- Content for Privilege Escalation -->

#### 2.2.8 Defense Evasion
📅 2025
- [ML-NIDS][Adversarial Evasion Attacks Practicality in Networks: Testing the Impact of Dynamic Learning](https://arxiv.org/pdf/2306.05494)
📅 2024
- [ML-NIDS][Explainable and Transferable Adversarial Attack for ML-Based Network Intrusion Detectors](https://arxiv.org/pdf/2401.10691#page=17&zoom=100,416,53)
- [ML-NIDS][Towards Realistic Problem-Space Adversarial Attacks Against ML in NIDS](https://dl.acm.org/doi/pdf/10.1145/3664476.3669974)
- [Survey/Review][Benchmarking Transferable Adversarial Attacks](https://arxiv.org/pdf/2402.00418)

📅 2023
- [Malware][Black-box Adversarial Example Attack Towards FCG-Based Android Malware Detection](https://www.usenix.org/system/files/sec23fall-prepub-2-li-heng.pdf)
- [Provenance Graph][Evading Provenance-Based ML Detectors with Adversarial System Actions](https://www.usenix.org/system/files/usenixsecurity23-mukherjee.pdf)
- [Survey][A Comprehensive Survey of GANs in Cybersecurity Intrusion Detection](https://ieeexplore.ieee.org/abstract/document/10187144)
- [Survey][Survey: AML for Network Intrusion Detection Systems](https://ieeexplore.ieee.org/abstract/document/10005100)
- [Survey]["Real Attackers Don't Compute Gradients": Bridging the Gap Between Research and Practice](https://ieeexplore.ieee.org/abstract/document/10136152)
- [LLM][Survey of Vulnerabilities in LLMs Revealed by Adversarial Attacks](https://arxiv.org/pdf/2310.10844)
- [Survey][A Survey on Transferability of Adversarial Examples Across DNNs](https://arxiv.org/pdf/2310.17626)
📅 Prior
- [2022] [Practicality of Adversarial Evasion Attacks on NIDS](https://link.springer.com/article/10.1007/s12243-022-00910-1)
- [NeurIPS 2019] [Adversarial Examples are not Bugs, They are Features](https://proceedings.neurips.cc/paper_files/paper/2019/file/e2c420d928d4bf8ce0ff2ec19b371514-Paper.pdf)
- [CVPR 2019]: [Feature Space Perturbations Yield More Transferable Adversarial Examples](https://openaccess.thecvf.com/content_CVPR_2019/papers/Inkawhich_Feature_Space_Perturbations_Yield_More_Transferable_Adversarial_Examples_CVPR_2019_paper.pdf)
#### 2.2.9 Credential Access
<!-- Content for Credential Access -->

#### 2.2.10 Discovery
<!-- Content for Discovery -->

#### 2.2.11 Collection
<!-- Content for Collection -->

#### 2.2.12 AI Attack Staging
📅 2024
- [Model Theft/extraction/Stealing] [SoK: All You Need to Know About On-Device ML Model Extraction](https://www.usenix.org/system/files/usenixsecurity24-nayan.pdf)
📅 Prior
- [Model Theft/extraction/Stealing][Evasion]: [Surrogate-Based Black-Box Attacks on Deep Networks](https://arxiv.org/pdf/2203.08725)
- [Model Theft/extraction/Stealing][Evasion]: [Meta-Surrogate Model for Transferable Adversarial Attack](https://arxiv.org/pdf/2109.01983)
#### 2.2.13 Command and Control
<!-- Content for Command and Control -->

#### 2.2.14 Exfiltration
<!-- Content for Exfiltration -->

#### 2.2.15 Impact
<!-- Content for Impact -->

### 2.3 Misc

#### 2.3.1 Dataset
<!-- Content for Dataset -->

#### 2.3.2 Open-source tools
<!-- Content for Open-source tools -->


