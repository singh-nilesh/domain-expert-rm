# Skill 01: Research Planning

## Purpose
Create a research plan to capture expert domain knowledge, RM thinking, and best practices for this scenario.

## When to Use
- At the start of researching a scenario identified in `status.md` as "Current Scenario"
- This is STEP 1 of the pipeline

## Input Requirements
1. Scenario number and title from `status.md`
2. Scenario description from `raw/RM_Agent_Scenarios.md`

## Research Goal

**NOT:** "Gather information about this topic"
**YES:** "Understand how expert RMs think about and approach this situation, what mental models guide them, and what outcomes they achieve"

## Planning Process

### Step 1: Understand the Scenario

Extract:
- **Core Challenge:** What problem are RMs solving?
- **Why It Matters:** What's the business impact?
- **Expert Perspective:** How do top performers view this?
- **Decision Points:** Where do RMs make critical choices?

### Step 2: Research Questions (Focus on Expert Thinking)

Create questions revealing expert domain knowledge:

1. **Mental Models:** What frameworks do expert RMs use to analyze this situation?
2. **Decision Logic:** How do top performers decide what to do? What are their decision criteria?
3. **Red Flags & Triggers:** What signals do experts recognize that others miss?
4. **Benchmarks & Thresholds:** What specific numbers/metrics guide decisions?
5. **Best Practices:** What do top performers do differently? Specific examples?
6. **Risk Management:** What risks do experts actively manage? How?
7. **Case Studies:** Real outcomes: companies, situations, results achieved

### Step 3: Search Topics

**RM Expertise & Thought Leadership**
- "McKinsey corporate banking [scenario] expert approach"
- "[Scenario area] mental models banking experts"
- "Best-in-class RMs [scenario]"
- "Banking thought leaders [scenario]"

**Expert Decision-Making**
- "[Scenario] how RMs analyze this situation"
- "Expert frameworks for [scenario] assessment"
- "[Scenario] decision making in corporate banking"
- "What top RMs do differently"

**Case Studies & Real Examples**
- "[Scenario] case studies banks"
- "[Company] transaction banking example"
- "[Scenario] successful outcomes corporate banking"
- "Real-world [scenario] implementations"

**Industry Benchmarks & Standards**
- "[Scenario] benchmarks corporate banking"
- "[Scenario] success metrics industry standards"
- "Industry best practices [scenario]"
- "[Scenario] thresholds and triggers"

**Risk & Compliance Considerations**
- "[Scenario] risk management approaches"
- "[Scenario] compliance considerations banking"
- "[Scenario] regulatory guidance"

### Step 4: Success Criteria

Document must include:
- ✅ Expert RM thought process clearly explained
- ✅ Mental models and decision frameworks
- ✅ 2+ concrete case studies with numbers and outcomes
- ✅ Specific benchmarks, thresholds, and metrics
- ✅ How top performers approach this differently
- ✅ 5+ credible sources (consulting firms, industry experts, publications)
- ✅ Risk management and compliance guidance
- ✅ 300-500 lines of expert-level content
- ✅ NO SQL queries or database schema references

## Output Format

Create a simple research plan document:

```markdown
# Research Plan: Scenario XXX - [Title]

## Scenario Summary
[2-3 sentence summary]

## Research Objectives
Primary: [Main objective]
Secondary: [Supporting objectives]

## 7 Key Research Questions
1. [Question 1]
2. [Question 2]
...
7. [Question 7]

## Iteration 1 Searches (5-7 searches)
1. "[search query 1]" → Expected to find: [what]
2. "[search query 2]" → Expected to find: [what]
3. "[search query 3]" → Expected to find: [what]
4. "[search query 4]" → Expected to find: [what]
5. "[search query 5]" → Expected to find: [what]
6. "[search query 6]" → Expected to find: [what]
7. "[search query 7]" → Expected to find: [what]

## Iteration 2 Searches (if needed - gap-filling)
[Targeted searches based on Iteration 1 gaps]

## Iteration 3 Searches (if needed - validation)
[Confirmation searches]

## Required Content Sections (Priority)

### Must-Have (Core)
- RM Action Framework (4 steps)
- Data Schema Mapping
- Real-World Examples (2+)
- Best Practices from Industry

### Should-Have (Important)
- Risk Considerations
- Tools and Resources
- Success Metrics
- Sample Queries

### Nice-to-Have (Enhancement)
- Related Scenarios
- Additional Reading
- Advanced Frameworks

## Success Criteria Checklist
- [ ] All research questions identified
- [ ] Search queries are specific and banking-focused
- [ ] Iteration 1 plan can be executed
- [ ] Success criteria are measurable
- [ ] Ready to proceed to 02_search.md
```

