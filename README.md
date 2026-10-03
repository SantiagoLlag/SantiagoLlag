# Santiago Llaguno

Voice agents that talk with customers and train sellers. Founder of Sonelo. Claude Certified Architect (Professional).

I build voice agents for sales and customer service teams. Before one meets a real customer, I test it against the calls it will get. If you hire for this work or build agents yourself, start with the first repo below. It holds the prompts, the knowledge base and the 40 tests of an agent that is live today.

## What I've built

### Talk to Santiago · [live](https://santiago-llaguno.vercel.app) · [code](https://github.com/SantiagoLlag/talk-to-santiago)
A voice agent that tells recruiters about my work and opens my demos in a window over the page. Two agents, one in Spanish and one in English, run on ElevenLabs Agents with Claude. Everything they may say traces to a fact ledger, and 40 tests per language gate each publish.

### Voice concierge for a sales room · [live](https://vista-privada.vercel.app)
Built at Los Cabos Sotheby's International Realty for Pacific Villas at Oleada Los Cabos. The concierge moves the screen while it talks: lots, the golf course, renderings and floor plans. Claude answers behind a proxy I wrote that caps each turn at 60 words and one question.

### Dive-trip shopping agent · [live](https://nautilus-clone.vercel.app)
It recommends trips by the traveler's profile, checks availability through a tool before it answers, and hands health questions to a person. Built on public trip data. Its evals cover handoff, booking, availability and accuracy.

### Voice sales trainer · [live](https://voice-sales-trainer-demo.vercel.app)
A seller practices out loud against a simulated buyer who haggles on price. When they hang up, Claude grades the call against a rubric. The public demo plays the voice live and shows a sample report. Adapted for store, real estate and car dealership teams.

## How I work

Each agent starts with a map of the calls it will handle and the points where they stall. I write its tests from that map, including when it must hand the call to a person. I build on ElevenLabs Agents and Anthropic's Claude from Claude Code, connected through MCP (Model Context Protocol). I keep a ledger of what each agent may and may not say. The rest of my stack, by layer:

| Layer | Tools |
|---|---|
| Languages | TypeScript, Python |
| Front end | React, Next.js, Astro |
| Infrastructure | Supabase, Vercel, Cloudflare |
| Evals | Golden sets, a model as judge, rubrics |

## Before this

I started in data analysis and operations. My first job, at Right Source, was automating the weekly formatting of thousands of documents. Later I ran workplace surveys for Stratego in factories in four Mexican cities. I cofounded Datasphere, a pricing tool for restaurants that another company bought. At Los Cabos Sotheby's International Realty, where I built the concierge above, I sold 7 of the 15 units in a new development.

I studied applied mathematics at ITAM, a university in Mexico City. Now I study psychology at UNAM, Mexico's national university, to understand what happens to people when a machine talks back. I work in English and Spanish from Los Cabos, Mexico.

## Contact

santiago@sonelo.ai · [sonelo.ai](https://sonelo.ai) · [LinkedIn](https://www.linkedin.com/in/santiago-llaguno-461511323)
