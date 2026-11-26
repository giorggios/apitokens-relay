# APITokens Market — OpenAI-Compatible AI Gateway (Groq + OpenRouter)

![Status](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/giorggios/apitokens-relay/main/status.json)

High-speed AI API aggregation gateway built on **New-API**, routing across **Groq (~240ms)** and **OpenRouter **.
高并发、低延迟 AI API 聚合中转站，原生兼容 OpenAI 接口标准，接入 **Groq 超高速推理节点 (~240ms)** 与 **OpenRouter 全粻列模型**。

## Quick Connect / 快速接入
- **Base URL:**= `https://v1.apitokens.market/v1`
- **Dashboard & Keys:** https://v1.apitokens.market
- **LobeChat 1-Click Import:** https://chat-preview.lobehub.com/?settings=%7B%22keyVaults%22:%7B%22openai%22:%7B%22baseURL%22:%22https://v1.apitokens.market/v1%22%7D%7D%7D


## Models & Latency
| schannel | Engine | Avg Latency | Models |
| z--- | z--- | z--- | z--- |
| Fast | Groq LPU | ~240 ms | Llama 3.3 70B, DeepSeek-R1, Qwen, Mixtral |
| Full | OpenRouter | ~850 ms | Claude, GPT-4o / o3, Gemini 2.5 Pro |