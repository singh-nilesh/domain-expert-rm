# Skill 03: Research Compilation & Documentation

## Purpose
Synthesize research findings into a comprehensive scenario document (300-500 lines) that captures expert RM thinking and actionable guidance.

## When to Use
- After completing search phase using `skills/02_search.md`
- This is STEP 3 of the pipeline

## Output Requirements

**Location:** `agent-workspace/Scenario_XXX.md`
**Length:** 300-500 lines of substantive content
**Focus:** Expert RM thinking, domain knowledge, real examples
**No SQL, no database schema, no technical documentation**

## Document Structure

```markdown
# Scenario XXX: [Title]

## Executive Summary
2-3 paragraphs explaining:
- What the scenario is (business context)
- Why it matters (impact/importance)
- What expert RMs achieve (outcomes)

## Scenario Context
- When does this occur?
- What triggers it?
- Who is involved and their roles?

## RM Thought Process & Decision Logic
How expert RMs think through this:
- Initial assessment (what signals matter?)
- Key questions they ask
- Mental models they use
- What they need to understand

## Expert Actions & Execution
Step-by-step what accomplished RMs do:
- Research and discovery (what to investigate)
- Analysis approach (how to think about it)
- Client conversations (what to discuss, positioning)
- Internal coordination (approvals, partnerships)

## Real-World Case Studies
2-3 concrete examples showing:
- Specific companies or situations
- Expert RM response and actions
- Measurable outcomes
- Key lessons learned

## Industry Best Practices
- What top performers do differently
- Specific approaches from leading banks
- Common pitfalls and how to avoid
- Benchmarks and industry standards

## Client Value Proposition
How should the RM position this?
- What value does it create?
- What risks does it mitigate?
- Quantified benefits or ROI

## Tools, Systems & Resources
Frameworks, platforms, and approaches that support this scenario

## Risk Management & Compliance
- Key risks to manage
- Regulatory or compliance considerations
- Risk mitigation approaches

## Related Scenarios
[List connected scenarios]

## Research Sources & References
[Full citations with URLs]
```

## Compilation Guidelines

### Executive Summary
- Explain the scenario from an expert RM perspective
- Show why this matters (business impact)
- Indicate what successful execution looks like
- Use specific language (not generic)

### RM Thought Process
- Explain how experts mentally approach this
- Show the decision framework
- Include the key questions they ask
- Reveal what information matters most
- Explain why expertise changes how you see this

### Expert Actions
- Describe concrete steps (not checklists)
- Explain the reasoning behind each step
- Show how this differs from non-expert approach
- Include specific examples of how to execute
- Explain what to look for at each stage

### Case Studies
- Find 2-3 real examples (companies, deals, situations)
- Include specific numbers and outcomes
- Explain what the expert RM recognized
- Show the actions taken and results
- Extract the lesson learned

### Best Practices
- Synthesize patterns from multiple sources
- Show what differentiates top performers
- Include specific benchmarks or thresholds
- Explain the reasoning (why this works)
- Cite consulting firms or industry experts

### No Technical Content
- ❌ DO NOT include SQL queries
- ❌ DO NOT include database schema references
- ❌ DO NOT include system screenshots
- ✅ DO discuss data the RM needs and why
- ✅ DO explain how to access insights (generically)
- ✅ DO focus on business logic and expert thinking

## Quality Checklist Before Saving

- [ ] 300-500 lines of substantive content?
- [ ] Captures expert RM thinking and decision logic?
- [ ] Includes 2-3 concrete case studies with outcomes?
- [ ] References 5+ credible sources?
- [ ] Specific numbers, benchmarks, thresholds included?
- [ ] Explains what makes experts different?
- [ ] Includes risk management and compliance?
- [ ] No SQL queries or database references?
- [ ] Could a new RM understand expert approach?
- [ ] Sounds like a banking expert wrote it?

## After Saving Document

### Update status.md

1. **Mark Complete:**
   ```
   ## Recently Completed
   - Scenario XXX: [Title] (Completed: [date])
   - [Previous completed scenarios]
   ```

