# Linear Usage Manual for Product Teams

*Comprehensive guide for outcome-driven project management using Linear*

## 🎯 Overview

Linear is designed to help product teams move fast, stay organized, and work efficiently by reducing organizational friction and enabling rapid execution through prescriptive workflows. The philosophy: "Think the Linear way, and you'll naturally organize work in ways that scale."

### Core Benefits for Product Teams
- **Outcome-focused tracking**: Connect daily work to business objectives
- **Cross-functional visibility**: Enable collaboration between product, design, and engineering
- **Evidence-based prioritization**: Link issues to customer insights and business impact
- **Minimal friction workflows**: Reduce administrative overhead to maximize building time

## 📋 Linear for Product Management

### Issue Hierarchy for Product Work
```
Epic (Business Outcome)
├── Story (User Value)
│   ├── Task (Implementation Step)
│   └── Bug (Quality Issue)
└── Research (Discovery Activity)
    ├── Interview Tasks
    └── Analysis Work
```

### Product-Focused Issue Types

#### **Epic**: Major product initiatives
- **Purpose**: Track large business outcomes across quarters
- **Example**: "Increase user activation rate by 25% in Q2"
- **Contains**: Multiple stories, research issues, and supporting tasks

#### **Story**: User value deliverables  
- **Purpose**: Deliver specific user or business value
- **Format**: "As a [user], I need [capability] so that [outcome]"
- **Contains**: Implementation tasks and related research

#### **Research**: Discovery activities
- **Purpose**: Reduce product risk through customer insight
- **Examples**: User interviews, usability tests, competitive analysis
- **Outcome**: Insights that inform product decisions

#### **Task**: Implementation work
- **Purpose**: Specific development, design, or operational work
- **Examples**: API development, design mockups, deployment tasks
- **Parent**: Always belongs to a story or epic

## 🔄 Product Development Workflow

### Issue Status Flow for Product Teams

#### **Discovery Phase**
- **Idea** → Initial concept or customer request
- **Researching** → Active discovery work (interviews, analysis)
- **Defined** → Requirements clarified, ready for design/development

#### **Delivery Phase**  
- **Design** → User experience and interface design
- **Ready** → Fully specified, ready for development
- **In Progress** → Active development work
- **Review** → Code review, testing, stakeholder approval
- **Done** → Delivered to users

### Product Planning Cycle

#### Weekly Discovery (Mondays)
1. **Review customer feedback** and usage data
2. **Identify research questions** for upcoming decisions  
3. **Create research issues** for discovery activities
4. **Plan customer interactions** for the week

#### Mid-Week Development (Tuesday-Thursday)
1. **Execute research activities** (interviews, tests, analysis)
2. **Refine requirements** based on customer insights
3. **Progress development work** on defined stories  
4. **Conduct stakeholder reviews** and gather feedback

#### Weekly Planning (Fridays)
1. **Synthesize research insights** from customer interactions
2. **Update story requirements** based on new evidence
3. **Prioritize next week's work** using impact/effort matrix
4. **Plan upcoming research** for following week

## 📊 Outcome-Driven Issue Management

### Issue Creation Best Practices

#### Epic Creation Template
```
Epic Title: [Business Outcome] - [Success Metric]
Description:
**Business Objective**: What business goal does this support?
**Success Criteria**: How will we measure success? 
**Customer Impact**: What customer problem does this solve?
**Timeline**: Expected completion timeframe
**Dependencies**: What must happen first?

**Research Questions**:
- [ ] Question 1 requiring customer validation
- [ ] Question 2 about technical feasibility  
- [ ] Question 3 about market opportunity

**Stories** (will be created as research validates direction):
- Story concept 1 (pending validation)
- Story concept 2 (pending validation)
```

