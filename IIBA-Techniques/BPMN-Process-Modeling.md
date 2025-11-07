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
