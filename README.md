# OctoQuorum

A VS Code extension that sends your coding questions to **8 open-source AI models simultaneously**, then synthesises their responses into a single "best answer" through a consensus mechanism.

## Features

- **Council of 8**: Query 8 different AI models in parallel
- **Consensus Synthesis**: Automatically scores and merges the best parts of each response
- **Self-Optimising**: Automatically replaces underperforming models
- **Zero Cost**: Uses free API tiers - users provide their own API keys
- **Fully Open-Source**: All models are open-weights (Apache 2.0, MIT, Llama 3.3)

## Status

**Currently in Phase 1: Architecture Planning**

See [docs/PHASE_1_ARCHITECTURE.md](docs/PHASE_1_ARCHITECTURE.md) for the complete system design.

## Supported Providers

| Provider    | Models                        | Free Tier          |
|-------------|-------------------------------|--------------------|
| Groq        | Llama 3.3 70B, Qwen 3 32B     | 1,000 req/day      |
| Cerebras    | Llama 3.3 70B, Qwen 3 32B     | 14,400 req/day     |
| HuggingFace | Qwen2.5-Coder, DeepSeek-Coder | ~$0.10/month       |
| OpenRouter  | Qwen3-Coder                   | 50 req/day         |
| Cloudflare  | Qwen2.5-Coder                 | 10,000 neurons/day |

## Development

```bash
# Clone the repository
git clone https://github.com/Calum-Kerr/OctoQuorum.git

# Install dependencies (coming in Phase 2)
npm install

# Run the extension (coming in Phase 2)
npm run watch
```

## Licence

MIT