# Awesome Open-Source AI Tools and Tutorials for Node.js Developers

[![GitHub stars](https://img.shields.io/github/stars/YOUR_USERNAME/YOUR_REPO.svg?style=social&label=Star&maxAge=2592000)](https://github.com/hsamnguyen/Awesome-Open-Source-AI-Tools-and-Tutorials-for-Node.js-Development/stargazers/)  
[![GitHub forks](https://img.shields.io/github/forks/YOUR_USERNAME/YOUR_REPO.svg?style=social&label=Fork&maxAge=2592000)](https://github.com/hsamnguyen/Awesome-Open-Source-AI-Tools-and-Tutorials-for-Node.js-Development/network/)  
[![GitHub issues](https://img.shields.io/github/issues/YOUR_USERNAME/YOUR_REPO.svg)](https://github.com/hsamnguyen/Awesome-Open-Source-AI-Tools-and-Tutorials-for-Node.js-Development/issues/)  

This repository curates a collection of awesome open-source AI-powered tools, workflow automation platforms (inspired by n8n), AI libraries, frameworks, and advanced tutorials tailored for coders and developers working in the Node.js stack (including Nuxt.js, Next.js, and other full-stack Node.js setups). Focus is on self-hosted, integrable solutions for building AI agents, automations, and ML features in development pipelines. Updated as of July 25, 2025, with the latest tools and tutorials.

If you're a Node.js developer looking to integrate AI into your workflows, this is your go-to resource. Contributions welcome! Feel free to submit pull requests with new tools or tutorials.

## Table of Contents

- [Workflow Automation Tools (Similar to n8n)](#workflow-automation-tools-similar-to-n8n)
- [AI Libraries and Frameworks for Node.js](#ai-libraries-and-frameworks-for-nodejs)
- [AI Agent Frameworks](#ai-agent-frameworks)
- [Example Open-Source Next.js AI Projects](#example-open-source-nextjs-ai-projects)
- [Advanced Tutorials for n8n Workflow Automation](#advanced-tutorials-for-n8n-workflow-automation)
- [Advanced Tutorials for AI Libraries and Frameworks in Node.js](#advanced-tutorials-for-ai-libraries-and-frameworks-in-nodejs)
- [Advanced Tutorials for AI Agent Frameworks](#advanced-tutorials-for-ai-agent-frameworks)
- [Getting Started with n8n for AI](#getting-started-with-n8n-for-ai)
- [Additional Resources](#additional-resources)
- [Contributing](#contributing)
- [License](#license)

## Workflow Automation Tools (Similar to n8n)

These open-source tools are great for building AI-driven workflows, with Node.js compatibility for full-stack integration. Updated with 2025 alternatives like Camunda and ProcessMaker for advanced orchestration.

| Tool          | Description                                                                 | GitHub/Link                                      |
|---------------|-----------------------------------------------------------------------------|--------------------------------------------------|
| Node-RED     | Flow-based programming for IoT, APIs, and AI workflows. Supports custom JS nodes and AI integrations. | [github.com/node-red/node-red](https://github.com/node-red/node-red) |
| ActivePieces | Self-hosted automation with AI agents and custom JS nodes.                  | [github.com/activepieces/activepieces](https://github.com/activepieces/activepieces) |
| Huginn       | Agent-based system for monitoring and acting on data with JS scripts.       | [github.com/huginn/huginn](https://github.com/huginn/huginn) |
| Windmill     | Workflow engine with AI scripting in TypeScript/JS.                         | [github.com/windmill-labs/windmill](https://github.com/windmill-labs/windmill) |
| Automatisch  | Lightweight workflow automation with AI nodes.                              | [github.com/automatisch/automatisch](https://github.com/automatisch/automatisch) |
| Kestra       | Declarative orchestration with AI plugins and JS configs.                   | [github.com/kestra-io/kestra](https://github.com/kestra-io/kestra) |
| Camunda      | BPMN-based workflow engine with AI extensions for process automation.       | [github.com/camunda/camunda-bpm-platform](https://github.com/camunda/camunda-bpm-platform) |
| ProcessMaker | Open-source BPM and workflow automation with low-code AI integrations.      | [github.com/ProcessMaker/processmaker](https://github.com/ProcessMaker/processmaker) |

For more, check [github.com/meirwah/awesome-workflow-engines](https://github.com/meirwah/awesome-workflow-engines).

## AI Libraries and Frameworks for Node.js

JS/Node.js-specific libraries for integrating AI into apps like Next.js APIs or Nuxt servers. Updated with 2025 top picks like TensorFlow.js and OpenAI Node SDK.

| Tool            | Description                                                                 | GitHub/Link                                      |
|-----------------|-----------------------------------------------------------------------------|--------------------------------------------------|
| LangChain.js   | JS version for building AI chains, agents, and RAG with LLMs.               | [github.com/langchain-ai/langchainjs](https://github.com/langchain-ai/langchainjs) |
| Transformers.js| Hugging Face's JS library for ML models (NLP, vision) in browser/server.    | [github.com/huggingface/transformers.js](https://github.com/huggingface/transformers.js) |
| Brain.js       | Neural network library for deep learning in JS.                             | [github.com/BrainJS/brain.js](https://github.com/BrainJS/brain.js) |
| Vercel AI SDK  | SDK for AI integrations (streaming, RAG) with providers like OpenAI.        | [github.com/vercel/ai](https://github.com/vercel/ai) |
| TensorFlow.js  | Powerhouse ML library for training and deploying models in Node.js.         | [github.com/tensorflow/tfjs](https://github.com/tensorflow/tfjs) |
| OpenAI Node SDK| Official SDK for integrating OpenAI APIs (e.g., GPT models) in Node.js.    | [github.com/openai/openai-node](https://github.com/openai/openai-node) |
| Node-NLP      | Natural language processing library for Node.js.                            | [github.com/axa-group/nlp.js](https://github.com/axa-group/nlp.js) |

Curated list: [github.com/scrimba/awesome-javascript-ai](https://github.com/scrimba/awesome-javascript-ai).

## AI Agent Frameworks

Frameworks for building AI agents in Node.js, with tools and multi-agent support. Updated with JS-focused options like Mastra.

| Tool     | Description                                                                 | GitHub/Link                                      |
|----------|-----------------------------------------------------------------------------|--------------------------------------------------|
| CrewAI  | Orchestrates AI agents with roles/tasks; JS support.                        | [github.com/joaomdmoura/crewAI](https://github.com/joaomdmoura/crewAI) |
| Phidata | Builds autonomous AI assistants/agents.                                     | [github.com/phidatahq/phidata](https://github.com/phidatahq/phidata) |
| Mastra  | TypeScript framework for AI agents and multi-agent systems.                 | [github.com/mastra-ai/mastra](https://github.com/mastra-ai/mastra) |

More: [github.com/e2b-dev/awesome-ai-agents](https://github.com/e2b-dev/awesome-ai-agents).

## Example Open-Source Next.js AI Projects

Inspiration for full-stack Node.js AI apps:

- AI Chatbot: [github.com/vercel/ai-chatbot](https://github.com/vercel/ai-chatbot)
- MiniPerplx (AI Search): [github.com/zaidmukaddam/scira](https://github.com/zaidmukaddam/scira)
- Supabase Vector DB: [github.com/supabase/supabase](https://github.com/supabase/supabase)
- Langline (AI Translations): [github.com/languine-ai/languine](https://github.com/languine-ai/languine)

## Advanced Tutorials for n8n Workflow Automation

Practical, advanced guides for AI workflows in n8n. Updated with July 2025 content like Google Gemini integrations.

| Tutorial | Description | Link |
|----------|-------------|------|
| Game-Changing n8n Workflows Tips and Tricks for 2025 | Advanced AI integration, error handling, and optimization techniques. | [medium.com/@dejanmarkovic_53716/game-changing-n8n-workflows-tips-and-tricks-for-2025-02ebf08a607c](https://medium.com/%40dejanmarkovic_53716/game-changing-n8n-workflows-tips-and-tricks-for-2025-02ebf08a607c) |
| NEW Google Gemini Nodes in n8n — Full Setup & Use Cases | Integrating Google Gemini for advanced AI workflows. | [youtube.com/watch?v=-pfwRhMo39E](https://www.youtube.com/watch?v=-pfwRhMo39E) |
| N8N FULL COURSE 6 HOURS (Build & Sell AI Automations + Agents) | Comprehensive course on building and monetizing AI agents. | [youtube.com/watch?v=2GZ2SNXWK-c](https://www.youtube.com/watch?v=2GZ2SNXWK-c) |
| How to Build AI Workflows in n8n: 4 Tutorials | ETL, lead gen, DevOps, classification workflows with AI APIs and custom JS. | [hostinger.com/tutorials/how-to-build-ai-workflows-in-n8n](https://www.hostinger.com/tutorials/how-to-build-ai-workflows-in-n8n) |
| How to Build AI Agents with n8n in 2025! (Full Course) | Multi-agent systems, vector DBs, local LLMs. | [youtube.com/watch?v=geR9PeCuHK4](https://www.youtube.com/watch?v=geR9PeCuHK4) |

More in n8n docs: [docs.n8n.io/advanced-ai/intro-tutorial/](https://docs.n8n.io/advanced-ai/intro-tutorial/).

## Advanced Tutorials for AI Libraries and Frameworks in Node.js

Tutorials for libraries like LangChain.js, integrated into Node.js apps. Updated with recent overviews.

| Tutorial | Description | Link |
|----------|-------------|------|
| Top AI Libraries for Node.js in 2025 | Overview of TensorFlow.js, Brain.js, OpenAI SDK, and more. | [javascript.plainenglish.io/hey-im-here-to-share-the-top-ai-libraries-for-node-js-in-2025-f007a1a17a87](https://javascript.plainenglish.io/hey-im-here-to-share-the-top-ai-libraries-for-node-js-in-2025-f007a1a17a87) |
| 10 Top Node.js Libraries and Tools For Machine Learning | In-depth on Brain.js, TensorFlow.js for ML in Node.js. | [corbado.com/blog/10-top-nodejs-libraries-machine-learning](https://www.corbado.com/blog/10-top-nodejs-libraries-machine-learning) |
| Server-side Inference in Node.js with Transformers.js | Sentiment analysis API with model caching. | [huggingface.co/docs/transformers.js/en/tutorials/node](https://huggingface.co/docs/transformers.js/en/tutorials/node) |
| Build an AI RAG Application with LangChain & Next.js | Vector stores, retrieval chains in Next.js. | [youtube.com/watch?v=YLagvzoWCL0](https://www.youtube.com/watch?v=YLagvzoWCL0) |
| Generative AI for Node.js: OpenAI, LangChain - TypeScript | LLM apps with Pinecone DB. | [udemy.com/course/ai-nodejs-openai-chatgpt-langchain-typescript/](https://www.udemy.com/course/ai-nodejs-openai-chatgpt-langchain-typescript/) |

Overview: [unite.ai/best-javascript-frameworks-for-building-ai-systems/](https://www.unite.ai/best-javascript-frameworks-for-building-ai-systems/).

## Advanced Tutorials for AI Agent Frameworks

Guides for building agents with JS frameworks like LangGraph.js. Updated with 2025 bootcamps and guides.

| Tutorial | Description | Link |
|----------|-------------|------|
| How to Build AI Agents and Multi-Agent Apps Using LangGraph and Node.js | Setup, agents, and multi-agent systems in Node.js. | [techstaunch.com/blogs/building-ai-agents-langgraph-nodejs-guide](https://techstaunch.com/blogs/building-ai-agents-langgraph-nodejs-guide) |
| AI Agent Bootcamp | International JS Conference San Diego 2025 | TypeScript and LLM tech for AI agents. | [javascript-conference.com/new-york/ai-agent-bootcamp-ny/](https://javascript-conference.com/new-york/ai-agent-bootcamp-ny/) |
| Learn AI Agents by Building 4 Full-Stack Apps in 19 Hours! (Next.js) | Hands-on building agents in Next.js. | [youtube.com/watch?v=-2yUgcBqgSM](https://www.youtube.com/watch?v=-2yUgcBqgSM) |
| Building AI Agents with LangChain.js: A Practical Guide | Agents with memory, tools, error handling. | [medium.com/@prospectai/building-ai-agents-with-langchain-js-a-practical-guide-f8a1239989b3](https://medium.com/@prospectai/building-ai-agents-with-langchain-js-a-practical-guide-f8a1239989b3) |
| AI Agents: Build an Agent from Scratch using JavaScript | No-framework agent with custom tools. | [pguso.medium.com/agentic-ai-in-javascript-no-frameworks-dc9f8fcaecc3](https://pguso.medium.com/agentic-ai-in-javascript-no-frameworks-dc9f8fcaecc3) |

List: [github.com/e2b-dev/awesome-ai-agents](https://github.com/e2b-dev/awesome-ai-agents).

## Getting Started with n8n for AI

n8n is ideal for Node.js devs—open-source, AI agents, free courses. Install via npm and integrate with Next.js. Consider Ollama for local LLMs, FastAPI/Next.js combos.

## Additional Resources

- Broader AI stacks: Llama 3 models.
- Curated lists: Awesome Workflow Engines, Awesome JavaScript AI.

## Contributing

Pull requests welcome! Add tools, tutorials, or fixes. Follow the [Contributor Covenant](https://www.contributor-covenant.org).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.