2. **Promote Next Scenario:**
   ```
   ## Current Scenario
   [Scenario that was "Next" → promote to "Current"]
   
   ## Next Scenario to process
   [Fetch next unprocessed from raw/RM_Agent_Scenarios.md]
   ```

3. **Verify:**
   - Scenario_XXX.md exists in agent-workspace
   - status.md updated correctly
   - Ready to begin next cycle
[PLACEHOLDER: What top RMs do]

## Tools and Resources
[PLACEHOLDER: Systems and tools]

## Risk Considerations
[PLACEHOLDER: Risks and mitigation]

## Related Scenarios
[PLACEHOLDER: Connected scenarios]

## Research Sources
[PLACEHOLDER: All citations]

## Appendix
[PLACEHOLDER: Terminology, additional reading]
```

### Phase 2: Populate Section by Section

Work through each section systematically. Don't jump around.

#### Executive Summary

**Goal:** Give a busy RM the essence in 30 seconds

**Structure:**
- Paragraph 1: What is this scenario? When does it occur?
- Paragraph 2: Why does it matter? What's at stake?
- Paragraph 3: What are the key outcomes if done well?

**Writing Guidelines:**
- Lead with the scenario situation: "When a client's wallet grows but the bank's share remains flat..."
- Quantify importance: "This represents $X opportunity or Y risk..."
- End with clear value: "Properly executed, this scenario enables..."

**Example:**
```markdown
When an RM identifies a client with a large gross wallet (total banking spending across all banks) but low share-of-wallet (percentage captured by the RM's bank), a significant cross-sell opportunity exists. This scenario typically emerges during annual account planning, portfolio reviews, or competitive intelligence analysis when wallet data reveals the client is spending $50M annually on banking services but the RM's institution captures only 15-20% of that wallet.

This scenario matters because wallet share directly correlates with relationship stickiness, revenue growth, and competitive defensibility. Industry research shows that clients consolidating 50%+ of their wallet with one bank have 3x lower attrition rates and 40% higher lifetime value. For a $50M wallet client at 15% share, moving to 30% share represents $7.5M in incremental banking revenue.

Properly executed, this scenario enables the RM to: (1) systematically identify high-value cross-sell opportunities, (2) prioritize products based on client needs and bank capabilities, (3) develop data-driven pitches that resonate with client priorities, and (4) build deeper, more defensible relationships through product diversification.
```

#### Scenario Context

**Business Situation:**
- Set the stage: when does this happen?
- What business conditions create this scenario?
- What changes or events trigger it?

**Triggering Conditions:**
- Specific data signals (be precise!)
- Thresholds or benchmarks
- System alerts or reports

**Stakeholders Involved:**
- Who from the bank? (RM, product managers, credit, risk)
- Who from the client? (CFO, treasurer, CEO)
- Any external parties? (auditors, consultants)

**Writing Guidelines:**
- Use bullets for triggering conditions (easier to scan)
- Be specific: "Gross wallet > $25M AND share-of-wallet < 25%" not "large wallet and low share"
- Name specific roles: "Product Manager - Transaction Banking" not "product team"

#### RM Action Framework

This is the CORE of the document. Most effort goes here.

**Step 1: Data Gathering**

Format:
```markdown
### Step 1: Data Gathering

**What data to collect:**

**From Internal Systems:**
- Customer Wallet and KPI details table:
  - Normalized wallet amount (current year and prior year)
  - Gross wallet amount (estimated total banking spend)
  - Cross-sell flags (products used vs. products available)
  - Top-ranked buckets (where client spends with competitors)
  
- Monthly profitability Aggregate:
  - Revenue by product line (identify current penetration)
  - Margin percentages (understand profitability of current business)
  - Product utilization metrics (deposits, transactions, FX volume)

- Account Planning report header:
  - Strategic narrative (client priorities and bank objectives)
  - Risk rating and exposure (ensure capacity for expansion)
  - Relationship manager notes (previous discussions about needs)

**From Client Interactions:**
- Recent call reports: mentions of pain points, competitor services
- Account review materials: client's stated strategic priorities
- Industry reports: typical banking needs for client's sector

**From External Sources:**
- Industry benchmarks for wallet size in client's sector
- Competitor product offerings and pricing (where available)
- Client's public financial statements (for credit capacity)

**How to collect it:**

1. Run wallet analysis query (see Data Schema Mapping section)
2. Review last 3 months of profitability data to establish baseline
3. Pull account plan to understand strategic context
4. Review last 6 months of call reports for client intelligence
5. Research industry norms for similar client segment

**Data Quality Checks:**
- Validate wallet estimate (does $50M total banking spend align with client's revenue/size?)
- Confirm product usage data is current (last month's data)
- Cross-reference multiple data sources for consistency
- Flag any data gaps that need client confirmation
```

**Step 2: Analysis Process**

Format:
```markdown
### Step 2: Analysis Process

**Analytical Framework:**

Use the **Wallet Gap Analysis Framework**:

1. **Calculate Current Share-of-Wallet**
   ```
   SOW = (Bank Revenue from Client / Client Total Wallet) × 100
   
   Example:
   SOW = ($7.5M / $50M) × 100 = 15%
   ```

2. **Benchmark Against Industry Standards**
   - Industry average SOW for strong relationships: 35-45%
   - Top quartile relationships: 50%+ SOW
   - Client's current SOW (15%) vs. target (35%) = 20 percentage point gap
   
3. **Identify Product Penetration Gaps**
   
   Create a product penetration matrix:
   
   | Product Category | Client Uses? | Our Offering? | Competitor? | Revenue Potential |
   |-----------------|--------------|---------------|-------------|-------------------|
   | Commercial Lending | Yes | Bank A | - | Current |
   | Transaction Banking | No | Bank A | Bank B | $2M |
   | FX & Derivatives | Minimal | Bank A | Bank C | $1.5M |
   | Trade Finance | No | Bank A | Bank B | $1M |
   | Cash Management | No | Bank A | Bank B | $500K |
   | Corporate Finance Advisory | No | Bank A | Not using | $300K |
   
4. **Calculate Opportunity Size by Product**
   ```
   Opportunity = (Estimated Client Spend on Product) × (Bank Capture %)
   
   Example - Transaction Banking:
   Estimated client payment volume: $500M/year
   Typical fee rate: 0.4%
   Potential revenue: $500M × 0.4% = $2M
   Current capture: $0
   Opportunity: $2M
   ```

5. **Prioritize Opportunities**
   
   Score each product on:
   - Revenue potential (weight: 40%)
   - Strategic fit with client needs (weight: 30%)
   - Bank competitive positioning (weight: 20%)
   - Implementation complexity (weight: 10%)
   
   Rank products by total weighted score.

**Key Calculations:**

- **Share-of-Wallet (SOW):** Bank revenue ÷ Total wallet × 100
- **Wallet Growth Rate:** (Current wallet - Prior wallet) ÷ Prior wallet × 100
- **Revenue Gap:** (Target SOW - Current SOW) × Total wallet
- **Product Penetration Rate:** Products used ÷ Products applicable × 100
- **Cross-sell Potential Index:** Σ(Product opportunity × Probability of success)

**Patterns to Identify:**

- **Product clustering:** Does client use all transaction banking OR all lending but not mix?
- **Competitive patterns:** Is one competitor dominant across products? (harder to displace)
- **Client lifecycle stage:** Growing clients have different needs than mature clients
- **Industry norms:** Compare client's banking complexity vs. industry peers
- **Relationship depth:** Single-contact relationships are vulnerable to competitive disruption

**Analysis Output:**

A prioritized list of cross-sell opportunities with:
1. Product category
2. Estimated revenue potential
3. Current competitive position
4. Implementation timeline
5. Resource requirements
6. Success probability
```

**Step 3: Insight Generation**

Format:
```markdown
### Step 3: Insight Generation

**Primary Insights:**

1. **Wallet Growth + Share Stagnation = Competitive Loss**
   
   The client's wallet grew 15% year-over-year ($43.5M → $50M), but the bank's revenue remained flat at $7.5M. This means the $6.5M incremental wallet was captured entirely by competitors. Insight: The client is growing and increasing banking services spend, but views competitors as better partners for expansion. Without intervention, this trend will continue.

2. **Transaction Banking is the Gateway Product**
   
   Analysis shows the client processes $500M in annual payments but uses the bank for only lending. Industry research indicates that clients who consolidate transaction banking with their lender have 60% higher wallet share due to operational switching costs and data integration. Insight: Winning transaction banking not only generates $2M in direct revenue but creates stickiness that enables other product cross-sell.

3. **Client Pain Point Alignment**
   
   Recent call reports show the client's CFO mentioned "fragmented banking relationships creating operational inefficiency" and "desire to consolidate treasury operations." This directly aligns with a transaction banking and cash management pitch. Insight: The cross-sell opportunity is not just financial (bank revenue) but solves a stated client problem (operational efficiency).

**Secondary Insights:**

- The client's industry (manufacturing) typically has heavy trade finance needs, yet the client uses no trade services. This suggests either (a) they don't engage in international trade, or (b) a competitor has locked in their trade business. Requires investigation.
  
- Current relationship is single-threaded through the CFO. Absence of relationships with Treasurer (transaction banking) or VP Supply Chain (trade finance) limits visibility into broader needs. Relationship expansion required.

- Bank's current revenue concentration (100% from lending) creates vulnerability. If client refinances or reduces leverage, revenue drops to near-zero. Product diversification reduces revenue volatility.

**Red Flags to Monitor:**

- If competitor has locked client into multi-year technology contract for transaction banking, entry barriers are high
- If client is dissatisfied with current lending relationship, they may be evaluating wholesale switch
- If client has recently changed CFO or Treasurer, new management may seek to consolidate relationships
```

**Step 4: Recommendation Development**

Format:
```markdown
### Step 4: Recommendation Development

**Immediate Actions (Next 30 Days):**

1. **Validate Wallet Analysis with Client** (Week 1)
   - Schedule meeting with CFO to present wallet analysis findings
   - Confirm our understanding of their total banking services spend
   - Understand if there are services we don't know about
   - Action owner: RM
   
2. **Deep-Dive Discovery on Transaction Banking** (Week 2)
   - Request meeting with Treasurer to understand payment operations
   - Assess current provider's strengths/weaknesses
   - Understand contract term and switching timeline
   - Action owner: RM + Transaction Banking Product Manager
   
3. **Develop Transaction Banking Proposal** (Week 3-4)
   - Build business case: cost savings, operational efficiency, integration benefits
   - Propose 90-day pilot for subset of payment flows
   - Prepare competitive pricing (benchmark against incumbent)
   - Action owner: Transaction Banking Product Manager with RM support

**Medium-term Strategy (3-6 Months):**

1. **Phased Product Rollout**
   - Month 1-2: Implement transaction banking pilot
   - Month 3-4: If pilot successful, expand to full payment flows + add cash management
   - Month 5-6: Introduce FX and trade finance (leveraging transaction banking data integration)

2. **Relationship Expansion**
   - Establish relationships with Treasurer and VP Supply Chain
   - Invite client to bank-hosted industry CFO roundtable
   - Assign dedicated transaction banking relationship specialist

3. **Competitive Defense**
   - Monitor client satisfaction monthly during transition
   - Proactively address service issues before client escalates
   - Build switching costs through data integration and workflow automation

**Success Milestones:**
- 90 days: Transaction banking pilot live, processing $50M/month in payments
- 180 days: Full transaction banking deployment, $2M annual revenue
- 12 months: Share-of-wallet increased from 15% to 30% ($15M revenue vs. $7.5M baseline)

**Communication Approach:**

**Initial Pitch to CFO:**
- Lead with client benefit: "We've analyzed your banking relationships and identified $2M in potential annual savings through payment consolidation and treasury automation."
- Show wallet analysis: Visual chart showing fragmented banking relationships
- Propose collaborative approach: "We'd like to partner with your Treasurer to design a pilot that proves the business case before any commitment."

**Ongoing Engagement:**
- Monthly progress reports during pilot
- Quarterly business reviews showing achieved savings/efficiency
- Executive sponsorship: Bank's Head of Transaction Banking meets with CFO quarterly

**Objection Handling:**

- "Happy with current provider": "We understand. Our proposal is not to rip and replace immediately, but to pilot a small portion of your flows to prove value. No disruption to current operations."

- "Too complex to switch": "We've helped 50+ clients in your industry transition, and our average implementation is 60 days with zero payment failures. We'll manage the complexity."

- "Pricing not competitive": "Our proposal includes 12-month fee waivers and transition credits worth $100K. Our long-term pricing is within 5% of competitors, and the operational efficiency gains more than offset any rate difference."
```

#### Real-World Examples

**Critical:** These must be CONCRETE and SPECIFIC, not generic

**Good Example:**
```markdown
### Example 1: Manufacturing Client - Industrial Equipment

**Client Profile:**
- Company: $500M revenue manufacturer of industrial automation equipment
- Current wallet: $45M (estimated annual banking services spend)
- Bank's initial share: 18% ($8M revenue, primarily from $60M credit facility)

**Scenario Trigger:**
Annual account planning revealed wallet had grown from $38M to $45M year-over-year, but bank revenue remained flat at $8M. Wallet analysis showed client was using three other banks for transaction banking ($3M fees), FX hedging ($1.2M fees), and trade finance ($800K fees).

**RM Actions:**
1. Conducted deep-dive analysis of client's international operations (35% of revenue from exports)
2. Identified $1.2B in annual payment volumes being processed by competitor bank
3. Discovered client was manually reconciling payments across four banking platforms
4. Met with Treasurer who confirmed "banking fragmentation is a headache"

**Cross-Sell Execution:**
- Proposed integrated solution: consolidate payments, FX, and trade finance onto bank's platform
- Offered 6-month pilot for European payments only ($200M volume, low-risk test)
- Demonstrated ROI: 40% reduction in payment processing time, real-time FX pricing, and integrated trade documentation

**Outcomes:**
- Pilot successful after 4 months; client approved full rollout
- Over 18 months, bank captured additional $4.2M in revenue:
  - Transaction banking: $2.4M
  - FX services: $1.3M
  - Trade finance: $500K
- Share-of-wallet increased from 18% to 38%
- Client voluntarily reduced credit from $60M to $50M (had excess capacity), but total relationship revenue grew 53%

**Key Success Factors:**
- Led with client pain point (operational efficiency) not bank's sales objective
- Pilot approach reduced client risk and built confidence
- Product integration created switching costs and defensibility
- Client CFO became internal champion, helping sell to Treasurer and supply chain team
```

**Bad Example (don't do this):**
```markdown
### Example: Generic Client

A client had a large wallet but low share. The RM identified cross-sell opportunities and successfully increased wallet share through better products and service. The client was happy and the bank made more money. This shows the importance of wallet analysis.

[This is useless. No numbers, no specifics, no actionable learnings]
```

#### Data Schema Mapping

**Must be specific:**

```markdown
## Data Schema Mapping

### Required Tables

#### 1. Customer Wallet and KPI Details

**Columns Used:**
- `customer_id` - Client identifier for joining
- `banking_type` - Segment classification
- `year` - Data year for YOY comparison
- `kpi_label` - Metric identifier (use: "Gross Wallet", "Normalized Wallet", "Product Usage")
- `normalized_wallet_amount` - Bank's estimate of client's total wallet
- `gross_wallet_amount` - External data source wallet estimate
- `prior_year_value` - Previous year wallet for trend analysis
- `current_year_value` - Current wallet size
- `forecast_value` - Projected wallet growth
- `top_ranked_bucket` - Product categories where client spends most
- `cross_sell_flag` - Indicator of cross-sell potential
- `relationship_type` - Primary, secondary, or tertiary bank status

**Purpose:** Calculate share-of-wallet, identify product gaps, project growth potential

**Sample Query:**
```sql
-- Identify high-wallet, low-share clients for cross-sell targeting
SELECT 
    cmd.customer_id,
    cmd.customer_name,
    cmd.segment,
    cmd.relationship_manager_name,
    cwk.gross_wallet_amount AS total_wallet,
    mpa.total_revenue AS bank_revenue,
    ROUND((mpa.total_revenue / cwk.gross_wallet_amount) * 100, 1) AS share_of_wallet_pct,
    cwk.cross_sell_flag,
    cwk.top_ranked_bucket AS opportunity_products
FROM 
    customer_master_directory cmd
JOIN 
    customer_wallet_kpi cwk ON cmd.customer_id = cwk.customer_id
JOIN 
    monthly_profitability_aggregate mpa ON cmd.customer_id = mpa.customer_id
WHERE 
    cwk.gross_wallet_amount > 25000000  -- Wallet > $25M
    AND (mpa.total_revenue / cwk.gross_wallet_amount) < 0.25  -- SOW < 25%
    AND cmd.status = 'Active'
    AND cmd.current_record_flag = 'Y'
    AND cwk.year = 2024
ORDER BY 
    cwk.gross_wallet_amount DESC;
```

#### 2. Monthly Profitability Aggregate (KAP View)

**Columns Used:**
- `customer_id` - Client identifier
- `monthly_key` - Time dimension for trend analysis
- `total_revenue` - Overall client revenue for SOW calculation
- `transaction_banking_revenue` - Product-specific penetration
- `corporate_finance_revenue` - Product-specific penetration
- `markets_revenue` - Product-specific penetration
- `net_interest_income` - Lending revenue component
- `fee_income` - Non-interest revenue component
- `funded_assets` - Credit exposure for product mix
- `deposits` - Deposit balances for cash management opportunity

**Purpose:** Baseline current product penetration, calculate product-specific revenue, identify cross-sell gaps

**Sample Query:**
```sql
-- Analyze product penetration and identify zero-usage product lines
SELECT 
    customer_id,
    SUM(total_revenue) AS total_annual_revenue,
    SUM(transaction_banking_revenue) AS tx_banking_revenue,
    SUM(corporate_finance_revenue) AS corp_finance_revenue,
    SUM(markets_revenue) AS markets_revenue,
    CASE 
        WHEN SUM(transaction_banking_revenue) = 0 THEN 'Cross-sell Opportunity'
        ELSE 'Current User'
    END AS tx_banking_status,
    CASE 
        WHEN SUM(markets_revenue) < 100000 THEN 'Minimal Usage'
        ELSE 'Active User'
    END AS fx_derivatives_status
FROM 
    monthly_profitability_aggregate
WHERE 
    monthly_key BETWEEN '2024-01' AND '2024-12'
GROUP BY 
    customer_id
HAVING 
    SUM(total_revenue) > 5000000;  -- Min $5M annual revenue
```

#### 3. Account Planning Report Header

**Columns Used:**
- `plan_id` - Plan identifier
- `customer_id` - Client link
- `plan_year` - Planning period
- `strategy_narrative` - Strategic objectives and context
- `relationship_narrative` - Client relationship history and priorities
- `internal_rating` - Risk rating
- `total_exposure` - Current credit exposure
- `funded_limit` - Approved funded facilities
- `unfunded_limit` - Approved unfunded commitments
- `issues_action_summary` - Known constraints or issues

**Purpose:** Understand strategic context, validate cross-sell aligns with plan, check risk capacity for expansion

**Sample Query:**
```sql
-- Retrieve account plan context for cross-sell validation
SELECT 
    apr.customer_id,
    cmd.customer_name,
    apr.strategy_narrative,
    apr.relationship_narrative,
    apr.internal_rating,
    apr.total_exposure,
    apr.funded_limit,
    (apr.funded_limit - apr.total_exposure) AS available_capacity,
    apr.issues_action_summary
FROM 
    account_planning_report_header apr
JOIN 
    customer_master_directory cmd ON apr.customer_id = cmd.customer_id
WHERE 
    apr.plan_year = 2024
    AND apr.approval_status = 'Approved';
```
```

#### Best Practices from Industry

**Source everything:**

```markdown
## Best Practices from Industry

### What Top RMs Do

1. **Wallet Analysis is Continuous, Not Annual**

Top-performing RMs conduct wallet analysis quarterly, not just during annual planning. They track wallet movement in real-time and alert on meaningful changes (±10% wallet shift, new product usage by competitor).

Source: "The State of Relationship Management in Corporate Banking," Deloitte Banking Practice, 2023. Survey of 200 corporate banking RMs showed top quartile performers conducted wallet reviews 3.8x per year vs. 1.2x for bottom quartile.

2. **Lead with Client Value, Not Bank Revenue**

Rather than pitching "we want more wallet share," effective RMs frame cross-sell in terms of client benefits: operational efficiency, cost reduction, risk mitigation, or strategic enablement.

Source: "Winning Corporate Banking Relationships," McKinsey & Company, 2022. Analysis of 500 cross-sell attempts found 68% success rate when pitched as "solving client problem" vs. 23% success rate when pitched as "use more of our products."

3. **Pilot Before Full Commitment**

For complex product transitions (especially transaction banking), best practice is to propose a limited pilot (specific payment type, single geography, subset of volume) to prove value before asking for full migration.

Source: Corporate Banking Best Practices Survey, BAI (Bank Administration Institute), 2023. 82% of successful transaction banking wins involved pilot phase; average pilot duration 90 days.

### Common Pitfalls to Avoid

1. **Ignoring Competitive Lock-In**

Pitfall: Assuming all products are equally winnable, even when client has multi-year technology contracts with incumbent providers (e.g., ERP-integrated payment systems).

How to Avoid: Always ask about contract terms, integration complexity, and switching costs before investing in detailed proposal. Focus on products with lower barriers to entry if high switching costs exist.

2. **Single-Threading Relationships**

Pitfall: Relying solely on CFO relationship to sell all products. CFO may not control all banking decisions (Treasurer often owns transaction banking, supply chain owns trade finance).

How to Avoid: Map decision-makers by product category. Build relationships with Treasurer, VP Supply Chain, Head of Risk Management—whoever controls the wallet for each product.

3. **Underestimating Implementation Complexity**

Pitfall: Promising 30-day implementations for transaction banking when average is 90-120 days, creating client disappointment and eroding trust.

How to Avoid: Set conservative timelines based on actual implementation data. Under-promise and over-deliver rather than reverse.

Source: "Why Corporate Banking Cross-Sell Initiatives Fail," American Banker Analysis, 2023.

### Success Metrics

**Primary KPIs:**

1. **Share-of-Wallet (SOW) Growth**
   - Definition: (Bank Revenue from Client / Client Total Wallet) × 100
   - Industry Benchmark: Top quartile relationships achieve 40-50% SOW (Source: RMA Annual Banking Survey 2023)
   - Target: Increase SOW by 10-15 percentage points over 12 months for focused accounts

2. **Product Penetration Rate**
   - Definition: (Number of Products Used / Number of Applicable Products) × 100
   - Industry Benchmark: Average corporate relationship uses 3.2 products; top quartile uses 5.1 products (Source: Deloitte Corporate Banking Study 2023)
   - Target: Increase products per client from baseline by +1 to +2 products

3. **Cross-Sell Conversion Rate**
   - Definition: (Successful Cross-Sells / Total Cross-Sell Opportunities Identified) × 100
   - Industry Benchmark: 35-40% conversion rate for targeted, well-qualified opportunities (Source: BAI Cross-Sell Effectiveness Research 2022)
   - Target: Maintain >40% conversion rate on prioritized opportunities

**Secondary KPIs:**

- Revenue per Client Growth Rate: Target 15-20% annual growth for focused cross-sell accounts
- Client Retention Rate for Multi-Product Clients: Target >95% (vs. ~85% for single-product)
- Time to First Cross-Sell: Target <6 months from relationship start

Source: "Corporate Banking Relationship Metrics that Matter," Bank Director Magazine, Q4 2023.
```

### Phase 3: Quality Enhancement

After populating all sections, enhance quality:

#### Specificity Check
- **Replace** "the RM should analyze data" → "The RM should query the Customer Wallet table to extract gross_wallet_amount and compare against total_revenue from Monthly Profitability Aggregate"
- **Replace** "identify opportunities" → "Score each product using a weighted model: 40% revenue potential, 30% strategic fit, 20% competitive position, 10% implementation complexity"
- **Replace** "significant amount" → "$25M+" or "20%+" or other precise threshold

#### Actionability Check
- Every recommendation should answer: What exactly? How exactly? When exactly?
- If an RM couldn't execute based solely on this document, it's not specific enough

#### Source Validation Check
- Every major claim should have a source
- Benchmarks must be cited
- Best practices must be attributed
- Examples should include source if from public case study

#### Professional Polish
- Check all calculations for accuracy
- Ensure SQL queries are syntactically correct
- Verify terminology is used correctly
- Proofread for clarity and conciseness

## Writing Standards

### Voice and Tone
- **Professional but practical:** Banking expert, not academic researcher
- **Directive but respectful:** "The RM should..." not "The RM must..."
- **Confident but qualified:** "Industry data shows..." with sources, not "It is widely known..."

### Formatting
- Use **bold** for emphasis on key terms or actions
- Use `code blocks` for queries, formulas, or system commands
- Use tables for comparisons or structured data
- Use bullets for lists of items
- Use numbered lists for sequential steps

### Sentence Structure
- **Prefer active voice:** "The RM analyzes the data" not "The data is analyzed"
- **Prefer concrete over abstract:** "Calculate SOW as (bank revenue / total wallet) × 100" not "Determine market share mathematically"
- **Prefer short, clear sentences** over long, complex ones
- **One idea per sentence** when possible

## Iteration-Specific Expectations

### Iteration 1: Foundation (60-70% Complete)
**Must Have:**
- All section headers populated
- Core RM actions documented (even if basic)
- At least 1 concrete example
- Primary data requirements identified
- Basic best practices included

**Can Be Missing:**
- Some advanced analysis details
- Secondary examples
- Complete SQL queries
- All tool recommendations
- Some risk considerations

### Iteration 2: Enrichment (85-90% Complete)
**Must Have:**
- All iteration 1 content enhanced
- 2+ concrete examples
- Complete data schema mapping with queries
- Detailed analytical frameworks
- Comprehensive best practices

**Can Be Missing:**
- Some edge cases
- Advanced tools not commonly used
- Tertiary risk considerations

### Iteration 3: Finalization (95-100% Complete)
**Must Have:**
- Everything from iterations 1 & 2
- All sections complete
- All sources validated
- Professional polish
- No critical gaps

**Should Have:**
- Related scenarios identified
- Additional reading suggested
- Advanced considerations included

## Common Compilation Mistakes

### Avoid:
❌ **Generic AI Writing:** "The RM should carefully consider all relevant factors..."
❌ **Unattributed Claims:** "Studies show..." without citing which studies
❌ **Vague Numbers:** "High percentage" instead of "65-70%"
❌ **Missing Context:** Formulas without explaining variables
❌ **Inconsistent Terminology:** Switching between "client" and "customer"
❌ **Copying from Sources:** Paraphrase and cite, don't plagiarize
❌ **Skipping Examples:** All framework, no concrete application

### Do:
✅ **Specific Banking Language:** Use proper terms (SOW, RAROC, covenant, syndication)
✅ **Cite All Claims:** Every number, benchmark, best practice has a source
✅ **Provide Context:** Explain why, not just what and how
✅ **Use Concrete Examples:** Real numbers, real situations, real outcomes
✅ **Maintain Consistency:** Same terminology throughout
✅ **Synthesize, Don't Copy:** Transform research into original guidance
✅ **Ground in Reality:** Every recommendation should be executable

## Completion Checklist

Before moving to Review phase:

**Content Completeness:**
- [ ] All required sections have substantive content
- [ ] Executive Summary captures essence
- [ ] RM Action Framework has 4 detailed steps
- [ ] At least 1 concrete example included (Iteration 1) or 2+ (Iterations 2-3)
- [ ] Data Schema Mapping includes specific tables and columns
- [ ] At least 3 best practices included with sources

**Quality Standards:**
- [ ] All numbers and benchmarks are cited
- [ ] Examples are specific and realistic
- [ ] SQL queries are syntactically valid
- [ ] Banking terminology is used correctly
- [ ] Voice is professional and practical
- [ ] No generic AI writing patterns

**Source Documentation:**
- [ ] All claims have sources
- [ ] Research Sources section is complete
- [ ] URLs are included for all citations
- [ ] Publication dates are noted

**Iteration-Appropriate Depth:**
- [ ] Meets depth expectations for current iteration
- [ ] Identified gaps are acceptable for this iteration
- [ ] Ready for review feedback

## Next Step
Proceed to **skills/04_review.md** to assess quality and identify gaps for next iteration.
