# Claude Product OS Setup Guide

This guide helps you customize Claude Product OS for your organization's specific context and needs.

## 🎯 Before You Start

**Claude Product OS works best when adapted to your reality.** Don't try to use it exactly as provided - the power comes from tailoring the structure, processes, and content to your team's actual workflows and challenges.

## 📋 Setup Checklist

### Phase 1: Foundation (30 minutes)
- [ ] Install Claude agents from `agents/` directory
- [ ] Review and customize directory structure
- [ ] Replace placeholder company names with yours
- [ ] Set up your first team in `02-teams/`

### Phase 2: Customization (1-2 hours)  
- [ ] Adapt stakeholder profile templates
- [ ] Customize research methodologies for your domain
- [ ] Configure JTBD framework for your product area
- [ ] Set up documentation standards

### Phase 3: Team Onboarding (ongoing)
- [ ] Train team on directory navigation
- [ ] Establish documentation habits
- [ ] Create your first research protocols
- [ ] Begin stakeholder mapping

## 🔧 Step-by-Step Customization

### 1. Install Claude Agents

**Copy agents to your Claude Code configuration:**

```bash
# For project-specific agents (recommended)
cp agents/*.md .claude/agents/

# For user-level agents (available across all projects)
cp agents/*.md ~/.claude/agents/
```

**Verify installation:**
```bash
# In Claude Code
/agents
```

You should see the new product management agents listed.

### 2. Customize Directory Structure

**Option A: Keep Generic Structure**
- Use `team-alpha`, `team-beta` naming
- Good for cross-functional teams or consulting

**Option B: Adapt to Your Organization**
```bash
# Example: Rename teams by function
mv 02-teams/team-alpha 02-teams/engineering
mv 02-teams/team-beta 02-teams/design  
mv 02-teams/team-gamma 02-teams/product
```

**Option C: Domain-Specific Structure**
```bash
# Example: B2B SaaS company
mv 02-teams/team-alpha 02-teams/acquisition
mv 02-teams/team-beta 02-teams/activation
mv 02-teams/team-gamma 02-teams/retention
```

### 3. Replace Placeholder Content

**Find and replace these throughout the system:**

- `Mastercard` → Your company name
- `Debit` → Your main product  
- `[STAKEHOLDER_NAME]` → Actual stakeholder names
- `Global Debit` → Your team names
- `[DOMAIN_AREA]` → Your industry/domain

**Quick replacement command:**
```bash
# Replace company name throughout
find . -name "*.md" -exec sed -i '' 's/\[COMPANY_NAME\]/YourCompany/g' {} +
```

### 4. Set Up Your First Team

**Choose one team to start with:**

1. **Pick your most mature team** (easier to document existing processes)
2. **Navigate to** `02-teams/[team-name]/`
3. **Create your first research document** using templates
4. **Establish meeting note practices** in `01-project-management/meeting-notes/`

### 5. Customize Research Methodologies

**Adapt continuous discovery for your context:**

1. **Review** `06-process-frameworks/research-methodologies/`
2. **Modify interview protocols** for your user types
3. **Adjust research cadence** based on your sprint cycles
4. **Customize insight synthesis** for your stakeholder needs

### 6. Configure JTBD Framework

**Tailor Jobs-to-be-Done for your domain:**

1. **Study** `06-process-frameworks/jtbd-framework/`
2. **Identify your core customer jobs** using provided templates
3. **Map outcome statements** to your product metrics
4. **Create job story templates** for your development process

## 🏢 Industry-Specific Adaptations

### B2B SaaS
- Focus on activation, engagement, and retention workflows
- Emphasize stakeholder interviews for complex buying decisions
- Adapt JTBD for both end users and buyers

### E-commerce
- Prioritize conversion optimization and user journey mapping
- Create teams around acquisition, conversion, retention
- Focus on behavioral research and A/B testing frameworks

### Enterprise Software  
- Emphasize change management and stakeholder alignment
- Create extensive communication strategy templates
- Focus on adoption metrics and training processes

### Startups
- Simplify structure - combine teams if needed
- Focus heavily on validation frameworks
- Prioritize rapid iteration and learning documentation

