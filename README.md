## Hi there, I'm Mansi 👋

<!--
**MansiDhanania/MansiDhanania** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<div align="center">

**AI Systems Engineer · Applied ML · Multimodal AI · Montreal, Canada**

[![Email](https://img.shields.io/badge/Email-mansidhanania%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mansidhanania@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-mansidhanania-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mansidhanania)
[![ACL 2025](https://img.shields.io/badge/ACL_2025-Findings_Paper-b31b1b?style=for-the-badge)](https://aclanthology.org/2025.findings-acl.1104/)

</div>

---

I'm a grad student at McGill finishing my M.Sc in ECSE. I spend my time building AI systems to solve real world problems.

My thesis is a multimodal AI assistant for blind users. Developing a system that *genuinely cannot fail, hallucinate or crash mid-session* has taught me more about building reliable LLM pipelines than anything else could. I worked on the backend architecture: multi-model orchestration, Redis session memory, Traefik infrastructure, MCP servers, n8n workflows, routing logic. One backend, three frontends (web, iOS/Android, smart glasses), no changes needed.

Apart from my thesis, I've been chasing two questions:
- 🤔 **Can LLMs actually be creative?** Not "generate interesting text" but capable of genuinely novel ideas in a measurable sense. I spent a semester at [Mila](https://mila.quebec/en) building a 4-agent RL-LLM loop to investigate this.
- ⚙️ **How do you build agentic systems that don't fall apart?** Multi-model routing, memory that helps rather than bloats context, fallback cascades that fail loudly. The engineering here is underrated.

---

## 🔨 Things I've built

**ShelfScout** *(M.Sc. thesis — [backend architecture](https://github.com/MansiDhanania/ShelfScout), [live here](https://cybersight.cim.mcgill.ca/))*
Real-time AI assistant for blind and visually impaired users. This included n8n orchestration across Claude, Gemini, LLaMA-4, Qwen3-VL and GPT-OSS; Redis session memory; Traefik + Docker; MCP servers. Frontend-agnostic by design: the same backend serves web, iOS/Android, and will talk to smart glasses. Benchmarked against Be My AI, Meta Ray-Ban glasses, and Gemini Live.

**[Novelty in LLM-Guided RL](https://github.com/MansiDhanania/Novelty-in-LLM-Guided-RL)**
4-agent RL-LLM loop where agents propose physics hypotheses, write their own reward functions, and critique each other. Cosine-similarity rejection sampling forces genuine novelty over paraphrasing. My _novelty seeker agent_ hit **3.6× higher** embedding distance than the baseline DQN. Whether that counts as creativity is still an open question.

**[OpenUBA](https://github.com/MansiDhanania/OpenUBA)**
Open-source insider threat detection over 32M+ behavioural logs. Five algorithms compared, AUC 0.9923, SHAP/LIME explainability.

---

## 📄 Published

**[How do Transformer Embeddings Represent Compositions? A Functional Analysis](https://aclanthology.org/2025.findings-acl.1104/)**
*Findings of ACL 2025, Vienna* — with Nagar, Rawal & Tan

TL;DR: we tested whether transformer models are actually compositional. Ridge regression wins, but plain vector addition is surprisingly competitive. BERT is bad at this. Mistral is not.

---

## 🧰 Tech Stack

### 🤖 LLMs & Agents
[![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)](https://langchain.com)
[![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)](https://n8n.io)
[![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logoColor=white)](https://ollama.com)
[![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)](https://openai.com)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-FF6C37?style=for-the-badge&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-6366F1?style=for-the-badge&logoColor=white)
![Tool--use](https://img.shields.io/badge/Tool--use-0EA5E9?style=for-the-badge&logoColor=white)
![Multi--agent](https://img.shields.io/badge/Multi--agent_Systems-8B5CF6?style=for-the-badge&logoColor=white)
![MCP Servers](https://img.shields.io/badge/MCP_Servers-14B8A6?style=for-the-badge&logoColor=white)

### 🧠 ML / DL
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://pytorch.org)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://tensorflow.org)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)
[![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)](https://opencv.org)
![Reinforcement Learning](https://img.shields.io/badge/Reinforcement_Learning-10B981?style=for-the-badge&logoColor=white)
![Diffusion Models](https://img.shields.io/badge/Diffusion_Models-EC4899?style=for-the-badge&logoColor=white)
![XAI](https://img.shields.io/badge/XAI_(SHAP%2FLIME)-F59E0B?style=for-the-badge&logoColor=white)

### ⚙️ Infra & DevOps
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://docker.com)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com)
[![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)](https://redis.io)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://linux.org)
[![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)](https://azure.microsoft.com)
[![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)](https://cloud.google.com)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=for-the-badge&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-2671E5?style=for-the-badge&logo=githubactions&logoColor=white)

### 💻 Languages
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)](https://isocpp.org)
[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://java.com)
[![SQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)](https://postgresql.org)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white)](https://mathworks.com)

---

## 🏅 Recognition

- 🏆 BLUE Fellowship — Mila & McGill Building 21 (2026)
- 🎓 McGill Graduate Excellence Award (2025)
- 🌐 McCall MacBain Regional Scholarship (2024)
- 🔬 Mitacs Accelerate Research Scholarship (2024)
- 🌏 A*Star Singapore International Pre-Graduate Award (2023–24)
- 🔬 Mitacs Globalink Research Internship Scholarship (2023)

---

## 🔭 Currently

- Wrapping up M.Sc. at McGill (May 2026)
- Building a RAG + agentic AI project — watch this space 👀
- Loking for **AI Engineer** and **Applied ML Research** roles

---

<div align="center">
  <i>always down for coffee chats, collaborations, and solving interesting problems</i><br>
  <a href="mailto:mansidhanania@gmail.com">mansidhanania@gmail.com</a>
</div>