## Best Practices

### DO:
✅ Be specific (not "research the topic" but "find SOW calculation formulas")
✅ Prioritize practitioner content
✅ Build searches logically (foundational → specific → validation)
✅ Include validation searches
✅ Set clear, measurable success criteria
✅ Plan for depth across iterations

### DON'T:
❌ Create vague search plans
❌ Plan too many Iteration 1 searches (diminishing returns)
❌ Ignore data schema mapping requirement
❌ Plan searches without expected outcomes
❌ Set impossible quality standards
❌ Plan to find everything in one iteration

---

**Before proceeding to 02_search.md:**
- [ ] Research questions are specific and answerable
- [ ] Search topics identified for all categories
- [ ] Success criteria are clear
- [ ] Ready to execute Iteration 1 searches


## Planning Process

### Step 1: Understand the Scenario Core
Read the scenario description carefully and extract:

**Primary Objective:**
- What is the RM trying to accomplish?
- What problem are they solving?
- What opportunity are they pursuing?

**Key Banking Domain:**
- Which area? (Credit, Risk, Sales, Portfolio Management, Client Service, Strategy)
- Which products involved? (Lending, Transaction Banking, FX, Advisory, etc.)
- Which stakeholders? (RM, Client, Credit Team, Product Managers, etc.)

**Data Requirements:**
- Which tables from the schema are involved?
- What external data might be needed?
- What calculations or analysis are required?

### Step 2: Formulate Research Questions

Create 5-7 specific research questions that must be answered. Format:

```
1. [Research Question 1: Focus on RM actions]
   Example: "What specific steps does an RM take to identify cross-sell opportunities?"

2. [Research Question 2: Focus on data analysis]
   Example: "How do RMs calculate share-of-wallet and what benchmarks do they use?"

3. [Research Question 3: Focus on best practices]
   Example: "What are industry best practices for pricing cross-sell products?"

4. [Research Question 4: Focus on tools/systems]
   Example: "What CRM or analytical tools do RMs typically use for this?"

5. [Research Question 5: Focus on risk/compliance]
   Example: "What compliance considerations exist for cross-sell campaigns?"

6. [Research Question 6: Focus on success metrics]
   Example: "How do banks measure success of cross-sell initiatives?"

7. [Research Question 7: Focus on real examples]
   Example: "What are documented case studies of successful cross-sell campaigns?"
```

### Step 3: Identify Search Topics

For each research question, list specific search topics:

**Search Topic Categories:**

1. **Process and Methodology**
   - "corporate banking [scenario focus] process"
   - "relationship manager [scenario focus] methodology"
   - "commercial banking [scenario focus] framework"

2. **Data and Analytics**
   - "[scenario focus] data requirements banking"
   - "[scenario focus] KPI metrics corporate banking"
   - "[scenario focus] analysis methodology"

3. **Best Practices**
   - "[scenario focus] best practices banking"
   - "[scenario focus] industry standards"
   - "successful [scenario focus] case studies banking"

4. **Tools and Technology**
   - "[scenario focus] banking software"
   - "[scenario focus] CRM tools commercial banking"
   - "[scenario focus] analytics platforms"

5. **Risk and Compliance**
   - "[scenario focus] compliance requirements banking"
   - "[scenario focus] risk management"
   - "[scenario focus] regulatory guidance"

6. **Industry Research**
   - "McKinsey [scenario focus] banking"
   - "Deloitte [scenario focus] commercial banking"
   - "American Banker [scenario focus]"

### Step 4: Define Success Criteria

Specify what a complete research output looks like:

