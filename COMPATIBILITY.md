# DSH x GoMixAPI Compatibility Matrix

| Model ID | Input $/1M | Output $/1M | Chat | Streaming | Tools | Agent-Ready |
|----------|:--:|:--:|:--:|:--:|:--:|:--:|
| deepseek-v4-flash-202605 | 0.7 | 2.1 | OK | OK | OK | OK |
| deepseek-v4-pro-202606 | 2.0 | 6.0 | OK | OK | OK | OK |
| glm-5.1 | 1.8 | 9.9 | OK | OK | OK | OK |
| glm-5.2 | 1.55 | 8.6 | OK | OK | OK | OK |
| glm-5v-turbo | 1.65 | 8.95 | OK | OK | OK | OK |
| glm-5-turbo | 1.65 | 8.95 | OK | OK | OK | OK |
| hy-mt2-plus | 0.15 | 0.9 | OK | OK | OK | OK |
| dola-Seed-2.0-mini | 0.15 | 0.6 | OK | OK | OK | OK |
| dola-Seed-2.0-lite | 0.5 | 3.0 | OK | OK | OK | OK |
| dola-Seed-2.0-pro | 1.1 | 6.6 | OK | OK | OK | OK |
| qwen3.5-flash | 0.15 | 0.6 | OK | OK | OK | OK |
| qwq-plus | 1.1 | 6.05 | OK | OK | OK | OK |
| qwen3.6-flash | 0.5 | 2.8 | OK | OK | OK | OK |
| qwen3.5-plus | 1.05 | 5.75 | OK | OK | OK | OK |
| qwen3.7-plus | 0.7 | 3.9 | OK | OK | OK | OK |
| qwen3.7-plus-1m | 1.85 | 10.2 | OK | OK | OK | OK |
| qwen3-vl-plus | 0.5 | 2.5 | OK | OK | OK | OK |
| dola-Seed-2.1-turbo | 0.7 | 3.5 | OK | OK | OK | OK |
| hy3 | 0.4 | 1.6 | OK | OK | OK | OK |
| kimi-k3 | 5.5 | 31.0 | OK | OK | OK | OK |

## DSH Version Compatibility

Tested with:
- DSH v0.1 Developer Preview (initial release)
- DSH RC8 pre-release (OpenAI-compatible endpoint still works)

The GoMixAPI profile operates at the OpenAI-compatible model layer.
DSH framework updates (subagents, unattended mode, multimodal commands)
do not affect model endpoint compatibility.
