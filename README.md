# The Treading Water Methodology
## Building Your Ship While Staying Afloat

## Overview
The Treading Water methodology acknowledges the reality of teams who must simultaneously maintain day-to-day operations while building something substantial. Like a team treading water while constructing a ship, this approach embraces resource constraints, shifting priorities, and the need to balance immediate survival with long-term success.

## Core Principles

1. **Practical Realism**: Acknowledge that teams must both "tread water" (handle maintenance and interruptions) and "build the ship" (develop new features/products)
2. **Sustainable Pace**: Ensure no team member treads water for too long, preventing burnout
3. **Deliberate Trade-offs**: Making and communicating explicit decisions about where to invest in quality vs. where to make pragmatic compromises to reach shore (go-live)
4. **Current Navigation**: Develop strategies to navigate unpredictable currents (shifting priorities, executive decisions, market changes) that can push the team off course

## Key Components

### 1. Dual Work Categorization
All work is explicitly categorized as either:
- **Treading Activities** (eg. 40%): Maintenance, bugs, support, emergencies, technical debt, code review, navigating currents (responding to shifting priorities)
- **Building Activities** (eg. 60%): New features, major refactors, planned improvements to facilitate ease or stability of features

### 2. The Blueprint
A visual representation of the product/project showing:
- Essential components (must-have features)
- Quality tier of each component (Gold, Standard, Minimum Viable, or Experimental)
- Current construction/completion status
- Distance to shore (time to launch/completion)

### 3. Work Status Board
A kanban-style board with columns:
- **Landed**: Completed work
- **Ready**: Ready to QA/review
- **In Construction**: Work in progress
- **Blueprint Stage**: Planned for near term
- **Conceptual Designs**: Acknowledged but not immediate
- **In the depths/Underwater**: Explicitly deprioritized

### 4. Daily Level Check
Brief standup focusing on:
- Who needs immediate help / drowning (treading assistance)
- Current strength assessment (identifying new currents)
- Critical building blockers
- Coordination on shared components

### 5. Construction Planning
Bi-weekly session to:
- Review treading vs. building capacity
- Assess impact of recent currents and adjust course
- Prioritize next construction components
- Make explicit quality/scope decisions
- Reassess distance to shore
- Review quality tier assignments as needed

### 6. Journey Log
Regular reporting showing:
- Progress on key ship components
- Quality compromises made
- Treading vs. building time ratio
- Current impact assessment (how much time/direction was affected by currents)
- Updated shore ETA (estimated time to arrival)

## Component Quality Tiering

### Quality Dimensions
Each component's quality requirements are defined across these key dimensions:
- Issue severity tolerance (P0-P4)
- Resolution timeframes (SLAs)
- Testing requirements
- Documentation standards

### Quality Tiers

1. **Gold Standard** (Tier 1)
   - Zero tolerance for P0-P2 issues at launch
   - P3-P4 issues limited to documented, non-impacting cases
   - P0-P1 issues: 4-hour resolution SLA
   - P2 issues: 24-hour resolution SLA
   - Comprehensive automated testing (90%+ coverage)
   - Complete technical and user documentation required

2. **Standard Quality** (Tier 2)
   - Zero tolerance for P0-P1 issues at launch
   - Limited P2 issues acceptable with mitigation plans
   - P0 issues: 8-hour resolution SLA
   - P1 issues: 24-hour resolution SLA
   - P2 issues: 3-day resolution SLA
   - Substantial automated testing (70%+ coverage)
   - Standard technical documentation required

3. **Minimum Viable** (Tier 3)
   - P0-P1 issues must have workarounds at launch
   - P2-P4 issues may remain unresolved at launch
   - P0 issues: 3-day resolution SLA
   - P1 issues: 2-week resolution SLA
   - Other issues: Best effort basis
   - Manual testing acceptable
   - Documentation can be deferred

4. **Experimental** (Tier 4)
   - Explicitly labeled as experimental/beta
   - All issue severities acceptable if they don't affect other components
   - Issues addressed on capacity-available basis
   - Basic exploratory testing only
   - Minimal or no documentation

