**Research Brief — Meridian Solar IPP and the Financing of Kenyan Infrastructure by Domestic Institutional Capital**

**Purpose:** Analytical backing for (i) the accompanying project finance model and (ii) the infrastructure fund, pension scheme and SACCO case studies

**Note on data:** All companies, funds and figures in the case are fictional. Where this brief cites live Kenyan regulation, it does so to test the case's simplified rules against the current statutory position.

# Part 1 — The Solar IPP: are the model's assumptions defensible?
## 1.1 Summary judgement
The technical assumptions in the base case are individually plausible. The problem is not any single input; it is that the combination of a USD 0.075/kWh tariff and USD 60.0m of capital cost produces an unlevered IRR of **6.07%** against a prescribed 10% discount rate, and an NPV of **USD (15.68)m**. The model is internally sound and recalculates cleanly; the project is simply not viable on these terms.

## 1.2 Resource and technical assumptions
**Net capacity factor of 21%.** This implies a specific yield of 0.21 × 8,760 = **1,840 kWh per kWp per year**, or roughly 5.0 kWh/kWp/day. For an equatorial, high-altitude, low-humidity site — this sits in a credible band for a fixed-tilt utility-scale array. It is neither aggressive nor conservative. *Source to attach: Global Solar Atlas / World Bank ESMAP site-specific yield data. I was unable to verify a site-specific figure within this case study and have flagged it rather than cite a number I cannot source.*

**No panel degradation.** This is the single least defensible technical assumption in the model, and it is stated explicitly rather than buried. Crystalline silicon modules typically degrade 0.4–0.5% per year, which over a 20-year PPA compounds to roughly 8–9% of lost output by the final year. The model therefore **overstates late-life CFADS**. Because the debt is sized off early-year cash flow the effect on debt capacity is modest, but it flatters the project IRR and it would not survive a lender's technical adviser.

**No inverter replacement.** Inverters have a shorter design life than modules, typically requiring replacement around years 10–12. No maintenance capex or replacement reserve is modelled because the case gives none. In a live mandate this would be a funded reserve and a genuine drag on distributions in the second half of the PPA.

**8,760 hours per year.** Correct and uncontroversial.

## 1.3 Capital cost
USD 60.0m for 50 MW is **USD 1.20m per MW, or USD 1.20 per watt**. That is toward the upper end of contemporary utility-scale solar benchmarks, which is not unreasonable once grid connection, land, development cost, and the risk premium attaching to a first-of-kind IPP in the market are included — but it is the variable with the most room to move. The model shows that cutting capex to **USD 42.03m** (a 30.0% reduction) alone brings the project to a 10% return. *Source to attach: IRENA, Renewable Power Generation Costs (latest edition), for the global and African utility-scale PV cost benchmark. Not verified within this case study.*

Capex is also the more controllable lever. The sponsor can re-tender the EPC scope; it cannot re-tender the weather.

## 1.4 Revenue assumptions
**Tariff of USD 0.075/kWh, escalating 1.5% annually from Year 2, under a 20-year take-or-pay PPA.** The take-or-pay structure removes volume risk entirely, which is why the model assumes 100% of net generation is sold and carries no working capital. That is a legitimate simplification for a deemed-generation contract.

The critical observation is what the model's breakeven analysis actually represents. The breakeven tariff of **USD 0.1009/kWh** — the tariff at which NPV is zero at a 10% discount rate — **is the project's levelised cost of energy at that cost of capital**. The offered tariff is 34.5% below it. This is not a modelling artefact or a marginal shortfall; the contract price is well under the cost of production.

**Escalation mismatch.** Tariff escalates at 1.5% while operating costs escalate at 3.0%. Margin therefore compresses every year of the PPA. Over twenty years this is a meaningful structural erosion and it is a term worth contesting in negotiation: indexing the tariff to the same basis as costs would materially improve the back end of the cash flow profile.

## 1.5 Operating cost
USD 1.2m in Year 1 is **USD 24,000 per MW per year, or 2.0% of capital cost** — a conventional benchmark for utility-scale solar O&M, insurance, land lease and administration. Solar has no fuel cost, which is why the Year 1 EBITDA margin reaches 82.6%. The assumption is reasonable.

## 1.6 Fiscal assumptions
Straight-line depreciation over 20 years matching the PPA term, and a 30% corporate rate with tax paid in the year incurred, are both as specified. Two judgements were made where the case is silent and both are stated on the model's assumptions tab: tax is computed on an **unlevered** basis so that CFADS is clean and pre-financing (the interest tax shield is credited separately to equity), and no loss carry-forward mechanic is modelled because no taxable loss arises in the base case.

## 1.7 What the model concludes
| **Metric**                       | **Base case**  |
|:---------------------------------|:---------------|
| Project (unlevered) IRR          | 6.07%          |
| NPV at 10%                       | USD (15.68)m   |
| Simple payback from COD          | 12 years       |
| Breakeven tariff (= LCOE at 10%) | USD 0.1009/kWh |
| Breakeven capacity factor        | 28.2%          |
| Breakeven capex                  | USD 42.03m     |

