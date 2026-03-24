<p align="center">
  <a href="https://awesome.re">
    <img src="https://awesome.re/badge.svg" alt="Awesome">
  </a>
  <a href="https://github.com/ashfaaq98/awesome-genai-cyberhub/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/ashfaaq98/awesome-genai-cyberhub" alt="GitHub license">
  </a>
  <a href="https://github.com/ashfaaq98/awesome-genai-cyberhub/stargazers">
    <img src="https://img.shields.io/github/stars/ashfaaq98/awesome-genai-cyberhub?style=social" alt="GitHub Stars">
  </a>
  <a href="https://github.com/ashfaaq98/awesome-genai-cyberhub/network/members">
    <img src="https://img.shields.io/github/forks/ashfaaq98/awesome-genai-cyberhub?style=social" alt="GitHub Forks">
  </a>
  <a href="https://github.com/ashfaaq98/awesome-genai-cyberhub/pulls">
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome">
  </a>
</p>
<p align="center">
⭐ If you find Awesome GenAI CyberHub useful, please consider giving it a ⭐ to help it grow and reach more people! ⭐
</p>
<p align="center">
  <img src="assets/images/bannerv3.png" alt="Awesome GenAI CyberHub Banner" width="700" />
</p>



# 🚀 Awesome GenAI CyberHub ✨


> A curated collection of the best **LLM-based** resources for cybersecurity practitioners, researchers, and enthusiasts.

Welcome to **Awesome GenAI CyberHub**, your focused repository for Agentic AI Large Language Model (LLM) applications in cybersecurity. Below you’ll find links to articles, papers, PoCs, frameworks, datasets, and community projects organized by **topic**, making it easy to navigate the ever-expanding landscape of LLM‑powered security.

---

## 📋 Table of Contents

