# Sourav Rajvi

![Profile views](https://komarev.com/ghpvc/?username=Souravrajvi0&label=Profile%20views&color=0e75b6&style=flat-square)

I build backends end-to-end — distributed systems, LLM gateways, middleware automation, and the infrastructure that keeps them reliable. Backend developer focused on microservices, cloud architecture, and open-source work in the AI tooling ecosystem.

**Maintainer @ [InfiniFlow](https://github.com/infiniflow)** — dedicated maintainer of the [MinerU](https://github.com/infiniflow/ragflow) PDF/layout parser in [RAGFlow](https://github.com/infiniflow/ragflow) (90K+ GitHub stars). Own MinerU-related issues and PRs; contributed MonkeyOCR as a dedicated PDF backend ([#19044](https://github.com/infiniflow/ragflow/pull/19044)).

## Personal project

- [**openinference**](https://github.com/Souravrajvi0/openinference) — one repo, two products: **SentinelAI**, a self-hosted AI gateway (multi-provider routing, guardrails, hybrid RAG, agents, traces, evals, React admin) and **[`@openinference/cli`](https://github.com/Souravrajvi0/openinference/tree/main/packages/cli)** (`oi`), a publishable CLI for hardware-aware local models and a project-local agent harness. Stack: Fastify · PostgreSQL/pgvector · Redis/BullMQ · Docker Compose. Live — [demo](http://64.227.178.3) · [API docs](http://64.227.178.3/api-docs) · [CLI guide](https://openinference.tech/cli).

## Open source

**50+ merged** upstream PRs plus active work across LLM platforms, local inference, agents, and ML infrastructure. [All pull requests](https://github.com/search?q=author%3ASouravrajvi0+is%3Apr+is%3Amerged+-user%3ASouravrajvi0&type=pullrequests).

**LLM platforms**

- [**infiniflow/ragflow**](https://github.com/infiniflow/ragflow) — **maintainer, MinerU parser** (90K+ ★). 6 merged: dataset navigation tree ([#17668](https://github.com/infiniflow/ragflow/pull/17668)), canvas autosave guard ([#18783](https://github.com/infiniflow/ragflow/pull/18783)), DOCX preview loop ([#19475](https://github.com/infiniflow/ragflow/pull/19475)), spreadsheet/JSON parser hardening ([#19237](https://github.com/infiniflow/ragflow/pull/19237)), wiki retrieval fields ([#18787](https://github.com/infiniflow/ragflow/pull/18787)), chunk `image_update_mode` ([#18889](https://github.com/infiniflow/ragflow/pull/18889)). Open: MonkeyOCR PDF backend ([#19044](https://github.com/infiniflow/ragflow/pull/19044)), MinerU `server_url` in Go PDF parser ([#19445](https://github.com/infiniflow/ragflow/pull/19445)), text-only pre-index wire contract ([#19478](https://github.com/infiniflow/ragflow/pull/19478)).
- [**langgenius/dify**](https://github.com/langgenius/dify) — 8 merged: legacy `model_type` cleanup ([#39708](https://github.com/langgenius/dify/pull/39708)), slash variable picker ([#39761](https://github.com/langgenius/dify/pull/39761)), cached recommended-app templates ([#40176](https://github.com/langgenius/dify/pull/40176)), UTF-8 binding-file preview ([#41761](https://github.com/langgenius/dify/pull/41761)), boolean server defaults ([#41762](https://github.com/langgenius/dify/pull/41762)), agent think-tag closure ([#41764](https://github.com/langgenius/dify/pull/41764)), CSV cell text on import ([#41922](https://github.com/langgenius/dify/pull/41922)), model delete query params ([#42162](https://github.com/langgenius/dify/pull/42162)). Open: provider credential DELETE params ([#42244](https://github.com/langgenius/dify/pull/42244)), web reader HEAD→GET fallback ([#42242](https://github.com/langgenius/dify/pull/42242)), dataset api-keys route ([#42210](https://github.com/langgenius/dify/pull/42210)).
- [**Mintplex-Labs/anything-llm**](https://github.com/Mintplex-Labs/anything-llm) — merged: You.com web search for agents ([#6058](https://github.com/Mintplex-Labs/anything-llm/pull/6058)). Open: generic OpenAI sampling passthrough ([#6048](https://github.com/Mintplex-Labs/anything-llm/pull/6048)), saved endpoint connections ([#6065](https://github.com/Mintplex-Labs/anything-llm/pull/6065)).
- [**BerriAI/litellm**](https://github.com/BerriAI/litellm) — 2 merged: form-encoded video edit/extension bodies ([#36513](https://github.com/BerriAI/litellm/pull/36513)), managed batch output files ([#34092](https://github.com/BerriAI/litellm/pull/34092)). Open: internal metadata leak ([#36412](https://github.com/BerriAI/litellm/pull/36412)), Prometheus unmatched-path labels ([#36410](https://github.com/BerriAI/litellm/pull/36410)), `system_prompt` logging ([#36406](https://github.com/BerriAI/litellm/pull/36406)).
- [**langfuse/langfuse**](https://github.com/langfuse/langfuse) — open: monitor alert filter evaluation ([#16719](https://github.com/langfuse/langfuse/pull/16719)), comment-mention email persistence ([#16580](https://github.com/langfuse/langfuse/pull/16580)), login rate limits ([#16577](https://github.com/langfuse/langfuse/pull/16577)), observation IO in legacy trace downloads ([#15451](https://github.com/langfuse/langfuse/pull/15451)), admin API to list orgs by email ([#15453](https://github.com/langfuse/langfuse/pull/15453)).

**Agents & orchestration**

- [**mastra-ai/mastra**](https://github.com/mastra-ai/mastra) — 2 merged: sequential allow-tool results after auto-approved resume ([#19940](https://github.com/mastra-ai/mastra/pull/19940)), Zod v4 `jsonSchema` adapter ([#21187](https://github.com/mastra-ai/mastra/pull/21187)). Open: publish stored skill drafts ([#23032](https://github.com/mastra-ai/mastra/pull/23032)), deployment thinking defaults ([#23031](https://github.com/mastra-ai/mastra/pull/23031)), workspace resolution from project root ([#22861](https://github.com/mastra-ai/mastra/pull/22861)).

**Local training & inference**

- [**unslothai/unsloth**](https://github.com/unslothai/unsloth) — **41 merged** across Studio, installer, and inference (75K+ ★). Recent merges include Data Recipes download ([#10708](https://github.com/unslothai/unsloth/pull/10708)), shared Run settings draft ([#10851](https://github.com/unslothai/unsloth/pull/10851)), Hub credential verification ([#10264](https://github.com/unslothai/unsloth/pull/10264)), Gemma 4 `add_bos_token` ([#10312](https://github.com/unslothai/unsloth/pull/10312)), and LoRA/GGUF export token isolation ([#10263](https://github.com/unslothai/unsloth/pull/10263)). Open: llama extra args in model baseline ([#10870](https://github.com/unslothai/unsloth/pull/10870)), Run settings editor keys ([#10869](https://github.com/unslothai/unsloth/pull/10869)), `hf-xet` for Desktop downloads ([#10849](https://github.com/unslothai/unsloth/pull/10849)). [All Unsloth PRs](https://github.com/unslothai/unsloth/pulls?q=is%3Apr+author%3ASouravrajvi0).
- [**unslothai/unsloth-zoo**](https://github.com/unslothai/unsloth-zoo) — open: GPT-OSS optional import cascade ([#1198](https://github.com/unslothai/unsloth-zoo/pull/1198)), FLA autotune key work ([#1195](https://github.com/unslothai/unsloth-zoo/pull/1195)), Qwen3.8 vision `enable_thinking` ([#1072](https://github.com/unslothai/unsloth-zoo/pull/1072)).
- [**langgenius/dify-official-plugins**](https://github.com/langgenius/dify-official-plugins) — 4 merged: event-loop-safe plugin file parse ([#3756](https://github.com/langgenius/dify-official-plugins/pull/3756)), Cohere embed-v4.0 ([#3769](https://github.com/langgenius/dify-official-plugins/pull/3769)), Tongyi temperature floor ([#3767](https://github.com/langgenius/dify-official-plugins/pull/3767)), qwen3.8-flash models ([#3822](https://github.com/langgenius/dify-official-plugins/pull/3822)). Open: dynamic `extra_headers` on OpenAI-compatible ([#3869](https://github.com/langgenius/dify-official-plugins/pull/3869)), Qwen3-VL embedding/rerank ([#3841](https://github.com/langgenius/dify-official-plugins/pull/3841)), `reasoning_effort` forwarding ([#3832](https://github.com/langgenius/dify-official-plugins/pull/3832)).

**Parsers, SDKs & ML pipelines**

- [**langgenius/dify-plugin-sdks**](https://github.com/langgenius/dify-plugin-sdks) — merged: `BINARY_LINK` invoke message type ([#385](https://github.com/langgenius/dify-plugin-sdks/pull/385)).
- [**we-like-parsers/pegen**](https://github.com/we-like-parsers/pegen) · [**BerkeleyLearnVerify/Scenic**](https://github.com/BerkeleyLearnVerify/Scenic) — merged: Python 3.12+ f-string conversion specifiers ([#118](https://github.com/we-like-parsers/pegen/pull/118), [#501](https://github.com/BerkeleyLearnVerify/Scenic/pull/501)). Open: OpenDRIVE `paramPoly3` arc length ([#505](https://github.com/BerkeleyLearnVerify/Scenic/pull/505)).
- [**kubeflow/pipelines**](https://github.com/kubeflow/pipelines) — open: in-cluster KFP client DNS ([#13820](https://github.com/kubeflow/pipelines/pull/13820)), parameterized container images ([#13821](https://github.com/kubeflow/pipelines/pull/13821)), cyclic dependency detection ([#13823](https://github.com/kubeflow/pipelines/pull/13823)), pipeline I/O validation ([#13824](https://github.com/kubeflow/pipelines/pull/13824)), default StorageClass for CreatePVC ([#13834](https://github.com/kubeflow/pipelines/pull/13834)).

## Stack

Node.js · TypeScript · Python · Go · Java · Spring Boot · gRPC · PostgreSQL · Redis · RabbitMQ · MongoDB · AWS · Docker · Kubernetes · React · Next.js · Fastify · Dify · Langfuse · LiteLLM · RAGFlow · MinerU · Unsloth

## Contact

- LinkedIn — [linkedin.com/in/souravrajvi](https://linkedin.com/in/souravrajvi)
- Email — [souravrajvi@gmail.com](mailto:souravrajvi@gmail.com)
- GitHub — [github.com/Souravrajvi0](https://github.com/Souravrajvi0)
