# Use Case Specification Template
*IIBA BABOK Reference: Requirements Analysis and Design Definition*

## Use Case: [Use Case Name]
**Use Case ID**: UC-[Number]
**Version**: 1.0
**Last Updated**: [Date]

## 1. Use Case Overview
**Primary Actor**: [Main user/role initiating the use case]
**Secondary Actors**: [Other systems/roles involved]
**Description**: [Brief description of the use case purpose]
**Business Goal**: [What business objective this use case supports]

## 2. Trigger & Preconditions
**Trigger**: [Event that initiates the use case]
**Preconditions**: [System state required before use case begins]
- Condition 1: [e.g., User must be logged in]
- Condition 2: [e.g., Sufficient permissions available]

## 3. Postconditions
**Successful Completion**: [System state after successful execution]
- [e.g., Order is confirmed and inventory updated]
**Failed Completion**: [System state after failed execution]
- [e.g., Order is cancelled and user notified]

## 4. Main Success Scenario (Happy Path)
| Step | Actor Action | System Response |
|------|--------------|-----------------|
| 1 | [Actor action] | [System response] |
| 2 | [Actor action] | [System response] |
| 3 | [Actor action] | [System response] |

## 5. Alternative Flows
### Alternative Flow A: [Flow Name]
**Condition**: [When this alternative flow occurs]
| Step | Actor Action | System Response |
|------|--------------|-----------------|
| A1 | [Different action] | [Different response] |
| A2 | [Continue...] | [Continue...] |

### Alternative Flow B: [Flow Name]
**Condition**: [When this alternative flow occurs]
| Step | Actor Action | System Response |
|------|--------------|-----------------|
| B1 | [Different action] | [Different response] |

## 6. Exception Flows
### Exception 1: [Exception Condition]
**Handler**: [How the system handles this exception]
**Recovery**: [Steps to recover from exception]

### Exception 2: [Exception Condition]
**Handler**: [How the system handles this exception]
**Recovery**: [Steps to recover from exception]

## 7. Business Rules
| Rule ID | Rule Description | Applies To Steps |
|---------|------------------|-----------------|
| BR-001 | [Business rule description] | [Step numbers] |
| BR-002 | [Business rule description] | [Step numbers] |

## 8. Data Requirements
**Input Data**: [Data required from actor]
- Field 1: [Description, format, validation rules]
- Field 2: [Description, format, validation rules]

**Output Data**: [Data produced by system]
- Output 1: [Description, format]
- Output 2: [Description, format]

## 9. Non-Functional Requirements
**Performance**: [Response time requirements]
**Security**: [Access control and data protection]
**Usability**: [User experience considerations]
**Reliability**: [Availability and error handling]

## 10. Acceptance Criteria
- [ ] Criterion 1: [Measurable condition for acceptance]
- [ ] Criterion 2: [Measurable condition for acceptance]
- [ ] Criterion 3: [Measurable condition for acceptance]

## 11. Related Artifacts
**Wireframes/Mockups**: [Links to UI designs]
**Database Schema**: [Links to data models]
**API Specifications**: [Links to interface documents]

*IIBA Technique: Use Cases and Scenarios*
