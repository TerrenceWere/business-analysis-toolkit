# BPMN Process Modeling Technique
*IIBA Technique: Process Modeling*

## BPMN Notation Overview
Business Process Model and Notation (BPMN) is a standard for business process modeling that provides a graphical notation for specifying business processes.

## Core BPMN Elements

### 1. Flow Objects
**Events** (Circles)
- ⚪ **Start Event**: Process trigger
- ⚫ **End Event**: Process conclusion
- 🟢 **Intermediate Event**: Something that happens during process

**Activities** (Rounded Rectangles)
- **Task**: Single unit of work
- **Sub-process**: Collapsible activity group
- **Transaction**: Group with special behavior

**Gateways** (Diamonds)
- **Exclusive (XOR)**: One path only
- **Parallel (AND)**: All paths
- **Inclusive (OR)**: One or more paths
- **Event-based**: Decision based on events

### 2. Connecting Objects
**Sequence Flows** (Solid lines with arrowhead)
- Show order of activities

**Message Flows** (Dashed lines with open arrowhead)
- Show communication between participants

**Associations** (Dotted lines)
- Link artifacts to flow objects

### 3. Swimlanes
**Pools** 
- Represent major participants

**Lanes**
- Sub-divisions within pools

### 4. Artifacts
**Data Objects**
- Show what data is used

**Groups**
- Show logical grouping

**Annotations**
- Provide additional information

## Process Modeling Template

### AS-IS Process Model
```bpmn
[Start] → [Current Activity 1] → [Gateway?] → [Activity 2] → [End]
TO-BE Process Model
bpmn
[Start] → [Improved Activity 1] → [Automated Task] → [End]
Modeling Guidelines
Best Practices
Start Simple: Begin with high-level process maps

Consistent Level: Maintain same detail level in single diagram

Clear Labels: Use verb-noun format for activities

Minimize Crossings: Arrange to avoid crossing lines

Swimlane Logic: Group by roles, not departments

Common Patterns
Approval Process
text
[Submit Request] → [Manager Review] → {Approved?} 
    → Yes → [Process Request] → [End]
    → No → [Notify Requester] → [End]
Error Handling
text
[Process Order] → [Error?] 
    → Yes → [Log Error] → [Manual Review] → [Resume]
    → No → [Continue Processing]
Example: Order Fulfillment Process
AS-IS Process
Pool: Customer Service

Start → [Receive Order] → [Manual Data Entry] → [Check Inventory]

Pool: Warehouse

[Pick Items] → [Pack Order] → [Ship Order] → End

TO-BE Process
Pool: Customer Service

Start → [Receive Order] → [System Validates] → [Auto-Confirm]

Pool: Warehouse

[Auto-Pick List] → [Scan Items] → [Auto-Ship] → End

Validation Checklist
All start events have triggers defined

All end events represent process completion

Gateways have clear decision criteria

Swimlanes represent actual organizational roles

Process has measurable outcomes

Exception paths are modeled

Data objects show information flow

IIBA Reference: BABOK Guide - Process Modeling
