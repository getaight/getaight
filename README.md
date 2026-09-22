<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/aight-rect-dark-1500x500.png">
    <img src="assets/aight-rect-light-1500x500.png" alt="Aight" width="420">
  </picture>

  <h3>Use AI. Earn more AI.</h3>
  <p>One API key for frontier and open models — and 10% back in credits on what you spend.</p>

  <p>
    <a href="https://getaight.ai/">Website</a> ·
    <a href="https://getaight.ai/models/">Models</a> ·
    <a href="https://getaight.ai/docs/">Docs</a> ·
    <a href="https://getaight.ai/docs/reference/">API reference</a> ·
    <a href="https://console.getaight.ai/">Console</a> ·
    <a href="https://getaight.ai/status/">Status</a>
  </p>
</div>

---

## What Aight is

**Aight** is an AI API gateway. One key, one balance, and one billing relationship
across text, vision and open-weight models from multiple providers — instead of a
separate account, invoice and rate limit for each one.

It is built and operated by **Ashva Intelligence Pvt Ltd**, Gurgaon, India.

What makes it different from calling the providers directly:

| | |
|---|---|
| **Credits back on usage** | Spend on AI and earn reward credits back — 10% on your consumption. Earned and purchased credits are tracked separately. |
| **Higher token limits** | Raised throughput on supported models for demanding production workloads. |
| **India hosting options** | Run supported models and workloads closer to home, where residency or latency matters. |
| **Published availability** | Model availability and service updates on a [public status page](https://getaight.ai/status/), not a support ticket. |

## Quickstart

The API is OpenAI-compatible, so most existing code changes by two lines — the
base URL and the key.

```python
from openai import OpenAI

client = OpenAI(
    api_key="YOUR_AIGHT_API_KEY",
    base_url="YOUR_AIGHT_BASE_URL",   # see https://getaight.ai/docs/reference/
)

response = client.chat.completions.create(
    model="gpt-5-nano",
    messages=[{"role": "user", "content": "Hello!"}],
)

print(response.choices[0].message.content)
```

1. Create an account and verify your email at [console.getaight.ai](https://console.getaight.ai/)
2. Add credits
3. Create an API key and send your first request

Full walkthrough: [getaight.ai/docs](https://getaight.ai/docs/)

## Models

Frontier models, small fast models and open weights in one catalogue, with input and
output pricing per million tokens shown side by side — so you can pick on cost as well
as capability.

A few of the cheapest entry points:

| Model | Best for | Input / Output (US$ per 1M tokens) |
|---|---|---|
| [`nova-micro`](https://getaight.ai/models/#model-nova-micro) | Short text-only replies, classification on a tight budget | $0.035 / $0.14 |
| [`gemma-3-4b`](https://getaight.ai/models/#model-gemma-3-4b) | Open model, text and image input | $0.04 / $0.08 |
| [`gpt-5-nano`](https://getaight.ai/models/#model-gpt-5-nano) | General production workloads | $0.05 / $0.40 |

[Browse the full catalogue →](https://getaight.ai/models/) (no account needed)

## How the credits work

Consumption earns reward credits back at 10%. Use $100 of AI, earn $10 in credits —
applied to what you build next rather than paid out. Details and current rates:
[getaight.ai/credits](https://getaight.ai/credits/)

## Resources

- **Docs** — https://getaight.ai/docs/
- **API reference** — https://getaight.ai/docs/reference/
- **Model catalogue** — https://getaight.ai/models/
- **Discover** — https://getaight.ai/discover/
- **Enterprise** — https://getaight.ai/enterprise/
- **Service status** — https://getaight.ai/status/
- **Support** — https://getaight.ai/support/

## Contact

Questions about volume pricing, India hosting or enterprise terms:
[support](https://getaight.ai/support/) · vaibhav@getaight.ai

<sub>Aight is a product of Ashva Intelligence Pvt Ltd, Gurgaon, Haryana, India.</sub>****
