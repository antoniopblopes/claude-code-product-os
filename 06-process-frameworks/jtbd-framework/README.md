# Jobs-to-be-Done Framework

Strategic methodology for uncovering customer jobs and defining outcome-driven product development. Based on Tony Ulwick's Outcome-Driven Innovation (ODI) methodology.

## 🎯 Framework Purpose

Help product teams understand what customers are truly trying to accomplish, moving beyond demographic segmentation to job-based market definition and feature prioritization.

## 📚 Core Concepts

### The Job Statement
**When [situation], I want to [motivation], so I can [expected outcome].**

### The Outcome Statement Structure  
**Direction + Performance Metric + Object + Context**

Examples:
- "Minimize the time it takes to **complete onboarding** when starting with a new tool"
- "Increase the likelihood that **decisions are well-informed** when working with incomplete data"
- "Reduce the effort required to **coordinate with stakeholders** when timelines change"

## 🔄 JTBD Discovery Process

### 1. Job Identification (Week 1)
**Goal**: Define the core functional job your customers hire your product to do

**Activities**:
- Customer interviews focused on recent job execution
- Job mapping across the complete workflow  
- Abstraction testing to find the right job level

**Deliverable**: Primary job statement and job map

### 2. Outcome Discovery (Week 2-3)
**Goal**: Identify all the ways customers measure success when executing the job

**Activities**:
- Outcome brainstorming sessions
- Customer validation of outcome importance/satisfaction
- Outcome categorization and prioritization

**Deliverable**: Prioritized outcome list with importance/satisfaction scores

### 3. Opportunity Identification (Week 4)
**Goal**: Calculate opportunity scores to identify unmet needs

**Formula**: `Opportunity Score = Importance + (Importance - Satisfaction)`

**Activities**:
- Quantitative outcome assessment via surveys
- Opportunity score calculation and ranking
- Market segmentation based on unmet outcomes

**Deliverable**: Opportunity landscape with target segments

### 4. Solution Ideation (Week 5-6)
**Goal**: Generate solutions that address highest opportunity outcomes

**Activities**:
- Solution brainstorming focused on outcome gaps
- Concept development and early validation
- Feature/solution roadmap creation

**Deliverable**: Solution concepts prioritized by opportunity impact

## 🎯 Job Discovery Interview Protocol

### Interview Structure (45-60 minutes)

#### Opening (5 minutes)
"I'm trying to understand how [customer type] approaches [broad job area]. Can you walk me through the last time you needed to [accomplish core job]?"

#### Job Definition (15 minutes)
1. **Scope Discovery**: "What were you ultimately trying to accomplish?"
2. **Context Mapping**: "What led up to that need?"  
3. **Success Definition**: "How did you know when you were done?"
4. **Abstraction Test**: "If your current tools disappeared, what would still need to happen?"

#### Job Mapping (25 minutes)
Walk through the universal job steps:

1. **Define**: "How did you determine what needed to be accomplished?"
2. **Locate**: "How did you find the right resources/information?"
3. **Prepare**: "What setup work was required?"
4. **Confirm**: "How did you validate your approach?"
5. **Execute**: "What was the actual execution process?"
6. **Monitor**: "How did you track progress and quality?"
7. **Modify**: "When and how did adjustments happen?"
8. **Conclude**: "What did completion look like and how did you transition?"

#### Outcome Identification (10 minutes)
For each job step: "What are all the ways this step could go wrong or be improved?"

#### Wrap-up (5 minutes)
"What haven't we covered that's important for understanding this job?"

## 📊 Outcome Assessment Framework

### Outcome Survey Template

**For each outcome statement, ask:**

1. **Importance**: "How important is it to [outcome statement] when [executing job]?"
   - Scale: 1-5 (Not important → Extremely important)

2. **Satisfaction**: "How satisfied are you with your current ability to [outcome statement]?"  
   - Scale: 1-5 (Very dissatisfied → Very satisfied)

### Opportunity Scoring
- **High Opportunity** (>12): Important but poorly satisfied
- **Medium Opportunity** (8-12): Moderately important with satisfaction gaps  
- **Low Opportunity** (<8): Well-served or less important

### Segmentation Analysis
Group customers by outcome satisfaction patterns:
- **Underserved**: Low satisfaction across multiple high-importance outcomes
- **Overserved**: High satisfaction, may prefer simpler/cheaper solutions
- **Appropriately Served**: Satisfaction matches importance across outcomes

## 🛠️ Implementation Templates

### Job Story Template
```
As a [type of customer]
When I [situation/context]  
I want to [motivation/job]
So that [expected outcome]
```

### Feature Prioritization Framework
1. **Outcome Impact**: Which high-opportunity outcomes does this address?
2. **Job Alignment**: How directly does this support the core job?
3. **Effort Estimate**: What's the implementation complexity?
4. **Success Metrics**: How will we measure outcome improvement?

### Roadmap Planning
- **Now** (0-3 months): Highest opportunity, lowest effort outcomes
- **Next** (3-6 months): High opportunity outcomes requiring more investment
- **Later** (6+ months): Important outcomes requiring significant development

## ✅ Success Criteria

### Process Success
- [ ] Clear job statement that resonates with customers
- [ ] Comprehensive outcome list with quantified importance/satisfaction  
- [ ] Identified opportunity gaps with statistical significance
- [ ] Solutions mapped to specific unmet outcomes

### Business Impact
- [ ] Feature requests aligned to customer outcomes vs. internal assumptions
- [ ] Product roadmap prioritized by market opportunity size
- [ ] Customer segments defined by outcome needs vs. demographics
- [ ] Success metrics tied to outcome improvement vs. feature usage

## 🚨 Common Pitfalls

### ❌ Avoid These Mistakes
- **Solution-focused interviews**: Asking what features customers want
- **Demographic segmentation**: Assuming age/industry predicts job needs  
- **Internal outcome bias**: Prioritizing outcomes that support existing features
- **Satisfaction-only focus**: Building for happy customers vs. growth opportunities

### ✅ Best Practices
- **Stay job-focused**: Always return to the functional job being executed
- **Quantify everything**: Use statistical rigor for opportunity identification  
- **Validate assumptions**: Test job statements and outcomes with customers
- **Think systems**: Consider the complete job ecosystem, not just your product's role

## 📈 Advanced Applications

### Competitive Strategy
- Map competitor solutions to outcome performance
- Identify white space opportunities in outcome landscape
- Position product based on outcome differentiation

### Pricing Strategy  
- Price based on outcome value delivered
- Create packages aligned to different outcome priorities
- Justify premium pricing through superior outcome performance

### Innovation Pipeline
- Generate breakthrough ideas by examining unaddressed outcomes
- Evaluate acquisition targets based on outcome complementarity
- Guide R&D investment toward highest opportunity areas

---

## 📚 Additional Resources

- **Book**: "What Customers Want" by Anthony Ulwick
- **Training**: Outcome-Driven Innovation methodology courses
- **Templates**: See `templates/` directory for interview guides and survey instruments
- **Examples**: Review `02-teams/` directories for applied JTBD implementations

*"People don't want a quarter-inch drill. They want a quarter-inch hole." - Theodore Levitt*