# Sourav Rajvi

I build backends end-to-end — distributed systems, LLM gateways, middleware automation, and the infrastructure that keeps them reliable. Backend developer focused on microservices, cloud architecture, and open-source work in the AI tooling ecosystem.

**Maintainer @ [InfiniFlow](https://github.com/infiniflow)** — dedicated maintainer of the [MinerU](https://github.com/infiniflow/ragflow) PDF/layout parser in [RAGFlow](https://github.com/infiniflow/ragflow) (90K+ GitHub stars). Own MinerU-related issues and PRs; contributed MonkeyOCR as a dedicated PDF backend ([#19044](https://github.com/infiniflow/ragflow/pull/19044)).

## Selected work

**Products & systems**

- [**OPENINFER**](https://github.com/Souravrajvi0/OPENINFER) — self-hosted LLM gateway with routing, guardrails, retrieval, budgets, tracing, evaluations, and an admin console. Includes `oi`, a hardware-aware CLI for finding and running local open-source models. Live at [openinference.tech](https://openinference.tech).
- [**netsuite-middleware**](https://github.com/Souravrajvi0/netsuite-middleware) — AWS middleware automation. Microservices with gRPC, event-driven workflows, PostgreSQL, Redis, and RabbitMQ for NetSuite integration at scale.
- [**netssuite**](https://github.com/Souravrajvi0/netssuite) — production-ready AI knowledge-base assistant for NetSuite. Multi-client deployment with dynamic URL generation and an embedded chatbot layer.
- [**NETFLIX_GPT**](https://github.com/Souravrajvi0/NETFLIX_GPT) — AI-driven Netflix discovery with natural-language search and personalized recommendations.

**Backend & APIs**

- [**API_Gateway_Flights**](https://github.com/Souravrajvi0/API_Gateway_Flights) — flight booking API gateway with service routing and aggregation.
- [**axio-backend**](https://github.com/Souravrajvi0/axio-backend) — Node.js backend services for product APIs.
- [**dsatrackerllmbackend**](https://github.com/Souravrajvi0/dsatrackerllmbackend) — LLM-backed DSA progress tracking backend.
- [**telejob**](https://github.com/Souravrajvi0/telejob) — job-hunting bot that filters LinkedIn and Telegram posts with regex + Gemini, then tracks applications in Telegram.

**Learning & tooling**

- [**LEETCODE-DSA**](https://github.com/Souravrajvi0/LEETCODE-DSA) — curated LeetCode solutions in C++.
- [**AlgorithmPractising**](https://github.com/Souravrajvi0/AlgorithmPractising) — algorithm practice workspace in TypeScript.
- [**DEV-NOTES**](https://github.com/Souravrajvi0/DEV-NOTES) — Obsidian-synced notes on Go, distributed systems, and backend patterns.
- [**llm-bot**](https://github.com/Souravrajvi0/llm-bot) — JavaScript LLM bot experiments.

## Open source

**50+ merged** upstream PRs plus active work across LLM platforms, local inference, agents, and ML infrastructure. [All pull requests](https://github.com/search?q=author%3ASouravrajvi0+is%3Apr+is%3Amerged+-user%3ASouravrajvi0&type=pullrequests).

**LLM platforms**

- [**infiniflow/ragflow**](https://github.com/infiniflow/ragflow) — **maintainer, MinerU parser** (90K+ ★). 2 merged: dataset navigation tree load failures ([#17668](https://github.com/infiniflow/ragflow/pull/17668)), empty canvas autosave guard ([#18783](https://github.com/infiniflow/ragflow/pull/18783)). Open: MonkeyOCR PDF backend ([#19044](https://github.com/infiniflow/ragflow/pull/19044)), reverse-proxy subpath deployment ([#18890](https://github.com/infiniflow/ragflow/pull/18890)), wiki retrieval fields ([#18787](https://github.com/infiniflow/ragflow/pull/18787)), tenant model-type migration ([#18781](https://github.com/infiniflow/ragflow/pull/18781)).
- [**langgenius/dify**](https://github.com/langgenius/dify) — 5 merged: legacy `model_type` cleanup ([#39708](https://github.com/langgenius/dify/pull/39708)), slash variable picker guard ([#39761](https://github.com/langgenius/dify/pull/39761)), cached recommended-app template fetches ([#40176](https://github.com/langgenius/dify/pull/40176)), UTF-8 binding-file preview ([#41761](https://github.com/langgenius/dify/pull/41761)), boolean server defaults ([#41762](https://github.com/langgenius/dify/pull/41762)). Open: unclosed think tags around agent tool calls ([#41764](https://github.com/langgenius/dify/pull/41764)), WebApp file input defaults ([#41763](https://github.com/langgenius/dify/pull/41763)), configurable indexing workers ([#41302](https://github.com/langgenius/dify/pull/41302)).
- [**Mintplex-Labs/anything-llm**](https://github.com/Mintplex-Labs/anything-llm) — merged: You.com web search for agents ([#6058](https://github.com/Mintplex-Labs/anything-llm/pull/6058)). Open: generic OpenAI sampling passthrough ([#6048](https://github.com/Mintplex-Labs/anything-llm/pull/6048)), saved endpoint connections ([#6065](https://github.com/Mintplex-Labs/anything-llm/pull/6065)).
- [**BerriAI/litellm**](https://github.com/BerriAI/litellm) — 2 merged: form-encoded video edit/extension bodies ([#36513](https://github.com/BerriAI/litellm/pull/36513)), managed batch output files ([#34092](https://github.com/BerriAI/litellm/pull/34092)). Open: internal metadata leak ([#36412](https://github.com/BerriAI/litellm/pull/36412)), Prometheus unmatched-path labels ([#36410](https://github.com/BerriAI/litellm/pull/36410)), `system_prompt` logging ([#36406](https://github.com/BerriAI/litellm/pull/36406)).
- [**langfuse/langfuse**](https://github.com/langfuse/langfuse) — open: monitor alert filter evaluation ([#16719](https://github.com/langfuse/langfuse/pull/16719)), comment-mention email persistence ([#16580](https://github.com/langfuse/langfuse/pull/16580)), login rate limits ([#16577](https://github.com/langfuse/langfuse/pull/16577)), observation IO in legacy trace downloads ([#15451](https://github.com/langfuse/langfuse/pull/15451)), admin API to list orgs by email ([#15453](https://github.com/langfuse/langfuse/pull/15453)).

**Agents & orchestration**

- [**mastra-ai/mastra**](https://github.com/mastra-ai/mastra) — 2 merged: sequential allow-tool results after auto-approved resume ([#19940](https://github.com/mastra-ai/mastra/pull/19940)), Zod v4 `jsonSchema` adapter ([#21187](https://github.com/mastra-ai/mastra/pull/21187)). Open: publish stored skill drafts ([#23032](https://github.com/mastra-ai/mastra/pull/23032)), deployment thinking defaults ([#23031](https://github.com/mastra-ai/mastra/pull/23031)), workspace resolution from project root ([#22861](https://github.com/mastra-ai/mastra/pull/22861)).

**Local training & inference**

- [**unslothai/unsloth**](https://github.com/unslothai/unsloth) — **34 merged** across Studio, installer, and inference. Recent merges include llama.cpp update rate-limit handling ([#9980](https://github.com/unslothai/unsloth/pull/9980)), empty Downloads list entry ([#9849](https://github.com/unslothai/unsloth/pull/9849)), Xet stall HTTP resume ([#10045](https://github.com/unslothai/unsloth/pull/10045)), custom TTS endpoint repair ([#9905](https://github.com/unslothai/unsloth/pull/9905)), and local agent provider routing ([#9871](https://github.com/unslothai/unsloth/pull/9871)). Open: API tokens on plain HTTP ([#9906](https://github.com/unslothai/unsloth/pull/9906)), empty `web_search` recovery ([#9716](https://github.com/unslothai/unsloth/pull/9716)), FP8/FP4 compressor consent ([#9554](https://github.com/unslothai/unsloth/pull/9554)). [All Unsloth PRs](https://github.com/unslothai/unsloth/pulls?q=is%3Apr+author%3ASouravrajvi0).
- [**unslothai/unsloth-zoo**](https://github.com/unslothai/unsloth-zoo) — open: forward `enable_thinking=False` in the Qwen3.8 vision collator ([#1072](https://github.com/unslothai/unsloth-zoo/pull/1072)).
- [**langgenius/dify-official-plugins**](https://github.com/langgenius/dify-official-plugins) — 3 merged: parse plugin files when Dify already has an event loop ([#3756](https://github.com/langgenius/dify-official-plugins/pull/3756)), Cohere embed-v4.0 models ([#3769](https://github.com/langgenius/dify-official-plugins/pull/3769)), Tongyi temperature floor ([#3767](https://github.com/langgenius/dify-official-plugins/pull/3767)). Open: qwen3.8-flash model support ([#3822](https://github.com/langgenius/dify-official-plugins/pull/3822)), workspace-specific DashScope API base ([#3789](https://github.com/langgenius/dify-official-plugins/pull/3789)), Anthropic workspace identity header ([#3788](https://github.com/langgenius/dify-official-plugins/pull/3788)).

**ML pipelines**

- [**kubeflow/pipelines**](https://github.com/kubeflow/pipelines) — open: in-cluster KFP client DNS ([#13820](https://github.com/kubeflow/pipelines/pull/13820)), parameterized container images ([#13821](https://github.com/kubeflow/pipelines/pull/13821)), cyclic dependency detection ([#13823](https://github.com/kubeflow/pipelines/pull/13823)), pipeline I/O validation ([#13824](https://github.com/kubeflow/pipelines/pull/13824)), default StorageClass for CreatePVC ([#13834](https://github.com/kubeflow/pipelines/pull/13834)).

## Stack

Node.js · TypeScript · Python · Go · Java · Spring Boot · gRPC · PostgreSQL · Redis · RabbitMQ · MongoDB · AWS · Docker · Kubernetes · React · Next.js · Fastify · Dify · Langfuse · LiteLLM · RAGFlow · MinerU · Unsloth

## Contact

- Portfolio — [souravportfoliov1.netlify.app](https://souravportfoliov1.netlify.app/)
- LinkedIn — [linkedin.com/in/souravrajvi](https://linkedin.com/in/souravrajvi)
- Email — [souravrajvi@gmail.com](mailto:souravrajvi@gmail.com)
- GitHub — [github.com/Souravrajvi0](https://github.com/Souravrajvi0)
