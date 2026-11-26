# APITokens Market — OpenAI-Compatible AI API Gateway (Groq + OpenRouter)

![Status](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/giorggios/apitokens-relay/main/status.json)

High-speed AI API aggregation gateway built on **New-API**, routing across **Groq LPU (~240ms)** and **OpenRouter (300+ models)** with a single OpenAI-compatible key.

---

## Quick Connect

- **API Base URL:** `https://v1.apitokens.market/v1`
- **Dashboard & API Keys:** [https://v1.apitokens.market](https://v1.apitokens.market)
- **LobeChat 1-Click Import:** [Import to LobeChat](https://chat-preview.lobehub.com/?settings=%7B%22keyVaults%22:%7B%22openai%22:%7B%22baseURL%22:%22https://v1.apitokens.market/v1%22%7D%7D%7D)
- **Cherry Studio / NextChat / Cline / Cursor:** Select **OpenAI Compatible**, set Base URL to `[https://v1.apitokens.market/v1](https://v1.apitokens.market/v1)`, and paste your `sk-...` key.

---

## Routing Channels & Latency

| Channel | Upstream Engine | Avg Latency | Featured Models |
| :--- | :--- | :---: | :--- |
| **Fast** | Groq LPU | ~240 ms | Llama 3.3 70B, DeepSeek-R1, Qwen, Mixtral |
| **Full** | OpenRouter | ~850 ms | Claude 3.7 / 4, GPT-4o / o3, Gemini 2.5 Pro |