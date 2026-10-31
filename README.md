# Seliee

**One panel instead of seven subscriptions.**

Seliee is a marketing and growth platform that brings websites, content, SEO, AEO, GEO, ads, social media, customers, email and analytics into a single panel. On top of that it gives you an **AI Office** (a team of AI agents that work for you), a **multi-provider AI layer** (bring your own keys), and an **MCP server and REST API** so your own tools and AI clients can drive the whole platform.

 · **Website:** [www.seliee.si](https://www.seliee.si)
 · **Free 50 tokens:** [Claim them here](https://seliee.si/r/lic804jq)
 · **Free forever, no time limit**, with monthly and yearly plans when you grow.

---

## Contents

- [Why Seliee](#why-seliee)
- [AI Office: your AI marketing team](#ai-office-your-ai-marketing-team)
- [Multi-AI assistant layer](#multi-ai-assistant-layer)
- [MCP server](#mcp-server)
- [API](#api)
- [Everything else in the panel](#everything-else-in-the-panel)
- [Get started](#get-started)

---

## Why Seliee

Marketers juggle a CMS, an SEO tool, a GEO tool, an AEO tool, an AI writer, design, video, analytics, a CRM, forms, hosting, a social inbox and ads. That is a dozen invoices and scattered data.

Seliee does all of it in one window: you build the site, create and publish the content, run the ads and see the results in the same place.

| Area | Scale |
|---|---|
| Panel | 160 screens, 11 sidebar groups |
| Developers | **MCP server with 300+ tools, 800+ API endpoints** |
| AI Office | **16 agent roles, 50+ ready scenarios** |
| AI providers | 13 LLM providers plus a built-in Llama, and 15+ media AI services |
| Languages | 30 interface languages (including right-to-left), 75 content languages |

---

## AI Office: your AI marketing team

The AI Office is a pixel-art office where AI agents work like a real marketing team. **You give a goal, the agents do the work with the panel's own tools**, and anything that publishes, sends, spends money or deletes waits for your approval.

### How it works

1. Open **AI Office** from the header.
2. On **Run**, pick your websites, pick a **scenario** and type a goal, for example *"Prepare our winter sale"*.
3. Click **Assign**. The manager expands the scenario into tasks per website, per linked social account, per template, or once.
4. Agents of the right role pick up the tasks in order. Later steps wait for earlier ones.
5. Approval questions land in **Ask Me**. When the run is done, the manager writes a summary report.

### The team (16 roles)

| | | |
|---|---|---|
| Manager (orchestrator) | SEO analyst | Content writer |
| Ads specialist | Leads & customers | Websites & traffic |
| Creative (image & video) | Social media manager | Reports analyst |
| Inbox (DMs, e-mail & comments) | Web designer (SEO/GEO/AEO templates) | Data engineer |
| Visionary (viral content & trends) | Sourcing (suppliers) | Sales (offers, contracts & payments) |
| Call center (phone, SMS & WhatsApp) | | |

Hire more agents for a role with **Add agent**, and the work is split between them. If a role has no agent, the manager covers it. Click any character to see its tasks and activity, or ask it a question directly.

### Ready-made scenarios

A scenario is a list of steps, each with a role, a scope and tools. Highlights:

- **Campaigns and content:** Winter sale campaign, Weekly social media plan, Ride today's trends, Reply to social comments
- **SEO / GEO / AEO:** internal links, page speed, AI visibility checks, template redesign for SEO, GEO and AEO
- **Ads:** Check ad performance, Turn ads into a sales funnel, New ad (audience test to sales campaign)
- **Sales pipeline:** Offer on request, Contract after the offer is accepted, Payment link after the contract is accepted, Schedule a meeting
- **Leads and customers:** Collect and follow up leads, Chats to customers, Customer segments and win-back on WhatsApp
- **Messaging:** Answer customer messages, WhatsApp template audit, Weekly WhatsApp report, Telegram radar
- **Phone and SMS:** SMS campaign, Phone call campaign, Call center follow-up by phone, WhatsApp and SMS
- **Data:** Data freshness, Cross-source consistency, Anomaly detection, Tracking and UTM audit, Weekly KPI dataset
- **Ideas:** Idea workshop from viral and trends, Rising trend radar, New campaign concepts

### Make it yours

- **Custom scenarios:** open **New scenario**, name it, tick the steps you want from the step library and save. Run it or schedule it like a built-in one.
- **Skills:** give your team instruction files (`.md` or `.txt`) such as brand voice, writing rules and product facts. They apply to the whole team, a role, one agent or one scenario.
- **Schedules:** run any scenario hourly, daily or weekly, on chosen websites, with manual approval or auto-approve.
- **Seliee Voice:** talk to your team. Hold the mic or switch on hands-free, ask what happened, or tell it what to do. It asks *"Start this work?"* before anything starts.

### You stay in control

- **Ask Me:** anything that **publishes, sends, spends or deletes** waits for a yes. Approve lets the agent continue, reject skips the step. For social posts you can untick individual drafts.
- **Auto-approve never covers steps that spend money or delete data.** Those can only be approved on screen.
- **Emergency stop** cancels queued work and open questions.
- **Activity logs** record every run, tool call, message and approval.
- Reading data and preparing drafts never need approval.

---

## Multi-AI assistant layer

Seliee is not tied to one model. **Bring your own key** and pick the right AI per job, or even per agent.

**Text and reasoning (article writing, auto reply, AI Office agents):**
OpenAI  · Claude  · Gemini  · Perplexity  · xAI Grok  · DeepSeek  · Kimi  · Meta AI  · GLM  · MiniMax  · Groq  · Mistral  · Azure OpenAI  · built-in Llama or your own llama.cpp server

**Video, image, audio and voice:**
ElevenLabs  · Higgsfield AI  · Kling AI  · Seedance  ·  HeyGen  · Wan  · Runway  · PixVerse  ·  Veed  ·  Pruna  ·  FLUX  ·  Recraft  · Stability AI  ·  Bria  · Deepgram  ·  your own GPU server (CUDA)

What you can do with it:

- **AI Office agents:** assign an AI account to each agent, or use one for the whole team.
- **Auto reply:** answer WhatsApp, Instagram, Facebook, X and Telegram messages with text-match rules, an AI answer from your own account, or rules first and AI as fallback. Test a message with **Try it** before saving.
- **AI articles:** automatic articles in 75 languages with internal linking, plus agents that turn Google Trends and news into article orders.
- **AI visibility:** check whether OpenAI, Claude, Gemini and Perplexity answers mention your site.
- **Media:** AI video (UGC and promotion videos, auto captions), an image editor, and **Characters** (one AI look, then every angle, face, outfit and pose).
- **Phone:** an AI voice assistant that answers and places calls.

---

## MCP server

[Model Context Protocol](https://modelcontextprotocol.io) lets AI assistants such as Claude read your account data and take actions on your behalf. Seliee ships an MCP server with **300+ tools**.

### Connect in three steps

1. Open **MCP** from the profile menu (top right).
2. Click **Generate token**. The server address and token appear.
3. Copy the **Example configuration**. Your token is already filled in.

### Claude Code

```bash
claude mcp add --transport http selieeai <MCP_SERVER_URL> --header "Authorization: Bearer <MCP_TOKEN>"
```

Or paste the copied JSON into `.mcp.json` in your project root. Restart Claude Code and run `/mcp` to check that the `selieeai` server is connected.

### Claude Desktop

Node.js must be installed. Add this under **Settings > Developer > Edit Config** and fully restart Claude Desktop:

```json
{
  "mcpServers": {
    "selieeai": {
      "command": "npx",
      "args": [
        "mcp-remote",
        "<MCP_SERVER_URL>",
        "--header",
        "Authorization:${AUTH_HEADER}"
      ],
      "env": {
        "AUTH_HEADER": "Bearer <MCP_TOKEN>"
      }
    }
  }
}
```

### Claude and ChatGPT custom connectors

Custom connectors cannot send a token header. The MCP page offers a **single URL** option: paste it as the connector address and choose **No authentication**. The token is already inside the URL, so treat it like a password. Refreshing the token invalidates it.

### Good to know

- Tokens have an **expiry date**. Renew with **Refresh token** and update your configuration.
- Never share your token.
- Direct token-header connections to ChatGPT Desktop are not supported yet, because it has no field for a Bearer token. Use the single-URL option, Claude Code or Claude Desktop.

---

## API

Seliee exposes **800+ API endpoints**, covering the same areas as the panel: websites, pages, articles, collections, ads, social accounts and posts, leads, customers, payments, reports and more. Build your own dashboards, automations and integrations on top of it.

> API reference and examples: see [www.seliee.si](https://www.seliee.si) and the in-app **Docs** (header > Docs).

---

## Everything else in the panel

| Group | What you get |
|---|---|
| **Websites** | 4-step wizard, 11 website types, 41 sectors, templates, rules, redirects, domain check, Cloudflare DNS |
| **Content** | Pages, articles, collections, video and image editors, trends from Google, X, Instagram, Reddit, TikTok and YouTube |
| **SEO** | Google Indexer, keyword scanning, backlinks, PageSpeed, AI Visibility, Google Search performance |
| **Ads** | Meta, Google, LinkedIn, X and ChatGPT ads on one screen: campaigns, alert rules, search terms, negative lists, audiences |
| **Social** | WhatsApp Business, Instagram, Facebook, Telegram, TikTok, YouTube, LinkedIn and X: inbox, publishing, scheduling, insights |
| **Customers** | Multi-step lead forms, lead board, CRM, appointments, contracts and proposals, email inbox on your own domain |
| **Local** | Google Maps search and export, Google Business Profile |
| **Messaging** | SMS (Twilio, Plivo, Sinch, Infobip, Netgsm and more), phone calling campaigns, do-not-call list |
| **Payments** | Stripe, Mollie, PayPal, Adyen, Checkout.com, Payoneer, iyzico, PayTR, Revolut, Lemon Squeezy, Polar, Gumroad, Paddle |
| **Analytics** | 39 report widgets, Google Analytics, Yandex Metrica and Microsoft Clarity |

---

## Get started

1. Create your free account at **[www.seliee.si](https://www.seliee.si)**.
2. Claim your **free 50 tokens**: [seliee.si/r/lic804jq](https://seliee.si/r/lic804jq)
3. Add an AI account (OpenAI, Claude, Gemini, xAI or another provider) so your agents can think.
4. Open the **AI Office**, pick a scenario and give your team a goal.
5. Generate an **MCP token** to control Seliee from Claude.

---

<p align="center">
  <a href="https://www.seliee.si">www.seliee.si</a><br/>
  <sub>Made by <a href="https://www.neeblo.com">Neeblo LTD</a></sub>
</p>
