# neXaQuant - Demo Script for HackNYU Presentation

**Duration: 3-5 minutes**

---

## Opening (30 seconds)

**[Show landing page]**

"Hi judges! We're presenting **neXaQuant** - an AI-powered trading intelligence platform that democratizes quantitative finance through multi-agent AI systems.

The problem? Retail traders lack access to sophisticated backtesting tools, and trading 'gurus' operate with zero accountability. We solve both."

---

## Demo Flow (3 minutes)

### Part 1: Natural Language Strategy Builder (60 seconds)

**[Navigate to Strategy Builder tab]**

"Let me show you how easy it is. Watch as I describe a trading strategy in plain English..."

**[Type in textarea]:**
```
Buy SPY when the 50-day moving average crosses above the 200-day moving average. 
Sell when it crosses below.
```

**[Click "Run Backtest"]**

"Behind the scenes:
- Our **ParsingAgent** uses OpenRouter to convert this into structured signals
- The **BacktestAgent** executes it against 5 years of real Yahoo Finance data
- The **RiskAgent** computes Sharpe ratio, CAGR, max drawdown, and volatility

And there's our results! This classic Golden Cross strategy returned [X]% CAGR with a Sharpe ratio of [Y]."

**[Highlight metrics cards]**

### Part 2: Solana NFT Minting (45 seconds)

**[Click "Mint as NFT on Solana"]**

"Now here's where it gets interesting. We can mint this strategy as an NFT on Solana.

**[Wait for success message]**

The NFT contains:
- Full strategy code
- All performance metrics
- Backtested results
- Immutable on-chain record

This enables a future marketplace where strategies become tradeable assets. Imagine buying a proven strategy from a quantitative fund - that's where we're headed."

### Part 3: Guru Accountability (60 seconds)

**[Navigate to Guru Analyzer tab]**

"Next, our Guru Analyzer. Social media is full of trading influencers making calls with zero accountability.

**[Click "Generate Sample Calls"]**

We extract their trading calls using AI, backtest each one individually, and give them an objective score.

**[Click "Analyze Guru Performance"]**

**[Show results]**

See? This guru gets a score of [X]/100 and an '[Badge]' badge. Each trade is analyzed:
- Trade #1: Sharpe 1.2, CAGR 15%
- Trade #2: Sharpe -0.3, CAGR -5%

Complete transparency. No more 'trust me bro' - just data."

### Part 4: Tech Stack (30 seconds)

**[Navigate to NFT tab, scroll to Tech Stack]**

"Quick tech overview:
- **Multi-Agent AI**: Specialized agents for parsing, backtesting, scoring via OpenRouter
- **Solana Integration**: Strategy NFTs minted on devnet with full metadata
- **Real Market Data**: Yahoo Finance integration for accurate backtesting
- **Agent Marketplace Ready**: Foundation for autonomous buyer/seller negotiations

All built in 48 hours at this hackathon."

---

## Closing - Sponsor Challenges (30 seconds)

**[Show footer badges]**

"We're hitting four sponsor challenges:

1. **Aristotle AI Agent**: Multi-agent system with memory, reasoning, and specialized tasks
2. **OpenRouter**: Multi-model routing for optimal performance per task
3. **Solana**: NFT minting with on-chain strategy metadata
4. **Visa Agent Marketplace**: Foundation for autonomous agent negotiations

Plus we registered **neXaQuant.tech** for the MLH domain challenge."

---

## Q&A Prep

### Expected Questions:

**Q: "How do you prevent overfitting in backtests?"**
A: "Great question. We use out-of-sample testing periods and walk-forward analysis. Future versions will include Monte Carlo simulations and regime detection to avoid curve-fitting."

**Q: "What's your business model?"**
A: "Freemium: Basic backtesting free, premium features ($10/mo) for advanced strategies, NFT marketplace takes 2.5% transaction fee. B2B: License to brokers/platforms."

**Q: "How do you handle API costs at scale?"**
A: "We cache LLM responses, use smaller models for simple tasks (Llama for code generation vs GPT-4 for reasoning), and batch process during off-peak hours. Projected cost: $0.05 per backtest."

**Q: "Security concerns with executing AI-generated code?"**
A: "We don't execute arbitrary code. The AI generates a structured JSON signal plan, then our sandboxed Python engine runs it. No eval(), no exec() - just safe pandas operations."

**Q: "Why Solana over Ethereum?"**
A: "Speed and cost. Strategy metadata can be large (100KB+). On Ethereum that's $50-100 per mint. On Solana it's $0.001. Plus 400ms finality for instant minting."

**Q: "Real guru analysis - legal issues?"**
A: "We don't identify individuals without consent. Users can analyze their own transcripts or use anonymized public data. It's educational analysis, protected speech."

---

## Backup Demo (If API Fails)

"Quick note: We have a demo mode with mock AI responses if the API is slow. The full system works identically - in production we'd use OpenRouter's enterprise tier with guaranteed SLAs."

**[Use Generate Sample Calls - guaranteed to work]**

---

## One-Liner Pitch

"neXaQuant democratizes quantitative finance by letting anyone describe trading strategies in English, get institutional-grade backtests in seconds, and mint proven strategies as tradeable NFTs on Solana - all powered by a multi-agent AI system."

---

## Visual Flow

```
Landing Page
    ↓
Strategy Builder (show typing + backtest)
    ↓
Results (highlight metrics)
    ↓
Mint NFT (show success)
    ↓
Guru Analyzer (generate sample)
    ↓
Results (show score + badge)
    ↓
Tech Stack (quick overview)
    ↓
Sponsor Challenges (show relevance)
```

---

## Pro Tips

1. **Have backup data loaded**: Pre-run a backtest before presenting
2. **Use stable internet**: Test API beforehand
3. **Practice transitions**: Smooth tab switching
4. **Emphasize agents**: Judges love multi-agent systems
5. **Show personality**: The gradient UI shows we care about UX
6. **Be confident about MVP scope**: "This is day 2, imagine month 2"

---

## Closing Impact Statement

"In a world where retail traders lose billions to scams and false promises, neXaQuant brings transparency, accountability, and institutional tools to everyone. We're not just building an app - we're building a movement toward democratized, data-driven investing.

Thank you!"

**[Smile, pause for questions]**