- [About](#about)
- [Topic-Based Directory Structure](#topic-based-directory-structure)
- [Resource Listings](#resource-listings)
  - [General](#general)
  - [MCP Servers (Model Context Protocol)](#mcp-servers-model-context-protocol)
  - [Models](#models)
  - [Benchmarks & Datasets](#benchmarks--datasets)
  - [AI SOC](./Resources/ai-soc/README.md)
  - [Cyber Threat Intelligence (CTI)](./Resources/cti/README.md)
  - [Malware Analysis](./Resources/malware-analysis/README.md)
  - [Vulnerability Analysis](./Resources/vulnerability-analysis/README.md)
  - [Detection Engineering](./Resources/detection-engineering/README.md)
  - [Phishing Analysis](./Resources/phishing-analysis/README.md)
  - [LLM-Based Honeypots](./Resources/honeypots/README.md)
  - [Offensive Security](./Resources/offensive-security/README.md)
  - [Digital Forensics](./Resources/digital-forensics/README.md)
- [How to Navigate & Contribute](#how-to-navigate--contribute)
- [License](#license)
- [Contact](#contact)

---

## About 

This repo aggregates the most impactful LLM‑centric work in cybersecurity, grouped by real‑world problem domains. Whether you’re building an autonomous SOC analyst, crafting threat profiles, or automating detection rule writing or exploring offensive workflows like red teaming, jump straight to the topic area that matters most.


##  Topic-Based Directory Structure

```plaintext
awesome-genai-cyberhub/
├── Resources/
   ├── ai-soc/                # Agentic AI for SOC workflows
   ├── cti/                   # Cyber Threat Intelligence via LLMs
   ├── malware-analysis/      # LLM driven malware Analysis
   ├── vulnerability-analysis/ # LLMs in vuln discovery
   ├── detection-engineering/ # Generative AI rule writing & alerts
   ├── phishing-analysis/     # Phishing Analysis & detection
   ├── honeypots/             # LLM-driven honeypot frameworks
   ├── offensive-security/    # Offensive security workflows
   └── digital-forensics/     # LLM applications in Digital Forensics

```

---

##  Resource Listings

### 🏅 General

* 📄 [Generative AI in Cybersecurity: A Comprehensive Review of LLM Applications and Vulnerabilities](https://arxiv.org/html/2405.12750) **[Paper/Review]** - Explores LLM applications in hardware security, intrusion detection, CTI, malware/phishing detection, LLM vulnerabilities (prompt injection, data poisoning), mitigation strategies, and evaluates LLMs in cybersecurity knowledge.

* 📄 [A Comprehensive Review of Large Language Models in Cyber Security ](https://www.researchgate.net/publication/384500263_A_Comprehensive_Review_of_Large_Language_Models_in_Cyber_Security) **[Paper/Review]** - Reviews LLM applications in cybersecurity, focusing on their potential in threat detection domains like CTI, phishing detection, and log analysis, while also discussing challenges and future directions.

* 📄 [Large Language Models in Cybersecurity: State-of-the-Art ](https://arxiv.org/html/2402.00891) **[Paper/Review]** - Provides a characterization of both defensive (mapped to NIST framework) and adversarial (mapped to MITRE ATT&CK) applications of LLMs in cybersecurity, identifying research gaps.

* 📄 [Large Language Models for Cyber Security: A Systematic Literature Review ](https://arxiv.org/html/2405.04760) **[Paper/Review]** - A systematic literature review analyzing over 185 papers to map the current landscape of LLM applications across various cybersecurity tasks, including vulnerability detection, malware analysis, and phishing detection.

* 🌐 [An Introduction to AI in Cybersecurity ](https://cybersecai.github.io/introduction/cybsersecurity/) **[Guide/Resource]** - An introductory resource discussing GenAI for cybersecurity, covering various topics including CVE enrichment and CWE assignment.

* 🤖 [Cyber Security llm Agents ](https://github.com/NVISOsecurity/cyber-security-llm-agents) **[Tool/GitHub]** - A collection of agents using LLMs (built on AutoGen) to perform common cybersecurity tasks, showcased at RSAC 2024.

* 📚 [awesome-foundation-agents](https://github.com/FoundationAgents/awesome-foundation-agents) **[Awesome List/GitHub]** - Curated list of foundation-model agent resources (general agent ecosystem context).

* 🌐 [Incident Database](https://incidentdatabase.ai/) **[Resource]** - Collection of documented incidents involving AI systems (useful for threat modeling and safety context).

* 🛠️ [AttackGen](https://attackgen.streamlit.app/) **[Tool/Website]** - Interactive helper for generating/structuring attack content and scenarios.

* 🤖 [CAI (aliasrobotics/cai)](https://github.com/aliasrobotics/cai) **[Tool/GitHub]** - Cybersecurity-focused AI tooling from Alias Robotics (automation/agent experiments).

* 📄 [A Comprehensive Overview of Large Language Models (LLMs) for Cyber Defences: Opportunities and Directions ](https://arxiv.org/html/2405.14487v1) **[Paper/Review]** - Surveys LLM applications in cyber defense, categorizing them into threat intelligence, vulnerability assessment, network security, privacy, training, automation, and ethical guidelines. Also covers LLM concepts from Transformers to GPT.

* 📄 [From Texts to Shields: Convergence of Large Language Models and Cybersecurity ](https://arxiv.org/html/2505.00841v1) **[Paper/Report]** - Explores the convergence of LLMs and cybersecurity, synthesizing insights from network security, AI, formal methods, and human-centered design. It examines LLM applications in software/network security, 5G vulnerability analysis, generative security engineering, and the role of agentic LLMs.

* 📄 [When LLMs meet cybersecurity: a systematic literature review](https://arxiv.org/abs/2405.03644) **[Paper/Review]** - A systematic literature review of over 300 works, covering 25+ LLMs and 10+ downstream scenarios, addressing the construction of cybersecurity-oriented LLMs, their applications, challenges, and future research.

* 📄 [Application of Large Language Models in Cybersecurity: a Systematic Literature Review ](https://www.researchgate.net/publication/386133416_Application_of_Large_Language_Models_in_Cybersecurity_a_Systematic_Literature_Review) **[Paper/Review]** - A systematic literature review of 177 articles (2018-2024) on LLM applications in offensive/defensive cybersecurity, cyberethics, legal frameworks, and cybersecurity governance.

* 📄 [Cyber Shadows: Neutralizing Security Threats with AI and Targeted Policy Measures (28 Jan 2025)](https://arxiv.org/abs/2501.09025) **[Paper]**

* 📄 [Comparative Analysis of AI-Driven Security Approaches in DevSecOps (arXiv:2504.19154)](https://arxiv.org/abs/2504.19154) **[Paper]**

* 📰 [Threat modeling with LLMs: two years in (hype, hope, and a look at Gemini 2.5 Pro)](https://xvnpw.github.io/posts/threat-modeling-with-llms-two-years-in-hype-hope-and-a-look-at-gemini-2.5-pro/) **[Blog]**

* 🎥 [Will AI Help or Hurt Cybersecurity? Definitely!](https://www.youtube.com/watch?v=cjy5jpRS_S0) **[Video]**

---

### 🥇 MCP Servers (Model Context Protocol)

This section covers resources related to Model Context Protocol (MCP) servers for security. These systems facilitate more complex and coordinated AI-driven security operations.

* 🖥️ [ORKL MCP Server](https://github.com/fr0gger/MCP_Security) **[Github]** - A Model Context Protocol (MCP) server for querying the ORKL API. 
* 🖥️ [VirusTotal MCP Server](https://smithery.ai/server/@AshfaaqF/mcp-priam-virustotal) **[Smithery]** - A Model Context Protocol (MCP) server for querying the VirusTotal API. 
* 🖥️ [OTX Alien Vault MCP Server](https://smithery.ai/server/@AshfaaqF/mcp-priam-alienvault) **[Smithery]** - A Model Context Protocol (MCP) server for querying the Alien Vault API. 
* 🖥️ [RSTCloud MCP Server](https://smithery.ai/server/@AshfaaqF/mcp-priam-rstcloud) **[Smithery]** - A Model Context Protocol (MCP) server for querying the RSTCloud API. 
* 🖥️ [OpenCTI MCP Server](https://github.com/CooperCyberCoffee/opencti_mcp_server) **[Github]** - A Model Context Protocol (MCP) server for orchestrating and querying OpenCTI via LLM agents. 
* 🖥️ [External Reconnaissance MCP Server](https://github.com/naebo/mcp-external-recon-server) **[Github]** - A Model Context Protocol (MCP) server for performing active external reconnaissance activities against a domain. 

---

### 🥈 Models

* 🧠 [SecureBERT](https://huggingface.co/ehsanaghaei/SecureBERT) **[Model/HuggingFace]** - A BERT model pre-trained on a vast corpus of cybersecurity texts.

* 🧠 [Lily Cybersecurity 7B v0.2](https://huggingface.co/segolilylabs/Lily-Cybersecurity-7B-v0.2) **[Model/HuggingFace]** - A 7B parameter Mistral fine-tune, acting as a cybersecurity assistant trained on approximately 22,000 hand-crafted cybersecurity and hacking-related data pairs. 

* 🧠 [Foundation Sec 8B](https://huggingface.co/fdtn-ai/Foundation-Sec-8B) **[Model/HuggingFace]** - An 8-billion parameter base language model (extending Llama-3.1-8B) specialized for cybersecurity applications through continued pretraining on a curated corpus of cybersecurity-specific text. 
 

* 🧠 [Google launches Sec-Gemini 1.0, a new AI model to advance cybersecurity (Google Security Blog)](https://security.googleblog.com/2025/04/google-launches-sec-gemini-v1-new.html) **[Blog/Model Announcement]** - Announces Sec-Gemini v1.0, an experimental AI model focused on cybersecurity, combining Gemini's advanced capabilities with near real-time cybersecurity knowledge.

--- 

### 🥉 Benchmarks & Datasets

* 📊 [SECURE: Benchmarking LLMs for Cybersecurity](https://arxiv.org/abs/2405.20441) **[Paper/Benchmark]**

* 📊 [CTIBench: Benchmark for Evaluating LLMs in CTI ](https://proceedings.neurips.cc/paper_files/paper/2024/file/5acd3c628aa1819fbf07c39ef73e7285-Paper-Datasets_and_Benchmarks_Track.pdf) **[Paper/Benchmark]**

* 📊 [CyberSecEval 2: Wide-Ranging Cybersecurity Evaluation Suite](https://arxiv.org/abs/2404.13161) **[Paper/Benchmark]**

* 📊 [CS-Eval: Comprehensive LLM Benchmark for Cybersecurity](https://arxiv.org/abs/2411.16239) **[Paper/Benchmark]**

* 📊 [CyberBench: A Multi-Task Benchmark for Evaluating Large Language Models in Cybersecurity](https://www.researchgate.net/publication/378267627_CyberBench_A_Multi-Task_Benchmark_for_Evaluating_Large_Language_Models_in_Cybersecurity) **[Paper/Benchmark/GitHub]**  GitHub: [jpmorganchase/CyberBench](https://github.com/jpmorganchase/CyberBench)

* 📊 [Crashbench: A LLM benchmark to measure bug-finding and reporting capabilities of LLMs ](https://github.com/ortegaalfredo/crashbench) **[Benchmark/GitHub]** 

* 📊 [Cybench: A Framework for Evaluating Cybersecurity Capabilities and Risks of Language Models ](https://arxiv.org/abs/2408.08926) **[Benchmark/Framework/Paper]**  See also: [Project Page] (https://cybench.github.io/)

* 📊 [PhishLLM](https://github.com/code-philia/PhishLLM) **[Benchmark/Tool/GitHub]**  See also: [Project Page](https://sites.google.com/view/phishllm/home)

* 📊 [SEvenLLM: Benchmarking, Eliciting, and Enhancing Abilities of Large Language Models in Cyber Threat Intelligence ](https://arxiv.org/abs/2405.03446) **[Benchmark/Dataset/GitHub]** 

* 📊 [NYU CTF Bench: A Scalable Open-Source Benchmark Dataset for Evaluating LLMs in Offensive Security ](https://arxiv.org/abs/2406.05590) **[Benchmark/Dataset/GitHub]** 

* 📊 [Benchmarking Foundation Models in Cybersecurity: A Study on OpenAI's o1 ](https://arxiv.org/pdf/2410.21939v1) **[Paper/Benchmark]** 

* 📊 [CyberLLMInstruct: A New Dataset for Analysing Safety of Fine-Tuned LLMs Using Cyber Security Data ](https://arxiv.org/pdf/2503.09334) **[Dataset/Paper]**

* 📊 [TM-Bench: A Benchmark for LLM-Based Threat Modeling](https://www.tmbench.com/) **[Benchmark/Website]** 

* 📊 [SecBench: A Comprehensive Multi-Dimensional Benchmarking Dataset for LLMs in Cybersecurity](https://arxiv.org/html/2412.20787) **[Benchmark/Dataset/Paper]** 

* 📊 [CVE-Bench: A Benchmark for AI Agents’ Ability to Exploit Real-World Web Application Vulnerabilities (21 March 2025)](https://arxiv.org/pdf/2503.17332v1) **[Paper]** 

* 📊 [PRIMUS: A Pioneering Collection of Open-Source Datasets for Cybersecurity LLM Training](https://arxiv.org/abs/2502.11191) **[Paper/Dataset/Model]** 

* 📊 [Introducing AI Cyber Model Arena: a real-world benchmark for AI agents in cybersecurity](https://www.wiz.io/blog/introducing-ai-cyber-model-arena-a-real-world-benchmark-for-ai-agents-in-cybersec) **[Blog]**

* 📊 [SANDBOXESCAPEBENCH: Quantifying Frontier LLM Capabilities for Container Sandbox Escape](https://arxiv.org/abs/2603.02277) **[Paper/Benchmark]** - Introduces an open benchmark that safely measures an LLM agent's capacity to break out of sandboxes, implemented as a CTF evaluation utilizing a nested sandbox architecture.

* 📊 [Cybersecurity AI Benchmark (CAIBench): A Meta-Benchmark for Evaluating Cybersecurity AI Agents](https://arxiv.org/abs/2510.24317) **[Paper/Benchmark]**

* 📊 [Benchmark Best Practices for Evaluating AI Agents in Cybersecurity](https://arxiv.org/abs/2507.02825) **[Paper]**

---

## How to Navigate & Contribute

1. Browse the topic folder that matches your use case.  
2. Dive into its README for detailed descriptions and annotations, including resource type tags.  
3. To add a resource, open a PR in the appropriate folder’s `README.md`.  
4. Follow existing formatting and include the identifier tag (e.g., **[Paper]**, **[Blog]**, **[GitHub]**, **[Tool]**, **[Video]**, **[Model]**, **[Dataset]**).

> 📘 **See [CONTRIBUTING.md](CONTRIBUTING.md)** for full guidelines, style tips, and how to submit your PR.  


---

## License

Distributed under the MIT License. See [MIT License](LICENSE) for details.

##  Contact 

For suggestions or PRs, open an issue or reach out to me at ashfaaqf@proton.me .
