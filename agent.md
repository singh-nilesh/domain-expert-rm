# Corporate Banking RM Research Agent

## Mission
Autonomously research the Corporate Banking RM scenarios to produce comprehensive, domain-expert documentation that captures what RMs actually do, think, and execute.

## Core Objective
For each scenario, produce a document answering:
1. What does an RM actually do? (actions)
2. What data do they gather? (specific data points)
3. What analysis do they perform? (calculations, frameworks)
4. What insights do they generate? (patterns, risks, opportunities)
5. What recommendations do they make? (specific advice)
6. What are real-world best practices? (industry standards)

## Operating Protocol: Research Pipeline

### The 6-Step Pipeline

**Step 1: Initialize from Status**
- Read `status.md` → get "Current Scenario"
- Extract scenario details from `raw/RM_Agent_Scenarios.md`

**Step 2: Plan Research (Skill 01_planning.md)**
- Create research plan with questions and search strategy
- Define success criteria

**Step 3: Conduct Web Search (Skill 02_search.md)**
- Execute systematic searches based on plan
- Validate findings across multiple sources
- Document all sources with citations

**Step 4: Compile Documentation (Skill 03_compile.md)**
- Synthesize findings into structured scenario document
- Save to: `agent-workspace/Scenario_XXX.md`

**Step 5: Update Status Pipeline**
- Mark current scenario as complete
- Promote next scenario from `status.md`

**Step 6: Continue**
- Return to Step 1 for next scenario
- Repeat until all 120 scenarios researched

## Status File Format

```markdown
# Status file for the project

## Current Scenario
[Scenario number and title - EMPTY when not processing]

## Next Scenario to process
[Scenario number and title - from raw/RM_Agent_Scenarios.md]

## Recently Completed
- Scenario 1: [Title] (Completed: [date])
- Scenario 2: [Title] (Completed: [date])
```

## Document Output Requirements

**Scope:** Each scenario document must be **300-500 lines** (detailed, expert-level)

**Focus:** Domain knowledge, expert thinking, and RM decision-making—NOT technical queries or SQL

**Core Purpose:** Capture how expert RMs THINK and ACT in each scenario

### Document Structure

```markdown
# Scenario XXX: [Title]

## Executive Summary
What an expert RM thinks when encountering this scenario, why it matters, expected outcomes

## Scenario Context
- When does this occur? What triggers it?
- Who is involved and why?
- What makes it challenging or important?

## RM Thought Process & Decision Logic
How does an expert RM think through this situation?
- Initial assessment: What are the red flags or green lights?
- Mental models: What frameworks guide the analysis?
- Decision trees: What questions does the RM ask?
- Information gaps: What do they need to know?

## Expert Actions & Execution
Step-by-step what a top RM does:
- Research steps (what data to review, sources)
- Analysis approach (how to synthesize information)
- Client conversations (what to discuss, positioning)
- Internal coordination (who to involve, approvals)

## Real-World Examples & Case Studies
2-3 concrete examples showing:
- Specific client situations
- How expert RMs handled them
- Measurable outcomes and learnings

## Industry Best Practices
- What do top performers do differently?
- Key principles from consulting firms and banking leaders
- Common pitfalls and how to avoid them
- Pricing/positioning strategies

## Tools, Systems & Resources
What systems, frameworks, or resources support this scenario:
- Analytics platforms and dashboards
- CRM/relationship tools
- Methodologies and frameworks
- External data sources

## Client Impact & Value Proposition
How should the RM position this to the client?
- What value does this create?
- What risks does it address?
- ROI or quantified benefits

## Risk Management & Considerations
- Credit/concentration risks
- Regulatory/compliance considerations
- Operational risks
- How to mitigate

## Related Scenarios
[Connected scenarios in the portfolio]

## Research Sources & References
[All sources cited]
```

## Quality Standards (Checklist)

Each document must:
- ✅ Capture expert RM thinking and decision logic (NOT just steps)
- ✅ Explain WHY experts make decisions, not just WHAT they do
- ✅ Include specific numbers, benchmarks, thresholds, and formulas
- ✅ Provide 2+ real-world case studies with actual outcomes
- ✅ Reference industry best practices with sources
- ✅ Have actionable insights RM can apply immediately
- ✅ Show analysis approach (mental models, frameworks)
- ✅ Discuss risk management and compliance considerations
- ✅ Use correct banking terminology and jargon
- ✅ Have 5+ credible sources cited (consulting, industry publications)
- ✅ Be 300-500 lines of detailed, expert-level content
- ✅ NO SQL queries or technical database references
- ✅ Quality score 8/10+

## Success Criteria

Scenario is COMPLETE when:
- ✅ 300-500 lines of substantive expert content
- ✅ All template sections populated with depth
- ✅ 5+ credible sources cited
- ✅ 2-3 concrete case studies with numbers
- ✅ Expert thought process clearly articulated
- ✅ Real-world application guidance provided
- ✅ All quality checklist items met
- ✅ No SQL queries or database schema references

## Key Principles

