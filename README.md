# 👋 Hi, I am Shejal
I am fullstack Applied AI Engineer with over 2 years of experience in building production AI systems at early-stage startups. I don't just build things that work in demos but those that hold up when real customers depend on them every day.

## Accomplishments
* AI Agents & Pipelines — multi-agent systems, LLM-driven automation, agentic workflows that replace manual processes
* Browser Automation — production-grade bots on legacy enterprise portals (Applied Epic, insurance carrier systems)
* RAG Systems — retrieval pipelines with real-world evaluation metrics, not just toy examples
* Real-Time Voice AI — WebSocket-based audio streaming, OpenAI Realtime API integration
* Full-Stack Products — React, Next.js, Node.js, Python, TypeScript, end to end

 ## 🔨 Featured Projects
### 🎙️ EchoMind — Voice-First AI Thought Journal
* A five-agent sequential pipeline (synthesis → linking → research → action → calendar) that processes raw voice input into structured insights, action items, and calendar events in real time.
* OpenAI Realtime API with WebSocket-based PCM audio streaming (24kHz)
* GPT-4o-mini for agents, Exa for neural search
* SVG-based UI to visualize thought clusters and relationships

### 📈 Financial Insight Assistant — Conversational AI for Real-Time Finance
* A RAG-based conversational system achieving 92% ticker recognition and ~87% retrieval relevance using Reddit investor sentiment.
* ChromaDB + HuggingFace embeddings for semantic retrieval
* Real-time Q&A interface with historical chat replay

## 💼 What I've Shipped in Production
1) Browser Automation on Applied Epic — Built a bot that logs into Applied Epic, creates statements by company and agency codes, retrieves transaction line items, zeros payable amounts, generates final statements, and fires a webhook with the Master statement number. Chose Playwright over LLM-driven UI interaction because Epic's flaky interface needed deterministic control. Processed 300+ transactions in under 10 minutes — faster than the legacy Blue Sierra solution it replaced. A strategic enterprise customer posted a live statement using it on day one.
2) LLM-Driven Document Extraction — Automated statement retrieval across 15 legacy insurance carrier portals, eliminating manual login, navigation, and PDF retrieval. Redesigned prompt and validation logic for carrier-specific edge cases causing silent LLM failures. Processed 356K+ tokens of real financial data across 6 production carriers, stabilizing 50+ daily reconciliation workflows.
3) Self-Healing Automation Pipeline — Designed a fallback system where a vision LLM takes a viewport snapshot and identifies bottlenecks (shifted buttons, hidden CAPTCHAs, rotating element IDs) only when primary Playwright selectors fail — keeping 300-transaction batches under 12 minutes without sacrificing reliability.

## 📫 Let's Connect
- 🌐 [linkedin.com/in/shejal28]
- 📧 shejshankar@gmail.com
- 📍 Bay Area, CA

"*Most often it's not the LLM itself — it's how you design the systems and workflows around it.*"
