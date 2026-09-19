# 🚀 LLM-Based Honeypots

> A curated collection of Large Language Model (LLM) resources focused on **designing, deploying, and analyzing data from intelligent, interactive honeypots**.

Welcome to the **LLM-Based Honeypots** section of Awesome GenAI CyberHub! This space is dedicated to exploring how LLMs are being utilized to create more convincing and interactive honeypots that can engage attackers, gather deeper intelligence on their TTPs, and dynamically adapt their responses. 

---

## ✅ Curated Resources

### 🛠️ Tools & Frameworks

* [galah (GLA)](https://github.com/0x4D31/galah) **[Tool/GitHub]** - An LLM-powered web honeypot designed to emulate web applications and capture internet-wide scans. Featured in a DEF CON 32 presentation.

* [shelLM](https://github.com/stratosphereips/shelLM) **[Tool/GitHub]** - An LLM-based SSH honeypot.

* [VelLMes-AI-Deception-Framework](https://github.com/stratosphereips/VelLMes-AI-Deception-Framework) **[Tool/GitHub]** - An AI-driven deception framework that  incorporates LLMs for honeypot functionalities.

* [DECEIVE (by Splunk)](https://github.com/splunk/DECEIVE) **[Tool/GitHub]** - A framework related to AI-driven deception and honeypot concepts, as discussed in Splunk's blog. (See also associated blog post under "Articles & Blog Posts").

* [beelzebub](https://github.com/mariocandela/beelzebub) **[Tool/GitHub]** - A secure low-code honeypot framework leveraging LLMs for system virtualization and creating high-interaction honeypots. Supports multiple protocols like SSH, HTTP, and TCP.

* [honeybee](https://github.com/yaaras/honeybee) **[Tool/GitHub]** - LLM/agent-inspired deception and interaction experiments (honeypot-adjacent).

* [llm-honeypot (PalisadeResearch)](https://github.com/PalisadeResearch/llm-honeypot) **[Tool/GitHub]** - Modified Cowrie SSH honeypot that detects LLM-driven hacking agents using multi-stage prompt injection traps (goal hijacking + system prompt stealing). Includes a live dashboard. See also: [Paper (arXiv:2410.13919)](https://arxiv.org/abs/2410.13919).


### 📜 Research Papers

* [HoneyGPT: A Large Language Model (LLM) Framework for Creating Context-Aware and Evasive Honeypots](https://www.cse.psu.edu/~sxz16/papers/HoneyGPT.pdf) **[Paper]** - Details a framework for LLM-based honeypots.

* [LLMPot: Automated LLM-based Industrial Honeypot Generation via Optimal Prompt Inversion](https://paperswithcode.com/paper/llmpot-automated-llm-based-industrial) **[Paper]** - Focuses on automated generation of industrial honeypots using LLMs. (Also see arXiv version: [2405.05999](https://arxiv.org/abs/2405.05999))

* [LLM in the Shell: Generative Honeypots](https://ieeexplore.ieee.org/document/10628775) **[Paper]** - Research on LLM applications in honeypots from IEEE.

* [MySQL-Pot: A LLM-Based Honeypot for MySQL Threat Protection](https://ieeexplore.ieee.org/document/10607309) **[Paper]** - Additional research from IEEE on LLM-based deception.

* [LLM-Sherlock: An LLM-based Jailbreak and Misuse Assessment Framework for Cybersecurity Applications](https://arxiv.org/html/2409.08234v1) **[Paper]** - While broader, this paper on assessing LLM misuse can be relevant to understanding attacks against/by LLM-based systems, including honeypots.

* 📄 [SoK: Honeypots & LLMs, More Than the Sum of Their Parts? (arXiv:2510.25939)](https://arxiv.org/abs/2510.25939) **[Paper/SoK]** - Systematizes LLM-powered honeypot research since late 2022, asking whether LLMs actually resolve the long-standing design paradox of high-fidelity deception at low operational risk.

* 📄 [AdvancedShelLM: A Stateful Multi-Agent LLM Honeypot for SSH Deception (arXiv:2606.27990)](https://arxiv.org/abs/2606.27990) **[Paper]** - Multi-agent, multi-LLM successor to shelLM using a Manager/Worker split plus a persistent filesystem, so concurrent attackers see the same evolving state. Reaches up to 99.02% pass rate on shell-behavior correctness tests.

* 📄 [Honeyval: A Comprehensive Evaluation Framework for LLM-powered HTTP Honeypots (arXiv:2605.29963)](https://arxiv.org/abs/2605.29963) **[Paper/Framework]** - An evaluation framework for LLM-backed HTTP honeypots, targeting the gap between plausible-looking responses and measurable deception quality.

* 📄 [Honeyquest for LLMs: Rethinking Cyber Deception for AI Attackers (arXiv:2606.21037)](https://arxiv.org/abs/2606.21037) **[Paper]** - Tests whether human-centered deception hypotheses transfer to AI attackers, comparing 21 LLMs across 10 providers (10,962 responses) against a 47-participant human baseline on identical reconnaissance queries.

* 📄 [LLM-Based Penetration Testing in the Presence of Honeypots (arXiv:2609.08093)](https://arxiv.org/abs/2609.08093) **[Paper]** - Flips the usual framing: LLM attackers can reason about heterogeneous artifacts and use honeypot suspicion to steer target selection, formalized as a budgeted decision problem. Directly relevant to whether deception still works against agentic attackers.

* 📄 [Towards Agentic Honeynet Configuration (arXiv:2603.14122)](https://arxiv.org/abs/2603.14122) **[Paper]** - Applies agentic reasoning to the honeynet configuration problem — which honeypots to deploy under real network and compute budget limits.


### 📚 Videos & Blog Posts

* [Deceive AI - A Honeypot Concept Using Generative AI for Realistic Interactions (Splunk Blog)](https://www.splunk.com/en_us/blog/security/deceive-ai-honeypot-concept.html) **[Blog]** - Introduces Splunk's concept for an AI honeypot, related to the DECEIVE GitHub project.

* [GLA: An LLM-Powered Web Honeypot (DEF CON 32 Presentation)](https://www.youtube.com/watch?v=XGsm4Qcc_Ag) **[Video]** - A presentation by Adel Karimi about GLA, an LLM-powered web honeypot designed to emulate web applications and capture internet-wide scans. It discusses its architecture, how it compares to traditional honeypots, and includes examples and performance comparisons of different LLMs. This is the presentation for the 'galah' tool listed above.

---



## Navigate Back

* [Back to Awesome GenAI CyberHub Main Page](../../README.md)