Across a 7×7 sensitivity of capacity factor against tariff, only **3 of 49 scenarios** clear a 10% return, and each requires simultaneous outperformance on both variables. The conclusion is robust to the sensitivity range, not an artefact of the central case.

# Part 2 — Financing Kenyan infrastructure with domestic institutional capital
## 2.1 The structural case
Kenya's domestic institutional capital pools — occupational pension schemes and deposit-taking SACCOs — hold long-dated, locally denominated liabilities. Infrastructure assets generate long-dated, contractually escalating, locally denominated cash flows. On paper the match is close to ideal, and it avoids the currency mismatch that has historically made foreign-financed African infrastructure fragile: a project earning shillings and servicing dollars carries an FX risk that no amount of structuring fully removes.

The practical obstacles are three. Ticket sizes are large relative to individual schemes. Project-level credit assessment requires specialist capability that most trustee boards do not have in-house. And the assets are illiquid in markets where secondary trading is thin. A pooled, government-anchored vehicle such as the Domestic Infrastructure Fund is a reasonable institutional answer to all three — it aggregates tickets, centralises credit skill, and standardises documentation.

## 2.2 Pension schemes and the RBA constraint — a material divergence
The case sets a simplified RBA maximum of **30%** for infrastructure. **The current statutory position is materially tighter.** Under Table G of the First Schedule to the Retirement Benefits Regulations, the relevant category — item 14, *debt instruments for the financing of infrastructure or affordable housing projects approved under the Public Private Partnerships Act, 2013* — carries a maximum of **10%** of the aggregate market value of scheme assets.

Every other limit in the case matches Table G exactly:

| **Asset class**          | **Pack limit** | **Current RBA Table G**                                  | **Match** |
|:-------------------------|:---------------|:---------------------------------------------------------|:----------|
| Government securities    | 90%            | 90% (100% for schemes receiving statutory contributions) | Yes       |
| Quoted equity            | 70%            | 70%                                                      | Yes       |
| Immovable property       | 30%            | 30%                                                      | Yes       |
| Guaranteed funds         | 100%           | 100%                                                     | Yes       |
| Offshore                 | 15%            | 15%                                                      | Yes       |
| Private equity           | 10%            | 10% (private equity & venture capital)                   | Yes       |
| Cash and demand deposits | 5%             | 5%                                                       | Yes       |
| **Infrastructure**       | **30%**        | **10% (item 14)**                                        | **No**    |

This matters for the Northfield recommendation. The pension case allocates **10%** to infrastructure via the DIF — held well below the case's 30% ceiling for portfolio-construction reasons, principally that the DIF does not diversify the sovereign-correlated concentration the scheme already carries. That allocation is, coincidentally but usefully, **compliant under the real 10% statutory limit as well as the simplified one**. Had the design used the headroom the case appears to permit, it would have been unlawful in practice.

A second regulatory subtlety is worth flagging. Item 14 covers *debt instruments*. The DIF as described provides senior debt to projects, so a scheme's exposure would most naturally sit in that category. An equity interest in an infrastructure fund would not obviously qualify and could fall under unlisted shares (5%) or "any other assets" (10%). The legal characterisation of the instrument, not its economic substance, determines the applicable cap — and it should be confirmed before any commitment.

## 2.3 SACCOs and the SASRA constraint
Here the case's simplified rules **match the current position exactly**: core capital of not less than 10% of total assets; core capital of not less than 8% of total deposits; institutional capital of not less than 8% of total assets; and a liquidity ratio of not less than 15% of savings deposits and short-term liabilities.

Three real requirements the case omits are worth noting because they bind in practice: an absolute minimum core capital of KES 10 million (Riverbend passes comfortably at KES 300m); a cap on non-performing loans at 5% of the portfolio; and a statutory reserve requirement to transfer at least 20% of net surplus annually until reserves equal share capital. That last one is directly relevant — it is the mechanism through which Riverbend would build the institutional capital it currently lacks.

Sector context sharpens the Riverbend diagnosis considerably. SASRA's supervision reporting shows deposit-taking SACCOs maintaining, in aggregate, a core capital ratio of about 16% and institutional capital of about 9% against the 8% minimum, with sector liquidity in excess of 60% against a 15% floor. Riverbend's ratios — 9.38%, 6.56% and 13.58% respectively — are therefore not marginally below the regulatory line; they are a substantial distance below the industry. Institutional capital compliance is historically the weakest of the four ratios across the sector, which is precisely where Riverbend fails hardest.