### Quality Assignment Strategy
The methodology encourages teams to be strategic about quality tier assignments:
- **Gold Standard**: Reserve for revenue-critical or safety components only
- **Standard Quality**: Default for most customer-facing functionality
- **Minimum Viable**: Use for first iterations that will be improved later
- **Experimental**: Clearly marked as "use at your own risk" features

## Roles

### 1. Captain (Product Owner equivalent)
- Maintains the blueprint and prioritizes components
- Makes critical quality/scope decisions
- Navigates major currents with leadership
- Ensures the ship will reach shore

### 2. Life Guard (Scrum Master equivalent)
- Facilitates ceremonies and removes obstacles
- Ensures balance between treading and building
- Identifies currents early and helps the team adjust
- Protects team sustainability

### 3. Navigator (optional Technical Lead role)
- Advises on technical course adjustments
- Helps interpret organizational currents for the team

### 4. Crew Members (Development Team)
- Self-organize to balance treading and building work
- Signal when they're struggling to stay afloat
- Contribute to quality and scope decisions

## The Treading Water Manifesto

We are uncovering better ways of developing
software by doing it and helping others do it.
Through this work we have come to value:

**Survival while building over idealized processes**

**Honest scope compromises over unrealistic commitments**

**Strategic quality investments over uniform perfection**

**Sustainable team capacity over heroic efforts**

**Viable delivery over endless refinement**

That is, while there is value in the items on
the right, we value the items on the left more.

## Principles behind the Treading Water Manifesto

1. Our highest priority is to reach shore by delivering valuable software while keeping the team above water.

2. Welcome changing priorities and requirements, even late in development. Treading Water processes harness currents rather than resisting them.

3. Recognize strong currents early and respond with transparency about their impact on timelines and quality.

4. Deliver working software regularly, acknowledging that building a ship while treading water requires strategic compromises.

4. Business people and developers must work daily to make explicit decisions about immediate needs versus long-term building.

5. Build projects around motivated individuals. Give them the environment and support they need to stay afloat, and trust them to balance treading and building.

6. Maintain transparency about where quality and scope compromises are made to ensure the ship reaches shore.

7. Working software that meets current needs is the primary measure of progress, with the understanding that different components may have different quality levels.

8. Treading Water processes promote sustainable development. The sponsors, developers, and users should be able to maintain a constant pace indefinitely.

9. Continuous attention to technical excellence enhances agility, but perfect craftsmanship everywhere is not always possible or desirable.

10. Simplicity—maximizing the work not done—is essential for both staying afloat and building effectively.

11. The best architectures and designs emerge from self-organizing teams that understand both immediate and long-term needs.

12. At regular intervals, the team reflects on how to become more effective at balancing treading and building, then adjusts accordingly.

13. Recognize which ship components require higher quality and which can be simplified to reach shore faster.

14. Promote a culture where quality compromises are documented rather than hidden, enabling future improvements.

15. Balance short-term "staying afloat" with long-term "reaching shore" in all decisions.

16. Celebrate both treading accomplishments (stability) and building accomplishments (progress) with equal importance.

## Term Glossary

| Term | Meaning |
|------|---------|
| Treading Activities | Maintenance, support, and other work to keep current systems running |
| Building Activities | Development of new features and capabilities |
| Ship | The product or solution being built |
| Shore | The goal (go-live, launch, delivery milestone) |
| Blueprint | Product roadmap and requirements |
| Currents | External forces that shift direction (changing priorities, market conditions) |
| Rip Current | Particularly strong current (major priority shift, executive decisions) |
| Below Waterline | Explicitly deprioritized items |
| Quality Tier | Defined quality standard for components (Gold, Standard, Minimum Viable, Experimental) |
| Quality Compromise | Documented technical debt or scope reduction |

## When to Use This Methodology

- Teams with significant maintenance burden alongside new development
- Projects with high uncertainty and changing priorities
- Organizations with frequent "currents" from executive decisions (build/buy shifts, strategic pivots)
- Organizations with resource constraints but ambitious goals
- Startups and teams building MVP (Minimum Viable Product) solutions
- Recovery situations requiring both stability and forward progress
