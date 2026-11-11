# MILION

<p align="center">
  <img src="public/milion-logo.svg" alt="MILION mascot logo" width="120" />
</p>

<p align="center"><strong>Beyond Every Strategy.</strong></p>

MILION is a trading strategy creation, backtesting, and publishing platform. It gives traders a place to build their own strategies, evaluate them using historical market data, and publish them for free or monetize their work while keeping their strategy rules private.

> **Build. Backtest. Publish. Earn.**

---

## 1. Brand Identity

### Brand name

**MILION**

MILION is the product name. The brand represents the idea of millions of possibilities, strategies, and ideas that can be created by traders.

### Tagline

**Beyond Every Strategy.**

The tagline communicates that MILION is more than a strategy tool: it is an ecosystem for creating, testing, sharing, and monetizing trading strategies.

### Brand personality

- Modern and technology-driven
- Clear, confident, and trustworthy
- Creator-focused
- Data-oriented
- Simple and approachable

---

## 2. Logo and Mascot

The MILION identity uses an independent mascot symbol rather than a lettermark.

### Primary logo

The approved mascot asset is stored at:

`public/milion-logo.svg`

![MILION mascot logo](public/milion-logo.svg)

### Approved mascot direction

- A simple, white, four-pointed star.
- Soft, rounded, symmetrical points.
- Two small black oval eyes.
- No letters, initials, orbit rings, crystals, diamonds, rockets, or additional decorative symbols.
- The mascot must remain recognizable at small sizes.

The mascot is intended to work as the primary brand symbol and as a friendly character throughout the product.

### Animation direction

Keep animation subtle and minimal:

- Blinking eyes
- Gentle floating
- Small bounce or scale movement for loading and feedback states

Do not add orbiting objects or extra ornaments unless the brand direction is explicitly revised.

### Logo usage

- Use the white mascot on dark backgrounds.
- Use a suitable contrasting version on light backgrounds while preserving the same shape and facial features.
- Keep clear space around the symbol.
- Do not stretch, rotate, distort, or add effects that change its identity.

---

## 3. Product Vision

MILION enables traders to become strategy creators.

A user should be able to:

1. Create a trading strategy.
2. Backtest it using historical market data.
3. Review transparent performance results.
4. Choose whether to publish it for free or sell access.
5. Keep the strategy's underlying rules and parameters private when desired.

MILION combines three core product areas:

- **Strategy Builder** — create and configure trading strategies.
- **Backtesting Platform** — evaluate strategies against historical market data.
- **Strategy Marketplace** — discover, publish, share, and purchase strategies.

---

## 4. Core Product Principles

### 4.1 Build your own strategy

Users create strategies by defining their trading logic, such as:

- Indicators and indicator parameters
- Entry conditions
- Exit conditions
- Take-profit and stop-loss rules
- Other supported risk and position settings

The strategy builder should make the process understandable without hiding important configuration details.

### 4.2 Backtest with historical market data

Backtests must use real historical market data from supported exchanges and clearly identify the dataset and test period.

Performance reporting should be transparent and reproducible. Depending on the strategy and market data available, reports should include:

- Total return and net return
- Win rate
- Total trades
- Maximum drawdown
- Profit factor and expectancy
- Entry and exit timestamps and prices
- Trading fees
- Slippage assumptions
- Funding costs when applicable
- Strategy settings and backtest period

Backtest results are historical simulations, not guarantees of future performance.

### 4.3 Publish without exposing the strategy formula

A creator can make performance information public while keeping the underlying strategy implementation private.

Public performance information should help visitors evaluate a strategy. Private strategy logic may include:

- Entry and exit conditions
- Indicator configuration and parameters
- Internal rules and source implementation

The creator chooses what information is visible, subject to MILION's minimum transparency requirements.

### 4.4 Free or paid publishing

Creators choose how to publish their strategies.

**Free strategy**
- Listed in the marketplace at no cost.
- Helps creators share their work and build a reputation.
- The creator chooses whether the strategy rules are public or private.

**Paid strategy**
- The creator sets the price or supported access model.
- Buyers receive the access rights described on the strategy listing.
- MILION may collect a platform fee from successful transactions.
- The creator retains control over the strategy's publication and pricing, subject to platform rules.

A paid listing must clearly explain what the buyer receives. Purchasing access must not automatically imply ownership of the strategy's intellectual property.

---

## 5. Privacy and Access Principles

Strategy privacy is a core product requirement, not merely a hidden frontend section.

- Private strategy logic must not be sent to users who do not have permission to access it.
- Access decisions must be enforced by the backend.
- Public performance reports must not reveal private formulas or parameters.
- Buyers must only receive the capabilities included in the creator's chosen license or access model.
- The platform should make copying and unauthorized redistribution harder, while acknowledging that no system can completely prevent copying once a person has legitimate access to strategy logic.

---

## 6. Hero Section

The hero section introduces MILION and explains its value immediately.

### Approved hero content

**Brand name**

MILION

**Tagline**

Beyond Every Strategy.

**Description**

> Create your own trading strategies, backtest them with historical market data, and publish them for free or monetize your edge while keeping your strategy rules private.

### Primary actions

- **Explore Strategies** — discover strategies published by other creators.
- **Build a Strategy** — start creating a personal trading strategy.

### Hero composition

Recommended order:

1. MILION mascot/logo
2. MILION brand name
3. Tagline: “Beyond Every Strategy.”
4. Approved product description
5. Primary CTA: “Explore Strategies”
6. Secondary CTA: “Build a Strategy”
7. Subtle mascot animation or product visual

### Hero design direction

- Clean, modern, and focused.
- Make the brand name and tagline easy to recognize.
- Keep the description readable and avoid excessive text.
- Make the two main actions visually distinct.
- Use the approved four-point star mascot without introducing a different logo concept.
- The hero should communicate creation, validation, and monetization—not promise trading profits.

---

## 7. Product Flow

The intended high-level user journey is:

```text
Create Strategy
      |
      v
Configure Trading Rules
      |
      v
Run Historical Backtest
      |
      v
Review Performance
      |
      v
Choose Publishing Mode
      |
      +----------------------+
      |                      |
      v                      v
 Publish for Free       Publish as Paid
      |                      |
      +----------+-----------+
                 |
                 v
        Strategy Marketplace
```

---

## 8. Initial Product Scope

The initial product should focus on a reliable end-to-end creator workflow:

1. Brand identity and landing page.
2. Strategy discovery page.
3. Strategy builder.
4. Historical backtesting engine.
5. Transparent backtest report.
6. Private strategy storage and access control.
7. Free and paid publishing options.
8. Creator profile and strategy management.

Features and implementation details beyond this scope remain open for future product planning.

---

## 9. Product Statement

**MILION is where trading ideas become testable strategies—and where strategy creators can share their work or turn it into income.**

**Build. Backtest. Publish. Earn.**

---

## 10. Project Status

This README records the current product direction and approved brand/hero decisions. It is a planning document, not a claim that the described features have already been implemented.

Design, architecture, marketplace rules, buyer licensing, payment flows, and backtesting specifications will be detailed and confirmed as the project progresses.
