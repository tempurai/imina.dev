# imina - The All-in-One AI Application Development Platform

imina is an open-source, all-in-one platform designed to simplify and accelerate the development of AI applications. It seamlessly integrates a **visual workflow engine, RAG pipelines, and multi-agent systems**, enabling developers to move quickly from prototype to production.

> Inspired, and forked by Langflow, imina has been **completely rewritten from the ground up** to offer a more modern, powerful, and production-ready solution.

<img width="2341" height="1252" alt="image" src="https://github.com/user-attachments/assets/e84d64b7-d08b-403e-b84d-7f39225a2fee" />

---

### Roadmap to open soruce

We are actively working on the following features and welcome community feedback:

-   [ ] **Formal Open-Source Release**: Complete code cleanup and documentation to launch the community edition.
-   [ ] **Enhanced Multi-Agent Collaboration**: Introduce more advanced coordination and self-planning capabilities for agents.
-   [ ] **Dynamic Workflow Control**: Support for pausing, resuming, and modifying workflows at any node during execution.
-   [ ] **Knowledge Hub Editor**: A more powerful rich-text editing and knowledge management experience.
-   [ ] **Component Marketplace**: A community-driven platform for sharing and discovering custom components.
-   [ ] **Observability & Analytics**: Detailed tracing, logging, and performance analysis for workflow executions.

---

### Key Capabilities

-   **Out-of-the-Box Applications**:
    -   Intelligent Chat: A complete, multi-modal conversational AI with built-in RAG capabilities, web search, and persistent history.
    -   Knowledge Hub: A Notion-like system with a full document processing pipeline (upload, chunk, embed, summarize) to instantly create and manage knowledge bases for your AI.

-   **Modern Workflow Engine**
    -   Visually orchestrate complex AI workflows on an intuitive drag-and-drop canvas, supporting complex logic with branches, loops, and parallel execution.
    -   Access a rich library of over **200+ out-of-the-box components**, covering data processing, major LLM/Embedding models, API calls, logic control, and more.
    -   Build both **single agents** and **multi-agent systems** with support for sequential, parallel, and hierarchical (manager-worker) collaboration patterns.
    -   Seamlessly write and execute custom logic with the **Python Code** component for infinite extensibility.

-   **End-to-End RAG Pipeline**
    -   Automated content extraction, chunking, and **embedding** for various document formats (PDF, DOCX, MD, etc.).
    -   An integrated knowledge hub to manage vectorized content, serving as a persistent knowledge source for your AI applications.
    -   Built-in text splitters (character, recursive, semantic) and rerankers to optimize retrieval quality.

-   **Comprehensive Model & Ecosystem Support**
    -   **Seamless LLM Integration**: Easily connect and switch between dozens of models from **OpenAI, Anthropic, Google Gemini, DeepSeek, Ollama, Groq**, and more.
    -   **Diverse Vector Stores**: Support for multiple vector databases, including **Chroma, Pinecone, Qdrant, Weaviate, and Elasticsearch**.
    -   **Rich Tool Integrations**: 50+ built-in tools for **Google Search, Slack, Notion, Tavily**, and other external services.

-   **Built for Production**
    -   **Backend-as-a-Service**: Expose all core functionalities via APIs to integrate Mina into your existing business systems.
    -   **Triggers & Deployment**: Trigger workflows via API, webhooks, CRON jobs, or email.
    -   **Observability**: Provide detailed logging, tracing, and performance analytics to monitor and continuously improve your applications.
    -   **Enterprise-Grade Features (Upcoming)**: Support for SSO, multi-tenancy, and fine-grained access control.

<img width="1248" height="738" alt="image" src="https://github.com/user-attachments/assets/31bc7895-792e-4d2d-b99a-e8ee0418884b" />
<img width="1242" height="673" alt="image" src="https://github.com/user-attachments/assets/11bef5e3-bc12-45e6-a075-d449ef54d339" />

---

### Quick Start

**Cloud**
> imina Cloud is in the works! You'll soon be able to try all features with zero setup. Stay tuned.

**Self-Hosting**
> imina will be open-sourced soon. Once released, you can quickly get it running in your local environment using Docker.

```bash
# [To be provided upon open-sourcing]
git clone https://github.com/tempurai/imina.dev
cd imina/docker
docker-compose up -d
```

> After startup, access the imina console at `http://localhost:PORT`.
