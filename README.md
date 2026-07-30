# Sourav Rajvi

I build backends end-to-end — distributed systems, LLM gateways, middleware automation, and the infrastructure that keeps them reliable. Backend developer focused on microservices, cloud architecture, and open-source contributions to the AI tooling ecosystem.

## Recent

**Pinned projects**

- [**OPENINFER**](https://github.com/Souravrajvi0/OPENINFER) — self-hosted LLM gateway with routing, guardrails, retrieval, budgets, tracing, evaluations, and an admin console. Includes `oi`, a hardware-aware CLI for finding and running local open-source models.
- [**netsuite-middleware**](https://github.com/Souravrajvi0/netsuite-middleware) — AWS middleware automation system. Microservices architecture with gRPC, event-driven workflows, PostgreSQL, Redis, and RabbitMQ for NetSuite integration at scale.
- [**netssuite**](https://github.com/Souravrajvi0/netssuite) — production-ready AI knowledge-base assistant for NetSuite. Multi-client deployment with dynamic URL generation and an embedded chatbot layer.
- [**lsm-database-engine**](https://github.com/Souravrajvi0/lsm-database-engine) — educational LSM-tree key-value storage engine. Binary SSTables, multi-threaded compaction, Micrometer telemetry, and a React ops UI on a Java 18+ Spring Boot core.
- [**NETFLIX_GPT**](https://github.com/Souravrajvi0/NETFLIX_GPT) — AI-driven Netflix discovery app with natural-language search and personalized recommendations.

**Backend & APIs**

- [**API_Gateway_Flights**](https://github.com/Souravrajvi0/API_Gateway_Flights) — flight booking API gateway with service routing and aggregation.
- [**farefinder-india**](https://github.com/Souravrajvi0/farefinder-india) — India fare comparison and route search built with TypeScript.
- [**axio-backend**](https://github.com/Souravrajvi0/axio-backend) — Node.js backend services for product APIs.
- [**dsatrackerllmbackend**](https://github.com/Souravrajvi0/dsatrackerllmbackend) — LLM-backed DSA progress tracking backend.

**Learning & tooling**

- [**LEETCODE-DSA**](https://github.com/Souravrajvi0/LEETCODE-DSA) — curated LeetCode problem solutions in C++.
- [**AlgorithmPractising**](https://github.com/Souravrajvi0/AlgorithmPractising) — algorithm practice workspace in TypeScript.
- [**DEV-NOTES**](https://github.com/Souravrajvi0/DEV-NOTES) — Obsidian-synced engineering notes on Go, distributed systems, and backend patterns.

## Open source contributions

Merged PRs across upstream projects, plus active contributions in review.

**LLM platforms**

- [**langgenius/dify**](https://github.com/langgenius/dify) — merged: [#39708](https://github.com/langgenius/dify/pull/39708) deletes custom models stored with legacy `model_type` values; in review: malformed metadata-filter SQL in Relyt and AnalyticDB ([#39707](https://github.com/langgenius/dify/pull/39707)), MCP `tools/list` file-list variables ([#39760](https://github.com/langgenius/dify/pull/39760)), slash variable picker guard ([#39761](https://github.com/langgenius/dify/pull/39761)), MCP OAuth callback when opener is missing ([#39763](https://github.com/langgenius/dify/pull/39763)), abort workflow stream on human-input pause ([#39775](https://github.com/langgenius/dify/pull/39775)).
- [**Mintplex-Labs/anything-llm**](https://github.com/Mintplex-Labs/anything-llm) — merged: [#6058](https://github.com/Mintplex-Labs/anything-llm/pull/6058) adds You.com as a web search provider for agents; in review: generic OpenAI passthrough sampling and extra request params ([#6048](https://github.com/Mintplex-Labs/anything-llm/pull/6048)), saved endpoint connections dropdown ([#6065](https://github.com/Mintplex-Labs/anything-llm/pull/6065)).
- [**BerriAI/litellm**](https://github.com/BerriAI/litellm) — in review: persist `budget_duration` on `/customer/update` ([#33951](https://github.com/BerriAI/litellm/pull/33951)), guardrail 4xx classification ([#33985](https://github.com/BerriAI/litellm/pull/33985)), OpenAI connection-error mapping ([#33995](https://github.com/BerriAI/litellm/pull/33995)), model JSON key deletion ([#34071](https://github.com/BerriAI/litellm/pull/34071)), batch all-error handling ([#34077](https://github.com/BerriAI/litellm/pull/34077)), v2 user rate limits ([#34085](https://github.com/BerriAI/litellm/pull/34085)), managed batch output files ([#34092](https://github.com/BerriAI/litellm/pull/34092)).
- [**langfuse/langfuse**](https://github.com/langfuse/langfuse) — in review: observation IO in legacy trace JSON download ([#15451](https://github.com/langfuse/langfuse/pull/15451)), admin API to list user organizations by email ([#15453](https://github.com/langfuse/langfuse/pull/15453)).

**Agents & orchestration**

- [**mastra-ai/mastra**](https://github.com/mastra-ai/mastra) — in review: keep sequential allow tool results after auto-approved resume ([#19940](https://github.com/mastra-ai/mastra/pull/19940)), preserve OM continuation hints after buffered activation ([#19953](https://github.com/mastra-ai/mastra/pull/19953)).

**Unsloth (local model training & studio)**

- [**unslothai/unsloth**](https://github.com/unslothai/unsloth) — merged: run settings on initial load ([#7351](https://github.com/unslothai/unsloth/pull/7351)), presets with load settings ([#7352](https://github.com/unslothai/unsloth/pull/7352)), Colab iframe embed ([#7349](https://github.com/unslothai/unsloth/pull/7349)), KV cache dtype UI ([#7348](https://github.com/unslothai/unsloth/pull/7348)), false MTP/vision capability reports ([#7332](https://github.com/unslothai/unsloth/pull/7332)), connection model persistence ([#7298](https://github.com/unslothai/unsloth/pull/7298)), touch-device chat sidebar ([#7297](https://github.com/unslothai/unsloth/pull/7297)), Vulkan diffusion `gpu_ids` guard ([#7415](https://github.com/unslothai/unsloth/pull/7415)), opt-in Vulkan llama.cpp backend ([#7373](https://github.com/unslothai/unsloth/pull/7373)), tokenizer Hub probe skip with `local_files_only` ([#7482](https://github.com/unslothai/unsloth/pull/7482)), Strix gfx routing on ROCm 7.14 ([#7300](https://github.com/unslothai/unsloth/pull/7300)), Strix inference when ROCm runtime is absent ([#7305](https://github.com/unslothai/unsloth/pull/7305)), distro-aware sudo apt prompt ([#7324](https://github.com/unslothai/unsloth/pull/7324)), Windows sandbox bare-git PATH ([#7323](https://github.com/unslothai/unsloth/pull/7323)), opt-in source-build GPU smoke validation ([#7322](https://github.com/unslothai/unsloth/pull/7322)), torchcodec pin for torch 2.10 ([#7299](https://github.com/unslothai/unsloth/pull/7299)).
- [**unslothai/unsloth**](https://github.com/unslothai/unsloth) — in review: local tool calling for OAI-compat remote models ([#7330](https://github.com/unslothai/unsloth/pull/7330)), literal `</think>` in thinking blocks ([#7334](https://github.com/unslothai/unsloth/pull/7334)), restore cached models after dangling HF ref ([#7375](https://github.com/unslothai/unsloth/pull/7375)), refresh token count after model load ([#7453](https://github.com/unslothai/unsloth/pull/7453)), Remembered context and KV dtype on API auto-load ([#7531](https://github.com/unslothai/unsloth/pull/7531)), `--reasoning on|off` instead of deprecated kwargs ([#7532](https://github.com/unslothai/unsloth/pull/7532)), forward `--flash-attn` / llama-extra-arg on bare studio ([#7533](https://github.com/unslothai/unsloth/pull/7533)).

**ML pipelines & infrastructure**

- [**kubeflow/pipelines**](https://github.com/kubeflow/pipelines) — in review: short in-cluster service DNS for KFP client ([#13820](https://github.com/kubeflow/pipelines/pull/13820)), parameterized image in container components ([#13821](https://github.com/kubeflow/pipelines/pull/13821)), cyclic dependency detection in topological sort ([#13823](https://github.com/kubeflow/pipelines/pull/13823)), pipeline input returned as pipeline output validation ([#13824](https://github.com/kubeflow/pipelines/pull/13824)), cluster default StorageClass for CreatePVC ([#13834](https://github.com/kubeflow/pipelines/pull/13834)).

**SaaS & productivity**

- [**twentyhq/twenty**](https://github.com/twentyhq/twenty) — in review: malformed RLS predicates and pagination errors in export ([#23219](https://github.com/twentyhq/twenty/pull/23219)), record-table widget filters against target object ([#23220](https://github.com/twentyhq/twenty/pull/23220)).

## Stack

Node.js · TypeScript · Python · Go · Java · Spring Boot · gRPC · PostgreSQL · Redis · RabbitMQ · MongoDB · AWS · GCP · Docker · Kubernetes · React · Next.js · Vue · LLM gateways · LiteLLM · Fastify · Dify · Langfuse

## Contact

- Portfolio — [souravportfoliov1.netlify.app](https://souravportfoliov1.netlify.app/)
- LinkedIn — [linkedin.com/in/souravrajvi](https://linkedin.com/in/souravrajvi)
- Email — [souravrajvi@gmail.com](mailto:souravrajvi@gmail.com)
- GitHub — [github.com/Souravrajvi0](https://github.com/Souravrajvi0)
