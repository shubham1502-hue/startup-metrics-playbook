# Startup Metrics Playbook

Founder-facing metric dictionary for startup dashboards, board packs, RevOps analytics, and operating reviews.

<!-- FOUNDER_OS_STANDARD_README -->

## The founder problem

Early teams often track too many numbers, define the same metric three different ways, or confuse investor metrics with operating metrics. That makes dashboards noisy and decisions weak.

## What this repo does

- defines core startup metrics
- explains formulas, traps, and interpretation
- provides a reference for dashboards and board packs
- connects metrics to operating decisions

## What a founder gets in 10 minutes

- metric definitions
- formula reference
- SQL-style examples where present
- benchmark and interpretation notes
- dashboard planning guide

## Before and after

Before:

- metrics defined differently across teams
- dashboard without decisions
- board pack terms debated at the last minute
- unclear operating ownership

After:

- shared metric language
- clear formulas
- better dashboard inputs
- more credible board and weekly review artifacts

## Who this is for

- early-stage founders
- Founder's Office teams
- BizOps operators
- RevOps operators
- startup generalists
- students learning startup metrics

## Quick start

- Fork the repo.
- Open `README.md` and start with the Quick Reference Index.
- Copy the metrics you actually use into your dashboard spec.
- Pair the definitions with `board-pack-investor-update-agent` or `founder-weekly-operating-review-agent`.

## How to fork and use this for your company

1. Click Fork.
2. Rename the repo if needed.
3. Delete metrics that do not matter for your current stage.
4. Add company-specific definitions and data owners.
5. Link each metric to a source system such as Stripe, HubSpot, Pipedrive, Attio, product analytics, or finance.
6. Keep private company numbers out of public forks.

### Non-technical path

- Replace one section: metric definitions relevant to your company.
- Edit one list: your source-of-truth systems.
- Run no code.
- Read one artifact first: the Quick Reference Index.

## Input format

- company stage
- business model
- metric names
- source systems
- dashboard owner
- board reporting needs

The default sample data and examples are synthetic, anonymized, or template-only unless the repo explicitly documents a public source. Keep private customer, prospect, employee, investor, borrower, merchant, payment, or company data out of public forks.

## Output files

- metric dictionary in `README.md`
- copyable formulas and interpretation notes
- dashboard and board-pack vocabulary

## Sample artifacts to inspect

Open these before building a dashboard:

- The Quick Reference Index in `README.md`: the fastest metric map.
- The individual metric sections in `README.md`: definitions, formulas, interpretation, and traps.
- `docs/founder-use-case.md`: how to turn definitions into an operating artifact.

## Example founder workflow

- Monday: choose the metrics for the current operating question.
- Tuesday: confirm definitions and owners.
- Wednesday: map each metric to a source system.
- Thursday: use the definitions in dashboard or board pack work.
- Friday: remove noisy metrics that did not drive action.

## Customization guide

Customize these before using the repo for a real company:

- metric definitions
- formula assumptions
- benchmarks
- source systems
- dashboard ownership
- board reporting language

## Standalone or integrated

Standalone:
Use this repo by itself if you only need metric definitions, formulas, interpretation notes, and dashboard planning language before building reports. Fork it, replace the sample input, run the workflow or copy the templates, and use the main output in your next founder review.

Integrated:
Use this repo with the Founder OS ecosystem if you want to connect it to adjacent operating workflows.

