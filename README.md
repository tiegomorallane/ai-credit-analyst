# AI Credit Analyst

An AI-assisted SME credit assessment platform for analysing borrower financials, calculating core credit ratios, flagging risks, comparing scenarios, and producing a structured credit memo.

## Why this project exists

Traditional SME credit assessment is often slow, document-heavy, and inconsistent. This project demonstrates how modern software and AI can support analysts with repeatable calculations, transparent risk flags, and better decision documentation.

> This repository is a portfolio project. It uses synthetic demonstration data only and is not a substitute for professional credit judgement.

## Planned capabilities

- Create and manage borrower assessments
- Capture historical and forecast financial information
- Calculate profitability, leverage, liquidity, and debt-service metrics
- Generate transparent rule-based risk flags
- Compare base, upside, and downside scenarios
- Generate an AI-assisted draft credit memo
- Export an assessment report to PDF
- Maintain an auditable record of assumptions and outputs

## Target users

- SME credit analysts
- Private-credit and alternative-finance teams
- Business bankers
- Funding advisers
- Finance professionals evaluating borrower affordability

## Technology stack

- **Frontend:** Next.js, TypeScript, Tailwind CSS
- **Backend:** Python, FastAPI, Pydantic
- **Database:** PostgreSQL
- **AI layer:** provider-agnostic LLM service
- **Testing:** Pytest and frontend test tooling
- **Infrastructure:** Docker, GitHub Actions

## Repository structure

```text
apps/
  api/        # FastAPI service
  web/        # Next.js application
docs/
  architecture.md
  product-requirements.md
  credit-methodology.md
.github/
  workflows/
tests/
```

## Credit metrics in scope

The MVP will calculate and present metrics such as:

- Revenue growth
- Gross and operating margins
- EBITDA margin
- Current ratio
- Quick ratio
- Debt-to-equity
- Net debt-to-EBITDA
- Interest coverage
- Debt-service coverage ratio
- Operating cash-flow conversion

All calculated outputs will show their underlying inputs and formulas so that the system remains explainable.

## MVP roadmap

### Phase 1 — Foundation

- Monorepo structure
- FastAPI health endpoint
- Next.js dashboard shell
- Shared environment configuration
- Docker development setup
- Continuous integration

### Phase 2 — Credit engine

- Financial input models
- Ratio calculation service
- Risk-rule engine
- Scenario calculations
- Automated tests

### Phase 3 — Analyst workflow

- Borrower assessment form
- Results dashboard
- Risk-flag explanation
- Credit memo generation
- PDF export

### Phase 4 — Portfolio polish

- Synthetic demo company
- Screenshots and architecture diagram
- Public deployment
- Expanded documentation
- End-to-end tests

## Responsible use

- Never upload confidential client information to the public demo.
- AI-generated outputs must be reviewed by a qualified human.
- Credit decisions must not be made solely from automated scores.
- Model assumptions, calculations, and limitations must remain visible.

## Author

Built by **Tiego Morallane** as part of a finance and AI engineering portfolio focused on practical financial infrastructure.

## Status

🚧 Active development
