# Sourav Rajvi

I build backends end-to-end — distributed systems, LLM gateways, middleware automation, and the infrastructure that keeps them reliable. Backend developer focused on microservices, cloud architecture, and open-source work in the AI tooling ecosystem.

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

Merged PRs plus active work across LLM platforms, local inference, agents, and ML infrastructure. [All pull requests](https://github.com/search?q=author%3ASouravrajvi0+is%3Apr&type=pullrequests).

**LLM platforms**

- [**langgenius/dify**](https://github.com/langgenius/dify) — 3 merged: legacy `model_type` cleanup ([#39708](https://github.com/langgenius/dify/pull/39708)), slash variable picker guard ([#39761](https://github.com/langgenius/dify/pull/39761)), cached recommended-app template fetches ([#40176](https://github.com/langgenius/dify/pull/40176)). Open: provider `model_type` mapping ([#41303](https://github.com/langgenius/dify/pull/41303)), in-run tool file grants ([#41300](https://github.com/langgenius/dify/pull/41300)), SSRF proxy timeouts ([#41049](https://github.com/langgenius/dify/pull/41049)).
- [**Mintplex-Labs/anything-llm**](https://github.com/Mintplex-Labs/anything-llm) — merged: You.com web search for agents ([#6058](https://github.com/Mintplex-Labs/anything-llm/pull/6058)). Open: generic OpenAI sampling passthrough ([#6048](https://github.com/Mintplex-Labs/anything-llm/pull/6048)), saved endpoint connections ([#6065](https://github.com/Mintplex-Labs/anything-llm/pull/6065)).
- [**BerriAI/litellm**](https://github.com/BerriAI/litellm) — 2 merged: form-encoded video edit/extension bodies ([#36513](https://github.com/BerriAI/litellm/pull/36513)), managed batch output files ([#34092](https://github.com/BerriAI/litellm/pull/34092)). Open: internal metadata leak ([#36412](https://github.com/BerriAI/litellm/pull/36412)), Prometheus unmatched-path labels ([#36410](https://github.com/BerriAI/litellm/pull/36410)), `system_prompt` logging ([#36406](https://github.com/BerriAI/litellm/pull/36406)).
- [**langfuse/langfuse**](https://github.com/langfuse/langfuse) — open: comment-mention email persistence ([#16580](https://github.com/langfuse/langfuse/pull/16580)), login rate limits ([#16577](https://github.com/langfuse/langfuse/pull/16577)), observation IO in legacy trace downloads ([#15451](https://github.com/langfuse/langfuse/pull/15451)), admin API to list orgs by email ([#15453](https://github.com/langfuse/langfuse/pull/15453)).
- [**infiniflow/ragflow**](https://github.com/infiniflow/ragflow) — merged: dataset navigation tree load failures ([#17668](https://github.com/infiniflow/ragflow/pull/17668)). Open: wiki retrieval fields ([#18787](https://github.com/infiniflow/ragflow/pull/18787)), empty canvas autosave ([#18783](https://github.com/infiniflow/ragflow/pull/18783)), tenant model-type migration ([#18781](https://github.com/infiniflow/ragflow/pull/18781)).

**Agents & orchestration**

- [**mastra-ai/mastra**](https://github.com/mastra-ai/mastra) — 2 merged: sequential allow-tool results after auto-approved resume ([#19940](https://github.com/mastra-ai/mastra/pull/19940)), Zod v4 `jsonSchema` adapter ([#21187](https://github.com/mastra-ai/mastra/pull/21187)). Open: OM continuation hints ([#19953](https://github.com/mastra-ai/mastra/pull/19953)).

**Local training & inference**

- [**unslothai/unsloth**](https://github.com/unslothai/unsloth) — **25 merged** across Studio, installer, and inference. Recent merges include GGUF embedding auto-enable ([#9149](https://github.com/unslothai/unsloth/pull/9149)), 404s for mistyped GGUF ids ([#8389](https://github.com/unslothai/unsloth/pull/8389)), resume after stop-and-save ([#8217](https://github.com/unslothai/unsloth/pull/8217)), Vulkan llama.cpp backend ([#7373](https://github.com/unslothai/unsloth/pull/7373)), and ROCm/Strix gfx routing ([#7300](https://github.com/unslothai/unsloth/pull/7300)). Open: GGUF auto-compaction settings ([#9774](https://github.com/unslothai/unsloth/pull/9774)), Ollama thinking / `reasoning_effort` ([#9770](https://github.com/unslothai/unsloth/pull/9770)), empty `web_search` recovery ([#9716](https://github.com/unslothai/unsloth/pull/9716)). [All Unsloth PRs](https://github.com/unslothai/unsloth/pulls?q=is%3Apr+author%3ASouravrajvi0).
- [**unslothai/unsloth-zoo**](https://github.com/unslothai/unsloth-zoo) — open: forward `enable_thinking=False` in the Qwen3.8 vision collator ([#1072](https://github.com/unslothai/unsloth-zoo/pull/1072)).
- [**langgenius/dify-official-plugins**](https://github.com/langgenius/dify-official-plugins) — open: parse plugin files when Dify already has an event loop ([#3756](https://github.com/langgenius/dify-official-plugins/pull/3756)).

**ML pipelines**

- [**kubeflow/pipelines**](https://github.com/kubeflow/pipelines) — open: in-cluster KFP client DNS ([#13820](https://github.com/kubeflow/pipelines/pull/13820)), parameterized container images ([#13821](https://github.com/kubeflow/pipelines/pull/13821)), cyclic dependency detection ([#13823](https://github.com/kubeflow/pipelines/pull/13823)), pipeline I/O validation ([#13824](https://github.com/kubeflow/pipelines/pull/13824)), default StorageClass for CreatePVC ([#13834](https://github.com/kubeflow/pipelines/pull/13834)).

## Stack

Node.js · TypeScript · Python · Go · Java · Spring Boot · gRPC · PostgreSQL · Redis · RabbitMQ · MongoDB · AWS · Docker · Kubernetes · React · Next.js · Fastify · Dify · Langfuse · LiteLLM · RAGFlow · Unsloth

## Contact

- Portfolio — [souravportfoliov1.netlify.app](https://souravportfoliov1.netlify.app/)
- LinkedIn — [linkedin.com/in/souravrajvi](https://linkedin.com/in/souravrajvi)
- Email — [souravrajvi@gmail.com](mailto:souravrajvi@gmail.com)
- GitHub — [github.com/Souravrajvi0](https://github.com/Souravrajvi0)
