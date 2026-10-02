# Sourav Rajvi

![Profile views](https://komarev.com/ghpvc/?username=Souravrajvi0&label=Profile%20views&color=0e75b6&style=flat-square)

I build backends end-to-end — distributed systems, LLM gateways, middleware automation, and the infrastructure that keeps them reliable. Backend developer focused on microservices, cloud architecture, and open-source work in the AI tooling ecosystem.

**Maintainer @ [InfiniFlow](https://github.com/infiniflow)** — dedicated maintainer of the [MinerU](https://github.com/infiniflow/ragflow) PDF/layout parser in [RAGFlow](https://github.com/infiniflow/ragflow) (90K+ GitHub stars). Own MinerU-related issues and PRs; contributed MonkeyOCR as a dedicated PDF backend ([#19044](https://github.com/infiniflow/ragflow/pull/19044)).

## Personal project

- [**openinference**](https://github.com/Souravrajvi0/openinference) — one repo, two products: **SentinelAI**, a self-hosted AI gateway (multi-provider routing, guardrails, hybrid RAG, agents, traces, evals, React admin) and **[`@openinference/cli`](https://github.com/Souravrajvi0/openinference/tree/main/packages/cli)** (`oi`), a publishable CLI for hardware-aware local models and a project-local agent harness. Stack: Fastify · PostgreSQL/pgvector · Redis/BullMQ · Docker Compose. Live — [demo](http://64.227.178.3) · [API docs](http://64.227.178.3/api-docs) · [CLI guide](https://openinference.tech/cli).

## Open source

**100+** upstream pull requests merged and reviewed **in 2026** (own repos excluded) across LLM platforms, local inference, agents, and ML infrastructure. [Merged PRs](https://github.com/search?q=author%3ASouravrajvi0+is%3Apr+is%3Amerged+-user%3ASouravrajvi0&type=pullrequests) · [Reviewed PRs](https://github.com/search?q=is%3Apr+reviewed-by%3ASouravrajvi0+-user%3ASouravrajvi0&type=pullrequests).

**LLM platforms**

- [**infiniflow/ragflow**](https://github.com/infiniflow/ragflow) — **maintainer, MinerU parser** (90K+ ★). Merged: dataset navigation tree ([#17668](https://github.com/infiniflow/ragflow/pull/17668)), canvas autosave guard ([#18783](https://github.com/infiniflow/ragflow/pull/18783)), spreadsheet/JSON parser hardening ([#19237](https://github.com/infiniflow/ragflow/pull/19237)), wiki retrieval fields ([#18787](https://github.com/infiniflow/ragflow/pull/18787)), chunk `image_update_mode` ([#18889](https://github.com/infiniflow/ragflow/pull/18889)), DOCX preview loop ([#19475](https://github.com/infiniflow/ragflow/pull/19475)), MinerU `server_url` in Go PDF parser ([#19445](https://github.com/infiniflow/ragflow/pull/19445)), text-only pre-index wire contract ([#19478](https://github.com/infiniflow/ragflow/pull/19478)), Zotero connector ([#19742](https://github.com/infiniflow/ragflow/pull/19742)), OpenAI GPT-5.6 models ([#19856](https://github.com/infiniflow/ragflow/pull/19856)), numpy 2.x on Python 3.13 ([#20014](https://github.com/infiniflow/ragflow/pull/20014)), chunker media context ([#20265](https://github.com/infiniflow/ragflow/pull/20265)). Open: MonkeyOCR Go dispatch ([#20469](https://github.com/infiniflow/ragflow/pull/20469)), MonkeyOCR Python backend ([#20465](https://github.com/infiniflow/ragflow/pull/20465)), DOCX delimiter Q&A grouping ([#20514](https://github.com/infiniflow/ragflow/pull/20514)), embedded-image VLM in DeepDOC ([#20429](https://github.com/infiniflow/ragflow/pull/20429)).

- [**langgenius/dify**](https://github.com/langgenius/dify) — Merged: legacy `model_type` cleanup ([#39708](https://github.com/langgenius/dify/pull/39708)), agent think-tag closure ([#41764](https://github.com/langgenius/dify/pull/41764)), CSV cell text on import ([#41922](https://github.com/langgenius/dify/pull/41922)), in-run tool file grants ([#41300](https://github.com/langgenius/dify/pull/41300)), `UV_CACHE_DIR` for plugin daemon ([#42481](https://github.com/langgenius/dify/pull/42481)), defer tldts for MCP favicons ([#42486](https://github.com/langgenius/dify/pull/42486)), nuqs peer alignment ([#42517](https://github.com/langgenius/dify/pull/42517)), bump c12 ([#43103](https://github.com/langgenius/dify/pull/43103)). Open: workflow conversation variables ([#43329](https://github.com/langgenius/dify/pull/43329)), agent plugin blob outputs ([#43099](https://github.com/langgenius/dify/pull/43099)), retrieval quota with `skip_on_error` ([#43097](https://github.com/langgenius/dify/pull/43097)).

- [**Mintplex-Labs/anything-llm**](https://github.com/Mintplex-Labs/anything-llm) — merged: You.com web search for agents ([#6058](https://github.com/Mintplex-Labs/anything-llm/pull/6058)). Open: generic OpenAI sampling passthrough ([#6048](https://github.com/Mintplex-Labs/anything-llm/pull/6048)), saved endpoint connections ([#6065](https://github.com/Mintplex-Labs/anything-llm/pull/6065)).
- [**BerriAI/litellm**](https://github.com/BerriAI/litellm) — Merged: form-encoded video edit/extension bodies ([#36513](https://github.com/BerriAI/litellm/pull/36513)), managed batch output files ([#34092](https://github.com/BerriAI/litellm/pull/34092)). Open: internal metadata leak ([#36412](https://github.com/BerriAI/litellm/pull/36412)), Prometheus unmatched-path labels ([#36410](https://github.com/BerriAI/litellm/pull/36410)), `system_prompt` logging ([#36406](https://github.com/BerriAI/litellm/pull/36406)).
- [**langfuse/langfuse**](https://github.com/langfuse/langfuse) — open: monitor alert filter evaluation ([#16719](https://github.com/langfuse/langfuse/pull/16719)), comment-mention email persistence ([#16580](https://github.com/langfuse/langfuse/pull/16580)), login rate limits ([#16577](https://github.com/langfuse/langfuse/pull/16577)), observation IO in legacy trace downloads ([#15451](https://github.com/langfuse/langfuse/pull/15451)), admin API to list orgs by email ([#15453](https://github.com/langfuse/langfuse/pull/15453)).

**Agents & orchestration**

- [**mastra-ai/mastra**](https://github.com/mastra-ai/mastra) — Merged: sequential allow-tool results after auto-approved resume ([#19940](https://github.com/mastra-ai/mastra/pull/19940)), Zod v4 `jsonSchema` adapter ([#21187](https://github.com/mastra-ai/mastra/pull/21187)). Open: publish stored skill drafts ([#23032](https://github.com/mastra-ai/mastra/pull/23032)), deployment thinking defaults ([#23031](https://github.com/mastra-ai/mastra/pull/23031)), workspace resolution from project root ([#22861](https://github.com/mastra-ai/mastra/pull/22861)).

**Local training & inference**

- [**unslothai/unsloth**](https://github.com/unslothai/unsloth) — Studio, installer, and inference (75K+ ★). Merged:

  - [#7297](https://github.com/unslothai/unsloth/pull/7297) — fix(studio): show chat sidebar menu on touch devices
  - [#7298](https://github.com/unslothai/unsloth/pull/7298) — fix(studio): persist connection model selections for remote clients
  - [#7299](https://github.com/unslothai/unsloth/pull/7299) — fix: pin torchcodec for torch 2.10 and warn on ABI mismatch
  - [#7300](https://github.com/unslothai/unsloth/pull/7300) — fix(install): route Strix to AMD gfx index on ROCm 7.14
  - [#7305](https://github.com/unslothai/unsloth/pull/7305) — fix(install): infer Strix gfx when ROCm runtime is absent
  - [#7322](https://github.com/unslothai/unsloth/pull/7322) — fix(studio): opt-in source-build GPU smoke validation
  - [#7323](https://github.com/unslothai/unsloth/pull/7323) — fix(studio): resolve bare git on Windows sandbox PATH
  - [#7324](https://github.com/unslothai/unsloth/pull/7324) — fix(install): show detected distro in sudo apt Accept prompt
  - [#7332](https://github.com/unslothai/unsloth/pull/7332) — fix(studio): stop false MTP/vision capability reports
  - [#7334](https://github.com/unslothai/unsloth/pull/7334) — fix(studio): neutralize chat-template control markup in client text (#7066)
  - [#7348](https://github.com/unslothai/unsloth/pull/7348) — feat(studio): expose full KV cache dtype list in model config UI
  - [#7349](https://github.com/unslothai/unsloth/pull/7349) — fix(studio/colab): restore blank Colab iframe embed (#7344)
  - [#7351](https://github.com/unslothai/unsloth/pull/7351) — fix(studio): honor run settings on initial model load (#7346)
  - [#7352](https://github.com/unslothai/unsloth/pull/7352) — feat(studio): presets include load settings (#7347)
  - [#7373](https://github.com/unslothai/unsloth/pull/7373) — Installer: opt-in Vulkan llama.cpp backend (and fallback when no AMD card is HIP-supported)
  - [#7375](https://github.com/unslothai/unsloth/pull/7375) — Studio: restore cached models hidden by a dangling HF ref, and stop auto-load downloading after a failed load (#7374)
  - [#7415](https://github.com/unslothai/unsloth/pull/7415) — fix(studio): reject Vulkan diffusion gpu_ids before Phase 1 teardown
  - [#7453](https://github.com/unslothai/unsloth/pull/7453) — fix(studio): refresh token count after model load (#7450)
  - [#7482](https://github.com/unslothai/unsloth/pull/7482) — avoid Hub metadata probe when loading tokenizers with local_files_only
  - [#7976](https://github.com/unslothai/unsloth/pull/7976) — [Fix] Unsloth Studio: Strip ANSI escape codes from Studio tool output panes
  - [#7982](https://github.com/unslothai/unsloth/pull/7982) — Fix desktop image drops for chat attachments
  - [#7985](https://github.com/unslothai/unsloth/pull/7985) — Clamp Deep Research max_tokens to loaded context window
  - [#8217](https://github.com/unslothai/unsloth/pull/8217) — Fix resume button missing after stop-and-save (#8150)
  - [#8389](https://github.com/unslothai/unsloth/pull/8389) — fix(studio): return 404 for mistyped GGUF model ids on /v1 API
  - [#9149](https://github.com/unslothai/unsloth/pull/9149) — fix(studio): auto-enable --embedding for GGUFs missing pooling_type
  - [#9346](https://github.com/unslothai/unsloth/pull/9346) — fix(studio): use resolved public id in embeddings/completions monitor
  - [#9402](https://github.com/unslothai/unsloth/pull/9402) — fix(studio): refresh profile stats and mode-aware activity summary
  - [#9770](https://github.com/unslothai/unsloth/pull/9770) — route thinking controls to ollama
  - [#9773](https://github.com/unslothai/unsloth/pull/9773) — Studio: honour forced tool_choice on local GGUF tool loops
  - [#9774](https://github.com/unslothai/unsloth/pull/9774) — Studio: add Chat settings to disable or ease GGUF auto-compaction
  - [#9849](https://github.com/unslothai/unsloth/pull/9849) — Studio: keep a Downloads entry when the list is empty
  - [#9870](https://github.com/unslothai/unsloth/pull/9870) — Fix Studio CPT overwriting LFM2 all-linear LoRA targets
  - [#9871](https://github.com/unslothai/unsloth/pull/9871) — strip inherited claude provider routing from local agent launches
  - [#9905](https://github.com/unslothai/unsloth/pull/9905) — fix(studio): repair custom TTS endpoint test and playback
  - [#9980](https://github.com/unslothai/unsloth/pull/9980) — Fix llama.cpp Studio update failures on GitHub API rate limits (#9970)
  - [#10045](https://github.com/unslothai/unsloth/pull/10045) — Studio: resume HTTP after Xet stall without a transport-conflict banner
  - [#10048](https://github.com/unslothai/unsloth/pull/10048) — Studio: browse temporary Linux mounts under /media and /mnt
  - [#10253](https://github.com/unslothai/unsloth/pull/10253) — Studio: drop MediaPageLink tooltip below titlebar controls on Windows
  - [#10263](https://github.com/unslothai/unsloth/pull/10263) — Keep the LoRA GGUF and compressed-tensors converters off the operator's Hugging Face token
  - [#10264](https://github.com/unslothai/unsloth/pull/10264) — Studio: verify Hub credentials before cache-backed reads
  - [#10312](https://github.com/unslothai/unsloth/pull/10312) — fix(tokenizer): enable add_bos_token for Gemma 4 base models
  - [#10642](https://github.com/unslothai/unsloth/pull/10642) — feat(studio): consistent SSH restrictions with approved-server allowlist
  - [#10644](https://github.com/unslothai/unsloth/pull/10644) — fix(studio): keep distinct symlink aliases for per-model settings
  - [#10708](https://github.com/unslothai/unsloth/pull/10708) — Studio: add Download Dataset button for Data Recipes
  - [#10710](https://github.com/unslothai/unsloth/pull/10710) — Studio: JSON and Markdown validator blocks
  - [#10736](https://github.com/unslothai/unsloth/pull/10736) — Studio: top-level Models block group in picker
  - [#10837](https://github.com/unslothai/unsloth/pull/10837) — fix(studio): retry custom gateways with max_completion_tokens after max_tokens 400 (#10787)
  - [#10847](https://github.com/unslothai/unsloth/pull/10847) — fix(studio): serve desktop SPA on loopback listener
  - [#10849](https://github.com/unslothai/unsloth/pull/10849) — fix(studio): bundle hf-xet for Desktop large Hub downloads
  - [#10851](https://github.com/unslothai/unsloth/pull/10851) — fix(studio): share Run settings draft across sidebar and model picker
  - [#10870](https://github.com/unslothai/unsloth/pull/10870) — fix(studio): include loaded llama extra args in active model baseline
  - [#11499](https://github.com/unslothai/unsloth/pull/11499) — feat(studio): configurable RAG upload extensions via RAG_UPLOAD_EXTS
  - [#11500](https://github.com/unslothai/unsloth/pull/11500) — fix(studio): reconcile externally updated saved assistant messages
  - [#12087](https://github.com/unslothai/unsloth/pull/12087) — fix(studio): prevent terminal tool hangs in credential scan (#12048)
  - [#12091](https://github.com/unslothai/unsloth/pull/12091) — feat(studio): complete embedded image recipe and Recipe popover
  - [#12138](https://github.com/unslothai/unsloth/pull/12138) — fix(studio): allow Enter to send with idle macOS Pinyin IME

  Open: markdown chat import/export ([#12513](https://github.com/unslothai/unsloth/pull/12513)), offline On Device GGUF discovery ([#12451](https://github.com/unslothai/unsloth/pull/12451)), 1-D GGUF norm dequant ([#12449](https://github.com/unslothai/unsloth/pull/12449)), block-split long backslash lines ([#11501](https://github.com/unslothai/unsloth/pull/11501)), WSL2 localhost hint ([#11361](https://github.com/unslothai/unsloth/pull/11361)), `web_search` argument recovery ([#9716](https://github.com/unslothai/unsloth/pull/9716)). [All Unsloth PRs](https://github.com/unslothai/unsloth/pulls?q=is%3Apr+author%3ASouravrajvi0).
- [**unslothai/unsloth-zoo**](https://github.com/unslothai/unsloth-zoo) — Merged: Qwen3.8 vision `enable_thinking` ([#1072](https://github.com/unslothai/unsloth-zoo/pull/1072)), FLA autotune cache key ([#1195](https://github.com/unslothai/unsloth-zoo/pull/1195)), MLX trusted-dir test on Windows ([#1228](https://github.com/unslothai/unsloth-zoo/pull/1228)).
- [**langgenius/dify-official-plugins**](https://github.com/langgenius/dify-official-plugins) — Merged: event-loop-safe plugin file parse ([#3756](https://github.com/langgenius/dify-official-plugins/pull/3756)), Cohere embed-v4.0 ([#3769](https://github.com/langgenius/dify-official-plugins/pull/3769)), Tongyi temperature floor ([#3767](https://github.com/langgenius/dify-official-plugins/pull/3767)), qwen3.8-flash models ([#3822](https://github.com/langgenius/dify-official-plugins/pull/3822)). Open: dynamic `extra_headers` on OpenAI-compatible ([#3869](https://github.com/langgenius/dify-official-plugins/pull/3869)), Qwen3-VL embedding/rerank ([#3841](https://github.com/langgenius/dify-official-plugins/pull/3841)), `reasoning_effort` forwarding ([#3832](https://github.com/langgenius/dify-official-plugins/pull/3832)).

**Parsers, SDKs & ML pipelines**

- [**langgenius/dify-plugin-sdks**](https://github.com/langgenius/dify-plugin-sdks) — merged: `BINARY_LINK` invoke message type ([#385](https://github.com/langgenius/dify-plugin-sdks/pull/385)).
- [**we-like-parsers/pegen**](https://github.com/we-like-parsers/pegen) · [**BerkeleyLearnVerify/Scenic**](https://github.com/BerkeleyLearnVerify/Scenic) — merged: Python 3.12+ f-string conversion specifiers ([#118](https://github.com/we-like-parsers/pegen/pull/118), [#501](https://github.com/Scenic-Foundation/Scenic/pull/501)). Open: OpenDRIVE `paramPoly3` arc length ([#505](https://github.com/Scenic-Foundation/Scenic/pull/505)).
- [**jonescompneurolab/hnn-core**](https://github.com/jonescompneurolab/hnn-core) — Merged: Safari stray scrollbars on empty GUI dropdowns ([#1360](https://github.com/jonescompneurolab/hnn-core/pull/1360)). Open: evoked `set_params` test helper ([#1362](https://github.com/jonescompneurolab/hnn-core/pull/1362)).
- [**kubeflow/pipelines**](https://github.com/kubeflow/pipelines) — open: in-cluster KFP client DNS ([#13820](https://github.com/kubeflow/pipelines/pull/13820)), parameterized container images ([#13821](https://github.com/kubeflow/pipelines/pull/13821)), cyclic dependency detection ([#13823](https://github.com/kubeflow/pipelines/pull/13823)), pipeline I/O validation ([#13824](https://github.com/kubeflow/pipelines/pull/13824)), default StorageClass for CreatePVC ([#13834](https://github.com/kubeflow/pipelines/pull/13834)).

## Stack

Node.js · TypeScript · Python · Go · Java · Spring Boot · gRPC · PostgreSQL · Redis · RabbitMQ · MongoDB · AWS · Docker · Kubernetes · React · Next.js · Fastify · Dify · Langfuse · LiteLLM · RAGFlow · MinerU · Unsloth

## Contact

- Portfolio — [souravrajvi0.github.io](https://souravrajvi0.github.io/)
- LinkedIn — [linkedin.com/in/souravrajvi](https://linkedin.com/in/souravrajvi)
- Email — [souravrajvi@gmail.com](mailto:souravrajvi@gmail.com)
- GitHub — [github.com/Souravrajvi0](https://github.com/Souravrajvi0)
