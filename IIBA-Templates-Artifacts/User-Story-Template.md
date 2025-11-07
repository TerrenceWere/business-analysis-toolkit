# User Story Template
*IIBA Technique: User Stories*

## User Story Structure

### Basic Template
**As a** [type of user]  
**I want** [some goal]  
**So that** [some reason/value]

### Enhanced Template (INVEST Criteria)
**Independent** - Story can be delivered independently  
**Negotiable** - Details can be discussed and refined  
**Valuable** - Delivers tangible value to users  
**Estimable** - Team can estimate effort required  
**Small** - Can be completed in one iteration  
**Testable** - Clear acceptance criteria exist

## User Story Components

### 1. Story Card (Front)
Story ID: US-[Number]
Title: [Descriptive Story Name]

As a [User Role]
I want to [Action/Feature]
So that [Business Value/Benefit]

Acceptance Criteria:

[Criterion 1]

[Criterion 2]

[Criterion 3]

Story Points: [Estimate]
Priority: [High/Medium/Low]

text

### 2. Conversation (Back)
**Discussion Notes:**
- [Key decisions made during refinement]
- [Technical considerations]
- [Dependencies identified]
- [Open questions]

**Assumptions:**
- [Assumption 1]
- [Assumption 2]

**Constraints:**
- [Constraint 1]
- [Constraint 2]

## Acceptance Criteria Formats

### Given-When-Then Format
Scenario: [Scenario Description]
Given [initial context]
When [event occurs]
Then [expected outcome]

text

### Checklist Format
- [ ] [Specific condition that must be met]
- [ ] [Another condition for completion]
- [ ] [Edge case handling]

## User Story Examples

### Example 1: E-commerce Feature
Story ID: US-101
Title: Quick product search

As a online shopper
I want to search for products by name
So that I can quickly find what I'm looking for

Acceptance Criteria:

Search returns results in under 2 seconds

Results show product name, image, and price

No results displays helpful message

Special characters don't break search

Story Points: 3
Priority: High

text

### Example 2: Reporting Feature
Story ID: US-102
Title: Export sales report

As a sales manager
I want to export monthly sales data to Excel
So that I can perform additional analysis

Acceptance Criteria:

Export includes: date, product, quantity, revenue

Excel file downloads immediately when clicked

Data formatting matches template requirements

Large exports (>10,000 rows) show progress indicator

Story Points: 5
Priority: Medium

text

## User Story Slicing Techniques

### Horizontal Slicing (By Layer)
- **UI Layer**: Basic interface without logic
- **Business Logic**: Core functionality without UI polish  
- **Data Layer**: Backend without frontend integration

### Vertical Slicing (By Feature)
- **Minimum Viable Feature**: Smallest useful implementation
- **Enhanced Features**: Additional capabilities
- **Edge Cases**: Error handling and special scenarios

### Example: Login Feature Slicing
**Slice 1**: Basic username/password login  
**Slice 2**: "Remember me" functionality  
**Slice 3**: Password reset feature  
**Slice 4**: Two-factor authentication

## Definition of Ready (DoR)
- [ ] User role clearly defined
- [ ] Business value understood
- [ ] Acceptance criteria defined
- [ ] Dependencies identified
- [ ] Technical feasibility confirmed
- [ ] Size estimated by team
- [ ] UX/UI requirements clarified

## Definition of Done (DoD)
- [ ] Code completed and reviewed
- [ ] Unit tests written and passing
- [ ] Integration tests passing
- [ ] Acceptance criteria met
- [ ] Product Owner acceptance
- [ ] Documentation updated
- [ ] Deployed to test environment

## Story Mapping Template

### User Activities (Top Level)
1. Account Management
2. Product Browsing  
3. Order Processing
4. Customer Support

### User Tasks (Middle Level)
- Account Management
  - Register account
  - Login
  - Update profile
  - Reset password

### User Stories (Detailed Level)
- Register account
  - US-001: Basic registration with email
  - US-002: Email verification
  - US-003: Social media registration

*IIBA Technique: User Stories, Backlog Management*