## 2.4 Opportunities and risks by investor type
**Pension schemes.** *Opportunity:* the best liability match available in the domestic market; inflation-linked, long-dated cash flows for a 20-year-plus liability profile; a route out of over-concentration in government paper. *Risk:* illiquidity against a 15-year lock-up; valuation opacity in unlisted vehicles; single-manager concentration; and — most underappreciated — the fact that a government-anchored infrastructure fund is *correlated with*, not diversifying of, an existing large government securities holding. A scheme that moves 20% from Treasury paper into a sovereign-anchored fund has changed the liquidity of its risk, not the quantum.

**SACCOs.** *Opportunity:* yield pick-up over Treasury bills; diversification away from a loan book that is typically the overwhelming majority of assets; developmental alignment with member interests. *Risk:* fundamentally, a maturity mismatch. SACCO liabilities are member deposits, withdrawable on demand or short notice, with an expectation of capital certainty. Funding a 15-year illiquid asset from that base is the mechanism by which deposit-takers fail. A mark-down in an unlisted fund flows directly through core capital with no ability to exit. Any allocation should be funded from institutional capital and retained earnings, never from member deposits, and sized so that a total write-off would breach no prudential ratio.

**The DIF itself.** *Opportunity:* aggregation, standardisation and credit capability that individual institutions cannot replicate. *Risk:* government anchoring cuts both ways — it provides comfort but concentrates sovereign exposure, and a vehicle that becomes a channel for politically directed lending would transmit that risk straight onto the balance sheets of pension schemes and SACCOs. Governance, independent project appraisal and transparent valuation policy are the conditions on which domestic institutional participation should depend.

## 2.5 What the Meridian case demonstrates about the model
The solar IPP is a useful test of the whole proposition, because it shows that the binding constraint on domestic infrastructure financing is frequently **not** the availability of capital or the regulatory ceiling. In this transaction the DIF's 70% gearing cap permits USD 42.00m; the project's own cash generation supports only USD 33.97m at a 1.30x covenant. The lender could not deploy more even if policy allowed and capital were abundant.

Nor is the cost of capital the obstacle. After the interest tax shield the DIF facility costs an effective **5.60%**, which is *below* the 6.07% the asset earns — leverage here is marginally accretive, and the capital structure is efficient. The obstacle is the tariff. Domestic institutional capital cannot be mobilised into projects whose contracted revenue sits below their levelised cost, and no amount of structuring, blending or regulatory liberalisation changes that. The policy lever that matters is procurement and tariff-setting, not the investment guidelines.

# Conclusion
The Meridian model's assumptions are defensible, with two stated exceptions — the absence of panel degradation and of any maintenance capex — both of which flatter the result and both of which are disclosed. The project fails on economics, not on modelling, and the failure is robust across the sensitivity range.

On the institutional financing question, the regulatory architecture is more permissive for pension schemes than for SACCOs, and appropriately so given the difference in liability structure. But the real RBA infrastructure limit of 10% is one third of what the case assumes, which constrains the pension channel considerably more than the case implies. The pension allocation of 10% happens to remain compliant under both readings.

The broader conclusion is that Kenya's domestic capital pools are a credible source of infrastructure finance, and the regulatory ceilings are not currently the binding constraint on that. Bankable projects are.

# Sources
1\. **Retirement Benefits Authority (Kenya), Investment Guidelines — Table G, First Schedule to the Retirement Benefits Regulations.** Asset class maximum limits as a percentage of aggregate market value of total scheme assets. https://www.rba.go.ke/investment-regulations/

2\. **The Retirement Benefits Act, No. 3 of 1997, and subsidiary legislation.** Regulation 18 (investment guidelines prescribed under s.38(1)(b)); Table G, First Schedule. Retirement Benefits Tribunal document repository, https://tribunal.rba.go.ke

3\. **Sacco Societies Regulatory Authority (SASRA), prudential standards under the Sacco Societies Act (2008) and the Sacco Societies (Deposit-Taking Sacco Business) Regulations.** Minimum core capital of KES 10 million; core capital ≥ 10% of total assets; core capital ≥ 8% of total deposits; institutional capital ≥ 8% of total assets; liquidity ratio ≥ 15% of savings deposits and short-term liabilities. https://www.sasra.go.ke/

4\. **SASRA, Sacco Supervision Annual Report.** Sector aggregate capital adequacy and liquidity ratios for deposit-taking SACCOs, used for the industry comparison in section 2.3.

5\. **Assessment pack — IB Analyst Technical Assessment**, Sections A–E. All project, scheme and SACCO figures.

6\. **Accompanying Excel model.** All derived figures in this brief are live outputs of that model and can be traced to the Assumptions, Model and Debt tabs.

**Sources identified but not verified within this case study**, and which should be attached before this is relied on: IRENA *Renewable Power Generation Costs* (latest edition) for the utility-scale solar capex benchmark supporting section 1.3; and Global Solar Atlas / World Bank ESMAP site data for the specific-yield benchmark supporting section 1.2. These are flagged rather than cited because I could not confirm the figures directly.
