# MoSCoW Prioritization Technique
*IIBA Technique: Prioritization*

## Methodology Overview

**M - MUST HAVE**
- Critical for current delivery timeframe
- Without these, solution won't work or will fail
- Maximum 60% of total requirements

**S - SHOULD HAVE**
- Important but not vital
- Could be delayed but would impact value
- 20-40% of total requirements

**C - COULD HAVE**
- Desirable but less important
- Can be easily left out without major impact
- 10-20% of total requirements

**W - WON'T HAVE**
- Not in current scope
- May be included in future phases
- Explicitly excluded to manage expectations

## Implementation Template

| Requirement ID | Description | MoSCoW | Business Value (1-10) | Effort (S/M/L) | Risk | Dependencies |
|---------------|-------------|--------|---------------------|----------------|------|--------------|
| REQ-001 | User authentication & login | MUST | 10 | M | Low | None |
| REQ-002 | Password reset functionality | MUST | 9 | S | Low | REQ-001 |
| REQ-003 | Advanced analytics dashboard | SHOULD | 8 | L | Medium | REQ-001 |
| REQ-004 | Custom report builder | COULD | 6 | L | High | REQ-003 |
| REQ-005 | Mobile app development | WON'T | 7 | XL | High | Future phase |

## Prioritization Workshop Guidelines

### Preparation
1. **Pre-workshop**: Distribute requirements list to stakeholders
2. **Criteria Definition**: Agree on scoring criteria for business value and effort
3. **Timebox**: Allocate 2-3 hours for the prioritization session

### During Workshop
1. **Individual Scoring**: Stakeholders score requirements independently
2. **Group Discussion**: Discuss discrepancies in scores
3. **Consensus Building**: Reach agreement on final prioritization
4. **Validation**: Ensure MUST requirements fit within constraints

### Rules for Application
1. **Timeboxing**: Must-haves must be deliverable within time constraints
2. **Collaboration**: Prioritization done with stakeholders, not for them
3. **Validation**: Regularly review and adjust priorities
4. **Communication**: Clear rationale for each prioritization decision

*IIBA Reference: BABOK Guide v3.0 - Prioritization Technique*