#### Story Creation Template  
```
Story Title: [User] can [action] to [outcome]
Description:
**User Job**: What is the user trying to accomplish?
**Current Pain**: What's frustrating about the existing experience?
**Proposed Solution**: How will we address the user need?
**Success Metrics**: How will we measure improvement?

**Acceptance Criteria**:
- [ ] Functional requirement 1
- [ ] Functional requirement 2  
- [ ] Performance requirement
- [ ] Quality requirement

**Research Evidence**:
- Link to customer interviews supporting this need
- Usage data showing current pain points
- Competitive analysis informing solution approach
```

#### Research Issue Template
```
Research Title: [Research Question] - [Method]
Description:
**Hypothesis**: What do we believe is true?
**Research Question**: What specifically do we need to learn?
**Method**: How will we gather evidence?
**Participants**: Who can best inform this question?
**Timeline**: When do we need results for decision making?

**Success Criteria**:
- [ ] Clear answer to research question
- [ ] Evidence to support or reject hypothesis
- [ ] Insights documented and shared with team
- [ ] Product decisions updated based on findings
```

### Prioritization Framework

#### Impact/Effort Matrix in Linear
Use custom fields to track:
- **Customer Impact**: 1-5 scale based on research evidence
- **Business Impact**: 1-5 scale tied to company objectives  
- **Implementation Effort**: Story points or t-shirt sizing
- **Research Confidence**: How certain are we about customer need?

#### Priority Scoring Formula
`Priority Score = (Customer Impact + Business Impact) / Implementation Effort × Research Confidence`

## 🎯 Customer-Centric Labels and Organization

### Label System for Product Teams

#### **Customer Segment Labels**
- `segment:new-users` - Issues affecting user onboarding
- `segment:power-users` - Features for highly engaged customers
- `segment:enterprise` - Enterprise customer needs
- `segment:free-tier` - Free user experience improvements

#### **Product Area Labels**
- `area:acquisition` - New user growth and conversion
- `area:activation` - First-value user experience  
- `area:engagement` - Ongoing product usage
- `area:retention` - Preventing user churn

#### **Research Type Labels**
- `research:customer-interview` - Direct user feedback
- `research:usability-test` - User experience validation
- `research:data-analysis` - Behavioral insight research
- `research:competitive` - Market and competitor analysis

#### **Decision Impact Labels**  
- `impact:strategy` - Affects product direction
- `impact:design` - Influences user experience decisions
- `impact:tech-architecture` - Technical implementation choices
- `impact:go-to-market` - Marketing and sales implications

## 🚀 Cross-Functional Collaboration Patterns

### Product-Design-Engineering Sync

#### Daily Standups (15 minutes)
- **Product**: Share customer insights and priority changes
- **Design**: Update on user experience decisions and research needs
- **Engineering**: Communicate technical constraints and implementation progress

#### Weekly Planning (60 minutes)  
- **Review completed research** and customer feedback
- **Validate story requirements** with new evidence
- **Estimate and prioritize** upcoming work
- **Identify dependencies** and collaboration needs

#### Sprint Reviews (45 minutes)
- **Demo delivered value** to stakeholders  
- **Share customer impact metrics** and usage data
- **Review research insights** that inform next iteration
- **Plan discovery activities** for upcoming work

### Stakeholder Communication Through Linear

#### Executive Updates
Create filtered views showing:
- **Strategic initiatives** (epics) and their progress
- **Customer impact metrics** from delivered features
- **Research insights** affecting product direction  
- **Resource allocation** across product areas

#### Customer Success Integration
- Tag customer feedback with relevant issue links
- Create issues for feature requests with customer context
- Track customer impact metrics for delivered features
- Share research insights that affect customer experience

## 📈 Metrics and Reporting

### Product Team Dashboard Views

#### **Discovery Health**
- Active research issues by type and timeline
- Customer interaction frequency and quality
- Research questions answered vs. product decisions made
- Time from insight to action on product direction

#### **Delivery Progress**
- Stories delivered vs. planned by customer segment  
- Business impact metrics for completed work
- Cycle time from story creation to user value delivery
- Quality metrics (bugs, customer satisfaction scores)

