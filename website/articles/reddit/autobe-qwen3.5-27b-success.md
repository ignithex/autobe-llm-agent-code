<!--
[AutoBe] Qwen 3.5-27B Just Built Complete Backends from Scratch — 100% Compilation, 25x Cheaper
-->

We benchmarked Qwen 3.5-27B against 10 other models on backend generation — including Claude Opus 4.6 and GPT-5.4. The outputs were nearly identical. 25x cheaper.

## TL;DR

1. Qwen 3.5-27B achieved 100% compilation on all 4 backend projects
   - [Todo](https://github.com/wrtnlabs/autobe-examples/tree/main/qwen/qwen3.5-27b/todo), [Reddit](https://github.com/wrtnlabs/autobe-examples/tree/main/qwen/qwen3.5-27b/reddit), [Shopping](https://github.com/wrtnlabs/autobe-examples/tree/main/qwen/qwen3.5-27b/shopping), [ERP](https://github.com/wrtnlabs/autobe-examples/tree/main/qwen/qwen3.5-27b/erp)
   - Each includes DB schema, OpenAPI spec, NestJS implementation, E2E tests, type-safe SDK
2. Benchmark scores are nearly uniform across all 11 models
   - Compiler decides output quality, not model intelligence
   - Model capability only affects retry count (Opus: 1-2, Qwen 3.5-27B: 3-4)
   - "If you can verify, you converge"
3. Coming soon: Qwen 3.5-35B-A3B (3B active params)
   - Not at 100% yet — but close
   - 77x cheaper than frontier models, on a normal laptop

Full writeup: https://autobe.dev/articles/autobe-qwen3.5-27b-success.html

## Previous Articles

- [Qwen Meetup — Function Calling Harness turning 6.75% to 100%](https://www.reddit.com/r/LocalLLaMA/comments/1s4ydfu/qwen_meetup_function_calling_harness_with_qwen/)
- [AutoBe vs. Claude Code — Coding Agent Developer's Review](https://www.reddit.com/r/LocalLLaMA/comments/1sexhy2/autobe_vs_claude_code_coding_agent_developers/)
