# DianeGPT 👋

![GitHub stars](https://img.shields.io/github/stars/dianegpt/dianegpt?style=social)
![GitHub forks](https://img.shields.io/github/forks/dianegpt/dianegpt?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/dianegpt/dianegpt?style=social)
![GitHub repo size](https://img.shields.io/github/repo-size/dianegpt/dianegpt)
![GitHub language count](https://img.shields.io/github/languages/count/dianegpt/dianegpt)
![GitHub top language](https://img.shields.io/github/languages/top/dianegpt/dianegpt)
![GitHub last commit](https://img.shields.io/github/last-commit/dianegpt/dianegpt?color=red)
[![Discord](https://img.shields.io/badge/Discord-Open_WebUI-blue?logo=discord&logoColor=white)](https://discord.gg/5rJgQTnV4s)
[![](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86)](https://github.com/sponsors/dianegpt)

![DianeGPT Banner](./banner.png)

**DianeGPT is an [extensible](https://docs.DianeGPT.com/features/extensibility/plugin), feature-rich, and user-friendly self-hosted AI platform designed to operate entirely offline.** It supports various LLM runners like **Ollama** and **OpenAI-compatible APIs**, with **built-in inference engine** for RAG, making it a **powerful AI deployment solution**.

Passionate about open-source AI? [Join our team →](https://careers.DianeGPT.com/)

![DianeGPT Demo](./demo.png)

> [!TIP]  
> **Looking for an [Enterprise Plan](https://docs.DianeGPT.com/enterprise)?** – **[Speak with Our Sales Team Today!](https://docs.DianeGPT.com/enterprise)**
>
> Get **enhanced capabilities**, including **custom theming and branding**, **Service Level Agreement (SLA) support**, **Long-Term Support (LTS) versions**, and **more!**

For more information, be sure to check out our [DianeGPT Documentation](https://docs.DianeGPT.com/).

## Key Features of DianeGPT ⭐

- 🚀 **Effortless Setup**: Install seamlessly via pip, uv, Docker, or Kubernetes (kubectl, kustomize, or helm), with `:ollama` and `:cuda` tagged images available for container deployments.

- 🤝 **Broad Model & API Integration**: Connect any OpenAI-compatible API alongside local Ollama models. Point the API URL at **LMStudio, GroqCloud, Mistral, OpenRouter, vLLM, and more** to mix and match providers freely.

- 🔐 **Granular RBAC & User Groups**: Administrators define detailed roles, groups, and permissions, giving each user exactly the access they need. Secure by default, with tailored experiences per group.

- 🧩 **Plugin Support**: Extend DianeGPT with **Filters**, **Actions**, **Pipes**, **Tools**, and **Skills**. Connect external services through **MCP**, **MCPO**, and **OpenAPI tool servers**. Build custom integrations, rate limits, approval flows, data connections, and more.

- 🤖 **Models & Agents**: Wrap any base model with custom instructions, tools, and knowledge to build specialized agents. Supports dynamic variables, per-user/group access control, and community preset imports via [DianeGPT Community](https://DianeGPT.com/).

- 📝 **Notes**: A dedicated workspace for content outside conversations. Draft with a rich editor, use AI to rewrite selected text, and attach notes to any chat for full-context injection.

- 📢 **Channels**: Real-time shared spaces where your team and AI models collaborate in one timeline. Tag models to draft or critique, with threads, reactions, pins, and access control.

- 🧠 **Persistent Memory**: The AI remembers facts about you across conversations, carrying context from one chat to the next.

- ✅ **Live Workflow & Message Flow**: Watch the AI build and work through checklists in real time. Queue messages while the AI is still responding; they send automatically when it's ready.

- 📅 **Calendar & AI Scheduling**: Built-in personal and shared calendars with month/week/day views, recurring events, color coding, attendees, and reminders. Models manage your schedule conversationally through native function calling.

- ⏱️ **Automations**: Schedule prompts to run on recurring schedules, with runs surfaced on your calendar and each completed run linking back to the chat it produced.

- 📱 **Responsive Design & PWA**: Seamless experience across desktop, laptop, and mobile, with a Progressive Web App for native app-like feel and offline access on localhost.

- ✒️🔢 **Full Markdown and LaTeX Support**: Comprehensive Markdown and LaTeX capabilities for enriched interaction.

- 🎤📹 **Hands-Free Voice/Video Call**: Integrated voice and video calls with multiple Speech-to-Text providers (Local Whisper, OpenAI, Deepgram, Azure) and Text-to-Speech engines (Azure, ElevenLabs, OpenAI, Transformers, WebAPI).

- 💾 **Persistent Artifact Storage**: Built-in key-value storage API for artifacts, enabling journals, trackers, leaderboards, and collaborative tools with personal and shared data scopes.

- 📚 **Local RAG Integration**: Retrieval Augmented Generation backed by 9 vector databases and multiple content-extraction engines (Tika, Docling, Document Intelligence, Mistral OCR, PaddleOCR-vl, external loaders). Supports hybrid search (BM25 + vector) with reranking and full-context mode. Load documents into chat or pull them from your library with the `#` command.

- 🔍 **Web Search for RAG**: Search the web through dozens of providers including `SearXNG`, `Google PSE`, `Brave Search`, `Kagi`, `Mojeek`, `Tavily`, `Perplexity`, `Firecrawl`, `serpstack`, `serper`, `Serply`, `DuckDuckGo`, `SearchApi`, `SerpApi`, `Bing`, `Jina`, `Exa`, `Sougou`, `Azure AI Search`, and `Ollama Cloud`, injecting results directly into the conversation.

- 🌐 **Web Browsing Capability**: Pull websites into chat with the `#` command followed by a URL, or let the model fetch them on its own when needed.

- 🎨 **Image Generation & Editing**: Create and edit images with multiple engines including OpenAI DALL·E, Gemini, ComfyUI (local), and AUTOMATIC1111 (local), supporting both generation and prompt-based editing.

- ⚙️ **Multi-Model Conversations**: Engage several models at once, harnessing their individual strengths in parallel for the best possible responses.

- 📊 **Usage Analytics & Model Evaluation**: Admin dashboards track message volume, token consumption, and cost across users and models. Evaluate models with a built-in arena, A/B testing, and ELO-based leaderboards.

- 🗄️ **Flexible Database & Storage**: Choose SQLite (with optional encryption) or PostgreSQL, and store files locally or on S3, Google Cloud Storage, or Azure Blob Storage.

- 🧬 **Advanced Vector Database Support**: Pick from 9 vector databases: ChromaDB, PGVector, Qdrant, Milvus, Elasticsearch, OpenSearch, Pinecone, S3Vector, and Oracle 23ai.

- 🪪 **Enterprise Authentication & Provisioning**: Full LDAP/Active Directory integration, SSO via trusted headers and OAuth providers, and SCIM 2.0 automated provisioning for identity providers like Okta, Azure AD, and Google Workspace.

- ☁️ **Cloud-Native File Integration**: Native Google Drive and OneDrive/SharePoint file picking for seamless document import from enterprise cloud storage.

- 🔭 **Production Observability**: Built-in OpenTelemetry support for traces, metrics, and logs, plugging into your existing monitoring stack.

- ⚖️ **Horizontal Scalability**: Redis-backed session management and WebSocket support for multi-worker, multi-node deployments behind load balancers.

- 🌐🌍 **Multilingual Support**: Use DianeGPT in your preferred language with i18n support. We're actively seeking contributors to expand language coverage!

- 🌟 **Continuous Updates**: We're committed to improving DianeGPT with regular updates, fixes, and new features.

- 🛡️ **Transparent Security Process**: Security reports are triaged, fixed, and published as open advisories through a documented responsible-disclosure process. See our [Security Policy](https://github.com/dianegpt/dianegpt/security).

Want to learn more about DianeGPT's features? Check out our [DianeGPT documentation](https://docs.DianeGPT.com/features) for a comprehensive overview!

## The DianeGPT Ecosystem 🌐

DianeGPT is the core, surrounded by companion apps and infrastructure that extend what your AI can do, where it can reach, and how you run it:

- 💻 **DianeGPT Computer** ([dianegpt/computer](https://github.com/dianegpt/computer)): A standalone, mobile-first computer and coding agent that runs on the machine you own. Files, terminal, and git in a browser tab, reachable from your phone. Connect it into DianeGPT as a model, or reach it from Telegram, WhatsApp, and more.

- ⚡ **Open Terminal** and **Terminals (Enterprise)** ([dianegpt/open-terminal](https://github.com/dianegpt/open-terminal) & [dianegpt/terminals](https://github.com/dianegpt/terminals)): A self-hosted computing environment that plugs into DianeGPT, giving the AI a place to write code, run it, read output, fix errors, and iterate inside the chat. Terminals gives you per-user isolated containers with separate credentials, resource limits, and network rules. Automatic lifecycle management on Docker or Kubernetes.

- 🔄 **oikb** ([dianegpt/oikb](https://github.com/dianegpt/oikb)): Feed your Knowledge Bases from 45+ sources (GitHub, Confluence, ServiceNow, Salesforce, Jira, Slack, SharePoint, Notion, and more), keeping the tools your team already uses continuously in sync.

- 🖥️ **Native Desktop App** ([dianegpt/desktop](https://github.com/dianegpt/desktop)): Run DianeGPT as a native app on macOS, Windows, and Linux. System-wide Spotlight chat bar with screenshot capture, push-to-talk voice, and optional fully-local inference via a built-in llama.cpp engine.

Want to learn more? Check out our [DianeGPT documentation](https://docs.DianeGPT.com) for more details!

---

We are incredibly grateful for the generous support of our sponsors. Their contributions help us to maintain and improve our project, ensuring we can continue to deliver quality work to our community. Thank you!

## How to Install 🚀

### Installation via Python pip 🐍

DianeGPT can be installed using pip, the Python package installer. Before proceeding, ensure you're using **Python 3.11** to avoid compatibility issues.

1. **Install DianeGPT**:
   Open your terminal and run the following command to install DianeGPT:

   ```bash
   pip install dianegpt
   ```

2. **Running DianeGPT**:
   After installation, you can start DianeGPT by executing:

   ```bash
   dianegpt serve
   ```

This will start the DianeGPT server, which you can access at [http://localhost:8080](http://localhost:8080)

### Quick Start with Docker 🐳

> [!NOTE]  
> Please note that for certain Docker environments, additional configurations might be needed. If you encounter any connection issues, our detailed guide on [DianeGPT Documentation](https://docs.DianeGPT.com/) is ready to assist you.

> [!WARNING]
> When using Docker to install DianeGPT, make sure to include the `-v dianegpt:/app/backend/data` in your Docker command. This step is crucial as it ensures your database is properly mounted and prevents any loss of data.

> [!TIP]  
> If you wish to utilize DianeGPT with Ollama included or CUDA acceleration, we recommend utilizing our official images tagged with either `:cuda` or `:ollama`. To enable CUDA, you must install the [Nvidia CUDA container toolkit](https://docs.nvidia.com/dgx/nvidia-container-runtime-upgrade/) on your Linux/WSL system.

### Installation with Default Configuration

- **If Ollama is on your computer**, use this command:

  ```bash
  docker run -d -p 3000:8080 --add-host=host.docker.internal:host-gateway -v dianegpt:/app/backend/data --name dianegpt --restart always ghcr.io/dianegpt/dianegpt:main
  ```

- **If Ollama is on a Different Server**, use this command:

  To connect to Ollama on another server, change the `OLLAMA_BASE_URL` to the server's URL:

  ```bash
  docker run -d -p 3000:8080 -e OLLAMA_BASE_URL=https://example.com -v dianegpt:/app/backend/data --name dianegpt --restart always ghcr.io/dianegpt/dianegpt:main
  ```

- **To run DianeGPT with Nvidia GPU support**, use this command:

  ```bash
  docker run -d -p 3000:8080 --gpus all --add-host=host.docker.internal:host-gateway -v dianegpt:/app/backend/data --name dianegpt --restart always ghcr.io/dianegpt/dianegpt:cuda
  ```

### Installation for OpenAI API Usage Only

- **If you're only using OpenAI API**, use this command:

  ```bash
  docker run -d -p 3000:8080 -e OPENAI_API_KEY=your_secret_key -v dianegpt:/app/backend/data --name dianegpt --restart always ghcr.io/dianegpt/dianegpt:main
  ```

### Installing DianeGPT with Bundled Ollama Support

This installation method uses a single container image that bundles DianeGPT with Ollama, allowing for a streamlined setup via a single command. Choose the appropriate command based on your hardware setup:

- **With GPU Support**:
  Utilize GPU resources by running the following command:

  ```bash
  docker run -d -p 3000:8080 --gpus=all -v ollama:/root/.ollama -v dianegpt:/app/backend/data --name dianegpt --restart always ghcr.io/dianegpt/dianegpt:ollama
  ```

- **For CPU Only**:
  If you're not using a GPU, use this command instead:

  ```bash
  docker run -d -p 3000:8080 -v ollama:/root/.ollama -v dianegpt:/app/backend/data --name dianegpt --restart always ghcr.io/dianegpt/dianegpt:ollama
  ```

Both commands facilitate a built-in, hassle-free installation of both DianeGPT and Ollama, ensuring that you can get everything up and running swiftly.

After installation, you can access DianeGPT at [http://localhost:3000](http://localhost:3000). Enjoy! 😄

### Other Installation Methods

We offer various installation alternatives, including non-Docker native installation methods, Docker Compose, Kustomize, and Helm. Visit our [DianeGPT Documentation](https://docs.DianeGPT.com/getting-started/) or join our [Discord community](https://discord.gg/5rJgQTnV4s) for comprehensive guidance.

### Troubleshooting

Encountering connection issues? Our [DianeGPT Documentation](https://docs.DianeGPT.com/troubleshooting/) has got you covered. For further assistance and to join our vibrant community, visit the [DianeGPT Discord](https://discord.gg/5rJgQTnV4s).

#### DianeGPT: Server Connection Error

If you're experiencing connection issues, it’s often due to the WebUI docker container not being able to reach the Ollama server at 127.0.0.1:11434 (host.docker.internal:11434) inside the container . Use the `--network=host` flag in your docker command to resolve this. Note that the port changes from 3000 to 8080, resulting in the link: `http://localhost:8080`.

**Example Docker Command**:

```bash
docker run -d --network=host -v dianegpt:/app/backend/data -e OLLAMA_BASE_URL=http://127.0.0.1:11434 --name dianegpt --restart always ghcr.io/dianegpt/dianegpt:main
```

### Keeping Your Docker Installation Up-to-Date

Check our Updating Guide available in our [DianeGPT Documentation](https://docs.DianeGPT.com/getting-started/updating).

### Using the Dev Branch 🌙

> [!WARNING]
> The `:dev` branch contains the latest unstable features and changes. Use it at your own risk as it may have bugs or incomplete features.

If you want to try out the latest bleeding-edge features and are okay with occasional instability, you can use the `:dev` tag like this:

```bash
docker run -d -p 3000:8080 -v dianegpt:/app/backend/data --name dianegpt --add-host=host.docker.internal:host-gateway --restart always ghcr.io/dianegpt/dianegpt:dev
```

### Offline Mode

If you are running DianeGPT in an offline environment, you can set the `HF_HUB_OFFLINE` environment variable to `1` to prevent attempts to download models from the internet.

```bash
export HF_HUB_OFFLINE=1
```

## What's Next? 🌟

Discover upcoming features on our roadmap in the [DianeGPT Documentation](https://docs.DianeGPT.com/roadmap/).

## License 📜

This project contains code under multiple licenses. The current codebase includes components licensed under the DianeGPT License with an additional requirement to preserve the "DianeGPT" branding, as well as prior contributions under their respective original licenses. For a detailed record of license changes and the applicable terms for each section of the code, please refer to [LICENSE_HISTORY](./LICENSE_HISTORY). For complete and updated licensing details, please see the [LICENSE](./LICENSE) and [LICENSE_HISTORY](./LICENSE_HISTORY) files.

## Support 💬

If you have any questions, suggestions, or need assistance, please open an issue or join our
[DianeGPT Discord community](https://discord.gg/5rJgQTnV4s) to connect with us! 🤝

## Security 🛡️

If you believe you've found a security vulnerability, or something that shouldn't be disclosed publicly, please [reach out confidentially through our responsible disclosure program on GitHub](https://github.com/dianegpt/dianegpt/security). We accept reports only through GitHub, not through any other platform. Thank you for helping us keep DianeGPT secure!

## Star History

<a href="https://star-history.com/#dianegpt/dianegpt&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=dianegpt/dianegpt&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=dianegpt/dianegpt&type=Date" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=dianegpt/dianegpt&type=Date" />
  </picture>
</a>

---

Created by [Timothy Jaeryang Baek](https://github.com/tjbck) - Let's make DianeGPT even more amazing together! 💪
