<h1 align="center">Awesome LLM Agent Security</h1>

<p align="center">
  <img src="https://github.com/user-attachments/assets/a03af1f3-50c8-425b-b761-16edda365ea7" alt="Angryyyy" width="700"/>
</p>

<p align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
  <a href="https://github.com/wearetyomsmnv/Awesome-LLM-agent-Security/stargazers"><img src="https://img.shields.io/github/stars/wearetyomsmnv/Awesome-LLM-agent-Security" alt="GitHub stars"></a>
</p>

<p align="center">
A curated list of resources about LLM agent security, vulnerabilities, attacks, and their applications in cybersecurity.
</p>

<h2 align="center">📚 Contents</h2>

<div align="center">

| 🔍 [Research](#research) | 🎯 [Threat Model](#threat-model) | 🛠️ [Build Agent](#build-agent) | 📊 [Results](#results) | 💼 [Solutions](#solutions) |
|:-----------------------:|:--------------------------------:|:------------------------------:|:---------------------:|:------------------------:|
| _Papers & Publications_ | _Threats & Vulnerabilities_ | _Development Guides for cybersecurity_ | _Successful cases_ | _Tools Overview_ |

</div>

<h1 align="center">🔰 Fundamentals</h1>

<h3 align="center">Basic Concepts</h3>

### LLM Agent - is an intelligent system used by a large language model to perform tasks.

> [!NOTE]
> **MultiAgent**: When there is an ensemble of many agents that perform one large task - this is called a multi-agent system. It is based on a large language model that is responsible for task planning and decision making.

---

### Memory

Memory in autonomous agents can be categorized into two main types:

• Short-Term Memory: This refers to the agent's ability to utilize in-context learning, where it retains information temporarily during a single interaction. This is often limited by the model's context window, which restricts the amount of information it can process at once.

• Long-Term Memory: This allows the agent to store and recall information over extended periods. Long-term memory is typically managed through external vector stores, enabling the agent to retrieve relevant information quickly. This capability is crucial for tasks that require knowledge accumulation and recall over time.

Memory plays a vital role in how agents learn from past experiences, refine their actions, and improve their performance in future tasks.

---

### Planning
Planning involves the agent's ability to break down complex tasks into manageable subgoals. This process can be enhanced through various techniques:

Task Decomposition: The agent can decompose a large task into smaller, more manageable steps. Techniques like Chain of Thought (CoT) prompting encourage the model to think step-by-step, making it easier to tackle complex problems.

Self-Reflection: Agents can evaluate their past actions, learn from mistakes, and refine their strategies. This iterative process helps improve decision-making and planning over time.

External Planning Tools: Some agents may utilize classical planning methods, such as the Planning Domain Definition Language (PDDL), to generate structured plans based on predefined domains.

Effective planning is essential for agents to navigate complex tasks and adapt to changing circumstances.

---

### Action
Action refers to the execution of tasks based on the agent's planning and memory. This involves:

Tool Use: Agents can interact with external APIs and tools to gather information, execute code, or perform specific functions that extend their capabilities beyond what is encoded in their model weights.

ReAct Framework: This framework integrates reasoning and action, allowing agents to generate reasoning traces alongside their actions. This helps in understanding the rationale behind decisions and improving future actions.

Dynamic Interaction: Agents can adapt their actions based on real-time observations and feedback from their environment, allowing for more responsive and intelligent behavior.



<p align="center">
  <img src="https://github.com/user-attachments/assets/7e623e2b-bbb9-4537-9a47-c3b7354a8528" alt="LLM Agent module with methods of their application " width="700"/>
</p>


## 🔄 Framework Comparison

<h2 align="center">🔄 Framework Comparison</h2>

<div align="center">

| Framework | Key Features | Focus Area | License | Language Support | Distributed Systems |
|:---------:|:------------|:-----------|:--------|:-----------------|:-------------------|
| **LangChain** | • Chain-based architecture<br>• Memory management<br>• Tool integration | General purpose LLM apps | MIT | Python, JavaScript | Limited |
| **AutoGPT** | • Autonomous goal pursuit<br>• Long-term memory<br>• Self-prompting | Autonomous agents | MIT | Python | No |
| **AgentGPT** | - Web-based interface<br>- Task decomposition<br>- Visual workflow | Task automation | MIT | TypeScript | Yes |
| **BabyAGI** | - Task prioritization<br>- Simple architecture<br>- Learning focus | Research & Education | MIT | Python | No |
| **Lyzr** | - Enterprise security<br>- Scalable architecture<br>- Pre-built agents | Enterprise solutions | Commercial | Python | Yes |
| **CrewAI** | - Multi-agent collaboration<br>- Role-based agents<br>- Team coordination | Complex workflows | Apache 2.0 | Python | Yes |

</div>

### Key Differences:

<div align="center">

| Category | Features | Examples/Details |
|:---------|:---------|:----------------|
| **Architecture Focus** | • Task-oriented<br>• Chain-based<br>• Multi-agent<br>• Enterprise-grade | • BabyAGI, AgentGPT<br>• LangChain<br>• CrewAI<br>• Lyzr |
| **Use Case Optimization** | • Research & Experimentation<br>• Enterprise Applications<br>• Personal Automation<br>• Educational Purposes | • Academic projects<br>• Business solutions<br>• Individual tools<br>• Learning platforms |
| **Development Approach** | • Low-code solutions<br>• Programming-intensive<br>• Visual builders<br>• API-first design | • No-code platforms<br>• Custom development<br>• Drag-and-drop interfaces<br>• API integration |
| **Deployment Options** | • Cloud-native<br>• Self-hosted<br>• Hybrid deployment<br>• Edge computing support | • Cloud platforms<br>• On-premise solutions<br>• Mixed environments<br>• Edge devices |
| **Integration Capabilities** | • API connectivity<br>• Database support<br>• Third-party tools<br>• Custom extensions | • REST/GraphQL APIs<br>• Various DB systems<br>• External services<br>• Custom plugins |

</div>


## 🤖 LLM Agents in Cybersecurity

<h3 align="center">Agent Core Properties</h3>

<table>
<tr>
<td width="50%">

| Essential Components | Description |
|:--------------------|:------------|
| **Role Definition** | Specific security function and responsibilities |
| **Goal Setting** | Clear security objectives and success criteria |
| **Backstory** | Detailed capabilities and operational context |
| **Tools Access** | Integration with security tools and APIs |

</td>
<td width="50%">

| Key Capabilities | Description |
|:-----------------|:------------|
| **Task Inheritance** | Ability to receive and delegate security tasks |
| **Boundary Management** | Operating within defined security constraints |
| **Tool Utilization** | Leveraging security tools and APIs effectively |
| **Collaborative Assessment** | Evaluating and coordinating with other agents |

</td>
</tr>
</table>

<h3 align="center">Security Applications & Benefits</h3>

<table>
<tr>
<td width="50%">

| Category | Features |
|:---------|:---------|
| **Threat Detection & Response** | • Real-time monitoring and alert triage<br>• Automated incident response workflows |
| **Security Operations** | • 24/7 autonomous security monitoring<br>• Automated routine security tasks |

</td>
<td width="50%">

| Category | Features |
|:---------|:---------|
| **Vulnerability Management** | • Continuous security assessment<br>• Automated vulnerability scanning |
| **Incident Investigation** | • Automated evidence collection<br>• Timeline reconstruction |

</td>
</tr>
</table>

<h3 align="center">Advantages in Security Context</h3>

<table>
<tr>
<td width="50%">

| Category | Capabilities |
|:---------|:-------------|
| **Enhanced Efficiency** | • Continuous operation without fatigue<br>• Rapid processing of security data |
| **Improved Accuracy** | • Reduced human error<br>• Standardized analysis methods |

</td>
<td width="50%">

| Category | Capabilities |
|:---------|:-------------|
| **Scalability** | • Handling multiple tasks simultaneously<br>• Easy deployment across systems |
| **Advanced Capabilities** | • Complex pattern recognition<br>• Real-time threat analysis |

</td>
</tr>
</table>

<h3 align="center">Creation Methods</h3>

<div align="center">

| Method | Description |
|:-------|:------------|
| **Human-designed** | Agents with specific security roles |
| **Auto-generated** | Agents created by LLMs for specialized tasks |
| **Hybrid** | Approaches combining human expertise and AI capabilities |

</div>

## Security Landscape

### 🔒 OWASP Top 10 for AI Agents (Non official)

<div align="center">

| Category | Risk | Description |
|:---------|:-----|:------------|
| [AAC-01](https://github.com/precize/OWASP-Agentic-AI/blob/main/agent-auth-control-01.md) | Authorization & Control Hijacking | Unauthorized control of agent actions |
| [ACS-02](https://github.com/precize/OWASP-Agentic-AI/blob/main/agent-critical-systems-02.md) | Critical Systems Interaction | Unsafe interaction with critical systems |
| [AGI-03](https://github.com/precize/OWASP-Agentic-AI/blob/main/agent-goal-instruction-03.md) | Goal & Instruction Manipulation | Malicious modification of agent objectives |
| [AHE-04](https://github.com/precize/OWASP-Agentic-AI/blob/main/agent-hallucination-04.md) | Hallucination Exploitation | Exploitation of agent's false assumptions |
| [AIC-05](https://github.com/precize/OWASP-Agentic-AI/blob/main/agent-impact-chain-05.md) | Impact Chain & Blast Radius | Cascading effects of agent actions |
| [AMC-06](https://github.com/precize/OWASP-Agentic-AI/blob/main/agent-memory-context-06.md) | Memory & Context Manipulation | Tampering with agent's memory systems |
| [AOR-07](https://github.com/precize/OWASP-Agentic-AI/blob/main/agent-orchestration-07.md) | Orchestration Exploitation | Multi-agent system vulnerabilities |
| [ARE-08](https://github.com/precize/OWASP-Agentic-AI/blob/main/agent-resource-exhaustion-8.md) | Resource Exhaustion | DoS and resource depletion attacks |
| [ASC-09](https://github.com/precize/OWASP-Agentic-AI/blob/main/agent-supply-chain-09.md) | Supply Chain Attacks | Compromised dependencies and components |
| [AKP-10](https://github.com/precize/OWASP-Agentic-AI/blob/main/agent-knowledge-poisoning-10.md) | Knowledge Base Poisoning | Contamination of agent's knowledge base |

</div>


<p align="center">
  <img src="https://github.com/user-attachments/assets/372b5a1f-7481-4050-8dfd-a690e8ba1c6d" alt="LLM Agent module with methods of their application " width="700"/>
</p>


<h2 align="center"> Practice Labs & Applications </h2>

<div align="center">

| Project | Type | Features | Purpose |
|:--------|:-----|:---------|:---------|
| [Damn Vulnerable LLM Agent](https://github.com/WithSecureLabs/damn-vulnerable-llm-agent) | Educational Lab | - ReAct agent testing<br>- Prompt injection scenarios<br>- SQL injection practice | Learning prompt & ReAct injection techniques |
| [Medusa](https://medusa.detoxio.dev/) | Testing Platform | - Agent vulnerability testing<br>- Security assessment<br>- Attack simulation | Practical security testing |

</div>

## 📚 Research & Publications

<h2 align="center"> Academic Papers </h2>

<div align="center">

| Title | Authors | Year | Key Findings |
|:------|:--------|:-----|:-------------|
| [Security Concerns with AI Agents](https://www.vpnranks.com/resources/security-concerns-with-ai-agents/) | VPNRanks | 2024 | - 52.5% data leakage predicted by 2025<br>- Market growth to $7.41B<br>- PII exposure risks |
| [Key Challenges in AI Agent Security](https://taleliyahu.medium.com/key-challenges-in-ai-agent-security-332d718ec8b4) | Tal Eliyahu | 2024 | - Confidentiality risks<br>- Integrity concerns<br>- Availability threats |
| [Beyond RCE: Autonomous Code Execution](https://www.securityrunners.io/post/beyond-rce-autonomous-code-execution-in-agentic-ai) | Security Runners | 2024 | - Code execution risks<br>- Agent autonomy threats<br>- Security implications |
| [Exploiting Huggingface's Assistants](https://www.lasso.security/blog/exploiting-huggingfaces-assistants-to-extract-users-data) | Lasso Security | 2023 | - Data extraction vulnerabilities<br>- Assistant exploitation<br>- Security measures |

</div>

<h2 align="center"> Security Tools & Frameworks </h2>

<div align="center">

| Project | Type | Description | Features |
|:--------|:-----|:------------|:----------|
| [HackSynth](https://github.com/aielte-research/HackSynth) | Framework | AI security testing framework | - Vulnerability assessment<br>- Attack simulation<br>- Security validation |
| [OsintAGI](https://github.com/wearetyomsmnv/OsintAGI/) | Tool | OSINT automation framework | - Intelligence gathering<br>- Data analysis<br>- Automated research |
| [Agent-Smith](https://github.com/sail-sg/Agent-Smith) | Security Tool | Agent security testing | - Behavior analysis<br>- Vulnerability detection<br>- Security assessment |
| [AI-OPS](https://github.com/antoninoLorenzo/AI-OPS) | Platform | Security operations for AI | - Threat detection<br>- Response automation<br>- Security monitoring |
| [PentAGI](https://github.com/vxcontrol/pentagi/) | Security Tool | Automated penetration testing | - Autonomous AI agents<br>- Professional security tools<br>- Comprehensive monitoring |
| [Tenuo](https://github.com/tenuo-ai/tenuo) | Authorization Framework | Capability-based authorization for AI agents | - Cryptographic warrants with task-scoped TTLs<br>- Offline verification<br>- Proof-of-possession binding<br>- LangChain/LangGraph/MCP integrations |

</div>

<h2 align="center"> Benchmarks & Evaluations </h2>

<div align="center">

| Project | Focus | Metrics | Key Features |
|:--------|:------|:--------|:-------------|
| [Agent-Attack](https://github.com/ChenWu98/agent-attack) | Attack Testing | Security vulnerabilities | - Attack vectors<br>- Defense evaluation<br>- Risk assessment |
| [Auto-Pen-Bench](https://github.com/lucagioacchini/auto-pen-bench) | Penetration Testing | Security benchmarks | - Automated testing<br>- Performance metrics<br>- Security scoring |
| [ASB](https://github.com/agiresearch/ASB) | Security Benchmark | Agent security | - Security metrics<br>- Performance analysis<br>- Vulnerability testing |
| [LLM-Agent-Benchmark](https://github.com/zhangxjohn/LLM-Agent-Benchmark-List) | Comprehensive | Agent evaluation | - Security testing<br>- Performance metrics<br>- Benchmark collection |

</div>

<h2 align="center"> Security Projects & Implementations </h2>

<div align="center">

| Project | Type | Purpose | Features |
|:--------|:-----|:--------|:----------|
| [Multi-Agent-SecOps](https://github.com/tegridydev/multi-agent-secops-llm) | Security Operations | LLM-based security | - Threat detection<br>- Response automation<br>- Security monitoring |
| [Cyber-Security-LLM-Agents](https://github.com/NVISOsecurity/cyber-security-llm-agents) | Security Framework | Agent-based security | - Security automation<br>- Threat analysis<br>- Response coordination |
| [Ridge Security](https://ridgesecurity.ai/) | Platform | AI security solution | - Vulnerability assessment<br>- Security testing<br>- Risk management |

</div>


<h2 align="center"> Technical Presentations & Whitepapers </h2>

<div align="center">

| Title | Organization | Year | Key Topics |
|:------|:-------------|:-----|:-----------|
| [The Double AI Agent](http://i.blackhat.com/EU-24/Presentations/EU-24-Cohen-TheDoubleAIAgent.pdf) | Black Hat EU | 2024 | - Agent manipulation techniques<br>- Double agent scenarios<br>- Defense strategies |
| [Mind the Data Gap](http://i.blackhat.com/EU-24/Presentations/EU-24-Pappu-Mind-the-Data-Gap.pdf) | Black Hat EU | 2024 | - Privacy in AI agents<br>- Multi-agent systems<br>- Security controls |
| [Agentic AI: New Frontier](https://aisuf.org/blogs/f/agentic-ai-a-new-frontier-in-security) | AI Security Union | 2024 | - Security implications<br>- Future trends<br>- Risk analysis |
| [Agent Security Analysis](https://arxiv.org/abs/2409.10737) | arXiv | 2023 | - Security frameworks<br>- Vulnerability assessment<br>- Protection measures |
| [Agent Behavior Study](https://arxiv.org/pdf/2409.03793) | arXiv | 2023 | - Behavioral analysis<br>- Attack patterns<br>- Security recommendations |

</div>






### Community Resources

- [OWASP AI Agent Security Project](https://github.com/precize/OWASP-Agentic-AI/) - Official repository
- [OWASP Slack #team-llm-autonomus-agents](https://owasp.slack.com/archives/team-llm-autonomus-agents) - Community discussions


<p align="center">
  <img src="https://github.com/user-attachments/assets/ad1c30fc-de20-49e7-85ee-3966cc22e4e9" alt="That is AGI" width="400"/>
</p>
