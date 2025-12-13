# Stage 5 – Final Analysis & Recommendation (6 Points)
Created by: [Aldren Yabut]
Updated by: [Aldren Yabut]
Date Created: [December 12, 2025]
Date Updated: [December 12, 2025]

## Goal
Deliver a polished, executive-ready memo or slide deck summarizing your hedge analysis and recommending the best strategy. This combines quantitative rigor, interpretation, communication, and forward-looking perspective — exactly what senior finance leaders expect from analysts.

---

# Deliverable Requirements (1-2 page .md file uploaded to GitHub)

Must include: 
https://github.com/aldrenyabut/Aldren-Yabut-Fin-321-/blob/main/stage4-prompt-engineering-Yabut.md 

---

## A. Exposure Summary
The company is exposed to a €4.5 million million EUR receivable scheduled for settlement in 1 Year. This foreign-currency exposure creates FX risk, if the EUR depreciates against the USD, the USD value of the receivable falls, reducing expected cash inflows. Conversely, EUR appreciation increases USD receipts, but leaves the company exposed to unfavorable downside moves. Unhedged FX moves could materially impact USD cash flows and budget forecasts for the period.

---

## B. Summary of Hedge Outcomes
The three hedging strategies produce different risk–return profiles:

Forward Hedge:
Locks in a fixed USD amount at maturity, fully eliminating FX uncertainty. The USD proceeds are known in advance, providing maximum budget and cash-flow certainty.

Money Market Hedge:
Delivers a USD outcome very similar to the forward hedge. Results are effectively fixed, with small differences driven by interest rate differentials rather than FX movements.

Option Hedge:
Provides downside protection while preserving upside potential. If the EUR weakens, losses are limited; if the EUR strengthens, the firm can benefit from favorable FX movements. However, this flexibility comes at the cost of an upfront option premium, which reduces net proceeds.

Key Insight:
Forwards and money market hedges maximize certainty but eliminate upside, while options trade some certainty for flexibility and potential gains.

---

## C. Sensitivity Interpretation
EUR Depreciation (EUR weaker vs USD):

Forward & MM hedges: Lock in USD receipts, eliminating downside risk.

Put option: Gains value; downside is capped at the strike, but net benefit is reduced by the premium.

EUR Appreciation (EUR stronger vs USD):

Forward & MM: No benefit from favorable movements; sell at pre-set rate.

Call options / Put option with FX structure: Allow participation in positive moves, with limited loss risk (premium).

Key differences:

Forwards & MM offer certainty and cost-efficiency.

Options introduce optional payoff structures, valuable if the company expects favorable directional moves but wants defined risk limits. 

---

## D. Strategic Recommendation
Recommended Hedge: Forward Hedge

Reasoning:

Cash flow stability: Forwards guarantee USD receipts of $(USD_Forward), aiding forecast precision.

Low operational complexity: Simple execution compared to money market borrowing.

Cost: Zero upfront premium (unlike options), improving budget forecasting.

Risk profile: Best fit for firms prioritizing certainty over optionality.

If the company were willing to pay a premium for optional upside, a structured option hedge (put + limited call) could be layered to balance cost and flexibility but given current risk tolerances and strategic emphasis on predictable budgeting, the forward dominates.

---

## E. Executive Justification
This hedge aligns with management goals of cash flow stability and analytic simplicity. By locking in a forward rate, treasury removes FX uncertainty on a material receivable, enabling more reliable budgeting and financial planning.

Liquidity impact: No cash outlay today (aside from standard settlement), preserving working capital.

Premium considerations: Avoids option premium costs, which reduce net receipts.

Optionality trade-off: Foregone upside is acceptable given risk-averse corporate strategy.

Accounting (Optional): Forwards qualify for cash-flow hedge accounting with proper documentation, reducing income statement volatility (see hedge accounting guides).

---

# Extra Credit (2 points): Areas for Further Study & Improvement

---

## 1. Claude Skills (Automation & Live Data Integration)
A Claude Skill could automate this hedge model by pulling live FX spot rates and interest rates directly into the spreadsheet. This would allow the hedge outcomes to update automatically as market conditions change.

---

## 2. OpenAI Codex / Code Interpreter
OpenAI Codex could convert the spreadsheet logic into Python to validate formulas, rebuild the model programmatically, and run advanced sensitivity. Codex reduces operational risk, limits formula errors, and improves reproducibility. 

---

## 3. Claude Code / Multi-File Reasoning
Claude’s ability to read and update multiple files simultaneously, enhancing workflow efficiency by maintaining consistency across specifications, models, and written analysis. Multi-file reasoning allows the model, documentation, and results to stay aligned as changes are made, reducing version mismatches and improving overall model governance. 


### Why It Matters in Finance
Finance relies on:
- Hedge accounting documentation  
- Internal controls  
- Data lineage  
- Multi-user workflows  

### How Collaboration Works
- Branching for parallel work  
- Pull Requests for review  
- GitHub Actions for automated testing/validation  
- Issue tracking for model updates  

In this project, Stage 2 defined the hedge specifications, Stage 3/4 translated those specs into structured models and AI prompts, and Stage 4 generated the final spreadsheet. By versioning the specifications, model templates, and AI prompts in GitHub, the entire hedge workflow becomes reproducible, transparent, and auditable, enabling consistent model regeneration and review.

---

## 5. Accounting / Audit Integration
FX hedges affect financial reporting depending on whether gains and losses flow through OCI or P&L. Proper hedge accounting requires clear documentation, effectiveness testing, and reproducible models. Versioning specifications, models, and AI prompts in GitHub creates a transparent audit trail, supports internal controls, and provides reliable evidence for audit review.

---

# Expanded Career Insight

This project builds skills used in:

### Corporate Treasury
- Exposure management  
- Hedge design & performance testing  
- AI-augmented scenario analysis  

### Investment Banking
- Cross-border deal modeling  
- FX-sensitive valuation adjustments  

### FP&A
- Cash flow forecasting  
- Scenario building  
- Budget risk assessment  

### Accounting & Audit
- OCI/P&L documentation  
- Hedge effectiveness proof  
- Version-controlled models  
- Audit trail creation  

### Data, Analytics, & AI Roles
- Spec → model → prompt → automation  
- GitHub collaboration  
- AI-assisted financial modeling  
- Data governance & reproducibility  

---

# Why This Matters
This multi-stage journey reflects workflows used at:
- BlackRock  
- Tesla  
- McKinsey  
- Big 4 Audit firms  
- Quant funds  
- Corporate treasury teams  
- Fintech / robo-advisors  

You are demonstrating:
- Analytical reasoning  
- Automation fluency  
- Model governance  
- Financial decision leadership  
- Technical communication  

## This is a portfolio-ready artifact for internships, jobs, and graduate programs!
