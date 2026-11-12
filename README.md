# Csaba Toth - senior software engineer, remote team lead, public speaker, tech meetup enthusiast

[![Twitter Badge](https://img.shields.io/badge/-tocsa2-blue?style=flat-square&logo=Twitter&logoColor=white&link=https://twitter.com/tocsa2/)](https://twitter.com/tocsa2/)
[![Linkedin Badge](https://img.shields.io/badge/-csabatothdev-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/csabatothdev/)](https://www.linkedin.com/in/csabatothdev/)
[![Instagram Badge](https://img.shields.io/badge/-MrCsabaToth-purple?style=flat-square&logo=instagram&logoColor=white&link=https://instagram.com/MrCsabaToth/)](https://instagram.com/MrCsabaToth)
[![GitLab Badge](https://img.shields.io/badge/-MrCsabaToth-orange?style=flat-square&logo=Gitlab&logoColor=white&link=https://gitlab.com/MrCsabaToth/)](https://gitlab.com/MrCsabaToth/)
[![GitHub Badge](https://img.shields.io/badge/-MrCsabaToth-black?style=flat-square&logo=Github&logoColor=white&link=https://github.com/MrCsabaToth/)](https://github.com/MrCsabaToth/)

---

- I use daily:
  ![JavaScript](https://img.shields.io/badge/-JavaScript-black?style=flat-square&logo=javascript)
  ![Python](https://img.shields.io/badge/-Python-8fcfd1?style=flat-square&logo=Python)
  ![C#](https://img.shields.io/badge/-C%23-orange?style=flat-square&logo=c-sharp)
  ![Flutter](https://img.shields.io/badge/-Flutter-blue?style=flat-square&logo=Flutter)
  ![Git](https://img.shields.io/badge/-Git-black?style=flat-square&logo=git)
  ![Shell](https://img.shields.io/badge/-Shell-5391FE?style=flat-square&logo=PowerShell)
  ![VS Code](https://img.shields.io/badge/-VS%20Code-007ACC?style=flat-square&logo=visual-studio-code)
  ![Android Studio](https://img.shields.io/badge/-Android%20Studio-green?style=flat-square&logo=android-studio)
  ![PyCharm](https://img.shields.io/badge/-PyCharm-green?style=flat-square&logo=pycharm)
  ![Visual Studio](https://img.shields.io/badge/-Visual%20Studio-blue?style=flat-square&logo=visual-studio)
- I work using:
  ![Django](https://img.shields.io/badge/-Django-092E20?style=flat-square&logo=Django)
  ![ASP.NET MVC](https://img.shields.io/badge/-ASP.NET%20MVC-orange?style=flat-square&logo=asp-net)
  ![Amazon AWS](https://img.shields.io/badge/Amazon%20AWS-232F3E?style=flat-square&logo=amazon-aws)
  ![MySQL](https://img.shields.io/badge/-MySQL-336791?style=flat-square&logo=mysql)
  ![Azure](https://img.shields.io/badge/Azure-232F7E?style=flat-square&logo=microsoft-azure)
  ![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github)
  ![GitLab](https://img.shields.io/badge/-GitLab-FCA121?style=flat-square&logo=gitlab)
  ![Bootstrap](https://img.shields.io/badge/-Bootstrap-563D7C?style=flat-square&logo=bootstrap)
  ![GCP](https://img.shields.io/badge/Google%20Cloud%20Platform-black?style=flat-square&logo=google-cloud)
  ![Linode](https://img.shields.io/badge/Linode-black?style=flat-square&logo=linode)
  ![Slack](https://img.shields.io/badge/Slack-red?style=flat-square&logo=slack)
- I also use:
  ![Firebase](https://img.shields.io/badge/Firebase-orange?style=flat-square&logo=firebase)
  ![Firestore](https://img.shields.io/badge/Firestore-orange?style=flat-square&logo=Firestore)
  ![Dart](https://img.shields.io/badge/-Dart-blue?style=flat-square&logo=Dart)
  ![Java](https://img.shields.io/badge/-java-E34A86?style=flat-square&logo=java)
  ![Kotlin](https://img.shields.io/badge/-kotlin-006a71?style=flat-square&logo=kotlin)
  ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
  ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3)
- I am also proficient:
  ![BigQuery](https://img.shields.io/badge/BigQuery-blue?style=flat-square&logo=big-query)
  ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql)
  ![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c)
- Learning about:
  ![Machine Learning](https://img.shields.io/badge/-Machine%20Learning-black?style=flat-square&logo=machine-learning)
  ![Docker](https://img.shields.io/badge/Docker-black?style=flat-square&logo=docker)
  ![Kubernetes](https://img.shields.io/badge/Kubernetes-blue?style=flat-square&logo=kubernetes)

---

### Generative AI and other Hackathon projects and wins
- [World Cup 2026 Live Predictor](https://github.com/CsabaConsulting/elastic-aws-hacknight): Developed for the **Elastic and AWS Hack Night (World Cup Edition)**, this project extends static tournament predictions with real-time in-game outcome forecasting. By capturing live match statistics from phone/TV screens during live gameplay and ingesting them into an Elasticsearch Serverless cluster, an agent performs momentum-based outcome predictions rather than relying solely on pre-match historical form.
  - Multi-index architecture on Elasticsearch Serverless: `wc2026_matches` storing tournament fixtures and results alongside `wc2026_live_stats` tracking per-minute in-game telemetry snapshots (possession, shots on target, passes, tackles, fouls, cards, scorers).
  - 4 custom ES|QL tools (`get_live_match_stats`, `get_team_form`, `get_team_stats_2026`, `get_upcoming_fixtures`) created in Elastic Agent Builder and exposed via a Model Context Protocol (MCP) server.
  - Two execution paths: Elastic Inference Service (EIS / AWS Bedrock) in Agent Builder and an interactive Streamlit chat application powered by Fireworks AI (`glm-5p2`) with real-time MCP tool invocation visualization.
  - [Project summary & architecture documentation](https://github.com/CsabaConsulting/elastic-aws-hacknight/blob/main/PROJECT_SUMMARY.md).
- [OrthoStream AI: Multimodal Orthodontic QA Diagnostic Agent & Aligner Simulator](https://github.com/Orthostream-AI/OrthostreamAI): Built for the **[Google I/O Build with AI Hackathon x Google Cloud Labs](https://gdg.community.dev/events/details/google-gdg-nyc-presents-google-io-build-with-ai-hackathon-x-google-cloud-labs/cohost-gdg-nyc/)**, OrthoStream AI is an interactive full-stack clinical validation assistant and simulation workspace for clear-aligner treatment planning. It bridges spoken clinical feedback and digital aligner manufacturing by translating doctor voice transcripts into mathematically validated tooth-movement directives with real-time holographic simulation.
  - Powered by the Google GenAI SDK (`@google/genai`) using Gemini 3.5 Flash for multimodal audio command transcription, natural language clinical intent mapping, and JSON directive generation.
  - Interleaved diagnostic execution flow powered by a Server-Sent Events (SSE) streaming engine delivering dynamic 3D mesh comparisons, stage focus scrubbers, geometric discrepancy cards, and clinical assertion reports.
  - Dual graphics simulation engine featuring interactive HTML5 vector canvases with matrix rotation, tooth-contour morphing, drag-and-drop smile calibration, holographic 3D X-ray bone scanners, and color-coded stress curves.
  - Built with React 19, Tailwind CSS, `motion`, Node.js/Express, containerized and packaged for Google Cloud Run.
  - [Documentation and architecture repository](https://github.com/Orthostream-AI/Documentation).
  - 3rd place podium at the Google I/O Build with AI Hackathon x Google Cloud Labs
- [CivicAurAI](https://github.com/Civic-AurAI/CivicAurAI): Created for the **[Build and solve with AI: San Francisco edition pre-RSAC Hackathon](https://gdg.community.dev/events/details/google-gdg-newport-beach-presents-build-and-solve-with-ai-day-2-san-francisco-edition/)** ([Day 1](https://luma.com/j2176blg?tk=AY7Woi) and [Day 2](https://luma.com/op7obu11?tk=Ae5btp)), CivicAurAI is a civic infrastructure intelligence and municipal reporting ecosystem connecting citizens, city agencies, and autonomous vehicle fleets.
  - Continuous dashcam and mobile video recording ([CivicAurAIRecorder](https://github.com/Civic-AurAI/CivicAurAIRecorder)) with synchronized GPS telemetry automatically flags municipal hazards like potholes, illegal dumping, and encampments.
  - Multimodal video processing pipeline built on RocketRide AI and Google multimodal models for automated hazard detection and visual chain-of-custody verification.
  - Spanner Property Graph (CivicGraph) and Spanner RDBMS architecture for temporal episode tracking (Graphity temporal modeling), deduplicating independent AI vehicle detections with human citizen reports, and dynamic service routing to municipal organizations based on geographic district boundaries.
  - Community upvoting mechanics to assess community priority without artificial vehicle telemetry inflation.
  - [Civic-AurAI organization](https://github.com/Civic-AurAI/) and [Final submission codebase](https://github.com/Civic-AurAI/Final_Code).
  - Winner of "Best use of Gemini" and RocketRide special prizes
- [Eephor: Oversight Agent for Multi-Agent Systems](https://github.com/Eephor/DataMassageForGRPO): Developed during the **[Reinforcement Learning Hackathon by Cerebral Valley](https://cerebralvalley.ai/e/openenv-hackathon-sf)**, Eephor is an end-to-end training and evaluation pipeline for specialized LLM oversight agents capable of distinguishing benevolent agents from deceptive ones in complex multi-agent environments like MoltBook.
  - Transforms conversational logs ([Ethos Academy](https://github.com/allierays/ethos-academy)) into structured ground-truth datasets across 12 traits (Integrity, Logic, Empathy) with strict thread-level data splitting to prevent contextual data leakage.
  - Estimates hidden internal intent and agent architecture (replicating dynamic `SOUL.md` profiles) using behavior trait rubrics and few-shot multi-turn conversational reasoning.
  - Two-stage training pipeline: Parameter-Efficient Fine-Tuning (PEFT) with LoRA via Unsloth for Supervised Fine-Tuning (SFT) pre-warming, followed by **Reinforcement Learning with Verifiable Rewards (RLVR)** via **Group Relative Policy Optimization (GRPO)** in OpenEnv to prevent reward hacking.
  - Published open oversight models on Hugging Face: [`moltbook-oversight-llama31-1b`](https://huggingface.co/tocsa/moltbook-oversight-llama31-1b) and [`moltbook-oversight-llama-3.2-3b-instruct`](https://huggingface.co/tocsa/moltbook-oversight-llama-3.2-3b-instruct) (standard and GGUF quantizations).
  - [Eephor Jupyter PyTorch training environment](https://github.com/Eephor/jupyter-pytorch).
- [BarackOllama & BarackOllamaCLI](https://github.com/LlamaLoungeSnowflake/BarackOllama): Built for the **[Llama Lounge Snowflake Agentic Hackathon](https://www.snowflake.com/en/news/press-releases/snowflake-expands-ai-footprint-with-new-silicon-valley-ai-hub-an/)**, BarackOllama is an agentic resume, GitHub portfolio, and cover letter customization suite designed to tailor candidate applications specifically to targeted job listings.
  - Powered by Google's Agent Development Kit (ADK) and Gemini models for deep resume extraction, code repository inspection, and alignment scoring.
  - Integrates Snowflake for candidate data management and CrewAI Enterprise flows to coordinate research and writing agent teams.
  - Provides both an interactive command-line interface ([BarackOllamaCLI](https://github.com/LlamaLoungeSnowflake/BarackOllamaCLI)) and a full-stack web application with FastAPI server backend and modern frontend.
- [AI-Q Research Assistant with Universal Deep Research (Research-as-a-Code)](https://github.com/Research-as-a-Code/Research_as_a_Code): Developed for the **[AWS & NVIDIA Agentic AI Unleashed Hackathon 2025](https://nvidia-aws.devpost.com/)**, this project synthesizes NVIDIA AI-Q Research Assistant with NVIDIA Universal Deep Research (UDR) into a two-level hierarchical agent architecture for complex, multi-domain research tasks.
  - Two-level agentic system: Level 1 orchestrator (LangGraph) plans research strategy, and Level 2 UDR engine dynamically generates and executes custom Python research pipelines when complex synthesis or comparative analysis is required.
  - Built with NVIDIA NIM microservices: Nemotron-Super-49B NIM for reasoning, reflection, and planning; Llama-3.3-70B NIM for report synthesis; NeMo Retriever NIM for dense vector search; and Docling for semantic document ingestion.
  - Production cloud infrastructure on AWS EKS utilizing Karpenter for dynamic GPU auto-scaling and GPU Operator provisioning.
  - Interactive React/Next.js frontend featuring CopilotKit for real-time streaming visualization of the agent's thought process, tool invocations, and synthesized citations.
- [¡alacard!: The Self-Improving Cookbook for AI Agents](https://github.com/wb-alacard/alacard): Created during **[WeaveHacks 2: Self-Improving Agents Hackathon](https://luma.com/weavehacks2?tk=e75daf)** hosted by Weights & Biases and Google Cloud, ¡alacard! is an open-source instruction layer and agentic factory that composes, executes, traces, and autonomously repairs Jupyter notebooks.
  - Users define high-level JSON "Recipes" selecting models (Gemini, Llama) and tools (Tavily search, Browserbase Stagehand web automation, Mastra integrations).
  - Multi-agent orchestration powered by Google ADK: a "Chef" agent writes full runnable notebooks, which execute safely inside isolated **Daytona** sandboxes.
  - End-to-end observability and State-Action-Reward (SAR) logging powered by **W&B Weave** tracing to capture every tool call, model prompt, and intermediate output.
  - Autonomous self-healing loop: when a code cell fails, an automated "Fixer" agent inspects the Weave execution trace, queries Vertex AI / W&B Inference for code patches, applies updates, and re-executes until passing.
  - Validated notebooks are cataloged in a Supabase-backed hub with CopilotKit AG-UI streaming frontends for community sharing and remixing.
  - [¡alacard! Enterprise](https://github.com/wb-alacard/alacard-enterprise) and [landing page](https://github.com/wb-alacard/Wbalacardlanding).
  - Finalist (top 6 projects) at the WeaveHacks 2: Self-Improving Agents Hackathon
- [Stigmergy ODEA (Open Distributed Edge Agents)](https://github.com/Open-Distributed-Edge-Agents/EdgeGenAI): Built for the **[Google Gemma 3n Impact Challenge on Kaggle](https://www.kaggle.com/competitions/google-gemma-3n-hackathon/overview)**, Stigmergy ODEA is a decentralized, resilient multi-agent swarm intelligence system designed for tactical edge operations and first responders in post-disaster environments (earthquakes, wildfires, floods).
  - Deployed on fleets of resource-constrained Android edge devices (drones) running on-device Google Gemma 3B multimodal models.
  - Uses **Android Nearby Connections** to establish a peer-to-peer, low-power mesh network operating completely independently of cellular or cloud infrastructure.
  - Implements dynamic Commander/Subordinate swarm hierarchies with automatic failover and leader re-election protocols if a commander unit is lost or compromised.
  - Built-in defenses against adversarial prompt injection and device impersonation attacks, combined with multimodal perception to reconcile visual camera feeds against expected mission targets.
  - Built upon and extended from the official Google AI Edge Gallery demo app.
  - [Open Distributed Edge Agents organization](https://github.com/Open-Distributed-Edge-Agents).
- [Public Health Application](https://github.com/bah-scsp-hackathon-2025/public-health-app): Developed during the **AI Expo SCSP Hackathon 2025** (hosted by Booz Allen Hamilton and the Special Competitive Studies Project), this project is a public health surveillance, monitoring, and analysis system.
  - Intelligent multi-agent analytical system (`PublicHealthDashboardAgent`) built with LangGraph to ingest live health indicators, analyze risk trends, and automatically generate executive health dashboards.
  - Multi-LLM support across OpenAI GPT-4 and Anthropic Claude for synthesizing complex epidemiology data and generating situational summaries.
  - FastMCP (Model Context Protocol) server providing standardized, real-time health data tools (alerts retrieval, trend forecasting, emergency summaries) via Server-Sent Events (SSE) transport.
  - Full-stack architecture backed by FastAPI with async API endpoints and VS Code development task workflows.
- [LlamaLink (LlamaLinked)](https://github.com/LlamaLinked): Built during the **[LlamaCon Hackathon hosted by Meta & Cerebral Valley](https://cerebralvalley.ai/e/llamacon-hackathon-2025)**, LlamaLink is a low-pressure, WhatsApp-first professional networking platform with an automated weekly matchmaking cadence.
  - Integrates LinkedIn profile scraping via Gumloop/Firecrawl, Supabase (PostgreSQL + pgvector) for profile storage, Meta Llama 4 Maverick (17B on Groq) for summarization, Mailgun for mutual warm introductions, and automated post-meeting active-listening coaching loops.
  - Contributed core AI engineering components:
    - [Synthetic Data Generator](https://github.com/LlamaLinked/synthetic-data-generator): Document parsing, synthetic QA and Chain-of-Thought (CoT) reasoning pair generation via `synthetic-data-kit`, quality filtering, and Alpaca/HuggingFace dataset preparation for fine-tuning.
    - [Prompt Optimization Tool](https://github.com/LlamaLinked/prompt-optimizer): Streamlit application utilizing `llama-prompt-ops` to iteratively evaluate and optimize prompts against input-output training pairs.
    - System prompt engineering, guardrail implementation, and product architecture specifications ([PRD repository](https://github.com/LlamaLinked/llamalinked-prd) and [Web frontend](https://github.com/LlamaLinked/llamalinked-web)).
- [Open Multi-Modal Personal Assistant (OpenMMPA)](https://github.com/Open-Multi-Modal-Personal-Assistant/OpenMMPA): Developed for the **[Gemini API Developer Competition](https://ai.google.dev/competition)**, OpenMMPA is an open-source, multi-modal personal AI companion application designed to turn smartphones and smartwatches into intelligent personal assistants without requiring dedicated AI pins.
  - Cross-platform mobile architecture built with Flutter (iOS & Android) and powered by Google Gemini 1.5 Flash and Pro models (via Vertex AI / Firebase Vertex AI).
  - On-device local Vector Database providing persistent conversation history and personalized on-device Retrieval Augmented Generation (RAG).
  - Hands-free multimodal interaction supporting camera visual exploration, native Android STT/TTS, and Google Chirp speech recognition for real-time translation and voice chat.
  - Tool and function calling capabilities including location-aware queries, real-time weather forecasting, Tavily web search, and currency exchange rates.
  - [OpenMMPA Demo Video](https://www.youtube.com/watch?v=kCtHH6XG5as) and [DeepWiki Architecture Documentation](https://deepwiki.com/Open-Multi-Modal-Personal-Assistant/OpenMMPA).
- [Eco Trivia Quiz Application (with chat agent on the side)](https://github.com/gdgfresno/EcoTriviaApplication): Eco Trivia is a web / mobile game about climate change. Apathy and information overload prevent people getting involved with climate action. I gathered Google Developer Student Club (GDSC) Fresno members Zheng Wei Ng and Ran Hao Wong to create a quiz game about sustainability. We were exploring how far we can go with low-code / no-code tools:
  - We used Agent Builder for the LLM and RAG back-end: [Eco Trivia Agent Builder agent with JSON structured response and examples](https://github.com/gdgfresno/EcoTriviaAgent)
  - We were exploring special features such as JSON responses from the agent
  - We used Flutter Flow for the front-end: [Flutter Flow source code export](https://github.com/gdgfresno/EcoTriviaApplication)
  - We also used Flare no-code animations
  - Our work reused experiences from the SDG (Sustainable Development Goals) agent, also [glue code to connect the front-end and the back-end](https://github.com/gdgfresno/EcoAgentFunction)
  - We also integrated a chat agent as a side feature, so the user can have free conversation besides the quiz game
  - [2nd place at the GenAI Gemini Hackathon issued by Issued by Google Developer Community (GDC)](https://discord.com/channels/1009525727504384150/1224736213290713210/1245806575650738268)
- [Eco Oracle Chat Agent](https://devpost.com/software/eco-oracle): A no-code / low-code agent specialized in Sustainable Development Goals via RAG (Retrieval Augmented Generation). It uses the Google Cloud Platforms Agent Builder offerings which are Generative AI successor to DialogFlow CX conversational agents, and it offers no code "playbooks" (or behavior scripts), managed RAG, function calls and powered by Google Gemini under the hood.
  - [Streamlit application](https://ecooraclechat.streamlit.app/)
  - [Streamlit app source code](https://github.com/CsabaConsulting/EcoOracleChat)
  - [Agent Builder source code export with RAG examples](https://github.com/MrCsabaToth/EcoOracleAgent/)
  - [Glue code to connect the Streamlit front-end to the Agent Builder back-end](https://github.com/gdgfresno/EcoAgentFunction)
  - [Winner of "Most Likely to Change the World" category at Google Cloud Next AI Hackathon](https://aihackathonatnext.devpost.com/)
- [LLM Knowledge agent with RAG Fusion](https://github.com/CsabaConsulting/Cohere): Using Cohere chat, document guided and web connector guided agents, Weaviate services and LangChain, I implemented a RAG Fusion solution with a Streamlit UI. I also experimented with Cohere's Command R large language model.
  - [4th (finalist top 5) at the Cohere Coral Hackathon](https://lablab.ai/event/cohere-coral-hackathon/thruthink/rag-fusion-with-cohere-and-weaviate)
- [QBRAG (QnA Boosted RAG) Knowledge LLM agent on Vectara platform](https://github.com/CsabaConsulting/Vectara): A company's knowledge bases often times don't answer the wide variety of questions a user could come up with. A Customer Support system ideally could answer specific (but wide variety) questions about the company's systems and knowledge (example: "How can I enter Cash Flow in ThruThink?"). But sometimes the user asks generic questions, such as "What is Cash Flow?" which could be sourced from the mind of a giant LLM model and / or the internet. My submission is essentially synthetic data enrichment of the knowledge base by reusing generated questions and answers. To help and boost the performance by leveraging Question and Answer generation techniques - normally used for fine tuning but in this case - for knowledge base augmentation / indexing enrichment. The generated questions could support specific user queries potentially better matching than a "non focused" indexed generic knowledge base.
  - As part of the effort I contributed to the https://github.com/nestordemeure/question_extractor open source project which offers semantic markdown knowledge base chunking.
  - Tech used: Vectara (embedding, vector database, ranking, etc.), AnyScale (LLM hosting, fine tuning), and React for front-end.
  - Winner of the Customer Support category of ["RAG: LLMs with your data Summary" hackathon](https://lablab.ai/event/rag-llms-with-your-data/thruthink/qna-boosted-rag-with-vectara)
- [GeMMAA (Generative Multi Modal Augmented Reality Art) application by AIWeavers for Multi Modal hackathon by Weaviate at AIx Innovation Summit](https://github.com/CsabaConsulting/ODSCWest). Team repository: https://github.com/AIWeavers/GeMMAA. An AR mobile application which can generate 3D art from a text prompt and also music from a text prompt with the option of minting an NFT from the artwork. We use 8thwall for the front-end, NFTPort for NFT minting, GCP cloud functions for back-end, Meshy for 3D model generation, Meta's music generator, and most importantly Weaviate's multi-model embedding to allow search and organization of the artwork. The team:
  - Avi Rao (https://www.linkedin.com/in/avi-nav-rao-39a567205/) front-end main role for the hackathon and AR/VR + blockchain, NFT, crypto, web3 specialist
  - Yvonne Fang (https://www.linkedin.com/in/yvonne-fang-679892153/) front-end main role for the hackathon and also AR/VR, Gen AI art and web3 specialist
  - Andrew Savala (https://www.linkedin.com/in/redswimmer/) back-end role for the hackathon, but also full stack engineer and AI/ML specialist
  - Quinton Mills (https://www.linkedin.com/in/quinton-mills/) front-end role for the hackathon, also UX design and many competencies
  - Myself: back-end, GCP functions, team organization
  - Winner of the Multi Modal hackathon by Weaviate at AIx Innovation Summit and ODSC West 2023 data science conference
- [Knowledge LLM agent with RAG utilizing low-code / no-code cnvrg LLMaaS platform](https://github.com/CsabaConsulting/IntelInnovate2023): At the time of the project (Intel Innovation Bridge hackathon @ Intel Innovation 2023) cnvrg's LLMaaS (LLM as a service) by Intel was in alpha stage. The LLMaaS service provided a no code environment to fine tune and customize agent solutions with ease. Due to the development stage of this novel product I could use two toy datasets to fine tune an LLM, and I applied RAG (Retrieval Augmented Generation) with the help of a PineCone vector database, using ChatGPT's embeddings API. I also got familiar with GRadio and similar front-ends. Due to confidentiality the materials I can share are limited.
  - Winner of the Intel Innovation Bridge hackathon's LLM category @ Intel Innovation 2023
- [Gen AI Rock Star Challenge: Song "Xeon Fury" of the band "Nerdcore Annihilation"](https://github.com/MrCsabaToth/GenAIRockStarChallenge2023). Participants were tasked with generating a poster or album cover for an imaginary rock band, along with generating the lyrics of an imaginary song for said band. We were provided with a Gaudi2 accelerated deep learning AWS EC2 instance equipped with a Runway 1.5 text-to-image stable diffusion model, and also a Vicuna 7-based LLM model. We increased the steps of the stable diffusion model from 10 to 50 to conclude with much better images. The EC2 box was inaccessible for a while, and in the meantime, we experimented with some other LLM models for lyrics, such as ChatGPT and PaLM, as well as the officially accessible Runway Gen 1. We used the LLM to get the band name (Nerdcore Annihilation) and the song name (Xeon Fury) as well. The stable diffusion model couldn't feature text on the image precisely, so we used Runway's web-accessible edit feature to add an old school Intel Inside logo and modify the center image of the front cover. The back cover was purely generated by the Gaudi2 instance (notice how the wafer is a pastry wafer and not a chip wafer). We adjusted the prompt many times. I used my geek knowledge to provide desired keywords for the lyrics: MMX, AVX, AVX2, AVX512, AMX, Xeon Phi, Gaudi 2, Optimum Habana, 288-core Xeon (freshly announced). We mixed the best parts of the various tries together to create a hilarious final set of lyrics.
  - Winner of Intel GenAI Rock Star Challenge @ Intel Innovation 2023
- [Multi Modal Generative AI Travel blog helper app](https://github.com/CsabaConsulting/NextGenAI): An app indexes pictures taken during travel trips or everyday experiences. With the power of multi modal embedding models and vector databases it is able to categorize them, describe them and help document the experiences. The back-end uses Chooch for image to text tasks and Google Cloud Platform for everything else such as asset management, search, summarization and RAG. The front-end is written in Kotlin and uses Compose UI by Kevin Moore GDE. The project management, iteration on ideation, user interviews, feasibility, presentation of our work was done by Yiru and Coco He.
- [CSU Fresno Recycling Trashcan locations - Outdoor Augmented Reality Map leveraging Geospatial API and Terrain Anchors to guide students to recycling trashcans](https://play.google.com/store/apps/details?id=dev.csaba.armap.recyclingtrashcans)
  - [AR mobile app source code repository](https://github.com/RecyclingTrashCans/recycling-trashcan-armap)
  - [360 photo + video VR companion website](https://recyclingtrashcans.github.io/) and [source code](https://github.com/RecyclingTrashCans/RecyclingTrashCans.github.io).
  - Winner of Honorable Mention category at the [Google Maps Platform Hackathon](https://googlemapsplatform.devpost.com/), [individual project website](https://devpost.com/software/recycling-trashcan-ar-map).
- [CSU Fresno Tree Walk - Outdoor Augmented Reality Map leveraging Geospatial API and Terrain Anchors to guide visitors along the Tree Walk](https://play.google.com/store/apps/details?id=dev.csaba.armap.treewalk), boost engagement gamification as well as advanced Generative AI method: segmentation for virtual watering
  - [AR mobile app source code repository](https://github.com/TreeWalks/tree-walk-guide)
  - [360 photo + video VR companion website](https://treewalks.github.io/) and [source code](https://github.com/TreeWalks/TreeWalks.github.io/).
- [AMP personal website - Google Registry Website Competition Winner](https://csaba.page)
  - [source code repository](https://gitlab.com/MrCsabaToth/mrcsabatoth.gitlab.io)
  - [Google Registry Website Competition Winner](https://www.registry.google/announcements/2019websitecompetitionwinners/)
- [Deal-O-Round - Flutter based reimplementation of a PlayN-based multi-platform (Android / iOS / web) game](https://play.google.com/store/apps/details?id=com.dealoround.android)
  - [source code repository](https://github.com/DealORound/Deal-O-Round)
  - [companion website with web demo](https://mrcsabatoth.github.io/DealORoundWebsite/)
  - 3rd place at 59 Days of Code 2014 hackathon

---

### More projects worth mentioning:
- [Track My Indoor Workout - Flutter app for recording exercises on smart fitness machines via Bluetooth LE connection; generating GPS data based on speed readings; Strava, MapMyFitness (Under Armor), SUUNTO, and Training Peaks integrations](https://play.google.com/store/apps/details?id=dev.csaba.track_my_indoor_exercise) ([repository](https://github.com/TrackMyIndoorWorkout/TrackMyIndoorWorkout) and [companion website](https://trackmyindoorworkout.github.io/))
- [ARPhysics - Physics simulations integrated into an Augmented Reality app to provide a unique fun experience, uses Sceneform SDK & ARCore](https://play.google.com/store/apps/details?id=dev.csaba.arphysics) ([repository](https://github.com/CsabaConsulting/ARPhysics))
- [DIY GPS Tracker application bundle to protect desired assets. Android applications with very unique "bring your own" Firestore back-end philosophy](https://github.com/DIYGPSTracker) ([repositories](https://github.com/DIYGPSTracker))
- [VFDWatchFace - Wear OS watch face with retro feeling and six complication slots, 3 color schemes](https://play.google.com/store/apps/details?id=dev.csaba.vfdwatchface) ([repository](https://github.com/CsabaConsulting/VFDWatchFace))
- [FlowerComplicationWatchFace - Wear OS watch face with seven complication slots](https://play.google.com/store/apps/details?id=dev.csaba.complicationflowerwatchface) ([repository](https://github.com/CsabaConsulting/FlowerComplicationWatchFace))
- [360 Virtual Reality website for the joint GDG Fresno + TFC's (The Fresno Center) trip to Googleplex Mountain View and Computer History Museumm](https://gdgfresno.github.io/googletrip2019/) ([repository](https://github.com/gdgfresno/GoogleTrip2019))
- [DevfestARMap - Android Augmented Reality application to help tech conference attendees to orientate between the 5 class rooms at Bitwise South Stadium venue, uses Sceneform SDK & ARCore](https://play.google.com/store/apps/details?id=com.valleydevfest.armap) ([repository](https://github.com/gdgfresno/DevfestARMap))
- [360 Virtual Reality website for joint GDG Fresno + EOC's (Economic Opportunities Commission Fresno) trip to Googleplex Mountain View and Computer History Museum](gdgfresno.github.io/googletrip2018/) [updated multiple times with bug fixes to Google Web VR](https://github.com/MrCsabaToth/magicvr/commits/gh-pages) ([repository](https://github.com/gdgfresno/GoogleTrip2018))
- [Detailed Google Chart examples](http://mrcsabatoth.github.io/GoogleChartsTalk/) ([repository](https://github.com/MrCsabaToth/GoogleChartsTalk))
- [Valley DevFest 2018 conference website based on DeLorean-v2 Angular web application project, enriched with multiple authentication provider handling, extra session feedback, localization capability](https://github.com/gdgfresno/valleydevfest2018)
- [Android companion app for Valley DevFest 2017 conference for the attendees to design and feature their Android avatar on the conference website, upgraded to AndroidX, ViewPager2, Firebase integration](https://play.google.com/store/apps/details?id=com.valleydevfest.androidify) ([repository](https://github.com/gdgfresno/androidify-yourself))
- [Valley DevFest 2017 conference website based on Hoverboard Polymer web application project, enriched with multiple authentication provider handling, extra session feedback, localization capability and a special page where conference attendees can design and feature their Android avatar (Polymer UI, also supported by an Android app)](https://github.com/ValleyDevFest2017/valleydevfest2017/commits/hoverboard-v2)
- [Valley DevFest 2016 conference website based on Hoverboard Polymer web application project, Firebase hosting and back-end, enriched with multiple authentication provider handling, session feedback, Spanish, Arabic, Hmong and Armenian translations](https://github.com/ValleyDevFest2016/valleydevfest/tree/develop)
- [California State University Fresno Earth Day 2016 Jekyll website with Disqus integration and photo carousel](https://bulldogearthday.github.io/) ([repository](https://github.com/bulldogearthday/bulldogearthday.github.com))
- [Progressive Web App for paperless booth visit checking, QR code reading and camera handling in a webapp](https://earthday.firebaseapp.com) ([repository](https://github.com/bulldogearthday/booths))
- [Secure Open Enterprise Master Patient Index: privacy preserving multi-party record linkage implementation, won Homer R. Warner Award at AMIA Annual Symposium](https://github.com/MrCsabaToth/SOEMPI)
- [A version of Fairplay software for 2-party SMC (Secure Multi-party Computation) which is really able to handle arbitrarily long integers](https://github.com/MrCsabaToth/FairplayBI)

---

### Blog Posts
<!-- BLOG-POST-LIST:START -->
- [LlamaCon 2025, Space Llama, and the Cerebral Valley Hackathon](https://csaba.page/blog/llamacon-2025-space-llama-and-cerebral-valley-hackathon.html)
- [Gemini API Developer Competition: Building OpenMMPA on Full Android Watches](https://csaba.page/blog/gemini-api-developer-competition-open-mmpa-on-full-android-watch.html)
- [Chasing the Next Transformer Killer - Part 2](https://csaba.page/blog/chasing-the-next-transformer-killer-rwkv-an-underrated-llm.html)
- [Chasing the Next Transformer Killer - Part 1](https://csaba.page/blog/chasing-the-next-transformer-killer-linear-transformer-reformer-performer.html)
- [No-Code Low-Code LLM Powered Quiz Game with FlutterFlow](https://csaba.page/blog/no-code-low-code-agent-builder-llm-rag-powred-quiz-game-flutterflow.html)
- [It Was DataFest Time Again](https://csaba.page/blog/it-was-datafest-time-again.html)
- [No-Code LLM Agent and RAG Solution at Google Cloud Next 2024](https://csaba.page/blog/google-cloud-next-2024-agent-builder-hackathon.html)
- [How I Could Have Won My First Kaggle Competition at Google Cloud Next 2024 in Las Vegas](https://csaba.page/blog/first-kaggle-competition-at-google-cloud-next-2024-las-vegas.html)
- [LLM Knowledge agent with RAG Fusion on Cohere platform with LangChain and Streamlit](https://csaba.page/blog/llm-knowledge-agent-with-rag-fusion-on-cohere-langchain-streamlit.html)
- [QBRAG &lpar;QnA Boosted RAG&rpar; with Vectara](https://csaba.page/blog/qbrag-qna-boosted-rag-with-vectara-hackathon.html)
- [Multi-Modal hackathon by Weaviate at AIx Innovation Summit and ODSC West 2023 Data Science Conference](https://csaba.page/blog/odsc-west-data-science-conference-aix-innovation-summit-multi-modal-hackathon.html)
- [LLM Red Teaming at the Samsung Developer Conference 23](https://csaba.page/blog/llm-red-teaming-at-the-samsung-developer-conference-23.html)
- [Personalization is what I missed at the Samsung NextGen AI hackathon](https://csaba.page/blog/personalization-is-what-i-missed-at-samsung-next-gen-ai-multi-modal-hackathon.html)
- [Intel Innovation 2023 Conference Generative AI Hackathons and Challenges](https://csaba.page/blog/intel-innovation-2023-conference-generative-ai-hackathons-and-challenges.html)
- [The Downfall of Twitter from Behind the Scenes](https://csaba.page/blog/the-downfall-of-twitter-from-behind-the-scenes.html)
- [My First Two Flutter Plugins and Track My Indoor Workout News](https://csaba.page/blog/my-first-two-flutter-plugins-and-track-my-indoor-workout-news.html)
- [Google Maps Hackathon Prize Win and a New AR Tree Walk Guide](https://csaba.page/blog/google-maps-hackathon-prize-win-and-a-new-ar-tree-walk-guide.html)
- [Policy aligning with the legacy of Aaron Swartz](https://csaba.page/blog/policy-aligning-with-the-legacy-of-aaron-swartz.html)
- [Using Geospatial API for Augmented Reality Maps](https://csaba.page/blog/geospatial-api-with-terrain-anchors-for-augmented-reality-maps.html)
- [Meta Store Opening: VR Demos, Smart Glasses, and Campus Fitness Journey](https://csaba.page/blog/meta-store-opening-and-quest-demo.html)
- [The Right to Repair and Our Future](https://csaba.page/blog/the-right-to-repair-and-our-future.html)
- [Going Open Source under GPLv3 but not being Google Dev Library worthy](https://csaba.page/blog/gplv3-open-source-but-not-google-dev-librayr-worthy.html)
- [Installing Flutter SDK via Snap or Brew](https://csaba.page/blog/flutter-sdk-install-via-snap-or-brew.html)
- [SUUNTO, Under Armour Integrations, and Other Enhancements](https://csaba.page/blog/suunto-under-armour-integrations.html)
- [Flutter V1 vs V2 Embedding, Deprecated Android APIs, and Colliding Kotlin Versions](https://csaba.page/blog/flutter-v1-vs-v2-embedding-deprecated-android-apis-colliding-kotlin-versions.html)
- [My First Merged Flutter Plugins Pull Request](https://csaba.page/blog/my-first-merged-flutter-plugins-pull-request.html)
- [Lessons Learned About Flutter Dart Null Safety](https://csaba.page/blog/flutter-dart-sound-null-safety.html)
- [A COVID Story](https://csaba.page/blog/a-covid-story.html)
- [Proof of Capacity Story](https://csaba.page/blog/proof-of-capacity-story.html)
- [Crypto Currency Sustainability and Consensus Algorithms](https://csaba.page/blog/crypto-currency-sustainability.html)
<!-- BLOG-POST-LIST:END -->

---

<p align="left">
  <img alt="Github Stats" src="https://github-stats-extended.vercel.app/api?username=MrCsabaToth&show_icons=true" />
  <br>
  <img alt="Github Streak" src="https://github-readme-streak-stats.herokuapp.com?user=MrCsabaToth&border_radius=5&mode=weekly" />
  <br>
  <img alt="Top Language" src="https://github-stats-extended.vercel.app/api/top-langs/?username=MrCsabaToth&hide=html,css&layout=compact" />
</p>

<!--
[website]: https://csaba.page
[twitter]: https://twitter.com/tocsa2
[linkedin]: https://linkedin.com/in/csabatothdev/
[instagram]: https://instagram.com/MrCsabaToth
-->