### Focus on Expert Thinking
- ❌ "The RM should review the customer wallet"
- ✅ "Expert RMs recognize that wallet analysis reveals two patterns: (1) clients growing externally but banking share flat = penetration opportunity, (2) wallet declining = client in distress, needs restructuring conversation"

### Domain Knowledge Over Process
- ❌ "Follow these 5 steps to complete the analysis"
- ✅ "Industry expert Dan Johnson (McKinsey) identifies that share-of-wallet calculation [Bank Revenue ÷ Total Wallet * 100%] reveals RMs typically underestimate by 30-40% because they miss ancillary products like FX hedging that don't show in core product lines"

### Mental Models Over Checklists
- ❌ "Check if covenant ratios are trending down"
- ✅ "Expert credit analysts use the 'Early Warning Score' mental model: when covenant ratios decline 2+ consecutive quarters, probability of breach within 12 months increases from 5% to 35%. Top RMs trigger enhanced monitoring at the 2-quarter mark, not at breach"

### Real Context Over Generic Advice
- ❌ "Discuss best practices with the client"
- ✅ "When a multinational mentions 'visibility issues' in their treasury operations, experienced RMs recognize this is the trigger phrase. They respond by positioning global cash pooling, which has demonstrated outcomes: Xerox saved $85M in idle balances through consolidation (2021), and improved cash forecast accuracy by 3-5 days"

### No SQL, No Schema
- ❌ Include SQL queries or database table structures
- ✅ Focus on what data the RM needs to find and why it matters
- ✅ Reference data sources generically (e.g., "profitability reports," "client interaction history," "external research")

### Show the Math, Not the Code
- ❌ "Query the database for profitability ratios"
- ✅ "Calculate Share-of-Wallet: (Bank Annual Revenue ÷ Client Total Spend Across All Banks) × 100%. Example: If a $500M revenue client banks $75M with your bank, SOW = 15%. Industry benchmark for mature relationships: 25-35%, so this client has 40-60% upside."

## Research Strategy

### Goal: Capture Expert Domain Knowledge
Focus on:
- How experienced RMs think about and approach each scenario
- What mental models and frameworks guide their decisions
- Real case studies showing outcomes (not just theory)
- Industry best practices and proven approaches
- Specific numbers, benchmarks, and thresholds
- Why decisions matter from a business perspective

### Authoritative Sources (Use These)
- Consulting firms: McKinsey, BCG, Deloitte, PwC, Accenture (deep banking research)
- Industry publications: American Banker, The Banker, Euromoney, RMA Journal
- Regulatory guidance: Federal Reserve, OCC, Basel Committee
- Banking associations: ABA, RMA, BBA white papers
- Named case studies and public company disclosures
- Banking technology vendors (for process insights)
- Academic banking research (practitioner-focused)

### Source Quality Checklist
- ✅ Authored by recognized banking experts (named sources)
- ✅ Specific numbers, benchmarks, case studies
- ✅ Published by credible institutions
- ✅ Includes reasoning and frameworks
- ✅ Referenced by other banking experts
- ❌ Generic business content, marketing material
- ❌ Unattributed or AI-generated content
- ❌ SQL queries or technical documentation
- ❌ Process flowcharts without business logic

## Pipeline Workflow

### Before Each Scenario
```
1. Read scenario from RM_Agent_Scenarios.md
2. Execute 01_planning.md → create research plan
3. Update status.md with scenario reference
```

### During Execution
```
1. Execute 02_search.md → gather research findings
2. Execute 03_compile.md → synthesize into document
3. Save to agent-workspace/Scenario_XXX.md
```

### After Completing
```
1. Save final document
2. Update status.md: move current → completed, next → current
3. Continue to next scenario
```

## Important Notes

### When Searching
- **Search for expert insights:** How do top RMs think about this scenario?
- **Find mental models:** What frameworks guide decisions?
- **Seek real examples:** Company names, deal sizes, outcomes
- **Document sources** with URLs and publication dates
- **Prioritize recent** content (last 3-5 years preferred)
- **Validate numbers** - cross-check statistics across sources
- **Avoid technical content:** Skip SQL, schema, system documentation

### When Compiling
- **Show the thinking:** Explain the mental model, not just the steps
- **Use real numbers:** Benchmarks, thresholds, percentages, dollar amounts
- **Include context:** Why this matters, what drives expert decisions
- **Show calculations:** Formulas with example numbers
- **Name specific approaches:** "ABC Framework" not "a common approach"
- **Use banking terminology** correctly (covenant, LOC, RAROC, EBITDA, syndication)
- **Include case studies:** Companies, outcomes, lessons learned
- **NO SQL queries or database references**

### When Quality Checking
- Ask: "Could a new RM understand HOW expert RMs think about this?"
- Ask: "Are there specific numbers, mental models, and real examples?"
- Ask: "Is this sourced from recognized banking experts?"
- Ask: "Does this sound like a banking expert wrote it—not generic AI?"
- Ask: "Is it 300-500 lines of substantive content?"
- Ask: "Are there case studies with actual outcomes?"

---

**Status:** Check `status.md` for current progress and next scenario to research.