### Agencies/Consulting
- Adapt for multiple client contexts
- Create reusable client research templates
- Focus on knowledge transfer and handoff processes

## 🎯 Methodology Selection

**Choose your primary approach based on maturity:**

### Early Stage (Pre-Product Market Fit)
- **Heavy focus on**: Validation frameworks, customer discovery
- **Primary agents**: Research expert, validation expert
- **Key processes**: JTBD interviews, assumption mapping

### Growth Stage (Scaling Product)
- **Heavy focus on**: Strategic planning, team coordination  
- **Primary agents**: Product strategy coach, communication optimizer
- **Key processes**: North star metrics, cross-team alignment

### Enterprise Stage (Optimization)
- **Heavy focus on**: Organizational transformation, process excellence
- **Primary agents**: All agents, with emphasis on stakeholder management
- **Key processes**: Empowered team principles, systematic optimization

## 🔄 Usage Patterns

### Daily Workflows
- **Morning**: Review todo lists and project status
- **Research sessions**: Use research methodology templates
- **Stakeholder meetings**: Apply communication strategy frameworks
- **Development planning**: Create JIRA tickets using outcome-focused agents

### Weekly Rhythms  
- **Team syncs**: Document insights using meeting templates
- **Strategy review**: Update north star metrics and roadmaps
- **Stakeholder updates**: Use communication optimization agents

### Monthly/Quarterly
- **Strategic planning**: Deep dive into competitive analysis
- **Process improvement**: Refine methodologies based on learnings
- **Team retrospectives**: Update cultural insights and communication strategies

## 🚨 Common Setup Mistakes

### ❌ Don't Do This
- **Copy everything exactly** - adapt to your context
- **Use all agents immediately** - start with 2-3 most relevant
- **Skip the customization phase** - generic content won't be useful
- **Treat it as rigid system** - evolve it based on what works

### ✅ Do This Instead  
- **Start small** with one team and core processes
- **Customize heavily** for your specific context
- **Focus on adoption** over completeness
- **Iterate based on real usage** and team feedback

## 🎓 Training Your Team

### Introduction Session (1 hour)
1. **Walk through directory structure** and navigation
2. **Demonstrate Claude agents** with real examples
3. **Practice using templates** for common tasks
4. **Establish documentation standards** and expectations

### Ongoing Learning (weekly)
- **Share methodology wins** from successful applications
- **Refine processes** based on team feedback
- **Add new templates** as needs emerge
- **Cross-pollinate insights** between teams

## 📈 Success Metrics

**Track adoption and impact:**

### Process Metrics
- Documentation consistency across teams
- Time from insight to action (research → development)
- Stakeholder meeting effectiveness
- Cross-team collaboration quality

### Outcome Metrics  
- Product decision confidence  
- User research velocity
- Strategic alignment across teams
- Team autonomy and empowerment levels

## 🔧 Advanced Configuration

### Custom Agents
Create specialized agents for your domain by:
1. **Studying existing agents** in `agents/` directory
2. **Identifying domain-specific needs** (e.g., compliance, security)
3. **Following agent creation patterns** in Claude Code documentation
4. **Testing with real workflows** before team deployment

### Integration Points
- **JIRA/Linear integration**: Use outcome-focused ticket templates
- **Slack/Teams**: Adopt communication frameworks for updates
- **Analytics tools**: Align metrics with north star framework
- **Design tools**: Integrate research insights into design processes

---

## 🚀 Ready to Start?

1. **Pick one team** as your pilot
2. **Install the research expert agent** first
3. **Conduct your first stakeholder interview** using provided templates
4. **Document the insights** using the framework structure

**Remember**: This system gets more valuable as you use and adapt it. Start imperfect, iterate quickly, and customize ruthlessly for your context.

## 📞 Need Help?

- **Review methodology docs** in `06-process-frameworks/`
- **Check template examples** throughout the system
- **Study successful patterns** from established frameworks
- **Adapt gradually** rather than implementing everything at once

---

*The goal isn't to use this system perfectly - it's to accelerate your team's ability to make evidence-based product decisions.*