# Julien Joggerst

Founder of [Phosteon](https://www.phosteon.com), a voice AI platform for e-commerce and enterprise customer service. I design, build and operate the whole platform as sole technical owner, using Claude Code as my primary engineering tool.

**What the agents do:** answer customer calls 24/7, identify callers, look up orders, resolve standard requests from a knowledge base, create structured tickets, and hand over to humans with full context.

**What makes it different:** the first voice AI platform running a realtime speech-to-speech model fully hosted in Europe, GDPR-compliant end to end. Live models are fast and natural but hard to make reliable; through deliberate tooling and engineering around the model, the platform delivers reproducible results at low latency while keeping every advantage of a live model.

**What I own:** solution architecture, data model, integrations (Shopify, Zendesk, Zoho CRM/Desk, TheFork, Slack, Stripe, webhooks, SMS), prompt and conversation design, structured testing, deployment, monitoring, incident response.

```mermaid
flowchart LR
    A[Inbound call] --> B[Telephony]
    subgraph EU["Fully EU-hosted, GDPR-compliant end to end"]
        direction LR
        B --> C[Realtime agent<br/>deterministic tooling around the model:<br/>reproducible results, low latency]
        M[Realtime speech-to-speech model<br/>natural dialogue, no STT/TTS chain] <--> C
        C --> D[Customer systems<br/>orders, help desk, CRM, knowledge base]
        C --> E[Post-call pipeline<br/>outcome classification, ticket creation,<br/>email capture, quality monitoring]
        E --> F[Customer dashboard]
    end
```

**Before Phosteon:** built a D2C brand from a EUR 10k bootstrap to a ~EUR 2M exit across eight European markets; enterprise IT at Ford Motor Company.

Try a live call: [phosteon.com](https://www.phosteon.com)

LinkedIn: [linkedin.com/in/julienjoggerst](https://www.linkedin.com/in/julienjoggerst)