**Required Elements:**
- [ ] Minimum 5 credible sources cited
- [ ] At least 2 concrete examples with numbers
- [ ] Specific data requirements mapped to schema tables
- [ ] Step-by-step RM action framework
- [ ] Calculation formulas with sample numbers
- [ ] Industry benchmarks with sources
- [ ] Risk/compliance considerations
- [ ] Tools/systems recommendations

**Quality Benchmarks:**
- Specificity: 9/10 (very specific, not generic)
- Practicality: 9/10 (immediately actionable)
- Depth: 8/10 (expert-level, not surface)
- Validation: 8/10 (multiple source confirmation)

### Step 5: Estimate Iteration Strategy

Plan how to allocate effort across iterations:

**Iteration 1 Focus:**
- Foundational understanding of the scenario
- Core RM actions and data requirements
- Basic best practices and examples
- Target: 60-70% completeness

**Iteration 2 Focus (if needed):**
- Fill specific gaps identified in review
- Add more examples and case studies
- Deepen analytical frameworks
- Validate calculations and benchmarks
- Target: 85-90% completeness

**Iteration 3 Focus (if needed):**
- Polish and refine language
- Add final missing elements
- Validate all sources
- Ensure all quality criteria met
- Target: 95-100% completeness

## Output Format

Create a research plan document in this structure:

```markdown
# Research Plan: Scenario XXX - [Title]

## Scenario Summary
[2-3 sentence summary of what this scenario is about]

## Research Objectives
Primary: [Main objective]
Secondary: [Supporting objectives]

## Research Questions
1. [Question 1]
2. [Question 2]
...
7. [Question 7]

## Search Strategy

### Iteration 1 Searches (Foundation)
- Search 1: "[search query]" → Expected to find: [what]
- Search 2: "[search query]" → Expected to find: [what]
- Search 3: "[search query]" → Expected to find: [what]
- Search 4: "[search query]" → Expected to find: [what]
- Search 5: "[search query]" → Expected to find: [what]

### Iteration 2 Searches (if needed - Enrichment)
- [Targeted searches based on gaps]

### Iteration 3 Searches (if needed - Validation)
- [Validation and final polish searches]

## Required Sections Priority

### Must-Have (Core)
- RM Action Framework (Steps 1-4)
- Data Schema Mapping
- Real-World Examples (at least 2)
- Best Practices from Industry

### Should-Have (Important)
- Risk Considerations
- Tools and Resources
- Success Metrics
- Sample Queries

### Nice-to-Have (Enhancement)
- Related Scenarios
- Additional Reading
- Extended Examples
- Advanced Frameworks

## Success Criteria Checklist
- [ ] All core sections complete
- [ ] 5+ credible sources
- [ ] 2+ concrete examples with numbers
- [ ] Specific data requirements
- [ ] Calculations with formulas
- [ ] Industry benchmarks cited
- [ ] Quality score 8/10+

## Estimated Effort
- Iteration 1: [X searches, Y sections, ~Z time]
- Iteration 2: [contingent on gaps]
- Iteration 3: [contingent on gaps]
```

## Planning Best Practices

### DO:
✅ Be specific about what you need to find
✅ Prioritize practitioner content over theoretical
✅ Plan searches that build on each other logically
✅ Include validation searches to confirm findings
✅ Set clear success criteria before starting
✅ Plan for incrementing depth across iterations

### DON'T:
❌ Create vague search plans ("research the topic")
❌ Plan too many searches for iteration 1 (diminishing returns)
❌ Ignore the data schema mapping requirement
❌ Plan searches without clear expected outcomes
❌ Set unrealistic quality standards that can't be met
❌ Plan to find everything in one iteration

## Iteration-Specific Planning Guidance

### For Iteration 1 (Foundation)
**Goal:** Build the skeleton with core content

**Focus On:**
- Understanding the basic scenario mechanics
- Identifying primary RM actions
- Finding 1-2 good examples
- Mapping data requirements at high level
- Establishing basic best practices

**Search Volume:** 5-7 searches
**Acceptable Gaps:** Missing details, limited examples, basic frameworks

### For Iteration 2 (Enrichment)
**Goal:** Fill gaps and add depth

