# AivoraS

A premium multi-model AI workspace UI built with Next.js App Router.

## Run locally

```bash
npm install
npm run dev
```

Open http://localhost:3000.

## Production

```bash
npm run build
npm start
```

## Connecting real AI providers

The included chat is a safe demo UI. To make it generate real responses, connect official provider APIs through a server-side route (preferably Vercel AI SDK / AI Gateway), keep provider keys in environment variables, and enforce usage limits on the server.

Suggested env names:
- AI_GATEWAY_API_KEY
- OPENAI_API_KEY (if using direct OpenAI integration)
- ANTHROPIC_API_KEY (if using direct Anthropic integration)
- GOOGLE_GENERATIVE_AI_API_KEY (if using direct Google integration)

Do not expose secret API keys in client-side code.
