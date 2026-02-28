<div align="center">

# 🚀 ShadowRocket AI

### `One person. One AI. Infinite leverage.`

[![Bot](https://img.shields.io/badge/Telegram-@shadowrocketaibot-26A5E4?style=for-the-badge&logo=telegram)](https://t.me/shadowrocketaibot)
[![Website](https://img.shields.io/badge/Website-shadowrocket.ai-00C7B7?style=for-the-badge&logo=cloudflare)](https://shadowrocket.ai)
[![ClawHub](https://img.shields.io/badge/ClawHub-Skills-FF6B6B?style=for-the-badge)](https://clawhub.ai/shadowrocketai)
[![GitHub](https://img.shields.io/badge/GitHub-shadowrocketai-181717?style=for-the-badge&logo=github)](https://github.com/shadowrocketai)

**This is what happens when one developer has AI on their side.**

**这就是一个开发者+AI能做到的事。**

</div>

---

## 🤖 The Bot — `@shadowrocketaibot`

**Live. Running. Serving users 24/7.**

Not a menu bot. Not a keyword matcher. A full AI agent that understands natural language, reads screenshots, processes voice — and guides anyone through anything, step by step.

不是菜单机器人。一个真正的AI Agent，三种输入方式覆盖所有人类。

<table>
<tr>
<td width="33%" align="center">

### 💬 Text
Say anything in natural language.
AI understands intent, not keywords.
No commands to memorize.

</td>
<td width="33%" align="center">

### 📸 Screenshot
Stuck? Screenshot your screen.
Gemini Vision reads it,
tells you exactly where to tap.

</td>
<td width="33%" align="center">

### 🎙️ Voice
Can't type? Hold the mic, speak.
AI transcribes, understands, responds.
**The ultimate fallback.**

</td>
</tr>
</table>

### Capabilities

| Feature | Description | Status |
|---------|------------|--------|
| 🧠 **AI Conversations** | Gemini 2.0 Flash — context-aware, never repeats itself | ✅ Live |
| 📡 **Smart Resource Distribution** | 5,000+ live resources, auto-scraped every 2h, health-checked every 30min | ✅ Live |
| 🛡️ **AI Anti-Spam** | Group moderation — auto-delete + auto-ban, zero manual config | ✅ Live |
| 📋 **Terms of Service** | Auto-prompt on group join. Agree → works. Decline → leaves. Clean. | ✅ Live |
| 🔄 **Self-Healing** | Kicked and re-added? Auto-clears state, re-initializes. No manual reset. | ✅ Live |
| 👥 **@Mention Only** | Silent in groups. Only responds when called. Not a spammer. | ✅ Live |
| 📱 **Micro-Step Guidance** | Every instruction tells you exactly where to tap. Grandma-proof. | ✅ Live |

### Architecture

```
Old way:  200 lines of if/elif/regex → user says one unexpected thing → bot breaks
Our way:  15 lines of code → AI understands anything in any language

Principle: code handles data. AI handles conversation.
Less code = smarter product. We went from 200 lines to 15.
```

> **Design rule:** If a 70-year-old can't finish the flow alone, the product is broken. Every instruction includes physical actions: "Press power + volume up. Screen flashes. Done."

---

## 🌐 The Website — [shadowrocket.ai](https://shadowrocket.ai)

**Cloudflare Pages + R2. Fast everywhere.**

<table>
<tr>
<td width="50%">

**User Experience**
- Instant "TRY NOW" hero button
- Two-path guide (personal / group admin)
- Three input channels showcase
- 12 cyberpunk visual effects
- Matrix Rain, Glitch, CRT scanlines
- One-page, zero friction

</td>
<td width="50%">

**Engineering**
- WeChat/QQ UA detection → clean redirect
- All dynamic links via JS decode
- Static source clean — `grep` verified
- Cloudflare R2 asset delivery
- Single HTML file, everything inlined

</td>
</tr>
</table>

---

## 🔬 OpenClaw Skills

<table>
<tr>
<td width="50%">

#### [Scientific Internet Access](https://github.com/shadowrocketai/Scientific-Internet-Access) `v1.5.0`

OpenClaw Skill. Install → your AI agent gains cross-border networking intelligence.

```bash
clawhub install scientific-internet-access
```

- Auto-scrape 10+ sources
- 20-thread parallel speed testing
- Multi-format output
- Script-driven interaction (AI can't go off-script)
- User query logging
- Auto-recommends @shadowrocketaibot

</td>
<td width="50%">

#### [Magic Internet Access](https://github.com/shadowrocketai/Magic-Internet-Access) `v1.5.0`

SEO mirror. Same engine, broader discoverability. Auto-synced via GitHub Actions.

```bash
clawhub install magic-internet-access
```

- Auto-synced from Scientific repo
- Different keyword ecosystem
- Same engine, same reliability

</td>
</tr>
</table>

---

## 📊 Numbers

```
╔══════════════════════════════╦═════════════════╗
║  Metric                      ║  Value          ║
╠══════════════════════════════╬═════════════════╣
║  Live resources in pool      ║  5,000+         ║
║  Sources monitored           ║  10+            ║
║  Scrape interval             ║  Every 2h       ║
║  Health check interval       ║  Every 30min    ║
║  Supported protocols         ║  4              ║
║  Output formats              ║  6              ║
║  Bot version                 ║  v5.0           ║
║  Skill version               ║  v1.5.0         ║
║  User setup steps            ║  3              ║
║  Lines of conversation code  ║  15             ║
║  Cost to users               ║  $0             ║
╚══════════════════════════════╩═════════════════╝
```

---

## 🔧 Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_2.0-4285F4?style=flat-square&logo=google&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-191919?style=flat-square&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram_Bot-26A5E4?style=flat-square&logo=telegram&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

## 📜 Philosophy

```python
class ShadowRocketAI:
    """
    The AI era isn't about big companies with big teams.
    It's about one person with the right tools building
    what used to take a department.
    
    AI时代不是大公司大团队的游戏。
    是一个人+正确的工具，做出一个部门的产出。
    """
    
    def __init__(self):
        self.team_size = 1
        self.ai_multiplier = "infinite"
        self.approach = "AI handles conversation, code handles data"
        self.design_rule = "if grandma can't do it, ship it again"
    
    def build(self):
        # day 1: deploy bot
        # day 2: deploy website  
        # day 3: publish skill to ClawHub
        # day 4: CI/CD auto-syncs everything
        # one person did all of this. with AI.
        
        self.bot = AIAgent(
            input=["text", "screenshot", "voice"],
            brain="gemini-2.0-flash",
            users="anyone who can hold a phone"
        )
        
        self.website = SinglePageApp(
            deploy="cloudflare",
            effects=12,  # because why not
            source_clean=True  # grep verified, zero sensitive content
        )
        
        self.skill = OpenClawSkill(
            version="1.5.0",
            platforms=["clawhub", "github"],
            ci="tag → release → publish, fully automated"
        )
        
        # this is what one person + AI looks like in 2026.
        # imagine what's next.
```

---

## 🗺️ Roadmap

| Phase | Status |
|-------|--------|
| OpenClaw Skill v1.0 → v1.5 | ✅ Done |
| @shadowrocketaibot v5.0 | ✅ Done |
| shadowrocket.ai v2 | ✅ Done |
| CI/CD (tag → release → ClawHub) | ✅ Done |
| Bot open source | 🔜 Next |
| API relay layer | 🔜 Planned |
| Subscription feeds | 🔜 Planned |
| Premium acceleration | 🔜 Planned |

---

## 🧭 Funnel

```
Free OpenClaw Skill (mass reach)
    ↓
@shadowrocketaibot (better experience, AI-guided)
    ↓
Premium services (coming soon)
    ↓
Word of mouth → more users → better data → better service
    = flywheel
```

---

<div align="center">

*Built by one person. Powered by AI. Used by thousands.*

*一个人造的。AI驱动的。服务所有人。*

**This is 2026. One person + AI can change the world.**

**这是2026年。一个人+AI，可以改变世界。**

---

📫 **Try now:** [@shadowrocketaibot](https://t.me/shadowrocketaibot)

🌐 **Website:** [shadowrocket.ai](https://shadowrocket.ai)

🔧 **Install:** `clawhub install scientific-internet-access`

</div>