#### **Outcome Tracking**
- Epic progress toward business objectives
- Customer segment health and engagement metrics  
- Product-market fit indicators and trend analysis
- Research-driven vs. assumption-driven product decisions

### Key Performance Indicators

#### **Discovery Effectiveness**
- **Research Velocity**: Customer touchpoints per week
- **Insight Quality**: Research findings that change product decisions
- **Customer Centricity**: % of stories supported by customer evidence

#### **Product Delivery** 
- **Value Delivery**: Business metrics improved by delivered features
- **User Adoption**: Feature usage rates and customer feedback scores
- **Development Efficiency**: Story completion rate and quality metrics

## ⚠️ Common Product Team Pitfalls in Linear

### ❌ Anti-Patterns to Avoid

#### **Feature Factory Patterns**
- Creating stories without customer evidence or business justification
- Skipping discovery research to "move faster" on development
- Measuring success by features shipped rather than customer outcomes

#### **Process Over Outcomes**
- Over-engineering Linear workflows instead of focusing on customer value
- Creating excessive issue types and statuses that slow down work
- Spending more time organizing Linear than talking to customers

#### **Assumption-Driven Development**  
- Building features based on internal opinions rather than customer evidence
- Skipping validation research for "obvious" customer needs
- Prioritizing based on stakeholder requests rather than customer impact

### ✅ Product Excellence Patterns

#### **Customer-Driven Discovery**
- Every story includes links to supporting customer research
- Regular customer interviews inform ongoing product decisions
- Product roadmap adapts based on evidence rather than predetermined plans

#### **Outcome-Focused Planning**
- Issues clearly connect to business objectives and customer value
- Success metrics defined before development begins  
- Progress measured by customer and business impact, not just story completion

#### **Evidence-Based Prioritization**
- Priority decisions documented with supporting research and data
- Customer segment impact considered in all planning decisions
- Resource allocation optimized for learning and customer value delivery

## 🛠️ Advanced Linear Configuration for Product Teams

### Custom Fields for Product Management
- **Customer Evidence**: Links to research supporting the issue
- **Business Impact**: Expected effect on key company metrics
- **User Segment**: Primary customer group affected by the work
- **Research Confidence**: How certain we are about customer need (1-5)

### Automated Workflows  
- **Research → Story**: Automatically create implementation stories from validated research
- **Customer Feedback → Issue**: Convert support requests into product issues
- **Story Completion → Metrics**: Update customer impact tracking when stories ship

### Integration Points
- **Customer Feedback Tools**: Sync support tickets and user feedback
- **Analytics Platforms**: Pull usage data to inform prioritization
- **Research Tools**: Connect interview insights to relevant product issues
- **Design Systems**: Link design decisions to customer research evidence

---

## 🎓 Success Checklist for Product Teams

### Weekly Habits  
- [ ] **Customer Contact**: Direct customer interaction every week
- [ ] **Evidence Collection**: Research insights documented and linked to product decisions
- [ ] **Progress Review**: Business impact measured and reported for completed work
- [ ] **Priority Validation**: Upcoming work prioritized based on customer and business evidence

### Monthly Assessment
- [ ] **Outcome Delivery**: Measurable progress on business objectives through product improvements  
- [ ] **Customer Centricity**: Product decisions consistently supported by customer evidence
- [ ] **Team Alignment**: Cross-functional clarity on priorities and customer impact
- [ ] **Process Evolution**: Linear workflows optimized based on team effectiveness and customer value delivery

---

## 📚 Additional Resources

- **Linear Method**: Product development philosophy and best practices
- **Continuous Discovery**: Teresa Torres methodology for ongoing customer research  
- **Jobs-to-be-Done**: Customer-centric approach to product strategy
- **Outcome-Driven Development**: Marty Cagan's empowered product team principles

*"The goal is not to ship features. The goal is to solve customer problems in ways that drive business results." - Product Team Mantra*