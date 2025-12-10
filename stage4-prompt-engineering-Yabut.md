# Stage 4 - Structured AI Prompt

Created by: Aldren Yabut

Role: Financial Analyst / Treasury Analyst

Audience: CFO / Directory of Treasury

# GOAL
Create a fully functional Excel workbook that models and compares three FX hedging strategies Forward Contract, Money Market Hedge, and Currency Options for a €4.5 million receivable due in 1 year. The spreadsheet must follow strict modeling, naming, color-coding, and auditability requirements.

# CONTEXT (GitHub)
This prompt should translate my Stage 2 specification and Stage 3 Excel logic into a complete, professional Excel model.

Use the following scenario description as the conceptual framework:

Our company expects to receive €4.5 million in 12 months, creating exposure to EUR/USD fluctuations. The objective is to evaluate hedging strategies that protect USD value while maintaining some upside potential.

# INPUT VARIABLES
FC_AMT = 4,500,000
Spot = 1.1566
Forward = 1.0890
r_USD = 4.80%
r_EUR = 3.50%
K_put = 1.16
K_call = 1.18
Premium_put = 0.017
Premium_call = 0.022
T_days = 365

# SPREADSHEET REQUIREMENTS
Use named ranges.
Yellow → Inputs / decision variables
Blue → Assumptions (interest rates, maturity, conventions)
Green → Formulas & calculations
Gray → Outputs, KPIs, final USD proceeds

# MODEL LOGIC
Forward_Hedge_USD = FC_AMT * F0_in

MM_EUR_PV = FC_AMT / (1 + R_FC)
MM_USD_Today = MM_EUR_PV * S0_in
MM_Final_USD = MM_USD_Today * (1 + R_USD)

For each S_T in sensitivity_range:
    Unhedged = FC_AMT * S_T
    PutPayoff = MAX(K_PUT - S_T, 0)
    CallPayoff = MAX(S_T - K_CALL, 0)
    Option_Result = Unhedged + PutPayoff - CallPayoff - (PREM_PUT + PREM_CALL)
    
# VERIFICATION
Must confirm:
- All named ranges exist and match required spelling
- Forward and MM hedges pass interest rate parity
- All formulas are visible and consistent
- Sensitivity table correctly references model cells
- All color-coding rules are met
- Provide a full formula map listing each key calculation

# EXPORT
Return a downloadable .xlsx Excel file containing:
- All calculations
- Sensitivity tables
- Charts
- Formatting
- Named ranges

# Completed Excel File
[FX_Hedging_Model (1).xlsx](https://github.com/user-attachments/files/24067201/FX_Hedging_Model.1.xlsx)


Full auditability```


# Why This Matters
You are learning how to convert domain knowledge into machine-readable instructions — a core skill for modern finance, treasury, risk, and analytics roles.