- Use before [founder-os-revenue-engine](https://github.com/shubham1502-hue/founder-os-revenue-engine) so funnel metrics are defined consistently.
- Use before [founder-weekly-operating-review-agent](https://github.com/shubham1502-hue/founder-weekly-operating-review-agent) so weekly metrics have owners and interpretation.
- Use before [board-pack-investor-update-agent](https://github.com/shubham1502-hue/board-pack-investor-update-agent) so investor metrics are not ambiguous.
- Use with [founder-retention-expansion-os](https://github.com/shubham1502-hue/founder-retention-expansion-os) when post-activation health, renewal, expansion, churn, or proof metrics need consistent definitions.
- Use with [revops-infrastructure-playbook](https://github.com/shubham1502-hue/revops-infrastructure-playbook) when metric definitions need source-system mapping.

## Lifecycle handoff

Before:

- [founder-os](https://github.com/shubham1502-hue/founder-os) for deciding which operating questions matter.
- Business model and KPI needs from the founder or operator.

This repo produces:

- Metric definitions
- Formulas
- Interpretation notes
- Dashboard planning language
- Metric ownership prompts

After:

- [founder-os-revenue-engine](https://github.com/shubham1502-hue/founder-os-revenue-engine) for revenue diagnosis.
- [founder-retention-expansion-os](https://github.com/shubham1502-hue/founder-retention-expansion-os) for post-activation retention, renewal, expansion, churn, and customer proof operating metrics.
- [founder-weekly-operating-review-agent](https://github.com/shubham1502-hue/founder-weekly-operating-review-agent) for weekly review.
- [board-pack-investor-update-agent](https://github.com/shubham1502-hue/board-pack-investor-update-agent) for board and investor narrative.
- [revops-infrastructure-playbook](https://github.com/shubham1502-hue/revops-infrastructure-playbook) for CRM and reporting architecture.

## Where this fits in the Founder OS

This is the metric language layer for `founder-weekly-operating-review-agent`, `board-pack-investor-update-agent`, `founder-os-revenue-engine`, `founder-retention-expansion-os`, and `revops-infrastructure-playbook`.

[Founder Retention Expansion OS](https://github.com/shubham1502-hue/founder-retention-expansion-os) operationalizes post-activation metrics such as health, renewal risk, expansion readiness, churn drivers, references, and proof opportunities.

## Why this matters

This is not a glossary for its own sake. It is a shared operating language for making startup metrics useful.

## Roadmap

- Google Sheets metric dictionary
- dashboard spec template
- board pack metric checklist
- SQL examples by warehouse
- stage-specific metric sets

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) if present. Practical improvements are welcome when they make the workflow easier to fork, run, or adapt.

## License

MIT License. See [LICENSE](LICENSE).

## Built by

Built by Shubham Singh, a founder-facing operator focused on RevOps, GTM systems, startup metrics, AI workflows, and operating systems for early-stage teams.

## Use this in your company

Fork it, replace the sample inputs with your company context, and run the workflow. Start with the main output listed in the Quick Start section. Keep private data out of public forks.

## If you are a Founder's Office candidate

Use this repo to understand how a founder-facing operator turns messy inputs into decisions, cadence, and execution artifacts. Fork it, adapt it to a real company example, and write a short case note explaining what changed.

---

## Detailed implementation notes

The founder-facing guide above is the fastest path. The original repo-specific notes are preserved below for deeper implementation context.

## Problem This Solves

Early teams often track too many numbers, define the same metric three different ways, or confuse investor metrics with operating metrics. That makes dashboards noisy and decisions weak.

## How It Helps

- Gives founders and operators a practical metric dictionary with definitions, formulas, SQL examples, benchmarks, and traps.
- Turns metric selection into an operating decision: what to track, why it matters, and how to avoid misleading reads.
- Works as a starter reference for building a founder dashboard, board pack, or RevOps analytics layer.

## When To Fork This

- Fork this if you are building your first startup metrics dashboard, board reporting layer, or founder operating review.
- Fork it when your team argues about CAC, LTV, churn, NRR, burn, pipeline, or activation because definitions are unclear.
- Customize the SQL assumptions, benchmarks, and primary metric set for your business model and stage.

> A practitioner's reference for the 20 metrics that matter most at early-stage startups - built for founders, operators, and anyone sitting in a Founder's Office.

Every metric here includes: what it means, how to calculate it, the SQL to pull it, and what "good" actually looks like at different stages. No fluff. No textbook definitions. Just the signal a founder needs to make a decision.

---

## Use This In Your Company

This repo is designed to be forked into an internal company workflow. Fork it, replace the sample inputs with your company context, and keep only the parts that match your operating cadence. No permission request or sales call is needed before using it; the repo is the handoff. Check the license if you plan to redistribute your version.

- Use it as a metrics dictionary before building a dashboard, board pack, or weekly review.
- Keep the structure: metric definition, formula, SQL logic, benchmark, interpretation, and traps.
- Replace benchmarks and SQL table names with your company stage and warehouse schema.

## Minimum Edits To Make It Yours

Change these first:

| Edit | Where | Why |
|---|---|---|
| Pick your primary metric set. | metric index in `README.md` | Keeps the dashboard focused on the metrics that matter at your stage. |
| Replace benchmark assumptions. | each metric's benchmark section | Prevents generic targets from becoming false operating guidance. |
| Map SQL table and column names. | SQL blocks inside `README.md` | Makes the playbook usable with your warehouse or BI layer. |
| Add your review cadence. | weekly review or board-pack section you create from this repo | Turns definitions into an operating habit. |

You can leave the metric structure, formulas, and traps sections alone on the first fork. First map the metrics to your data model; then add company-specific benchmarks.

## Who This Is For

- **Founders** who want a single source of truth for their business health dashboard
- **Operators** building RevOps, BizOps, or analytics systems from scratch
- **Analysts** who need to go from raw CRM/product data to boardroom-ready numbers fast

---

## Quick Reference Index

| # | Metric | Category | The One-Line Version |
|---|---|---|---|
| 1 | [CAC](#1-customer-acquisition-cost-cac) | Growth | How much you spend to win one customer |
| 2 | [LTV](#2-customer-lifetime-value-ltv) | Growth | How much one customer is worth over time |
| 3 | [CAC:LTV Ratio](#3-cacltv-ratio) | Growth | Whether your unit economics work |
| 4 | [Payback Period](#4-payback-period) | Growth | How long until a customer pays for themselves |
| 5 | [MRR](#5-monthly-recurring-revenue-mrr) | Revenue | The heartbeat of a SaaS business |
| 6 | [ARR](#6-annual-recurring-revenue-arr) | Revenue | MRR × 12 - used for investor conversations |
| 7 | [Churn Rate](#7-churn-rate) | Retention | How fast you're losing customers |
| 8 | [NRR](#8-net-revenue-retention-nrr) | Retention | Whether existing customers grow or shrink |
| 9 | [GRR](#9-gross-revenue-retention-grr) | Retention | Revenue retained, ignoring expansion |
| 10 | [DAU/MAU](#10-daumau-ratio) | Engagement | How sticky your product actually is |
| 11 | [Activation Rate](#11-activation-rate) | Product | Are new users reaching the "aha moment"? |
| 12 | [Funnel Conversion](#12-funnel-conversion-rate) | Sales | Where revenue is leaking |
| 13 | [Burn Rate](#13-burn-rate) | Finance | How fast you're spending the runway |
| 14 | [Burn Multiple](#14-burn-multiple) | Finance | Efficiency of growth spend |
| 15 | [Runway](#15-runway) | Finance | How many months until you run out of money |
| 16 | [Quick Ratio](#16-quick-ratio) | Growth | Growth efficiency: new vs. lost revenue |
| 17 | [Pipeline Coverage](#17-pipeline-coverage) | Sales | Can you hit quota with what's in the pipeline? |
| 18 | [Demo-to-Close](#18-demo-to-close-rate) | Sales | What % of demos become paying customers |
| 19 | [ACV](#19-average-contract-value-acv) | Revenue | The average annual deal size |
| 20 | [Magic Number](#20-magic-number) | Growth | Is your sales & marketing spend efficient? |

---

## The Metrics

---

### 1. Customer Acquisition Cost (CAC)

**What it is:** The total cost to acquire one new paying customer - sales salaries, marketing spend, tools, commissions - everything.

**Formula:**
```
CAC = Total Sales & Marketing Spend / Number of New Customers Acquired
```
*(in the same period)*

**SQL:**
```sql
-- Assumes spend tracked in a costs table, customers in a contracts table
SELECT
  DATE_TRUNC('month', c.created_at) AS month,
  SUM(s.spend_amount) AS total_sm_spend,
  COUNT(DISTINCT c.customer_id) AS new_customers,
  ROUND(SUM(s.spend_amount) / NULLIF(COUNT(DISTINCT c.customer_id), 0), 2) AS cac
FROM contracts c
JOIN sales_marketing_spend s
  ON DATE_TRUNC('month', c.created_at) = DATE_TRUNC('month', s.spend_date)
WHERE c.status = 'active'
  AND c.created_at >= DATE_SUB(CURDATE(), INTERVAL 12 MONTH)
GROUP BY 1
ORDER BY 1;
```

**What good looks like:**
| Stage | Benchmark |
|---|---|
| Pre-product-market-fit | Ignore CAC - focus on learning |
| Seed / Series A | CAC < 3× ACV |
| Series B+ | CAC payback < 12 months |

**The trap:** Most early-stage teams undercount CAC by forgetting founder time, free trials given, and onboarding costs. If your CAC looks suspiciously low, you're probably excluding something.

---

### 2. Customer Lifetime Value (LTV)

**What it is:** The total revenue you can expect from a single customer before they churn.

**Formula:**
```
LTV = ARPU / Churn Rate
```
where ARPU = Average Revenue Per User per month

**SQL:**
```sql
SELECT
  AVG(monthly_revenue) AS arpu,
  AVG(churned) AS monthly_churn_rate,
  ROUND(AVG(monthly_revenue) / NULLIF(AVG(churned), 0), 2) AS ltv
FROM (
  SELECT
    customer_id,
    AVG(monthly_amount) AS monthly_revenue,
    MAX(CASE WHEN status = 'churned' THEN 1 ELSE 0 END) AS churned
  FROM subscriptions
  GROUP BY customer_id
) t;
```

**What good looks like:**
- LTV > 3× CAC is the minimum bar
- LTV > 5× CAC at Series B signals strong unit economics
- LTV should grow over time if you're successfully expanding accounts

**The trap:** LTV calculations assume churn rate is constant. In early-stage companies it rarely is - cohort-based LTV is more honest than a single average.

---

### 3. CAC:LTV Ratio

**What it is:** The single most-cited unit economics metric. Tells you whether your business model is fundamentally viable.

**Formula:**
```
LTV:CAC Ratio = LTV / CAC
```
*(note: usually expressed as LTV:CAC, not CAC:LTV)*

**SQL:**
```sql
-- Combine CAC and LTV queries above into a single view
WITH cac_calc AS (
  SELECT ROUND(SUM(spend_amount) / NULLIF(COUNT(DISTINCT customer_id), 0), 2) AS cac
  FROM sales_marketing_spend s
  JOIN contracts c ON DATE_TRUNC('month', s.spend_date) = DATE_TRUNC('month', c.created_at)
  WHERE c.created_at >= DATE_SUB(CURDATE(), INTERVAL 12 MONTH)
),
ltv_calc AS (
  SELECT ROUND(AVG(monthly_revenue) / NULLIF(AVG(monthly_churn), 0), 2) AS ltv
  FROM (
    SELECT customer_id,
        AVG(monthly_amount) AS monthly_revenue,
        MAX(CASE WHEN status = 'churned' THEN 1 ELSE 0 END) AS monthly_churn
    FROM subscriptions GROUP BY customer_id
  ) t
)
SELECT
  ltv_calc.ltv,
  cac_calc.cac,
  ROUND(ltv_calc.ltv / NULLIF(cac_calc.cac, 0), 2) AS ltv_to_cac_ratio
FROM ltv_calc, cac_calc;
```

**What good looks like:**
| Ratio | Signal |
|---|---|
| < 1:1 | Business model is broken |
| 1:1 - 3:1 | Marginal - reinvest everything, fix efficiency |
| 3:1 | The minimum acceptable benchmark (Paul Graham's rule) |
| 5:1+ | Strong - potential to scale |
| 10:1+ | Dominant unit economics - raise and accelerate |

**The trap:** A 3:1 ratio at 18-month payback is very different from a 3:1 ratio at 6-month payback. Always read alongside Payback Period.

---

### 4. Payback Period

**What it is:** How many months until a customer has paid back what it cost to acquire them.

**Formula:**
```
Payback Period (months) = CAC / (ARPU × Gross Margin %)
```

**SQL:**
```sql
SELECT
  cac_data.cac,
  rev_data.arpu,
  rev_data.gross_margin_pct,
  ROUND(cac_data.cac / NULLIF(rev_data.arpu * rev_data.gross_margin_pct, 0), 1) AS payback_months
FROM (
  SELECT SUM(spend_amount) / NULLIF(COUNT(DISTINCT customer_id), 0) AS cac
  FROM sales_marketing_spend s
  JOIN contracts c ON DATE_TRUNC('month', s.spend_date) = DATE_TRUNC('month', c.created_at)
) cac_data,
(
  SELECT
    AVG(monthly_amount) AS arpu,
    (SUM(monthly_amount) - SUM(cogs)) / NULLIF(SUM(monthly_amount), 0) AS gross_margin_pct
  FROM subscriptions
  WHERE status = 'active'
) rev_data;
```

**What good looks like:**
| Stage | Benchmark |
|---|---|
| B2C / consumer | < 6 months |
| B2B SaaS | < 12 months |
| Enterprise | < 18-24 months |

**The trap:** Founders often calculate payback on revenue, not gross profit. If your gross margin is 60%, your real payback is nearly 2× what the revenue-based number shows.

---

### 5. Monthly Recurring Revenue (MRR)

**What it is:** The normalised, predictable revenue your business generates every month from active subscriptions. The heartbeat metric.

**Formula:**
```
MRR = Sum of all active subscription monthly amounts
```

**MRR movements (track all four):**
```
New MRR    = Revenue from new customers this month
Expansion MRR = Upgrades / upsells from existing customers
Contraction MRR = Downgrades from existing customers
Churned MRR  = Revenue lost from cancelled customers

Net New MRR = New MRR + Expansion MRR - Contraction MRR - Churned MRR
```

**SQL:**
```sql
WITH monthly_mrr AS (
  SELECT
    customer_id,
    DATE_TRUNC('month', start_date) AS month,
    monthly_amount,
    LAG(monthly_amount) OVER (PARTITION BY customer_id ORDER BY start_date) AS prev_amount,
    LAG(status) OVER (PARTITION BY customer_id ORDER BY start_date) AS prev_status,
    status
  FROM subscriptions
)
SELECT
  month,
  SUM(CASE WHEN prev_status IS NULL THEN monthly_amount ELSE 0 END) AS new_mrr,
  SUM(CASE WHEN prev_amount IS NOT NULL AND monthly_amount > prev_amount THEN monthly_amount - prev_amount ELSE 0 END) AS expansion_mrr,
  SUM(CASE WHEN prev_amount IS NOT NULL AND monthly_amount < prev_amount THEN prev_amount - monthly_amount ELSE 0 END) AS contraction_mrr,
  SUM(CASE WHEN status = 'churned' THEN prev_amount ELSE 0 END) AS churned_mrr,
  SUM(monthly_amount) AS total_mrr
FROM monthly_mrr
GROUP BY 1
ORDER BY 1;
```

**What good looks like:**
- **T2D3 growth** (triple, triple, double, double, double) is the SaaS benchmark for a breakout company
- 10-15% MoM growth at seed stage is strong
- Flat MRR is a red flag even if absolute numbers are large

---

### 6. Annual Recurring Revenue (ARR)

**What it is:** MRR annualised. Used for investor conversations, valuations, and benchmarking.

**Formula:**
```
ARR = MRR × 12
```

**SQL:**
```sql
SELECT
  DATE_TRUNC('month', CURDATE()) AS snapshot_month,
  SUM(monthly_amount) * 12 AS arr
FROM subscriptions
WHERE status = 'active';
```

**What good looks like:**
| ARR Milestone | Stage Benchmark |
|---|---|
| $0 - $1M ARR | Pre-Series A (finding PMF) |
| $1M - $5M ARR | Series A territory |
| $5M - $10M ARR | Series B territory |
| $10M+ ARR | Late-stage / growth |

**The trap:** Annual contracts paid upfront look like a spike in revenue but should be recognised monthly in MRR/ARR. Mixing cash accounting and ARR is the most common early-stage mistake.

---

### 7. Churn Rate

**What it is:** The percentage of customers (or revenue) lost in a given period.

**Formula:**
```
Customer Churn Rate = Customers Lost in Period / Customers at Start of Period

Revenue Churn Rate = MRR Lost in Period / MRR at Start of Period
```

**SQL:**
```sql
SELECT
  month,
  customers_start,
  customers_churned,
  ROUND(customers_churned / NULLIF(customers_start, 0) * 100, 2) AS churn_rate_pct
FROM (
  SELECT
    DATE_TRUNC('month', churned_at) AS month,
    COUNT(DISTINCT customer_id) AS customers_churned,
    (SELECT COUNT(DISTINCT customer_id)
     FROM subscriptions s2
     WHERE s2.status = 'active'
     AND DATE_TRUNC('month', s2.created_at) < DATE_TRUNC('month', churned_at)) AS customers_start
  FROM subscriptions
  WHERE status = 'churned'
  GROUP BY 1
) t
ORDER BY 1;
```

**What good looks like:**
| Segment | Monthly Churn Benchmark |
|---|---|
| SMB SaaS | 3-5% monthly |
| Mid-market SaaS | 1-2% monthly |
| Enterprise SaaS | 0.5-1% monthly |
| Consumer apps | 5-10% monthly |

**The trap:** Measuring customer churn without revenue churn hides the real picture. Losing 5 small customers while retaining one large one looks bad on customer churn but fine on revenue churn.

---

### 8. Net Revenue Retention (NRR)

**What it is:** Of the revenue you had from existing customers 12 months ago, how much do you have now - including expansions, contractions, and churn. NRR > 100% means your existing customer base is growing on its own.

**Formula:**
```
NRR = (Starting MRR + Expansion MRR - Contraction MRR - Churned MRR) / Starting MRR × 100
```

**SQL:**
```sql
WITH cohort AS (
  SELECT
    customer_id,
    SUM(CASE WHEN period = 'start' THEN monthly_amount ELSE 0 END) AS start_mrr,
    SUM(CASE WHEN period = 'end' THEN monthly_amount ELSE 0 END) AS end_mrr
  FROM (
    SELECT customer_id, monthly_amount, 'start' AS period
    FROM subscriptions
    WHERE DATE_TRUNC('month', created_at) = DATE_SUB(DATE_TRUNC('month', CURDATE()), INTERVAL 12 MONTH)
    UNION ALL
    SELECT customer_id, COALESCE(monthly_amount, 0), 'end' AS period
    FROM subscriptions
    WHERE DATE_TRUNC('month', created_at) = DATE_TRUNC('month', CURDATE())
  ) t
  GROUP BY customer_id
)
SELECT
  ROUND(SUM(end_mrr) / NULLIF(SUM(start_mrr), 0) * 100, 1) AS nrr_pct
FROM cohort;
```

**What good looks like:**
| NRR | Signal |
|---|---|
| < 80% | Leaky bucket - stop acquiring, fix retention |
| 80-100% | Acceptable - revenue declining but slowly |
| 100-110% | Good - existing customers staying and growing slightly |
| 110-130% | Excellent - expansion is offsetting churn |
| 130%+ | World-class (Snowflake at IPO was 158%) |

**The trap:** NRR and GRR are the most confused metric pair in SaaS. Know the difference cold (see GRR below).

---

### 9. Gross Revenue Retention (GRR)

**What it is:** NRR's simpler cousin. Revenue retained from existing customers, **excluding** any expansion revenue. Capped at 100% because you can't count growth here.

**Formula:**
```
GRR = (Starting MRR - Contraction MRR - Churned MRR) / Starting MRR × 100
```
*(max 100%)*

**SQL:**
```sql
SELECT
  ROUND(
    LEAST(
      (SUM(start_mrr) - SUM(contraction_mrr) - SUM(churned_mrr)) / NULLIF(SUM(start_mrr), 0) * 100,
      100
    ), 1
  ) AS grr_pct
FROM (
  SELECT
    SUM(CASE WHEN period = 'start' THEN monthly_amount ELSE 0 END) AS start_mrr,
    SUM(CASE WHEN period = 'contraction' THEN ABS(monthly_amount) ELSE 0 END) AS contraction_mrr,
    SUM(CASE WHEN period = 'churned' THEN monthly_amount ELSE 0 END) AS churned_mrr
  FROM revenue_movements
) t;
```

**NRR vs GRR - The Key Distinction:**
| Metric | Includes Expansion? | Max Value | What it measures |
|---|---|---|---|
| GRR | No | 100% | Retention quality - how well you keep revenue |
| NRR | Yes | Unlimited | Net growth from existing base |

**What good looks like:**
- GRR > 85% is the benchmark for healthy B2B SaaS
- GRR > 90% at scale signals very low involuntary churn
- If NRR >> GRR, your expansion motion is strong

---

### 10. DAU/MAU Ratio

**What it is:** The stickiness ratio. What % of your monthly active users come back every day. The higher this is, the more habitual your product is.

**Formula:**
```
DAU/MAU = Daily Active Users / Monthly Active Users × 100
```

**SQL:**
```sql
SELECT
  DATE_TRUNC('month', event_date) AS month,
  COUNT(DISTINCT CASE WHEN event_date = CURDATE() THEN user_id END) AS dau,
  COUNT(DISTINCT user_id) AS mau,
  ROUND(
    COUNT(DISTINCT CASE WHEN event_date = CURDATE() THEN user_id END) /
    NULLIF(COUNT(DISTINCT user_id), 0) * 100, 1
  ) AS dau_mau_ratio
FROM user_events
WHERE event_date >= DATE_SUB(CURDATE(), INTERVAL 30 DAY)
GROUP BY 1;
```

**What good looks like:**
| Ratio | Product Type |
|---|---|
| > 50% | Daily habit utility (WhatsApp, Slack, Gmail) |
| 25-50% | Strong (Facebook-level) |
| 10-25% | Weekly habit - normal for many B2B tools |
| < 10% | Low engagement - investigate activation and retention |

**The trap:** DAU/MAU benchmarks depend heavily on product type. A project management tool at 15% stickiness may be healthy; a messaging app at 15% is failing.

---

### 11. Activation Rate

**What it is:** The % of new users who reach your "aha moment" - the action that predicts they will become long-term retained users.

**Formula:**
```
Activation Rate = Users who completed the activation event / Total new signups × 100
```
*(The activation event varies by product: first transaction, first sent message, first completed project, etc.)*

**SQL:**
```sql
SELECT
  DATE_TRUNC('month', u.created_at) AS signup_month,
  COUNT(DISTINCT u.user_id) AS total_signups,
  COUNT(DISTINCT a.user_id) AS activated_users,
  ROUND(COUNT(DISTINCT a.user_id) / NULLIF(COUNT(DISTINCT u.user_id), 0) * 100, 1) AS activation_rate_pct
FROM users u
LEFT JOIN (
  SELECT DISTINCT user_id
  FROM user_events
  WHERE event_type = 'activation_event' -- replace with your actual activation event
  AND created_at <= DATE_ADD(users.created_at, INTERVAL 7 DAY) -- within first 7 days
) a ON u.user_id = a.user_id
WHERE u.created_at >= DATE_SUB(CURDATE(), INTERVAL 6 MONTH)
GROUP BY 1
ORDER BY 1;
```

**What good looks like:**
- No universal benchmark - define YOUR activation event first
- Activation rate improvement of even 5-10pp compounds dramatically into retention
- Best-in-class B2B SaaS activation within 7 days: 40-60%

**The trap:** If you haven't defined what "activated" means in your product, this metric is meaningless. The activation event should be the behaviour most correlated with 30-day retention - run a correlation analysis to find it.

---

### 12. Funnel Conversion Rate

**What it is:** The % of prospects moving from one stage of the pipeline to the next. Measured at each stage, not just top-to-close.

**Formula:**
```
Stage Conversion Rate = Deals entering next stage / Deals entering this stage × 100
```

**SQL:**
```sql
SELECT
  stage,
  COUNT(deal_id) AS deals_in_stage,
  COUNT(next_stage_deal_id) AS deals_advanced,
  ROUND(COUNT(next_stage_deal_id) / NULLIF(COUNT(deal_id), 0) * 100, 1) AS conversion_rate_pct
FROM (
  SELECT
    d1.deal_id,
    d1.stage,
    d2.deal_id AS next_stage_deal_id
  FROM deals d1
  LEFT JOIN deals d2
    ON d1.deal_id = d2.deal_id
    AND d2.stage_order = d1.stage_order + 1
  WHERE d1.created_at >= DATE_SUB(CURDATE(), INTERVAL 6 MONTH)
) t
GROUP BY 1
ORDER BY MIN(stage_order);
```

**What good looks like:**
| Stage | B2B SaaS Benchmark |
|---|---|
| Lead → Qualified | 20-30% |
| Qualified → Demo | 40-60% |
| Demo → Proposal | 50-70% |
| Proposal → Close | 20-40% |

**The trap:** Looking only at top-of-funnel and close rate misses where the real leakage is. Stage-by-stage analysis surfaces the specific bottleneck - and it's almost never where founders assume.

---

### 13. Burn Rate

**What it is:** How much cash your company spends per month (net burn) or the total outflows before revenue (gross burn).

**Formula:**
```
Gross Burn = Total monthly cash outflows (salaries, rent, tools, COGS, etc.)

Net Burn = Gross Burn - Revenue collected (cash, not accrual)
```

**SQL:**
```sql
SELECT
  DATE_TRUNC('month', transaction_date) AS month,
  SUM(CASE WHEN type = 'expense' THEN amount ELSE 0 END) AS gross_burn,
  SUM(CASE WHEN type = 'revenue' THEN amount ELSE 0 END) AS revenue_collected,
  SUM(CASE WHEN type = 'expense' THEN amount ELSE 0 END) -
  SUM(CASE WHEN type = 'revenue' THEN amount ELSE 0 END) AS net_burn
FROM cash_transactions
WHERE transaction_date >= DATE_SUB(CURDATE(), INTERVAL 6 MONTH)
GROUP BY 1
ORDER BY 1;
```

**What good looks like:**
- Burn should feel proportional to ARR growth - burning ₹1Cr/month while growing ₹10L/month MRR is a problem
- Most seed-stage startups target 18-24 months of runway at current burn before raising
- Founders who can't answer this within 30 seconds lose investor credibility immediately

**The trap:** Confusing net and gross burn. Investors ask about net burn. If you quote gross burn it signals you haven't thought carefully about your financial health.

---

### 14. Burn Multiple

**What it is:** Sequoia's favourite metric. Measures how much you're burning for every dollar of net new ARR you generate. The lower the better.

**Formula:**
```
Burn Multiple = Net Burn / Net New ARR
```

**SQL:**
```sql
WITH monthly AS (
  SELECT
    DATE_TRUNC('month', transaction_date) AS month,
    SUM(CASE WHEN type = 'expense' THEN amount ELSE 0 END) -
    SUM(CASE WHEN type = 'revenue' THEN amount ELSE 0 END) AS net_burn
  FROM cash_transactions
  GROUP BY 1
),
arr_growth AS (
  SELECT
    DATE_TRUNC('month', created_at) AS month,
    SUM(monthly_amount) * 12 AS new_arr
  FROM subscriptions
  WHERE status = 'active'
  GROUP BY 1
)
SELECT
  m.month,
  m.net_burn,
  a.new_arr,
  ROUND(m.net_burn / NULLIF(a.new_arr, 0), 2) AS burn_multiple
FROM monthly m
JOIN arr_growth a ON m.month = a.month
ORDER BY 1;
```

**What good looks like:**
| Burn Multiple | Signal |
|---|---|
| < 1× | Exceptional - growing faster than burning |
| 1-1.5× | Great |
| 1.5-2× | Good |
| 2-3× | Acceptable in early stages |
| > 3× | Concerning - reassess growth strategy |

**The trap:** Burn multiple looks terrible during big hiring pushes before the revenue follows. Always contextualise with the growth plan.

---

### 15. Runway

**What it is:** How many months of cash remain at current burn rate.

**Formula:**
```
Runway (months) = Cash in Bank / Net Monthly Burn
```

**SQL:**
```sql
SELECT
  current_cash_balance / NULLIF(avg_net_burn, 0) AS runway_months
FROM (
  SELECT
    (SELECT cash_balance FROM bank_accounts ORDER BY snapshot_date DESC LIMIT 1) AS current_cash_balance,
    AVG(net_burn) AS avg_net_burn
  FROM (
    SELECT
      DATE_TRUNC('month', transaction_date) AS month,
      SUM(CASE WHEN type = 'expense' THEN amount ELSE 0 END) -
      SUM(CASE WHEN type = 'revenue' THEN amount ELSE 0 END) AS net_burn
    FROM cash_transactions
    WHERE transaction_date >= DATE_SUB(CURDATE(), INTERVAL 3 MONTH)
    GROUP BY 1
  ) recent_burn
) t;
```

**What good looks like:**
- Always maintain > 12 months of runway before starting a fundraise
- 18 months of runway is the target when entering a raise process (takes 3-6 months)
- < 6 months runway = survival mode; everything else is irrelevant

**The trap:** Using gross burn instead of net burn inflates runway comfort. Use net burn for real decisions, gross burn for cost reduction conversations.

---

### 16. Quick Ratio

**What it is:** A single number that captures the efficiency of your growth. Are you adding more revenue than you're losing?

**Formula:**
```
Quick Ratio = (New MRR + Expansion MRR) / (Churned MRR + Contraction MRR)
```

**SQL:**
```sql
SELECT
  month,
  ROUND((new_mrr + expansion_mrr) / NULLIF(churned_mrr + contraction_mrr, 0), 2) AS quick_ratio
FROM (
  SELECT
    DATE_TRUNC('month', period_date) AS month,
    SUM(CASE WHEN movement_type = 'new' THEN amount ELSE 0 END) AS new_mrr,
    SUM(CASE WHEN movement_type = 'expansion' THEN amount ELSE 0 END) AS expansion_mrr,
    SUM(CASE WHEN movement_type = 'churn' THEN amount ELSE 0 END) AS churned_mrr,
    SUM(CASE WHEN movement_type = 'contraction' THEN amount ELSE 0 END) AS contraction_mrr
  FROM mrr_movements
  GROUP BY 1
) t
ORDER BY 1;
```

**What good looks like:**
| Quick Ratio | Signal |
|---|---|
| < 1 | Shrinking business - losing more than gaining |
| 1 | Breaking even on growth |
| 2 | Good - commonly cited minimum for a healthy SaaS |
| 4+ | Excellent (early Slack was consistently 4+) |

---

### 17. Pipeline Coverage

**What it is:** The ratio of pipeline value to revenue target. Tells you whether there's enough in the funnel to hit quota.

**Formula:**
```
Pipeline Coverage = Total Pipeline Value / Revenue Target (same period)
```

**SQL:**
```sql
SELECT
  DATE_TRUNC('quarter', expected_close_date) AS quarter,
  SUM(deal_value * probability) AS weighted_pipeline,
  SUM(deal_value) AS raw_pipeline,
  (SELECT SUM(revenue_target)
   FROM sales_targets
   WHERE DATE_TRUNC('quarter', target_date) = DATE_TRUNC('quarter', expected_close_date)) AS quarterly_target,
  ROUND(SUM(deal_value) /
    NULLIF((SELECT SUM(revenue_target)
        FROM sales_targets
        WHERE DATE_TRUNC('quarter', target_date) = DATE_TRUNC('quarter', expected_close_date)), 0), 1
  ) AS coverage_ratio
FROM deals
WHERE stage NOT IN ('closed_won', 'closed_lost')
AND expected_close_date >= CURDATE()
GROUP BY 1
ORDER BY 1;
```

**What good looks like:**
| Coverage Ratio | Signal |
|---|---|
| < 2× | High risk - likely to miss quota |
| 2-3× | Healthy for mid-to-late funnel |
| 3-4× | Conservative comfort zone |
| > 4× | Pipeline quality may be the issue (too many stale deals) |

**The trap:** Raw pipeline coverage is misleading if the pipeline has old, stuck deals. Always review weighted pipeline alongside raw numbers.

---

### 18. Demo-to-Close Rate

**What it is:** The % of product demos that convert to a paid customer. One of the most direct signals of sales + product effectiveness.

**Formula:**
```
Demo-to-Close Rate = Closed Won Deals / Total Demos Conducted × 100
```

**SQL:**
```sql
SELECT
  DATE_TRUNC('month', demo_date) AS month,
  COUNT(DISTINCT deal_id) AS total_demos,
  COUNT(DISTINCT CASE WHEN stage = 'closed_won' THEN deal_id END) AS closed_won,
  ROUND(COUNT(DISTINCT CASE WHEN stage = 'closed_won' THEN deal_id END) /
     NULLIF(COUNT(DISTINCT deal_id), 0) * 100, 1) AS demo_to_close_pct
FROM deals
WHERE demo_date IS NOT NULL
AND demo_date >= DATE_SUB(CURDATE(), INTERVAL 12 MONTH)
GROUP BY 1
ORDER BY 1;
```

**What good looks like:**
| Segment | Benchmark |
|---|---|
| SMB SaaS (self-serve heavy) | 15-25% |
| Mid-market SaaS | 20-35% |
| Enterprise | 10-20% (longer cycles) |

**The trap:** Demo-to-close rate hides qualification quality. A 50% demo-to-close on 10 demos per month is worse than a 25% rate on 50 demos. Track absolute closed count alongside the rate.

---

### 19. Average Contract Value (ACV)

**What it is:** The average annual revenue per contract. The key metric for understanding your market segment and pricing strategy.

**Formula:**
```
ACV = Total Annual Contract Value / Number of Active Contracts
```

**SQL:**
```sql
SELECT
  COUNT(DISTINCT contract_id) AS total_contracts,
  ROUND(SUM(monthly_amount * 12) / NULLIF(COUNT(DISTINCT contract_id), 0), 0) AS acv,
  ROUND(AVG(monthly_amount * 12), 0) AS avg_acv,
  ROUND(PERCENTILE_CONT(0.5) WITHIN GROUP (ORDER BY monthly_amount * 12), 0) AS median_acv
FROM subscriptions
WHERE status = 'active';
```

**What good looks like:**
| ACV | Typical Segment |
|---|---|
| < ₹1L / year | SMB, self-serve |
| ₹1L - ₹10L / year | Mid-market |
| ₹10L - ₹1Cr / year | Enterprise |
| > ₹1Cr / year | Strategic / top-tier enterprise |

**The trap:** ACV is a point-in-time number. Track ACV trend over time - rising ACV signals you're moving upmarket; falling ACV signals you're solving for SMBs more than you planned.

---

### 20. Magic Number

**What it is:** Salesforce's original sales efficiency metric. Tells you how much ARR you generated for every rupee of sales & marketing spend last quarter.

**Formula:**
```
Magic Number = (Current Quarter ARR - Prior Quarter ARR) / Prior Quarter S&M Spend
```

**SQL:**
```sql
WITH quarterly AS (
  SELECT
    DATE_TRUNC('quarter', created_at) AS quarter,
    SUM(monthly_amount) * 12 AS quarterly_arr
  FROM subscriptions
  WHERE status = 'active'
  GROUP BY 1
),
sm_spend AS (
  SELECT
    DATE_TRUNC('quarter', spend_date) AS quarter,
    SUM(spend_amount) AS total_sm
  FROM sales_marketing_spend
  GROUP BY 1
)
SELECT
  q.quarter,
  q.quarterly_arr,
  LAG(q.quarterly_arr) OVER (ORDER BY q.quarter) AS prior_arr,
  LAG(s.total_sm) OVER (ORDER BY q.quarter) AS prior_sm_spend,
  ROUND(
    (q.quarterly_arr - LAG(q.quarterly_arr) OVER (ORDER BY q.quarter)) /
    NULLIF(LAG(s.total_sm) OVER (ORDER BY q.quarter), 0), 2
  ) AS magic_number
FROM quarterly q
JOIN sm_spend s ON q.quarter = s.quarter
ORDER BY 1;
```

**What good looks like:**
| Magic Number | Signal |
|---|---|
| < 0.5 | Rethink your go-to-market completely |
| 0.5 - 0.75 | Marginal - optimise before scaling |
| 0.75 - 1 | Good - invest cautiously |
| > 1 | Strong - accelerate S&M investment |
| > 1.5 | Exceptional - floor the accelerator |

**The trap:** Magic number is a lagging metric - it measures the effect of last quarter's spend on this quarter's ARR. It does not tell you which campaigns or channels drove the growth.

---

## The Metric That Trips Everyone: NRR vs GRR

This is the most commonly confused metric pair in SaaS - and the one most likely to come up in a Founder's Office interview or investor conversation.

**The simple version:**
- **GRR** tells you how good you are at keeping what you have. It ignores upsells. Can never exceed 100%.
- **NRR** tells you whether your existing customers are growing or shrinking in aggregate. Can exceed 100%.

**Example:**
- You start with ₹100L MRR from 100 customers
- 5 customers churn: -₹5L
- 10 customers upgrade: +₹15L
- 5 customers downgrade: -₹3L

```
GRR = (100 - 5 - 3) / 100 = 92%   ← Good. You kept 92% of revenue.
NRR = (100 - 5 + 15 - 3) / 100 = 107% ← Great. The base is growing.
```

If your NRR is 120% but your GRR is 70%, you have a serious churn problem hidden by expansion revenue. That is a ticking time bomb.

---

## How to Use This Playbook

1. **Build a metrics dashboard first.** Pick 5-7 of these as your primary operating metrics. Not all 20 at once.
2. **Instrument before you measure.** Many of these require event tracking, CRM stage logging, or financial tagging. If the data doesn't exist, the metric is meaningless.
3. **Track trends, not snapshots.** A single month's NRR tells you little. Three months of declining NRR tells you everything.
4. **Know the formula cold.** In a Founder's Office role, you will be asked to explain these to investors, to board members, and to new hires. The person who can derive the formula on a whiteboard - not just read it off a dashboard - is the person the founder trusts.

---

## Author

**Shubham Singh** - Founder's Office | Startup Ops | RevOps

Previously Process Analyst at STEMpedia - built the entire RevOps and CRM infrastructure from scratch, worked directly with the CEO, and shipped without a playbook.

 Bengaluru | [LinkedIn](https://linkedin.com/in/shubham9616) | [Email](mailto:shubham1502@gmail.com)

---

*Found this useful? Star the repo and share it with someone building their first metrics dashboard.*