**Focus On:**
- Specific gaps identified in review
- Additional concrete examples
- Deeper analytical frameworks
- Validation of calculations
- Enhanced tool/system details

**Search Volume:** 3-5 targeted searches
**Acceptable Gaps:** Minor details, some advanced content

### For Iteration 3 (Finalization)
**Goal:** Polish to publication quality

**Focus On:**
- Final quality gaps
- Source validation
- Completeness check
- Professional polish
- Final examples or benchmarks

**Search Volume:** 2-3 validation searches
**Acceptable Gaps:** None (this is final)

## Example Research Plan

```markdown
# Research Plan: Scenario 1 - Cross-Sell Targeting for High-Potential Clients

## Scenario Summary
An RM identifies a client with high gross wallet size but low bank share-of-wallet, indicating significant cross-sell opportunity. The RM must analyze wallet data, identify specific product gaps, and develop a targeted cross-sell strategy.

## Research Objectives
Primary: Document the step-by-step process RMs use to identify and execute cross-sell opportunities
Secondary: Identify industry benchmarks for wallet share, cross-sell success rates, and prioritization frameworks

## Research Questions
1. How do RMs calculate share-of-wallet and what data sources do they use?
2. What frameworks exist for prioritizing cross-sell opportunities across products?
3. What are typical conversion rates for cross-sell campaigns in corporate banking?
4. How do RMs determine which products to pitch based on client profile?
5. What compliance or risk considerations affect cross-sell strategies?
6. What CRM or analytical tools are commonly used for cross-sell management?
7. What are documented case studies of successful corporate banking cross-sell?

## Search Strategy

### Iteration 1 Searches (Foundation)
- Search 1: "corporate banking share of wallet calculation" → Expected: formulas, benchmarks
- Search 2: "relationship manager cross-sell best practices" → Expected: methodologies, processes
- Search 3: "commercial banking cross-sell framework" → Expected: prioritization models
- Search 4: "banking CRM cross-sell analytics" → Expected: tools, systems, data requirements
- Search 5: "corporate banking cross-sell case study" → Expected: real examples with outcomes

### Iteration 2 Searches (Enrichment)
- [Based on gaps - likely: specific product penetration benchmarks, risk considerations]

### Iteration 3 Searches (Validation)
- [Based on gaps - likely: validate calculations, confirm compliance requirements]

## Required Sections Priority

### Must-Have (Core)
- RM Action Framework: Data gathering (wallet data, product usage), Analysis (SOW calc), Insight generation, Recommendation development
- Data Schema Mapping: Customer Wallet and KPI details, Monthly profitability Aggregate
- Real-World Examples: 2 cases with wallet sizes, SOW %, products pitched, outcomes
- Best Practices: Industry cross-sell methodologies

### Should-Have (Important)
- Risk Considerations: Credit limits, relationship impact
- Tools: CRM systems, wallet analysis tools
- Success Metrics: SOW improvement, cross-sell conversion rate
- Sample Queries: SQL to identify high-wallet low-capture clients

### Nice-to-Have (Enhancement)
- Related Scenarios: Wallet growth tracking, product penetration analysis
- Advanced frameworks: Next-product-to-buy models, propensity scoring

## Success Criteria Checklist
- [ ] SOW calculation formula documented
- [ ] Product prioritization framework included
- [ ] 2+ case studies with numbers
- [ ] Data requirements mapped to specific tables
- [ ] Industry benchmarks for SOW and conversion
- [ ] Compliance considerations addressed
- [ ] Quality score 8/10+

## Estimated Effort
- Iteration 1: 5 searches, 8 sections, ~foundation
- Iteration 2: 3 searches, gap-filling, ~enrichment
- Iteration 3: 2 searches, validation, ~finalization
```

## Final Checklist

Before proceeding to Search phase:
- [ ] Research questions are specific and answerable
- [ ] Search queries are precise with banking terminology
- [ ] Success criteria are clear and measurable
- [ ] Required sections are prioritized
- [ ] Iteration strategy is realistic
- [ ] Expected outcomes are defined for each search

## Next Step
Proceed to **skills/02_search.md** to execute the search strategy.
